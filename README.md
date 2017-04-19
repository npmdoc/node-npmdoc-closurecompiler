# npmdoc-closurecompiler

#### api documentation for  [closurecompiler (v1.6.1)](https://github.com/dcodeIO/ClosureCompiler.js#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-closurecompiler.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-closurecompiler) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-closurecompiler.svg)](https://travis-ci.org/npmdoc/node-npmdoc-closurecompiler)

#### ClosureCompiler.js: Closure Compiler for node.js. The all-round carefree package.

[![NPM](https://nodei.co/npm/closurecompiler.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/closurecompiler)

- [https://npmdoc.github.io/node-npmdoc-closurecompiler/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-closurecompiler/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-closurecompiler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-closurecompiler/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-closurecompiler/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-closurecompiler/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel Wirtz"
    },
    "bin": {
        "ccjs": "./bin/ccjs"
    },
    "bugs": {
        "url": "https://github.com/dcodeIO/ClosureCompiler.js/issues"
    },
    "contributors": [
        {
            "name": "Feross Aboukhadijeh"
        }
    ],
    "dependencies": {
        "bl": "~0.9.3",
        "closurecompiler-externs": "*",
        "tar": "~2.2.1"
    },
    "description": "ClosureCompiler.js: Closure Compiler for node.js. The all-round carefree package.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "2adde92bc8e89ff6871a11cf01a59e12650a030f",
        "tarball": "https://registry.npmjs.org/closurecompiler/-/closurecompiler-1.6.1.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "96fd199f24eaada9aa67c30164ffc720218f64a4",
    "homepage": "https://github.com/dcodeIO/ClosureCompiler.js#readme",
    "keywords": [
        "closure compiler",
        "closure",
        "compiler",
        "util",
        "utility"
    ],
    "license": "Apache-2.0",
    "main": "ClosureCompiler.js",
    "maintainers": [
        {
            "name": "dcode"
        }
    ],
    "name": "closurecompiler",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dcodeIO/ClosureCompiler.js.git"
    },
    "scripts": {
        "compile": "node bin/ccjs ClosureCompiler.js --externs=node --compilation_level=SIMPLE_OPTIMIZATIONS > ClosureCompiler.min.js",
        "configure": "node scripts/configure.js",
        "install": "npm run-script configure",
        "make": "npm run-script compile && npm test",
        "test": "node tests/test.js",
        "update": "npm run-script configure"
    },
    "version": "1.6.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
