# npmtest-rule-reactor

#### basic test coverage for  [rule-reactor (v0.1.10)](https://github.com/anywhichway/rule-reactorl#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-rule-reactor.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rule-reactor) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rule-reactor.svg)](https://travis-ci.org/npmtest/node-npmtest-rule-reactor)

#### A light weight, fast, expressive forward chaining business rule engine leveraging JavaScript internals, lazy cross-products, and Functions as objects rather than Rete.

[![NPM](https://nodei.co/npm/rule-reactor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rule-reactor)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rule-reactor/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rule-reactor/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rule-reactor/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rule-reactor/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rule-reactor/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rule-reactor/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rule-reactor/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rule-reactor/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rule-reactor/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rule-reactor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rule-reactor/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rule-reactor/build/test-report.html](https://npmtest.github.io/node-npmtest-rule-reactor/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rule-reactor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rule-reactor/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rule-reactor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rule-reactor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rule-reactor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rule-reactor/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rule-reactor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rule-reactor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Simon Y. Blackwell",
        "url": "http://www.github.com/anywhichway"
    },
    "bugs": {
        "url": "https://github.com/anywhichway/rule-reactor/issues"
    },
    "client": "./browser/rule-reactor.js",
    "dependencies": {
        "uuid": "^2.0.1"
    },
    "description": "A light weight, fast, expressive forward chaining business rule engine leveraging JavaScript internals, lazy cross-products, and Functions as objects rather than Rete.",
    "devDependencies": {
        "bluebird": "^3.3.5",
        "browserify": "^13.0.0",
        "chai": "^3.4.1",
        "codacy-coverage": "^2.0.0",
        "codeclimate-test-reporter": "^0.2.0",
        "istanbul": "^0.4.2",
        "minify": "^2.0.8",
        "mocha": "^2.3.4"
    },
    "directories": {},
    "dist": {
        "shasum": "5d97c751c097a35bc78baf0065248b23e1de304a",
        "tarball": "https://registry.npmjs.org/rule-reactor/-/rule-reactor-0.1.10.tgz"
    },
    "gitHead": "f7f43c1d5355adab959d459e3c9bcd612c1b41b4",
    "homepage": "https://github.com/anywhichway/rule-reactorl#readme",
    "isomorphic": true,
    "keywords": [
        "Rete",
        "business rules",
        "BRML",
        "expert system",
        "nools",
        "drools",
        "rule based",
        "rule engine",
        "PHREAK",
        "TREAT"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "anywhichway"
        }
    ],
    "name": "rule-reactor",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/anywhichway/rule-reactor.git"
    },
    "reveal": true,
    "scripts": {
        "browserify": "browserify index.js -o browser/rule-reactor.js",
        "minify": "minify browser/rule-reactor.js > browser/rule-reactor.min.js",
        "prepublish": "npm run browserify && npm run minify",
        "test": "keys.bat && istanbul cover node_modules/mocha/bin/_mocha --report lcov -- -R spec && cat coverage/lcov.info | node_modules\\.bin\\codacy-coverage && rm -rf coverage"
    },
    "version": "0.1.10",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
