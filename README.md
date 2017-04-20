# npmdoc-fuse-bindings

#### api documentation for  [fuse-bindings (v2.11.1)](https://github.com/mafintosh/fuse-bindings)  [![npm package](https://img.shields.io/npm/v/npmdoc-fuse-bindings.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-fuse-bindings) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-fuse-bindings.svg)](https://travis-ci.org/npmdoc/node-npmdoc-fuse-bindings)

#### Fully maintained fuse bindings for Node that aims to cover the entire FUSE api

[![NPM](https://nodei.co/npm/fuse-bindings.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fuse-bindings)

- [https://npmdoc.github.io/node-npmdoc-fuse-bindings/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fuse-bindings/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fuse-bindings/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fuse-bindings/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-fuse-bindings/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-fuse-bindings/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "fuse-bindings",
    "version": "2.11.1",
    "description": "Fully maintained fuse bindings for Node that aims to cover the entire FUSE api",
    "main": "index.js",
    "scripts": {
        "install": "prebuild --install",
        "test": "standard && tape test/*.js",
        "rebuild": "prebuild --compile",
        "prebuild": "prebuild --all --strip --verbose"
    },
    "gypfile": true,
    "dependencies": {
        "bindings": "^1.2.1",
        "nan": "^2.3.5",
        "prebuild": "^4.2.2",
        "xtend": "^4.0.1"
    },
    "devDependencies": {
        "concat-stream": "^1.4.7",
        "standard": "^7.1.2",
        "tape": "^4.6.0"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/mafintosh/fuse-bindings.git"
    },
    "author": "Mathias Buus (@mafintosh)",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/mafintosh/fuse-bindings/issues"
    },
    "homepage": "https://github.com/mafintosh/fuse-bindings"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
