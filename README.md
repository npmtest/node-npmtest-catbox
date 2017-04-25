# npmtest-catbox

#### basic test coverage for  [catbox (v7.1.3)](https://github.com/hapijs/catbox#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-catbox.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-catbox) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-catbox.svg)](https://travis-ci.org/npmtest/node-npmtest-catbox)

#### Multi-strategy object caching service

[![NPM](https://nodei.co/npm/catbox.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/catbox)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-catbox/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-catbox/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-catbox/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-catbox/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-catbox/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-catbox/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-catbox/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-catbox/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-catbox/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-catbox/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-catbox/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-catbox/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-catbox/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-catbox/build/test-report.html](https://npmtest.github.io/node-npmtest-catbox/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-catbox/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-catbox/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-catbox/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-catbox/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-catbox/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-catbox/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-catbox/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-catbox/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/hapijs/catbox/issues"
    },
    "dependencies": {
        "boom": "4.x.x",
        "hoek": "4.x.x",
        "joi": "10.x.x"
    },
    "description": "Multi-strategy object caching service",
    "devDependencies": {
        "code": "4.x.x",
        "lab": "11.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "9817edec5a921743282addfc9c45ace52847eebb",
        "tarball": "https://registry.npmjs.org/catbox/-/catbox-7.1.3.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "de95ba689f3858dca375be02b4ba05cb5581c05a",
    "homepage": "https://github.com/hapijs/catbox#readme",
    "keywords": [
        "cache",
        "generic",
        "adapter"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse"
        },
        {
            "name": "wyatt"
        }
    ],
    "name": "catbox",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/catbox.git"
    },
    "scripts": {
        "test": "lab -a code -t 100 -L",
        "test-cov-html": "lab -a code -r html -o coverage.html"
    },
    "version": "7.1.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
