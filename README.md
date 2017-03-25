# api documentation for  [eslint-config-airbnb (v14.1.0)](https://github.com/airbnb/javascript)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-eslint-config-airbnb.svg)](https://travis-ci.org/npmdoc/node-npmdoc-eslint-config-airbnb)
#### Airbnb's ESLint config, following our styleguide

[![NPM](https://nodei.co/npm/eslint-config-airbnb.png?downloads=true)](https://www.npmjs.com/package/eslint-config-airbnb)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-config-airbnb/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-eslint_config_airbnb_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-config-airbnb/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-eslint-config-airbnb/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Jake Teton-Landis",
        "url": "https://twitter.com/@jitl"
    },
    "bugs": {
        "url": "https://github.com/airbnb/javascript/issues"
    },
    "contributors": [
        {
            "name": "Jake Teton-Landis",
            "url": "https://twitter.com/jitl"
        },
        {
            "name": "Jordan Harband",
            "email": "ljharb@gmail.com",
            "url": "http://ljharb.codes"
        },
        {
            "name": "Harrison Shoff",
            "url": "https://twitter.com/hshoff"
        }
    ],
    "dependencies": {
        "eslint-config-airbnb-base": "^11.1.0"
    },
    "description": "Airbnb's ESLint config, following our styleguide",
    "devDependencies": {
        "babel-preset-airbnb": "^2.2.3",
        "babel-tape-runner": "^2.0.1",
        "editorconfig-tools": "^0.1.1",
        "eslint": "^3.15.0",
        "eslint-find-rules": "^1.14.3",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-react": "^6.9.0",
        "in-publish": "^2.0.0",
        "react": ">= 0.13.0",
        "safe-publish-latest": "^1.1.1",
        "tape": "^4.6.3"
    },
    "directories": {},
    "dist": {
        "shasum": "355d290040bbf8e00bf8b4b19f4b70cbe7c2317f",
        "tarball": "https://registry.npmjs.org/eslint-config-airbnb/-/eslint-config-airbnb-14.1.0.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "homepage": "https://github.com/airbnb/javascript",
    "keywords": [
        "eslint",
        "eslintconfig",
        "config",
        "airbnb",
        "javascript",
        "styleguide"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "airbnb",
            "email": "jordan.harband+npm@airbnb.com"
        },
        {
            "name": "jitl",
            "email": "just.1.jake@gmail.com"
        },
        {
            "name": "ljharb",
            "email": "ljharb@gmail.com"
        }
    ],
    "name": "eslint-config-airbnb",
    "optionalDependencies": {},
    "peerDependencies": {
        "eslint": "^3.15.0",
        "eslint-plugin-jsx-a11y": "^3.0.2 || ^4.0.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-react": "^6.9.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/airbnb/javascript.git"
    },
    "scripts": {
        "lint": "eslint .",
        "prelint": "editorconfig-tools check * rules/* test/*",
        "prepublish": "(not-in-publish || npm test) && safe-publish-latest",
        "pretest": "npm run --silent lint",
        "test": "npm run --silent tests-only",
        "tests-only": "babel-tape-runner ./test/test-*.js",
        "travis": "cd ../eslint-config-airbnb-base && npm install && npm link && cd - && npm link eslint-config-airbnb-base && npm run --silent test ; npm unlink eslint-config-airbnb-base >/dev/null &"
    },
    "version": "14.1.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module eslint-config-airbnb](#apidoc.module.eslint-config-airbnb)
1.  object <span class="apidocSignatureSpan">eslint-config-airbnb.</span>extends
1.  object <span class="apidocSignatureSpan">eslint-config-airbnb.</span>rules



# <a name="apidoc.module.eslint-config-airbnb"></a>[module eslint-config-airbnb](#apidoc.module.eslint-config-airbnb)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
