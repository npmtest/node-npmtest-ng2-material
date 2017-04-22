# npmtest-ng2-material

#### basic test coverage for  ng2-material (v0.8.1)  [![npm package](https://img.shields.io/npm/v/npmtest-ng2-material.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ng2-material) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ng2-material.svg)](https://travis-ci.org/npmtest/node-npmtest-ng2-material)

####

[![NPM](https://nodei.co/npm/ng2-material.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ng2-material)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ng2-material/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ng2-material/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ng2-material/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ng2-material/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ng2-material/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ng2-material/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ng2-material/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ng2-material/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ng2-material/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ng2-material/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ng2-material/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ng2-material/build/test-report.html](https://npmtest.github.io/node-npmtest-ng2-material/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ng2-material/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ng2-material/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ng2-material/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ng2-material/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ng2-material/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ng2-material/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ng2-material/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ng2-material/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ng2-material",
    "version": "0.8.1",
    "description": "",
    "main": "./index.js",
    "repository": {
        "type": "git",
        "url": "git@github.com:justindujardin/ng2-material.git"
    },
    "author": "Justin DuJardin <justin@dujardinconsulting.com>",
    "license": "MIT",
    "readmeFilename": "README.md",
    "scripts": {
        "tdd": "./node_modules/.bin/grunt tdd",
        "start": "./node_modules/.bin/grunt serve",
        "test": "./node_modules/.bin/grunt karma"
    },
    "dependencies": {
        "@angular/common": "^2.0.0",
        "@angular/compiler": "^2.0.0",
        "@angular/core": "^2.0.0",
        "@angular/forms": "^2.0.0",
        "@angular/http": "^2.0.0",
        "@angular/material": "^2.0.0-alpha.9",
        "@angular/platform-browser": "^2.0.0",
        "@angular/platform-browser-dynamic": "^2.0.0",
        "@angular/router": "^3.0.0",
        "es6-promise": ">=3.3.1",
        "es6-shim": "^0.35.1",
        "reflect-metadata": "^0.1.8",
        "rxjs": "^5.0.0-beta.12",
        "zone.js": "^0.6.23"
    },
    "typings": "./index.d.ts",
    "devDependencies": {
        "@types/core-js": "^0.9.34",
        "@types/hammerjs": "^2.0.32",
        "@types/jasmine": "^2.2.33",
        "@types/node": "^6.0.38",
        "autoprefixer": "6.5.0",
        "codelyzer": "1.0.0-beta.0",
        "core-js": "^2.4.1",
        "coveralls": "2.11.14",
        "css": "^2.2.1",
        "css-loader": "0.25.0",
        "es6-module-loader": "0.17.11",
        "file-loader": "0.9.0",
        "glob": "7.1.0",
        "grunt": "1.0.1",
        "grunt-bump": "0.8.0",
        "grunt-cli": "1.2.0",
        "grunt-continue": "^0.1.0",
        "grunt-contrib-clean": "1.0.0",
        "grunt-contrib-connect": "1.0.2",
        "grunt-contrib-copy": "1.0.0",
        "grunt-contrib-sass": "1.0.0",
        "grunt-contrib-watch": "1.0.0",
        "grunt-conventional-changelog": "6.1.0",
        "grunt-karma": "2.0.0",
        "grunt-notify": "0.4.5",
        "grunt-npm": "0.0.2",
        "grunt-postcss": "0.8.0",
        "grunt-sass": "^1.2.1",
        "grunt-ts": "6.0.0-beta.3",
        "highlightjs": "8.7.0",
        "istanbul": "1.0.0-alpha.2",
        "jasmine-core": "^2.5.2",
        "karma": "^1.3.0",
        "karma-chrome-launcher": "2.0.0",
        "karma-coverage": "1.1.1",
        "karma-firefox-launcher": "1.0.0",
        "karma-jasmine": "1.0.2",
        "karma-mocha-reporter": "2.2.0",
        "karma-sauce-launcher": "1.0.0",
        "lcov-parse": "0.0.10",
        "marked": "0.3.6",
        "npm": "^3.10.7",
        "remap-istanbul": "0.6.4",
        "style-loader": "0.13.1",
        "systemjs": "0.19.39",
        "tslint": "^3.15.1",
        "typescript": "^2.0.0",
        "underscore": "1.8.3"
    },
    "contributors": [
        "Justin DuJardin <justindujardin@users.noreply.github.com>",
        "Grégory Copin <gregcop1@gmail.com>",
        "Jaroslav Řehořka <jaroslav.rehorka@gmail.com>",
        "Sam <samuel.jones@q-free.com>",
        "Sylvain Dumont <sylvain.dumont35@gmail.com>",
        "Sam Jones <ollwen.jones@gmail.com>",
        "samuel.jones <samuel.jones@q-free.com>",
        "Dotan Simha <dotansimha@gmail.com>",
        "Adam Busbin <aw.busbin@gmail.com>",
        "Jared Dickson <code@jareddickson.com>",
        "Daniel Rasmuson <dan123911@gmail.com>",
        "Dan MacFarlane <dan@dancity.com>",
        "Christian Beilschmidt <fyaa@ntacity.de>",
        "Lukas Ruebbelke <simpul@gmail.com>",
        "Maks3w <github.maks3w@virtualplanets.net>",
        "Milos Stanic <milos.stanic@gmail.com>",
        "Miloš Stanić <milos.stanic@gmail.com>",
        "N. Schipper <n.schippper@twensoc.nl>",
        "Paul Robinson <paul.robinson@kyndling.com>",
        "Chris Seto <chriskseto@gmail.com>",
        "BIZID Amine <amine.bizid@gmail.com>",
        "Sam Van Brussel <sam.vanbrussel@linqed.be>",
        "Alexander Zeiher <alexander@zeiher.se>",
        "Tally Barak <tally.barak@gmail.com>",
        "Ferdinand Torggler <ferdinand.torggler@gmail.com>"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
