---
sidebar_position : 1
---

# Package

The Package feature in Apps4x is used to move metadata (like forms, entities, queries, etc.) from one environment to another—for example, from Development to Testing or Production.

## What It Does

  - Packages allow you to clone and export meta objects.

  - These can then be imported into a different environment.

  - This helps manage deployments across environments without manual rework.

## How to Create a Package

  1. Go to the Package section and click Create.

  2. Enter a Package Name and optional Image.

  3. In the details page:

        - Select the Connector.

        - Choose the meta objects you want to include (forms, entities, queries, etc.).

  4. Click Save, then Export the package.

## How to Import and Deploy

  1. Import the exported connector package into the target environment.

  2. After import, go to the package details page and click:

        - **Schema Migration** – Migrates the table structure.

        - **Data Migration** – Migrates the actual data.

        - **Testing** – Run validations to ensure everything works.

        - **Activation** – Finalize the package. After this, meta objects can't be edited.

        - **Complete** – Marks the process as finished.

## App Packages

After importing the connector package, follow the same steps for the App package:

  1. Create and export the App package by selecting required meta objects.

  2. Import into the target environment.

  3. Follow the same steps:

        - Schema Migration
        - Data Migration
        - Testing
        - Activation
        - Complete

> **Note:**
After Activation, no changes can be made to the meta objects included in the package.