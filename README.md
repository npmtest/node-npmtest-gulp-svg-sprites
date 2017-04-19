# npmtest-gulp-svg-sprites

#### test coverage for  [gulp-svg-sprites (v4.1.1)](https://github.com/shakyshane/gulp-svg-sprites#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-svg-sprites.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-svg-sprites) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-svg-sprites.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-svg-sprites)

#### Create SVG sprites with PNG fallbacks

[![NPM](https://nodei.co/npm/gulp-svg-sprites.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-svg-sprites)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-svg-sprites/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-svg-sprites/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-svg-sprites/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-svg-sprites/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-svg-sprites/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-svg-sprites/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-svg-sprites/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-svg-sprites/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-svg-sprites/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-svg-sprites/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-svg-sprites/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-svg-sprites/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-svg-sprites/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-svg-sprites/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-svg-sprites/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-svg-sprites/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-svg-sprites/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-svg-sprites/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-svg-sprites/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-svg-sprites/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-svg-sprites/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/shakyshane/gulp-svg-sprites/issues"
    },
    "dependencies": {
        "gulp-util": "3.0.7",
        "lodash": "4.14.1",
        "q": "1.4.1",
        "svg-sprite-data": "3.1.0",
        "svgo": "0.6.6",
        "through2": "2.0.1",
        "vinyl": "1.2.0"
    },
    "description": "Create SVG sprites with PNG fallbacks",
    "devDependencies": {
        "chai": "3.5.0",
        "gulp": "3.9.1",
        "gulp-clean": "0.3.2",
        "gulp-contribs": "0.0.3",
        "gulp-filter": "4.0.0",
        "gulp-jshint": "2.0.1",
        "gulp-svg2png": "2.0.0",
        "gulp-yuidoc": "0.1.2",
        "img-compare": "1.2.0",
        "jshint": "^2.9.1",
        "marked": "0.3.6",
        "mocha": "3.0.1",
        "sinon": "1.17.5",
        "vinyl-fs": "2.4.3"
    },
    "directories": {},
    "dist": {
        "shasum": "4f5e7d393e2c0af64e64c0f20ebc798de6fae1a9",
        "tarball": "https://registry.npmjs.org/gulp-svg-sprites/-/gulp-svg-sprites-4.1.1.tgz"
    },
    "engines": {
        "node": ">= 4.0.0"
    },
    "gitHead": "d4c862eef13222c143f529f3413730a6e61579d8",
    "homepage": "https://github.com/shakyshane/gulp-svg-sprites#readme",
    "keywords": [
        "svg",
        "sprites",
        "gulpplugin"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "/blob/master/LICENSE-MIT"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "shakyshane"
        },
        {
            "name": "soenkekluth"
        }
    ],
    "name": "gulp-svg-sprites",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/shakyshane/gulp-svg-sprites.git"
    },
    "scripts": {
        "example": "node example-stream.js",
        "gulp": "gulp",
        "gulp-basic": "gulp sprite:basic",
        "gulp-basic-scss": "gulp sprite:basic-scss",
        "gulp-options": "gulp sprite:options",
        "gulp-scss": "gulp sprite:scss",
        "test": "gulp lint && mocha --recursive test/specs"
    },
    "version": "4.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
