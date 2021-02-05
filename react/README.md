# @wolox/eslint-config-react

Wolox's default ESLint React configuration

## Dependencies

We use [eslint](https://eslint.org/) as our linter and [prettier](https://github.com/prettier/prettier) as our code formatter

Also, this configuration relies on some peer dependencies you must add in your project as dev dependencies:

- [eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import)
- [eslint-plugin-jsx-a11y](https://github.com/jsx-eslint/eslint-plugin-jsx-a11y)
- [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react)
- [eslint-plugin-babel](https://github.com/babel/eslint-plugin-babel)
- [eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier)
- [eslint-plugin-react-hooks](https://github.com/facebook/react)

Make sure you check that the version you install in your project matches the one in this configuration's package.json

## Usage

To use this config, make your eslint config extend from this configuration:

```js
{
  // In case you want to use more than one config, you can compose it 
  // using an array of configurations instead of this string 
  "extends": "@wolox/eslint-config-react",
  "rules": {
    // You can override any rule here.
  }
}
```

Note that we use this configuration with [@wolox/eslint-config](../javascript). Although it is recommended to do so, it's not mandatory.
