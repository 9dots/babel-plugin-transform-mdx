# babel-plugin-transform-mdx

Turn MDX into function calls

## Installation

```sh
$ npm install babel-plugin-transform-mdx
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```js
// without options
{
  "plugins": ["transform-mdx"]
}
// with options
{
  "plugins": [
    ["transform-mdx", {
      "pragma": "element"
    }]
  ]
}
```

### Via CLI

```sh
$ babel --plugins transform-mdx script.js
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  plugins: ["transform-mdx"]
});
```
