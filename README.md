# npmtest-gulp-cache-bust

#### test coverage for  [gulp-cache-bust (v1.1.0)](https://github.com/furzeface/gulp-cache-bust#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-cache-bust.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-cache-bust) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-cache-bust.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-cache-bust)

#### Append a query string to your assets to bust that cache!

[![NPM](https://nodei.co/npm/gulp-cache-bust.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-cache-bust)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-cache-bust/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-cache-bust/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-cache-bust/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-cache-bust/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-cache-bust/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-cache-bust/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-cache-bust/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-cache-bust/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-cache-bust/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-cache-bust/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-cache-bust/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-cache-bust/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-cache-bust/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-cache-bust/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-cache-bust/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-cache-bust/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-cache-bust/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-cache-bust/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-cache-bust/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-cache-bust/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-cache-bust/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel Furze",
        "url": "https://github.com/furzeface"
    },
    "bugs": {
        "url": "https://github.com/furzeface/gulp-cache-bust/issues"
    },
    "dependencies": {
        "cachebust": "2.0.1",
        "graceful-fs": "^4.1.9",
        "gulp-util": "3.0.7",
        "map-stream": "^0.1.0",
        "temp-write": "^2.1.0",
        "through2": "2.0.1"
    },
    "description": "Append a query string to your assets to bust that cache!",
    "devDependencies": {
        "coveralls": "*",
        "event-stream": "*",
        "gulp": "^3.8.8",
        "istanbul": "*",
        "mocha": "*",
        "mocha-lcov-reporter": "*",
        "should": "~11.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "3fe702ab2e0cc01945debd8f1cc2a2f2b510511d",
        "tarball": "https://registry.npmjs.org/gulp-cache-bust/-/gulp-cache-bust-1.1.0.tgz"
    },
    "engines": {
        "node": ">=4.4.5",
        "npm": ">=2.15.1"
    },
    "gitHead": "bb7ad93dc495ea2e85c80a79f7619dd5719f46b7",
    "homepage": "https://github.com/furzeface/gulp-cache-bust#readme",
    "keywords": [
        "assets",
        "cache",
        "cachebust",
        "gulpplugin",
        "MD5",
        "timestamp"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "davinkevin"
        },
        {
            "name": "furzeface"
        }
    ],
    "name": "gulp-cache-bust",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/furzeface/gulp-cache-bust.git"
    },
    "scripts": {
        "coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "test": "istanbul test _mocha --report html -- test/*.js --reporter spec"
    },
    "version": "1.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
