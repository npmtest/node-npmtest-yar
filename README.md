# npmtest-yar

#### basic test coverage for  [yar (v8.1.2)](https://github.com/hapijs/yar#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-yar.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-yar) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-yar.svg)](https://travis-ci.org/npmtest/node-npmtest-yar)

#### Cookie jar plugin for Hapi

[![NPM](https://nodei.co/npm/yar.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yar)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-yar/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-yar/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-yar/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-yar/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-yar/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-yar/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-yar/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-yar/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-yar/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-yar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-yar/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-yar/build/test-report.html](https://npmtest.github.io/node-npmtest-yar/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-yar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-yar/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-yar/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yar/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yar/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-yar/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-yar/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/hapijs/yar/issues"
    },
    "dependencies": {
        "hoek": "4.x.x",
        "statehood": "5.x.x",
        "uuid": "3.x.x"
    },
    "description": "Cookie jar plugin for Hapi",
    "devDependencies": {
        "boom": "4.x.x",
        "code": "4.x.x",
        "hapi": "15.x.x",
        "lab": "11.x.x",
        "npmignore": "0.2.x"
    },
    "directories": {},
    "dist": {
        "shasum": "302912c2e01d0f3be1bf3ff3b5d3d1e215530700",
        "tarball": "https://registry.npmjs.org/yar/-/yar-8.1.2.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "42470f853a95bd5bac1190cf8f96f307cbbb2b15",
    "homepage": "https://github.com/hapijs/yar#readme",
    "keywords": [
        "hapi",
        "plugin",
        "cookies",
        "jar",
        "session"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse"
        },
        {
            "name": "markbradshaw"
        }
    ],
    "name": "yar",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/yar.git"
    },
    "scripts": {
        "test": "lab -a code -t 100 -L",
        "test-cov-html": "lab -a code -r html -o coverage.html",
        "update-npmignore": "npmignore"
    },
    "version": "8.1.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
