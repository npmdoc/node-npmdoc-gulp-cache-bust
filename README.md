# api documentation for  [gulp-cache-bust (v1.1.0)](https://github.com/furzeface/gulp-cache-bust#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-cache-bust.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-cache-bust) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-cache-bust.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-cache-bust)
#### Append a query string to your assets to bust that cache!

[![NPM](https://nodei.co/npm/gulp-cache-bust.png?downloads=true)](https://www.npmjs.com/package/gulp-cache-bust)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-cache-bust/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-gulp-cache-bust_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-cache-bust/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-cache-bust/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-cache-bust/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel Furze",
        "email": "daniel@furzeface.com",
        "url": "https://github.com/furzeface"
    },
    "bugs": {
        "url": "https://github.com/furzeface/gulp-cache-bust/issues"
    },
    "dependencies": {
        "cachebust": "2.0.1",
        "graceful-fs": "^4.1.9",
        "gulp-util": "3.0.7",
        "map-stream": "^0.1.0",
        "temp-write": "^2.1.0",
        "through2": "2.0.1"
    },
    "description": "Append a query string to your assets to bust that cache!",
    "devDependencies": {
        "coveralls": "*",
        "event-stream": "*",
        "gulp": "^3.8.8",
        "istanbul": "*",
        "mocha": "*",
        "mocha-lcov-reporter": "*",
        "should": "~11.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "3fe702ab2e0cc01945debd8f1cc2a2f2b510511d",
        "tarball": "https://registry.npmjs.org/gulp-cache-bust/-/gulp-cache-bust-1.1.0.tgz"
    },
    "engines": {
        "node": ">=4.4.5",
        "npm": ">=2.15.1"
    },
    "gitHead": "bb7ad93dc495ea2e85c80a79f7619dd5719f46b7",
    "homepage": "https://github.com/furzeface/gulp-cache-bust#readme",
    "keywords": [
        "assets",
        "cache",
        "cachebust",
        "gulpplugin",
        "MD5",
        "timestamp"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "davinkevin",
            "email": "davin.kevin@gmail.com"
        },
        {
            "name": "furzeface",
            "email": "daniel@furzeface.com"
        }
    ],
    "name": "gulp-cache-bust",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/furzeface/gulp-cache-bust.git"
    },
    "scripts": {
        "coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "test": "istanbul test _mocha --report html -- test/*.js --reporter spec"
    },
    "version": "1.1.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gulp-cache-bust](#apidoc.module.gulp-cache-bust)



# <a name="apidoc.module.gulp-cache-bust"></a>[module gulp-cache-bust](#apidoc.module.gulp-cache-bust)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
