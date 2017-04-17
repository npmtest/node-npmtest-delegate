# test coverage for  [delegate (v3.1.2)](https://github.com/zenorocha/delegate#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-delegate.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-delegate) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-delegate.svg)](https://travis-ci.org/npmtest/node-npmtest-delegate)
#### Lightweight event delegation

[![NPM](https://nodei.co/npm/delegate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/delegate)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-delegate/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-delegate/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-delegate/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-delegate/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-delegate/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-delegate/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-delegate/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-delegate/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-delegate/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-delegate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-delegate/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-delegate/build/test-report.html](https://npmtest.github.io/node-npmtest-delegate/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-delegate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-delegate/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-delegate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-delegate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-delegate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-delegate/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-delegate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-delegate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/zenorocha/delegate/issues"
    },
    "dependencies": {},
    "description": "Lightweight event delegation",
    "devDependencies": {
        "browserify": "^13.1.0",
        "chai": "^3.5.0",
        "karma": "^1.3.0",
        "karma-browserify": "^5.1.0",
        "karma-chai": "^0.1.0",
        "karma-mocha": "^1.2.0",
        "karma-phantomjs-launcher": "^1.0.2",
        "karma-sinon": "^1.0.4",
        "mocha": "^3.1.2",
        "phantomjs-polyfill": "0.0.2",
        "simulant": "^0.2.2",
        "sinon": "^1.17.6"
    },
    "directories": {},
    "dist": {
        "shasum": "1e1bc6f5cadda6cb6cbf7e6d05d0bcdd5712aebe",
        "tarball": "https://registry.npmjs.org/delegate/-/delegate-3.1.2.tgz"
    },
    "gitHead": "dc4abc8b2ac96aaa006bf2ab702513b54a77c067",
    "homepage": "https://github.com/zenorocha/delegate#readme",
    "keywords": [
        "event",
        "delegate",
        "delegation"
    ],
    "license": "MIT",
    "main": "src/delegate.js",
    "maintainers": [
        {
            "name": "zenorocha"
        }
    ],
    "name": "delegate",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zenorocha/delegate.git"
    },
    "scripts": {
        "build": "browserify src/delegate.js -s delegate -o dist/delegate.js",
        "test": "karma start --single-run"
    },
    "version": "3.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
