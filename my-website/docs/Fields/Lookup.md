---
sidebar_position : 4
---

# Lookup

> **Note:**
This feature is used only for displaying related data in a view (like a table or form). It is not meant for creating a dropdown list or selection input.

## How It Works

The **LookUp Data Column** allows you to fetch and show related information from another table. It acts like a "reference field" — pulling in data based on relationships between tables.

| Field Name | Description |
| -----------| ----------- |
| **Related Table** | The name of the table you want to fetch data from. <br>➡️ You can find the table name in **Entity Details**. |
| **Related Table Alias** | An alias (nickname) for the related table. <br>➡️ You can use any name here to simplify references. |
| **Related Table Condition** | A condition (like a `WHERE` clause) to filter the data. <br>➡️ Example: `status = 'active'` |
| **ID Field** | The field from the related table that you want to use as the **key** or reference. |
| **ID Description** | The field from the related table that you want to **display** in the view. <br>➡️ This is what the user will see. |

**Example Use Case**

Let’s say you have a table for Orders, and each order has a **Customer ID**.

If you want to **display the customer’s name** instead of just showing the ID:

  - **Related Table :** `Customers`

  - **Related Table Alias :** `cust`

  - **Related Table Condition :** `cust.isActive = true`

  - **ID Field :** `cust.customerId`

  - **ID Description :** `cust.name`

This will show the customer’s name instead of their ID in the Orders table view.