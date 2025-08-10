# HandleBar Keywords

HandleBar helps you automatically fill in values like names or numbers while your app is running.

You just use double curly brackets `{{ }}` to show where a value should appear.

## How It Works

Let’s say your data has this:

  `{name: "Mohamed Asim"}`

If you write `{{name}}` in your form or message, it will show:

→ Mohamed Asim

### Example

  - You write: Hello, `{{name}}`!
  - It shows: Hello, Mohamed Asim!

You only need to enter the keyword inside `{{ }}`, and the system will fill in the correct value for you.

## HandleBar Usage Examples

HandleBar lets you insert live data into your app by using `{{ }}`. Below are some common ways to use it based on where your data comes from:

**1. Direct Value**

Use this when you want to display simple data like a name:

  - `{{name}}` → Will show the value of `name`, like **"Asim"**.

**2. From a Page URL (Query Parameter)**

Use this to get data from the web address (URL):

  - `{{Query.name}}` → Shows the value passed through the URL, like **`?name=Asim`**.

**3. From the Current Page Data**

Use this to access data already available on the page:

  - `{{Current.name}}` → Displays data from the current page’s info.

**4. Environment ID**

Use this when you want to get the current environment’s ID:

  - `{{EnvironmentId}}` → Shows the ID of the app environment you're in.

**5. Create Form Parameters**

Used when opening or closing a popup or form:

  - `{{Params.name}}` → Shows values passed when a form or popup opens.

**6. From Local Storage**

Use this if you've saved data in the browser (local storage):

  - `{{Local.name}}` → Shows saved values like settings or previous input.

**7. User Info from Local Storage**

Access saved user details like username:

  - `{{LocalUserInfo.username}}` → Displays the logged-in user’s name from stored info.

**8. From Navbar Search (Not commonly used)**

This is used to show the value entered in the top search bar, saved in local storage.

  - `{{NavbarSearchData.searchvalue}}`

>  Pulls the search text from the navbar search (stored as CommonNavbarSearch in local storage).
**Currently not in use.**

**9. From Cookies**

Use this to get data saved in browser cookies:

  - `{{Cookies.name}}`

>  Shows the value of the cookie named name.

**10. From System Configuration File**

Use this to get information from your app’s configuration file `(systemConfig.json)`:

  - `{{System.ServerUrl}}`

>  Pulls the server URL or other values set in `assets/json/systemConfig.json`.

**11. From Parameters Table**

  - `{{Parameter.faazurl}}`

>  This gets a value from the Parameters table.
Use it when you want to insert dynamic values like URLs or settings that may change later.

**12. From Global Service Variables**

  - `{{Global.SystemTitle}}`

  - [Global Service Fields](../../docs/Global%20Service/Global%20Service%20Fields.md)

> This gets information from global app settings (called global service variables).

>  Example: Showing the name or title of your app throughout the system.

**13. From Parent Component**

  - `{{ParentData.name}}`

>  Gets a value (like name) from the parent component.

**14. From Custom Filter**

  - `{{Filter.salaryid}}`

>  Gets a value entered in a custom filter form.

**15. From Page Data**

  - `{{PageData.id}}`

>  Retrieves the current page’s data like the record ID.

**16. Current Workflow Stage ID**

  - `{{currentStageId}}`

>  Displays the current stage ID of a workflow.

**17.  Workflow Stage Data**

  - `{{WFData.stageId}}`

>  Pulls stage data from the workflow.
This is a dynamic value updated during workflow steps.

**18. From Page Group Values**

  - `{{ListData.RecId}}`

>  Used to access grouped values in screens like Dynamic Form or Dynamic View.

**19. Form Mode**

  - `{{Mode}}`

>  Tells you whether the form is in Create, Edit, or View mode.
Available in Dynamic View pages.

**20. Custom Helpers (Example)**

  - `{{TodayDatePipe 'DATE'}}`

>  This is a custom helper to show today’s date in a specific format (like date only).

**21. From Form Data (Entity or Action Form)**

  - `{{FormData.Name}}`

>  Gets a field value (like Name) from the current form you’re working in.