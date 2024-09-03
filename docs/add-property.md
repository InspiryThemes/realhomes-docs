# Add Property

To add a new property, go to **Dashboard → Easy Real Estate → New Property**

### **Add _Property Title_ and _Property Description_**

![Property Title & Description](images/add-content/title-and-description.png)

### **Add Basic Information**

Add basic information about the property, e.g., price, area, beds, baths, garages, etc.

![Property Basic Information](images/add-content/basic-info.png)

### **Add Additional Information**

You can add any additional information as key-value pairs.

![Property Additional Information](images/add-content/additional-information.png)

### **Add Vacation Rentals Information**

If you are using the **RealHomes Vacation Rentals** plugin and have [configured](vacation-rentals-setup.md) it, you can see the **Vacation Rentals** tab at the top. There, you can add pricing and other property rental information. For more details, check out the guide on adding a property with [vacation rental information here](add-property-vr.md).

![Vacation Rentals](images/add-content/vacation-rentals.png)

### **iCalendar Synchronization**

To stay up to date and avoid double bookings when your properties are listed on third-party websites, you can synchronize the booking calendar with third-party calendar services.

#### **Step 1: Add iCalendar Feed Page**

Before syncing the properties' calendar dates, you need to create an *iCalendar feed* page using the **iCalendar Feed** template, as shown below.

![iCalendar Feed](images/add-content/add-icalendar-page.png)

#### **Step 2: Syncing Your Booking Calendar to Third-Party Calendars**

Once you have created the iCalendar feed page, you will see the booking calendar feed export URL at the very bottom of the *Vacation Rentals* property meta-box tab (as shown below). Copy the **Feed URL** and add it to the third-party iCalendar import field as per their settings.

![iCalendar Import & Export](images/add-content/icalendar-import-export.png)

#### **Step 3: Syncing Your Booking Calendar from Third-Party Calendars**

To sync third-party booking calendars with your booking calendar, copy the iCalendar feed URL from their website. After that, add the feed URL to the *iCalendar Import* section (as shown below). Set a name for reference in the **Feed Name** field and enter the feed URL in the **Feed URL** field. You can add multiple feed URLs to sync from.

![iCalendar Import & Export](images/add-content/icalendar-import-export.png)

### **Mark Property as Featured**

If you want to add this property to featured properties, mark it as **Featured**.

![Mark Property as Featured](images/add-content/mark-featured.png)

### **Provide Location on Google Map**

Enter the property address and drag the Google map pointer to the correct location.

![Property Map](images/add-content/property-map.png)

### **Add Gallery Images**

Provide images for the property gallery.

**Ultra**

![Property Gallery - Ultra](images/add-content/property-gallery-ultra.png)

> **Note:** Images should have a minimum size of 1240px by 720px. Larger images will be cropped automatically. A minimum of 2 images are required to display the gallery.

**Modern**

![Property Gallery - Modern](images/add-content/property-gallery3.png)

> **Note:** Images should have a minimum size of 1240px by 720px. Larger images will be cropped automatically. A minimum of 2 images are required to display the gallery.

**Classic**

![Property Gallery - Classic](images/add-content/property-gallery2.png)

> **Note:** Images should have a minimum size of 1170px by 648px for thumbnails on the right and 830px by 460px for thumbnails on the bottom. Larger images will be cropped automatically. A minimum of 2 images are required to display the gallery.

### **Add Floor Plans**

Provide floor plan details. The **Floor Plan Image** and the **Floor Name** are the two essential details you must add, or the floor section will not show on the property details page.

![Property Floor Plans](images/add-content/floor-plans.png)

### **Add Featured Image**

You must set a featured image for the property. This featured image will be displayed in property cards on listing pages throughout the website.

**Classic:**  
The featured image in **Classic Design** should have a minimum width of **770 pixels** and a minimum height of **386 pixels**.

**Modern:**  
The featured image in **Modern Design** should have a minimum width of **680 pixels** and a minimum height of **510 pixels**.

![Property Featured Image](images/add-content/featured-image-updated.png)

### **Add Video Tour and Virtual Tour**

If your property has a virtual tour video, it is recommended to upload the video on Vimeo or YouTube and provide its URL here, along with a related screenshot or property photo.

Property Photo is essential because if no property photo is assigned to the video, it will not be shown. You can add multiple virtual tour videos by clicking the **+ Add more** button.

> You can also add a 360 Virtual Tour of your property using an iframe tag. For example, the following code will add a 360 virtual tour from matterport.com to your property.

`<iframe src="https://my.matterport.com/show/?m=aSx1MpRRqif&play=1" width="100%" height="100%" allowvr="" allowfullscreen="allowfullscreen"></iframe>`

You can also use the [iPanorama 360 WordPress Virtual Tour Builder](https://wordpress.org/plugins/ipanorama-360-virtual-tour-builder-lite/) plugin to build custom virtual tours and then put the property-related `iPanorama` short-code in the **360 Virtual Tour** box.

![Property Video](images/add-content/property-video.png)

### **Assign Agent Information**

Choose the information you want to display in the Agent's Information section.

![Property Agent](images/add-content/property-agent-info.png)

> **Difference Between Author Profile Information and Agent's Information**

> From the visitor's point of view, there is no difference, and information for an agent and author will be displayed similarly.

> From the website admin's point of view, an author is a site user/member who logs in to the website and adds a property using the admin side (if their role is the author or above) OR adds a property from the front end property submission page (if their role is a subscriber). An agent is a custom post type. Any user with a role equal to or above the author role can add those agents to the database and assign properties to those agents later. So, it is a flexible feature that can be used to suit your needs.

1. **None** will hide the agent's information box.
2. **Author profile information** will display the Author (user who added the property) information. You can configure your user information from the edit profile page (check the related documentation section for details of setting up the front-end profile edit page).  
If you have adequate rights, you can also modify the author from the Author meta box on the property edit page.  
![Property Author](images/add-content/property-author.png)
3. **Display agent's information** will display the selected agent's information. You can add the agent from **Dashboard → Agents → Add New**.

### **Energy Performance**

You can add a property **Energy Performance Certificate** details in this section. This information will display with a visual energy class graphic.

![Property Energy Performance](images/add-content/energy-performance.png)

### **Schedule a Tour**

You can easily showcase the **Schedule A Tour** section on the property details page by activating this feature.

![Schedule a Tour - Property Details Page](images/single-property-page/schedule-a-tour.png)

### **Misc Settings**

#### **Mark Property as Sticky**

If you want to make this property stick to the top on the home page and listing pages, mark it as **Sticky**.

![Mark Property as Sticky](images/single-property-page/sticky-property.png)

#### **Property Label Text & Background Color**

You can apply a custom banner or label to each property card for the listing pages and other sections using **Property Label Text & Background Color**.

![Property Label Text & Background Color](images/single-property-page/property-label-text-background-color.png)

#### **Attachments**

Using the Attachments feature, you can upload important property attachments, documents, etc., to each property.

![Property Attachments](images/single-property-page/upload-property-attachments.png)

#### **Owner Information & Private Note**

Property owner information and a private note can only be used for internal information purposes. It is not displayed anywhere throughout the website.

![Property Owner Information & Private Note](images/single-property-page/property-owner-information.png)

#### **Message to the Reviewer**

This area contains a message from the property submitter for the property reviewer or website administrator. It is not displayed anywhere for the public.

![Message to the Reviewer](images/single-property-page/message-to-the-reviewer.png)

### **Add Property in Homepage Slider**

If you want to add this property to the homepage slider, check the related option and provide a slide image.

![Add Property to Homepage Slider](images/add-content/add-property-to-home-page-slider.png)

### **Add Top Banner**

##### **Classic**

You can override the default banner set in Customizer settings by adding a new banner for a specific property in the below settings.

![Top Banner Settings - Classic](images/add-content/top-banner-property-settings.png)

##### **Modern**

Along with banner settings, you can also hide the advanced search form in the header on a single property page.

![Top Banner Settings - Modern](images/add-content/top-banner-property-settings-modern.png)

!!! info "More information about **Banner Settings** can be found here: "
    [**Configure Banner Settings**](https://support.inspirythemes.com/knowledgebase/how-to-configure-the-banner-settings/)

### **Custom Header & Footer**

You can also apply a unique custom header and footer to any property by selecting it from **Custom Header** or **Custom Footer** settings.

![Custom Header & Footer](images/add-content/custom-header-footer-single-property.png)

!!! info "Custom Header & Footer"
    You can create your own Custom Header or Footer using Elementor (free version) with RealHomes. You can consult [this section of the documentation](https://realhomes.io/documentation/custom-header-footer-elementor/) to learn how.

### **Add/Select Property Features**

You can choose or add **Property Features** from the related meta-box displayed below.

![Property Features](images/add-content/property-features-updated.png)

You can also add an icon to each property feature. This icon will appear on the property details page before the property feature. To add an icon to a feature, follow these steps:

1. Go to **Dashboard → RealHomes → Property Features**.
2. Create a new property feature or select an existing one.  
3. Upload your icon using the Property Feature Icon option.

![Add Property Features](images/add-content/property-add-features.png)

The icon will now display on the property details page in place of the default theme icons.

!!! note
    Recommended image size for an icon is 64px by 64px.

### **Add/Assign Property Types**

You can choose or add **Property Types** from the related meta-box displayed below.

![Property Types](images/add-content/property-types-updated.png)

### **Add/Assign Property Locations**

You can choose or add **Property Locations** from the related meta-box displayed below.

![Property Locations](images/add-content/property-cities-updated.png)

### **Add/Assign Property Statuses**

You can choose or add **Property Statuses** from the related meta-box displayed below.

![Property Status](images/add-content/property-status-updated.png)

### **Assign Parent Property**

If this property is a sub/child property of another property, you can select the **Parent Property** from the related meta-box displayed below.

![Property Attributes](images/add-content/property-attributes.png)

### **Property Page Layout**

If you want to make the single property page full width, you can change the **Page Template** from **Templates** to **Property Full Width**. For **Classic Editor**, select the same template from **Page Attributes**.

![Property Page Layout](images/add-content/select-single-property-template.gif)

### **RealHomes Misc Settings**

Miscellaneous settings are available for the single property page, which you can use to change the custom header, footer, sidebar, or other single property attributes.

![Property Misc Settings](images/add-content/misc-settings-add-property.gif)

**Publish the property once it is ready**.
