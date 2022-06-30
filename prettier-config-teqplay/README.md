**Welcome!**

This repository contains initial configuration file for Teqplay ES-lint rules.

The rules will be updated regarding the Teqplay developer feedbacks soon.

First Step : Install

```bash
yarn add @teqplay/prettier-config --dev
```

or

```bash
npm install --save-dev @prettier-config
```

Second Step : Extend your `.prettierrc.js`

```js
module.exports = {
  ...require('@teqplay/eslint-config')
}
```

(Optional) Third Step: add `check-lint` script to your `package.json`

```json
"check-lint": "prettier --check \"./src/**/*.ts\" \"./src/**/*.tsx\""
```

It is ready!
Happy coding!
