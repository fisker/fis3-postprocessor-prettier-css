fis3-postprocessor-prettier-css
a code formatter of fis3 based on prettier

[![npm](https://img.shields.io/npm/v/fis3-postprocessor-prettier-css.svg?style=flat-square)](https://www.npmjs.com/package/fis3-postprocessor-prettier-css) 
[![npm](https://img.shields.io/npm/dt/fis3-postprocessor-prettier-css.svg?style=flat-square)](https://www.npmjs.com/package/fis3-postprocessor-prettier-css) 
[![npm](https://img.shields.io/npm/dm/fis3-postprocessor-prettier-css.svg?style=flat-square)](https://www.npmjs.com/package/fis3-postprocessor-prettier-css)

## usage

    $ npm i -g fis3-postprocessor-prettier-css

```
// fis-conf.js
var options = {};

fis.match('*.css', {
  postprocessor: fis.plugin('prettier-css', options)
});
```

## config 
https://github.com/prettier/prettier#options

both options && Configuration File are supported.

## links
fis3: [http://fis.baidu.com/]

prettier: [https://github.com/prettier/prettier]
