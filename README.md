# api documentation for  [json2csv (v3.7.3)](https://github.com/zemirco/json2csv#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-json2csv.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-json2csv) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-json2csv.svg)](https://travis-ci.org/npmdoc/node-npmdoc-json2csv)
#### Convert JSON to CSV

[![NPM](https://nodei.co/npm/json2csv.png?downloads=true)](https://www.npmjs.com/package/json2csv)

[![apidoc](https://npmdoc.github.io/node-npmdoc-json2csv/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-json2csv_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-json2csv/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-json2csv/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-json2csv/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mirco Zeiss",
        "email": "mirco.zeiss@gmail.com"
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
            "name": "azhang",
            "email": "azhang@bottlenose.com"
        },
        {
            "name": "knownasilya",
            "email": "ilya@burstcreations.com"
        },
        {
            "name": "zemirco",
            "email": "mirco.zeiss@gmail.com"
        }
    ],
    "name": "json2csv",
    "optionalDependencies": {},
    "preferGlobal": "true",
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module json2csv](#apidoc.module.json2csv)



# <a name="apidoc.module.json2csv"></a>[module json2csv](#apidoc.module.json2csv)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
