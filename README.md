# npmtest-generator-polymer

#### basic test coverage for  generator-polymer (v1.3.0)  [![npm package](https://img.shields.io/npm/v/npmtest-generator-polymer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generator-polymer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generator-polymer.svg)](https://travis-ci.org/npmtest/node-npmtest-generator-polymer)

#### Scaffold out a Polymer project

[![NPM](https://nodei.co/npm/generator-polymer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-polymer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generator-polymer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-polymer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generator-polymer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generator-polymer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generator-polymer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generator-polymer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generator-polymer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generator-polymer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generator-polymer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-polymer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generator-polymer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generator-polymer/build/test-report.html](https://npmtest.github.io/node-npmtest-generator-polymer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generator-polymer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generator-polymer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generator-polymer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-polymer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-polymer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-polymer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generator-polymer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generator-polymer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "generator-polymer",
    "version": "1.3.0",
    "description": "Scaffold out a Polymer project",
    "keywords": [
        "yeoman-generator",
        "scaffold",
        "framework",
        "mvc",
        "polymer"
    ],
    "author": "Chrome Developer Relations",
    "main": "app/index.js",
    "repository": "yeoman/generator-polymer",
    "scripts": {
        "test": "jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec",
        "prepublish": "git submodule update --init --recursive"
    },
    "dependencies": {
        "chalk": "^1.0.0",
        "html-wiring": "^1.2.0",
        "js-beautify": "^1.5.10",
        "lodash": "^4.0.0",
        "mkdirp": "^0.5.1",
        "ncp": "^2.0.0",
        "rimraf": "^2.2.8",
        "validate-element-name": "^1.0.0",
        "yeoman-generator": "^0.22.3",
        "yosay": "^1.0.0"
    },
    "devDependencies": {
        "fs-extra": "*",
        "jshint": "*",
        "mocha": "*",
        "yeoman-assert": "^2.1.1",
        "yeoman-test": "^1.0.0"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "licenses": "BSD",
    "files": [
        "app",
        "el",
        "element",
        "gh",
        "seed",
        "script-base.js",
        "util.js"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
