# Page

The Page feature in Apps4x lets you design a layout by combining different elements like forms, tables, collections, tabs, and more—all in one place.

## How to Configure

  - Click the `+` icon on the left menu to create a new page.

  - Choose a `Base Entity` for the page.

  - Open the Page Canvas and select the Form option to start designing.

### Parent Types

When adding a form to the page, choose a Parent Type:

  - **Entity** – Use data from a standard entity
  - **Query** – Use a custom query
  - **Connector** – Use external API data
  - **Function** – Use output from a function

After selecting the parent type, choose the form you've already created under that entity.

### Final Step

To display the page in the output menu:

  - Create a Menu, then
  - Link your created Page to that menu.

## Page Versioning

Page Versioning enables you to manage and control changes made to a page's configuration over time.

  - When a new page is created, it is assigned **Version 1** and set to **Draft** status by default.

  - You can configure and update the page while it is in **Draft** status.

  - Once you’ve completed your updates, you can **Activate** the page. Activation finalizes the page, and no further changes can be made to that version.

  - To make additional changes or updates, you must create a **new version** of the page.

  - When a new version is created:

    - It is assigned the next version number (e.g., **Version 2**).

    - It is set to **Draft** status by default.

  - You can make your updates in the Draft version. Once complete, **activate the new version** to apply the changes to the live output.

  - Until the new version is activated, the previously active version (e.g., Version 1) will continue to appear on the output page.

  - After activating the new version :

    - The previous version is automatically **Deactivated**.

    - The newly activated version becomes the current live version.

    - If needed, you can revert **Version 1** from **Deactivated** back to **Draft** status for further modifications or reuse.