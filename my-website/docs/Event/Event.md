# Event

The Event feature in Apps4x allows you to trigger actions automatically based on specific conditions—such as sending an email, creating a record, or running other automated tasks.

## How to Configure

  1. Go to the Entity details page and create a new Event.

  2. Select an Event Type. The system supports:

      - **Created** – Trigger when a record is created

      - **Updated** – Trigger when a record is updated

      - **Deleted** – Trigger when a record is deleted

      - **Goal Escalation** – Trigger based on goal rules

      - **Deadline Escalation** – Trigger when a deadline is missed

      - **Recurring Type** – Trigger on a recurring schedule

      - **File Upload** – Trigger when a file is uploaded

  3. Before creating the event, make sure you have a form of type "Create" ready. This is where the action will apply.

  4. Set up Event Conditions when creating the event (or update them later). 
  
  **Example: “Employee Id is not null.”**

## Configure Actions:

  1. Define what should happen when the event is triggered (e.g., create a record, send a message).

  2. Use placeholders in the form to pass dynamic values (like Employee ID, Created Date, etc.).

  3. **Example:**

  - If a record is created in the Employee form,

  - And the Employee Id is not null,

  - Then the system triggers an action to create a record in the Employee History table.

Use Events to automate workflows, reduce manual steps, and ensure important actions happen at the right time.