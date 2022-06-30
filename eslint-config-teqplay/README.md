**Welcome!**

This repository contains initial configuration file for Teqplay ES-lint rules.

The rules will be updated regarding the Teqplay developer feedbacks soon.

First Step : Install

```bash
yarn add @teqplay/eslint-config eslint-config-airbnb --dev
```

or

```bash
npm install --save-dev @teqplay/eslint-config eslint-config-airbnb
```

Second Step : Extend your `.eslintrc`

```js
{
  "extends": "@teqplay"
}
```

Third Step : Add the following into your `.eslintignore`

```eslint
build/*
public/*
src/react-app-env.d.ts
src/serviceWorker.ts
```

(Optional) Fourth Step: add `check-lint` script to your `package.json`

```json
"check-lint": "eslint --ext .js,.jsx,.ts,.tsx src --color"
```

It is ready!
Happy coding!
