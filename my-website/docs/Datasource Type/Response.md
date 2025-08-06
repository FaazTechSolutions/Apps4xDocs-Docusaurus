---
sidebar_position : 3
---

# Response

This section explains how to handle API responses and apply filters to the data before it's used.

## Success Format:

This is how Apps4x determines whether an API call was successful or not :

  - You provide a condition (for example, checking if a certain value exists or is true).

  - If the condition is truthy (i.e., it returns true), then :

    - The API call is treated as a success.

    - The given success message will be shown.

  - If the condition is falsy (i.e., it returns false), then:

    - The API call is treated as a failure.

    - The given error message will be shown instead.

### Response Data Filter

You can filter the data returned from an API using a condition format. Here's how it works:

  - **Condition Format:**

`{{fieldName}}@@Operator@@value`

  Example:

`{{age}}@@Equals@@20`

→ This will filter the data to only include records where the `age` field is equal to `20`. All other records will be removed.

  - Use `@@` as the separator between parts of the condition:

    - `{{fieldName}}` = the name of the field in the data

    - `Operator` = the comparison operator (like Equals, NotEquals, GreaterThan, etc.)

    - `value` = the value you want to compare against.

  - **Need help with operators ?**

You can refer to the list of available operators here.