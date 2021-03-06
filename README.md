# npmtest-passport-azure-ad

#### basic test coverage for  [passport-azure-ad (v3.0.6)](https://github.com/AzureAD/passport-azure-ad#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-passport-azure-ad.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-passport-azure-ad) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-passport-azure-ad.svg)](https://travis-ci.org/npmtest/node-npmtest-passport-azure-ad)

#### OIDC and Bearer Passport strategies for Azure Active Directory

[![NPM](https://nodei.co/npm/passport-azure-ad.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/passport-azure-ad)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-passport-azure-ad/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-azure-ad/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-passport-azure-ad/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-passport-azure-ad/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-passport-azure-ad/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-passport-azure-ad/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-passport-azure-ad/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-passport-azure-ad/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-passport-azure-ad/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-azure-ad/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-passport-azure-ad/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-passport-azure-ad/build/test-report.html](https://npmtest.github.io/node-npmtest-passport-azure-ad/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-passport-azure-ad/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-passport-azure-ad/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-passport-azure-ad/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-passport-azure-ad/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-passport-azure-ad/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-passport-azure-ad/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-passport-azure-ad/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-passport-azure-ad/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "azuread",
        "url": "http://microsoft.com/"
    },
    "bugs": {
        "url": "https://github.com/AzureAD/passport-azure-ad/issues"
    },
    "dependencies": {
        "async": "^1.5.2",
        "base64url": "^2.0.0",
        "bunyan": "^1.8.0",
        "cache-manager": "^2.0.0",
        "jwk-to-pem": "^1.2.6",
        "jws": "^3.1.3",
        "lodash": "^4.11.2",
        "oauth": "0.9.14",
        "passport": "^0.3.2",
        "pkginfo": "^0.4.0",
        "request": "^2.72.0",
        "valid-url": "^1.0.6"
    },
    "description": "OIDC and Bearer Passport strategies for Azure Active Directory",
    "devDependencies": {
        "adal-node": "^0.1.22",
        "azure-keyvault": "^0.11.0",
        "chai": "2.x.x",
        "chai-passport-strategy": "1.x.x",
        "chromedriver": "^2.24.1",
        "eslint": "^2.9.0",
        "eslint-config-oniyi": "^3.0.0",
        "grunt": "^1.0.1",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-nodeunit": "^1.0.0",
        "grunt-contrib-uglify": "^1.0.1",
        "grunt-contrib-watch": "^1.0.0",
        "grunt-eslint": "^18.1.0",
        "grunt-mocha-test": "^0.12.7",
        "mocha": "^3.0.2",
        "nodeunit": "^0.9.1",
        "selenium-webdriver": "^3.0.0",
        "server-graceful-shutdown": "^0.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "05d787e986a3edbf150d4bb4112581fb04c59f85",
        "tarball": "https://registry.npmjs.org/passport-azure-ad/-/passport-azure-ad-3.0.6.tgz"
    },
    "engines": {
        "node": ">= 4.0.1"
    },
    "gitHead": "d1fb360fcf02da89624e47126a8380c371768dc6",
    "homepage": "https://github.com/AzureAD/passport-azure-ad#readme",
    "keywords": [
        "azure active directory",
        "aad",
        "adfs",
        "sso",
        "oidc",
        "bearer",
        "shibboleth"
    ],
    "license": "MIT",
    "main": "./lib",
    "maintainers": [
        {
            "name": "msopentech"
        },
        {
            "name": "azuread"
        }
    ],
    "name": "passport-azure-ad",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/AzureAD/passport-azure-ad.git"
    },
    "scripts": {
        "test": "grunt run_tests"
    },
    "version": "3.0.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
