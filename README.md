# mso-properties

NPM package of all MSO CSS properties


## Installation

```sh
npm install @useparcel/mso-properties
```

## Usage


```js
const msoProperties = require('@useparcel/mso-properties')

// ... your code here
```

## The data 

The package contains an array of objects.

Each object has the following attributes:

* `property` - Name of the CSS property.
* `values` - Array of valid values.
* `default` - The default value. If there is no default, it is set to null.
* `inherits` - Whether the value is inherited from parents.