# npmtest-cqrs-domain

#### basic test coverage for  [cqrs-domain (v2.5.7)](https://github.com/adrai/node-cqrs-domain)  [![npm package](https://img.shields.io/npm/v/npmtest-cqrs-domain.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cqrs-domain) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cqrs-domain.svg)](https://travis-ci.org/npmtest/node-npmtest-cqrs-domain)

#### Node-cqrs-domain is a node.js module based on node-eventstore. It can be very useful as domain component if you work with (d)ddd, cqrs, eventdenormalizer, host, etc.

[![NPM](https://nodei.co/npm/cqrs-domain.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cqrs-domain)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cqrs-domain/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cqrs-domain/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cqrs-domain/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cqrs-domain/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cqrs-domain/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cqrs-domain/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cqrs-domain/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cqrs-domain/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cqrs-domain/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cqrs-domain/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cqrs-domain/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cqrs-domain/build/test-report.html](https://npmtest.github.io/node-npmtest-cqrs-domain/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cqrs-domain/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cqrs-domain/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cqrs-domain/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cqrs-domain/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cqrs-domain/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cqrs-domain/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cqrs-domain/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cqrs-domain/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "adrai",
    "name": "cqrs-domain",
    "version": "2.5.7",
    "private": false,
    "main": "index.js",
    "engines": {
        "node": ">=0.8.0"
    },
    "directories": {
        "lib": "./lib"
    },
    "dependencies": {
        "async": "1.5.2",
        "debug": "2.6.0",
        "dotty": "0.0.2",
        "eventstore": "1.12.2",
        "jsondate": "0.0.1",
        "lodash": "4.17.4",
        "parent-require": "1.0.0",
        "tolerance": "1.0.0",
        "tv4": "1.2.7",
        "uuid": "3.0.1"
    },
    "devDependencies": {
        "azure-storage": ">=0.10.0",
        "cradle": ">=0.6.7",
        "eslint": ">=1.0.0",
        "expect.js": ">= 0.1.2",
        "mocha": ">= 1.0.1",
        "mongodb": ">= 0.0.1",
        "redis": ">= 0.10.1",
        "tingodb": ">= 0.0.1",
        "tv4-formats": ">=1.0.0"
    },
    "description": "Node-cqrs-domain is a node.js module based on node-eventstore. It can be very useful as domain component if you work with (d)ddd, cqrs, eventdenormalizer, host, etc.",
    "keywords": [
        "cqrs",
        "eventsourcing",
        "ddd",
        "dddd",
        "command",
        "event",
        "eventdenormalizer",
        "domain"
    ],
    "homepage": "https://github.com/adrai/node-cqrs-domain",
    "repository": {
        "type": "git",
        "url": "git@github.com:adrai/node-cqrs-domain.git"
    },
    "bugs": {
        "url": "https://github.com/adrai/node-cqrs-domain/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://raw.github.com/adrai/node-cqrs-domain/master/licence"
        }
    ],
    "scripts": {
        "test": "mocha test/unit && mocha test/integration"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
