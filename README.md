# npmtest-verb

#### basic test coverage for  [verb (v0.8.10)](https://github.com/verbose/verb)  [![npm package](https://img.shields.io/npm/v/npmtest-verb.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-verb) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-verb.svg)](https://travis-ci.org/npmtest/node-npmtest-verb)

#### Documentation generator for GitHub projects. Verb is extremely powerful, easy to use, and is used on hundreds of projects of all sizes to generate everything from API docs to readmes.

[![NPM](https://nodei.co/npm/verb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/verb)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-verb/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-verb/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-verb/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-verb/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-verb/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-verb/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-verb/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-verb/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-verb/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-verb/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-verb/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-verb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-verb/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-verb/build/test-report.html](https://npmtest.github.io/node-npmtest-verb/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-verb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-verb/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-verb/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-verb/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-verb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-verb/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-verb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-verb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jon Schlinkert",
        "url": "https://github.com/jonschlinkert"
    },
    "bugs": {
        "url": "https://github.com/verbose/verb/issues"
    },
    "dependencies": {
        "ansi-bold": "^0.1.1",
        "ansi-cyan": "^0.1.1",
        "ansi-red": "^0.1.1",
        "ansi-yellow": "^0.1.1",
        "arr-union": "^3.0.0",
        "async-helper-base": "^0.2.0",
        "base-loader": "^0.1.0",
        "chalk": "^1.1.1",
        "composer": "^0.4.0",
        "computed-property": "^0.1.2",
        "cwd": "^0.8.0",
        "data-store": "^0.8.2",
        "diff": "^2.0.2",
        "engine-lodash": "^0.8.0",
        "event-stream": "^3.3.1",
        "export-files": "^2.1.0",
        "extend-shallow": "^2.0.1",
        "get-value": "^1.1.5",
        "gfm-code-blocks": "^0.3.0",
        "git-user-name": "^1.1.2",
        "globby": "^2.1.0",
        "gulp-drafts": "^0.2.0",
        "gulp-util": "^3.0.6",
        "helper-changelog": "^0.1.0",
        "helper-codelinks": "^0.1.2",
        "helper-copyright": "^1.4.0",
        "helper-coverage": "^0.1.2",
        "helper-date": "^0.2.2",
        "helper-license": "^0.2.1",
        "helper-reflinks": "^1.4.1",
        "helper-related": "^0.10.0",
        "helper-resolve": "^0.3.1",
        "helper-toc": "^0.2.0",
        "init-file-loader": "^0.1.1",
        "is-plain-object": "^2.0.1",
        "is-true": "^0.1.0",
        "js-comments": "^0.5.4",
        "lint-templates": "^0.1.2",
        "lodash": "^3.10.1",
        "log-symbols": "^1.0.2",
        "logging-helpers": "^0.4.0",
        "markdown-toc": "^0.11.5",
        "markdown-utils": "^0.7.1",
        "micromatch": "^2.2.0",
        "middleware-utils": "^0.1.4",
        "parse-author": "^0.2.0",
        "parse-copyright": "^0.4.0",
        "parse-filepath": "^0.6.3",
        "parse-github-url": "^0.1.1",
        "parse-gitignore": "^0.2.0",
        "parser-front-matter": "^1.2.5",
        "plugin-error": "^0.1.2",
        "pretty-remarkable": "^0.1.8",
        "readme-badges": "^0.3.3",
        "readme-includes": "^0.2.9",
        "relative": "^3.0.1",
        "relative-dest": "^0.1.0",
        "remarkable": "^1.6.0",
        "stringify-travis-url": "^0.1.0",
        "template": "^0.14.3",
        "template-helper-apidocs": "^0.4.4",
        "template-helpers": "^0.3.2",
        "template-toc": "^0.3.3",
        "through2": "^2.0.0",
        "update-copyright": "^0.1.0",
        "vinyl-fs": "^1.0.0",
        "year": "^0.2.1"
    },
    "description": "Documentation generator for GitHub projects. Verb is extremely powerful, easy to use, and is used on hundreds of projects of all sizes to generate everything from API docs to readmes.",
    "devDependencies": {
        "consolidate": "^0.13.1",
        "gulp-istanbul": "^0.10.0",
        "gulp-jshint": "^1.11.2",
        "gulp-mocha": "^2.1.3",
        "handlebars": "^3.0.3",
        "jshint-stylish": "^2.0.1",
        "mocha": "*",
        "should": "*",
        "swig": "^1.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "52a0803b883eea489a59288cf9452645b2676532",
        "tarball": "https://registry.npmjs.org/verb/-/verb-0.8.10.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js",
        "lib/"
    ],
    "gitHead": "492ba7079bac3014ff629ead1b99fdf8e8bb8359",
    "homepage": "https://github.com/verbose/verb",
    "keywords": [
        "comment",
        "comments",
        "doc",
        "docs",
        "document",
        "documentation",
        "generate",
        "generator",
        "gh",
        "gh-pages",
        "markdown",
        "md",
        "pages",
        "readme",
        "repo",
        "repository",
        "template",
        "templates",
        "verb",
        "verbiage"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jonschlinkert"
        },
        {
            "name": "doowb"
        },
        {
            "name": "adjohnson916"
        }
    ],
    "name": "verb",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/verbose/verb.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "verb": {
        "ignore": [
            ".git"
        ],
        "deps": {
            "include": [
                "readme-includes",
                "readme-badges"
            ],
            "ignore": [
                "support"
            ]
        },
        "related": {
            "list": [
                "composer",
                "assemble",
                "template",
                "engine"
            ]
        },
        "reflinks": {
            "list": [
                "jsdiff",
                "option-cache",
                "template",
                "plasma",
                "config-cache"
            ]
        }
    },
    "version": "0.8.10",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
