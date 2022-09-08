# Sweetsky tailwind package for WorkAdventure

A style for WorkAdventure

## Getting started

### Install

Install with yarn:
```
yarn add @workadventure/sweetsky
```

Install with npm
```
npm install @workadventure/sweetsky
```

### Scss import

Scss import in your index.scss
```scss
    ...
    @import '@workadventure-test/sweetsky/style/index.scss';
    ...
```

OR

Css import in your index.scss
```css
    ...
    @import '@workadventure-test/sweetsky/sweetsky.min.css';
    ...
```
### Tailwind configuration

Tailwind configuration in your file `tailwind.config.js`
```js
const defaultTheme = require('@workadventure-test/sweetsky/tailwind.config.js');
module.exports = defaultTheme;
```

OR

Tailwind configuration in your file `tailwind.config.cjs`
```js
const defaultTheme = require('@workadventure-test/sweetsky/tailwind.config.cjs');
module.exports = defaultTheme;
```

### Postcss configuration

Postcss configuration in your file `postcss.config.js`
```js
const defaultPostcssConfig = require('@workadventure-test/sweetsky/postcss.config.js');
module.exports = defaultPostcssConfig;
```


