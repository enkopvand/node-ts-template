helios-shared-ts-template


npm init
npm install -D typescript
npm i -D --save-exact prettier
.prettierrc.json
.prettierignore
npx tsc --init
Add changes to tsconfig.json

npm i -D eslint
npx eslint --init
npm i -D eslint-plugin-prettier
npm i -D eslint-config-prettier

.vscode folder
settings.json
{
    "editor.formatOnPaste": true,
    "editor.defaultFormatter": "dbaeumer.vscode-eslint",
    // "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,
    "editor.tabSize": 4,
    "eslint.alwaysShowStatus": true,  
    "editor.codeActionsOnSave": {
      "source.fixAll": true,
      "source.fixAll.eslint": true
    },
    "javascript.format.insertSpaceBeforeFunctionParenthesis": true,
    "javascript.format.placeOpenBraceOnNewLineForControlBlocks": false,
    "javascript.format.placeOpenBraceOnNewLineForFunctions": false,
    "typescript.format.insertSpaceBeforeFunctionParenthesis": true,
    "typescript.format.placeOpenBraceOnNewLineForControlBlocks": false,
    "typescript.format.placeOpenBraceOnNewLineForFunctions": false,
    "explorer.confirmDragAndDrop": false,
    "typescript.updateImportsOnFileMove.enabled": "always",
    "typescript.preferences.importModuleSpecifier": "non-relative",
}