# npmtest-node-python

#### basic test coverage for  node-python (v0.0.4)  [![npm package](https://img.shields.io/npm/v/npmtest-node-python.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-python) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-python.svg)](https://travis-ci.org/npmtest/node-npmtest-node-python)

#### Call python stuff from nodejs

[![NPM](https://nodei.co/npm/node-python.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-python)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-python/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-python/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-python/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-python/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-python/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-python/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-python/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-python/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-python/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-python/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-python/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-python/build/test-report.html](https://npmtest.github.io/node-npmtest-node-python/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-python/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-python/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-python/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-python/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-python/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-python/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-python/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-python/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-python",
    "version": "0.0.4",
    "description": "Call python stuff from nodejs",
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/JeanSebTr/node-python.git"
    },
    "bugs": "https://github.com/JeanSebTr/node-python/issues",
    "keywords": [
        "python",
        "bridge"
    ],
    "author": {
        "name": "Jean-Sébastien Tremblay",
        "url": "http://blog.jeansebtr.com"
    },
    "contributors": [
        {
            "name": "Chris Dickinson"
        }
    ],
    "scripts": {
        "test": "node test/linker.js"
    },
    "license": "BSD",
    "gypfile": true,
    "readmeFilename": "README.md",
    "dependencies": {
        "bindings": "~1.1.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
