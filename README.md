<div align="center">
  <h1>prettier-config</h1>
  <p>Boring Prettier Config</p>

  <div>
    <a href="https://github.com/boringcodes/prettier-config/commits" aria-label="Commitizen Friendly">
      <img src="https://img.shields.io/badge/commitizen-friendly-brightgreen.svg?style=flat-square">
    </a>
    <a href="https://github.com/boringcodes" aria-label="Code Style Prettier">
      <img src="https://img.shields.io/badge/code_style-prettier-brightgreen?style=flat-square">
    </a>
    <a href="https://github.com/boringcodes/prettier-config/actions" aria-label="GitHub Workflow Status">
      <img src="https://img.shields.io/github/workflow/status/boringcodes/prettier-config/publish-npm?style=flat-square">
    </a>
    <a href="https://david-dm.org/boringcodes/prettier-config" aria-label="Dependencies Status">
      <img src="https://img.shields.io/david/boringcodes/prettier-config?style=flat-square">
    </a>
    <a href="https://www.npmjs.com/package/@boringcodes/prettier-config" aria-label="NPM Version">
      <img src="https://img.shields.io/npm/v/@boringcodes/prettier-config?color=brightgreen&style=flat-square">
    </a>
    <a href="https://www.npmjs.com/package/@boringcodes/prettier-config" aria-label="NPM Downloads">
      <img src="https://img.shields.io/npm/dm/@boringcodes/prettier-config?style=flat-square">
    </a>
    <a href="https://github.com/boringcodes/prettier-config/blob/master/LICENSE" aria-label="MIT License">
      <img src="https://img.shields.io/github/license/boringcodes/prettier-config?color=brightgreen&style=flat-square">
    </a>
    <a href="https://github.com/boringcodes" aria-label="BoringCodes Verified">
      <img src="https://img.shields.io/badge/boringcodes-verified-brightgreen?style=flat-square">
    </a>
  </div>
</div>

## Installation

Use the package manager to install

```bash
yarn add @boringcodes/prettier-config --dev
```

## Usage

Create `.prettierrc` and add the content

```json
"@boringcodes/prettier-config"
```

Or if you want to extend the config, create `.prettierrc.js` instead

```javascript
const config = require('@boringcodes/prettier-config');

module.exports = {
  ...config,
  // TODO: add your prettier configs below
};
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Authors

[BoringCodes](https://github.com/boringcodes)

## License

[MIT](https://github.com/boringcodes/prettier-config/blob/master/LICENSE)
