# npmtest-private-bower

#### basic test coverage for  [private-bower (v1.1.8)](http://hacklone.github.io/private-bower)  [![npm package](https://img.shields.io/npm/v/npmtest-private-bower.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-private-bower) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-private-bower.svg)](https://travis-ci.org/npmtest/node-npmtest-private-bower)

#### A simple private bower registry

[![NPM](https://nodei.co/npm/private-bower.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/private-bower)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-private-bower/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-private-bower/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-private-bower/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-private-bower/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-private-bower/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-private-bower/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-private-bower/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-private-bower/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-private-bower/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-private-bower/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-private-bower/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-private-bower/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-private-bower/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-private-bower/build/test-report.html](https://npmtest.github.io/node-npmtest-private-bower/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-private-bower/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-private-bower/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-private-bower/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-private-bower/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-private-bower/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-private-bower/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-private-bower/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-private-bower/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "analyze": false,
    "author": {
        "name": "Hacklone"
    },
    "bin": {
        "private-bower": "./bin/private-bower"
    },
    "bugs": {
        "url": "https://github.com/Hacklone/private-bower/issues"
    },
    "dependencies": {
        "URIjs": "^1.5.0",
        "bluebird": "^2.9.14",
        "body-parser": "^1.12.0",
        "colors": "^0.6.2",
        "express": "^4.12.2",
        "log4js": "^0.6.14",
        "mkdirp": "0.5.x",
        "moment": "^2.7.0",
        "node-rest-client": "^1.0.0",
        "optimist": "^0.5.2",
        "path-is-absolute": "^1.0.0"
    },
    "description": "A simple private bower registry",
    "devDependencies": {
        "chai": "^2.2.0",
        "gulp": "3.8.11",
        "gulp-mocha": "^2.0.0",
        "mockery": "1.4.0",
        "run-sequence": "^1.0.2",
        "sinon": "^1.14.1",
        "sinon-chai": "^2.7.0",
        "superagent": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "aa094b083e10f34cd0c521189d8e243ccb84cb3c",
        "tarball": "https://registry.npmjs.org/private-bower/-/private-bower-1.1.8.tgz"
    },
    "gitHead": "b185343a414eb4759d995a5d062ea3dbe69d2962",
    "homepage": "http://hacklone.github.io/private-bower",
    "keywords": [
        "bower",
        "private",
        "registry",
        "repository",
        "repo",
        "cache",
        "git",
        "svn",
        "package"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/Hacklone/private-bower/raw/master/LICENSE"
        }
    ],
    "main": "./bin/private-bower",
    "maintainers": [
        {
            "name": "hacklone"
        }
    ],
    "name": "private-bower",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/Hacklone/private-bower.git"
    },
    "scripts": {
        "start": "node ./bin/private-bower"
    },
    "version": "1.1.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
