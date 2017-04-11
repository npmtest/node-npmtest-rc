# test coverage for  [rc (v1.2.1)](https://github.com/dominictarr/rc#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-rc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rc.svg)](https://travis-ci.org/npmtest/node-npmtest-rc)
#### hardwired configuration loader

[![NPM](https://nodei.co/npm/rc.png?downloads=true)](https://www.npmjs.com/package/rc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rc/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rc/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-rc/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-rc/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-rc%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rc/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rc/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-rc%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dominic Tarr",
        "email": "dominic.tarr@gmail.com",
        "url": "dominictarr.com"
    },
    "bin": {
        "rc": "./index.js"
    },
    "browserify": "browser.js",
    "bugs": {
        "url": "https://github.com/dominictarr/rc/issues"
    },
    "dependencies": {
        "deep-extend": "~0.4.0",
        "ini": "~1.3.0",
        "minimist": "^1.2.0",
        "strip-json-comments": "~2.0.1"
    },
    "description": "hardwired configuration loader",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "2e03e8e42ee450b8cb3dce65be1bf8974e1dfd95",
        "tarball": "https://registry.npmjs.org/rc/-/rc-1.2.1.tgz"
    },
    "gitHead": "41251ff2bdc6a067dd3bf77efcdad57cae23b515",
    "homepage": "https://github.com/dominictarr/rc#readme",
    "keywords": [
        "config",
        "rc",
        "unix",
        "defaults"
    ],
    "license": "(BSD-2-Clause OR MIT OR Apache-2.0)",
    "main": "index.js",
    "maintainers": [
        {
            "name": "dominictarr",
            "email": "dominic.tarr@gmail.com"
        }
    ],
    "name": "rc",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dominictarr/rc.git"
    },
    "scripts": {
        "test": "set -e; node test/test.js; node test/ini.js; node test/nested-env-vars.js"
    },
    "version": "1.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
