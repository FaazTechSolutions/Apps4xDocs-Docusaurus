# Rest API

The REST API data source type allows you to connect an external API to your app, so you can fetch and use real-time data inside forms, tables, or other components.

## Step-by-Step Setup

**1. Create a New Form**

  - Start by creating a new form in your app where the API data will be used.

**2. Go to Form Details**

  - Open the form you just created.

  - Click on the **"DataSource"** tab.

**3. Create Client Fields**

  - These are the fields that will be used to send data to or receive data from the API.

**4. Set Up a Base URL Parameter**

  - Before creating the data source, you must first [create a parameter](../../docs/Parameter/Parameter%20Create.md) for the base URL of the API.

  - This makes it easier to reuse and manage the API URL across different parts of the app.

**5. Add URL Using Parameter**

  - In the data source URL, use the **parameter** you created like this:

  `{{Parameter.keyOfYourParameter}}`

  - This uses **Handlebars** syntax, which means the actual value of the parameter will automatically be inserted at **runtime**.

**6. Create a Menu (Optional)**

  - You can [create a menu](../../docs/Menu/Menu.md) linked to this data source to display the fetched data in a user-friendly way.