# npmtest-react-pdf-js

#### basic test coverage for  [react-pdf-js (v1.0.35)](https://github.com/mikecousins/react-pdf-js)  [![npm package](https://img.shields.io/npm/v/npmtest-react-pdf-js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-pdf-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-pdf-js.svg)](https://travis-ci.org/npmtest/node-npmtest-react-pdf-js)

#### A React component to wrap PDF.js

[![NPM](https://nodei.co/npm/react-pdf-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-pdf-js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-pdf-js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-pdf-js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-pdf-js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-pdf-js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-pdf-js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-pdf-js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-pdf-js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-pdf-js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-pdf-js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-pdf-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-pdf-js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-pdf-js/build/test-report.html](https://npmtest.github.io/node-npmtest-react-pdf-js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-pdf-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-pdf-js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-pdf-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-pdf-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-pdf-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-pdf-js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-pdf-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-pdf-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-pdf-js",
    "version": "1.0.35",
    "description": "A React component to wrap PDF.js",
    "main": "./lib/index.js",
    "jsnext:main": "./src/index.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/mikecousins/react-pdf-js"
    },
    "scripts": {
        "build": "npm run build:lib && npm run build:umd && npm run build:umd:min",
        "build:lib": "babel src --out-dir lib",
        "build:umd": "webpack src/index.js dist/react-pdf-js.js --config webpack.config.development.js",
        "build:umd:min": "webpack src/index.js dist/react-pdf-js.min.js --config webpack.config.production.js",
        "clean": "rimraf dist lib",
        "lint": "eslint src --ext .js --ext .jsx",
        "prepublish": "npm run lint && npm run clean && npm run build"
    },
    "keywords": [
        "react",
        "reactjs",
        "pdf",
        "pdfjs"
    ],
    "author": "Mike Cousins <mike@mikecousins.com> (http://github.com/mikecousins)",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/mikecousins/react-pdf-js/issues"
    },
    "homepage": "https://github.com/mikecousins/react-pdf-js",
    "peerDependencies": {
        "react": "^15.5.3 || ~0.14.0",
        "react-dom": "^15.5.3 || ~0.14.0"
    },
    "dependencies": {
        "pdfjs-dist": "1.8.177",
        "prop-types": "^15.5.6"
    },
    "devDependencies": {
        "babel-cli": "6.24.1",
        "babel-core": "6.24.1",
        "babel-eslint": "7.2.1",
        "babel-loader": "6.4.1",
        "babel-plugin-react-transform": "2.0.2",
        "babel-plugin-transform-class-properties": "6.24.1",
        "babel-plugin-transform-runtime": "6.23.0",
        "babel-plugin-typecheck": "3.9.0",
        "babel-preset-es2015": "6.24.1",
        "babel-preset-react": "6.24.1",
        "babel-runtime": "6.23.0",
        "eslint": "3.19.0",
        "eslint-config-airbnb": "14.1.0",
        "eslint-plugin-import": "2.2.0",
        "eslint-plugin-jsx-a11y": "4.0.0",
        "eslint-plugin-react": "6.10.3",
        "react": "15.5.3",
        "react-dom": "15.5.3",
        "rifraf": "2.0.3",
        "rimraf": "2.6.1",
        "webpack": "2.3.3"
    },
    "npmName": "react-pdf-js",
    "npmFileMap": [
        {
            "files": [
                "dist/*.js",
                "lib/*.js",
                "src/*.js"
            ]
        }
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
