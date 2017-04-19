# npmtest-firebase-tools

#### test coverage for  [firebase-tools (v3.6.1)](https://github.com/firebase/firebase-tools)  [![npm package](https://img.shields.io/npm/v/npmtest-firebase-tools.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-firebase-tools) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-firebase-tools.svg)](https://travis-ci.org/npmtest/node-npmtest-firebase-tools)

#### Command-Line Interface for Firebase

[![NPM](https://nodei.co/npm/firebase-tools.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/firebase-tools)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-firebase-tools/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-firebase-tools/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-firebase-tools/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-firebase-tools/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-firebase-tools/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-firebase-tools/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-firebase-tools/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-firebase-tools/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-firebase-tools/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-firebase-tools/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-firebase-tools/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-firebase-tools/build/test-report.html](https://npmtest.github.io/node-npmtest-firebase-tools/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-firebase-tools/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-firebase-tools/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-firebase-tools/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-firebase-tools/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-firebase-tools/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-firebase-tools/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-firebase-tools/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-firebase-tools/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Firebase",
        "url": "https://firebase.google.com/"
    },
    "bin": {
        "firebase": "./bin/firebase"
    },
    "bugs": {
        "url": "https://github.com/firebase/firebase-tools/issues"
    },
    "dependencies": {
        "JSONStream": "^1.2.1",
        "archiver": "^0.16.0",
        "chalk": "^1.1.0",
        "cjson": "^0.3.1",
        "cli-table": "^0.3.1",
        "commander": "^2.8.1",
        "configstore": "^1.2.0",
        "cross-spawn": "^4.0.0",
        "csv-streamify": "^3.0.4",
        "didyoumean": "^1.2.1",
        "es6-set": "^0.1.4",
        "exit-code": "^1.0.2",
        "filesize": "^3.1.3",
        "firebase": "2.x.x",
        "fs-extra": "^0.23.1",
        "fstream-ignore": "^1.0.2",
        "inquirer": "^0.12.0",
        "jsonschema": "^1.0.2",
        "jsonwebtoken": "^5.4.0",
        "lodash": "^4.6.1",
        "open": "^0.0.5",
        "ora": "0.2.3",
        "portfinder": "^0.4.0",
        "progress": "^1.1.8",
        "request": "^2.58.0",
        "rsvp": "^3.0.18",
        "semver": "^5.0.3",
        "superstatic": "^4.0",
        "tar": "^2.2.0",
        "tmp": "0.0.27",
        "universal-analytics": "^0.3.9",
        "update-notifier": "^0.5.0",
        "user-home": "^2.0.0",
        "uuid": "^3.0.0",
        "winston": "^1.0.1"
    },
    "description": "Command-Line Interface for Firebase",
    "devDependencies": {
        "chai": "^3.0.0",
        "chai-as-promised": "^5.1.0",
        "coveralls": "2.11.2",
        "eslint": "^1.4.1",
        "gulp": "^3.9.0",
        "gulp-eslint": "^1.0.0",
        "gulp-exit": "0.0.2",
        "gulp-istanbul": "^0.10.0",
        "gulp-mocha": "^2.1.2",
        "jshint-stylish": "^2.0.1",
        "nock": "^2.10.0",
        "sinon": "^1.17.4",
        "sinon-as-promised": "^4.0.0",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ab1e788f42ab29135ff9225de85b0cfe088ad17d",
        "tarball": "https://registry.npmjs.org/firebase-tools/-/firebase-tools-3.6.1.tgz"
    },
    "engine-strict": true,
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "bin/**",
        "lib/**",
        "commands/**",
        "templates/**",
        "index.js"
    ],
    "gitHead": "56b1bc437dd43abb2dc444274488dd7466183ec9",
    "homepage": "https://github.com/firebase/firebase-tools",
    "keywords": [
        "cdn",
        "cli",
        "ssl",
        "cloud",
        "hosting",
        "firebase",
        "realtime",
        "websockets",
        "synchronization"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "firebase"
        }
    ],
    "name": "firebase-tools",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/firebase/firebase-tools.git"
    },
    "scripts": {
        "test": "gulp"
    },
    "version": "3.6.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
