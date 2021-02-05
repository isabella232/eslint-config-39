# @wolox/eslint-config-react

[![FEArmy](../assets/FEA_open_source_sm.png)](https://github.com/orgs/Wolox/teams/front-end-army/members)

Wolox's default ESLint React Native configuration

## Dependencies

We use [eslint](https://eslint.org/) as our linter and [prettier](https://github.com/prettier/prettier) as our code formatter

Also, this configuration relies on some peer dependencies you must add in your project as dev dependencies:

- [@react-native-community/eslint-config](https://www.npmjs.com/package/@react-native-community/eslint-config)
- [@typescript-eslint/parser](https://www.npmjs.com/package/@typescript-eslint/parser)
- [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react)
- [@wolox/eslint-config](../javascript)
- [eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier)
- [@typescript-eslint/eslint-plugin](https://www.npmjs.com/package/@typescript-eslint/eslint-plugin)
- [eslint-plugin-import](https://www.npmjs.com/package/eslint-plugin-import)
- [eslint-plugin-react-native](https://www.npmjs.com/package/eslint-plugin-react-native)

Make sure you check that the version you install in your project matches the one in this configuration's package.json

## Usage

To use this config, make your eslint config extend from this configuration:

```js
{
  // In case you want to use more than one config, you can compose it 
  // using an array of configurations instead of this string 
  "extends": "@wolox/eslint-config-react-native",
  "rules": {
    // You can override any rule here.
  }
}
```

Note that this configuration already extends [@wolox/eslint-config](../javascript), there's no need to do so in your projects
