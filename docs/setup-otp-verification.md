# OTP Verification Setup

RealHomes provides built-in support for **OTP (One-Time Password)** verification. This feature significantly enhances security by requiring users to enter a code sent to their registered email before they can complete the login process. It protects against automated brute force attacks and tightens overall user identity verification.

**How it Works:**  
- For the standard login process, the OTP verification is completely seamless and occurs directly within the login modal.  
- If you use **Social Login** (like Google or Facebook), you must create a dedicated OTP page to handle the verification since social login operates outside of the modal.

## 1. Enabling and Configuring OTP

The core functional settings for OTP Verification are conveniently located within the Easy Real Estate plugin settings.

1. Navigate to **Easy Real Estate → Settings → Social** in your WordPress dashboard.
2. Scroll to the bottom of the page to find the OTP settings.
3. **Enable OTP for Login:** Turn this toggle **ON**. When enabled, users will receive a one-time password via email upon successfully entering their standard login credentials.
4. **OTP Max Login Attempts:** Input the maximum number of times a user can attempt to enter an incorrect OTP. This helps prevent brute force attacks.
5. **OTP Duration (Minutes):** Define the validity lifespan (in minutes) for the generated OTP code before it automatically expires. *(Maximum allowed is 10 minutes)*.
6. Make sure to click the **Save Changes** button.

Once you enable these settings, OTP Verification will start working fully within the standard RealHomes login modal out of the box.

## 2. Creating an OTP Page (Required for Social Login)

If you are using the Social Login feature on your website, you must create a dedicated page where users connecting with social networks will be redirected to enter their one-time passwords.

1. Navigate to **Pages → Add New** in your WordPress dashboard.
2. Give the page a title, such as **OTP Verification**.
3. Within the page editor settings, under **Page Attributes**, select **OTP Verification** from the **Template** dropdown.
4. Click **Publish** to make the page live.
5. *Important Note:* Ensure your site's permalinks are configured to **Post name** under **Settings → Permalinks** for the OTP page to process correctly.

## 3. Configuring OTP Settings in Customizer (For Social Login)

After creating the OTP template page, you must assign it in your customizer settings so the social login flow knows where to redirect users.

1. Go to **Appearance → Customize** from your WordPress dashboard.
2. Navigate to **Header → Login & Register**.
3. Locate the **Select OTP Page** dropdown option. *(Note: This option displays when any OTP or social login functionality is enabled).*
4. Select the **OTP Verification** page you created in the previous step.
5. Click **Publish** to save your selection.
