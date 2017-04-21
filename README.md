# npmdoc-yeoman-doctor

#### api documentation for  yeoman-doctor (v2.1.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-yeoman-doctor.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-yeoman-doctor) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-yeoman-doctor.svg)](https://travis-ci.org/npmdoc/node-npmdoc-yeoman-doctor)

#### Detect potential issues with users system that could prevent Yeoman from working correctly

[![NPM](https://nodei.co/npm/yeoman-doctor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yeoman-doctor)

- [https://npmdoc.github.io/node-npmdoc-yeoman-doctor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yeoman-doctor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yeoman-doctor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yeoman-doctor/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-yeoman-doctor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-yeoman-doctor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "yeoman-doctor",
    "version": "2.1.0",
    "description": "Detect potential issues with users system that could prevent Yeoman from working correctly",
    "license": "BSD-2-Clause",
    "author": "Yeoman",
    "repository": "yeoman/doctor",
    "main": "lib/index.js",
    "bin": {
        "yodoctor": "lib/cli.js"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "scripts": {
        "test": "xo && mocha test/** -R spec"
    },
    "files": [
        "lib"
    ],
    "keywords": [
        "cli-app",
        "cli",
        "yeoman",
        "yo",
        "doctor",
        "system",
        "health",
        "report",
        "check"
    ],
    "dependencies": {
        "bin-version-check": "^2.1.0",
        "chalk": "^1.0.0",
        "each-async": "^1.1.1",
        "log-symbols": "^1.0.1",
        "object-values": "^1.0.0",
        "semver": "^5.0.3",
        "twig": "^0.8.2",
        "user-home": "^2.0.0"
    },
    "devDependencies": {
        "mocha": "^2.0.1",
        "sinon": "^1.12.1",
        "xo": "*"
    },
    "xo": {
        "space": true,
        "envs": [
            "node",
            "mocha"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
