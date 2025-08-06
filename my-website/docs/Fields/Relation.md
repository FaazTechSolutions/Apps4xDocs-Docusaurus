---
sidebar_position : 5
---

# Relation

This section is used to configure a dropdown field that loads its options from another entity (table) in your app. It’s helpful when you want to show a list of related records — like selecting a customer from a list, or showing cities based on a selected state.

| Field Name | Description |
| ---------- | ----------- |
| **Relation Entity** | The entity (table) from which you want to load the dropdown data. <br>➡️ Example: `States`, `Customers`, `Products` |
| **Related Field** | The field whose **value** will be stored when a user selects an item from the dropdown. <br>➡️ This is typically the **ID or Code**. |
| **Related Display Field** | The field whose **text** will be shown in the dropdown list. <br>➡️ Example: `name`, `title` |
| **Related List Field Group** | Choose a field group (predefined set of fields) to include extra data when listing options. |
| **Related Lookup Field Group** | Choose a field group to fetch additional data when using this dropdown in **lookup views**. |
| **Relation Field Condition** | Optional condition to filter data when loading dropdown options. <br>➡️ Example: `status = 'active'` |
| **Dependent Lookup Field** | Used when dropdown options depend on another field's value. <br>➡️ Example: If selecting a **city** depends on the selected **state**, then `state code` is the dependency. |
| **Is Relation Data Pagination?** | Enable this to load **all** data from the related entity into the dropdown at once. <br>➡️ If disabled, data may be loaded in pages (useful for large datasets). |

**Example: State → City Dropdown**

Let’s say you have two dropdowns — one for State and one for City. You want cities to be loaded based on the selected state.

  - **Relation Entity:** `Cities`

  - **Related Field:** `cityCode`

  - **Related Display Field:** `cityName`

  - **Dependent Lookup Field:** `stateCode`(this field must match the selected state)

  - **Relation Field Condition:** Optional — you could use `isActive = true`

  - **Is Relation Data Pagination?:** Enable if the city list is small; otherwise, leave it paginated