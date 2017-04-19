# npmtest-webpack-svgstore-plugin

#### test coverage for  [webpack-svgstore-plugin (v4.0.0)](https://github.com/mrsum/webpack-svgstore-plugin#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-webpack-svgstore-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-webpack-svgstore-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-webpack-svgstore-plugin.svg)](https://travis-ci.org/npmtest/node-npmtest-webpack-svgstore-plugin)

#### Webpack svgstore plugin

[![NPM](https://nodei.co/npm/webpack-svgstore-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/webpack-svgstore-plugin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-webpack-svgstore-plugin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack-svgstore-plugin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-webpack-svgstore-plugin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-webpack-svgstore-plugin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-webpack-svgstore-plugin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-webpack-svgstore-plugin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-webpack-svgstore-plugin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-webpack-svgstore-plugin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-webpack-svgstore-plugin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack-svgstore-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-webpack-svgstore-plugin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-webpack-svgstore-plugin/build/test-report.html](https://npmtest.github.io/node-npmtest-webpack-svgstore-plugin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-webpack-svgstore-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-webpack-svgstore-plugin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-webpack-svgstore-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-webpack-svgstore-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webpack-svgstore-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webpack-svgstore-plugin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-webpack-svgstore-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-webpack-svgstore-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "me@mrsum.ru"
    },
    "bugs": {
        "url": "https://github.com/mrsum/webpack-svgstore-plugin/issues"
    },
    "contributors": [
        {
            "name": "Mike Chernobrov"
        },
        {
            "name": "Gordey Levchenko"
        }
    ],
    "dependencies": {
        "async": "2.1.4",
        "globby": "6.1.0",
        "htmlparser2": "3.9.2",
        "lodash": "4.17.2",
        "pug": "2.0.0-beta6",
        "svgo": "0.7.1"
    },
    "description": "Webpack svgstore plugin",
    "devDependencies": {
        "chai": "3.5.0",
        "codeclimate-test-reporter": "0.4.0",
        "eslint-config-rambler": "0.2.5",
        "istanbul": "0.4.5",
        "mocha": "3.2.0",
        "path": "0.12.7",
        "webpack": "2.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "b1413befca8ea06f6d23e093d8f76cf9a9efd7c7",
        "tarball": "https://registry.npmjs.org/webpack-svgstore-plugin/-/webpack-svgstore-plugin-4.0.0.tgz"
    },
    "gitHead": "9df3cf12902569ba086b98cc513259c9ffc8e100",
    "homepage": "https://github.com/mrsum/webpack-svgstore-plugin#readme",
    "license": "MIT",
    "main": "src/svgstore.js",
    "maintainers": [
        {
            "name": "mrsum"
        },
        {
            "name": "lgordey"
        }
    ],
    "name": "webpack-svgstore-plugin",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mrsum/webpack-svgstore-plugin.git"
    },
    "scripts": {
        "build": "rm -rf platform/dist/* && NODE_ENV=platform webpack --progress --colors --bail",
        "code:coverage": "NODE_ENV=platform ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha ./src/__tests__/index.js && npm run code:report",
        "code:report": "CODECLIMATE_REPO_TOKEN=29b2c943849c33562af12b70563d86e95c073e04c7510e9da5d9711cf3233b17 ./node_modules/.bin/codeclimate-test-reporter < coverage/lcov.info",
        "test": "NODE_ENV=platform ./node_modules/.bin/_mocha ./src/__tests__/index.js"
    },
    "version": "4.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
