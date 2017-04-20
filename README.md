# npmdoc-depd

#### api documentation for  depd (v1.1.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-depd.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-depd) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-depd.svg)](https://travis-ci.org/npmdoc/node-npmdoc-depd)

#### Deprecate all the things

[![NPM](https://nodei.co/npm/depd.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/depd)

- [https://npmdoc.github.io/node-npmdoc-depd/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-depd/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-depd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-depd/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-depd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-depd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "depd",
    "description": "Deprecate all the things",
    "version": "1.1.0",
    "author": "Douglas Christopher Wilson <doug@somethingdoug.com>",
    "license": "MIT",
    "keywords": [
        "deprecate",
        "deprecated"
    ],
    "repository": "dougwilson/nodejs-depd",
    "browser": "lib/browser/index.js",
    "devDependencies": {
        "benchmark": "1.0.0",
        "beautify-benchmark": "0.2.4",
        "istanbul": "0.3.5",
        "mocha": "~1.21.5"
    },
    "files": [
        "lib/",
        "History.md",
        "LICENSE",
        "index.js",
        "Readme.md"
    ],
    "engines": {
        "node": ">= 0.6"
    },
    "scripts": {
        "bench": "node benchmark/index.js",
        "test": "mocha --reporter spec --bail test/",
        "test-ci": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --no-exit test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot test/"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
