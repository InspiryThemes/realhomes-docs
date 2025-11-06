# **Mega Menu Setup**

This guide explains how to enable the mega menu feature, create or import a template, and assign it to a menu item. 

!!! info "Prerequisite"
    Please note: The Mega Menu feature is only available for the **Modern** and **Ultra** design variations.

---

### Step 1: Enable the Mega Menu Feature

Before you can assign a template, you must globally enable the mega menu feature.

1.  Go to **Dashboard → Appearance → Customize**.
2.  Navigate to the **Header → Basics** section.
3.  Find the **Mega Menu** setting and select **Enable**.
4.  **Publish** your changes.

![Enable Mega Menu feature in Customizer](images/elementor/enable-mega-menu.png)

---

### Step 2: Get a Mega Menu Template

You must have an Elementor template saved in your library. You can either import our pre-built templates or create your own from scratch.

#### Option A: Import Pre-built Templates (Recommended)

1.  Locate the main theme package `**rh-main-package.zip**` and extract it.
2.  Navigate to the `rh-main-package/Elementor Templates/19 - Mega Menus/` folder to find the template JSON files.
    ![Location of Mega Menu JSON files](images/elementor/mega-menu-json.png)
3.  In your WordPress dashboard, go to **Templates → Saved Templates**.
4.  Click the **Import Templates** button at the top of the page.
5.  Select the JSON file you want to use and click **Import Now**.

The template is now in your library and ready to be assigned.

#### Option B: Create Your Own Template

You can design a completely custom mega menu using the Elementor editor.

1.  Go to **Dashboard → Templates → Add New**.
2.  Select a template type (e.g., **"Page"** or **"Section"**).
3.  Give your template a descriptive name (e.g., "Custom Properties Menu").
4.  Click **Create Template**.
5.  Design your layout using the Elementor editor. Add columns, images, listing carousels, or any other widgets you need.
6.  When finished, click **Publish** (or **Update**).

Your new custom template is now saved in the library.

---

### Step 3: Assign the Template to a Menu Item

Finally, assign your imported or created template to a top-level item in your navigation menu.

1.  Go to **Dashboard → Appearance → Menus**.
2.  Ensure you have the correct menu selected (e.g., "Main Menu").
3.  Click the small arrow on a top-level menu item to expand its options.
4.  Find the **"Select Elementor Mega Menu Template"** dropdown.
5.  Choose the template you imported or created in Step 2.
6.  Click **Save Menu** to apply the changes.

![Assigning an Elementor template in WordPress Menus](images/elementor/assign-mega-menu-template.png)