# npmtest-send-data

#### basic test coverage for  [send-data (v8.0.0)](https://github.com/Raynos/send-data)  [![npm package](https://img.shields.io/npm/v/npmtest-send-data.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-send-data) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-send-data.svg)](https://travis-ci.org/npmtest/node-npmtest-send-data)

#### send data through response

[![NPM](https://nodei.co/npm/send-data.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/send-data)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-send-data/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-send-data/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-send-data/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-send-data/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-send-data/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-send-data/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-send-data/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-send-data/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-send-data/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-send-data/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-send-data/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-send-data/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-send-data/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-send-data/build/test-report.html](https://npmtest.github.io/node-npmtest-send-data/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-send-data/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-send-data/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-send-data/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-send-data/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-send-data/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-send-data/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-send-data/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-send-data/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Raynos"
    },
    "bugs": {
        "url": "https://github.com/Raynos/send-data/issues"
    },
    "contributors": [
        {
            "name": "Jake Verbaten"
        }
    ],
    "dependencies": {
        "json-stringify-safe": "^5.0.0",
        "xtend": "^4.0.0"
    },
    "description": "send data through response",
    "devDependencies": {
        "hammock": "^0.1.10",
        "hammock-request": "^2.1.0",
        "istanbul": "^0.3.5",
        "opn": "^1.0.1",
        "tape": "^3.4.0",
        "tern": "git://github.com/marijnh/tern.git",
        "test-server": "~0.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "8398ecc1fba49534757a8c17a48fa583caaaaeec",
        "tarball": "https://registry.npmjs.org/send-data/-/send-data-8.0.0.tgz"
    },
    "gitHead": "fc4126aa0ec5dac534930837a7b8c9ff0f0ea58b",
    "homepage": "https://github.com/Raynos/send-data",
    "keywords": [],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/Raynos/send-data/raw/master/LICENSE"
        }
    ],
    "main": "index",
    "maintainers": [
        {
            "name": "raynos"
        },
        {
            "name": "jwolski"
        }
    ],
    "name": "send-data",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Raynos/send-data.git"
    },
    "scripts": {
        "cover": "istanbul cover --print detail --report html -- test/index.js",
        "test": "node ./test/index.js",
        "view-cover": "opn coverage/index.html"
    },
    "version": "8.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
