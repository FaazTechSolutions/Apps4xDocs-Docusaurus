# Connector

## Setup Guide

Connectors in Apps4x let you link your app to various data sources like databases and APIs. Follow these simple steps to create a connector.

## What is a Connector?

A Connector allows your app to connect and interact with external data sources—like SQL databases, APIs, or services—so you can pull in data or send it out as needed.

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

  - **DB Connector (SQL/Mongo DB)**

    - [Create Parameter](../../docs/Parameter/Parameter%20Create.md), before creating DB Connector.

    - Now You can create DB Connector.

    - Click to [view DB Connector usage](../../docs/Connector/DB%20Connector.md).

  - **REST API Connector**

    - You can integrate the third party APIs into the application by using REST API connector.

    - [Create Parameter](../../docs/Parameter/Parameter%20Create.md) for Base Url to sue the REST API connector.

    - Click to [view Rest API Connector usage](../../docs/Connector/Rest%20Api%20&%20Swagger%20Connector.md).

  - **Swagger Connector**

    - You should have Swagger Json to use Swagger connector.

    - [Create Parameter](../../docs/Parameter/Parameter%20Create.md) for Base Url to sue the Swagger connector.

    - Your absoulte path should be `/swagger/v1/swagger.json`

    - Also make sure your swagger is working fine.

    - Click to [view Swagger Connector usage](../../docs/Connector/Rest%20Api%20&%20Swagger%20Connector.md).

  - **API Method Connector** - (Will Develop in Future)

**4. Enter Connection Details**

  - Provide a Connection String or other required credentials, depending on the selected connector type.

**Sample Connection string for the database connector :**

> Server=tcp:dummy.database.windows.net,1433;Initial Catalog=dummyDBNAME;Persist Security Info=False;User 

> ID=UserID;Password=123;MultipleActiveResultSets=False;Encrypt=True;TrustServerCertificate=False;Connection Timeout=180;

**5. Save the Connector**

  - Click Submit to complete the setup. Your connector is now ready to be used with Collections.