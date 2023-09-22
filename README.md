# Rollup Tailwind

Bundle Tailwind CSS Stylesheet as a [Rollup](https://rollupjs.org) asset.

---------------------------------------------------------------------------------

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

## Installation

Install @logiclabs/rollup-tailwind with npm

```bash
npm i -D @logiclabs/rollup-tailwind # yarn add -D @logiclabs/rollup-tailwind
```
    
## Usage/Examples

```javascript
//rollup.config.js
import tailwind from 'rollup-plugin-tailwind';

export default {
  ...
  plugins: [
    tailwind({
      input: path/to/entry.css,
      ...
      // Tailor the emitted stylesheet to the bundle by removing any unused css
      // (hightly recommended when packaging for distribution).
      purge: false,
    }),
  ],
  ...
};
```


## Contributing

Contributions are always welcome!

## Running Tests

To run tests, run the following command

```bash
  npm run test
```


## Feedback

If you have any feedback, please reach out to us at fake@fake.com


## Authors

- [@developerwithout](https://www.github.com/developerwithout)


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Acknowledgements

- Inspired by [rollup-plugin-tailwindcss](https://www.npmjs.com/package/rollup-plugin-tailwindcss)
    - created by [@Henry-Pulver](https://github.com/Henry-Pulver)