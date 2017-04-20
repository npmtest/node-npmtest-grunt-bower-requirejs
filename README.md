# npmtest-grunt-bower-requirejs

#### basic test coverage for  grunt-bower-requirejs (v2.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-bower-requirejs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-bower-requirejs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-bower-requirejs.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-bower-requirejs)

#### Automagically wire-up installed Bower components into your RequireJS config

[![NPM](https://nodei.co/npm/grunt-bower-requirejs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-bower-requirejs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-bower-requirejs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-bower-requirejs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-bower-requirejs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-bower-requirejs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-bower-requirejs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-bower-requirejs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-bower-requirejs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-bower-requirejs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-bower-requirejs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-bower-requirejs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-bower-requirejs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-bower-requirejs/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-bower-requirejs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-bower-requirejs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-bower-requirejs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-bower-requirejs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-bower-requirejs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-bower-requirejs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-bower-requirejs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-bower-requirejs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-bower-requirejs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-bower-requirejs",
    "version": "2.0.0",
    "description": "Automagically wire-up installed Bower components into your RequireJS config",
    "keywords": [
        "gruntplugin",
        "bower",
        "requirejs",
        "rjs",
        "config",
        "wire",
        "inject",
        "install",
        "component",
        "package",
        "module"
    ],
    "license": "BSD",
    "author": {
        "name": "Rob Dodson",
        "url": "http://robdodson.me"
    },
    "repository": "yeoman/grunt-bower-requirejs",
    "scripts": {
        "test": "grunt test"
    },
    "dependencies": {
        "bower-requirejs": "^1.0.0",
        "load-grunt-tasks": "^2.0.0"
    },
    "devDependencies": {
        "bower": "^1.x",
        "durable-json-lint": "^0.0.1",
        "grunt": "^0.4.5",
        "grunt-contrib-clean": "^0.6.0",
        "grunt-contrib-copy": "^0.7.0",
        "grunt-contrib-jshint": "^0.10.0",
        "grunt-contrib-nodeunit": "^0.4.1",
        "grunt-simple-mocha": "^0.4.0",
        "should": "^4.0.4"
    },
    "peerDependencies": {
        "grunt": ">=0.4.0",
        "bower": "^1.x"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "tasks/bower-requirejs.js"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
