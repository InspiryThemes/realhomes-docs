## Configure Property Search in Ultra Design

Before starting with this section, Make sure you have pretty permalinks enabled from **Dashboard → Settings → Permalinks** and Property Search Page is created.

## Create Property Search Page

Create a new page "**Property Search**" Using **Property Search Template** ( In case of Imported XML this page is already created ). 
Other search templates with sidebar support are also available to use.

!!! Warning
    Make sure that the slug of this page should not be "**yourwebsite.com/search/**" because that will conflict with internal WordPress search and create issues for your website.

![Create Property Search Page](images/home-setup/create-search-page-gutenberg.png)

![Property Search Template Selection](images/create-pages/properties-search-template.png)

## Setup Search Page in Theme Settings

After the creation of search page, you must set it up as search results page by assigning the newly created search page in **Select Search Page** option. Navigate based on your version:

=== "v4.5.1 and Later"

    !!! success "RealHomes Settings"
        <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">RealHomes</span> ➤ <span class="nav-step">Settings</span> ➤ <span class="nav-step">Property Search</span> ➤ <span class="nav-step">Search Page</span>

    ![Setup Search Page in Customizer](images/ultra/properties-search-page-customizer-ultra-v4.5.1.png)

=== "v4.5.0 and Earlier"

    !!! info "Legacy Settings"
        <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">RealHomes</span> ➤ <span class="nav-step">Customize Settings</span> ➤ <span class="nav-step">Properties Search</span> ➤ <span class="nav-step">Properties Search Page</span>

    ![Setup Search Page in Customizer](images/ultra/properties-search-page-customizer-ultra.png)