# Server Caching & RealHomes

If you are using a cache plugin like **LiteSpeed Cache**, **WP Rocket**, or any other caching tool, you may encounter issues with interactive features like **AJAX Login**, **Registration**, **Add to Favorites**, or **Property Submissions**. 

This is usually because these features rely on security tokens called **Nonces** (number used once). By default, WordPress nonces expire every 12-24 hours. If your cache plugin saves a page with a nonce and serves that cached page *after* the nonce has expired, the form validation will fail and the request will be rejected.

To ensure RealHomes works perfectly with your cache plugin, you need to tell the caching system which security tokens should remain dynamic and never be cached.

---

## LiteSpeed Cache Configuration (Highly Recommended)

If you are using **LiteSpeed Cache**, the best way to handle nonces is by using the **ESI (Edge Side Includes)** feature. This allows the theme to privately serve fresh security tokens dynamically, even on pages that are otherwise fully public and cached.

1.  Navigate to **LiteSpeed Cache → Cache → [5] ESI**.
2.  Enable **Enable ESI** if it is not enabled already.
3.  Find the text box labeled **ESI Nonces**.
4.  Copy the following list of RealHomes nonces (one per line) and paste it into that box:

```text
inspiry-ajax-login-nonce
inspiry-ajax-register-nonce
inspiry-ajax-forgot-nonce
ere_inline_otp_nonce
ere_social_login_nonce
add_to_favorite_nonce
favorites_nonce
fav_share_nonce
compare_share_nonce
similar_property_nonce
inspiry_save_search
saved_searches_nonce
agency_search_nonce
agent_search_nonce
send_message_nonce
agent_message_nonce
schedule_a_tour_nonce
rvr_booking_request
realhomes_report_property_form_nonce
send_cfos_message_nonce
submit_property
submit_agent_agency
update_user
inspiry_allow_upload
dashboard_analytics_nonce
rh_unit_switcher_nonce
```

5.  Click **Save Changes**.

---

### Fixing Google reCAPTCHA Issues with LiteSpeed

If you use Google reCAPTCHA and see errors like *"reCAPTCHA Failed: The response parameter is missing,"* you should exclude reCAPTCHA scripts from being combined, minified, or deferred by the caching plugin.

1.  Navigate to **LiteSpeed Cache → Page Optimization → Tuning**.
2.  Find the **JS Excludes** option.
3.  Add the following lines:

```text
https://www.google.com/recaptcha/api.js
grecaptcha
loadInspiryReCAPTCHA
```

4.  Click **Save Changes** and purge your cache.

---

## General Advice for Other Cache Plugins (WP Rocket, Autoptimize, etc.)

If your cache plugin does not support ESI (like WP Rocket), it cannot serve dynamic tokens inside a cached page. To prevent nonces from expiring and breaking forms, you should follow these rules:

### 1. Exclude Dynamic Pages
Avoid caching the following pages entirely:

*   **Login & Register Page**
*   **User Dashboard Pages** (My Properties, Profile, Submissions, Favorites)
*   **Submit Property Page**

### 2. Adjust Cache Lifespan
For interactive features on other public pages (like the "Favorite" or "Compare" buttons appearing on property cards), you should set your **Cache Lifespan** to **less than 12 hours** (ideally 10 hours). 

Because WordPress nonces expire every 12 to 24 hours naturally, purging the cache every 10 hours guarantees that your visitors will never be served a stale security token.
