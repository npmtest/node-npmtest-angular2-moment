# npmtest-angular2-moment

#### basic test coverage for  [angular2-moment (v1.3.3)](https://github.com/urish/angular2-moment#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-angular2-moment.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-angular2-moment) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-angular2-moment.svg)](https://travis-ci.org/npmtest/node-npmtest-angular2-moment)

#### Moment.JS pipes for Angular2 (timeago and more)

[![NPM](https://nodei.co/npm/angular2-moment.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/angular2-moment)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-angular2-moment/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular2-moment/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-angular2-moment/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-angular2-moment/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-angular2-moment/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-angular2-moment/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-angular2-moment/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-angular2-moment/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-angular2-moment/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-angular2-moment/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-angular2-moment/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular2-moment/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-angular2-moment/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-angular2-moment/build/test-report.html](https://npmtest.github.io/node-npmtest-angular2-moment/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-angular2-moment/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-angular2-moment/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-angular2-moment/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-angular2-moment/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-angular2-moment/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-angular2-moment/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-angular2-moment/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-angular2-moment/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Uri Shaked"
    },
    "bugs": {
        "url": "https://github.com/urish/angular2-moment/issues"
    },
    "dependencies": {
        "moment": "^2.16.0"
    },
    "description": "Moment.JS pipes for Angular2 (timeago and more)",
    "devDependencies": {
        "@angular/common": "2.0.2",
        "@angular/compiler": "2.0.2",
        "@angular/compiler-cli": "0.6.4",
        "@angular/core": "2.0.2",
        "@angular/platform-browser": "2.0.2",
        "@angular/platform-server": "2.0.2",
        "@types/jasmine": "2.5.35",
        "awesome-typescript-loader": "2.2.4",
        "copyfiles": "1.0.0",
        "es6-shim": "0.35.1",
        "jasmine-core": "2.4.1",
        "karma": "1.1.0",
        "karma-jasmine": "1.0.2",
        "karma-phantomjs-launcher": "1.0.1",
        "karma-sourcemap-loader": "0.3.7",
        "karma-webpack": "1.7.0",
        "phantomjs-prebuilt": "2.1.7",
        "reflect-metadata": "0.1.3",
        "rxjs": "5.0.0-beta.12",
        "tslint": "3.15.1",
        "typescript": "2.0.3",
        "webpack": "1.13.2",
        "zone.js": "0.6.25"
    },
    "directories": {},
    "dist": {
        "shasum": "569c433bbfa2448d5424f0e10dce6f8c8c9533eb",
        "tarball": "https://registry.npmjs.org/angular2-moment/-/angular2-moment-1.3.3.tgz"
    },
    "files": [
        "index.js",
        "index.js.map",
        "index.d.ts",
        "index.metadata.json",
        "moment.module.js",
        "moment.module.js.map",
        "moment.module.d.ts",
        "moment.module.metadata.json",
        "calendar.pipe.js",
        "calendar.pipe.js.map",
        "calendar.pipe.d.ts",
        "calendar.pipe.metadata.json",
        "date-format.pipe.js",
        "date-format.pipe.js.map",
        "date-format.pipe.d.ts",
        "date-format.pipe.metadata.json",
        "difference.pipe.js",
        "difference.pipe.js.map",
        "difference.pipe.d.ts",
        "difference.pipe.metadata.json",
        "duration.pipe.js",
        "duration.pipe.js.map",
        "duration.pipe.d.ts",
        "duration.pipe.metadata.json",
        "time-ago.pipe.js",
        "time-ago.pipe.js.map",
        "time-ago.pipe.d.ts",
        "time-ago.pipe.metadata.json",
        "from-unix.pipe.js",
        "from-unix.pipe.js.map",
        "from-unix.pipe.d.ts",
        "from-unix.pipe.metadata.json",
        "add.pipe.js",
        "add.pipe.js.map",
        "add.pipe.d.ts",
        "add.pipe.metadata.json",
        "subtract.pipe.js",
        "subtract.pipe.js.map",
        "subtract.pipe.d.ts",
        "subtract.pipe.metadata.json",
        "utc.pipe.js",
        "utc.pipe.js.map",
        "utc.pipe.d.ts",
        "utc.pipe.metadata.json",
        "CHANGELOG.md"
    ],
    "gitHead": "21c56044e997c0a8cb70b5abfbc299dbf4eb92df",
    "homepage": "https://github.com/urish/angular2-moment#readme",
    "keywords": [
        "angular2",
        "momentjs"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "urish"
        }
    ],
    "name": "angular2-moment",
    "optionalDependencies": {},
    "peerDependencies": {
        "@angular/core": ">=2.0.0 <5.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/urish/angular2-moment.git"
    },
    "scripts": {
        "prepublish": "ngc && copyfiles -f src/*.js src/*.js.map src/*.d.ts src/*.metadata.json .",
        "test": "tslint src/*.ts --exclude=src/*.d.ts && ngc && karma start"
    },
    "typings": "./index.d.ts",
    "version": "1.3.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
