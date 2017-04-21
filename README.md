# npmtest-jingo

#### basic test coverage for  jingo (v1.7.3)  [![npm package](https://img.shields.io/npm/v/npmtest-jingo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jingo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jingo.svg)](https://travis-ci.org/npmtest/node-npmtest-jingo)

#### A nodejs based wiki engine

[![NPM](https://nodei.co/npm/jingo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jingo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jingo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jingo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jingo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jingo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jingo/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jingo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jingo/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jingo/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jingo/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jingo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jingo/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jingo/build/test-report.html](https://npmtest.github.io/node-npmtest-jingo/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jingo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jingo/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jingo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jingo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jingo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jingo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jingo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jingo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jingo",
    "version": "1.7.3",
    "description": "A nodejs based wiki engine",
    "author": "Claudio Cicali <claudio.cicali@gmail.com>",
    "keywords": [
        "wiki",
        "git",
        "engine",
        "gollum",
        "cms",
        "markdown"
    ],
    "standard": {
        "ignore": [
            "/public/vendor/"
        ],
        "globals": [
            "expect",
            "describe",
            "Git",
            "sinon",
            "chai"
        ]
    },
    "main": "jingo",
    "bin": {
        "jingo": "./jingo"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/claudioc/jingo"
    },
    "directories": {
        "lib": "./lib/"
    },
    "dependencies": {
        "bluebird": "^2.3.11",
        "body-parser": "^1.10.0",
        "commander": "^2.5.1",
        "cookie-parser": "^1.3.3",
        "cookie-session": "^1.1.0",
        "cors": "^2.7.1",
        "ecstatic": "0.4.x",
        "express": "^4.10.6",
        "express-flash": "0.0.2",
        "express-session": "^1.9.3",
        "express-validator": "^2.7.0",
        "gravatar": "^1.1.0",
        "jade": "*",
        "js-yaml": "^3.1.0",
        "lodash": "^2.4.1",
        "markdown-toc": "^0.11.7",
        "marked": "^0.3.5",
        "method-override": "^2.3.0",
        "morgan": "^1.5.0",
        "node-syntaxhighlighter": "*",
        "passport": "^0.2.0",
        "passport-github": "^0.1.5",
        "passport-google-oauth": "^0.1.5",
        "passport-local": "^1.0.0",
        "semver": "^2.3.2",
        "serve-favicon": "^2.1.7",
        "transliteration": "^0.1.1"
    },
    "devDependencies": {
        "chai": "*",
        "mocha": "*",
        "nodemon": "^1.10.2",
        "sinon": "^1.10.3"
    },
    "scripts": {
        "test": "mocha test/spec",
        "start": "./jingo -c config.yaml",
        "start-dev": "nodemon ./jingo -c config.yaml"
    },
    "engines": {
        "node": ">=0.8",
        "npm": ">=1.1"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
