---
sidebar_position : 4
---

# Condition Operators

Condition operators are used to filter API response data based on specific rules. Below is a list of supported operators and how to use them.

## Old Operators (No Longer in Use)

These operators have been deprecated and should not be used:

  - Equals
  - NotEquals
  - LessThan
  - LessThanOrEqual
  - GreaterThan
  - GreaterThanOrEqual

## New Operators (Recommended)

These are the currently supported operators in Apps4x:

| Operator           | Description                                                                                 |
| ------------------ | ------------------------------------------------------------------------------------------- |
| `IsNull`           | Returns true if the field has a null value                                                  |
| `IsNotNull`        | Returns true if the field is **not** null                                                   |
| `IsEmpty`          | Returns true if the field is an empty string or list                                        |
| `IsNotEmpty`       | Returns true if the field is **not** empty                                                  |
| `Length`           | Compares the **length** of the value (string or list)                                       |
| `Contains`         | Returns true if the field **contains** a specific value                                     |
| `NotContains`      | Returns true if the field **does not contain** a specific value                             |
| `StartsWith`       | Returns true if the value **starts with** a given string                                    |
| `EndsWith`         | Returns true if the value **ends with** a given string                                      |
| `Equal`            | Returns true if the value is exactly equal                                                  |
| `NotEqual`         | Returns true if the value is not equal                                                      |
| `LessThen`         | Returns true if the value is less than the given number *(note typo: should be "LessThan")* |
| `LessThenEqual`    | Returns true if value is less than or equal *(should be "LessThanOrEqual")*                 |
| `GreaterThen`      | Returns true if value is greater than *(should be "GreaterThan")*                           |
| `GreaterThenEqual` | Returns true if value is greater than or equal *(should be "GreaterThanOrEqual")*           |


## Boolean Operators
You can also check for true/false values using special boolean operators:

  - `1` → Checks if the value is true

  Example:

If `value = 'true'`,
`{{value}}@@1@@true` → returns true

  - `0` → Checks if the value is false

  Example:

If `value = 'true'`,
`{{value}}@@0@@true` → returns false

## How to Write a Condition

Use this format:

  `{{fieldName}}@@Operator@@value`

**Example :**

  `{{age}}@@Equal@@30`

→ This filters the data to only include records where the age is 30.