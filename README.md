# deep-object-copy

A simple library to create a deep copy of JavaScript objects.

## Installation

```bash
npm install deep-object-copy
```

## Usage

```js
const deepCopy = require('deep-object-copy');
const original = { a: 1, b: { c: 2 } };
const copy = deepCopy(original);
console.log(copy); // { a: 1, b: { c: 2 } }
console.log(copy.b === original.b); // false
```

### LICENSED UNDER MIT LICENSE
