# STD-ENV

Detect running environment of the current Node.js process.

## Installation

Using yarn:

```
yarn add std-env
```

Usin npm:

```
npm i std-env
```

## Usage

```js
cost env = require('std-env')

console.log(env)

/*
{
  test: false,
  dev: false,
  production: false,
  debug: false,
  ci: false,
  tty: true,
  minimalCLI: false
}
*/
```

## License

MIT
