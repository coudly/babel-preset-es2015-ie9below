# babel-preset-es2015-ie9below

> Babel preset for all es2015 plugins, but loosely supports IE9 below IE browser(ie7, 8) [1]

| supported | plugin |
| ---------:| ------ |
|  &#x2714; | babel-plugin-transform-es2015-template-literals |
|  &#x2716; | babel-plugin-transform-es2015-literals |
|  &#x2714; | babel-plugin-transform-es2015-function-name |
|  &#x2714; | babel-plugin-transform-es2015-arrow-functions |
|  &#x2714; | babel-plugin-transform-es2015-block-scoped-functions |
|  &#x2716; | babel-plugin-transform-es2015-classes |
|  &#x2714; | babel-plugin-transform-es2015-object-super |
|  &#x2714; | babel-plugin-transform-es2015-shorthand-properties |
|  &#x2714; | babel-plugin-transform-es2015-computed-properties |
|  &#x2716; | babel-plugin-transform-es2015-for-of |
|  &#x2714; | babel-plugin-transform-es2015-sticky-regex |
|  &#x2714; | babel-plugin-transform-es2015-unicode-regex |
|  &#x2714; | babel-plugin-check-es2015-constants |
|  &#x2716; | babel-plugin-transform-es2015-spread |
|  &#x2714; | babel-plugin-transform-es2015-parameters |
|  &#x2714; | babel-plugin-transform-es2015-destructuring |
|  &#x2714; | babel-plugin-transform-es2015-block-scoping |
|  &#x2716; | babel-plugin-transform-es2015-typeof-symbol |
|  &#x2716; | babel-plugin-transform-es2015-modules-commonjs |
|  &#x2716; | babel-plugin-transform-regenerator |



## Install

```sh
$ npm install --save-dev babel-preset-es2015-ie9below
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-ie9below"]
}
```

### Via CLI

```sh
$ babel script.js --presets es2015-ie9below
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es2015-ie9below"]
});
```


[1] https://github.com/ouvens/ecmaScript-2015-babel-rules