# npmtest-play-sound

#### basic test coverage for  [play-sound (v1.1.1)](https://github.com/shime/play-sound)  [![npm package](https://img.shields.io/npm/v/npmtest-play-sound.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-play-sound) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-play-sound.svg)](https://travis-ci.org/npmtest/node-npmtest-play-sound)

#### Play audio files by shelling out to available audio tool.

[![NPM](https://nodei.co/npm/play-sound.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/play-sound)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-play-sound/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-play-sound/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-play-sound/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-play-sound/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-play-sound/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-play-sound/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-play-sound/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-play-sound/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-play-sound/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-play-sound/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-play-sound/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-play-sound/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-play-sound/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-play-sound/build/test-report.html](https://npmtest.github.io/node-npmtest-play-sound/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-play-sound/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-play-sound/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-play-sound/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-play-sound/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-play-sound/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-play-sound/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-play-sound/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-play-sound/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Hrvoje Simic"
    },
    "bugs": {
        "url": "https://github.com/shime/play-sound/issues"
    },
    "dependencies": {
        "find-exec": "0.0.8"
    },
    "description": "Play audio files by shelling out to available audio tool.",
    "devDependencies": {
        "expect.js": "^0.3.1",
        "mocha": "^1.21.4",
        "mock-fs": "^3.11.0",
        "proxyquire": "^1.0.1",
        "sinon": "^1.10.3"
    },
    "directories": {},
    "dist": {
        "shasum": "a0a5d29358beb298d33021b13bdedee09c67e7f1",
        "tarball": "https://registry.npmjs.org/play-sound/-/play-sound-1.1.1.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "51b9bc900cf7802eff105c072cc6e3f1fe6ad733",
    "homepage": "https://github.com/shime/play-sound",
    "keywords": [
        "audio",
        "sound",
        "play"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "justinjmoses"
        },
        {
            "name": "shime"
        }
    ],
    "name": "play-sound",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/shime/play-sound.git"
    },
    "scripts": {
        "test": "export PATH=$PATH:./shims && node_modules/.bin/mocha tests.js"
    },
    "version": "1.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
