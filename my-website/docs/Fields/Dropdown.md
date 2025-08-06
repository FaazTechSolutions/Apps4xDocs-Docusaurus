---
sidebar_position : 3
---

# Dropdown

Dropdown datatype field is used to configure in the entity in the apps4x.

  - Create a Field and select the datatype as dropdown.

  - You can give a static value for the dropdown datatype field by selecting the `Field Data` field in the field create form.

  - You can add Value and Text as the static dropdown value.

  - Or else, you can checkin the isDynamic checkbox to configure the dynamic dropdown value with [data source](../../docs/Datasource%20Type/Datasource%20Type.md).

  - **Dropdown Value**

    - **Name** (Key name of field that what needs to be stored in dropdown value)

    - **Text** (Key name of display field that needs to be show in the drodown name)

  - **Value Field Hide** (Enable this checkbox to hide the value field in dropdown list)

  - **Dropdown Description** (Add multiple column to show in dropdown)

    - **Field** (Key name of the column to display in list)
    - **Name** (Label name to display in dropdown header)
    - **Data Type** (Select the Datatype of the column)

  - **TextboxShowData** (Key name of the field to display in the dropdown selection)

  - **Is have criteria** (Inbuild Criteria like pageNo, pageSize. Enable this checkbox to page the criteria in api payload)

  - **Has Server side Search ?** (Enable this checkbox to send values of table filter in api payload and filtered from server side)

  - **Has Client side Search ?** (Enable this checkbox to filter the values of table filter with available records in client side)

  - **Is Multiple Select ?** (Enable this checkbox to select multiple values in the dropdown)

  - You can use tree view dropdown
    - Child Key (Child key field name)
    - Parent Key (Parent key field name)
    - Expanded Field (Key field name that you want to expand)

  - [Datasource Type](../../docs/Datasource%20Type/Datasource%20Type.md)