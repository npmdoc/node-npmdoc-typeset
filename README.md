# npmdoc-typeset

#### basic api documentation for  [typeset (v0.2.2)](https://github.com/davidmerfield/Typeset.js)  [![npm package](https://img.shields.io/npm/v/npmdoc-typeset.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-typeset) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-typeset.svg)](https://travis-ci.org/npmdoc/node-npmdoc-typeset)

#### Typesetting for the web

[![NPM](https://nodei.co/npm/typeset.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/typeset)

- [https://npmdoc.github.io/node-npmdoc-typeset/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-typeset/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-typeset/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-typeset/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-typeset/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-typeset/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Merfield"
    },
    "bin": {
        "typeset-js": "src/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/davidmerfield/Typeset.js/issues"
    },
    "dependencies": {
        "cheerio": "^0.19.0",
        "commander": "^2.8.1",
        "html-entities": "^1.1.2",
        "hypher": "^0.2.3"
    },
    "description": "Typesetting for the web",
    "devDependencies": {
        "chai": "^3.2.0",
        "html-minifier": "^0.7.2",
        "mocha": "^2.2.5",
        "webpack": "^1.11.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9804deacff428159d2aabc9e82bd9fbd5236a3ea",
        "tarball": "https://registry.npmjs.org/typeset/-/typeset-0.2.2.tgz"
    },
    "homepage": "https://github.com/davidmerfield/Typeset.js",
    "keywords": [
        "type",
        "typeset",
        "typography",
        "dropcap",
        "smallcap",
        "hyphenation"
    ],
    "license": "MIT",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "davidmerfield"
        }
    ],
    "name": "typeset",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/davidmerfield/Typeset.js.git"
    },
    "scripts": {
        "build": "npm run clean; npm run build-dev; npm run build-prod",
        "build-dev": "./node_modules/webpack/bin/webpack.js",
        "build-prod": "PROD=1 ./node_modules/webpack/bin/webpack.js",
        "clean": "rm -rf build/",
        "test": "mocha -u bdd -R spec -t 500 --recursive",
        "watch": "mocha src/ test/ -u bdd -R spec -t 500 --recursive --watch"
    },
    "version": "0.2.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
