# eslint-config-remarkable-lives

#### An ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) for [Remarkable Lives](https://remarkablelives.co.uk/)

## Install

```bash
yarn add eslint-config-remarkable-lives
```

## Usage

To use the Remarkable Lives shareable config, first run this:

```bash
yarn add -D eslint-config-standard eslint-plugin-standard eslint-plugin-promise eslint-plugin-import eslint-plugin-node
```

Then, add this to your .eslintrc file:

```
{
  "extends": "remarkable-lives"
}
```

*Note: the `eslint-config-` prefix was not added since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.

## License

MIT. Copyright (c) [Remarkable Lives](https://remarkablelives.co.uk/).
