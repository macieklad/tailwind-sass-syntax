# tailwind-sass-syntax

Simple extension that adds tailwind grammar rules for scss and sass files to allow for framework directives syntax highlighting.

## Important note

This extension adds only syntax highlighting for now. Sass validator will fail the built in tailwind directives, such as **@apply**. You can disable sass validation in you linter of choice, or add ignored directives there.

Example for stylelint:
```
"scss.validate": false
```

## Contributing and development
Install packages, and launch vscode in the directory. After that follow the instructions provided within
vscode developer guides [here](https://code.visualstudio.com/api/get-started/your-first-extension). When you are ready, create a pull request
so we can discuss it (as the extension is simple, there is no template for contributions, feel free to write anything). Inside the ``test`` directory there is a sample file with tailwind directives, to test the extension on.
```bash
npm install && code ./
```
