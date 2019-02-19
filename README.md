# get-random-values
Cross browser and node.js implementation to generate random values.

Either uses:

  - window.crypto
  - window.msCrypto
  - node crypto

if it exists, otherwise throws.

## Example

``` javascript
import getRandomValues from 'get-random-values';

const array = getRandomValues(new Uint32Array(4));
// [9, 50, 194, 143]
```

## Installation

``` bash
npm install github:ProtonMail/get-random-values.git#semver:^1.0.0
```
