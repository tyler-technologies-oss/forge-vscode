# Forge Extension for VS Code

An extension for VS Code that adds code snippets for all Forge Web Components, including variants and common usages.

## Usage

Type part of a snippet (ex. `<forge-scaffold`), press `enter`, and the snippet unfolds.

## Installation

- Copy the extension into your `<user home>/.vscode/extensions` folder and restart Code.

OR install from `.vsix` file:

- Open VS Code
- Press `ctrl+shift+p` (`cmd+shift+p` on mac) to open the command palette
- Type `"vsix"` and select `Extensions: Install from VSIX...`
- Navigate to the location where you downloaded the `.vsix` file and select it

## Development

- Make necessary changes to snippets
- Press `F5` to open dev instance of VS Code
- Test snippets by creating a new file and setting language mode
- Verify that your snippets are proposed on intellisense.

## Publishing

- Update `version` property `package.json`
- Run `npm run pack`
- `.vsix` file will be placed at the root of the project
