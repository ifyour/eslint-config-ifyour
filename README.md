# eslint-config-ifyour

ifyour's eslint configuration, with some sensible defaults for ES2015, React and Mocha.

## Installation

#### Project
Install eslint and this config:

```
npm i -D eslint eslint-config-ifyour
```

Now in your `package.json`:

````
...

"eslintConfig": {
  "extends": "eslint-config-ifyour"
},

...
````

#### VSCode

Install [Eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint), and in your `settings.json`:
```
...

"editor.codeActionsOnSave": {
  "source.fixAll": true,
},
"editor.formatOnSave": false,
"editor.formatOnPaste": false,

...
```


## Credits

This is a modified version of [eslint-config-developit](https://github.com/developit/eslint-config-developit)
