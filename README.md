# cypress_poc
This is a POC project to learn and improve knowles about cypress framework.

---

## Install and open
Init npm
```cmd
npm init 
```

Install cypress
```cmd
npm install cypress --save-dev
```

Open cypress
```cmd
npx cypress open
```

---

## Config

### Intellisense
In order to enable the intellisense, create `cypress/tsconfig.json` file and copy the above config:

```json
{
    "compilerOptions": {
      "allowJs": true,
      "baseUrl": "../node_modules",
      "types": [
        "cypress"
      ]
    },
    "include": [
      "**/*.*"
    ]
}
```

or in any test file (`.js`) insert at the first line:

```js
/// <reference types="Cypress" />
```

---

