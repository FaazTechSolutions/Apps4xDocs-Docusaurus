# DataSource

DataSource defines the origin of data that powers your forms. It allows you to connect forms to different sources such as APIs, queries, collections, or connectors. Configuring a proper DataSource is essential for displaying dynamic and live data on the output page.

## Supported DataSource Types

Apps4x supports various DataSource types to suit different data integration needs:

  - RestApi
  - Query
  - Collection
  - Entity
  - Rest API Connector
  - SQL Connector
  - Swagger Connector
  - Logic
  - Default

**RestApi**

  - Connect directly to REST APIs to fetch and display external data.

**Query**

  - Use a custom query to retrieve and manipulate data before showing it in the form.

**Collection**

  - Bind the form to an existing Collection from the app's data model.

**Entity**

  - Directly use an Entity within a Collection as the data source.

**Rest API Connector**

  - Use a pre-configured REST API Connector created in the App Studio.

**SQL Connector**

  - Fetch data from SQL databases using a SQL Connector.

**Swagger Connector**

  - Integrate with APIs that expose Swagger documentation for easy field mapping.

**Logic**

  - Use business logic or predefined scripts to fetch and control data presentation.

**Default**

  - A fallback data source used when no specific configuration is provided.

## DataSource Setup

In Apps4x, the DataSource Setup allows you to configure how data is fetched, filtered, and transformed before it is displayed in a form. This configuration is applicable to all DataSource types.

### Setup Configurations

The setup consists of four key tabs:

  - Configure
  - Condition
  - Transform
  - Response

**1. Configure**

  - Define the Query list and Parameters required for fetching data.

  - This is where you set the main structure and entry point for data retrieval.

**2. Condition**

  - Add logical conditions to determine when and how the data should be fetched.

  - The data will be retrieved only if the specified condition is met.

**3. Transform**

  - Use the Transform option to map or extract a specific part of the response.

  - This ensures that only the relevant data path is used in the form, keeping the response clean and structured.

**4. Response**

Manage how the response is handled and shown to the user:

  - **Success Format**
    - Defines the condition under which the API call is considered successful. If false, it is treated as an error.

  - **Success Message** 
    - Message shown when the Success Format condition evaluates to true.

  - **Error Message** 
    - Message shown when the Success Format condition evaluates to false.

  - **Response Data Filter** 

    - Apply a filter to the returned data. Only records that match the condition will be shown.

    Example Format:

    `{{age}}@@Equals@@20`

  This filters the response to include only records where the age field equals 20.

  - This is the formate you have use for the condition `{{age}}@@Equals@@20` you have to separate by @@ symbol.

> Note: Use @@ as the separator between the field, operator, and value.