# npmdoc-socketstream

#### api documentation for  [socketstream (v0.5.3)](http://www.socketstream.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-socketstream.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-socketstream) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-socketstream.svg)](https://travis-ci.org/npmdoc/node-npmdoc-socketstream)

#### A framework for Realtime Web Apps

[![NPM](https://nodei.co/npm/socketstream.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/socketstream)

- [https://npmdoc.github.io/node-npmdoc-socketstream/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-socketstream/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-socketstream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-socketstream/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-socketstream/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-socketstream/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Henrik Vendelbo"
    },
    "bin": {
        "socketstream": "./bin/socketstream"
    },
    "bugs": {
        "url": "https://github.com/socketstream/socketstream/issues"
    },
    "contributors": [
        {
            "name": "Owen Barnes"
        },
        {
            "name": "Paul Jensen"
        },
        {
            "name": "Alan Milford"
        },
        {
            "name": "Addy Osmani"
        },
        {
            "name": "nponeccop"
        },
        {
            "name": "Gilbert B Garza"
        },
        {
            "name": "Craig Jordan Muir"
        },
        {
            "name": "David Rosen"
        },
        {
            "name": "Michael Lawson"
        }
    ],
    "dependencies": {
        "apitree": "1.2.0",
        "async": "1.4.2",
        "clean-css": "3.3.9",
        "colors": "1.1.2",
        "connect-redis": "2.4.1",
        "cookie": "^0.2.2",
        "csurf": "1.8.3",
        "debug": "~2.2.0",
        "eventemitter2": "0.4.14",
        "findup-sync": "^0.3.0",
        "glob": "5.0.14",
        "micromatch": "2.2.0",
        "orchestrator": "0.3.7",
        "parseurl": "1.3.0",
        "redis": "0.12.1",
        "resolve": "~1.1.6",
        "send": "0.13.0",
        "shortid": "2.2.2",
        "uglify-js": "2.4.24",
        "utils-merge": "1.0.0",
        "uuid": "2.0.1"
    },
    "description": "A framework for Realtime Web Apps",
    "devDependencies": {
        "chai": "^3.3.0",
        "chokidar": "~1.1.0",
        "commander": "2.8.1",
        "connect-livereload": "~0.5.2",
        "conventional-changelog": "^0.4.3",
        "cookie-parser": "^1.4.0",
        "coveralls": "~2.11.4",
        "dgeni": "^0.4.1",
        "express-session": "^1.11.3",
        "fs-extra": "~0.24.0",
        "gently": "~0.10.0",
        "grunt": "0.4.5",
        "grunt-cli": "0.1.13",
        "grunt-concurrent": "~2.0.3",
        "grunt-contrib-clean": "~0.6.0",
        "grunt-contrib-connect": "~0.11.2",
        "grunt-contrib-watch": "~0.6.1",
        "grunt-conventional-changelog": "~4.1.0",
        "grunt-ngdocs": "~0.2.9",
        "istanbul": "~0.3.18",
        "jshint": "~2.8.0",
        "lolex": "^1.3.1",
        "mocha": "~2.3.3",
        "notes": "0.0.4",
        "npm-dview": "~2.0.0",
        "pre-commit": "~1.1.1",
        "semver": "~5.0.3",
        "shelljs": "~0.5.3",
        "should": "~7.1.0",
        "sinon": "~1.17.0",
        "sinon-chai": "^2.8.0",
        "supertest": "~1.1.0",
        "vinyl-fs": "~2.0.0"
    },
    "directories": {
        "lib": "./lib",
        "doc": "./doc"
    },
    "dist": {
        "shasum": "ebefad1746fe95025181680cfa91c0375a506165",
        "tarball": "https://registry.npmjs.org/socketstream/-/socketstream-0.5.3.tgz"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "gitHead": "5c80a49e1e5239fc382026fd29166525e71b7e0d",
    "homepage": "http://www.socketstream.org",
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "socketstream"
        },
        {
            "name": "paulbjensen"
        },
        {
            "name": "thepian"
        }
    ],
    "name": "socketstream",
    "optionalDependencies": {},
    "pre-commit": [
        "lint",
        "quick-test"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/socketstream/socketstream.git"
    },
    "scripts": {
        "build-docs": "dgeni ./src/docs",
        "changelog": "conventional-changelog  -p angular -i CHANGELOG.md -w",
        "checkDependencies": "npm-dview",
        "cover-test": "istanbul cover -x **/new_project/** node_modules/.bin/_mocha test/unit/**/* && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "lint": "jshint .",
        "notes": "notes",
        "quick-test": "mocha test/unit/**/* --reporter progress",
        "test": "mocha test/unit/**/* --reporter spec",
        "test-debug": "mocha --debug-brk test/unit/**/* --reporter spec"
    },
    "version": "0.5.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
