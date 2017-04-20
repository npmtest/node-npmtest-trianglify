# npmtest-trianglify

#### basic test coverage for  [trianglify (v1.0.1)](https://github.com/qrohlf/trianglify)  [![npm package](https://img.shields.io/npm/v/npmtest-trianglify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-trianglify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-trianglify.svg)](https://travis-ci.org/npmtest/node-npmtest-trianglify)

#### Trianglify is a javascript library for generating colorful triangle meshes that can be used as SVG images and CSS backgrounds.

[![NPM](https://nodei.co/npm/trianglify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/trianglify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-trianglify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-trianglify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-trianglify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-trianglify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-trianglify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-trianglify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-trianglify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-trianglify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-trianglify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-trianglify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-trianglify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-trianglify/build/test-report.html](https://npmtest.github.io/node-npmtest-trianglify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-trianglify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-trianglify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-trianglify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-trianglify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-trianglify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-trianglify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-trianglify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-trianglify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "trianglify",
    "version": "1.0.1",
    "description": "Trianglify is a javascript library for generating colorful triangle meshes that can be used as SVG images and CSS backgrounds.",
    "main": "lib/trianglify.js",
    "dependencies": {
        "chroma-js": "^0.6.3",
        "colors": "^1.1.2",
        "delaunay-fast": "^1.0.1",
        "gulp": "^3.9.1",
        "jsdom": "^7.0.2",
        "seedrandom": "^2.3.11"
    },
    "optionalDependencies": {
        "canvas": "^1.3.0"
    },
    "directories": {
        "example": "examples"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/qrohlf/trianglify.git"
    },
    "keywords": [
        "svg",
        "d3.js",
        "visualization"
    ],
    "author": "Quinn Rohlf <qr@qrohlf.com>",
    "license": "GPL-3.0",
    "bugs": {
        "url": "https://github.com/qrohlf/trianglify/issues"
    },
    "homepage": "https://github.com/qrohlf/trianglify",
    "scripts": {
        "test": "mocha test/test.js",
        "start": "gulp",
        "postinstall": "node scripts/postinstall.js"
    },
    "browser": {
        "jsdom": false,
        "canvas": false
    },
    "devDependencies": {
        "browserify": "^9.0.3",
        "chai": "^2.1.0",
        "del": "^0.1.1",
        "gulp": "^3.8.6",
        "gulp-bump": "^0.1.11",
        "gulp-filter": "^1.0.2",
        "gulp-git": "^0.5.2",
        "gulp-jshint": "^1.7.1",
        "gulp-mocha": "^1.1.1",
        "gulp-rename": "^1.2.0",
        "gulp-sourcemaps": "^1.5.0",
        "gulp-tag-version": "^1.1.0",
        "gulp-uglify": "^0.3.1",
        "jshint-stylish": "^0.4.0",
        "mocha": "^2.1.0",
        "node-notifier": "^4.1.2",
        "vinyl-buffer": "^1.0.0",
        "vinyl-source-stream": "^1.0.0"
    },
    "npmName": "trianglify",
    "npmFileMap": [
        {
            "basePath": "dist",
            "files": [
                "trianglify.min.js"
            ]
        }
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
