# npmdoc-naught

#### api documentation for  naught (v1.6.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-naught.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-naught) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-naught.svg)](https://travis-ci.org/npmdoc/node-npmdoc-naught)

#### zero downtime deployment for your node.js server

[![NPM](https://nodei.co/npm/naught.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/naught)

- [https://npmdoc.github.io/node-npmdoc-naught/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-naught/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-naught/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-naught/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-naught/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-naught/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "naught",
    "version": "1.6.0",
    "description": "zero downtime deployment for your node.js server",
    "keywords": [
        "deploy",
        "unicorn",
        "forever",
        "cluster",
        "daemon",
        "daemonize"
    ],
    "scripts": {
        "test": "node test/test.js"
    },
    "bin": {
        "naught": "./lib/main.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/andrewrk/naught"
    },
    "author": "Andrew Kelley",
    "license": "MIT",
    "engines": {
        "node": ">=0.10.20"
    },
    "devDependencies": {
        "ncp": "~2.0.0",
        "rimraf": "~2.4.0",
        "whynoteq": "~1.0.2"
    },
    "dependencies": {
        "mkdirp": "~0.5.1",
        "pend": "~1.2.0"
    },
    "bugs": {
        "url": "https://github.com/andrewrk/naught/issues"
    },
    "directories": {
        "test": "test"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
