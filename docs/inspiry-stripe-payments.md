# Individual Property Payments Via Stripe

To enable Stripe payments for individual properties, install and configure the [Inspiry Stripe Payments for RealHomes](https://wordpress.org/plugins/inspiry-stripe-payments/) plugin.

!!!important "Prerequisite"
	Before starting, ensure the **RealHomes theme** and its **Easy Real Estate plugin** are installed and activated.

## Install & Activate 'Inspiry Stripe Payments for RealHomes' Plugin

1. Navigate to **Dashboard → Plugins → Add New** and search for **Inspiry Stripe Payments**. 
	
	![Install Inspiry Stripe Payments Plugin](images/other-features/search-inspiry-stripe-payments.png)

2. **Install** and **Activate** the plugin.

## Configure Plugin Settings

1. Navigate to the Stripe settings page based on your version:

=== "v4.5.1 and Later"

    !!! success "RealHomes Settings"
        <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">RealHomes</span> ➤ <span class="nav-step">Settings</span> ➤ <span class="nav-step">Stripe Settings</span>

=== "v4.5.0 and Earlier"

    !!! info "Legacy Settings"
        <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">Easy Real Estate</span> ➤ <span class="nav-step">Stripe Settings</span>

    ![Stripe Settings](images/other-features/inspiry-stripe-payments-settings.png)

This page contains the following settings:

	- Enable/Disable Stripe Payments.
	- Stripe Account API Keys.
	- Currency Code.
	- Payment Amount Per Property.
	- Payment Button Label.
	- Publish Submitted Property after Payment.

2. Configure all settings. For help retrieving your **Publishable Key** and **Secret Key**, refer to [Retrieving the Stripe API Keys](https://inspirythemes.com/realhomes-memberships-setup/#retrieving-stripe-api-keys).

6. Once done, visit the *My Properties* page to view the Stripe payment button.

	![My Properties Payment Buttons](images/other-features/my-properties-payment-buttons.png)

!!!note
	In case of any issue, you can signup/login to our [support website](https://support.inspirythemes.com/login-register/) and [ask your question](https://support.inspirythemes.com/ask-question/).
