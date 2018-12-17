# theme

The theme colors, variables, configs

## Install

`npm i @arrant/theme`

## Usage

### Colors

```js
const theme = require('@arrant/theme')

console.log(theme.colors[$color])
```

Supported colors -  [colors](https://github.com/arrant-org/theme/blob/master/lib/colors.js)

### Sizes

```js
const theme = require('@arrant/theme')

console.log(theme.sizes.small.width)
```

#### Variants

- small
- medium
- large

#### Properties

- min-width
- min-height
- font-size
- padding