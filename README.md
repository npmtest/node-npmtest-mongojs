# test coverage for  [mongojs (v2.4.0)](https://github.com/mafintosh/mongojs#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-mongojs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mongojs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mongojs.svg)](https://travis-ci.org/npmtest/node-npmtest-mongojs)
#### Easy to use module that implements the mongo api

[![NPM](https://nodei.co/npm/mongojs.png?downloads=true)](https://www.npmjs.com/package/mongojs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mongojs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mongojs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mongojs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mongojs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mongojs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mongojs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mongojs/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mongojs/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-mongojs/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-mongojs/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-mongojs%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mongojs/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mongojs/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-mongojs%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mongojs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mongojs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mongojs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mathias Buus Madsen",
        "email": "mathiasbuus@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/mafintosh/mongojs/issues"
    },
    "contributors": [
        {
            "name": "Mathias Buus Madsen",
            "email": "mathiasbuus@gmail.com"
        },
        {
            "name": "Ian Jorgensen"
        },
        {
            "name": "Eduardo Sorribas"
        },
        {
            "name": "Taeho Kim"
        },
        {
            "name": "Forbes Lindesay"
        },
        {
            "name": "Robert S."
        },
        {
            "name": "Srirangan"
        },
        {
            "name": "Erkan Yilmaz"
        },
        {
            "name": "Jake Maskiewicz"
        },
        {
            "name": "Bjarke Walling"
        },
        {
            "name": "Tobias Baunbæk"
        },
        {
            "name": "Benedikt Arnold"
        },
        {
            "name": "Kevin McTigue"
        },
        {
            "name": "Thomas Watson Steen",
            "email": "w@tson.dk"
        }
    ],
    "coordinates": [
        48.2317966,
        16.3996661
    ],
    "dependencies": {
        "each-series": "^1.0.0",
        "mongodb": "^2.0.45",
        "once": "^1.3.2",
        "parse-mongo-url": "^1.1.0",
        "readable-stream": "^2.0.2",
        "thunky": "^0.1.0",
        "to-mongodb-core": "^2.0.0",
        "xtend": "^4.0.0"
    },
    "description": "Easy to use module that implements the mongo api",
    "devDependencies": {
        "concat-stream": "^1.5.0",
        "geopkg": "^4.0.3",
        "istanbul": "^0.4.1",
        "shelljs": "^0.7.0",
        "standard": "^6.0.8",
        "tap-spec": "^4.1.1",
        "tape": "^4.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "f287fbfd457fedf588b5a9011e68513d9dd32bfb",
        "tarball": "https://registry.npmjs.org/mongojs/-/mongojs-2.4.0.tgz"
    },
    "gitHead": "8e7ae24c3963d706c2b94f1778dcc0fcba2fbc99",
    "homepage": "https://github.com/mafintosh/mongojs#readme",
    "keywords": [
        "mongo",
        "db",
        "mongodb"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "mafintosh",
            "email": "mathiasbuus@gmail.com"
        },
        {
            "name": "sorribas",
            "email": "eduardo@sorribas.org"
        },
        {
            "name": "watson",
            "email": "w@tson.dk"
        },
        {
            "name": "saintedlama",
            "email": "christoph.walcher@gmail.com"
        }
    ],
    "name": "mongojs",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/mafintosh/mongojs.git"
    },
    "scripts": {
        "cover": "node --harmony --harmony-proxies node_modules/istanbul/lib/cli.js cover node_modules/tape/bin/tape \"test/test-*.js\" --report html",
        "geotag": "geopkg update",
        "test": "standard && (tape \"test/test-*.js\" && node --harmony --harmony-proxies node_modules/tape/bin/tape \"test/test-*.js\") | tap-spec"
    },
    "version": "2.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
