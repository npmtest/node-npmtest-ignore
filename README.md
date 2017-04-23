# npmtest-ignore

#### basic test coverage for  [ignore (v3.2.7)](https://github.com/kaelzhang/node-ignore#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ignore.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ignore) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ignore.svg)](https://travis-ci.org/npmtest/node-npmtest-ignore)

#### Ignore is a manager and filter for .gitignore rules.

[![NPM](https://nodei.co/npm/ignore.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ignore)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ignore/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ignore/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ignore/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ignore/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ignore/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ignore/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ignore/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ignore/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ignore/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ignore/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ignore/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ignore/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ignore/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ignore/build/test-report.html](https://npmtest.github.io/node-npmtest-ignore/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ignore/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ignore/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ignore/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ignore/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ignore/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ignore/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ignore/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ignore/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "kael"
    },
    "bugs": {
        "url": "https://github.com/kaelzhang/node-ignore/issues"
    },
    "dependencies": {},
    "description": "Ignore is a manager and filter for .gitignore rules.",
    "devDependencies": {
        "chai": "~1.7.2",
        "codecov": "^1.0.1",
        "istanbul": "^0.4.5",
        "mocha": "~1.13.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4810ca5f1d8eca5595213a34b94f2eb4ed926bbd",
        "tarball": "https://registry.npmjs.org/ignore/-/ignore-3.2.7.tgz"
    },
    "files": [
        "ignore.js",
        "LICENSE-MIT"
    ],
    "gitHead": "cb06a8101172a17536ac318a979b30c2c5951ed8",
    "homepage": "https://github.com/kaelzhang/node-ignore#readme",
    "keywords": [
        "ignore",
        ".gitignore",
        "gitignore",
        "npmignore",
        "rules",
        "manager",
        "filter",
        "regexp",
        "regex",
        "fnmatch",
        "glob",
        "asterisks",
        "regular-expression"
    ],
    "license": "MIT",
    "main": "./ignore.js",
    "maintainers": [
        {
            "name": "kael"
        }
    ],
    "name": "ignore",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/kaelzhang/node-ignore.git"
    },
    "scripts": {
        "cov-report": "istanbul report",
        "test": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec ./test/ignore.js && codecov",
        "test-no-cov": "mocha --reporter spec ./test/ignore.js"
    },
    "version": "3.2.7",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
