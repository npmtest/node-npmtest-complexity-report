# npmtest-complexity-report

#### test coverage for  [complexity-report (v1.4.1)](https://github.com/philbooth/complexity-report)  [![npm package](https://img.shields.io/npm/v/npmtest-complexity-report.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-complexity-report) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-complexity-report.svg)](https://travis-ci.org/npmtest/node-npmtest-complexity-report)

#### Software complexity analysis for JavaScript projects

[![NPM](https://nodei.co/npm/complexity-report.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/complexity-report)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-complexity-report/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-complexity-report/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-complexity-report/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-complexity-report/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-complexity-report/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-complexity-report/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-complexity-report/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-complexity-report/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-complexity-report/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-complexity-report/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-complexity-report/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-complexity-report/build/test-report.html](https://npmtest.github.io/node-npmtest-complexity-report/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-complexity-report/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-complexity-report/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-complexity-report/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-complexity-report/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-complexity-report/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-complexity-report/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-complexity-report/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-complexity-report/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Phil Booth"
    },
    "bin": {
        "cr": "./src/index.js"
    },
    "bugs": {
        "url": "https://github.com/philbooth/complexity-report/issues"
    },
    "contributors": [
        {
            "name": "Phil Booth",
            "url": "https://github.com/philbooth"
        },
        {
            "name": "Juzer Ali",
            "url": "https://github.com/juzerali"
        },
        {
            "name": "Mark Trostler",
            "url": "https://github.com/zzo"
        },
        {
            "name": "Wyatt Preul",
            "url": "https://github.com/wpreul"
        },
        {
            "name": "Rowan Manning",
            "url": "https://github.com/rowanmanning"
        },
        {
            "name": "Andrew Pennebaker",
            "url": "https://github.com/mcandre"
        },
        {
            "name": "Nils Kenneweg",
            "url": "https://github.com/nkenneweg"
        },
        {
            "name": "Eric Burin des Roziers",
            "url": "https://github.com/Ericbdr"
        },
        {
            "name": "Matt Field",
            "url": "https://github.com/mattfield"
        },
        {
            "name": "Addison Higham",
            "url": "https://github.com/addisonj"
        },
        {
            "name": "Daniel Kavassy",
            "url": "https://github.com/dkavassy"
        }
    ],
    "dependencies": {
        "async": "^0.9.0",
        "check-types": "2.1.x",
        "commander": "2.0.x",
        "escomplex": "1.2.x",
        "escomplex-coffee": "0.3.x",
        "escomplex-js": "1.2.x"
    },
    "description": "Software complexity analysis for JavaScript projects",
    "devDependencies": {
        "chai": "1.8.x",
        "jshint": "2.1.x",
        "mocha": "1.13.x"
    },
    "directories": {},
    "dist": {
        "shasum": "2d8416787ee128a0dbe57f3badd255442d094779",
        "tarball": "https://registry.npmjs.org/complexity-report/-/complexity-report-1.4.1.tgz"
    },
    "gitHead": "bcd3325a93d28dee2ed1461fdf9b208087690e23",
    "homepage": "https://github.com/philbooth/complexity-report",
    "keywords": [
        "complexity",
        "simplicity",
        "cyclomatic",
        "halstead",
        "maintainability",
        "static",
        "analysis",
        "metrics",
        "escomplex"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "philbooth"
        },
        {
            "name": "addisonj"
        }
    ],
    "name": "complexity-report",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/philbooth/complexity-report.git"
    },
    "scripts": {
        "lint": "./node_modules/jshint/bin/jshint src --config config/jshint.json",
        "test": "./node_modules/mocha/bin/mocha --ui tdd --reporter spec --colors test"
    },
    "version": "1.4.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
