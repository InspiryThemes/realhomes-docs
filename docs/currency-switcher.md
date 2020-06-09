# How to set up Currency Switcher

To enable Currency Switching feature in RealHomes theme you would need to install and configure the [RealHomes Currency Switcher](https://wordpress.org/plugins/realhomes-currency-switcher/) plugin. Plesae follow the steps given blow.

!!!important "Prerequisite"
	Before you start following the Social Login setup guide, please make sure the **RealHomes theme** and its **Easy Real Estate plugin** are installed and activated on your site.

## Install & Activate 'RealHomes Currency Switcher' Plugin

1. Navigate to **Dashboard → Plugins → Add New** and search for **RealHomes Currency Switcher** as displayed in the screenshot below: 
	
	![Install RealHomes Currency Switcher Plugin](images/other-features/search-realhomes-currency-switcher.png)

2. Once found, **Install** and **Activate** the plugin.

## Configure Plugin Settings

Navigate to **Dashboard → Easy Real Estate → Currencies Settings** page. This page contains the following settings.
	
- Enable/Disable Currency Switcher
- Open Exchange App ID
- Update Interval
- Base Currency
- Allowed Currencies
- Expiry Period of Switched Currency
- Update Currencies Rates

![Currencies Settings](images/other-features/realhomes-currency-switcher-settings.png)

Configure all the settings as per your preferences. You can get your Open Exchange Rate **App ID** from [here](https://support.openexchangerates.org/article/121-your-app-id).

!!!note
	In case of any issue, you can signup/login to our [support website](https://support.inspirythemes.com/login-register/) and [ask your question](https://support.inspirythemes.com/ask-question/) over there.

## The End!

We will use [WP Currencies plugin](https://wordpress.org/plugins/wp-currencies/) to add currency switcher. If you are unable to install it via Dashboard Plugin then you can directly download it from [here](https://github.com/unfulvio/wp-currencies/archive/1.4.6.zip).

Install the [WP Currencies plugin](https://wordpress.org/plugins/wp-currencies/). As guided in screen shot below. 

![RealHomes Documentation](images/other-features/wp-currency-plugin-search.png)

After installing and activating the plugin. 

Go to **Dashboard → Settings → Currencies**. You need to sign up and get a free api key for your site from https://openexchangerates.org/signup/free. 

Provide the **API key** and save the changes. 

![RealHomes Documentation](images/other-features/wp-currencies-settings.png)

Now you need to navigate to **Dashboard → Real Homes → Customize Settings → Floating Features** panel. This panel contains **Currency Switcher** section ( which only appears if related plugin is installed ) There you can configure related settings.

![RealHomes Documentation](images/other-features/floating-features-currency-switcher.png)

![RealHomes Documentation](images/other-features/currency-switcher-settings.png)

Configure base currency and target currencies.

!!! note
    If you find base currency dropdown empty then simply wait for few minutes and refresh your settings page. As this could be due to the late completion of first time data fetch request from openexchangerates.org. In case of any problem reach us on our support site.

After making all the above settings, Visit your site's front end and you will have a currency switcher floating on the right side of your site. As displayed in screenshot below.

![RealHomes Documentation](images/other-features/currency-switcher-frontend.png)

Use it and you will find that prices are being displayed in your selected currency.
