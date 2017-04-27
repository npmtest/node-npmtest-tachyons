# npmtest-tachyons

#### basic test coverage for  [tachyons (v4.7.1)](https://github.com/tachyons-css/tachyons#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-tachyons.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-tachyons) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-tachyons.svg)](https://travis-ci.org/npmtest/node-npmtest-tachyons)

#### Functional CSS for humans

[![NPM](https://nodei.co/npm/tachyons.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tachyons)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-tachyons/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-tachyons/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-tachyons/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-tachyons/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-tachyons/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-tachyons/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-tachyons/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-tachyons/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-tachyons/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-tachyons/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-tachyons/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-tachyons/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-tachyons/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-tachyons/build/test-report.html](https://npmtest.github.io/node-npmtest-tachyons/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-tachyons/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-tachyons/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-tachyons/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tachyons/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tachyons/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tachyons/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-tachyons/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-tachyons/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "mrmrs"
    },
    "bugs": {
        "url": "https://github.com/tachyons-css/tachyons/issues"
    },
    "contributors": [
        {
            "name": "adam morse"
        },
        {
            "name": "john otander",
            "url": "http://johnotander.com"
        }
    ],
    "dependencies": {},
    "description": "Functional CSS for humans",
    "devDependencies": {
        "copy-files": "^0.1.0",
        "immutable-css-cli": "^1.1.1",
        "normalize.css": "^6.0.0",
        "tachyons-cli": "^1.0.10",
        "tachyons-modules": "^1.1.8",
        "watch": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "2ca7295f3eb081470e54d23ef94fffe4322153b4",
        "tarball": "https://registry.npmjs.org/tachyons/-/tachyons-4.7.1.tgz"
    },
    "files": [
        "css",
        "src"
    ],
    "gitHead": "841e24eb57469f14392a1fe525dbf48a947bda39",
    "homepage": "https://github.com/tachyons-css/tachyons#readme",
    "keywords": [
        "css",
        "oocss",
        "postcss",
        "functional css",
        "design",
        "responsive",
        "performance"
    ],
    "license": "MIT",
    "main": "css/tachyons.css",
    "maintainers": [
        {
            "name": "donnieberg"
        },
        {
            "name": "johno"
        },
        {
            "name": "mrmrs"
        }
    ],
    "name": "tachyons",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tachyons-css/tachyons.git"
    },
    "scripts": {
        "build": "npm run build:css && npm run build:minify",
        "build:css": "tachyons src/tachyons.css > css/tachyons.css",
        "build:minify": "tachyons src/tachyons.css -m > css/tachyons.min.css",
        "build:watch": "watch \"npm run build\" ./src/",
        "mutations": "immutable-css src/tachyons.css --strict",
        "start": "npm run build:watch"
    },
    "style": "css/tachyons.min.css",
    "version": "4.7.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
