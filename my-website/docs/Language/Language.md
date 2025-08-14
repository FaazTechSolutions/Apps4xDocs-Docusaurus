# Language

Apps4x supports multi-language capabilities, allowing your application to display content in different languages. This is useful when building apps for users across various regions and language preferences.

## How to Enable Multiple Languages in Apps4x?

To enable and manage multiple languages, you’ll need to manually create and configure two entities:

### 1. SYSLanguage Entity

This entity defines the available languages.

**Required Fields:**

  - **Language**: The language you are adding (e.g., English, Arabic).

  - **Name**: Display name of the language.

  - **ShortCode**: A short identifier for the language (e.g., en, ar).

  - **Direction**: Text direction, either:

    - `LTR` (Left to Right) – for languages like English

    - `RTL` (Right to Left) – for languages like Arabic

### 2. SYSLabel Entity

This entity stores translations for the words used in your application.

**Required Fields:**

  - **Default Value**: The original word or phrase used in the app.

  - **English**: Translation of the default word in English.

  - **Arabic**: Translation of the word in Arabic.

> **Note :** For the Meta Object Id column, use the entity name (e.g., Customer) — not the GUID.

## How to Add Language Data (SYSLanguage and SYSLabel)?

### 1. Create entries in SYSLanguage:

  - Add each language you want to support with valid `ShortCode` and `Direction`.

### 2. Add translation words in SYSLabel:

  - For each `Default Value`, provide the corresponding translations in `English`, `Arabic`, or any other languages you support.

### 3. Change the language in your app:

  - When the language is changed, the app will automatically show words from the `SYSLabel` entity based on the selected language.

## Example

If you want to add support for **Arabic**:

  - In **SYSLanguage**, add:

    - `Language`: Arabic

    - `Name`: Arabic

    - `ShortCode`: ar

    - `Direction`: RTL

  - In **SYSLabel**, for a button labeled "Save":

    - `Default Value`: Save

    - `English`: Save

    - `Arabic`: حفظ

Now, when a user switches to Arabic, the app will display `“حفظ”` instead of `“Save”`.