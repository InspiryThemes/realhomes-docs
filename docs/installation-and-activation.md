# Installation

Before installation, you must make sure that your hosting environment/server must meet the [requirements of WordPress](https://wordpress.org/about/requirements/). RealHomes doesn't require any specific setup, and it will work perfectly fine on a hosting account (shared, reseller, or dedicated) that meets WordPress requirements.

To start, you must have a working version of WordPress. Almost all primary web hosts provide one-click WordPress install, and you can consult your host's help site for more information in this regard. For manual installation, you can consult [WordPress Official Installation guide](https://wordpress.org/support/article/how-to-install-wordpress/).

Once you have a working version of WordPress, You need to download "**All Files and Documentation**" from the ThemeForest download page (screenshot below) and extract the downloaded zip to get the required files, including **realhomes.zip**.
![Screenshot](images/installation/download-rh-full-package.png)

### **Install Theme Via WordPress Dashboard ( _Recommended_ )**

#### **Upload realhomes.zip & Activate**

Go to **Appearance → Themes** section and click **Add New**
![Screenshot](images/installation/add-new.png)

Click **Upload Theme**
![Screenshot](images/installation/upload-theme.png)

Choose the **realhomes.zip** file and press **Install Now**
![Screenshot](images/installation/realhomes-zip.png)

Once the theme is uploaded, then you need to activate it.

#### **Select Design Variation**

![Screenshot](images/installation/activate-theme.png)

After theme activation, you will be redirected to the RealHomes welcome page. Here you select your desired design variation and click the **Save Changes** button. 
![Screenshot](images/installation/welcome-page.png)
For more details please check [Design Selection](design-selection.md) page.

#### **Activate Your License**

- Also, a notice will be displayed at the top of the welcome page asking you to **Enter Item Purchase Code** and then click on the **Verify** button. RealHomes purchase verification allows you to **install plugins, import demo contents**, and avail **auto-updates**. For help to retrieve RealHomes purchase code, you can follow our knowledge base article on [How to Get Themeforest Item Purchase Code](https://support.inspirythemes.com/knowledgebase/how-to-get-themeforest-item-purchase-code/) 
![Screenshot](images/installation/purchase-verification.png)

#### **Required Plugin Installation & Activation**

- After **RealHomes Purchase Verification**, a notice will be displayed at the top asking you to install and activate the required plugins. So, go ahead and click on **Begin installing plugins**.<br>
![Screenshot](images/installation/begin-plugin-installation.png)
- On the next page, you will see the list of plugins to install. Please select all the plugins and click on **Install** and then click on **Apply** to install all of them at once (as shown in the screenshot below). </br>
![Screenshot](images/installation/install-plugins.png)
- After all the plugins are installed, click on **Return** to **Required Plugins Installer**. <br>
![Screenshot](images/installation/return-to-install.png)
- Once again, select all the plugins and click on **Activate** and then click on **Apply** to activate all the plugins and you are done. <br>
![Screenshot](images/installation/activate-plugins.png)

#### **Update Permalinks Settings**

Go to **Dashboard → Settings → Permalinks** and choose **Post name** from **Common Settings** and save the changes, As displayed in the screenshot below.
![Screenshot](images/import-demo/permalinks.png)

#### **Initial Elementor Settings**

Navigate to **Dashboard → Elementor → Settings** and make sure **Disable Default Colors** and **Disable Default Fonts** are enabled.
![Screenshot](images/elementor/disable-default-colors-fonts-elementor.png)

If you face any problem during upload through the dashboard, please upload the theme using FTP as guided below.

### **Alternative Installation Method**
#### **Install Theme Via FTP**

1. Access your hosting server using an FTP client like **FileZilla**
2. Go to the '**wp-content → themes**' folder of your WordPress installation
3. Extract the **realhomes.zip** file and put the realhomes folder in '**wp-content → themes**' folder
4. Go to '**Dashboard → Appearance → Themes**' section to activate the theme
5. Go to **Dashboard → Settings → Permalinks** and choose **Post name** from **Common Settings** and save the changes.
6. After activation, go to "**Dashboard → Real Homes → Customize Settings**" to play with the theme's settings.

#### **Install Child Theme ( Highly Recommended )**

It is highly recommended to use a child theme if you are going to customize the parent theme's code. A pre-built ready-to-use child theme is included in the main theme pack that you have downloaded from ThemeForest.


To install the child theme, You need to upload the **realhomes-child.zip** and activate it just like a standard WordPress Theme.

### **Common Installation Issues**

All the following issues/errors are either user-created or server-side problems.

!!! error "**Theme is missing the style.css stylesheet error**"
    This issue occurs if you upload the rh-main-package.zip file. Check out this guide: https://help.market.envato.com/hc/en-us/articles/202821510-Theme-is-missing-the-style-css-stylesheet-error

!!! error "**The link you followed has expired**"
    This error happens if your hosting server is not configured with proper PHP parameters, you can find the solution in this guide: https://support.inspirythemes.com/knowledgebase/how-to-fix-the-link-you-followed-has-expired-in-wordpress/

!!! error "**Broken / Missing CSS Styles**"
    This problem only occurs if the theme directory doesn't have appropriate permissions. Learn how you can fix it in this article: https://support.inspirythemes.com/knowledgebase/how-to-fix-broken-styles-after-installing-or-updating-the-theme/

!!! error "**Missing temporary directory**"
    You might also face this problem on some rare hosting servers if WordPress is not installed correctly, so we have a solution in this quick guide: https://support.inspirythemes.com/knowledgebase/destination-directory-for-file-streaming-does-not-exist-or-is-not-writable/

If you face any other problem that is not listed above, then [create a ticket](https://support.inspirythemes.com/ask-question/) at our support platform by [signing up](https://support.inspirythemes.com/login-register/) and we will assist you as soon as possible.