---
sidebar_position : 4
---

# Fields

Fields play a crucial role in your application—they define how data is captured, displayed, and stored. Once created, fields can be reused across your forms, entities, and collections as data blueprints.

## How to Create Fields ?

**1. Access the Entity**

  - Open your app in Apps4x Studio.

  - Navigate to the Entity where you want to add fields.

**2. Use the Field Creation Options**

  - If fields were already created during Collection setup, they will be stored as Base Fields.

  - To create new fields:
    - Click `+ Create` to add a base field.
    - Or, click `Create +` at the top of the field list to define new fields manually.

## Field Properties & Configuration

  - When creating a field, you'll be prompted to fill out the following attributes:

    - Label
    - Name
    - Data Type
    - Order Id
    - Ready only
    - Hide
    - Mandatory
    - Unique
    - Sequence
    - Client Field
    - Computed Field
    - Json Field
    - Default Value
    - Min - Max Length
    - Pattern

  - **Label**
    - Display name for the field shown in forms and UI.

  - **Name**
    - Internal name used as a column in the database.

  - **Data Type**
    - Specifies the kind of data the field holds. (See Data Types below)

    - Datatype types are,
      - String
      - Integer
      - Date
      - Date Time
      - Decimal
      - TimeSpan
      - Image
      - Dropdown
      - Relation
      - Boolean
      - Text Area
      - DB Computed
      - Formula
      - File
      - Time
      - QR Code
      - List
      - HTML Editor
      - Button
      - Icon
      - Password
      - Int64
      - Chips
      - Image Slider

  - **Order Id**
    - Determines the position/order of the field in lists.

  - **Readonly**
    - 	If enabled, field cannot be edited in forms.

  - **Hide**
    - 	If enabled, field will be hidden in the UI.

  - **Mandatory**
    - 	Marks the field as required; cannot be left blank.

  - **Unique**
    - Prevents duplicate values; ensures field uniqueness.

  - **Sequence**
    - 	Converts the field into a sequential ID (requires prefix and pattern).

  - **Sequence Pattern**
    - Custom formatting for sequence values (special characters, prefixes, etc.)

  - **Client Field**
    - Creates the field only at the client/UI level (not stored in DB).

  - **Computed Field**
    - Value is derived from logic (not stored in DB); calculated at runtime.

  - **Json Field**
    - Stores value in JSON format.

  - **Default Value**
    - Predefined value auto-filled in forms unless changed.

  - **Min-Max Length**
    - Sets the allowed range of characters or digits.

  - **Pattern**
    - Regex validation for input formatting. Patterns should be defined in the master table.