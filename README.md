# npmdoc-mem-fs-editor

#### api documentation for  mem-fs-editor (v3.0.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-mem-fs-editor.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mem-fs-editor) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mem-fs-editor.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mem-fs-editor)

#### File edition helpers working on top of mem-fs

[![NPM](https://nodei.co/npm/mem-fs-editor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mem-fs-editor)

- [https://npmdoc.github.io/node-npmdoc-mem-fs-editor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mem-fs-editor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mem-fs-editor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mem-fs-editor/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mem-fs-editor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mem-fs-editor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "mem-fs-editor",
    "version": "3.0.2",
    "description": "File edition helpers working on top of mem-fs",
    "scripts": {
        "pretest": "eslint **/*.js",
        "test": "jest",
        "prepublish": "nsp check"
    },
    "repository": "SBoudrias/mem-fs-editor",
    "author": "Simon Boudrias",
    "license": "MIT",
    "main": "lib/index.js",
    "files": [
        "lib"
    ],
    "dependencies": {
        "commondir": "^1.0.1",
        "deep-extend": "^0.4.0",
        "ejs": "^2.3.1",
        "glob": "^7.0.3",
        "globby": "^6.1.0",
        "mkdirp": "^0.5.0",
        "multimatch": "^2.0.0",
        "rimraf": "^2.2.8",
        "through2": "^2.0.0",
        "vinyl": "^2.0.1"
    },
    "devDependencies": {
        "coveralls": "^2.11.15",
        "escape-regexp": "0.0.1",
        "eslint": "^3.14.1",
        "eslint-config-xo-space": "^0.15.0",
        "jest": "^18.1.0",
        "mem-fs": "^1.0.0",
        "nsp": "^2.6.2",
        "sinon": "^1.12.2"
    },
    "jest": {
        "collectCoverage": true,
        "coverageDirectory": "coverage",
        "testEnvironment": "node"
    },
    "eslintConfig": {
        "extends": "xo-space",
        "env": {
            "jest": true
        },
        "rules": {
            "eqeqeq": [
                2,
                "allow-null"
            ],
            "no-eq-null": 0
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
