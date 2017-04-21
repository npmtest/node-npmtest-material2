# npmtest-material2

#### basic test coverage for  [material2 (v2.0.0-alpha.6-2)](https://github.com/angular/material2)  [![npm package](https://img.shields.io/npm/v/npmtest-material2.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-material2) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-material2.svg)](https://travis-ci.org/npmtest/node-npmtest-material2)

#### Material Design components for Angular 2

[![NPM](https://nodei.co/npm/material2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/material2)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-material2/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-material2/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-material2/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-material2/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-material2/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-material2/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-material2/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-material2/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-material2/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-material2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-material2/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-material2/build/test-report.html](https://npmtest.github.io/node-npmtest-material2/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-material2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-material2/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-material2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-material2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-material2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-material2/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-material2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-material2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "material2",
    "description": "Material Design components for Angular 2",
    "homepage": "https://github.com/angular/material2",
    "bugs": "https://github.com/angular/material2/issues",
    "repository": {
        "type": "git",
        "url": "https://github.com/angular/material2.git"
    },
    "scripts": {
        "ci:forbidden-identifiers": "node ./scripts/ci/forbidden-identifiers.js",
        "build": "ng build",
        "demo-app": "ng serve",
        "test": "karma start test/karma.conf.js",
        "tslint": "tslint -c tslint.json 'src/**/*.ts'",
        "stylelint": "stylelint 'src/**/*.scss' --config stylelint-config.json --syntax scss",
        "check-circular-deps": "madge --circular ./dist",
        "typings": "typings install --global",
        "postinstall": "npm run typings",
        "e2e": "protractor",
        "inline-resources": "node ./scripts/release/inline-resources.js ./dist/components",
        "deploy": "firebase deploy",
        "webdriver-manager": "webdriver-manager"
    },
    "version": "2.0.0-alpha.6-2",
    "license": "MIT",
    "engines": {
        "node": ">= 4.2.1 < 5"
    },
    "dependencies": {
        "@angular/common": "2.0.0-rc.4",
        "@angular/compiler": "2.0.0-rc.4",
        "@angular/core": "2.0.0-rc.4",
        "@angular/http": "2.0.0-rc.4",
        "@angular/platform-browser": "2.0.0-rc.4",
        "@angular/platform-browser-dynamic": "2.0.0-rc.4",
        "@angular/router": "v3.0.0-alpha.8",
        "@angular/forms": "^0.1.0",
        "core-js": "^2.4.0",
        "hammerjs": "^2.0.8",
        "rxjs": "5.0.0-beta.6",
        "systemjs": "0.19.31",
        "zone.js": "0.6.12"
    },
    "devDependencies": {
        "@angular/compiler-cli": "^0.4.1",
        "add-stream": "^1.0.0",
        "angular-cli": "^1.0.0-beta.9",
        "broccoli-autoprefixer": "^4.1.0",
        "broccoli-funnel": "^1.0.1",
        "broccoli-merge-trees": "^1.1.1",
        "browserstacktunnel-wrapper": "^1.4.2",
        "conventional-changelog": "^1.1.0",
        "ember-cli-inject-live-reload": "^1.4.0",
        "firebase-tools": "^2.2.1",
        "fs-extra": "^0.26.5",
        "glob": "^6.0.4",
        "jasmine-core": "^2.4.1",
        "js-yaml": "^3.5.2",
        "karma": "^1.1.1",
        "karma-browserstack-launcher": "^1.0.1",
        "karma-chrome-launcher": "^1.0.1",
        "karma-firefox-launcher": "^1.0.0",
        "karma-jasmine": "^1.0.2",
        "karma-sauce-launcher": "^1.0.0",
        "madge": "^0.6.0",
        "node-sass": "^3.4.2",
        "protractor": "^3.3.0",
        "protractor-accessibility-plugin": "0.1.1",
        "sass": "^0.5.0",
        "strip-ansi": "^3.0.0",
        "stylelint": "^6.9.0",
        "symlink-or-copy": "^1.0.1",
        "ts-node": "^0.7.3",
        "tslint": "^3.13.0",
        "typescript": "^2.0.0",
        "typings": "^1.3.1",
        "which": "^1.2.4"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
