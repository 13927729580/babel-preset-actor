# babel-preset-actor

Babel preset for Actor web applications

## Install

```sh
$ npm install --save-dev babel-preset-actor
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["actor"]
}
```

### Via CLI

```sh
$ babel script.js --presets actor
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["actor"]
})
```
