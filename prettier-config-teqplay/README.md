**Welcome!**

This repository contains initial configuration file for Teqplay Prettier rules.

The rules will be updated regarding the Teqplay developer feedbacks soon.

First Step : Install

```bash
yarn add @teqplay/prettier-config --dev
```

or

```bash
npm install --save-dev @teqplay/prettier-config
```

Second Step : Extend your `.prettierrc.js`

```js
module.exports = {
  ...require('@teqplay/prettier-config')
}
```

(Optional) Third Step: add the following scripts to your `package.json`

```json
"check-lint": "prettier --check \"./src/**/*.ts\" \"./src/**/*.tsx\"",
"format": "prettier --write 'src/**/*.{ts,tsx,scss,css,json}'"
```

It is ready!
Happy coding!
