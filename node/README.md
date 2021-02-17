# @wolox/eslint-config-node

Linter configuration that specifies the specific [practices](https://github.com/arinaldi118/documentacion/blob/master/standards.md) established for Wolox NodeJS proyects. It's mostly used to extend [@wolox/eslint-config](../javascript), but it's not necessary to do so.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## About

This project is maintained by [Wolox](https://github.com/wolox) and it was written by [Wolox](http://www.wolox.com.ar).

![Wolox](https://raw.githubusercontent.com/Wolox/press-kit/master/logos/logo_banner.png)

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
  // using an array of configurations instead of this string, for example:
  // "extends": ["@wolox/eslint-config", "@wolox/eslint-config-node"]
  "extends": "@wolox/eslint-config-node",
  "rules": {
    // You can override any rule here.
  }
}
```
