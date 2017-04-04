# api documentation for  [knex (v0.12.9)](https://github.com/tgriesser/knex#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-knex.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-knex) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-knex.svg)](https://travis-ci.org/npmdoc/node-npmdoc-knex)
#### A batteries-included SQL query & schema builder for Postgres, MySQL and SQLite3 and the Browser

[![NPM](https://nodei.co/npm/knex.png?downloads=true)](https://www.npmjs.com/package/knex)

[![apidoc](https://npmdoc.github.io/node-npmdoc-knex/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-knex_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-knex/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-knex/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-knex/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tim Griesser",
        "url": "https://github.com/tgriesser"
    },
    "bin": {
        "knex": "./bin/cli.js"
    },
    "browser": {
        "./lib/migrate/index.js": "./lib/util/noop.js",
        "./lib/bin/cli.js": "./lib/util/noop.js",
        "./lib/seed/index.js": "./lib/util/noop.js",
        "mssql": false,
        "mysql": false,
        "mysql2": false,
        "mariasql": false,
        "pg": false,
        "pg-query-stream": false,
        "oracle": false,
        "strong-oracle": false,
        "sqlite3": false,
        "oracledb": false
    },
    "bugs": {
        "url": "https://github.com/tgriesser/knex/issues"
    },
    "buildDependencies": [
        "babel-cli",
        "babel-plugin-add-module-exports",
        "babel-plugin-lodash",
        "babel-plugin-transform-runtime",
        "babel-preset-es2015",
        "babel-preset-es2015-loose",
        "rimraf"
    ],
    "dependencies": {
        "babel-runtime": "^6.11.6",
        "bluebird": "^3.4.6",
        "chalk": "^1.0.0",
        "commander": "^2.2.0",
        "debug": "^2.1.3",
        "generic-pool": "^2.4.2",
        "inherits": "~2.0.1",
        "interpret": "^0.6.5",
        "liftoff": "~2.2.0",
        "lodash": "^4.6.0",
        "minimist": "~1.1.0",
        "mkdirp": "^0.5.0",
        "pg-connection-string": "^0.1.3",
        "readable-stream": "^1.1.12",
        "safe-buffer": "^5.0.1",
        "tildify": "~1.0.0",
        "uuid": "^3.0.0",
        "v8flags": "^2.0.2"
    },
    "description": "A batteries-included SQL query & schema builder for Postgres, MySQL and SQLite3 and the Browser",
    "devDependencies": {
        "JSONStream": "^1.0.3",
        "async": "^0.9.0",
        "babel-cli": "^6.11.4",
        "babel-eslint": "^5.0.0",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-lodash": "3.2.9",
        "babel-plugin-transform-runtime": "^6.12.0",
        "babel-preset-es2015": "^6.13.2",
        "babel-preset-es2015-loose": "^8.0.0",
        "chai": "^3.5.0",
        "coveralls": "~2.11.1",
        "eslint": "2.2.0",
        "eslint-plugin-import": "^1.8.0",
        "istanbul": "^0.4.5",
        "json-loader": "^0.5.4",
        "mariasql": "^0.2.3",
        "mocha": "^3.1.2",
        "mysql": "^2.6.2",
        "mysql2": "^1.1.1",
        "pg": "^6.1.0",
        "pg-query-stream": "^1.0.0",
        "rimraf": "2.x",
        "sinon": "^1.10.0",
        "sinon-chai": "^2.5.0",
        "source-map-support": "^0.4.0",
        "sqlite3": "^3.0.5",
        "tap-spec": "^4.0.0",
        "tape": "^4.0.0",
        "through": "^2.3.4"
    },
    "directories": {},
    "dist": {
        "shasum": "aa852138c09ed46181e890fd698270bbe7761124",
        "tarball": "https://registry.npmjs.org/knex/-/knex-0.12.9.tgz"
    },
    "files": [
        "CONTRIBUTING.md",
        "README.md",
        "bin/*",
        "src/*",
        "lib/*",
        "knex.js",
        "LICENSE",
        "CHANGELOG.md",
        "scripts/*"
    ],
    "gitHead": "ce375c54230297e7cd20964b63a1c214e57693db",
    "homepage": "https://github.com/tgriesser/knex#readme",
    "keywords": [
        "sql",
        "query",
        "postgresql",
        "mysql",
        "mariadb",
        "sqlite3",
        "oracle",
        "mssql"
    ],
    "license": "MIT",
    "main": "knex.js",
    "maintainers": [
        {
            "name": "elhigu",
            "email": "mikael.lepisto@vincit.com"
        },
        {
            "name": "erisds",
            "email": "erisds@gmail.com"
        },
        {
            "name": "kirrg001",
            "email": "katharina.irrgang@googlemail.com"
        },
        {
            "name": "rhys-vdw",
            "email": "rhys.vdw@gmail.com"
        },
        {
            "name": "tgriesser",
            "email": "tgriesser10@gmail.com"
        },
        {
            "name": "tjwebb",
            "email": "me@traviswebb.com"
        },
        {
            "name": "tkellen",
            "email": "tyler@sleekcode.net"
        },
        {
            "name": "wubzz",
            "email": "wubzz94@hotmail.com"
        }
    ],
    "name": "knex",
    "optionalDependencies": {},
    "react-native": {
        "./lib/migrate": "./lib/util/noop.js",
        "./lib/seed": "./lib/util/noop.js"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/tgriesser/knex.git"
    },
    "scripts": {
        "babel": "rimraf ./lib && babel src --out-dir lib --copy-files",
        "build": "npm run babel",
        "coveralls": "cat ./test/coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js",
        "debug_tape": "node-debug test/tape/index.js",
        "debug_test": "node-debug _mocha -t 0 test/index.js",
        "dev": "rm -rf ./lib && babel -w src --out-dir lib --copy-files",
        "lint": "eslint src/**",
        "plaintest": "mocha --check-leaks -b -R spec test/index.js && npm run tape",
        "prepublish": "npm run babel",
        "tape": "node test/tape/index.js | tap-spec",
        "test": "npm run lint && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape"
    },
    "version": "0.12.9"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module knex](#apidoc.module.knex)
1.  [function <span class="apidocSignatureSpan">knex.</span>Client ()](#apidoc.element.knex.Client)
1.  [function <span class="apidocSignatureSpan">knex.</span>formatter (client)](#apidoc.element.knex.formatter)
1.  [function <span class="apidocSignatureSpan">knex.</span>functionhelper (client)](#apidoc.element.knex.functionhelper)
1.  [function <span class="apidocSignatureSpan">knex.</span>raw (sql, bindings)](#apidoc.element.knex.raw)
1.  [function <span class="apidocSignatureSpan">knex.</span>runner (client, builder)](#apidoc.element.knex.runner)
1.  [function <span class="apidocSignatureSpan">knex.</span>transaction (client, container, config, outerTx)](#apidoc.element.knex.transaction)
1.  object <span class="apidocSignatureSpan">knex.</span>Client.prototype
1.  object <span class="apidocSignatureSpan">knex.</span>formatter.prototype
1.  object <span class="apidocSignatureSpan">knex.</span>functionhelper.prototype
1.  object <span class="apidocSignatureSpan">knex.</span>helpers
1.  object <span class="apidocSignatureSpan">knex.</span>raw.prototype
1.  object <span class="apidocSignatureSpan">knex.</span>runner.prototype
1.  object <span class="apidocSignatureSpan">knex.</span>transaction.prototype

#### [module knex.Client](#apidoc.module.knex.Client)
1.  [function <span class="apidocSignatureSpan">knex.</span>Client ()](#apidoc.element.knex.Client.Client)
1.  [function <span class="apidocSignatureSpan">knex.Client.</span>super_ ()](#apidoc.element.knex.Client.super_)

#### [module knex.Client.prototype](#apidoc.module.knex.Client.prototype)
1.  boolean <span class="apidocSignatureSpan">knex.Client.prototype.</span>canCancelQuery
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>_escapeBinding (val)](#apidoc.element.knex.Client.prototype._escapeBinding)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>_formatQuery (sql, bindings, timeZone)](#apidoc.element.knex.Client.prototype._formatQuery)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>acquireConnection ()](#apidoc.element.knex.Client.prototype.acquireConnection)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>assertCanCancelQuery ()](#apidoc.element.knex.Client.prototype.assertCanCancelQuery)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>cancelQuery ()](#apidoc.element.knex.Client.prototype.cancelQuery)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>columnBuilder (tableBuilder, type, args)](#apidoc.element.knex.Client.prototype.columnBuilder)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>columnCompiler (tableBuilder, columnBuilder)](#apidoc.element.knex.Client.prototype.columnCompiler)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>database ()](#apidoc.element.knex.Client.prototype.database)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>destroy (callback)](#apidoc.element.knex.Client.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>formatter ()](#apidoc.element.knex.Client.prototype.formatter)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>initializeDriver ()](#apidoc.element.knex.Client.prototype.initializeDriver)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>initializePool (config)](#apidoc.element.knex.Client.prototype.initializePool)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>poolDefaults (poolConfig)](#apidoc.element.knex.Client.prototype.poolDefaults)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>prepBindings (bindings)](#apidoc.element.knex.Client.prototype.prepBindings)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>query (connection, obj)](#apidoc.element.knex.Client.prototype.query)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>queryBuilder ()](#apidoc.element.knex.Client.prototype.queryBuilder)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>queryCompiler (builder)](#apidoc.element.knex.Client.prototype.queryCompiler)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>raw ()](#apidoc.element.knex.Client.prototype.raw)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>releaseConnection (connection)](#apidoc.element.knex.Client.prototype.releaseConnection)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>runner (connection)](#apidoc.element.knex.Client.prototype.runner)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>schemaBuilder ()](#apidoc.element.knex.Client.prototype.schemaBuilder)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>schemaCompiler (builder)](#apidoc.element.knex.Client.prototype.schemaCompiler)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>stream (connection, obj, _stream, options)](#apidoc.element.knex.Client.prototype.stream)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>tableBuilder (type, tableName, fn)](#apidoc.element.knex.Client.prototype.tableBuilder)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>tableCompiler (tableBuilder)](#apidoc.element.knex.Client.prototype.tableCompiler)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>toString ()](#apidoc.element.knex.Client.prototype.toString)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>transaction (container, config, outerTx)](#apidoc.element.knex.Client.prototype.transaction)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>validateConnection (connection)](#apidoc.element.knex.Client.prototype.validateConnection)
1.  [function <span class="apidocSignatureSpan">knex.Client.prototype.</span>wrapIdentifier (value)](#apidoc.element.knex.Client.prototype.wrapIdentifier)

#### [module knex.formatter](#apidoc.module.knex.formatter)
1.  [function <span class="apidocSignatureSpan">knex.</span>formatter (client)](#apidoc.element.knex.formatter.formatter)

#### [module knex.formatter.prototype](#apidoc.module.knex.formatter.prototype)
1.  [function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>_wrapString (value)](#apidoc.element.knex.formatter.prototype._wrapString)
1.  [function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>alias (first, second)](#apidoc.element.knex.formatter.prototype.alias)
1.  [function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>columnize (target)](#apidoc.element.knex.formatter.prototype.columnize)
1.  [function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>compileCallback (callback, method)](#apidoc.element.knex.formatter.prototype.compileCallback)
1.  [function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>direction (value)](#apidoc.element.knex.formatter.prototype.direction)
1.  [function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>operator (value)](#apidoc.element.knex.formatter.prototype.operator)
1.  [function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>outputQuery (compiled, isParameter)](#apidoc.element.knex.formatter.prototype.outputQuery)
1.  [function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>parameter (value)](#apidoc.element.knex.formatter.prototype.parameter)
1.  [function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>parameterize (values, notSetValue)](#apidoc.element.knex.formatter.prototype.parameterize)
1.  [function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>rawOrFn (value, method)](#apidoc.element.knex.formatter.prototype.rawOrFn)
1.  [function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>unwrapRaw (value, isParameter)](#apidoc.element.knex.formatter.prototype.unwrapRaw)
1.  [function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>wrap (value)](#apidoc.element.knex.formatter.prototype.wrap)
1.  [function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>wrapAsIdentifier (value)](#apidoc.element.knex.formatter.prototype.wrapAsIdentifier)

#### [module knex.functionhelper](#apidoc.module.knex.functionhelper)
1.  [function <span class="apidocSignatureSpan">knex.</span>functionhelper (client)](#apidoc.element.knex.functionhelper.functionhelper)

#### [module knex.functionhelper.prototype](#apidoc.module.knex.functionhelper.prototype)
1.  [function <span class="apidocSignatureSpan">knex.functionhelper.prototype.</span>now ()](#apidoc.element.knex.functionhelper.prototype.now)

#### [module knex.helpers](#apidoc.module.knex.helpers)
1.  boolean <span class="apidocSignatureSpan">knex.helpers.</span>__esModule
1.  [function <span class="apidocSignatureSpan">knex.helpers.</span>containsUndefined (mixed)](#apidoc.element.knex.helpers.containsUndefined)
1.  [function <span class="apidocSignatureSpan">knex.helpers.</span>debugLog (msg)](#apidoc.element.knex.helpers.debugLog)
1.  [function <span class="apidocSignatureSpan">knex.helpers.</span>deprecate (method, alternate)](#apidoc.element.knex.helpers.deprecate)
1.  [function <span class="apidocSignatureSpan">knex.helpers.</span>error (msg)](#apidoc.element.knex.helpers.error)
1.  [function <span class="apidocSignatureSpan">knex.helpers.</span>exit (msg)](#apidoc.element.knex.helpers.exit)
1.  [function <span class="apidocSignatureSpan">knex.helpers.</span>normalizeArr ()](#apidoc.element.knex.helpers.normalizeArr)
1.  [function <span class="apidocSignatureSpan">knex.helpers.</span>skim (data)](#apidoc.element.knex.helpers.skim)
1.  [function <span class="apidocSignatureSpan">knex.helpers.</span>warn (msg)](#apidoc.element.knex.helpers.warn)

#### [module knex.raw](#apidoc.module.knex.raw)
1.  [function <span class="apidocSignatureSpan">knex.</span>raw ()](#apidoc.element.knex.raw.raw)
1.  [function <span class="apidocSignatureSpan">knex.raw.</span>super_ ()](#apidoc.element.knex.raw.super_)

#### [module knex.raw.prototype](#apidoc.module.knex.raw.prototype)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>asCallback ()](#apidoc.element.knex.raw.prototype.asCallback)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>bind ()](#apidoc.element.knex.raw.prototype.bind)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>catch ()](#apidoc.element.knex.raw.prototype.catch)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>connection (connection)](#apidoc.element.knex.raw.prototype.connection)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>debug (enabled)](#apidoc.element.knex.raw.prototype.debug)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>delay ()](#apidoc.element.knex.raw.prototype.delay)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>ensure ()](#apidoc.element.knex.raw.prototype.ensure)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>finally ()](#apidoc.element.knex.raw.prototype.finally)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>get ()](#apidoc.element.knex.raw.prototype.get)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>map ()](#apidoc.element.knex.raw.prototype.map)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>mapSeries ()](#apidoc.element.knex.raw.prototype.mapSeries)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>options (opts)](#apidoc.element.knex.raw.prototype.options)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>pipe (writable, options)](#apidoc.element.knex.raw.prototype.pipe)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>reduce ()](#apidoc.element.knex.raw.prototype.reduce)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>reflect ()](#apidoc.element.knex.raw.prototype.reflect)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>return ()](#apidoc.element.knex.raw.prototype.return)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>set (sql, bindings)](#apidoc.element.knex.raw.prototype.set)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>spread ()](#apidoc.element.knex.raw.prototype.spread)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>stream (options)](#apidoc.element.knex.raw.prototype.stream)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>tap ()](#apidoc.element.knex.raw.prototype.tap)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>then ()](#apidoc.element.knex.raw.prototype.then)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>thenReturn ()](#apidoc.element.knex.raw.prototype.thenReturn)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>timeout (ms)](#apidoc.element.knex.raw.prototype.timeout)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>toQuery (tz)](#apidoc.element.knex.raw.prototype.toQuery)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>toSQL (method, tz)](#apidoc.element.knex.raw.prototype.toSQL)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>toString ()](#apidoc.element.knex.raw.prototype.toString)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>transacting (t)](#apidoc.element.knex.raw.prototype.transacting)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>wrap (before, after)](#apidoc.element.knex.raw.prototype.wrap)
1.  [function <span class="apidocSignatureSpan">knex.raw.prototype.</span>yield ()](#apidoc.element.knex.raw.prototype.yield)

#### [module knex.runner](#apidoc.module.knex.runner)
1.  [function <span class="apidocSignatureSpan">knex.</span>runner (client, builder)](#apidoc.element.knex.runner.runner)

#### [module knex.runner.prototype](#apidoc.module.knex.runner.prototype)
1.  [function <span class="apidocSignatureSpan">knex.runner.prototype.</span>ensureConnection ()](#apidoc.element.knex.runner.prototype.ensureConnection)
1.  [function <span class="apidocSignatureSpan">knex.runner.prototype.</span>pipe (writable, options)](#apidoc.element.knex.runner.prototype.pipe)
1.  [function <span class="apidocSignatureSpan">knex.runner.prototype.</span>query ()](#apidoc.element.knex.runner.prototype.query)
1.  [function <span class="apidocSignatureSpan">knex.runner.prototype.</span>queryArray (queries)](#apidoc.element.knex.runner.prototype.queryArray)
1.  [function <span class="apidocSignatureSpan">knex.runner.prototype.</span>run ()](#apidoc.element.knex.runner.prototype.run)
1.  [function <span class="apidocSignatureSpan">knex.runner.prototype.</span>stream (options, handler)](#apidoc.element.knex.runner.prototype.stream)

#### [module knex.transaction](#apidoc.module.knex.transaction)
1.  [function <span class="apidocSignatureSpan">knex.</span>transaction (client, container, config, outerTx)](#apidoc.element.knex.transaction.transaction)

#### [module knex.transaction.prototype](#apidoc.module.knex.transaction.prototype)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>acquireConnection (client, config, txid)](#apidoc.element.knex.transaction.prototype.acquireConnection)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>asCallback ()](#apidoc.element.knex.transaction.prototype.asCallback)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>begin (conn)](#apidoc.element.knex.transaction.prototype.begin)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>bind ()](#apidoc.element.knex.transaction.prototype.bind)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>catch ()](#apidoc.element.knex.transaction.prototype.catch)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>commit (conn, value)](#apidoc.element.knex.transaction.prototype.commit)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>debug (enabled)](#apidoc.element.knex.transaction.prototype.debug)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>delay ()](#apidoc.element.knex.transaction.prototype.delay)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>ensure ()](#apidoc.element.knex.transaction.prototype.ensure)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>exec ()](#apidoc.element.knex.transaction.prototype.exec)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>finally ()](#apidoc.element.knex.transaction.prototype.finally)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>get ()](#apidoc.element.knex.transaction.prototype.get)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>isCompleted ()](#apidoc.element.knex.transaction.prototype.isCompleted)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>map ()](#apidoc.element.knex.transaction.prototype.map)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>mapSeries ()](#apidoc.element.knex.transaction.prototype.mapSeries)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>query (conn, sql, status, value)](#apidoc.element.knex.transaction.prototype.query)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>reduce ()](#apidoc.element.knex.transaction.prototype.reduce)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>reflect ()](#apidoc.element.knex.transaction.prototype.reflect)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>release (conn, value)](#apidoc.element.knex.transaction.prototype.release)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>return ()](#apidoc.element.knex.transaction.prototype.return)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>rollback (conn, error)](#apidoc.element.knex.transaction.prototype.rollback)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>rollbackTo (conn, error)](#apidoc.element.knex.transaction.prototype.rollbackTo)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>savepoint (conn)](#apidoc.element.knex.transaction.prototype.savepoint)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>spread ()](#apidoc.element.knex.transaction.prototype.spread)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>tap ()](#apidoc.element.knex.transaction.prototype.tap)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>then ()](#apidoc.element.knex.transaction.prototype.then)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>thenReturn ()](#apidoc.element.knex.transaction.prototype.thenReturn)
1.  [function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>yield ()](#apidoc.element.knex.transaction.prototype.yield)



# <a name="apidoc.module.knex"></a>[module knex](#apidoc.module.knex)

#### <a name="apidoc.element.knex.Client"></a>[function <span class="apidocSignatureSpan">knex.</span>Client ()](#apidoc.element.knex.Client)
- description and source-code
```javascript
function Client() {
  var config = arguments.length <= 0 || arguments[0] === undefined ? {} : arguments[0];

  this.config = config;

  //Client is a required field, so throw error if it's not supplied.
  //If 'this.dialect' is set, then this is a 'super()' call, in which case
  //'client' does not have to be set as it's already assigned on the client prototype.
  if (!this.config.client && !this.dialect) {
    throw new Error('knex: Required configuration option \'client\' is missing.');
  }

  this.connectionSettings = (0, _cloneDeep3.default)(config.connection || {});
  if (this.driverName && config.connection) {
    this.initializeDriver();
    if (!config.pool || config.pool && config.pool.max !== 0) {
      this.__cid = clientId();
      this.initializePool(config);
    }
  }
  this.valueForUndefined = this.raw('DEFAULT');
  if (config.useNullAsDefault) {
    this.valueForUndefined = null;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.formatter"></a>[function <span class="apidocSignatureSpan">knex.</span>formatter (client)](#apidoc.element.knex.formatter)
- description and source-code
```javascript
function Formatter(client) {
  (0, _classCallCheck3.default)(this, Formatter);

  this.client = client;
  this.bindings = [];
}
```
- example usage
```shell
...
return this.toQuery();
  },


  // Returns the raw sql for the query.
  toSQL: function toSQL(method, tz) {
var obj = void 0;
var formatter = this.client.formatter();

if (Array.isArray(this.bindings)) {
  obj = replaceRawArrBindings(this, formatter);
} else if (this.bindings && (0, _isPlainObject3.default)(this.bindings)) {
  obj = replaceKeyBindings(this, formatter);
} else {
  obj = {
...
```

#### <a name="apidoc.element.knex.functionhelper"></a>[function <span class="apidocSignatureSpan">knex.</span>functionhelper (client)](#apidoc.element.knex.functionhelper)
- description and source-code
```javascript
function FunctionHelper(client) {
  this.client = client;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.raw"></a>[function <span class="apidocSignatureSpan">knex.</span>raw (sql, bindings)](#apidoc.element.knex.raw)
- description and source-code
```javascript
raw = function (sql, bindings) {
  (0, _helpers.warn)('global Knex.raw is deprecated, use knex.raw (chain off an initialized knex object)');
  return new _raw2.default().set(sql, bindings);
}
```
- example usage
```shell
...
// FunctionHelper
// -------
function FunctionHelper(client) {
  this.client = client;
}

FunctionHelper.prototype.now = function () {
  return this.client.raw('CURRENT_TIMESTAMP');
};

exports.default = FunctionHelper;
module.exports = exports['default'];
...
```

#### <a name="apidoc.element.knex.runner"></a>[function <span class="apidocSignatureSpan">knex.</span>runner (client, builder)](#apidoc.element.knex.runner)
- description and source-code
```javascript
function Runner(client, builder) {
  this.client = client;
  this.builder = builder;
  this.queries = [];

  // The "connection" object is set on the runner when
  // "run" is called.
  this.connection = void 0;
}
```
- example usage
```shell
...
  return (0, _map3.default)(data, function (statement) {
    return _this.client._formatQuery(statement.sql, statement.bindings, tz);
  }).join(';\n');
};

// Create a new instance of the 'Runner', passing in the current object.
Target.prototype.then = function () /* onFulfilled, onRejected */{
  var result = this.client.runner(this).run();
  return result.then.apply(result, arguments);
};

// Add additional "options" to the builder. Typically used for client specific
// items, like the 'mysql' and 'sqlite3' drivers.
Target.prototype.options = function (opts) {
  this._options = this._options || [];
...
```

#### <a name="apidoc.element.knex.transaction"></a>[function <span class="apidocSignatureSpan">knex.</span>transaction (client, container, config, outerTx)](#apidoc.element.knex.transaction)
- description and source-code
```javascript
function Transaction(client, container, config, outerTx) {
  (0, _classCallCheck3.default)(this, Transaction);

  var _this = (0, _possibleConstructorReturn3.default)(this, _EventEmitter.call(this));

  var txid = _this.txid = (0, _uniqueId3.default)('trx');

  _this.client = client;
  _this.outerTx = outerTx;
  _this.trxClient = undefined;
  _this._debug = client.config && client.config.debug;

  debug('%s: Starting %s transaction', txid, outerTx ? 'nested' : 'top level');

  _this._promise = _bluebird2.default.using(_this.acquireConnection(client, config, txid), function (connection) {

    var trxClient = _this.trxClient = makeTxClient(_this, client, connection);
    var init = client.transacting ? _this.savepoint(connection) : _this.begin(connection);

    init.then(function () {
      return makeTransactor(_this, connection, trxClient);
    }).then(function (transactor) {
      // If we've returned a "thenable" from the transaction container, assume
      // the rollback and commit are chained to this object's success / failure.
      // Directly thrown errors are treated as automatic rollbacks.
      var result = void 0;
      try {
        result = container(transactor);
      } catch (err) {
        result = _bluebird2.default.reject(err);
      }
      if (result && result.then && typeof result.then === 'function') {
        result.then(function (val) {
          return transactor.commit(val);
        }).catch(function (err) {
          return transactor.rollback(err);
        });
      }
      return null;
    }).catch(function (e) {
      return _this._rejecter(e);
    });

    return new _bluebird2.default(function (resolver, rejecter) {
      _this._resolver = resolver;
      _this._rejecter = rejecter;
    });
  });

  _this._completed = false;

  // If there's a wrapping transaction, we need to wait for any older sibling
  // transactions to settle (commit or rollback) before we can start, and we
  // need to register ourselves with the parent transaction so any younger
  // siblings can wait for us to complete before they can start.
  _this._previousSibling = _bluebird2.default.resolve(true);
  if (outerTx) {
    if (outerTx._lastChild) _this._previousSibling = outerTx._lastChild;
    outerTx._lastChild = _this._promise;
  }
  return _this;
}
```
- example usage
```shell
...

exports.default = Transaction;
function makeTransactor(trx, connection, trxClient) {

var transactor = (0, _makeKnex2.default)(trxClient);

transactor.transaction = function (container, options) {
  return trxClient.transaction(container, options, trx);
};
transactor.savepoint = function (container, options) {
  return transactor.transaction(container, options);
};

if (trx.client.transacting) {
  transactor.commit = function (value) {
...
```



# <a name="apidoc.module.knex.Client"></a>[module knex.Client](#apidoc.module.knex.Client)

#### <a name="apidoc.element.knex.Client.Client"></a>[function <span class="apidocSignatureSpan">knex.</span>Client ()](#apidoc.element.knex.Client.Client)
- description and source-code
```javascript
function Client() {
  var config = arguments.length <= 0 || arguments[0] === undefined ? {} : arguments[0];

  this.config = config;

  //Client is a required field, so throw error if it's not supplied.
  //If 'this.dialect' is set, then this is a 'super()' call, in which case
  //'client' does not have to be set as it's already assigned on the client prototype.
  if (!this.config.client && !this.dialect) {
    throw new Error('knex: Required configuration option \'client\' is missing.');
  }

  this.connectionSettings = (0, _cloneDeep3.default)(config.connection || {});
  if (this.driverName && config.connection) {
    this.initializeDriver();
    if (!config.pool || config.pool && config.pool.max !== 0) {
      this.__cid = clientId();
      this.initializePool(config);
    }
  }
  this.valueForUndefined = this.raw('DEFAULT');
  if (config.useNullAsDefault) {
    this.valueForUndefined = null;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.Client.super_"></a>[function <span class="apidocSignatureSpan">knex.Client.</span>super_ ()](#apidoc.element.knex.Client.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.knex.Client.prototype"></a>[module knex.Client.prototype](#apidoc.module.knex.Client.prototype)

#### <a name="apidoc.element.knex.Client.prototype._escapeBinding"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>_escapeBinding (val)](#apidoc.element.knex.Client.prototype._escapeBinding)
- description and source-code
```javascript
function finalEscape(val) {
  var ctx = arguments.length <= 1 || arguments[1] === undefined ? {} : arguments[1];

  return escapeFn(val, finalEscape, ctx);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.Client.prototype._formatQuery"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>_formatQuery (sql, bindings, timeZone)](#apidoc.element.knex.Client.prototype._formatQuery)
- description and source-code
```javascript
function _formatQuery(sql, bindings, timeZone) {
  var _this = this;

  bindings = bindings == null ? [] : [].concat(bindings);
  var index = 0;
  return sql.replace(/\\?\?/g, function (match) {
    if (match === '\\?') {
      return '?';
    }
    if (index === bindings.length) {
      return match;
    }
    var value = bindings[index++];
    return _this._escapeBinding(value, { timeZone: timeZone });
  });
}
```
- example usage
```shell
...

Target.prototype.toQuery = function (tz) {
  var _this = this;

  var data = this.toSQL(this._method, tz);
  if (!(0, _isArray3.default)(data)) data = [data];
  return (0, _map3.default)(data, function (statement) {
    return _this.client._formatQuery(statement.sql, statement.bindings, tz);
  }).join(';\n');
};

// Create a new instance of the 'Runner', passing in the current object.
Target.prototype.then = function () /* onFulfilled, onRejected */{
  var result = this.client.runner(this).run();
  return result.then.apply(result, arguments);
...
```

#### <a name="apidoc.element.knex.Client.prototype.acquireConnection"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>acquireConnection ()](#apidoc.element.knex.Client.prototype.acquireConnection)
- description and source-code
```javascript
function acquireConnection() {
  var _this4 = this;

  return new _bluebird2.default(function (resolver, rejecter) {
    if (!_this4.pool) {
      return rejecter(new Error('Unable to acquire a connection'));
    }
    var wasRejected = false;
    var t = setTimeout(function () {
      wasRejected = true;
      rejecter(new _bluebird2.default.TimeoutError('Knex: Timeout acquiring a connection. The pool is probably full. ' + 'Are you
 missing a .transacting(trx) call?'));
    }, _this4.config.acquireConnectionTimeout || 60000);
    _this4.pool.acquire(function (err, connection) {
      clearTimeout(t);
      if (err) {
        return rejecter(err);
      }
      if (wasRejected) {
        _this4.pool.release(connection);
      } else {
        debug('acquired connection from pool: %s', connection.__knexUid);
        resolver(connection);
      }
    });
  });
}
```
- example usage
```shell
...
  // Check whether there's a transaction flag, and that it has a connection.
  ensureConnection: function ensureConnection() {
var _this2 = this;

return _bluebird2.default.try(function () {
  return _this2.connection || new _bluebird2.default(function (resolver, rejecter) {
    // need to return promise or null from handler to prevent warning from bluebird
    return _this2.client.acquireConnection().then(resolver).catch(_bluebird2.default.TimeoutError, function (error) {
      if (_this2.builder) {
        error.sql = _this2.builder.sql;
        error.bindings = _this2.builder.bindings;
      }
      throw error;
    }).catch(rejecter);
  });
...
```

#### <a name="apidoc.element.knex.Client.prototype.assertCanCancelQuery"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>assertCanCancelQuery ()](#apidoc.element.knex.Client.prototype.assertCanCancelQuery)
- description and source-code
```javascript
function assertCanCancelQuery() {
  if (!this.canCancelQuery) {
    throw new Error("Query cancelling not supported for this dialect");
  }
}
```
- example usage
```shell
...
  var _ref = arguments.length <= 1 || arguments[1] === undefined ? {} : arguments[1];

  var cancel = _ref.cancel;

  if ((0, _isNumber3.default)(ms) && ms > 0) {
    this._timeout = ms;
    if (cancel) {
      this.client.assertCanCancelQuery();
      this._cancelOnTimeout = true;
    }
  }
  return this;
},
...
```

#### <a name="apidoc.element.knex.Client.prototype.cancelQuery"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>cancelQuery ()](#apidoc.element.knex.Client.prototype.cancelQuery)
- description and source-code
```javascript
function cancelQuery() {
  throw new Error("Query cancelling not supported for this dialect");
}
```
- example usage
```shell
...
var timeout = obj.timeout;
var sql = obj.sql;
var bindings = obj.bindings;


var cancelQuery = void 0;
if (obj.cancelOnTimeout) {
  cancelQuery = _this.client.cancelQuery(_this.connection);
} else {
  cancelQuery = _bluebird2.default.resolve();
}

return cancelQuery.catch(function (cancelError) {
  // cancellation failed
  throw (0, _assign3.default)(cancelError, {
...
```

#### <a name="apidoc.element.knex.Client.prototype.columnBuilder"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>columnBuilder (tableBuilder, type, args)](#apidoc.element.knex.Client.prototype.columnBuilder)
- description and source-code
```javascript
function columnBuilder(tableBuilder, type, args) {
  return new _columnbuilder2.default(this, tableBuilder, type, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.Client.prototype.columnCompiler"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>columnCompiler (tableBuilder, columnBuilder)](#apidoc.element.knex.Client.prototype.columnCompiler)
- description and source-code
```javascript
function columnCompiler(tableBuilder, columnBuilder) {
  return new _columncompiler2.default(this, tableBuilder, columnBuilder);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.Client.prototype.database"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>database ()](#apidoc.element.knex.Client.prototype.database)
- description and source-code
```javascript
function database() {
  return this.connectionSettings.database;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.Client.prototype.destroy"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>destroy (callback)](#apidoc.element.knex.Client.prototype.destroy)
- description and source-code
```javascript
function destroy(callback) {
  var _this6 = this;

  var promise = new _bluebird2.default(function (resolver) {
    if (!_this6.pool) {
      return resolver();
    }
    _this6.pool.drain(function () {
      _this6.pool.destroyAllNow(function () {
        _this6.pool = undefined;
        resolver();
      });
    });
  });

  // Allow either a callback or promise interface for destruction.
  if (typeof callback === 'function') {
    promise.asCallback(callback);
  } else {
    return promise;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.Client.prototype.formatter"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>formatter ()](#apidoc.element.knex.Client.prototype.formatter)
- description and source-code
```javascript
function formatter() {
  return new _formatter2.default(this);
}
```
- example usage
```shell
...
return this.toQuery();
  },


  // Returns the raw sql for the query.
  toSQL: function toSQL(method, tz) {
var obj = void 0;
var formatter = this.client.formatter();

if (Array.isArray(this.bindings)) {
  obj = replaceRawArrBindings(this, formatter);
} else if (this.bindings && (0, _isPlainObject3.default)(this.bindings)) {
  obj = replaceKeyBindings(this, formatter);
} else {
  obj = {
...
```

#### <a name="apidoc.element.knex.Client.prototype.initializeDriver"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>initializeDriver ()](#apidoc.element.knex.Client.prototype.initializeDriver)
- description and source-code
```javascript
function initializeDriver() {
  try {
    this.driver = this._driver();
  } catch (e) {
    helpers.exit('Knex: run\n$ npm install ' + this.driverName + ' --save\n' + e.stack);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.Client.prototype.initializePool"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>initializePool (config)](#apidoc.element.knex.Client.prototype.initializePool)
- description and source-code
```javascript
function initializePool(config) {
  if (this.pool) {
    helpers.warn('The pool has already been initialized');
    return;
  }
  this.pool = new _genericPool.Pool((0, _assign3.default)(this.poolDefaults(config.pool || {}), config.pool));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.Client.prototype.poolDefaults"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>poolDefaults (poolConfig)](#apidoc.element.knex.Client.prototype.poolDefaults)
- description and source-code
```javascript
function poolDefaults(poolConfig) {
  var _this3 = this;

  var name = this.dialect + ':' + this.driverName + ':' + this.__cid;
  return {
    min: 2,
    max: 10,
    name: name,
    log: function log(str, level) {
      if (level === 'info') {
        debugPool(level.toUpperCase() + ' pool ' + name + ' - ' + str);
      }
    },

    create: function create(callback) {
      _this3.acquireRawConnection().tap(function (connection) {
        connection.__knexUid = (0, _uniqueId3.default)('__knexUid');
        if (poolConfig.afterCreate) {
          return _bluebird2.default.promisify(poolConfig.afterCreate)(connection);
        }
      }).asCallback(callback);
    },
    destroy: function destroy(connection) {
      if (poolConfig.beforeDestroy) {
        helpers.warn('\n            beforeDestroy is deprecated, please open an issue if you use this\n            to discuss alternative
 apis\n          ');
        poolConfig.beforeDestroy(connection, function () {});
      }
      if (connection !== void 0) {
        _this3.destroyRawConnection(connection);
      }
    },
    validate: function validate(connection) {
      if (connection.__knex__disposed) {
        helpers.warn('Connection Error: ' + connection.__knex__disposed);
        return false;
      }
      return _this3.validateConnection(connection);
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.Client.prototype.prepBindings"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>prepBindings (bindings)](#apidoc.element.knex.Client.prototype.prepBindings)
- description and source-code
```javascript
function prepBindings(bindings) {
  return bindings;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.Client.prototype.query"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>query (connection, obj)](#apidoc.element.knex.Client.prototype.query)
- description and source-code
```javascript
function query(connection, obj) {
  var _this2 = this;

  if (typeof obj === 'string') obj = { sql: obj };
  obj.bindings = this.prepBindings(obj.bindings);
  debugQuery(obj.sql);
  this.emit('query', (0, _assign3.default)({ __knexUid: connection.__knexUid }, obj));
  debugBindings(obj.bindings);
  return this._query(connection, obj).catch(function (err) {
    err.message = _this2._formatQuery(obj.sql, obj.bindings) + ' - ' + err.message;
    _this2.emit('query-error', err, (0, _assign3.default)({ __knexUid: connection.__knexUid }, obj));
    throw err;
  });
}
```
- example usage
```shell
...
  if (runner.builder._debug) {
    helpers.debugLog(sql);
  }

  if ((0, _isArray3.default)(sql)) {
    return runner.queryArray(sql);
  }
  return runner.query(sql);
})

// If there are any "error" listeners, we fire an error event
// and then re-throw the error to be eventually handled by
// the promise chain. Useful if you're wrapping in a custom 'Promise'.
.catch(function (err) {
  if (runner.builder._events && runner.builder._events.error) {
...
```

#### <a name="apidoc.element.knex.Client.prototype.queryBuilder"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>queryBuilder ()](#apidoc.element.knex.Client.prototype.queryBuilder)
- description and source-code
```javascript
function queryBuilder() {
  return new _builder2.default(this);
}
```
- example usage
```shell
...


  Formatter.prototype.compileCallback = function compileCallback(callback, method) {
var client = this.client;

// Build the callback

var builder = client.queryBuilder();
callback.call(builder, builder);

// Compile the callback, using the current formatter (to track all bindings).
var compiler = client.queryCompiler(builder);
compiler.formatter = this;

// Return the compiled & parameterized sql.
...
```

#### <a name="apidoc.element.knex.Client.prototype.queryCompiler"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>queryCompiler (builder)](#apidoc.element.knex.Client.prototype.queryCompiler)
- description and source-code
```javascript
function queryCompiler(builder) {
  return new _compiler2.default(this, builder);
}
```
- example usage
```shell
...
  }
  return this.unwrapRaw(value, true) || '?';
};

Formatter.prototype.unwrapRaw = function unwrapRaw(value, isParameter) {
  var query = void 0;
  if (value instanceof _builder2.default) {
    query = this.client.queryCompiler(value).toSQL();
    if (query.bindings) {
      this.bindings = this.bindings.concat(query.bindings);
    }
    return this.outputQuery(query, isParameter);
  }
  if (value instanceof _raw2.default) {
    value.client = this.client;
...
```

#### <a name="apidoc.element.knex.Client.prototype.raw"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>raw ()](#apidoc.element.knex.Client.prototype.raw)
- description and source-code
```javascript
function raw() {
  var _ref;

  return (_ref = new _raw2.default(this)).set.apply(_ref, arguments);
}
```
- example usage
```shell
...
// FunctionHelper
// -------
function FunctionHelper(client) {
  this.client = client;
}

FunctionHelper.prototype.now = function () {
  return this.client.raw('CURRENT_TIMESTAMP');
};

exports.default = FunctionHelper;
module.exports = exports['default'];
...
```

#### <a name="apidoc.element.knex.Client.prototype.releaseConnection"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>releaseConnection (connection)](#apidoc.element.knex.Client.prototype.releaseConnection)
- description and source-code
```javascript
function releaseConnection(connection) {
  var _this5 = this;

  return new _bluebird2.default(function (resolver) {
    debug('releasing connection to pool: %s', connection.__knexUid);
    _this5.pool.release(connection);
    resolver();
  });
}
```
- example usage
```shell
...
            error.bindings = _this2.builder.bindings;
          }
          throw error;
        }).catch(rejecter);
      });
    }).disposer(function () {
      // need to return promise or null from handler to prevent warning from bluebird
      return _this2.client.releaseConnection(_this2.connection);
    });
  }
});

exports.default = Runner;
module.exports = exports['default'];
...
```

#### <a name="apidoc.element.knex.Client.prototype.runner"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>runner (connection)](#apidoc.element.knex.Client.prototype.runner)
- description and source-code
```javascript
function runner(connection) {
  return new _runner2.default(this, connection);
}
```
- example usage
```shell
...
  return (0, _map3.default)(data, function (statement) {
    return _this.client._formatQuery(statement.sql, statement.bindings, tz);
  }).join(';\n');
};

// Create a new instance of the 'Runner', passing in the current object.
Target.prototype.then = function () /* onFulfilled, onRejected */{
  var result = this.client.runner(this).run();
  return result.then.apply(result, arguments);
};

// Add additional "options" to the builder. Typically used for client specific
// items, like the 'mysql' and 'sqlite3' drivers.
Target.prototype.options = function (opts) {
  this._options = this._options || [];
...
```

#### <a name="apidoc.element.knex.Client.prototype.schemaBuilder"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>schemaBuilder ()](#apidoc.element.knex.Client.prototype.schemaBuilder)
- description and source-code
```javascript
function schemaBuilder() {
  return new _builder4.default(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.Client.prototype.schemaCompiler"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>schemaCompiler (builder)](#apidoc.element.knex.Client.prototype.schemaCompiler)
- description and source-code
```javascript
function schemaCompiler(builder) {
  return new _compiler4.default(this, builder);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.Client.prototype.stream"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>stream (connection, obj, _stream, options)](#apidoc.element.knex.Client.prototype.stream)
- description and source-code
```javascript
function stream(connection, obj, _stream, options) {
  if (typeof obj === 'string') obj = { sql: obj };
  this.emit('query', (0, _assign3.default)({ __knexUid: connection.__knexUid }, obj));
  debugQuery(obj.sql);
  obj.bindings = this.prepBindings(obj.bindings);
  debugBindings(obj.bindings);
  return this._stream(connection, obj, _stream, options);
}
```
- example usage
```shell
...
    }
  }
  return this;
};

// Initializes a stream.
Target.prototype.stream = function (options) {
  return this.client.runner(this).stream(options);
};

// Initialize a stream & pipe automatically.
Target.prototype.pipe = function (writable, options) {
  return this.client.runner(this).pipe(writable, options);
};
...
```

#### <a name="apidoc.element.knex.Client.prototype.tableBuilder"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>tableBuilder (type, tableName, fn)](#apidoc.element.knex.Client.prototype.tableBuilder)
- description and source-code
```javascript
function tableBuilder(type, tableName, fn) {
  return new _tablebuilder2.default(this, type, tableName, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.Client.prototype.tableCompiler"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>tableCompiler (tableBuilder)](#apidoc.element.knex.Client.prototype.tableCompiler)
- description and source-code
```javascript
function tableCompiler(tableBuilder) {
  return new _tablecompiler2.default(this, tableBuilder);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.Client.prototype.toString"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>toString ()](#apidoc.element.knex.Client.prototype.toString)
- description and source-code
```javascript
function toString() {
  return '[object KnexClient]';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.Client.prototype.transaction"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>transaction (container, config, outerTx)](#apidoc.element.knex.Client.prototype.transaction)
- description and source-code
```javascript
function transaction(container, config, outerTx) {
  return new _transaction2.default(this, container, config, outerTx);
}
```
- example usage
```shell
...

exports.default = Transaction;
function makeTransactor(trx, connection, trxClient) {

var transactor = (0, _makeKnex2.default)(trxClient);

transactor.transaction = function (container, options) {
  return trxClient.transaction(container, options, trx);
};
transactor.savepoint = function (container, options) {
  return transactor.transaction(container, options);
};

if (trx.client.transacting) {
  transactor.commit = function (value) {
...
```

#### <a name="apidoc.element.knex.Client.prototype.validateConnection"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>validateConnection (connection)](#apidoc.element.knex.Client.prototype.validateConnection)
- description and source-code
```javascript
function validateConnection(connection) {
  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.Client.prototype.wrapIdentifier"></a>[function <span class="apidocSignatureSpan">knex.Client.prototype.</span>wrapIdentifier (value)](#apidoc.element.knex.Client.prototype.wrapIdentifier)
- description and source-code
```javascript
function wrapIdentifier(value) {
  return value !== '*' ? '"' + value.replace(/"/g, '""') + '"' : '*';
}
```
- example usage
```shell
...
  var raw = this.unwrapRaw(value);
  if (raw) return raw;
  if (typeof value === 'number') return value;
  return this._wrapString(value + '');
};

Formatter.prototype.wrapAsIdentifier = function wrapAsIdentifier(value) {
  return this.client.wrapIdentifier((value || '').trim());
};

Formatter.prototype.alias = function alias(first, second) {
  return first + ' as ' + second;
};

// The operator method takes a value and returns something or other.
...
```



# <a name="apidoc.module.knex.formatter"></a>[module knex.formatter](#apidoc.module.knex.formatter)

#### <a name="apidoc.element.knex.formatter.formatter"></a>[function <span class="apidocSignatureSpan">knex.</span>formatter (client)](#apidoc.element.knex.formatter.formatter)
- description and source-code
```javascript
function Formatter(client) {
  (0, _classCallCheck3.default)(this, Formatter);

  this.client = client;
  this.bindings = [];
}
```
- example usage
```shell
...
return this.toQuery();
  },


  // Returns the raw sql for the query.
  toSQL: function toSQL(method, tz) {
var obj = void 0;
var formatter = this.client.formatter();

if (Array.isArray(this.bindings)) {
  obj = replaceRawArrBindings(this, formatter);
} else if (this.bindings && (0, _isPlainObject3.default)(this.bindings)) {
  obj = replaceKeyBindings(this, formatter);
} else {
  obj = {
...
```



# <a name="apidoc.module.knex.formatter.prototype"></a>[module knex.formatter.prototype](#apidoc.module.knex.formatter.prototype)

#### <a name="apidoc.element.knex.formatter.prototype._wrapString"></a>[function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>_wrapString (value)](#apidoc.element.knex.formatter.prototype._wrapString)
- description and source-code
```javascript
function _wrapString(value) {
  var asIndex = value.toLowerCase().indexOf(' as ');
  if (asIndex !== -1) {
    var first = value.slice(0, asIndex);
    var second = value.slice(asIndex + 4);
    return this.alias(this.wrap(first), this.wrapAsIdentifier(second));
  }
  var wrapped = [];
  var i = -1;
  var segments = value.split('.');
  while (++i < segments.length) {
    value = segments[i];
    if (i === 0 && segments.length > 1) {
      wrapped.push(this.wrap((value || '').trim()));
    } else {
      wrapped.push(this.client.wrapIdentifier((value || '').trim()));
    }
  }
  return wrapped.join('.');
}
```
- example usage
```shell
...
Formatter.prototype.wrap = function wrap(value) {
  if (typeof value === 'function') {
    return this.outputQuery(this.compileCallback(value), true);
  }
  var raw = this.unwrapRaw(value);
  if (raw) return raw;
  if (typeof value === 'number') return value;
  return this._wrapString(value + '');
};

Formatter.prototype.wrapAsIdentifier = function wrapAsIdentifier(value) {
  return this.client.wrapIdentifier((value || '').trim());
};

Formatter.prototype.alias = function alias(first, second) {
...
```

#### <a name="apidoc.element.knex.formatter.prototype.alias"></a>[function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>alias (first, second)](#apidoc.element.knex.formatter.prototype.alias)
- description and source-code
```javascript
function alias(first, second) {
  return first + ' as ' + second;
}
```
- example usage
```shell
...


Formatter.prototype.outputQuery = function outputQuery(compiled, isParameter) {
  var sql = compiled.sql || '';
  if (sql) {
    if ((compiled.method === 'select' || compiled.method === 'first') && (isParameter || compiled.as)) {
      sql = '(' + sql + ')';
      if (compiled.as) return this.alias(sql, this.wrap(compiled.as));
    }
  }
  return sql;
};

// Coerce to string to prevent strange errors when it's not a string.
...
```

#### <a name="apidoc.element.knex.formatter.prototype.columnize"></a>[function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>columnize (target)](#apidoc.element.knex.formatter.prototype.columnize)
- description and source-code
```javascript
function columnize(target) {
  var columns = typeof target === 'string' ? [target] : target;
  var str = '',
      i = -1;
  while (++i < columns.length) {
    if (i > 0) str += ', ';
    str += this.wrap(columns[i]);
  }
  return str;
}
```
- example usage
```shell
...
  if (match === '\\?') {
    return match;
  }

  var value = values[index++];

  if (match === '??') {
    return formatter.columnize(value);
  }
  return formatter.parameter(value);
});

if (expectedBindings !== index) {
  throw new Error('Expected ' + expectedBindings + ' bindings, saw ' + index);
}
...
```

#### <a name="apidoc.element.knex.formatter.prototype.compileCallback"></a>[function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>compileCallback (callback, method)](#apidoc.element.knex.formatter.prototype.compileCallback)
- description and source-code
```javascript
function compileCallback(callback, method) {
  var client = this.client;

  // Build the callback

  var builder = client.queryBuilder();
  callback.call(builder, builder);

  // Compile the callback, using the current formatter (to track all bindings).
  var compiler = client.queryCompiler(builder);
  compiler.formatter = this;

  // Return the compiled & parameterized sql.
  return compiler.toSQL(method || 'select');
}
```
- example usage
```shell
...

// Checks whether a value is a function... if it is, we compile it
// otherwise we check whether it's a raw


Formatter.prototype.parameter = function parameter(value) {
  if (typeof value === 'function') {
    return this.outputQuery(this.compileCallback(value), true);
  }
  return this.unwrapRaw(value, true) || '?';
};

Formatter.prototype.unwrapRaw = function unwrapRaw(value, isParameter) {
  var query = void 0;
  if (value instanceof _builder2.default) {
...
```

#### <a name="apidoc.element.knex.formatter.prototype.direction"></a>[function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>direction (value)](#apidoc.element.knex.formatter.prototype.direction)
- description and source-code
```javascript
function direction(value) {
  var raw = this.unwrapRaw(value);
  if (raw) return raw;
  return orderBys.indexOf((value || '').toLowerCase()) !== -1 ? value : 'asc';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.formatter.prototype.operator"></a>[function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>operator (value)](#apidoc.element.knex.formatter.prototype.operator)
- description and source-code
```javascript
function operator(value) {
  var raw = this.unwrapRaw(value);
  if (raw) return raw;
  if (operators[(value || '').toLowerCase()] !== true) {
    throw new TypeError('The operator "' + value + '" is not permitted');
  }
  return value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.formatter.prototype.outputQuery"></a>[function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>outputQuery (compiled, isParameter)](#apidoc.element.knex.formatter.prototype.outputQuery)
- description and source-code
```javascript
function outputQuery(compiled, isParameter) {
  var sql = compiled.sql || '';
  if (sql) {
    if ((compiled.method === 'select' || compiled.method === 'first') && (isParameter || compiled.as)) {
      sql = '(' + sql + ')';
      if (compiled.as) return this.alias(sql, this.wrap(compiled.as));
    }
  }
  return sql;
}
```
- example usage
```shell
...

// Checks whether a value is a function... if it is, we compile it
// otherwise we check whether it's a raw


Formatter.prototype.parameter = function parameter(value) {
  if (typeof value === 'function') {
    return this.outputQuery(this.compileCallback(value), true);
  }
  return this.unwrapRaw(value, true) || '?';
};

Formatter.prototype.unwrapRaw = function unwrapRaw(value, isParameter) {
  var query = void 0;
  if (value instanceof _builder2.default) {
...
```

#### <a name="apidoc.element.knex.formatter.prototype.parameter"></a>[function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>parameter (value)](#apidoc.element.knex.formatter.prototype.parameter)
- description and source-code
```javascript
function parameter(value) {
  if (typeof value === 'function') {
    return this.outputQuery(this.compileCallback(value), true);
  }
  return this.unwrapRaw(value, true) || '?';
}
```
- example usage
```shell
...
};

// Turns a list of values into a list of ?'s, joining them with commas unless
// a "joining" value is specified (e.g. ' and ')


Formatter.prototype.parameterize = function parameterize(values, notSetValue) {
  if (typeof values === 'function') return this.parameter(values);
  values = Array.isArray(values) ? values : [values];
  var str = '',
      i = -1;
  while (++i < values.length) {
    if (i > 0) str += ', ';
    str += this.parameter(values[i] === undefined ? notSetValue : values[i]);
  }
...
```

#### <a name="apidoc.element.knex.formatter.prototype.parameterize"></a>[function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>parameterize (values, notSetValue)](#apidoc.element.knex.formatter.prototype.parameterize)
- description and source-code
```javascript
function parameterize(values, notSetValue) {
  if (typeof values === 'function') return this.parameter(values);
  values = Array.isArray(values) ? values : [values];
  var str = '',
      i = -1;
  while (++i < values.length) {
    if (i > 0) str += ', ';
    str += this.parameter(values[i] === undefined ? notSetValue : values[i]);
  }
  return str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.formatter.prototype.rawOrFn"></a>[function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>rawOrFn (value, method)](#apidoc.element.knex.formatter.prototype.rawOrFn)
- description and source-code
```javascript
function rawOrFn(value, method) {
  if (typeof value === 'function') {
    return this.outputQuery(this.compileCallback(value, method));
  }
  return this.unwrapRaw(value) || '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.formatter.prototype.unwrapRaw"></a>[function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>unwrapRaw (value, isParameter)](#apidoc.element.knex.formatter.prototype.unwrapRaw)
- description and source-code
```javascript
function unwrapRaw(value, isParameter) {
  var query = void 0;
  if (value instanceof _builder2.default) {
    query = this.client.queryCompiler(value).toSQL();
    if (query.bindings) {
      this.bindings = this.bindings.concat(query.bindings);
    }
    return this.outputQuery(query, isParameter);
  }
  if (value instanceof _raw2.default) {
    value.client = this.client;
    query = value.toSQL();
    if (query.bindings) {
      this.bindings = this.bindings.concat(query.bindings);
    }
    return query.sql;
  }
  if (isParameter) {
    this.bindings.push(value);
  }
}
```
- example usage
```shell
...
// otherwise we check whether it's a raw


Formatter.prototype.parameter = function parameter(value) {
  if (typeof value === 'function') {
    return this.outputQuery(this.compileCallback(value), true);
  }
  return this.unwrapRaw(value, true) || '?';
};

Formatter.prototype.unwrapRaw = function unwrapRaw(value, isParameter) {
  var query = void 0;
  if (value instanceof _builder2.default) {
    query = this.client.queryCompiler(value).toSQL();
    if (query.bindings) {
...
```

#### <a name="apidoc.element.knex.formatter.prototype.wrap"></a>[function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>wrap (value)](#apidoc.element.knex.formatter.prototype.wrap)
- description and source-code
```javascript
function wrap(value) {
  if (typeof value === 'function') {
    return this.outputQuery(this.compileCallback(value), true);
  }
  var raw = this.unwrapRaw(value);
  if (raw) return raw;
  if (typeof value === 'number') return value;
  return this._wrapString(value + '');
}
```
- example usage
```shell
...

Formatter.prototype.columnize = function columnize(target) {
  var columns = typeof target === 'string' ? [target] : target;
  var str = '',
      i = -1;
  while (++i < columns.length) {
    if (i > 0) str += ', ';
    str += this.wrap(columns[i]);
  }
  return str;
};

// Turns a list of values into a list of ?'s, joining them with commas unless
// a "joining" value is specified (e.g. ' and ')
...
```

#### <a name="apidoc.element.knex.formatter.prototype.wrapAsIdentifier"></a>[function <span class="apidocSignatureSpan">knex.formatter.prototype.</span>wrapAsIdentifier (value)](#apidoc.element.knex.formatter.prototype.wrapAsIdentifier)
- description and source-code
```javascript
function wrapAsIdentifier(value) {
  return this.client.wrapIdentifier((value || '').trim());
}
```
- example usage
```shell
...


  Formatter.prototype._wrapString = function _wrapString(value) {
var asIndex = value.toLowerCase().indexOf(' as ');
if (asIndex !== -1) {
  var first = value.slice(0, asIndex);
  var second = value.slice(asIndex + 4);
  return this.alias(this.wrap(first), this.wrapAsIdentifier(second));
}
var wrapped = [];
var i = -1;
var segments = value.split('.');
while (++i < segments.length) {
  value = segments[i];
  if (i === 0 && segments.length > 1) {
...
```



# <a name="apidoc.module.knex.functionhelper"></a>[module knex.functionhelper](#apidoc.module.knex.functionhelper)

#### <a name="apidoc.element.knex.functionhelper.functionhelper"></a>[function <span class="apidocSignatureSpan">knex.</span>functionhelper (client)](#apidoc.element.knex.functionhelper.functionhelper)
- description and source-code
```javascript
function FunctionHelper(client) {
  this.client = client;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.knex.functionhelper.prototype"></a>[module knex.functionhelper.prototype](#apidoc.module.knex.functionhelper.prototype)

#### <a name="apidoc.element.knex.functionhelper.prototype.now"></a>[function <span class="apidocSignatureSpan">knex.functionhelper.prototype.</span>now ()](#apidoc.element.knex.functionhelper.prototype.now)
- description and source-code
```javascript
now = function () {
  return this.client.raw('CURRENT_TIMESTAMP');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.knex.helpers"></a>[module knex.helpers](#apidoc.module.knex.helpers)

#### <a name="apidoc.element.knex.helpers.containsUndefined"></a>[function <span class="apidocSignatureSpan">knex.helpers.</span>containsUndefined (mixed)](#apidoc.element.knex.helpers.containsUndefined)
- description and source-code
```javascript
function containsUndefined(mixed) {
  var argContainsUndefined = false;

  if ((0, _isTypedArray3.default)(mixed)) return false;

  if (mixed && (0, _isFunction3.default)(mixed.toSQL)) {
    //Any QueryBuilder or Raw will automatically be validated during compile.
    return argContainsUndefined;
  }

  if ((0, _isArray3.default)(mixed)) {
    for (var i = 0; i < mixed.length; i++) {
      if (argContainsUndefined) break;
      argContainsUndefined = this.containsUndefined(mixed[i]);
    }
  } else if ((0, _isObject3.default)(mixed)) {
    for (var key in mixed) {
      if (argContainsUndefined) break;
      argContainsUndefined = this.containsUndefined(mixed[key]);
    }
  } else {
    argContainsUndefined = (0, _isUndefined3.default)(mixed);
  }

  return argContainsUndefined;
}
```
- example usage
```shell
...
  //Any QueryBuilder or Raw will automatically be validated during compile.
  return argContainsUndefined;
}

if ((0, _isArray3.default)(mixed)) {
  for (var i = 0; i < mixed.length; i++) {
    if (argContainsUndefined) break;
    argContainsUndefined = this.containsUndefined(mixed[i]);
  }
} else if ((0, _isObject3.default)(mixed)) {
  for (var key in mixed) {
    if (argContainsUndefined) break;
    argContainsUndefined = this.containsUndefined(mixed[key]);
  }
} else {
...
```

#### <a name="apidoc.element.knex.helpers.debugLog"></a>[function <span class="apidocSignatureSpan">knex.helpers.</span>debugLog (msg)](#apidoc.element.knex.helpers.debugLog)
- description and source-code
```javascript
function debugLog(msg) {
  console.log(msg);
}
```
- example usage
```shell
...
  runner.connection = connection;

  runner.client.emit('start', runner.builder);
  runner.builder.emit('start', runner.builder);
  var sql = runner.builder.toSQL();

  if (runner.builder._debug) {
    helpers.debugLog(sql);
  }

  if ((0, _isArray3.default)(sql)) {
    return runner.queryArray(sql);
  }
  return runner.query(sql);
})
...
```

#### <a name="apidoc.element.knex.helpers.deprecate"></a>[function <span class="apidocSignatureSpan">knex.helpers.</span>deprecate (method, alternate)](#apidoc.element.knex.helpers.deprecate)
- description and source-code
```javascript
function deprecate(method, alternate) {
  warn(method + ' is deprecated, please use ' + alternate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.helpers.error"></a>[function <span class="apidocSignatureSpan">knex.helpers.</span>error (msg)](#apidoc.element.knex.helpers.error)
- description and source-code
```javascript
function error(msg) {
  console.log(_chalk2.default.red('Knex:Error ' + msg));
}
```
- example usage
```shell
...
// .map over the results
.map(function(row) {
  console.log(row);
})

// Finally, add a .catch handler for the promise chain
.catch(function(e) {
  console.error(e);
});
'''
...
```

#### <a name="apidoc.element.knex.helpers.exit"></a>[function <span class="apidocSignatureSpan">knex.helpers.</span>exit (msg)](#apidoc.element.knex.helpers.exit)
- description and source-code
```javascript
function exit(msg) {
  console.log(_chalk2.default.red(msg));
  process.exit(1);
}
```
- example usage
```shell
...
// Used to warn about incorrect use, without error'ing
function warn(msg) {
console.log(_chalk2.default.yellow('Knex:warning - ' + msg));
}

function exit(msg) {
console.log(_chalk2.default.red(msg));
process.exit(1);
}

function containsUndefined(mixed) {
var argContainsUndefined = false;

if ((0, _isTypedArray3.default)(mixed)) return false;
...
```

#### <a name="apidoc.element.knex.helpers.normalizeArr"></a>[function <span class="apidocSignatureSpan">knex.helpers.</span>normalizeArr ()](#apidoc.element.knex.helpers.normalizeArr)
- description and source-code
```javascript
function normalizeArr() {
  var args = new Array(arguments.length);
  for (var i = 0; i < args.length; i++) {
    args[i] = arguments[i];
  }
  if (Array.isArray(args[0])) {
    return args[0];
  }
  return args;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.helpers.skim"></a>[function <span class="apidocSignatureSpan">knex.helpers.</span>skim (data)](#apidoc.element.knex.helpers.skim)
- description and source-code
```javascript
function skim(data) {
  return (0, _map3.default)(data, function (obj) {
    return (0, _pick3.default)(obj, (0, _keys3.default)(obj));
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.helpers.warn"></a>[function <span class="apidocSignatureSpan">knex.helpers.</span>warn (msg)](#apidoc.element.knex.helpers.warn)
- description and source-code
```javascript
function warn(msg) {
  console.log(_chalk2.default.yellow('Knex:warning - ' + msg));
}
```
- example usage
```shell
...
  return this;
};

// Set the transaction object for this query.
Target.prototype.transacting = function (t) {
  if (t && t.client) {
    if (!t.client.transacting) {
      helpers.warn('Invalid transaction value: ' + t.client);
    } else {
      this.client = t.client;
    }
  }
  return this;
};
...
```



# <a name="apidoc.module.knex.raw"></a>[module knex.raw](#apidoc.module.knex.raw)

#### <a name="apidoc.element.knex.raw.raw"></a>[function <span class="apidocSignatureSpan">knex.</span>raw ()](#apidoc.element.knex.raw.raw)
- description and source-code
```javascript
function Raw() {
  var client = arguments.length <= 0 || arguments[0] === undefined ? fakeClient : arguments[0];

  this.client = client;

  this.sql = '';
  this.bindings = [];

  // Todo: Deprecate
  this._wrappedBefore = undefined;
  this._wrappedAfter = undefined;
  this._debug = client && client.config && client.config.debug;
}
```
- example usage
```shell
...
// FunctionHelper
// -------
function FunctionHelper(client) {
  this.client = client;
}

FunctionHelper.prototype.now = function () {
  return this.client.raw('CURRENT_TIMESTAMP');
};

exports.default = FunctionHelper;
module.exports = exports['default'];
...
```

#### <a name="apidoc.element.knex.raw.super_"></a>[function <span class="apidocSignatureSpan">knex.raw.</span>super_ ()](#apidoc.element.knex.raw.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.knex.raw.prototype"></a>[module knex.raw.prototype](#apidoc.module.knex.raw.prototype)

#### <a name="apidoc.element.knex.raw.prototype.asCallback"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>asCallback ()](#apidoc.element.knex.raw.prototype.asCallback)
- description and source-code
```javascript
asCallback = function () {
  var promise = this.then();
  return promise[method].apply(promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.raw.prototype.bind"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>bind ()](#apidoc.element.knex.raw.prototype.bind)
- description and source-code
```javascript
bind = function () {
  var promise = this.then();
  return promise[method].apply(promise, arguments);
}
```
- example usage
```shell
...
    throw error;
  });
}),

// In the case of the "schema builder" we call 'queryArray', which runs each
// of the queries in sequence.
queryArray: function queryArray(queries) {
  return queries.length === 1 ? this.query(queries[0]) : _bluebird2.default.bind(this).return(queries).reduce(function (memo, query
) {
    return this.query(query).then(function (resp) {
      memo.push(resp);
      return memo;
    });
  }, []);
},
...
```

#### <a name="apidoc.element.knex.raw.prototype.catch"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>catch ()](#apidoc.element.knex.raw.prototype.catch)
- description and source-code
```javascript
catch = function () {
  var promise = this.then();
  return promise[method].apply(promise, arguments);
}
```
- example usage
```shell
...

// .map over the results
.map(function(row) {
  console.log(row);
})

// Finally, add a .catch handler for the promise chain
.catch(function(e) {
  console.error(e);
});
'''
...
```

#### <a name="apidoc.element.knex.raw.prototype.connection"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>connection (connection)](#apidoc.element.knex.raw.prototype.connection)
- description and source-code
```javascript
connection = function (connection) {
  this._connection = connection;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.raw.prototype.debug"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>debug (enabled)](#apidoc.element.knex.raw.prototype.debug)
- description and source-code
```javascript
debug = function (enabled) {
  this._debug = arguments.length ? enabled : true;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.raw.prototype.delay"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>delay ()](#apidoc.element.knex.raw.prototype.delay)
- description and source-code
```javascript
delay = function () {
  var promise = this.then();
  return promise[method].apply(promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.raw.prototype.ensure"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>ensure ()](#apidoc.element.knex.raw.prototype.ensure)
- description and source-code
```javascript
ensure = function () {
  var promise = this.then();
  return promise[method].apply(promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.raw.prototype.finally"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>finally ()](#apidoc.element.knex.raw.prototype.finally)
- description and source-code
```javascript
finally = function () {
  var promise = this.then();
  return promise[method].apply(promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.raw.prototype.get"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>get ()](#apidoc.element.knex.raw.prototype.get)
- description and source-code
```javascript
get = function () {
  var promise = this.then();
  return promise[method].apply(promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.raw.prototype.map"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>map ()](#apidoc.element.knex.raw.prototype.map)
- description and source-code
```javascript
map = function () {
  var promise = this.then();
  return promise[method].apply(promise, arguments);
}
```
- example usage
```shell
...
.then(function() {
  return knex('users')
    .join('accounts', 'users.id', 'accounts.user_id')
    .select('users.user_name as user', 'accounts.account_name as account');
})

// .map over the results
.map(function(row) {
  console.log(row);
})

// Finally, add a .catch handler for the promise chain
.catch(function(e) {
  console.error(e);
});
...
```

#### <a name="apidoc.element.knex.raw.prototype.mapSeries"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>mapSeries ()](#apidoc.element.knex.raw.prototype.mapSeries)
- description and source-code
```javascript
mapSeries = function () {
  var promise = this.then();
  return promise[method].apply(promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.raw.prototype.options"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>options (opts)](#apidoc.element.knex.raw.prototype.options)
- description and source-code
```javascript
options = function (opts) {
  this._options = this._options || [];
  this._options.push((0, _clone3.default)(opts) || {});
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.raw.prototype.pipe"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>pipe (writable, options)](#apidoc.element.knex.raw.prototype.pipe)
- description and source-code
```javascript
pipe = function (writable, options) {
  return this.client.runner(this).pipe(writable, options);
}
```
- example usage
```shell
...
// Initializes a stream.
Target.prototype.stream = function (options) {
  return this.client.runner(this).stream(options);
};

// Initialize a stream & pipe automatically.
Target.prototype.pipe = function (writable, options) {
  return this.client.runner(this).pipe(writable, options);
};

// Creates a method which "coerces" to a promise, by calling a
// "then" method on the current 'Target'
(0, _each3.default)(['bind', 'catch', 'finally', 'asCallback', 'spread', 'map', 'reduce', 'tap', 'thenReturn', 'return', 'yield', '
ensure', 'reflect', 'get', 'mapSeries', 'delay'], function (method) {
  Target.prototype[method] = function () {
    var promise = this.then();
...
```

#### <a name="apidoc.element.knex.raw.prototype.reduce"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>reduce ()](#apidoc.element.knex.raw.prototype.reduce)
- description and source-code
```javascript
reduce = function () {
  var promise = this.then();
  return promise[method].apply(promise, arguments);
}
```
- example usage
```shell
...
    throw error;
  });
}),

// In the case of the "schema builder" we call 'queryArray', which runs each
// of the queries in sequence.
queryArray: function queryArray(queries) {
  return queries.length === 1 ? this.query(queries[0]) : _bluebird2.default.bind(this).return(queries).reduce(function (memo, query
) {
    return this.query(query).then(function (resp) {
      memo.push(resp);
      return memo;
    });
  }, []);
},
...
```

#### <a name="apidoc.element.knex.raw.prototype.reflect"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>reflect ()](#apidoc.element.knex.raw.prototype.reflect)
- description and source-code
```javascript
reflect = function () {
  var promise = this.then();
  return promise[method].apply(promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.raw.prototype.return"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>return ()](#apidoc.element.knex.raw.prototype.return)
- description and source-code
```javascript
return = function () {
  var promise = this.then();
  return promise[method].apply(promise, arguments);
}
```
- example usage
```shell
...
    throw error;
  });
}),

// In the case of the "schema builder" we call 'queryArray', which runs each
// of the queries in sequence.
queryArray: function queryArray(queries) {
  return queries.length === 1 ? this.query(queries[0]) : _bluebird2.default.bind(this).return(queries).reduce(function (memo, query
) {
    return this.query(query).then(function (resp) {
      memo.push(resp);
      return memo;
    });
  }, []);
},
...
```

#### <a name="apidoc.element.knex.raw.prototype.set"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>set (sql, bindings)](#apidoc.element.knex.raw.prototype.set)
- description and source-code
```javascript
function set(sql, bindings) {
  this.sql = sql;
  this.bindings = (0, _isObject3.default)(bindings) && !bindings.toSQL || (0, _isUndefined3.default)(bindings) ? bindings : [bindings
];

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.raw.prototype.spread"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>spread ()](#apidoc.element.knex.raw.prototype.spread)
- description and source-code
```javascript
spread = function () {
  var promise = this.then();
  return promise[method].apply(promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.raw.prototype.stream"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>stream (options)](#apidoc.element.knex.raw.prototype.stream)
- description and source-code
```javascript
stream = function (options) {
  return this.client.runner(this).stream(options);
}
```
- example usage
```shell
...
    }
  }
  return this;
};

// Initializes a stream.
Target.prototype.stream = function (options) {
  return this.client.runner(this).stream(options);
};

// Initialize a stream & pipe automatically.
Target.prototype.pipe = function (writable, options) {
  return this.client.runner(this).pipe(writable, options);
};
...
```

#### <a name="apidoc.element.knex.raw.prototype.tap"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>tap ()](#apidoc.element.knex.raw.prototype.tap)
- description and source-code
```javascript
tap = function () {
  var promise = this.then();
  return promise[method].apply(promise, arguments);
}
```
- example usage
```shell
...
      runner.builder.emit('error', err);
    }
    throw err;
  })

  // Fire a single "end" event on the builder when
  // all queries have successfully completed.
  .tap(function () {
    runner.builder.emit('end');
  });
},


// Stream the result set, by passing through to the dialect's streaming
// capabilities. If the options are
...
```

#### <a name="apidoc.element.knex.raw.prototype.then"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>then ()](#apidoc.element.knex.raw.prototype.then)
- description and source-code
```javascript
then = function () /* onFulfilled, onRejected */{
  var result = this.client.runner(this).run();
  return result.then.apply(result, arguments);
}
```
- example usage
```shell
...
.createTable('accounts', function(table) {
  table.increments('id');
  table.string('account_name');
  table.integer('user_id').unsigned().references('users.id');
})

// Then query the table...
.then(function() {
  return knex.insert({user_name: 'Tim'}).into('users');
})

// ...and using the insert id, insert into the other table.
.then(function(rows) {
  return knex.table('accounts').insert({account_name: 'knex', user_id: rows[0]});
})
...
```

#### <a name="apidoc.element.knex.raw.prototype.thenReturn"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>thenReturn ()](#apidoc.element.knex.raw.prototype.thenReturn)
- description and source-code
```javascript
thenReturn = function () {
  var promise = this.then();
  return promise[method].apply(promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.raw.prototype.timeout"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>timeout (ms)](#apidoc.element.knex.raw.prototype.timeout)
- description and source-code
```javascript
function timeout(ms) {
  var _ref = arguments.length <= 1 || arguments[1] === undefined ? {} : arguments[1];

  var cancel = _ref.cancel;

  if ((0, _isNumber3.default)(ms) && ms > 0) {
    this._timeout = ms;
    if (cancel) {
      this.client.assertCanCancelQuery();
      this._cancelOnTimeout = true;
    }
  }
  return this;
}
```
- example usage
```shell
...
var _this = this;

this.builder.emit('query', (0, _assign3.default)({ __knexUid: this.connection.__knexUid }, obj));
var runner = this;
var queryPromise = this.client.query(this.connection, obj);

if (obj.timeout) {
  queryPromise = queryPromise.timeout(obj.timeout);
}

return queryPromise.then(function (resp) {
  var processedResponse = _this.client.processResponse(resp, runner);
  _this.builder.emit('query-response', processedResponse, (0, _assign3.default)({ __knexUid: _this.connection.__knexUid }, obj),
_this.builder);
  _this.client.emit('query-response', processedResponse, (0, _assign3.default)({ __knexUid: _this.connection.__knexUid }, obj),
_this.builder);
  return processedResponse;
...
```

#### <a name="apidoc.element.knex.raw.prototype.toQuery"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>toQuery (tz)](#apidoc.element.knex.raw.prototype.toQuery)
- description and source-code
```javascript
toQuery = function (tz) {
  var _this = this;

  var data = this.toSQL(this._method, tz);
  if (!(0, _isArray3.default)(data)) data = [data];
  return (0, _map3.default)(data, function (statement) {
    return _this.client._formatQuery(statement.sql, statement.bindings, tz);
  }).join(';\n');
}
```
- example usage
```shell
...
  this._wrappedAfter = after;
  return this;
},


// Calls 'toString' on the Knex object.
toString: function toString() {
  return this.toQuery();
},


// Returns the raw sql for the query.
toSQL: function toSQL(method, tz) {
  var obj = void 0;
  var formatter = this.client.formatter();
...
```

#### <a name="apidoc.element.knex.raw.prototype.toSQL"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>toSQL (method, tz)](#apidoc.element.knex.raw.prototype.toSQL)
- description and source-code
```javascript
function toSQL(method, tz) {
  var obj = void 0;
  var formatter = this.client.formatter();

  if (Array.isArray(this.bindings)) {
    obj = replaceRawArrBindings(this, formatter);
  } else if (this.bindings && (0, _isPlainObject3.default)(this.bindings)) {
    obj = replaceKeyBindings(this, formatter);
  } else {
    obj = {
      method: 'raw',
      sql: this.sql,
      bindings: (0, _isUndefined3.default)(this.bindings) ? [] : [this.bindings]
    };
  }

  if (this._wrappedBefore) {
    obj.sql = this._wrappedBefore + obj.sql;
  }
  if (this._wrappedAfter) {
    obj.sql = obj.sql + this._wrappedAfter;
  }

  obj.options = (0, _reduce3.default)(this._options, _assign3.default, {});

  if (this._timeout) {
    obj.timeout = this._timeout;
    if (this._cancelOnTimeout) {
      obj.cancelOnTimeout = this._cancelOnTimeout;
    }
  }

  obj.bindings = obj.bindings || [];
  if (helpers.containsUndefined(obj.bindings)) {
    debugBindings(obj.bindings);
    throw new Error('Undefined binding(s) detected when compiling RAW query: ' + obj.sql);
  }

  obj.__knexQueryUid = _uuid2.default.v4();

  return obj;
}
```
- example usage
```shell
...
  }
  return this.unwrapRaw(value, true) || '?';
};

Formatter.prototype.unwrapRaw = function unwrapRaw(value, isParameter) {
  var query = void 0;
  if (value instanceof _builder2.default) {
    query = this.client.queryCompiler(value).toSQL();
    if (query.bindings) {
      this.bindings = this.bindings.concat(query.bindings);
    }
    return this.outputQuery(query, isParameter);
  }
  if (value instanceof _raw2.default) {
    value.client = this.client;
...
```

#### <a name="apidoc.element.knex.raw.prototype.toString"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>toString ()](#apidoc.element.knex.raw.prototype.toString)
- description and source-code
```javascript
function toString() {
  return this.toQuery();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.raw.prototype.transacting"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>transacting (t)](#apidoc.element.knex.raw.prototype.transacting)
- description and source-code
```javascript
transacting = function (t) {
  if (t && t.client) {
    if (!t.client.transacting) {
      helpers.warn('Invalid transaction value: ' + t.client);
    } else {
      this.client = t.client;
    }
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.raw.prototype.wrap"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>wrap (before, after)](#apidoc.element.knex.raw.prototype.wrap)
- description and source-code
```javascript
function wrap(before, after) {
  this._wrappedBefore = before;
  this._wrappedAfter = after;
  return this;
}
```
- example usage
```shell
...

Formatter.prototype.columnize = function columnize(target) {
  var columns = typeof target === 'string' ? [target] : target;
  var str = '',
      i = -1;
  while (++i < columns.length) {
    if (i > 0) str += ', ';
    str += this.wrap(columns[i]);
  }
  return str;
};

// Turns a list of values into a list of ?'s, joining them with commas unless
// a "joining" value is specified (e.g. ' and ')
...
```

#### <a name="apidoc.element.knex.raw.prototype.yield"></a>[function <span class="apidocSignatureSpan">knex.raw.prototype.</span>yield ()](#apidoc.element.knex.raw.prototype.yield)
- description and source-code
```javascript
yield = function () {
  var promise = this.then();
  return promise[method].apply(promise, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.knex.runner"></a>[module knex.runner](#apidoc.module.knex.runner)

#### <a name="apidoc.element.knex.runner.runner"></a>[function <span class="apidocSignatureSpan">knex.</span>runner (client, builder)](#apidoc.element.knex.runner.runner)
- description and source-code
```javascript
function Runner(client, builder) {
  this.client = client;
  this.builder = builder;
  this.queries = [];

  // The "connection" object is set on the runner when
  // "run" is called.
  this.connection = void 0;
}
```
- example usage
```shell
...
  return (0, _map3.default)(data, function (statement) {
    return _this.client._formatQuery(statement.sql, statement.bindings, tz);
  }).join(';\n');
};

// Create a new instance of the 'Runner', passing in the current object.
Target.prototype.then = function () /* onFulfilled, onRejected */{
  var result = this.client.runner(this).run();
  return result.then.apply(result, arguments);
};

// Add additional "options" to the builder. Typically used for client specific
// items, like the 'mysql' and 'sqlite3' drivers.
Target.prototype.options = function (opts) {
  this._options = this._options || [];
...
```



# <a name="apidoc.module.knex.runner.prototype"></a>[module knex.runner.prototype](#apidoc.module.knex.runner.prototype)

#### <a name="apidoc.element.knex.runner.prototype.ensureConnection"></a>[function <span class="apidocSignatureSpan">knex.runner.prototype.</span>ensureConnection ()](#apidoc.element.knex.runner.prototype.ensureConnection)
- description and source-code
```javascript
function ensureConnection() {
  var _this2 = this;

  return _bluebird2.default.try(function () {
    return _this2.connection || new _bluebird2.default(function (resolver, rejecter) {
      // need to return promise or null from handler to prevent warning from bluebird
      return _this2.client.acquireConnection().then(resolver).catch(_bluebird2.default.TimeoutError, function (error) {
        if (_this2.builder) {
          error.sql = _this2.builder.sql;
          error.bindings = _this2.builder.bindings;
        }
        throw error;
      }).catch(rejecter);
    });
  }).disposer(function () {
    // need to return promise or null from handler to prevent warning from bluebird
    return _this2.client.releaseConnection(_this2.connection);
  });
}
```
- example usage
```shell
...
(0, _assign3.default)(Runner.prototype, {

  // "Run" the target, calling "toSQL" on the builder, returning
  // an object or array of queries to run, each of which are run on
  // a single connection.
  run: function run() {
    var runner = this;
    return _bluebird2.default.using(this.ensureConnection(), function (connection) {
runner.connection = connection;

runner.client.emit('start', runner.builder);
runner.builder.emit('start', runner.builder);
var sql = runner.builder.toSQL();

if (runner.builder._debug) {
...
```

#### <a name="apidoc.element.knex.runner.prototype.pipe"></a>[function <span class="apidocSignatureSpan">knex.runner.prototype.</span>pipe (writable, options)](#apidoc.element.knex.runner.prototype.pipe)
- description and source-code
```javascript
function pipe(writable, options) {
  return this.stream(options).pipe(writable);
}
```
- example usage
```shell
...
// Initializes a stream.
Target.prototype.stream = function (options) {
  return this.client.runner(this).stream(options);
};

// Initialize a stream & pipe automatically.
Target.prototype.pipe = function (writable, options) {
  return this.client.runner(this).pipe(writable, options);
};

// Creates a method which "coerces" to a promise, by calling a
// "then" method on the current 'Target'
(0, _each3.default)(['bind', 'catch', 'finally', 'asCallback', 'spread', 'map', 'reduce', 'tap', 'thenReturn', 'return', 'yield', '
ensure', 'reflect', 'get', 'mapSeries', 'delay'], function (method) {
  Target.prototype[method] = function () {
    var promise = this.then();
...
```

#### <a name="apidoc.element.knex.runner.prototype.query"></a>[function <span class="apidocSignatureSpan">knex.runner.prototype.</span>query ()](#apidoc.element.knex.runner.prototype.query)
- description and source-code
```javascript
query = function () {
    var ret = new Promise(INTERNAL);
    ret._captureStackTrace();
    ret._pushContext();
    var value = tryCatch(fn).apply(this, arguments);
    var promiseCreated = ret._popContext();
    debug.checkForgottenReturns(
        value, promiseCreated, "Promise.method", ret);
    ret._resolveFromSyncValue(value);
    return ret;
}
```
- example usage
```shell
...
  if (runner.builder._debug) {
    helpers.debugLog(sql);
  }

  if ((0, _isArray3.default)(sql)) {
    return runner.queryArray(sql);
  }
  return runner.query(sql);
})

// If there are any "error" listeners, we fire an error event
// and then re-throw the error to be eventually handled by
// the promise chain. Useful if you're wrapping in a custom 'Promise'.
.catch(function (err) {
  if (runner.builder._events && runner.builder._events.error) {
...
```

#### <a name="apidoc.element.knex.runner.prototype.queryArray"></a>[function <span class="apidocSignatureSpan">knex.runner.prototype.</span>queryArray (queries)](#apidoc.element.knex.runner.prototype.queryArray)
- description and source-code
```javascript
function queryArray(queries) {
  return queries.length === 1 ? this.query(queries[0]) : _bluebird2.default.bind(this).return(queries).reduce(function (memo, query
) {
    return this.query(query).then(function (resp) {
      memo.push(resp);
      return memo;
    });
  }, []);
}
```
- example usage
```shell
...
  var sql = runner.builder.toSQL();

  if (runner.builder._debug) {
    helpers.debugLog(sql);
  }

  if ((0, _isArray3.default)(sql)) {
    return runner.queryArray(sql);
  }
  return runner.query(sql);
})

// If there are any "error" listeners, we fire an error event
// and then re-throw the error to be eventually handled by
// the promise chain. Useful if you're wrapping in a custom 'Promise'.
...
```

#### <a name="apidoc.element.knex.runner.prototype.run"></a>[function <span class="apidocSignatureSpan">knex.runner.prototype.</span>run ()](#apidoc.element.knex.runner.prototype.run)
- description and source-code
```javascript
function run() {
  var runner = this;
  return _bluebird2.default.using(this.ensureConnection(), function (connection) {
    runner.connection = connection;

    runner.client.emit('start', runner.builder);
    runner.builder.emit('start', runner.builder);
    var sql = runner.builder.toSQL();

    if (runner.builder._debug) {
      helpers.debugLog(sql);
    }

    if ((0, _isArray3.default)(sql)) {
      return runner.queryArray(sql);
    }
    return runner.query(sql);
  })

  // If there are any "error" listeners, we fire an error event
  // and then re-throw the error to be eventually handled by
  // the promise chain. Useful if you're wrapping in a custom 'Promise'.
  .catch(function (err) {
    if (runner.builder._events && runner.builder._events.error) {
      runner.builder.emit('error', err);
    }
    throw err;
  })

  // Fire a single "end" event on the builder when
  // all queries have successfully completed.
  .tap(function () {
    runner.builder.emit('end');
  });
}
```
- example usage
```shell
...
  return (0, _map3.default)(data, function (statement) {
    return _this.client._formatQuery(statement.sql, statement.bindings, tz);
  }).join(';\n');
};

// Create a new instance of the 'Runner', passing in the current object.
Target.prototype.then = function () /* onFulfilled, onRejected */{
  var result = this.client.runner(this).run();
  return result.then.apply(result, arguments);
};

// Add additional "options" to the builder. Typically used for client specific
// items, like the 'mysql' and 'sqlite3' drivers.
Target.prototype.options = function (opts) {
  this._options = this._options || [];
...
```

#### <a name="apidoc.element.knex.runner.prototype.stream"></a>[function <span class="apidocSignatureSpan">knex.runner.prototype.</span>stream (options, handler)](#apidoc.element.knex.runner.prototype.stream)
- description and source-code
```javascript
function stream(options, handler) {

  // If we specify stream(handler).then(...
  if (arguments.length === 1) {
    if (typeof options === 'function') {
      handler = options;
      options = {};
    }
  }

  // Determines whether we emit an error or throw here.
  var hasHandler = typeof handler === 'function';

  // Lazy-load the "PassThrough" dependency.
  PassThrough = PassThrough || require('readable-stream').PassThrough;

  var runner = this;
  var stream = new PassThrough({ objectMode: true });
  var promise = _bluebird2.default.using(this.ensureConnection(), function (connection) {
    runner.connection = connection;
    var sql = runner.builder.toSQL();
    var err = new Error('The stream may only be used with a single query statement.');
    if ((0, _isArray3.default)(sql)) {
      if (hasHandler) throw err;
      stream.emit('error', err);
    }
    return runner.client.stream(runner.connection, sql, stream, options);
  });

  // If a function is passed to handle the stream, send the stream
  // there and return the promise, otherwise just return the stream
  // and the promise will take care of itsself.
  if (hasHandler) {
    handler(stream);
    return promise;
  }

  // This promise is unreachable since no handler was given, so noop any
  // exceptions. Errors should be handled in the stream's 'error' event.
  promise.catch(_noop3.default);
  return stream;
}
```
- example usage
```shell
...
    }
  }
  return this;
};

// Initializes a stream.
Target.prototype.stream = function (options) {
  return this.client.runner(this).stream(options);
};

// Initialize a stream & pipe automatically.
Target.prototype.pipe = function (writable, options) {
  return this.client.runner(this).pipe(writable, options);
};
...
```



# <a name="apidoc.module.knex.transaction"></a>[module knex.transaction](#apidoc.module.knex.transaction)

#### <a name="apidoc.element.knex.transaction.transaction"></a>[function <span class="apidocSignatureSpan">knex.</span>transaction (client, container, config, outerTx)](#apidoc.element.knex.transaction.transaction)
- description and source-code
```javascript
function Transaction(client, container, config, outerTx) {
  (0, _classCallCheck3.default)(this, Transaction);

  var _this = (0, _possibleConstructorReturn3.default)(this, _EventEmitter.call(this));

  var txid = _this.txid = (0, _uniqueId3.default)('trx');

  _this.client = client;
  _this.outerTx = outerTx;
  _this.trxClient = undefined;
  _this._debug = client.config && client.config.debug;

  debug('%s: Starting %s transaction', txid, outerTx ? 'nested' : 'top level');

  _this._promise = _bluebird2.default.using(_this.acquireConnection(client, config, txid), function (connection) {

    var trxClient = _this.trxClient = makeTxClient(_this, client, connection);
    var init = client.transacting ? _this.savepoint(connection) : _this.begin(connection);

    init.then(function () {
      return makeTransactor(_this, connection, trxClient);
    }).then(function (transactor) {
      // If we've returned a "thenable" from the transaction container, assume
      // the rollback and commit are chained to this object's success / failure.
      // Directly thrown errors are treated as automatic rollbacks.
      var result = void 0;
      try {
        result = container(transactor);
      } catch (err) {
        result = _bluebird2.default.reject(err);
      }
      if (result && result.then && typeof result.then === 'function') {
        result.then(function (val) {
          return transactor.commit(val);
        }).catch(function (err) {
          return transactor.rollback(err);
        });
      }
      return null;
    }).catch(function (e) {
      return _this._rejecter(e);
    });

    return new _bluebird2.default(function (resolver, rejecter) {
      _this._resolver = resolver;
      _this._rejecter = rejecter;
    });
  });

  _this._completed = false;

  // If there's a wrapping transaction, we need to wait for any older sibling
  // transactions to settle (commit or rollback) before we can start, and we
  // need to register ourselves with the parent transaction so any younger
  // siblings can wait for us to complete before they can start.
  _this._previousSibling = _bluebird2.default.resolve(true);
  if (outerTx) {
    if (outerTx._lastChild) _this._previousSibling = outerTx._lastChild;
    outerTx._lastChild = _this._promise;
  }
  return _this;
}
```
- example usage
```shell
...

exports.default = Transaction;
function makeTransactor(trx, connection, trxClient) {

var transactor = (0, _makeKnex2.default)(trxClient);

transactor.transaction = function (container, options) {
  return trxClient.transaction(container, options, trx);
};
transactor.savepoint = function (container, options) {
  return transactor.transaction(container, options);
};

if (trx.client.transacting) {
  transactor.commit = function (value) {
...
```



# <a name="apidoc.module.knex.transaction.prototype"></a>[module knex.transaction.prototype](#apidoc.module.knex.transaction.prototype)

#### <a name="apidoc.element.knex.transaction.prototype.acquireConnection"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>acquireConnection (client, config, txid)](#apidoc.element.knex.transaction.prototype.acquireConnection)
- description and source-code
```javascript
function acquireConnection(client, config, txid) {
  var configConnection = config && config.connection;
  return _bluebird2.default.try(function () {
    return configConnection || client.acquireConnection();
  }).disposer(function (connection) {
    if (!configConnection) {
      debug('%s: releasing connection', txid);
      client.releaseConnection(connection);
    } else {
      debug('%s: not releasing external connection', txid);
    }
  });
}
```
- example usage
```shell
...
  // Check whether there's a transaction flag, and that it has a connection.
  ensureConnection: function ensureConnection() {
var _this2 = this;

return _bluebird2.default.try(function () {
  return _this2.connection || new _bluebird2.default(function (resolver, rejecter) {
    // need to return promise or null from handler to prevent warning from bluebird
    return _this2.client.acquireConnection().then(resolver).catch(_bluebird2.default.TimeoutError, function (error) {
      if (_this2.builder) {
        error.sql = _this2.builder.sql;
        error.bindings = _this2.builder.bindings;
      }
      throw error;
    }).catch(rejecter);
  });
...
```

#### <a name="apidoc.element.knex.transaction.prototype.asCallback"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>asCallback ()](#apidoc.element.knex.transaction.prototype.asCallback)
- description and source-code
```javascript
asCallback = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.transaction.prototype.begin"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>begin (conn)](#apidoc.element.knex.transaction.prototype.begin)
- description and source-code
```javascript
function begin(conn) {
  return this.query(conn, 'BEGIN;');
}
```
- example usage
```shell
...
    _this._debug = client.config && client.config.debug;

    debug('%s: Starting %s transaction', txid, outerTx ? 'nested' : 'top level');

    _this._promise = _bluebird2.default.using(_this.acquireConnection(client, config, txid), function (connection) {

var trxClient = _this.trxClient = makeTxClient(_this, client, connection);
var init = client.transacting ? _this.savepoint(connection) : _this.begin(connection);

init.then(function () {
  return makeTransactor(_this, connection, trxClient);
}).then(function (transactor) {
  // If we've returned a "thenable" from the transaction container, assume
  // the rollback and commit are chained to this object's success / failure.
  // Directly thrown errors are treated as automatic rollbacks.
...
```

#### <a name="apidoc.element.knex.transaction.prototype.bind"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>bind ()](#apidoc.element.knex.transaction.prototype.bind)
- description and source-code
```javascript
bind = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
...
    throw error;
  });
}),

// In the case of the "schema builder" we call 'queryArray', which runs each
// of the queries in sequence.
queryArray: function queryArray(queries) {
  return queries.length === 1 ? this.query(queries[0]) : _bluebird2.default.bind(this).return(queries).reduce(function (memo, query
) {
    return this.query(query).then(function (resp) {
      memo.push(resp);
      return memo;
    });
  }, []);
},
...
```

#### <a name="apidoc.element.knex.transaction.prototype.catch"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>catch ()](#apidoc.element.knex.transaction.prototype.catch)
- description and source-code
```javascript
catch = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
...

// .map over the results
.map(function(row) {
  console.log(row);
})

// Finally, add a .catch handler for the promise chain
.catch(function(e) {
  console.error(e);
});
'''
...
```

#### <a name="apidoc.element.knex.transaction.prototype.commit"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>commit (conn, value)](#apidoc.element.knex.transaction.prototype.commit)
- description and source-code
```javascript
function commit(conn, value) {
  return this.query(conn, 'COMMIT;', 1, value);
}
```
- example usage
```shell
...
  try {
    result = container(transactor);
  } catch (err) {
    result = _bluebird2.default.reject(err);
  }
  if (result && result.then && typeof result.then === 'function') {
    result.then(function (val) {
      return transactor.commit(val);
    }).catch(function (err) {
      return transactor.rollback(err);
    });
  }
  return null;
}).catch(function (e) {
  return _this._rejecter(e);
...
```

#### <a name="apidoc.element.knex.transaction.prototype.debug"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>debug (enabled)](#apidoc.element.knex.transaction.prototype.debug)
- description and source-code
```javascript
function debug(enabled) {
  this._debug = arguments.length ? enabled : true;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.transaction.prototype.delay"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>delay ()](#apidoc.element.knex.transaction.prototype.delay)
- description and source-code
```javascript
delay = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.transaction.prototype.ensure"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>ensure ()](#apidoc.element.knex.transaction.prototype.ensure)
- description and source-code
```javascript
ensure = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.transaction.prototype.exec"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>exec ()](#apidoc.element.knex.transaction.prototype.exec)
- description and source-code
```javascript
exec = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.transaction.prototype.finally"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>finally ()](#apidoc.element.knex.transaction.prototype.finally)
- description and source-code
```javascript
finally = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.transaction.prototype.get"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>get ()](#apidoc.element.knex.transaction.prototype.get)
- description and source-code
```javascript
get = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.transaction.prototype.isCompleted"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>isCompleted ()](#apidoc.element.knex.transaction.prototype.isCompleted)
- description and source-code
```javascript
function isCompleted() {
  return this._completed || this.outerTx && this.outerTx.isCompleted() || false;
}
```
- example usage
```shell
...
    if (outerTx._lastChild) _this._previousSibling = outerTx._lastChild;
    outerTx._lastChild = _this._promise;
  }
  return _this;
}

Transaction.prototype.isCompleted = function isCompleted() {
  return this._completed || this.outerTx && this.outerTx.isCompleted() || false;
};

Transaction.prototype.begin = function begin(conn) {
  return this.query(conn, 'BEGIN;');
};

Transaction.prototype.savepoint = function savepoint(conn) {
...
```

#### <a name="apidoc.element.knex.transaction.prototype.map"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>map ()](#apidoc.element.knex.transaction.prototype.map)
- description and source-code
```javascript
map = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
...
.then(function() {
  return knex('users')
    .join('accounts', 'users.id', 'accounts.user_id')
    .select('users.user_name as user', 'accounts.account_name as account');
})

// .map over the results
.map(function(row) {
  console.log(row);
})

// Finally, add a .catch handler for the promise chain
.catch(function(e) {
  console.error(e);
});
...
```

#### <a name="apidoc.element.knex.transaction.prototype.mapSeries"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>mapSeries ()](#apidoc.element.knex.transaction.prototype.mapSeries)
- description and source-code
```javascript
mapSeries = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.transaction.prototype.query"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>query (conn, sql, status, value)](#apidoc.element.knex.transaction.prototype.query)
- description and source-code
```javascript
function query(conn, sql, status, value) {
  var _this4 = this;

  var q = this.trxClient.query(conn, sql).catch(function (err) {
    status = 2;
    value = err;
    _this4._completed = true;
    debug('%s error running transaction query', _this4.txid);
  }).tap(function () {
    if (status === 1) {
      _this4._resolver(value);
    }
    if (status === 2) {
      if ((0, _isUndefined3.default)(value)) {
        value = new Error('Transaction rejected with non-error: ' + value);
      }
      _this4._rejecter(value);
    }
  });
  if (status === 1 || status === 2) {
    this._completed = true;
  }
  return q;
}
```
- example usage
```shell
...
  if (runner.builder._debug) {
    helpers.debugLog(sql);
  }

  if ((0, _isArray3.default)(sql)) {
    return runner.queryArray(sql);
  }
  return runner.query(sql);
})

// If there are any "error" listeners, we fire an error event
// and then re-throw the error to be eventually handled by
// the promise chain. Useful if you're wrapping in a custom 'Promise'.
.catch(function (err) {
  if (runner.builder._events && runner.builder._events.error) {
...
```

#### <a name="apidoc.element.knex.transaction.prototype.reduce"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>reduce ()](#apidoc.element.knex.transaction.prototype.reduce)
- description and source-code
```javascript
reduce = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
...
    throw error;
  });
}),

// In the case of the "schema builder" we call 'queryArray', which runs each
// of the queries in sequence.
queryArray: function queryArray(queries) {
  return queries.length === 1 ? this.query(queries[0]) : _bluebird2.default.bind(this).return(queries).reduce(function (memo, query
) {
    return this.query(query).then(function (resp) {
      memo.push(resp);
      return memo;
    });
  }, []);
},
...
```

#### <a name="apidoc.element.knex.transaction.prototype.reflect"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>reflect ()](#apidoc.element.knex.transaction.prototype.reflect)
- description and source-code
```javascript
reflect = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.transaction.prototype.release"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>release (conn, value)](#apidoc.element.knex.transaction.prototype.release)
- description and source-code
```javascript
function release(conn, value) {
  return this.query(conn, 'RELEASE SAVEPOINT ' + this.txid + ';', 1, value);
}
```
- example usage
```shell
...
};
transactor.savepoint = function (container, options) {
  return transactor.transaction(container, options);
};

if (trx.client.transacting) {
  transactor.commit = function (value) {
    return trx.release(connection, value);
  };
  transactor.rollback = function (error) {
    return trx.rollbackTo(connection, error);
  };
} else {
  transactor.commit = function (value) {
    return trx.commit(connection, value);
...
```

#### <a name="apidoc.element.knex.transaction.prototype.return"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>return ()](#apidoc.element.knex.transaction.prototype.return)
- description and source-code
```javascript
return = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
...
    throw error;
  });
}),

// In the case of the "schema builder" we call 'queryArray', which runs each
// of the queries in sequence.
queryArray: function queryArray(queries) {
  return queries.length === 1 ? this.query(queries[0]) : _bluebird2.default.bind(this).return(queries).reduce(function (memo, query
) {
    return this.query(query).then(function (resp) {
      memo.push(resp);
      return memo;
    });
  }, []);
},
...
```

#### <a name="apidoc.element.knex.transaction.prototype.rollback"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>rollback (conn, error)](#apidoc.element.knex.transaction.prototype.rollback)
- description and source-code
```javascript
function rollback(conn, error) {
  var _this2 = this;

  return this.query(conn, 'ROLLBACK;', 2, error).timeout(5000).catch(_bluebird2.default.TimeoutError, function () {
    _this2._resolver();
  });
}
```
- example usage
```shell
...
  } catch (err) {
    result = _bluebird2.default.reject(err);
  }
  if (result && result.then && typeof result.then === 'function') {
    result.then(function (val) {
      return transactor.commit(val);
    }).catch(function (err) {
      return transactor.rollback(err);
    });
  }
  return null;
}).catch(function (e) {
  return _this._rejecter(e);
});
...
```

#### <a name="apidoc.element.knex.transaction.prototype.rollbackTo"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>rollbackTo (conn, error)](#apidoc.element.knex.transaction.prototype.rollbackTo)
- description and source-code
```javascript
function rollbackTo(conn, error) {
  var _this3 = this;

  return this.query(conn, 'ROLLBACK TO SAVEPOINT ' + this.txid, 2, error).timeout(5000).catch(_bluebird2.default.TimeoutError, function
 () {
    _this3._resolver();
  });
}
```
- example usage
```shell
...
};

if (trx.client.transacting) {
  transactor.commit = function (value) {
    return trx.release(connection, value);
  };
  transactor.rollback = function (error) {
    return trx.rollbackTo(connection, error);
  };
} else {
  transactor.commit = function (value) {
    return trx.commit(connection, value);
  };
  transactor.rollback = function (error) {
    return trx.rollback(connection, error);
...
```

#### <a name="apidoc.element.knex.transaction.prototype.savepoint"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>savepoint (conn)](#apidoc.element.knex.transaction.prototype.savepoint)
- description and source-code
```javascript
function savepoint(conn) {
  return this.query(conn, 'SAVEPOINT ' + this.txid + ';');
}
```
- example usage
```shell
...
    _this._debug = client.config && client.config.debug;

    debug('%s: Starting %s transaction', txid, outerTx ? 'nested' : 'top level');

    _this._promise = _bluebird2.default.using(_this.acquireConnection(client, config, txid), function (connection) {

var trxClient = _this.trxClient = makeTxClient(_this, client, connection);
var init = client.transacting ? _this.savepoint(connection) : _this.begin(connection);

init.then(function () {
  return makeTransactor(_this, connection, trxClient);
}).then(function (transactor) {
  // If we've returned a "thenable" from the transaction container, assume
  // the rollback and commit are chained to this object's success / failure.
  // Directly thrown errors are treated as automatic rollbacks.
...
```

#### <a name="apidoc.element.knex.transaction.prototype.spread"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>spread ()](#apidoc.element.knex.transaction.prototype.spread)
- description and source-code
```javascript
spread = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.transaction.prototype.tap"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>tap ()](#apidoc.element.knex.transaction.prototype.tap)
- description and source-code
```javascript
tap = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
...
      runner.builder.emit('error', err);
    }
    throw err;
  })

  // Fire a single "end" event on the builder when
  // all queries have successfully completed.
  .tap(function () {
    runner.builder.emit('end');
  });
},


// Stream the result set, by passing through to the dialect's streaming
// capabilities. If the options are
...
```

#### <a name="apidoc.element.knex.transaction.prototype.then"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>then ()](#apidoc.element.knex.transaction.prototype.then)
- description and source-code
```javascript
then = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
...
.createTable('accounts', function(table) {
  table.increments('id');
  table.string('account_name');
  table.integer('user_id').unsigned().references('users.id');
})

// Then query the table...
.then(function() {
  return knex.insert({user_name: 'Tim'}).into('users');
})

// ...and using the insert id, insert into the other table.
.then(function(rows) {
  return knex.table('accounts').insert({account_name: 'knex', user_id: rows[0]});
})
...
```

#### <a name="apidoc.element.knex.transaction.prototype.thenReturn"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>thenReturn ()](#apidoc.element.knex.transaction.prototype.thenReturn)
- description and source-code
```javascript
thenReturn = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.knex.transaction.prototype.yield"></a>[function <span class="apidocSignatureSpan">knex.transaction.prototype.</span>yield ()](#apidoc.element.knex.transaction.prototype.yield)
- description and source-code
```javascript
yield = function () {
  return this._promise = this._promise[method].apply(this._promise, arguments);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
