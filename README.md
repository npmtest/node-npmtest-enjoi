# npmtest-enjoi

#### basic test coverage for  [enjoi (v2.2.3)](https://github.com/tlivings/enjoi)  [![npm package](https://img.shields.io/npm/v/npmtest-enjoi.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-enjoi) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-enjoi.svg)](https://travis-ci.org/npmtest/node-npmtest-enjoi)

#### Converts json-schema to Joi schema for validation.

[![NPM](https://nodei.co/npm/enjoi.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/enjoi)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-enjoi/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-enjoi/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-enjoi/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-enjoi/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-enjoi/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-enjoi/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-enjoi/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-enjoi/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-enjoi/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-enjoi/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-enjoi/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-enjoi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-enjoi/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-enjoi/build/test-report.html](https://npmtest.github.io/node-npmtest-enjoi/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-enjoi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-enjoi/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-enjoi/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-enjoi/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-enjoi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-enjoi/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-enjoi/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-enjoi/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Trevor Livingston"
    },
    "bugs": {
        "url": "https://github.com/tlivings/enjoi/issues"
    },
    "dependencies": {
        "core-util-is": "^1.0.1",
        "joi": "^9.2.0"
    },
    "description": "Converts json-schema to Joi schema for validation.",
    "devDependencies": {
        "istanbul": "^0.3.2",
        "jshint": "^2.5.5",
        "tape": "^2.14.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8e51f19a24cd709dc740157370e16442d0d214cc",
        "tarball": "https://registry.npmjs.org/enjoi/-/enjoi-2.2.3.tgz"
    },
    "engines": {
        "node": ">=4.x"
    },
    "gitHead": "2371aaa75d4b25fd003721dc04469e3c6c58ebd2",
    "homepage": "https://github.com/tlivings/enjoi",
    "keywords": [
        "joi",
        "json-schema",
        "json",
        "schema",
        "validation",
        "hapi",
        "hapijs"
    ],
    "license": "Apache 2.0",
    "main": "lib/enjoi.js",
    "maintainers": [
        {
            "name": "tlivings"
        }
    ],
    "name": "enjoi",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/tlivings/enjoi.git"
    },
    "scripts": {
        "bench": "node test/bench/run.js",
        "cover": "istanbul cover tape -- test/*.js",
        "lint": "jshint -c .jshintrc lib/*.js",
        "test": "tape test/*.js"
    },
    "version": "2.2.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
