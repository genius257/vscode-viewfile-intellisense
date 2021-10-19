# ViewFile intellisense

Language server for the viewfile php composer package: https://github.com/genius257/view

## Functionality

This Language Server adds code completion for html attributes on the special viewfile html elements.

## Running the project in development

- Run `npm install` in this folder. This installs all necessary npm modules in the client folder
- Run `composer install` in this folder. This installs all necessary composer packages for the server
- Open VS Code on this folder.
- Press Ctrl+Shift+B to compile the client.
- Switch to the Debug viewlet.
- Select `Launch Client` from the drop down.
- Run the launch config.
- If you want to debug the server as well use the launch configuration `Attach to Server`
