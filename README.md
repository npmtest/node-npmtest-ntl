# npmtest-ntl

#### basic test coverage for  [ntl (v1.2.0)](https://github.com/ruyadorno/ntl#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ntl.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ntl) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ntl.svg)](https://travis-ci.org/npmtest/node-npmtest-ntl)

#### Npm Task List: Interactive cli menu to list/run npm tasks

[![NPM](https://nodei.co/npm/ntl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ntl)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ntl/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ntl/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ntl/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ntl/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ntl/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ntl/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ntl/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ntl/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ntl/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ntl/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ntl/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ntl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ntl/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ntl/build/test-report.html](https://npmtest.github.io/node-npmtest-ntl/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ntl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ntl/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ntl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ntl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ntl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ntl/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ntl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ntl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ruy Adorno",
        "url": "http://ruyadorno.com"
    },
    "ava": {
        "files": [
            "test/index.js"
        ],
        "tap": true,
        "verbose": true
    },
    "bin": {
        "ntl": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/ruyadorno/ntl/issues"
    },
    "dependencies": {
        "inquirer": "^0.12.0",
        "minimist": "^1.2.0",
        "pkginfo": "~0.3.1"
    },
    "description": "Npm Task List: Interactive cli menu to list/run npm tasks",
    "devDependencies": {
        "ava": "^0.11.0",
        "tempdir": "^1.0.0",
        "tempfile": "^1.1.1",
        "xo": "^0.12.1"
    },
    "directories": {},
    "dist": {
        "shasum": "40ae664e04e607f7d04b1b5f609c0b831e6914a3",
        "tarball": "https://registry.npmjs.org/ntl/-/ntl-1.2.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js",
        "cli.js"
    ],
    "gitHead": "bcac2d31da966cb2a1f8a474c553317c174aa4e6",
    "homepage": "https://github.com/ruyadorno/ntl#readme",
    "keywords": [
        "npm",
        "task",
        "list",
        "interactive",
        "inquirer",
        "cli-app",
        "cli",
        "ntl",
        "runner",
        "menu"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "ruyadorno"
        }
    ],
    "name": "ntl",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ruyadorno/ntl.git"
    },
    "scripts": {
        "pretest": "xo",
        "test": "ava"
    },
    "version": "1.2.0",
    "xo": {
        "rules": {
            "consistent-return": 0
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
