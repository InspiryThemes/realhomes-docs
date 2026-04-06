# Setup Registration

## Allow Registration

To allow user registration, you need to check the **Anyone can register** option from **Dashboard → Settings → General** page and *Save Changes* as displayed in the following screenshot. Otherwise only Login form will be available for the users.

![Anyone can register](images/member-pages/anyone_can_register.gif)

## Restrict Backend Access

You must restrict backend access of the user level which you have setup in the previous setup. Navigate based on your version of the **RealHomes** theme:

=== "v4.5.1 and Later"

    !!! success "RealHomes Settings"
        <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">RealHomes</span> ➤ <span class="nav-step">Settings</span> ➤ <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">Basic</span>

=== "v4.5.0 and Earlier"

    !!! info "Legacy Settings"
        <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">RealHomes</span> ➤ <span class="nav-step">Customize Settings</span> ➤ <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">Basic</span>

    ![Login & Register Page Title](images/member-pages/restrict-backend-access.png)

## Create Login & Register Page (Optional)

!!! note
    If you have imported demo contents then Login & Register page might already be created. But you still need to configure related settings as guided near the end of this section.

To add Login & Register page, Go to **Dashboard → Pages → Add New**

Provide the page title

![Login & Register Page Title](images/member-pages/login-register-page-title-gutenberg.png)

Select the **Login & Register** template from page attributes.
 
![Login & Register Template](images/member-pages/login-register-template.png)

Provide the top banner related information 

**Classic**
![Login & Register Banner Area Settings](images/create-pages/banner-spacing-classic.png)

**Modern**
![Login & Register Banner Area Settings](images/create-pages/modern-banner-spacing-full.png)

**Ultra**
![Login & Register Banner Area Settings](images/create-pages/ultra-banner-spacing-full.png)

!!!info "More information about **Banner Settings** can be found here: "
    **https://support.inspirythemes.com/knowledgebase/how-to-configure-the-banner-settings/**

Publish the page once it is ready.

## Configure Settings

Now you need to configure the created page in your theme settings. Navigate based on your version:

=== "v4.5.1 and Later"

    !!! success "RealHomes Settings"
        <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">RealHomes</span> ➤ <span class="nav-step">Settings</span> ➤ <span class="nav-step">Headers</span> ➤ <span class="nav-step">Login & Register</span>

=== "v4.5.0 and Earlier"

    !!! info "Legacy Settings"
        <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">RealHomes</span> ➤ <span class="nav-step">Customize Settings</span> ➤ <span class="nav-step">Header</span> ➤ <span class="nav-step">Login & Register Basics</span>

    Now select the **Login Or Register** page that has been created earlier as shown in image below.

    ![Login & Register Customizer Settings](images/member-pages/customizer-login-modal-1.jpg)

Publish the settings and your **Login & Register** page is ready for use.