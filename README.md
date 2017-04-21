# npmtest-exiftool

#### basic test coverage for  exiftool (v0.0.3)  [![npm package](https://img.shields.io/npm/v/npmtest-exiftool.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-exiftool) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-exiftool.svg)](https://travis-ci.org/npmtest/node-npmtest-exiftool)

#### Metadata extraction from numerous filetypes including JPEG, PNG, PDF, MOV, WMV, MP3, MP4, and others.

[![NPM](https://nodei.co/npm/exiftool.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/exiftool)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-exiftool/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-exiftool/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-exiftool/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-exiftool/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-exiftool/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-exiftool/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-exiftool/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-exiftool/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-exiftool/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-exiftool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-exiftool/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-exiftool/build/test-report.html](https://npmtest.github.io/node-npmtest-exiftool/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-exiftool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-exiftool/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-exiftool/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-exiftool/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-exiftool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-exiftool/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-exiftool/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-exiftool/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "exiftool",
    "version": "0.0.3",
    "description": "Metadata extraction from numerous filetypes including JPEG, PNG, PDF, MOV, WMV, MP3, MP4, and others.",
    "main": "./lib/exiftool",
    "author": {
        "name": "Nathan Peck"
    },
    "devDependencies": {
        "mocha": "1.17.1",
        "chai": "1.8.1"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/nathanpeck/exiftool.git"
    },
    "keywords": [
        "exif",
        "file",
        "metadata",
        "binary",
        "image",
        "video",
        "PNG",
        "PDF"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://raw.githubusercontent.com/nathanpeck/exiftool/master/LICENSE"
        }
    ],
    "readmeFilename": "README.md",
    "scripts": {
        "test": "./node_modules/.bin/mocha -R spec -s 100 ./tests/test.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
