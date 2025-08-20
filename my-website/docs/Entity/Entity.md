---
sidebar_position : 3
---

# Entity

An Entity is a core component within a Collection. It defines the structure of your data by grouping Fields, Forms, Events, Activities, and Actions under one logical unit.

## How to Create an Entity ?

Follow these steps to create an entity within a collection:

**1. Navigate to the Collection**

  - In Apps4x Studio, open the app and select the parent Collection where you want to add the entity.

**2. Click the `+` Icon**

  - On the left side of the Collection menu, click the `+` icon to open the Create Entity popup.

  - Fill the required informations in the entity create popup.

**3. Create the Entity**

  - Click `Save` to add the entity to your collection.

## Entity Versioning :

Entity Versioning allows you to manage and control changes made to an Entity over time. This feature ensures that once an Entity is finalized, it remains unchanged unless explicitly versioned.

  - When an Entity is initially created, it starts in **Draft** status with **Version 1** by default.

  - After configuring all necessary components—such as fields, forms, and events—you can change the Entity status from **Draft** to **Active** once no further modifications are needed.

  - **Active** Entities are locked from further editing. To make changes, you must create a **new version** of the Entity.

  - Creating a new version automatically:

    - Sets the previous version to **Inactive**.

    - Creates a new version (e.g., **Version 2**) in **Draft** status.

  - You can then modify and configure the new version as needed.

  - Once you're satisfied with the updates, activate the new version. Upon activation:

    - The new version becomes **Active**.

    - The previous version remains **Inactive**.

    - If needed, you can revert **Version 1** from **Deactivated** back to **Draft** status for further modifications or reuse.

This versioning mechanism helps preserve historical configurations while enabling controlled updates to Entities.