# RH: Search Form Widget

The **RH: Search Form** widget provides a powerful and highly customizable property search form for your website. It allows you to control the layout, fields, and styling of the form extensively.

---

### Content Tab

#### Basic Settings

##### Select Search Template
- **Description:** If no search template is selected, the settings from `RealHomes > Customize Settings > Property Search > Properties Search Page` will be used.
- **Default Value:** None

##### Top Fields To Display
- **Description:** Select the number of fields to display in the top bar before they collapse into the "Advanced Search" section.
- **Default Value:** `3`

##### Advance Fields Default State
- **Description:** Choose whether the advanced fields section should be open or collapsed by default.
- **Default Value:** `Collapsed`

##### Show Labels
- **Description:** If enabled, labels will be displayed above each search field.
- **Default Value:** `No`

##### Show Advance Fields Button
- **Description:** Toggles the visibility of the "Advanced Search" button.
- **Default Value:** `Yes`

##### Show Search Buttons At Top
- **Description:** If enabled, the main search and advanced search buttons will appear at the top, next to the fields.
- **Default Value:** `No`

##### Advance Fields Button Text
- **Description:** The text for the button that expands the advanced search fields.
- **Default Value:** `Advance Search`

##### Search Button Text
- **Description:** The text for the main property search button.
- **Default Value:** `Search`

##### Show More Features
- **Description:** Toggles the visibility of the property features/amenities section.
- **Default Value:** `Yes`

##### More Features Styles
- **Description:** Choose how the property features are displayed.
- **Default Value:** `Select`

##### More Features Text
- **Description:** The text for the button that reveals the property features.
- **Default Value:** `Looking for certain features`

##### More Features Button Alignment
- **Description:** Aligns the "More Features" button to the left, right, or center.
- **Default Value:** `Flex Start`

##### Show Fields Separator
- **Description:** Toggles the vertical line separator between search fields.
- **Default Value:** `Yes`

#### Search Fields Sorting

##### Control Name
- **Description:** Allows you to drag and drop to reorder the search fields that appear in the form.
- **Default Value:** N/A

#### Property Locations

##### Enable Radius Location Search
- **Description:** Enables searching for properties within a certain radius (Google Maps API required).
- **Default Value:** `No`

##### Number of Location Select Boxes
- **Description:** Choose how many cascading dropdowns to use for locations (e.g., Country > State > City).
- **Default Value:** `1`

##### Main Location Label/Placeholder
- **Description:** Sets the label and placeholder text for the first location dropdown.
- **Default Value:** `Main Location` / `All Main Locations`

##### Location Count Placeholder
- **Description:** Text displayed when multiple locations are selected in a multi-select dropdown.
- **Default Value:** `Locations Selected`

##### Child/Grand Child/Great Grand Child Location Labels & Placeholders
- **Description:** Sets the labels and placeholders for the subsequent location dropdowns (if enabled).
- **Default Value:** Varies

##### Enable Multi Select?
- **Description:** Allows users to select multiple locations. (Only works when "Number of Location Select Boxes" is 1).
- **Default Value:** `No`

##### Enable Ajax Based Locations?
- **Description:** Enables a live search for locations as the user types. (Only works when "Number of Location Select Boxes" is 1).
- **Default Value:** `No`

##### Live Search Placeholder
- **Description:** Placeholder text for the AJAX-based location search input.
- **Default Value:** `Enter location name`

##### No Result Text
- **Description:** Text displayed when the AJAX location search finds no matches.
- **Default Value:** `No Location Matched`

##### Hide Empty Locations?
- **Description:** If enabled, locations with no properties assigned will not be shown.
- **Default Value:** `No`

##### Sort Locations Alphabetically?
- **Description:** Sorts locations in alphabetical order. (Only for AJAX-based locations).
- **Default Value:** `No`

##### Field Size (%)
- **Description:** Controls the width of the location field(s).
- **Default Value:** N/A

#### Check In/Out (Visible if Vacation Rentals are enabled)

##### Show Single Field
- **Description:** Combines Check In and Check Out into a single date range picker field.
- **Default Value:** `No`

##### Check In Label/Placeholder
- **Description:** Sets the label and placeholder for the check-in date field.
- **Default Value:** `Check In`

##### Check Out Label/Placeholder
- **Description:** Sets the label and placeholder for the check-out date field.
- **Default Value:** `Check Out`

##### Field Size (%)
- **Description:** Controls the width of the check-in and check-out fields.
- **Default Value:** N/A

#### Guests (Visible if Vacation Rentals are enabled)

##### Guests Label/Placeholder
- **Description:** Sets the label and placeholder for the number of guests.
- **Default Value:** `Guests`

##### Max Guests
- **Description:** The maximum number of guests a user can select.
- **Default Value:** `10`

##### Field Size (%)
- **Description:** Controls the width of the guests field.
- **Default Value:** N/A

#### Property Status

##### Label/Placeholder
- **Description:** Sets the label and placeholder for the property status dropdown.
- **Default Value:** `Property Status` / `All Status`

##### Count Placeholder
- **Description:** Text displayed when multiple statuses are selected.
- **Default Value:** `Status Selected`

##### Show Property Status In Tabs
- **Description:** Displays property statuses (e.g., For Sale, For Rent) as clickable tabs instead of a dropdown.
- **Default Value:** `No`

##### Tabs Display Location
- **Description:** If tabs are enabled, choose to display them at the top of the form or within the fields area.
- **Default Value:** `At Top`

##### Show All Statuses Tab
- **Description:** If tabs are enabled, this adds a tab to show properties of all statuses.
- **Default Value:** `Yes`

##### Default Selected Status
- **Description:** Select a property status to be selected by default when the page loads.
- **Default Value:** None

##### Select Status To Show In Tabs
- **Description:** Choose which specific statuses to display as tabs.
- **Default Value:** All

##### Exclude Status
- **Description:** Hide specific statuses from the dropdown list.
- **Default Value:** None

##### Field Size (%)
- **Description:** Controls the width of the property status field.
- **Default Value:** N/A

*... (Sections for Property Type, Bedrooms, Bathrooms, Min Max Price, Garages, Agents, Agencies, Area, Lot Size, Keyword, and Property ID follow a similar structure with options for labels, placeholders, values, and field sizes.)*

#### Additional Fields

This section allows you to configure how custom fields (created in `Easy Real Estate > New Fields Builder`) appear in the search form.

##### Select to display in placeholder
- **Description:** Choose if the placeholder text for additional fields should be the Field Name (e.g., "All Garages") or a generic "Any" text.
- **Default Value:** `Field Name`

##### Any Text PlaceHolder
- **Description:** The generic placeholder text to use if "Any Text" is selected above.
- **Default Value:** `Any`

##### Placeholder Prefix/Postfix
- **Description:** Text to add before or after the field name in the placeholder (e.g., `All` [Garages] ``).
- **Default Value:** `All` / None

---

### Style Tab

The Style tab provides extensive options to customize the appearance of every element in the search form.

- **Typography**: Controls font settings for all text elements, including field labels, dropdowns, buttons, and more.
- **Basic Styles**: Manages the form's position (relative or absolute), max-width, padding, field heights, and spacing between fields.
- **Colors**: Provides color pickers for every element, including form background, button backgrounds and text (in normal and hover states), field borders, text color, dropdowns, and more.
- **Dropdown List Scroll Styles**: Customizes the appearance of the scrollbar within dropdown lists.
- **Top Tabs Layout Styles**: Styles the property status/type tabs, including padding, spacing, typography, colors, and borders.
- **Radiuses**: Controls the border-radius for all elements to create sharp or rounded corners.