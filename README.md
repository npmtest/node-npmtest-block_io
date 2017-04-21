# npmtest-block_io

#### basic test coverage for  [block_io (v1.0.9-2)](https://github.com/BlockIo/block_io-nodejs)  [![npm package](https://img.shields.io/npm/v/npmtest-block_io.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-block_io) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-block_io.svg)](https://travis-ci.org/npmtest/node-npmtest-block_io)

#### Block.io API wrapper for node.js

[![NPM](https://nodei.co/npm/block_io.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/block_io)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-block_io/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-block_io/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-block_io/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-block_io/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-block_io/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-block_io/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-block_io/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-block_io/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-block_io/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-block_io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-block_io/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-block_io/build/test-report.html](https://npmtest.github.io/node-npmtest-block_io/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-block_io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-block_io/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-block_io/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-block_io/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-block_io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-block_io/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-block_io/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-block_io/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "block_io",
    "description": "Block.io API wrapper for node.js",
    "keywords": [
        "block.io",
        "block_io",
        "bitcoin",
        "litecoin",
        "dogecoin",
        "wallet"
    ],
    "version": "1.0.9-2",
    "preferGlobal": false,
    "homepage": "https://github.com/BlockIo/block_io-nodejs",
    "author": "Patrick Lodder <patrick.lodder@gmail.com> (https://github.com/patricklodder)",
    "repository": {
        "type": "git",
        "url": "git://github.com/BlockIo/block_io-nodejs.git"
    },
    "bugs": {
        "url": "https://github.com/BlockIo/block_io-nodejs/issues"
    },
    "directories": {
        "lib": "./lib"
    },
    "main": "./lib/block_io.js",
    "dependencies": {
        "request": "=2.79.0",
        "bigi": "=1.4.2",
        "bitcoinjs-lib": "=1.5.6",
        "pbkdf2-sha256": "=1.1.1"
    },
    "devDependencies": {
        "vows": "0.8.x"
    },
    "engines": {
        "node": ">=0.8",
        "npm": ">=1.0.0"
    },
    "scripts": {
        "test": "node_modules/.bin/vows --spec test/*.js"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/BlockIo/block_io-nodejs/raw/master/LICENSE"
        }
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
