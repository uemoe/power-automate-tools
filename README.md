![Extension Logo](public/icons/pa-tools-128.png)

# Power Automate Tools Extension

![Extension Screen Shot](static/pa-tools-extension.jpg)

The Chrome/Edge extension that enables editing a Power Automate flow definition as JSON.

## Motivation

The reason behind creating this extension is constantly struggling with repetitive tasks in the flow authoring workflow like replacing a SharePoint site's URL or changing the variable name.

## Features

- Edit a Power Automate flow as JSON in your browser.
- Workflow definition JSON schema validation.
- Rich text manipulation features thanks to [Monaco Editor (VS Code)](https://microsoft.github.io/monaco-editor/).
- Validating actions using "Flow Checker".
- More features may come in future :)

## Getting started

1. Get the extension from the Edge extensions store or download a [release](https://github.com/rithala/power-automate-tools/releases), unzip the package, enable developer mode in your browser, and add the exnsion as unpacked.
2. Open the flow details or edit page in the Power Automate portal.
3. Click the extension icon.
4. Edit your flow!

## Known limitations

- Works only with the Power Automate portal
- The authentication token is not refreshed automatically at this moment. Sometimes might be necessary to refresh the flow's page that was used to open the extension.
