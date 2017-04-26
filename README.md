# npmdoc-passport-saml

#### basic api documentation for  [passport-saml (v0.15.0)](https://github.com/bergie/passport-saml)  [![npm package](https://img.shields.io/npm/v/npmdoc-passport-saml.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-passport-saml) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-passport-saml.svg)](https://travis-ci.org/npmdoc/node-npmdoc-passport-saml)

#### SAML 2.0 authentication strategy for Passport

[![NPM](https://nodei.co/npm/passport-saml.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/passport-saml)

- [https://npmdoc.github.io/node-npmdoc-passport-saml/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-passport-saml/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-passport-saml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-passport-saml/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-passport-saml/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-passport-saml/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Henri Bergius",
        "url": "http://bergie.iki.fi"
    },
    "bugs": {
        "url": "https://github.com/bergie/passport-saml/issues"
    },
    "contributors": [
        {
            "name": "Michael Bosworth"
        },
        {
            "name": "Herbert Vojčík"
        },
        {
            "name": "Peter Loer"
        }
    ],
    "dependencies": {
        "passport-strategy": "*",
        "q": "1.1.x",
        "xml-crypto": "0.8.x",
        "xml-encryption": "~0.7",
        "xml2js": "0.4.x",
        "xmlbuilder": "2.5.x",
        "xmldom": "0.1.x"
    },
    "description": "SAML 2.0 authentication strategy for Passport",
    "devDependencies": {
        "body-parser": "1.9.x",
        "ejs": "1.0.x",
        "express": "4.x",
        "jshint": "*",
        "mocha": "*",
        "passport": "0.3.x",
        "request": "*",
        "should": "*",
        "sinon": "^1.10.2"
    },
    "directories": {},
    "dist": {
        "shasum": "7d45c07baaf80d8e2cf898367132a5e4c0535cad",
        "tarball": "https://registry.npmjs.org/passport-saml/-/passport-saml-0.15.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "525748647c8a8c6e79073bf8965c639c36f262b5",
    "homepage": "https://github.com/bergie/passport-saml",
    "keywords": [
        "saml",
        "adfs",
        "sso",
        "shibboleth"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/bergie/passport-saml/raw/master/LICENSE"
        }
    ],
    "main": "./lib/passport-saml",
    "maintainers": [
        {
            "name": "bergie"
        },
        {
            "name": "ploer"
        }
    ],
    "name": "passport-saml",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bergie/passport-saml.git"
    },
    "scripts": {
        "jshint": "jshint lib",
        "test": "mocha"
    },
    "version": "0.15.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
