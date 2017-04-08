# api documentation for  [apiai (v4.0.2)](https://github.com/api-ai/api-ai-node-js#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-apiai.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-apiai) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-apiai.svg)](https://travis-ci.org/npmdoc/node-npmdoc-apiai)
#### Node.js SDK for api.ai

[![NPM](https://nodei.co/npm/apiai.png?downloads=true)](https://www.npmjs.com/package/apiai)

[![apidoc](https://npmdoc.github.io/node-npmdoc-apiai/build/screenCapture.buildNpmdoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-apiai%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-apiai/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-apiai/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-apiai/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dmitriy Kuragin"
    },
    "bugs": {
        "url": "https://github.com/api-ai/api-ai-node-js/issues"
    },
    "dependencies": {},
    "description": "Node.js SDK for api.ai",
    "devDependencies": {
        "@types/node": "^7.0.5",
        "nodemon": "^1.11.0",
        "ts-node": "^2.1.0",
        "typescript": "^2.1.6",
        "typing": "^0.1.9",
        "typings": "^2.0.0"
    },
    "directories": {
        "example": "examples"
    },
    "dist": {
        "shasum": "9a4d6921877e43cee4719eb73609da1d520ac857",
        "tarball": "https://registry.npmjs.org/apiai/-/apiai-4.0.2.tgz"
    },
    "files": [
        "index.js",
        "index.d.ts",
        "module/"
    ],
    "gitHead": "a1824b0a0d315037807fdc7c5c8e304d43e3d5b4",
    "homepage": "https://github.com/api-ai/api-ai-node-js#readme",
    "keywords": [
        "apiai",
        "NLU",
        "natural",
        "language",
        "understanding"
    ],
    "license": "Apache 2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "sstepashka",
            "email": "kuragin@speaktoit.com"
        }
    ],
    "name": "apiai",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/api-ai/apiai-nodejs-client.git"
    },
    "scripts": {
        "build:live": "NODE_ENV=development nodemon --exec ./node_modules/.bin/ts-node -- ./typescript_examples/text_request.ts"
    },
    "types": "index.d.ts",
    "version": "4.0.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module apiai](#apidoc.module.apiai)
1.  object <span class="apidocSignatureSpan">apiai.</span>contexts_request
1.  object <span class="apidocSignatureSpan">apiai.</span>delete_contexts_request
1.  object <span class="apidocSignatureSpan">apiai.</span>event_request
1.  object <span class="apidocSignatureSpan">apiai.</span>exceptions
1.  object <span class="apidocSignatureSpan">apiai.</span>json_api_request
1.  object <span class="apidocSignatureSpan">apiai.</span>query_request
1.  object <span class="apidocSignatureSpan">apiai.</span>request
1.  object <span class="apidocSignatureSpan">apiai.</span>text_request
1.  object <span class="apidocSignatureSpan">apiai.</span>tts_request
1.  object <span class="apidocSignatureSpan">apiai.</span>user_entities_request
1.  object <span class="apidocSignatureSpan">apiai.</span>voice_request

#### [module apiai.contexts_request](#apidoc.module.apiai.contexts_request)
1.  [function <span class="apidocSignatureSpan">apiai.contexts_request.</span>ContextsRequest (application, contexts, options)](#apidoc.element.apiai.contexts_request.ContextsRequest)

#### [module apiai.delete_contexts_request](#apidoc.module.apiai.delete_contexts_request)
1.  [function <span class="apidocSignatureSpan">apiai.delete_contexts_request.</span>DeleteContextsRequest (application, options)](#apidoc.element.apiai.delete_contexts_request.DeleteContextsRequest)

#### [module apiai.event_request](#apidoc.module.apiai.event_request)
1.  [function <span class="apidocSignatureSpan">apiai.event_request.</span>EventRequest (application, event, options)](#apidoc.element.apiai.event_request.EventRequest)

#### [module apiai.exceptions](#apidoc.module.apiai.exceptions)
1.  [function <span class="apidocSignatureSpan">apiai.exceptions.</span>ServerError (statusCode, responseBody, message)](#apidoc.element.apiai.exceptions.ServerError)

#### [module apiai.json_api_request](#apidoc.module.apiai.json_api_request)
1.  [function <span class="apidocSignatureSpan">apiai.json_api_request.</span>JSONApiRequest ()](#apidoc.element.apiai.json_api_request.JSONApiRequest)

#### [module apiai.query_request](#apidoc.module.apiai.query_request)
1.  [function <span class="apidocSignatureSpan">apiai.query_request.</span>QueryRequest (application, options)](#apidoc.element.apiai.query_request.QueryRequest)

#### [module apiai.request](#apidoc.module.apiai.request)
1.  [function <span class="apidocSignatureSpan">apiai.request.</span>Request (application, options)](#apidoc.element.apiai.request.Request)

#### [module apiai.text_request](#apidoc.module.apiai.text_request)
1.  [function <span class="apidocSignatureSpan">apiai.text_request.</span>TextRequest (application, query, options)](#apidoc.element.apiai.text_request.TextRequest)

#### [module apiai.tts_request](#apidoc.module.apiai.tts_request)
1.  [function <span class="apidocSignatureSpan">apiai.tts_request.</span>TTSRequest (application, text, options)](#apidoc.element.apiai.tts_request.TTSRequest)

#### [module apiai.user_entities_request](#apidoc.module.apiai.user_entities_request)
1.  [function <span class="apidocSignatureSpan">apiai.user_entities_request.</span>UserEntitiesRequest (application, user_entities_body, options)](#apidoc.element.apiai.user_entities_request.UserEntitiesRequest)

#### [module apiai.voice_request](#apidoc.module.apiai.voice_request)
1.  [function <span class="apidocSignatureSpan">apiai.voice_request.</span>VoiceRequest (application, options)](#apidoc.element.apiai.voice_request.VoiceRequest)



# <a name="apidoc.module.apiai"></a>[module apiai](#apidoc.module.apiai)



# <a name="apidoc.module.apiai.contexts_request"></a>[module apiai.contexts_request](#apidoc.module.apiai.contexts_request)

#### <a name="apidoc.element.apiai.contexts_request.ContextsRequest"></a>[function <span class="apidocSignatureSpan">apiai.contexts_request.</span>ContextsRequest (application, contexts, options)](#apidoc.element.apiai.contexts_request.ContextsRequest)
- description and source-code
```javascript
function ContextsRequest(application, contexts, options) {
    var self = this;

    self.contexts = contexts;
    self.sessionId = options.sessionId;

    ContextsRequest.super_.apply(this, [application, options]);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.apiai.delete_contexts_request"></a>[module apiai.delete_contexts_request](#apidoc.module.apiai.delete_contexts_request)

#### <a name="apidoc.element.apiai.delete_contexts_request.DeleteContextsRequest"></a>[function <span class="apidocSignatureSpan">apiai.delete_contexts_request.</span>DeleteContextsRequest (application, options)](#apidoc.element.apiai.delete_contexts_request.DeleteContextsRequest)
- description and source-code
```javascript
function DeleteContextsRequest(application, options) {
    var self = this;

    self.sessionId = options.sessionId;

    DeleteContextsRequest.super_.apply(this, [application, options]);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.apiai.event_request"></a>[module apiai.event_request](#apidoc.module.apiai.event_request)

#### <a name="apidoc.element.apiai.event_request.EventRequest"></a>[function <span class="apidocSignatureSpan">apiai.event_request.</span>EventRequest (application, event, options)](#apidoc.element.apiai.event_request.EventRequest)
- description and source-code
```javascript
function EventRequest(application, event, options) {
    EventRequest.super_.apply(this, [application, options]);

    var self = this;
    self.event = event;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.apiai.exceptions"></a>[module apiai.exceptions](#apidoc.module.apiai.exceptions)

#### <a name="apidoc.element.apiai.exceptions.ServerError"></a>[function <span class="apidocSignatureSpan">apiai.exceptions.</span>ServerError (statusCode, responseBody, message)](#apidoc.element.apiai.exceptions.ServerError)
- description and source-code
```javascript
function ServerError(statusCode, responseBody, message) {
    var self = this;

    Error.captureStackTrace(this, ServerError);

    self.statusCode = statusCode;
    self.responseBody = responseBody;

    this.name = this.constructor.name;
    this.message = message;

    ServerError.super_.apply(this, []);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.apiai.json_api_request"></a>[module apiai.json_api_request](#apidoc.module.apiai.json_api_request)

#### <a name="apidoc.element.apiai.json_api_request.JSONApiRequest"></a>[function <span class="apidocSignatureSpan">apiai.json_api_request.</span>JSONApiRequest ()](#apidoc.element.apiai.json_api_request.JSONApiRequest)
- description and source-code
```javascript
function JSONApiRequest() {
    JSONApiRequest.super_.apply(this, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.apiai.query_request"></a>[module apiai.query_request](#apidoc.module.apiai.query_request)

#### <a name="apidoc.element.apiai.query_request.QueryRequest"></a>[function <span class="apidocSignatureSpan">apiai.query_request.</span>QueryRequest (application, options)](#apidoc.element.apiai.query_request.QueryRequest)
- description and source-code
```javascript
function QueryRequest(application, options) {
    var self = this;

    self.language = application.language;

    if ('timezone' in options) {
        self.timezone = options.timezone;
    }

    if ('resetContexts' in options) {
        self.resetContexts = options.resetContexts;
    }

    if ('contexts' in options) {
        self.contexts = options.contexts;
    }

    if ('entities' in options) {
        self.entities = options.entities;
    }

    if ('sessionId' in options) {
        self.sessionId = options.sessionId;
    } else {
        throw Error(
            'Now \'sessionId\' is required parameter. Please add this parameter to \'options\' of request.\n' +
            'Like following example:\n' +
            '> var app = ...\n' +
            '> request = app.textRequest("Hello", {sessionId: "UNIQUE_SESSION_ID"})\n' +
            '> ... \n'
        );
    }

    if ('version' in options) {
        self.version = options.version;
    }

    if ('requestSource' in application) {
        self.requestSource = application.requestSource;
    }

    if ('originalRequest' in options) {
        self.originalRequest = options.originalRequest;
    }

    QueryRequest.super_.apply(this, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.apiai.request"></a>[module apiai.request](#apidoc.module.apiai.request)

#### <a name="apidoc.element.apiai.request.Request"></a>[function <span class="apidocSignatureSpan">apiai.request.</span>Request (application, options)](#apidoc.element.apiai.request.Request)
- description and source-code
```javascript
function Request(application, options) {
    var self = this;

    self.clientAccessToken = application.clientAccessToken;

    self.hostname = application.hostname;

    self.endpoint = options.endpoint;
    self.requestSource = application.requestSource;

    var _http = application.secure ? https : http;

    var requestOptions = self._requestOptions();

    requestOptions.agent = application._agent;

    var request = _http.request(requestOptions, function(response) {
        self._handleResponse(response);
    });

    request.on('error', function(error) {
        self.emit('error', error);
    });

    self.request = request;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.apiai.text_request"></a>[module apiai.text_request](#apidoc.module.apiai.text_request)

#### <a name="apidoc.element.apiai.text_request.TextRequest"></a>[function <span class="apidocSignatureSpan">apiai.text_request.</span>TextRequest (application, query, options)](#apidoc.element.apiai.text_request.TextRequest)
- description and source-code
```javascript
function TextRequest(application, query, options) {
    TextRequest.super_.apply(this, [application, options]);

    var self = this;
    self.query = query;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.apiai.tts_request"></a>[module apiai.tts_request](#apidoc.module.apiai.tts_request)

#### <a name="apidoc.element.apiai.tts_request.TTSRequest"></a>[function <span class="apidocSignatureSpan">apiai.tts_request.</span>TTSRequest (application, text, options)](#apidoc.element.apiai.tts_request.TTSRequest)
- description and source-code
```javascript
function TTSRequest(application, text, options) {
    var self = this;

    self.text = text;

    self.language = options.language || options.lang || 'en-US';

    if('writeStream' in options){
        self.writeStream = options.writeStream;
    } else {
        throw new Error('\'writeStream\' cannot be empty.');
    }

    TTSRequest.super_.apply(this, [application, options]);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.apiai.user_entities_request"></a>[module apiai.user_entities_request](#apidoc.module.apiai.user_entities_request)

#### <a name="apidoc.element.apiai.user_entities_request.UserEntitiesRequest"></a>[function <span class="apidocSignatureSpan">apiai.user_entities_request.</span>UserEntitiesRequest (application, user_entities_body, options)](#apidoc.element.apiai.user_entities_request.UserEntitiesRequest)
- description and source-code
```javascript
function UserEntitiesRequest(application, user_entities_body, options) {
    var self = this;

    self.user_entities_body = user_entities_body;

    UserEntitiesRequest.super_.apply(this, [application, options]);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.apiai.voice_request"></a>[module apiai.voice_request](#apidoc.module.apiai.voice_request)

#### <a name="apidoc.element.apiai.voice_request.VoiceRequest"></a>[function <span class="apidocSignatureSpan">apiai.voice_request.</span>VoiceRequest (application, options)](#apidoc.element.apiai.voice_request.VoiceRequest)
- description and source-code
```javascript
function VoiceRequest(application, options) {
    var self = this;
    self.boundary = self._generateBoundary();

    VoiceRequest.super_.apply(this, [application, options]);

    self._sendMetaData();
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
