# tailwind-sass-syntax

Simple extension that adds tailwind grammar rules for scss and sass files to allow for framework directives syntax highlighting.

## Important note

This extension adds only syntax highlighting for now. Sass validator will fail the built in tailwind directives, such as **@apply**. You can disable sass validation in you linter of choice, or add ignored directives there.

Example for stylelint:
```
"scss.validate": false
```

