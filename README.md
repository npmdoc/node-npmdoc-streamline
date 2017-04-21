# npmdoc-streamline

#### api documentation for  [streamline (v2.0.19)](http://github.com/Sage/streamlinejs)  [![npm package](https://img.shields.io/npm/v/npmdoc-streamline.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-streamline) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-streamline.svg)](https://travis-ci.org/npmdoc/node-npmdoc-streamline)

#### Asynchronous Javascript for dummies

[![NPM](https://nodei.co/npm/streamline.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/streamline)

- [https://npmdoc.github.io/node-npmdoc-streamline/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-streamline/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-streamline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-streamline/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-streamline/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-streamline/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "streamline",
    "description": "Asynchronous Javascript for dummies",
    "version": "2.0.19",
    "license": "MIT",
    "homepage": "http://github.com/Sage/streamlinejs",
    "author": "Bruno Jouhier",
    "repository": {
        "type": "git",
        "url": "git://github.com/Sage/streamlinejs.git"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "dependencies": {
        "babel-core": "^6.3.26",
        "babel-plugin-streamline": "^2.0.19",
        "babel-preset-es2015": "^6.3.13",
        "colors": "^1.1.2",
        "commander": "^2.8.1",
        "source-map-support": "git+https://github.com/Sage/node-source-map-support#catch-missing-sourcemap-element",
        "streamline-runtime": "^1.0.17",
        "typescript": "^2.0.0"
    },
    "optionalDependencies": {
        "fibers": "^1.0.6"
    },
    "devDependencies": {
        "babelify": "^7.2.0",
        "browserify": "^12.0.1",
        "qunit": "git+https://github.com/Sage/node-qunit.git#sage",
        "uglifyify": "^3.0.4"
    },
    "bin": {
        "_node": "./bin/_node",
        "_coffee": "./bin/_coffee"
    },
    "preferGlobal": true,
    "scripts": {
        "prepublish": "node build.js || nodejs build.js",
        "test": "node test"
    },
    "main": "index.js"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
