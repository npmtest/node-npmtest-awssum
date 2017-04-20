# npmtest-awssum

#### basic test coverage for  [awssum (v1.2.0)](http://awssum.io/)  [![npm package](https://img.shields.io/npm/v/npmtest-awssum.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-awssum) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-awssum.svg)](https://travis-ci.org/npmtest/node-npmtest-awssum)

#### NodeJS module to aid talking to Web Service APIs. Requires plugins.

[![NPM](https://nodei.co/npm/awssum.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/awssum)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-awssum/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-awssum/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-awssum/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-awssum/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-awssum/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-awssum/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-awssum/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-awssum/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-awssum/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-awssum/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-awssum/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-awssum/build/test-report.html](https://npmtest.github.io/node-npmtest-awssum/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-awssum/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-awssum/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-awssum/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-awssum/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-awssum/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-awssum/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-awssum/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-awssum/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrew Chilton",
        "url": "http://chilts.org/"
    },
    "bugs": {
        "url": "https://github.com/awssum/awssum/issues"
    },
    "contributors": [
        {
            "name": "Giannis Kosmas",
            "url": "https://github.com/kosmasgiannis"
        }
    ],
    "dependencies": {
        "underscore": "1.4.x",
        "xml2js": "0.2.x"
    },
    "description": "NodeJS module to aid talking to Web Service APIs. Requires plugins.",
    "devDependencies": {
        "tape": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "6bf4336594185d76d06d9f515b13b7c874d56a04",
        "tarball": "https://registry.npmjs.org/awssum/-/awssum-1.2.0.tgz"
    },
    "engines": {
        "node": ">= 0.6.0"
    },
    "homepage": "http://awssum.io/",
    "keywords": [
        "api",
        "apis",
        "webapi",
        "client"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/awssum/awssum/raw/master/LICENSE"
        }
    ],
    "main": "awssum.js",
    "maintainers": [
        {
            "name": "chilts"
        }
    ],
    "name": "awssum",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/awssum/awssum.git"
    },
    "scripts": {
        "test": "set -e; find test/ -name '*.js' -exec echo --- {} --- ';' -exec node {} ';'"
    },
    "version": "1.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
