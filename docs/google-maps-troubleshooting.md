# **Google Maps Troubleshooting**

### **How to Troubleshoot Google Maps**

The easiest way to inspect issues related to Google Maps is to open the console being on the page where the Google Map is not working. Follow the steps below.

**1.** Open the page where Google Maps is displaying some issue.
**2.** Once the page is loaded, open the **Console**. You can open it by using the shortcut keys which is **CMD + Option + J** on **Mac** and **CTRL + Shift + J** on **Windows**.
**3.** In the console, you can find the warnings in **RED** about Google Map problem. For example, if it says **RefererNotAllowedMapError** it means the URLs you have added in the setup process are wrong. To learn about any error, you can visit the relevant page of Google: https://developers.google.com/maps/documentation/javascript/error-messages

### **RefererNotAllowedMapError in Console**

If you see **RefererNotAllowedMapError** in the console it means the URLs you have added in the **Credentials** section of your Google Maps API Project are wrong. Repeat the **5th Step** in the setup explained here: https://realhomes.io/documentation/google-maps-setup/

### **Find Address is not working**

One of the most common issues is the **Find Address** section in the **Property Edit** page on backend **Dashboard**. It will not work if you have not activated the **Geocoding API Services** for your Google Maps Project which you created to get **Google Maps API Key**. So, you can find it in **APIs** section and **Enable** it for the project.

### **Any Other Issues**

If you experience any other problem which is not explained in the Documentation then drop a ticket at our [support website](https://support.inspirythemes.com/) and our support team will assist you in every possible manner.