# npmdoc-react-shallow-testutils

#### api documentation for  [react-shallow-testutils (v2.0.0)](https://github.com/sheepsteak/react-shallow-testutils#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-shallow-testutils.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-shallow-testutils) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-shallow-testutils.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-shallow-testutils)

#### Replacement for TestUtils when using React's shallow rendering

[![NPM](https://nodei.co/npm/react-shallow-testutils.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-shallow-testutils)

- [https://npmdoc.github.io/node-npmdoc-react-shallow-testutils/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-shallow-testutils/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-shallow-testutils/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-shallow-testutils/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-shallow-testutils/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-shallow-testutils/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-shallow-testutils",
    "version": "2.0.0",
    "description": "Replacement for TestUtils when using React's shallow rendering",
    "main": "lib/index.js",
    "scripts": {
        "clean": "rimraf lib/",
        "compile": "babel -d lib/ src/",
        "lint": "eslint --cache .",
        "prepublish": "npm run clean && npm run compile",
        "test": "node specs/support/jasmine"
    },
    "pre-commit": [
        "lint",
        "test"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sheepsteak/react-shallow-testutils.git"
    },
    "keywords": [
        "React",
        "testing",
        "components"
    ],
    "author": "Chris Shepherd <chris@chrisshepherd.me>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/sheepsteak/react-shallow-testutils/issues"
    },
    "homepage": "https://github.com/sheepsteak/react-shallow-testutils#readme",
    "devDependencies": {
        "babel-cli": "^6.7.5",
        "babel-core": "^6.7.6",
        "babel-eslint": "^6.0.2",
        "babel-plugin-transform-export-extensions": "^6.3.13",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.3.13",
        "eslint": "^2.7.0",
        "eslint-plugin-react": "^4.3.0",
        "jasmine": "^2.3.1",
        "pre-commit": "^1.1.1",
        "react": "^15.0.1",
        "react-addons-test-utils": "^15.0.1",
        "rimraf": "2.5.2"
    },
    "peerDependencies": {
        "react": "^15.0.0",
        "react-addons-test-utils": "^15.0.0"
    },
    "dependencies": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
