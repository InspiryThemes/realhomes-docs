# User Roles Management

!!! info "Important"

    Ensure **User Registration** is set up and activated for this feature to function properly.

### **User, Agent, Agency Synchronization**

The **User Roles** feature allows seamless synchronization between user profiles and their respective Agent or Agency profiles, providing a range of roles including Agent, Agency, Owner, Developer, Buyer, and Seller.

To enable this feature, go to **Dashboard → Easy Real Estate → Settings → Users → User Role Management**.

Once enabled, the system will automatically create a new Agent or Agency profile for each newly registered user, depending on their selected role. Any profile updates by the user will be synchronized with the associated Agent or Agency details.

**Available options:**<br>

**Enable User Synchronization:** Easily toggle user synchronization with Agent/Agency profiles to streamline profile updates.

**Avatar Fallback:** If user profile images are not available, avatars can automatically fall back to Agent/Agency profile images for a unified visual experience.

**Control Auto-Assignment:** Allows admins to prevent auto-assignment of users to Agent roles if the synchronization feature is disabled.

**Enable/Disable Specific Roles:** Choose which roles (e.g., Agent, Agency, Owner, Buyer, Developer, Seller) to enable or disable within your system.

This ensures that profile information remains consistent across all roles, making property and agency management more efficient.

=== "v4.5.1 and Later"

    !!! success "RealHomes Settings"
        <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">RealHomes</span> ➤ <span class="nav-step">Settings</span> ➤ <span class="nav-step">User Management</span> ➤ <span class="nav-step">User Roles</span>

    ![User Role Synchronization](images/ere-tabs/user-roles-settings.png)

=== "v4.5.0 and Earlier"

    !!! info "Legacy Settings"
        <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">Easy Real Estate</span> ➤ <span class="nav-step">Settings</span> ➤ <span class="nav-step">Users</span> ➤ <span class="nav-step">User Role Management</span>

    ![User Role Synchronization](images/dashboard/user-roles-agent-agency-sync.png)

---

### **Custom User Roles**

RealHomes allows you to add and manage custom user roles directly from the settings panel. This is particularly useful if your business requires specific roles such as Manager, Staff, or Coordinator alongside the default ones.

To add custom roles, go to **Dashboard → RealHomes → Settings → User Management → Access Management** (or **Dashboard → Easy Real Estate → Settings → Users → User Role Management** for legacy versions).

In the **Custom User Roles** field, simply enter a comma-separated list of the custom roles you wish to add (e.g., `manager, staff, coordinator`).

![Custom User Roles](images/ere-tabs/add-user-role-in-realhomes.gif)

!!! note "Important"
    After adding the custom roles, make sure to **save the settings and refresh the page**. The newly added roles will then appear in the **Enable/Disable User Roles** section and the **User Role Access Management** tabs, allowing you to configure their permissions just like any other role.

---

### **User Role Access Management**

This feature gives you granular control over access permissions for various user roles within WordPress and RealHomes, such as Agent, Agency, Owner, Buyer, Seller, Developer, and more.

You can allow or deny access to specific functionalities for each user role by navigating to **Dashboard → Easy Real Estate → Settings → Users → User Role Management**.

Key access options include:

- **Manage Profile:** Enable/disable the ability to manage user profiles.

- **Select/Change Agency:** Control whether users can select or change their agency.

- **Manage Listings:** Allow/deny access to create, edit, or delete property listings.

- **Save/Manage Favorites:** Control the ability to save favorite properties.

- **Submit Listings:** Decide whether users can submit, edit, and delete property listings.

- **Manage Agents:** Allow management of agents.

- **Manage Agencies:** Allow users with this role to manage agencies.

- **Check Invoices:** Enable/disable access to check current invoices for users with specific roles.

- **Manage Reservations:** Control access to manage reservations.

- **Property Analytics:** Control access to property performance analytics.

This flexible access management system helps streamline roles and responsibilities, allowing you to tailor permissions according to each user's role.

=== "v4.5.1 and Later"

    !!! success "RealHomes Settings"
        <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">RealHomes</span> ➤ <span class="nav-step">Settings</span> ➤ <span class="nav-step">User Management</span> ➤ <span class="nav-step">Access Management</span>

    ![User Role Access Management](images/ere-tabs/access-management-settings.png)

=== "v4.5.0 and Earlier"

    !!! info "Legacy Settings"
        <span class="nav-step">Dashboard</span> ➤ <span class="nav-step">Easy Real Estate</span> ➤ <span class="nav-step">Settings</span> ➤ <span class="nav-step">Users</span> ➤ <span class="nav-step">User Role Management</span>

    ![User Role Access Management](images/easy-real-estate/user-role-access-management.png)
