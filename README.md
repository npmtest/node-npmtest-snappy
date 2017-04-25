# npmtest-snappy

#### basic test coverage for  [snappy (v6.0.0)](https://github.com/kesla/node-snappy)  [![npm package](https://img.shields.io/npm/v/npmtest-snappy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-snappy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-snappy.svg)](https://travis-ci.org/npmtest/node-npmtest-snappy)

#### Nodejs bindings to Google's Snappy compression library

[![NPM](https://nodei.co/npm/snappy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/snappy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-snappy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-snappy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-snappy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-snappy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-snappy/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-snappy/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-snappy/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-snappy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-snappy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-snappy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-snappy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-snappy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-snappy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-snappy/build/test-report.html](https://npmtest.github.io/node-npmtest-snappy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-snappy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-snappy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-snappy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-snappy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-snappy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-snappy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-snappy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-snappy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Björklund"
    },
    "bugs": {
        "url": "https://github.com/kesla/node-snappy/issues"
    },
    "dependencies": {
        "bindings": "1.2.1",
        "nan": "2.4.0",
        "node-gyp": "3.4.0"
    },
    "description": "Nodejs bindings to Google's Snappy compression library",
    "devDependencies": {
        "ava": "^0.16.0",
        "bluebird": "^3.3.4",
        "nyc": "^8.3.0",
        "semistandard": "^9.0.0",
        "snazzy": "^5.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "43f6d17ae78f3e261c8e817dca183844ac5b4649",
        "tarball": "https://registry.npmjs.org/snappy/-/snappy-6.0.0.tgz"
    },
    "gitHead": "75f582408acb4d519237b93a9b03f6ef12617f33",
    "gypfile": true,
    "homepage": "https://github.com/kesla/node-snappy",
    "license": "MIT",
    "main": "snappy.js",
    "maintainers": [
        {
            "name": "kesla"
        }
    ],
    "name": "snappy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/kesla/node-snappy.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "nyc ava test.js && semistandard | snazzy"
    },
    "version": "6.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
