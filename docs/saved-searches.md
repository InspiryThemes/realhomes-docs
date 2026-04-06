# Saved Searches

## Setup Saved Searches Feature

Enabling this feature will display a **Save Search** button at the top of search results. It will also add a **Saved Searches** menu item to the user menu.

Navigate based on your version of the **RealHomes** theme:

=== "v4.5.1 and Later"

    !!! success "RealHomes Settings"
        <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">RealHomes</span> ➤ <span class="nav-step">Settings</span> ➤ <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">Saved Searches</span>

    ![RealHomes Documentation](images/member-pages/saved-searches-settings.png)

=== "v4.5.0 and Earlier"

    !!! info "Legacy Settings"
        <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">RealHomes</span> ➤ <span class="nav-step">Customize Settings</span> ➤ <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">Saved Searches</span>

    ![RealHomes Documentation](images/member-pages/saved-searches-setting-1.png)

    ![RealHomes Documentation](images/member-pages/saved-searches-setting-2.jpg)

    ![RealHomes Documentation](images/member-pages/saved-searches-setting-3.jpg)

**Modern**

![RealHomes Documentation](images/member-pages/save-search-modern.jpg)

**Classic**

![RealHomes Documentation](images/member-pages/save-search-classic.jpg)

## How Save Search Feature Works

- Any visiter can save searched criteria by clicking on the **Save Search** button.
- If user is not logged-in, then the saved searches will be stored to the browser’s local storage.
- If user is logged-in, then the saved searches will be stored in the database as user meta.
- Any saved searches that are stored to the local storage before logging-in will be migrated autometically to the logged-in user meta in the database.
- User will receive email notifications for the latest properties matching their saved searches criteria.
- The saved searches can be accessed through the **Saved Searches** dashaboard page, where user can view or delete them.

![RealHomes Documentation](images/member-pages/save-search-dashboard.jpg)

## How an Administrator can see All the Saved Searches by the Users

The website administrators can see all the saved searches of the users in the **User Dashboard** in "**All Users Saved Searches**" page.

![RealHomes - All Users Saved Searches](images/member-pages/all-users-saved-searches.png)