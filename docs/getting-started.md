# SwordCSS

> A powerful CSS compiler

## Installation

```
$ npm install swordcss
# or with yarn
$ yarn add swordcss
```

## Usage

```js
const SwordCSS = require("swordcss");

// Create a SwordCSS instance
const sword = SwordCSS();

// Compile CSS
sword.compile(
    ".all-elem {width: 100%; height: 100%;} #elem {sw-class: all-elem;}"
);
```