# test coverage for  [libxmljs (v0.18.4)](https://github.com/libxmljs/libxmljs)  [![npm package](https://img.shields.io/npm/v/npmtest-libxmljs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-libxmljs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-libxmljs.svg)](https://travis-ci.org/npmtest/node-npmtest-libxmljs)
#### libxml bindings for v8 javascript engine

[![NPM](https://nodei.co/npm/libxmljs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/libxmljs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-libxmljs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-libxmljs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-libxmljs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-libxmljs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-libxmljs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-libxmljs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-libxmljs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-libxmljs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-libxmljs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-libxmljs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-libxmljs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-libxmljs/build/test-report.html](https://npmtest.github.io/node-npmtest-libxmljs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-libxmljs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-libxmljs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-libxmljs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-libxmljs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-libxmljs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-libxmljs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-libxmljs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-libxmljs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Marco Rogers"
    },
    "binary": {
        "module_name": "xmljs",
        "module_path": "./build/Release/",
        "host": "https://github.com",
        "remote_path": "./libxmljs/libxmljs/releases/download/v{version}/",
        "package_name": "{node_abi}-{platform}-{arch}.tar.gz"
    },
    "bugs": {
        "url": "http://github.com/libxmljs/libxmljs/issues"
    },
    "contributors": [
        {
            "name": "Jeff Smick"
        }
    ],
    "dependencies": {
        "bindings": "1.2.1",
        "nan": "~2.5.0",
        "node-pre-gyp": "~0.6.32"
    },
    "description": "libxml bindings for v8 javascript engine",
    "devDependencies": {
        "nodeunit": "0.9.0"
    },
    "directories": {},
    "dist": {
        "shasum": "253028925900e9f8d454418034a25b8af4e1507f",
        "tarball": "https://registry.npmjs.org/libxmljs/-/libxmljs-0.18.4.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "homepage": "https://github.com/libxmljs/libxmljs",
    "license": "MIT",
    "main": "./index",
    "maintainers": [
        {
            "name": "defunctzombie"
        },
        {
            "name": "polotek"
        },
        {
            "name": "rchipka"
        }
    ],
    "name": "libxmljs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/libxmljs/libxmljs.git"
    },
    "scripts": {
        "install": "node-pre-gyp install --fallback-to-build --loglevel http",
        "test": "node --expose_gc ./node_modules/.bin/nodeunit test"
    },
    "version": "0.18.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
