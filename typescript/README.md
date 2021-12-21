# @wolox/eslint-config-typescript

[![FEArmy](../assets/FEA_open_source_sm.png)](https://github.com/orgs/Wolox/teams/front-end-army/members)

Wolox's default ESLint Typescript configuration

## Dependencies

We use [eslint](https://eslint.org/) as our linter.

Also, this configuration relies on some peer dependencies you must add in your project as dev dependencies:

- [eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import)
- [eslint-plugin-babel](https://github.com/babel/eslint-plugin-babel)
- [eslint-import-resolver-typescript](https://www.npmjs.com/package/eslint-import-resolver-typescript)
- [@typescript-eslint/parser](https://www.npmjs.com/package/@typescript-eslint/parser)
- [@typescript-eslint/eslint-plugin](https://www.npmjs.com/package/@typescript-eslint/eslint-plugin)

Make sure you check that the version you install in your project matches the one in this configuration's package.json

## Usage

To use this config, make your eslint config extend from this configuration:

```js
{
  // In case you want to use more than one config, you can compose it 
  // using an array of configurations instead of this string 
  "extends": "@wolox/eslint-config-typescript",
  "rules": {
    // You can override any rule here.
  }
}
```

Note that we use this configuration with [@wolox/eslint-config](../javascript). Although it is recommended to do so, it's not mandatory.
