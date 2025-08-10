# Rules

The Rules feature in Apps4x allows you to define and execute custom logic based on certain actions or events within your application.

With Rules, you can automate behaviors, validate data, or trigger processes when specific conditions are met.

## Rules Action Implementation

  - **OnBeforeInsert** - Runs before a new record is inserted. Useful for validation or preprocessing.

  - **OnAfterInsert** - Runs after a new record is added. Use this to trigger follow-up actions.

  - **OnBeforeUpdate** - Runs before a record is updated. Ideal for checking data or conditions.

  - **OnAfterUpdate** - Runs after a record is updated. Often used to trigger notifications or logs.

  - **OnBeforeDelete** - Runs before a record is deleted. Great for confirming conditions or blocking actions.

  - **OnAfterDelete** - Runs before a record is deleted. Great for confirming conditions or blocking actions.

## Example Use Cases

  - **Auto-calculate a value** before saving a form.

  - **Send an email** after a new customer is added.

  - **Prevent deletion** of a record if certain conditions are met.

  - **Log changes** to a record after updates.