# npmdoc-raml2html

#### api documentation for  [raml2html (v6.1.1)](https://github.com/raml2html/raml2html)  [![npm package](https://img.shields.io/npm/v/npmdoc-raml2html.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-raml2html) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-raml2html.svg)](https://travis-ci.org/npmdoc/node-npmdoc-raml2html)

#### RAML to HTML documentation generator

[![NPM](https://nodei.co/npm/raml2html.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/raml2html)

- [https://npmdoc.github.io/node-npmdoc-raml2html/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-raml2html/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-raml2html/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-raml2html/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-raml2html/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-raml2html/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "raml2html",
    "description": "RAML to HTML documentation generator",
    "version": "6.1.1",
    "author": {
        "name": "Kevin Renskers"
    },
    "bugs": {
        "url": "https://github.com/raml2html/raml2html/issues"
    },
    "dependencies": {
        "marked": "0.3.x",
        "minimize": "2.1.x",
        "nunjucks": "2.5.x",
        "nunjucks-markdown": "2.0.x",
        "raml2html-default-theme": "2.x",
        "raml2obj": "5.x",
        "yargs": "7.1.x"
    },
    "devDependencies": {
        "eslint": "3.19.x",
        "eslint-plugin-prettier": "2.0.x",
        "prettier": "1.x"
    },
    "homepage": "https://github.com/raml2html/raml2html",
    "keywords": [
        "RAML"
    ],
    "license": "MIT",
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/raml2html/raml2html.git"
    },
    "preferGlobal": true,
    "scripts": {
        "lint": "eslint . --fix"
    },
    "bin": {
        "raml2html": "./bin/raml2html"
    },
    "files": [
        "index.js",
        "bin/raml2html"
    ],
    "engines": {
        "node": ">=4"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
