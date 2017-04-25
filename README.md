# npmdoc-ionic-native

#### basic api documentation for  ionic-native (v3.5.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-ionic-native.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ionic-native) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ionic-native.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ionic-native)

#### Native plugin wrappers for Cordova and Ionic with TypeScript, ES6+, Promise and Observable support

[![NPM](https://nodei.co/npm/ionic-native.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ionic-native)

- [https://npmdoc.github.io/node-npmdoc-ionic-native/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ionic-native/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ionic-native/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ionic-native/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ionic-native/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ionic-native/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "dependencies": {},
    "description": "Native plugin wrappers for Cordova and Ionic with TypeScript, ES6+, Promise and Observable support",
    "devDependencies": {
        "@angular/compiler": "2.4.8",
        "@angular/compiler-cli": "2.4.8",
        "@angular/core": "2.4.8",
        "canonical-path": "0.0.2",
        "child-process-promise": "2.2.0",
        "conventional-changelog-cli": "1.2.0",
        "cpr": "2.0.2",
        "cz-conventional-changelog": "1.2.0",
        "decamelize": "1.2.0",
        "dgeni": "0.4.7",
        "dgeni-packages": "0.16.10",
        "fs-extra": "2.0.0",
        "fs-extra-promise": "0.4.1",
        "gulp": "3.9.1",
        "gulp-rename": "1.2.2",
        "gulp-replace": "0.5.4",
        "gulp-tslint": "6.1.2",
        "lodash": "4.17.4",
        "minimist": "1.1.3",
        "node-html-encoder": "0.0.2",
        "q": "1.4.1",
        "queue": "4.2.1",
        "rimraf": "2.5.4",
        "rxjs": "5.0.1",
        "semver": "5.3.0",
        "tslint": "3.15.1",
        "tslint-ionic-rules": "0.0.7",
        "typescript": "2.0.09",
        "zone.js": "0.7.2"
    },
    "directories": {},
    "dist": {
        "shasum": "08d9bd2488d6bddff0c1c594dc4e647242efbd55",
        "tarball": "https://registry.npmjs.org/ionic-native/-/ionic-native-3.5.0.tgz"
    },
    "gitHead": "7df7a557da3cd2ea2064fb0343dcda6a4b6b7949",
    "license": "MIT",
    "maintainers": [
        {
            "name": "ihadeed"
        },
        {
            "name": "ionicjs"
        },
        {
            "name": "maxlynch"
        },
        {
            "name": "tlancina"
        }
    ],
    "name": "ionic-native",
    "optionalDependencies": {},
    "scripts": {
        "build": "npm run clean && npm run lint && npm run build:core && npm run build:modules",
        "build:core": "ngc -p scripts/build/tsconfig-core.json",
        "build:modules": "node scripts/build/build.js",
        "changelog": "conventional-changelog -p angular -i CHANGELOG.md -s -r 0",
        "clean": "rimraf dist .tmp",
        "lint": "gulp lint",
        "npmpub": "node scripts/build/publish.js",
        "postchangelog": "git commit -am \"chore(): update changelog\"",
        "shipit": "npm run build && gulp readmes && npm run npmpub",
        "start": "npm run test:watch"
    },
    "version": "3.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
