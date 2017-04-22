# npmdoc-hexo-cli

#### api documentation for  [hexo-cli (v1.0.2)](https://hexo.io/)  [![npm package](https://img.shields.io/npm/v/npmdoc-hexo-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-hexo-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-hexo-cli.svg)](https://travis-ci.org/npmdoc/node-npmdoc-hexo-cli)

#### Command line interface for Hexo

[![NPM](https://nodei.co/npm/hexo-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hexo-cli)

- [https://npmdoc.github.io/node-npmdoc-hexo-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hexo-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hexo-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hexo-cli/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-hexo-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-hexo-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tommy Chen",
        "url": "http://zespia.tw"
    },
    "bin": {
        "hexo": "./bin/hexo"
    },
    "bugs": {
        "url": "https://github.com/hexojs/hexo-cli/issues"
    },
    "dependencies": {
        "abbrev": "^1.0.7",
        "bluebird": "^3.4.0",
        "chalk": "^1.1.3",
        "hexo-fs": "^0.1.5",
        "hexo-log": "^0.1.2",
        "hexo-util": "^0.6.0",
        "minimist": "^1.2.0",
        "object-assign": "^4.1.0",
        "tildify": "^1.2.0"
    },
    "description": "Command line interface for Hexo",
    "devDependencies": {
        "chai": "^3.5.0",
        "chai-as-promised": "^5.3.0",
        "eslint": "^2.12.0",
        "eslint-config-hexo": "^1.0.3",
        "hexo-renderer-marked": "^0.2.10",
        "istanbul": "^0.4.3",
        "jscs": "^3.0.4",
        "jscs-preset-hexo": "^1.0.1",
        "mocha": "^2.5.3",
        "proxyquire": "^1.7.9",
        "rewire": "^2.5.1",
        "sinon": "^1.17.4"
    },
    "directories": {
        "lib": "./lib",
        "bin": "./bin"
    },
    "dist": {
        "shasum": "8ebcae88cac29254f1e9ac07f8a9f07399a8a1ae",
        "tarball": "https://registry.npmjs.org/hexo-cli/-/hexo-cli-1.0.2.tgz"
    },
    "gitHead": "fb567e2d1e32929c4183ab4fcf1a5645fb646eb2",
    "homepage": "https://hexo.io/",
    "keywords": [
        "website",
        "blog",
        "cms",
        "framework",
        "hexo",
        "cli"
    ],
    "license": "MIT",
    "main": "lib/hexo",
    "maintainers": [
        {
            "name": "tommy351"
        }
    ],
    "name": "hexo-cli",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/hexojs/hexo-cli.git"
    },
    "scripts": {
        "eslint": "eslint .",
        "jscs": "jscs .",
        "test": "mocha test/index.js",
        "test-cov": "istanbul cover --print both _mocha -- test/index.js"
    },
    "version": "1.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
