# npmdoc-node.io

#### api documentation for  [node.io (v0.5.1)](http://github.com/chriso/node.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-node.io.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node.io) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node.io.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node.io)

#### A distributed data scraping and processing framework

[![NPM](https://nodei.co/npm/node.io.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node.io)

- [https://npmdoc.github.io/node-npmdoc-node.io/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node.io/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node.io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node.io/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node.io/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node.io/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node.io",
    "description": "A distributed data scraping and processing framework",
    "version": "0.5.1",
    "homepage": "http://github.com/chriso/node.io",
    "keywords": [
        "data",
        "mapreduce",
        "map",
        "reduce",
        "scraping",
        "html",
        "parsing",
        "parse",
        "scrape",
        "process",
        "processing",
        "data"
    ],
    "author": "Chris O'Hara <cohara87@gmail.com>",
    "main": "./lib/node.io",
    "directories": {
        "lib": "./lib/node.io"
    },
    "bugs": {
        "mail": "cohara87@gmail.com",
        "url": "http://github.com/chriso/node.io/issues"
    },
    "repository": {
        "type": "git",
        "url": "http://github.com/chriso/node.io.git"
    },
    "engines": {
        "node": ">=0.4.0"
    },
    "preferGlobal": true,
    "dependencies": {
        "htmlparser": ">= 1.7.3",
        "coffee-script": ">= 0.9.5",
        "jquery": ">= 1.4.4",
        "jsdom": ">= 0.2.0",
        "request": "2.9.202",
        "sigmund": ">= 1.0.0"
    },
    "devDependencies": {
        "expresso": "*"
    },
    "bin": {
        "io": "./bin/io",
        "node.io": "./bin/node.io",
        "node.io-web": "./bin/node.io-web"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/chriso/node.io/raw/master/LICENSE"
        }
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
