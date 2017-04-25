# npmtest-redux-storage

#### basic test coverage for  [redux-storage (v4.1.2)](https://github.com/react-stack/redux-storage)  [![npm package](https://img.shields.io/npm/v/npmtest-redux-storage.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-redux-storage) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-redux-storage.svg)](https://travis-ci.org/npmtest/node-npmtest-redux-storage)

#### Persistence layer for redux with flexible backends

[![NPM](https://nodei.co/npm/redux-storage.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redux-storage)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-redux-storage/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-storage/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-redux-storage/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-redux-storage/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-redux-storage/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-redux-storage/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-redux-storage/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-redux-storage/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-redux-storage/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-redux-storage/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-redux-storage/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-storage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-redux-storage/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-redux-storage/build/test-report.html](https://npmtest.github.io/node-npmtest-redux-storage/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-redux-storage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-redux-storage/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-redux-storage/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redux-storage/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-storage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-storage/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-redux-storage/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-redux-storage/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "browserify": {
        "transform": [
            "loose-envify"
        ]
    },
    "bugs": {
        "url": "https://github.com/react-stack/redux-storage/issues"
    },
    "dependencies": {
        "lodash.isfunction": "^3.0.8",
        "lodash.isobject": "^3.0.2",
        "loose-envify": "^1.2.0",
        "redux-actions": "^0.10.1",
        "redux-storage-merger-simple": "^1.0.2"
    },
    "description": "Persistence layer for redux with flexible backends",
    "devDependencies": {
        "babel-cli": "^6.11.4",
        "babel-core": "^6.11.4",
        "babel-polyfill": "^6.9.1",
        "babel-preset-modern-node": "^3.0.0",
        "babel-preset-stage-2": "^6.11.0",
        "eslint": "^1.10.3",
        "eslint-config-michaelcontento": "^1.1.1",
        "eslint-plugin-mocha-only": "0.0.3",
        "mocca": "^1.0.3",
        "release-it": "^2.4.1"
    },
    "directories": {},
    "dist": {
        "shasum": "e06f4bdeee262aead9132fc9f7eadc67e9f9bea2",
        "tarball": "https://registry.npmjs.org/redux-storage/-/redux-storage-4.1.2.tgz"
    },
    "eslintConfig": {
        "extends": "michaelcontento"
    },
    "files": [
        "build/",
        "build-es/",
        "src",
        "!**/__tests__/**"
    ],
    "gitHead": "b62f000bcc05f0ab43866d49416f32381de2a5c9",
    "homepage": "https://github.com/react-stack/redux-storage",
    "jsnext:main": "build-es/index.js",
    "keywords": [
        "redux",
        "redux-middleware",
        "fsa",
        "flux-standard-action",
        "flux",
        "immutable",
        "persistent",
        "data",
        "localstorage"
    ],
    "license": "MIT",
    "main": "build/index.js",
    "maintainers": [
        {
            "name": "michaelcontento"
        }
    ],
    "name": "redux-storage",
    "optionalDependencies": {},
    "peerDependencies": {
        "redux": "^3.0.0 || ^2.0.0 || ^1.0.0 || 1.0.0-alpha || 1.0.0-rc"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/react-stack/redux-storage.git"
    },
    "scripts": {
        "test": "make lint test build"
    },
    "version": "4.1.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
