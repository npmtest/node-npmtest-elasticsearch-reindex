# npmtest-elasticsearch-reindex

#### basic test coverage for  [elasticsearch-reindex (v1.1.15)](https://github.com/garbin/elasticsearch-reindex)  [![npm package](https://img.shields.io/npm/v/npmtest-elasticsearch-reindex.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-elasticsearch-reindex) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-elasticsearch-reindex.svg)](https://travis-ci.org/npmtest/node-npmtest-elasticsearch-reindex)

#### Elasticsearch reindex tool

[![NPM](https://nodei.co/npm/elasticsearch-reindex.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/elasticsearch-reindex)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-elasticsearch-reindex/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-elasticsearch-reindex/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-elasticsearch-reindex/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-elasticsearch-reindex/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-elasticsearch-reindex/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-elasticsearch-reindex/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-elasticsearch-reindex/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-elasticsearch-reindex/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-elasticsearch-reindex/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-elasticsearch-reindex/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-elasticsearch-reindex/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-elasticsearch-reindex/build/test-report.html](https://npmtest.github.io/node-npmtest-elasticsearch-reindex/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-elasticsearch-reindex/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-elasticsearch-reindex/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-elasticsearch-reindex/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-elasticsearch-reindex/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-elasticsearch-reindex/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-elasticsearch-reindex/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-elasticsearch-reindex/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-elasticsearch-reindex/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "elasticsearch-reindex",
    "version": "1.1.15",
    "description": "Elasticsearch reindex tool",
    "main": "index.js",
    "scripts": {
        "test": "npm test"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/garbin/elasticsearch-reindex.git"
    },
    "bin": {
        "elasticsearch-reindex": "./bin/elasticsearch-reindex.js"
    },
    "keywords": [
        "elasticsearch",
        "reindex",
        "tool"
    ],
    "author": "Garbin Huang <garbinh@gmail.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/garbin/elasticsearch-reindex/issues"
    },
    "homepage": "https://github.com/garbin/elasticsearch-reindex",
    "dependencies": {
        "agentkeepalive": "^3.0.0",
        "async": "^1.5.0",
        "bluebird": "^3.3.4",
        "bunyan": "^1.2.0",
        "commander": "^2.4.0",
        "elasticsearch": "^11.0.0",
        "event-emitter": "^0.3.1",
        "http-aws-es": "^1.1.3",
        "moment": "^2.8.3",
        "pace": "0.0.4",
        "progress": "^1.1.8",
        "underscore": "^1.7.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
