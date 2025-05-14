# Property Settings

You can configure global property-related options by navigating to **Dashboard → Easy Real Estate → Settings → Property**

These settings allow you to define area units, auto-generated property ID formats, and energy performance classes for properties.

![RealHomes Documentation](images/ere-tabs/property.png)

---

### **Area Size Unit**

Specify the default unit for property area (e.g., **sq ft**, **m²**, **acres**, etc.).  
This unit will be used across all property listings for area fields.

---

### **Lot Size Unit**

Define the unit for the lot size, which is separate from the area unit.  
Example: **sq ft**, **m²**, etc.

---

### **Enable Auto-Generated Property ID**

Toggle this setting to automatically generate a property ID when a new property is added:
- **Enable** – Auto-generates ID using a defined pattern.
- **Disable** – Requires manual entry of property ID.

---

### **Auto-Generated Property ID Pattern**

Define a pattern for the system to use when generating property IDs.

- Use `{ID}` in the pattern to dynamically insert the actual property ID.
- Example: `RH-{ID}-property` will become something like `RH-154-property`.

!!! note
    Make sure to include `{ID}` in your pattern. It will be replaced with the actual property ID number.

---

### **Energy Performance Certificate Classes**

Manage energy rating classes (e.g., A+, A, B, C, etc.) for properties. Each class can be:
- Labeled with a **custom name**
- Assigned a **specific color**

This feature helps display energy ratings visually on frontend property listings.

You can also click **+ Add more** to add new custom rating classes as needed.

---

Click the **Save Changes** button to apply your updated settings.