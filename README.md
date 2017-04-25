# npmtest-stream-throttle

#### basic test coverage for  [stream-throttle (v0.1.3)](https://github.com/tjgq/node-stream-throttle)  [![npm package](https://img.shields.io/npm/v/npmtest-stream-throttle.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-stream-throttle) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-stream-throttle.svg)](https://travis-ci.org/npmtest/node-npmtest-stream-throttle)

#### A rate limiter for Node.js streams.

[![NPM](https://nodei.co/npm/stream-throttle.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/stream-throttle)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-stream-throttle/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-stream-throttle/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-stream-throttle/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-stream-throttle/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-stream-throttle/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-stream-throttle/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-stream-throttle/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-stream-throttle/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-stream-throttle/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-stream-throttle/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-stream-throttle/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-stream-throttle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-stream-throttle/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-stream-throttle/build/test-report.html](https://npmtest.github.io/node-npmtest-stream-throttle/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-stream-throttle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-stream-throttle/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-stream-throttle/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-stream-throttle/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stream-throttle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stream-throttle/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-stream-throttle/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-stream-throttle/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tiago Quelhas"
    },
    "bin": {
        "throttleproxy": "./bin/throttleproxy.js"
    },
    "bugs": {
        "url": "https://github.com/tjgq/node-stream-throttle/issues"
    },
    "contributors": [
        {
            "name": "Tiago Quelhas"
        }
    ],
    "dependencies": {
        "commander": "^2.2.0",
        "limiter": "^1.0.5"
    },
    "description": "A rate limiter for Node.js streams.",
    "devDependencies": {
        "async": "^0.6.2"
    },
    "directories": {},
    "dist": {
        "shasum": "add57c8d7cc73a81630d31cd55d3961cfafba9c3",
        "tarball": "https://registry.npmjs.org/stream-throttle/-/stream-throttle-0.1.3.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "homepage": "https://github.com/tjgq/node-stream-throttle",
    "keywords": [
        "streams",
        "throttling",
        "ratelimit"
    ],
    "license": "BSD-3-Clause",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "tjgq"
        }
    ],
    "name": "stream-throttle",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/tjgq/node-stream-throttle.git"
    },
    "scripts": {
        "test": "nodeunit test"
    },
    "version": "0.1.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
