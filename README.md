# Assert Is Equal Uint32Array

![GitHub Release](https://img.shields.io/github/release/Jemma0529/assert-is-equal-uint32array.svg) ![GitHub Issues](https://img.shields.io/github/issues/Jemma0529/assert-is-equal-uint32array.svg) ![GitHub Stars](https://img.shields.io/github/stars/Jemma0529/assert-is-equal-uint32array.svg)

## Overview

Welcome to the **Assert Is Equal Uint32Array** repository! This project provides a simple utility to test if two arguments are both `Uint32Arrays` and if they contain equal values. This function is essential for developers working with typed arrays in JavaScript, particularly in Node.js environments.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [API](#api)
5. [Examples](#examples)
6. [Contributing](#contributing)
7. [License](#license)
8. [Releases](#releases)

## Features

- **Type Checking**: Ensure both inputs are `Uint32Arrays`.
- **Value Comparison**: Check if the arrays have the same values.
- **Lightweight**: Minimal dependencies for quick integration.
- **Node.js Compatibility**: Works seamlessly in Node.js environments.

## Installation

To install the package, you can use npm or yarn. Run one of the following commands in your terminal:

```bash
npm install assert-is-equal-uint32array
```

or

```bash
yarn add assert-is-equal-uint32array
```

## Usage

After installation, you can import the utility into your project. Here’s how to do it:

```javascript
const assertIsEqualUint32Array = require('assert-is-equal-uint32array');
```

Now you can use the function to compare two `Uint32Arrays`.

## API

### `assertIsEqualUint32Array(arr1, arr2)`

- **Parameters**:
  - `arr1` - The first `Uint32Array` to compare.
  - `arr2` - The second `Uint32Array` to compare.

- **Returns**: `true` if both arrays are equal, `false` otherwise.

### Example

```javascript
const arr1 = new Uint32Array([1, 2, 3]);
const arr2 = new Uint32Array([1, 2, 3]);
const arr3 = new Uint32Array([4, 5, 6]);

console.log(assertIsEqualUint32Array(arr1, arr2)); // true
console.log(assertIsEqualUint32Array(arr1, arr3)); // false
```

## Examples

Here are a few more examples to illustrate how the utility works.

### Example 1: Equal Arrays

```javascript
const a = new Uint32Array([10, 20, 30]);
const b = new Uint32Array([10, 20, 30]);

console.log(assertIsEqualUint32Array(a, b)); // true
```

### Example 2: Unequal Arrays

```javascript
const a = new Uint32Array([1, 2, 3]);
const b = new Uint32Array([1, 2, 4]);

console.log(assertIsEqualUint32Array(a, b)); // false
```

### Example 3: Different Types

```javascript
const a = new Uint32Array([1, 2, 3]);
const b = [1, 2, 3]; // Not a Uint32Array

console.log(assertIsEqualUint32Array(a, b)); // false
```

## Contributing

We welcome contributions to this project! If you would like to help, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Write tests for your changes.
5. Submit a pull request.

Please ensure that your code adheres to the existing style and includes relevant tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

To view the latest releases, please visit the [Releases](https://github.com/Jemma0529/assert-is-equal-uint32array/releases) section. You can download the latest version from there and follow the instructions to integrate it into your project.

## Conclusion

Thank you for checking out the **Assert Is Equal Uint32Array** repository! We hope this utility helps you with your JavaScript projects. If you have any questions or suggestions, feel free to open an issue or submit a pull request.

For more information on releases, please visit the [Releases](https://github.com/Jemma0529/assert-is-equal-uint32array/releases) page.