---
sidebar_position : 2
---

# Transform

The transform option helps the system know where to look in the response data to find the values that should be shown in the table.

  - If the data we need is nested inside the response, we use transform to tell the system the exact path to that data.

  - In some cases, the data is already directly inside an array (list), so we don’t need to set the transform path — the system can use the values as they are.

  - When transform is used, make sure to save the correct transform path so that the table can display the right information.