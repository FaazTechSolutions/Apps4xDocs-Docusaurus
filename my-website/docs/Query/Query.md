# Query

The Query feature in Apps4x is used to fetch and display data from the database, based on your specific needs. It works with data from existing Entities or Collections.

## Before You Begin

Make sure you have already created a `Collection or Entity` before creating a query.

## How to Create a Query

  1. Click the `+` icon from the left-side Query menu.

  2. Choose the Table Type and Query Type from the dropdown.

  3. Select one of the following Query Types:

**1. Table List**

  - Use this to read data directly from a table.

  - Click the `Edit` button to customize how data is shown.

  - Save to link the query with the datasource.

**2. Aggregate**

  - Use this type to create queries with `joins between tables`.

  - After saving, you can connect this query to a datasource for output.

**3. Custom Query**

  - Write your own SQL-style query manually.

  - After writing the query:

    - Click `Save`, then
    - Click `Execute` to preview the result.

## Query Configuration

  - You can add parameters for the query, that you have creating.

## Query Versioning

Query Versioning allows users to manage and track changes made to a query’s configuration over time.

  - When a new query is created, it is assigned **Version 1** and set to **Draft** status by default.

  - You can configure the query as needed while it is in Draft status.

  - Once your configurations are complete, you can **Activate** the query. After activation, the query becomes locked, and no further changes can be made to that version.

  - To update or modify the query after activation, you must create a **new version** by selecting the **New Version** option.

  - Upon creating a new version :

    - The previous version (e.g., Version 1) remains **Active** and continues to be used in the live environment.

    - The new version (e.g., Version 2) is created in **Draft** status.

  - You can now make your desired changes in Version 2.

  - Once the updates are finalized, you can **Activate** Version 2 to apply the changes to the live environment.

  - When Version 2 is activated:

    - Version 1 is automatically set to **Deactivated** status.

    - If needed, you can revert **Version 1** from **Deactivated** back to **Draft** status for further modifications or reuse.