# my-npm-package


A simple utility package with functions to check if a number is even or odd and to calculate the square of a number.

## Installation

```bash
npm install basic-helpers
```
## Usage

```bash
const { isEven, isOdd, square } = require('basic-helpers');

console.log(isEven(4));   // Output: true
console.log(isOdd(7));    // Output: true
console.log(square(3));   // Output: 9
```

## Functions
```
isEven(num): Returns true if the given number is even, false otherwise.
isOdd(num): Returns true if the given number is odd, false otherwise.
square(num): Returns the square of the given number.
```
