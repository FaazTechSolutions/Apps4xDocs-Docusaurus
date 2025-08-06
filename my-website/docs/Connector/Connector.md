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

**4. Enter Connection Details**

  - Provide a Connection String or other required credentials, depending on the selected connector type.

**Sample Connection string for the database connector :**

> Server=tcp:dummy.database.windows.net,1433;Initial Catalog=dummyDBNAME;Persist Security Info=False;User 

> ID=UserID;Password=123;MultipleActiveResultSets=False;Encrypt=True;TrustServerCertificate=False;Connection Timeout=180;

**5. Save the Connector**

  - Click Submit to complete the setup. Your connector is now ready to be used with Collections.