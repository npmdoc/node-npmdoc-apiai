# npmdoc-apiai

#### api documentation for  [apiai (v4.0.2)](https://github.com/api-ai/api-ai-node-js#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-apiai.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-apiai) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-apiai.svg)](https://travis-ci.org/npmdoc/node-npmdoc-apiai)

#### Node.js SDK for api.ai

[![NPM](https://nodei.co/npm/apiai.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/apiai)

- [https://npmdoc.github.io/node-npmdoc-apiai/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-apiai/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-apiai/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-apiai/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-apiai/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-apiai/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "apiai",
    "version": "4.0.2",
    "description": "Node.js SDK for api.ai",
    "main": "index.js",
    "types": "index.d.ts",
    "directories": {
        "example": "examples"
    },
    "files": [
        "index.js",
        "index.d.ts",
        "module/"
    ],
    "scripts": {
        "build:live": "NODE_ENV=development nodemon --exec ./node_modules/.bin/ts-node -- ./typescript_examples/text_request.ts"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/api-ai/apiai-nodejs-client.git"
    },
    "keywords": [
        "apiai",
        "NLU",
        "natural",
        "language",
        "understanding"
    ],
    "author": "Dmitriy Kuragin",
    "license": "Apache 2.0",
    "bugs": {
        "url": "https://github.com/api-ai/api-ai-node-js/issues"
    },
    "homepage": "https://github.com/api-ai/api-ai-node-js#readme",
    "devDependencies": {
        "@types/node": "^7.0.5",
        "nodemon": "^1.11.0",
        "ts-node": "^2.1.0",
        "typescript": "^2.1.6",
        "typing": "^0.1.9",
        "typings": "^2.0.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
