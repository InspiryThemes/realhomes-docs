# How to get Google Maps API Key for your website

### **Login & Select Maps**

Please go to [**Google API Console**](https://cloud.google.com/maps-platform/#get-started). and login with your google account. Once logged in it will display a popup so pick Maps from it.
![Google Maps Setup](images/google-maps/pick-maps-popup.png)

### **Select a New or Existing Project**

Create a new project or select an existing project then click on **Continue** to enable the **API** and any related services.
![RealHomes Documentation](images/google-maps/create-or-existing.png)

### **Activate Billing for your Account**

On the next step you have to create a billing profile. You can consult the [**Official Guide of Google**](https://developers.google.com/maps/billing/gmp-billing) to learn how you can activate billing for you account.

### **Enable Maps Javascript API & Geocoding API**

After creating the billing profile navigate to the Console and click on **APIs** from the right navigation.
![RealHomes Documentation](images/google-maps/google-maps-apis.png)

On this new page, click on **Maps Javascript API** and **Enable** it. Now go back to the **APIs** page and click on **Geocoding API** and **Enable** it as well. This is also needed to make the **Find Address** field work properly on **Property Edit Page**. 
![RealHomes Documentation](images/google-maps/enable-geocoding-api.gif)

### **Restrict the API Key to your Domain Only**

After activating both **APIs** in the previous step now click on the **Navigation Menu** and select **APIs & Services** and click on **Credentials**.

In this section, you will see the name of your **API Key** (so click on it) and restrict it by adding your site URLs (in 3 formats: yourdomain.com, *.yourdomain.com and *.yourdomain.com/*) as shown in the screencast below.
![RealHomes Documentation](images/google-maps/apis-and-services-http-referrers.gif)

!!! warning "Important"
    If you don't restrict the Google Maps API Key then anyone can use it on his website because the API Key is exposed in the code. So, you must restrict the API Key to your domain only.

### **Copy the API Key and Add it**

Copy the generated **Google Maps API key** from the popup. Click on **Close** button to proceed after you copied the **API Key**. 
![RealHomes Documentation](images/google-maps/api-key.png)

Put this **API Key** you just copied in **Maps** Settings (**Easy Real Estate → Settings → Maps → Google Maps API Key**).
![RealHomes Documentation](images/google-maps/google-maps-ere.png)

### **Default Location for Maps on Single Property & Property Listing Pages**

In this **Maps** settings tab, you can also provide the default location for *New Property Map* and *Properties Listing Map* (when there is no property to display).

!!! info "Important Information"
    If you are running the RealHomes Theme older than {==3.9.0==} version then related settings can be found by navigating to **Dashboard → RealHomes → Customize Settings → Map**

**Verify Domain with Google**: [https://support.google.com/webmasters/answer/35179](https://support.google.com/webmasters/answer/35179)

### **How to Change Google Map Type**

The Google Map Type can be changed in **Dashboard → RealHomes → Customize Settings → Properties Templates & Archives → Google Map Type**.

![RealHomes Documentation](images/google-maps/change-google-map-type.png)