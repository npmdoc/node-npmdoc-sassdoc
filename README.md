# npmdoc-sassdoc

#### api documentation for  [sassdoc (v2.2.2)](http://sassdoc.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-sassdoc.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sassdoc) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sassdoc.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sassdoc)

#### Release the docs!

[![NPM](https://nodei.co/npm/sassdoc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sassdoc)

- [https://npmdoc.github.io/node-npmdoc-sassdoc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sassdoc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sassdoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sassdoc/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sassdoc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sassdoc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Hugo Giraudel",
        "url": "http://hugogiraudel.com"
    },
    "bin": {
        "sassdoc": "bin/sassdoc"
    },
    "browser": {
        "./dist/notifier.js": false,
        "./dist/exclude.js": false,
        "./dist/cli.js": false,
        "./dist/recurse.js": false,
        "vinyl-fs": false,
        "glob2base": false,
        "docopt": false,
        "glob": false,
        "js-yaml": false,
        "minimatch": false,
        "mkdirp": false,
        "multipipe": false,
        "rimraf": false,
        "safe-wipe": false,
        "sass-convert": false,
        "sassdoc-theme-default": false,
        "update-notifier": false,
        "through2": false,
        "concat-stream": false,
        "vinyl-source-stream": false
    },
    "bugs": {
        "url": "https://github.com/SassDoc/sassdoc/issues"
    },
    "contributors": [
        {
            "name": "Fabrice Weinberg",
            "url": "https://twitter.com/fweinb"
        },
        {
            "name": "Valérian Galliat",
            "url": "https://val.codejam.info"
        },
        {
            "name": "Pascal Duez",
            "url": "https://twitter.com/pascalduez"
        }
    ],
    "dependencies": {
        "babel-runtime": "^6.22.0",
        "chalk": "^1.0.0",
        "concat-stream": "^1.4.7",
        "docopt": "^0.6.1",
        "glob": "^7.1.1",
        "glob2base": "0.0.12",
        "js-yaml": "^3.2.1",
        "lodash.difference": "^4.5.0",
        "lodash.uniq": "^4.5.0",
        "minimatch": "^3.0.3",
        "mkdirp": "^0.5.0",
        "multipipe": "^1.0.2",
        "rimraf": "^2.3.2",
        "safe-wipe": "0.*",
        "sass-convert": "^0.5.0",
        "sassdoc-theme-default": "^2.5.2",
        "scss-comment-parser": "^0.8.1",
        "strip-indent": "^2.0.0",
        "through2": "^1.1.1",
        "update-notifier": "^2.1.0",
        "vinyl-fs": "^2.4.4",
        "vinyl-source-stream": "^1.0.0"
    },
    "description": "Release the docs!",
    "devDependencies": {
        "babel-cli": "^6.24.0",
        "babel-plugin-transform-builtin-extend": "^1.1.2",
        "babel-plugin-transform-runtime": "^6.22.0",
        "babel-preset-env": "^1.2.2",
        "coveralls": "^2.11.2",
        "dateformat": "^2.0.0",
        "jsesc": "^2.4.0",
        "mocha": "^3.2.0",
        "nyc": "^10.1.2",
        "opn-cli": "^3.1.0",
        "sinon": "^2.1.0",
        "standard": "^9.0.2",
        "vinyl": "^2.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "785eb72f4b469690177054b74fd5f909f67bd70e",
        "tarball": "https://registry.npmjs.org/sassdoc/-/sassdoc-2.2.2.tgz"
    },
    "files": [
        "bin",
        "dist",
        "index.js",
        "CHANGELOG.md",
        "UPGRADE-2.0.md",
        "LICENCE.md",
        "README.md"
    ],
    "gitHead": "aa59c29ca37ccf1f39ea7be5bfa8ec52cc10f04b",
    "homepage": "http://sassdoc.com",
    "keywords": [
        "sass",
        "scss",
        "css",
        "doc",
        "documentation",
        "comments",
        "theme"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "hugogiraudel"
        },
        {
            "name": "fweinb"
        },
        {
            "name": "valeriangalliat"
        },
        {
            "name": "pascalduez"
        }
    ],
    "name": "sassdoc",
    "nyc": {
        "exclude": [
            "**/*.test.js",
            "test"
        ]
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/SassDoc/sassdoc.git"
    },
    "scripts": {
        "test": "make"
    },
    "standard": {
        "env": {
            "mocha": true
        }
    },
    "version": "2.2.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
