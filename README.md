# test coverage for  [kafka-node (v1.6.0)](https://github.com/SOHU-Co/kafka-node#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-kafka-node.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-kafka-node) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-kafka-node.svg)](https://travis-ci.org/npmtest/node-npmtest-kafka-node)
#### Client for Apache Kafka v0.8+

[![NPM](https://nodei.co/npm/kafka-node.png?downloads=true)](https://www.npmjs.com/package/kafka-node)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-kafka-node/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-kafka-node/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-kafka-node/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-kafka-node/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-kafka-node/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-kafka-node/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-kafka-node/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-kafka-node/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-kafka-node/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-kafka-node/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-kafka-node%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-kafka-node/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-kafka-node/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-kafka-node%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-kafka-node/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-kafka-node/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-kafka-node/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/SOHU-co/kafka-node/issues"
    },
    "dependencies": {
        "async": ">0.9 <2.0",
        "binary": "~0.3.0",
        "buffer-crc32": "~0.2.5",
        "buffermaker": "~1.2.0",
        "debug": "^2.1.3",
        "lodash": "^4.17.4",
        "minimatch": "^3.0.2",
        "nested-error-stacks": "^2.0.0",
        "node-zookeeper-client": "~0.2.2",
        "optional": "^0.1.3",
        "retry": "^0.10.1",
        "snappy": "^5.0.5",
        "uuid": "^3.0.0"
    },
    "description": "Client for Apache Kafka v0.8+",
    "devDependencies": {
        "coveralls": "^2.11.12",
        "doctoc": "^1.2.0",
        "eslint": "^3.7.0",
        "eslint-config-semistandard": "^7.0.0",
        "eslint-config-standard": "^6.2.0",
        "eslint-plugin-dependencies": "^1.3.0",
        "eslint-plugin-promise": "^3.4.0",
        "eslint-plugin-standard": "^2.0.1",
        "istanbul": "^0.4.4",
        "mocha": "^3.1.0",
        "nsp": "^2.6.2",
        "optimist": "^0.6.1",
        "proxyquire": "^1.7.10",
        "should": "^6.0.0",
        "sinon": "^1.17.2"
    },
    "directories": {},
    "dist": {
        "shasum": "c8c4b779610a45c53b7a5d177c20f63b46d36f87",
        "tarball": "https://registry.npmjs.org/kafka-node/-/kafka-node-1.6.0.tgz"
    },
    "engines": {
        "node": ">4.4.7"
    },
    "files": [
        "kafka.js",
        "logging.js",
        "lib"
    ],
    "gitHead": "a9f22e134f78dfc8aeeac8deee6331492dd7ceed",
    "homepage": "https://github.com/SOHU-Co/kafka-node#readme",
    "keywords": [
        "kafka",
        "zookeeper",
        "consumer",
        "producer",
        "broker"
    ],
    "license": "MIT",
    "main": "kafka.js",
    "maintainers": [
        {
            "name": "estliberitas",
            "email": "estliberitas@gmail.com"
        },
        {
            "name": "haio",
            "email": "mockingror@gmail.com"
        },
        {
            "name": "hyperlink",
            "email": "javascript@yahoo.com"
        }
    ],
    "name": "kafka-node",
    "optionalDependencies": {
        "snappy": "^5.0.5"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/SOHU-Co/kafka-node.git"
    },
    "scripts": {
        "startDocker": "./start-docker.sh",
        "stopDocker": "docker-compose down",
        "test": "eslint . && ./run-tests.sh && nsp check",
        "updateToc": "doctoc README.md --maxlevel 2 --notitle"
    },
    "version": "1.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
