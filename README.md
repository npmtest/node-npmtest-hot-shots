# npmtest-hot-shots

#### basic test coverage for  hot-shots (v4.4.0)  [![npm package](https://img.shields.io/npm/v/npmtest-hot-shots.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hot-shots) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hot-shots.svg)](https://travis-ci.org/npmtest/node-npmtest-hot-shots)

#### Node.js client for StatsD, DogStatsD, and Telegraf

[![NPM](https://nodei.co/npm/hot-shots.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hot-shots)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hot-shots/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hot-shots/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hot-shots/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hot-shots/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hot-shots/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hot-shots/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hot-shots/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hot-shots/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hot-shots/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hot-shots/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hot-shots/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hot-shots/build/test-report.html](https://npmtest.github.io/node-npmtest-hot-shots/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hot-shots/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hot-shots/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hot-shots/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hot-shots/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hot-shots/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hot-shots/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hot-shots/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hot-shots/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "hot-shots",
    "description": "Node.js client for StatsD, DogStatsD, and Telegraf",
    "version": "4.4.0",
    "author": "Steve Ivy",
    "contributors": [
        "Russ Bradberry <rbradberry@gmail.com>",
        "Brian Deitte <bdeitte@gmail.com>",
        "Mikhail Mazurskiy <mikhail.mazursky@gmail.com>"
    ],
    "keywords": [
        "statsd",
        "dogstatsd",
        "datadog",
        "metrics",
        "telegraf"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/brightcove/hot-shots.git"
    },
    "bugs": {
        "url": "https://github.com/brightcove/hot-shots/issues"
    },
    "directories": {
        "lib": "./lib/"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "scripts": {
        "test": "mocha -R spec",
        "lint": "jshint lib/**.js test/**.js",
        "pretest": "npm run lint"
    },
    "dependencies": {},
    "devDependencies": {
        "jshint": "2.x",
        "mocha": "2.x"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
