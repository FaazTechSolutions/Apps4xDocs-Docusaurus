---
sidebar_position : 2
---

# Collection

Each Application in Apps4x has a Collection, which organizes a group of Entities, their Fields, and associated Forms.

## How to create Connectors ?

Before creating a Collection, you must set up a Database Connector in App Studio to manage data effectively.

### Steps to Create a Connector :

**1. Open App Studio**

  - Navigate to your app and enter the Apps4x Studio.

**2. Go to the Connectors Tab**

  - In the Apps4x studio, select `connectors` from the top navigation tab and click `+` tab, it will appear the connector create popup.

**3. Choose Connector Type**

  - Select the type of connector that suits your data source:

  - The Connector types are,
    - SQL
    - MongoDB
    - Rest Api
    - API Method
    - Swagger

**4. Enter Connection Details**

  - Provide a Connection String or other required credentials, depending on the selected connector type.

**5. Save the Connector**

  - Click Submit to complete the setup. Your connector is now ready to be used with Collections.

## How to create Collection ?

Once you've created a Database Connector, you can start building Collections in your app.

### Steps to Create a Collection :

**1. Open the App in Studio**

  - Go to the Apps4x Studio and select the app where you want to create the collection.

**2. Click the `+` Icon in the Collection Menu**

  - In the left-side navigation, find the Collections section.

  - Click the + icon to open the Create Collection form.

**3. Fill in Collection Details**

  - Provide the required information like:
    - Collection Name
    - Description (optional)
    - Connector ID – Choose the Database Connector you created earlier.

**4. Save the Collection**

  - Once all fields are completed, Click continue button. It will take to you create entity and it's fields.

  - If you're ready to create entity and it's fields, then you can proceed with the flow.