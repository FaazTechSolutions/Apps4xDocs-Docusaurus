# Decision Table

The Decision Table in Apps4x allows you to define and test logic-based conditions. It helps you verify whether a condition works as expected before it runs in the backend.

## How to Create

  1. Click the `+` icon in the left-side Decision Table menu.

  2. Enter a name to create the Decision Table.

  3. Add your conditions and define the expected outcomes.

Once the logic is verified in preview, it will be executed in the backend.

**Example :**

You can create a rule like:

  - **Condition: If Age > 18**

  - **Then:** Show **"Eligible to vote"**

  - **Else:** Show **"Not eligible for vote"**

If the condition is true (Age is over 18), the system shows only the eligible message.

If not, it will show "Not eligible for vote".

This feature is useful for applying simple rules without writing code.