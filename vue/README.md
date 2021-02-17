# @wolox/eslint-config-vue

[![FEArmy](../assets/FEA_open_source_sm.png)](https://github.com/orgs/Wolox/teams/front-end-army/members)

Wolox's default ESLint Vue configuration

## Dependencies

We use [eslint](https://eslint.org/) as our linter and [prettier](https://github.com/prettier/prettier) as our code formatter

Also, this configuration relies on some peer dependencies you must add in your project as dev dependencies:

- [eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier)
- [eslint-plugin-vue](https://github.com/vuejs/eslint-plugin-vue)

Make sure you check that the version you install in your project matches the one in this configuration's package.json

## Usage

To use this config, make your eslint config extend from this configuration:

```js
{
  // In case you want to use more than one config, you can compose it 
  // using an array of configurations instead of this string 
  "extends": "@wolox/eslint-config-vue",
  "rules": {
    // You can override any rule here.
  }
}
```

Note that we use this configuration with [@wolox/eslint-config](../javascript). Although it is recommended to do so, it's not mandatory.
