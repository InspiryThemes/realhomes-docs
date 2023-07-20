# WPML Basic Setup

> Before proceeding, make sure you have purchased the **WPML Multilingual CMS package** and have a working version of WordPress with the RealHomes Theme installed and configured based on the provided documentation and sample data within the theme package.

Please follow the steps below to configure the basic settings for the WPML Plugin.

## Installation & Activation

Install and activate the **WPML Multilingual CMS Plugin**.
![RealHomes Documentation](images/wpml/wpml-cms.png)

## Initial Setup

Upon activation, you will see a notice at the top to configure WPML if this is your first time activating it. Click on **Configure WPML**.
![RealHomes Documentation](images/wpml/configure-wpml.png)

## Languages Setup

Next, add the languages of your choice that you want to use for your website's translation.
![RealHomes Documentation](images/wpml/WPML-step-1.png)

## Configure Site's URL

On the next step, select "**Different languages in directories**" to configure the **site's URL** for multilingual content.
![RealHomes Documentation](images/wpml/WPML-step-2.png)

## Verify WPML License

In order to verify the license of WPML and receive regular plugin updates, please add the Site Key provided by WPML.
![RealHomes Documentation](images/wpml/WPML-step-3.png)

## Translators Settings

Configure the settings about who will be translating the content. Select "Only myself" if you plan to add all the translations manually.
![RealHomes Documentation](images/wpml/WPML-step-4.png)

## Share Usage Data with WPML

The next step allows you to choose whether you want to share data with WPML officials for future support and improvements.
![RealHomes Documentation](images/wpml/WPML-step-5.png)

## Install String Translation Plugin

The 6th step in the onboarding process is crucial. Select "String Translation" to install the string translation plugin, as it enables the String Translation feature of WPML.
![RealHomes Documentation](images/wpml/WPML-step-6.png)

## Finish the Onboarding Process

Click "Finish" to complete the onboarding process and the initial setup of the WPML Translation plugin.
![RealHomes Documentation](images/wpml/WPML-step-7.png)

## Make Themes Work Multilingual

Search for **Make themes work multilingual** and disable this option.
![RealHomes Documentation](images/wpml/adjust-ids.gif)

## Theme & Plugin Localization

Go to **Dashboard → WPML → Theme and Plugin Localization**. Under **Localization options**, choose **Automatically load the theme's .mo file using 'load_textdomain'**, and type **framework** in the **Enter textdomain** field below, then click **Save**.
![RealHomes Documentation](images/wpml/load_translation_domain_framework.gif)

## Scan the Theme and Plugins

Navigate to the **Strings in the Theme** section, press the **Scan the theme for Strings** button, and wait for the results.
![RealHomes Documentation](images/wpml/string-in-theme.png)

## Track Strings Appearance

Go to **Dashboard → WPML → String Translation** section and configure the following settings.
![RealHomes Documentation](images/wpml/track-strings.png)

## Disable WPML Advance (side-by-side) Translation Editor

In **Dashboard → WPML → Settings**, scroll down until you find "**How to translate posts and pages**" and set it to **Use WPML's Classic Translation Editor** as shown below.
![RealHomes Documentation](images/wpml/wpml-classic-editor.png)

## Start Translating the Strings

With the basic settings complete, you can now translate any string that does not exist in the posts, pages, and taxonomies via the **Dashboard → WPML → String Translation** section. For more information, consult the [WPML String Translation Documentation](https://wpml.org/documentation/getting-started-guide/string-translation/).

## WPML Language Switcher Settings

Once the basic setup is complete, you can proceed to set up the **[WPML Language Switcher](https://realhomes.io/documentation/wpml-language-switcher/)**.

By following these steps, you'll have the WPML Plugin configured and ready to manage multilingual content on your RealHomes WordPress theme website.