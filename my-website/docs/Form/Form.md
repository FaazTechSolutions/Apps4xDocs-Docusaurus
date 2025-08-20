---
sidebar_position : 6
---

# Form

Forms in Apps4x are versatile components that allow users to view, create, interact with, and manage data within the application. Each form type is tailored to a specific use case or presentation style, providing flexibility in how information is displayed or entered.

## Types of Forms

Apps4x supports a wide range of form types, categorized by function and display format:

  - [Table](../../docs/Form%20Types/Table.md)
  - [Card](../../docs/Form%20Types/Card.md)
  - [Board](../../docs/Form%20Types/Board.md)
  - [Chart](../../docs/Form%20Types/Chart.md)
  - [List](../../docs/Form%20Types/List.md)
  - [Custom Template](../../docs/Form%20Types/Custom%20Template.md)
  - [Report](../../docs/Form%20Types/Report.md)
  - [Tree Grid](../../docs/Form%20Types/Tree%20Grid.md)
  - Tree View - Not Implemented
  - [Chat](../../docs/Form%20Types/Chat.md)
  - Timeline - Same as like Chat
  - Profile - Not in Use
  - [Image Slider](../../docs/Form%20Types/Image%20Slider.md)
  - Form - Not in Use
  - Create - Same like [Details](../../docs/Form%20Types/Details.md) the purpose of the form is we can use this in event action type create.
  - [Details](../../docs/Form%20Types/Details.md)
  - [Action](../../docs/Form%20Types/Action.md)
  - [Workflow](../../docs/Form%20Types/Workflow.md)
  - [Datasource](../../docs/Form%20Types/DataSource/DataSource.md)
  - [Activity](../../docs/Form%20Types/Activity.md)
  - Assignment - Not in Use
  - [Filter](../../docs/Form%20Types/Filter.md)
  - Menu - Not in Use

## Form Versioning

Form versioning enables efficient management and control of changes made to a form's configuration.

  - When a form is first created, it starts in **Draft** status by default.

  - While in Draft status, you can modify the form’s **design**, **rules**, **data sources**, and other **configurations**.

  - Once you’ve finalized your changes, you can **Activate** the form. Activation locks the form, preventing any further modifications.

  - After a form is activated, it can no longer be edited directly.

  - To make updates or changes to an already activated form, you must **create a new version** of the form.

  - When a new version is created :

    - The previous version (e.g., Version 1) remains **Active**.

    - The new version (e.g., Version 2) is created in **Draft** status.

  - You can then update and configure Version 2 as needed. Once satisfied, activate it to apply the changes.

  - Upon activation of the new version :

    - The previous version is automatically set to **Deactivated**.

    - The newly activated version becomes the current live form.

    - If needed, you can revert **Version 1** from **Deactivated** back to **Draft** status for further modifications or reuse.

> **Notes :** If the associated **Entity** is in Active status, you cannot create a new form. However, you can still make changes to existing forms.