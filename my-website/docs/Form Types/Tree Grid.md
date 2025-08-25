---
sidebar_position : 8
---

# Tree Grid

The Tree Grid form in Apps4x lets you display data in a hierarchical (parent-child) structure. It’s useful when you need to group records under a parent row—like showing employees grouped by manager.

## Key Features

  - Shows records in a tree-style view with expandable/collapsible rows.

  - Groups data based on parent-child relationships.

## Example Use Case

If you have a table with:

  - EmployeeId
  - ParentId (manager or reporting person)

The Tree Grid will group employees under their respective managers automatically.

## How to Configure

  - **Create a Tree Grid form** under your desired entity.

  - **Add the required fields** for your data structure.

  - Create a **ParentId** field as a **Client Field**.

  - Navigate to the Tree View tab and configure the following:

    - Set the `RecId` field as the **Child Key**.
    - Set the `ParentId` field as the **Parent Key**.
    - Select any field you want to display as the **expandable label** under the Parent Key (e.g., Employee Name).

## Configuration Tabs

  - [Configuration](../../docs/Form%20Types/Configuration/Configuration.md)
  - [Column](../../docs/Form%20Types/Columns/Columns.md)
  - [Data Source](../../docs/Form%20Types/DataSource/DataSource.md)
  - [Sorting](../../docs/Form%20Types/Sorting/Sorting.md)
  - [Condition](../../docs/Form%20Types/Condition/Condition.md)