# npmdoc-json2csv

#### basic api documentation for  [json2csv (v3.7.3)](https://github.com/zemirco/json2csv#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-json2csv.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-json2csv) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-json2csv.svg)](https://travis-ci.org/npmdoc/node-npmdoc-json2csv)

#### Convert JSON to CSV

[![NPM](https://nodei.co/npm/json2csv.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/json2csv)

- [https://npmdoc.github.io/node-npmdoc-json2csv/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-json2csv/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-json2csv/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-json2csv/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-json2csv/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-json2csv/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mirco Zeiss"
    },
    "bin": {
        "json2csv": "./bin/json2csv.js"
    },
    "bugs": {
        "url": "https://github.com/zemirco/json2csv/issues"
    },
    "dependencies": {
        "cli-table": "^0.3.1",
        "commander": "^2.8.1",
        "debug": "^2.2.0",
        "flat": "^2.0.0",
        "lodash.clonedeep": "^4.3.0",
        "lodash.flatten": "^4.2.0",
        "lodash.get": "^4.3.0",
        "lodash.set": "^4.3.0",
        "lodash.uniq": "^4.3.0",
        "path-is-absolute": "^1.0.0"
    },
    "description": "Convert JSON to CSV",
    "devDependencies": {
        "async": "^2.0.1",
        "docpress": "^0.7.0",
        "eslint": "^3.3.1",
        "git-update-ghpages": "^1.3.0",
        "in-publish": "^2.0.0",
        "istanbul": "^0.4.3",
        "standard-version": "^4.0.0",
        "tap-spec": "^4.1.0",
        "tape": "^4.0.0",
        "webpack": "^1.13.1"
    },
    "directories": {},
    "dist": {
        "shasum": "dacfdfa7fb0c1b1b163868dc75f3902d023354ec",
        "tarball": "https://registry.npmjs.org/json2csv/-/json2csv-3.7.3.tgz"
    },
    "gitHead": "19e77972578e73748baa0936c1e200be41b906a3",
    "homepage": "https://github.com/zemirco/json2csv#readme",
    "keywords": [
        "json",
        "to",
        "csv",
        "export",
        "convert",
        "parse"
    ],
    "license": "MIT",
    "main": "./lib/json2csv.js",
    "maintainers": [
        {
            "name": "azhang"
        },
        {
            "name": "knownasilya"
        },
        {
            "name": "zemirco"
        }
    ],
    "name": "json2csv",
    "optionalDependencies": {},
    "preferGlobal": "true",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zemirco/json2csv.git"
    },
    "scripts": {
        "before:publish": "npm test && npm run build && npm run deploy:docs && npm run release",
        "build": "webpack",
        "deploy:docs": "docpress b && git-update-ghpages zemirco/json2csv _docpress",
        "prepublish": "in-publish && npm run before:publish || not-in-publish",
        "release": "standard-version",
        "test": "node test | tap-spec",
        "test-coverage": "istanbul cover test/index.js --report lcovonly | tap-spec"
    },
    "version": "3.7.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
