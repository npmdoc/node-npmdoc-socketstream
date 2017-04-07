# api documentation for  [socketstream (v0.5.3)](http://www.socketstream.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-socketstream.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-socketstream) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-socketstream.svg)](https://travis-ci.org/npmdoc/node-npmdoc-socketstream)
#### A framework for Realtime Web Apps

[![NPM](https://nodei.co/npm/socketstream.png?downloads=true)](https://www.npmjs.com/package/socketstream)

[![apidoc](https://npmdoc.github.io/node-npmdoc-socketstream/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-socketstream_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-socketstream/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-socketstream/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-socketstream/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Henrik Vendelbo",
        "email": "henrik@socketstream.org"
    },
    "bin": {
        "socketstream": "./bin/socketstream"
    },
    "bugs": {
        "url": "https://github.com/socketstream/socketstream/issues"
    },
    "contributors": [
        {
            "name": "Owen Barnes"
        },
        {
            "name": "Paul Jensen"
        },
        {
            "name": "Alan Milford"
        },
        {
            "name": "Addy Osmani"
        },
        {
            "name": "nponeccop"
        },
        {
            "name": "Gilbert B Garza"
        },
        {
            "name": "Craig Jordan Muir"
        },
        {
            "name": "David Rosen"
        },
        {
            "name": "Michael Lawson"
        }
    ],
    "dependencies": {
        "apitree": "1.2.0",
        "async": "1.4.2",
        "clean-css": "3.3.9",
        "colors": "1.1.2",
        "connect-redis": "2.4.1",
        "cookie": "^0.2.2",
        "csurf": "1.8.3",
        "debug": "~2.2.0",
        "eventemitter2": "0.4.14",
        "findup-sync": "^0.3.0",
        "glob": "5.0.14",
        "micromatch": "2.2.0",
        "orchestrator": "0.3.7",
        "parseurl": "1.3.0",
        "redis": "0.12.1",
        "resolve": "~1.1.6",
        "send": "0.13.0",
        "shortid": "2.2.2",
        "uglify-js": "2.4.24",
        "utils-merge": "1.0.0",
        "uuid": "2.0.1"
    },
    "description": "A framework for Realtime Web Apps",
    "devDependencies": {
        "chai": "^3.3.0",
        "chokidar": "~1.1.0",
        "commander": "2.8.1",
        "connect-livereload": "~0.5.2",
        "conventional-changelog": "^0.4.3",
        "cookie-parser": "^1.4.0",
        "coveralls": "~2.11.4",
        "dgeni": "^0.4.1",
        "express-session": "^1.11.3",
        "fs-extra": "~0.24.0",
        "gently": "~0.10.0",
        "grunt": "0.4.5",
        "grunt-cli": "0.1.13",
        "grunt-concurrent": "~2.0.3",
        "grunt-contrib-clean": "~0.6.0",
        "grunt-contrib-connect": "~0.11.2",
        "grunt-contrib-watch": "~0.6.1",
        "grunt-conventional-changelog": "~4.1.0",
        "grunt-ngdocs": "~0.2.9",
        "istanbul": "~0.3.18",
        "jshint": "~2.8.0",
        "lolex": "^1.3.1",
        "mocha": "~2.3.3",
        "notes": "0.0.4",
        "npm-dview": "~2.0.0",
        "pre-commit": "~1.1.1",
        "semver": "~5.0.3",
        "shelljs": "~0.5.3",
        "should": "~7.1.0",
        "sinon": "~1.17.0",
        "sinon-chai": "^2.8.0",
        "supertest": "~1.1.0",
        "vinyl-fs": "~2.0.0"
    },
    "directories": {
        "lib": "./lib",
        "doc": "./doc"
    },
    "dist": {
        "shasum": "ebefad1746fe95025181680cfa91c0375a506165",
        "tarball": "https://registry.npmjs.org/socketstream/-/socketstream-0.5.3.tgz"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "gitHead": "5c80a49e1e5239fc382026fd29166525e71b7e0d",
    "homepage": "http://www.socketstream.org",
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "socketstream",
            "email": "info@socketstream.org"
        },
        {
            "name": "paulbjensen",
            "email": "paulbjensen@gmail.com"
        },
        {
            "name": "thepian",
            "email": "henrik@thepia.com"
        }
    ],
    "name": "socketstream",
    "optionalDependencies": {},
    "pre-commit": [
        "lint",
        "quick-test"
    ],
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/socketstream/socketstream.git"
    },
    "scripts": {
        "build-docs": "dgeni ./src/docs",
        "changelog": "conventional-changelog  -p angular -i CHANGELOG.md -w",
        "checkDependencies": "npm-dview",
        "cover-test": "istanbul cover -x **/new_project/** node_modules/.bin/_mocha test/unit/**/* && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "lint": "jshint .",
        "notes": "notes",
        "quick-test": "mocha test/unit/**/* --reporter progress",
        "test": "mocha test/unit/**/* --reporter spec",
        "test-debug": "mocha --debug-brk test/unit/**/* --reporter spec"
    },
    "version": "0.5.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module socketstream](#apidoc.module.socketstream)
1.  [function <span class="apidocSignatureSpan">socketstream.</span>api.require (id, contextPath, defaultId)](#apidoc.element.socketstream.api.require)
1.  [function <span class="apidocSignatureSpan">socketstream.</span>session.Cookie (options)](#apidoc.element.socketstream.session.Cookie)
1.  [function <span class="apidocSignatureSpan">socketstream.</span>session.MemoryStore ()](#apidoc.element.socketstream.session.MemoryStore)
1.  [function <span class="apidocSignatureSpan">socketstream.</span>session.Session (req, data)](#apidoc.element.socketstream.session.Session)
1.  [function <span class="apidocSignatureSpan">socketstream.</span>session.Store ()](#apidoc.element.socketstream.session.Store)
1.  [function <span class="apidocSignatureSpan">socketstream.</span>set (where, what)](#apidoc.element.socketstream.set)
1.  [function <span class="apidocSignatureSpan">socketstream.</span>start ()](#apidoc.element.socketstream.start)
1.  [function <span class="apidocSignatureSpan">socketstream.</span>task (name, dependents, fn)](#apidoc.element.socketstream.task)
1.  object <span class="apidocSignatureSpan">socketstream.</span>api
1.  object <span class="apidocSignatureSpan">socketstream.</span>api.bundler
1.  object <span class="apidocSignatureSpan">socketstream.</span>api.client
1.  object <span class="apidocSignatureSpan">socketstream.</span>api.log
1.  object <span class="apidocSignatureSpan">socketstream.</span>client
1.  object <span class="apidocSignatureSpan">socketstream.</span>client.assets
1.  object <span class="apidocSignatureSpan">socketstream.</span>client.formatters
1.  object <span class="apidocSignatureSpan">socketstream.</span>client.templateEngine
1.  object <span class="apidocSignatureSpan">socketstream.</span>events
1.  object <span class="apidocSignatureSpan">socketstream.</span>http
1.  object <span class="apidocSignatureSpan">socketstream.</span>http.cached
1.  object <span class="apidocSignatureSpan">socketstream.</span>http.session
1.  object <span class="apidocSignatureSpan">socketstream.</span>livereload
1.  object <span class="apidocSignatureSpan">socketstream.</span>publish
1.  object <span class="apidocSignatureSpan">socketstream.</span>publish.transport
1.  object <span class="apidocSignatureSpan">socketstream.</span>responders
1.  object <span class="apidocSignatureSpan">socketstream.</span>session
1.  object <span class="apidocSignatureSpan">socketstream.</span>session.Cookie.prototype
1.  object <span class="apidocSignatureSpan">socketstream.</span>session.MemoryStore.prototype
1.  object <span class="apidocSignatureSpan">socketstream.</span>session.Session.prototype
1.  object <span class="apidocSignatureSpan">socketstream.</span>session.Store.prototype
1.  object <span class="apidocSignatureSpan">socketstream.</span>session.store
1.  object <span class="apidocSignatureSpan">socketstream.</span>tasks
1.  object <span class="apidocSignatureSpan">socketstream.</span>ws
1.  object <span class="apidocSignatureSpan">socketstream.</span>ws.transport
1.  string <span class="apidocSignatureSpan">socketstream.</span>env
1.  string <span class="apidocSignatureSpan">socketstream.</span>root
1.  string <span class="apidocSignatureSpan">socketstream.</span>version

#### [module socketstream.api](#apidoc.module.socketstream.api)
1.  [function <span class="apidocSignatureSpan">socketstream.api.</span>add (name, fn)](#apidoc.element.socketstream.api.add)
1.  [function <span class="apidocSignatureSpan">socketstream.api.</span>defaultTask (name, dependents, fn)](#apidoc.element.socketstream.api.defaultTask)
1.  [function <span class="apidocSignatureSpan">socketstream.api.</span>load ()](#apidoc.element.socketstream.api.load)
1.  [function <span class="apidocSignatureSpan">socketstream.api.</span>require (id, contextPath, defaultId)](#apidoc.element.socketstream.api.require)
1.  [function <span class="apidocSignatureSpan">socketstream.api.</span>task (name, dependents, fn)](#apidoc.element.socketstream.api.task)
1.  [function <span class="apidocSignatureSpan">socketstream.api.</span>unload ()](#apidoc.element.socketstream.api.unload)
1.  object <span class="apidocSignatureSpan">socketstream.api.</span>bundler
1.  object <span class="apidocSignatureSpan">socketstream.api.</span>client
1.  object <span class="apidocSignatureSpan">socketstream.api.</span>events
1.  object <span class="apidocSignatureSpan">socketstream.api.</span>http
1.  object <span class="apidocSignatureSpan">socketstream.api.</span>livereload
1.  object <span class="apidocSignatureSpan">socketstream.api.</span>log
1.  object <span class="apidocSignatureSpan">socketstream.api.</span>server
1.  object <span class="apidocSignatureSpan">socketstream.api.</span>session
1.  string <span class="apidocSignatureSpan">socketstream.api.</span>env
1.  string <span class="apidocSignatureSpan">socketstream.api.</span>root
1.  string <span class="apidocSignatureSpan">socketstream.api.</span>version

#### [module socketstream.api.bundler](#apidoc.module.socketstream.api.bundler)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>browserifyLoader ()](#apidoc.element.socketstream.api.bundler.browserifyLoader)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>clientFilePath (rel)](#apidoc.element.socketstream.api.bundler.clientFilePath)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>constants (client)](#apidoc.element.socketstream.api.bundler.constants)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>create (bundler)](#apidoc.element.socketstream.api.bundler.create)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>define (client, args)](#apidoc.element.socketstream.api.bundler.define)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>destsFor (client)](#apidoc.element.socketstream.api.bundler.destsFor)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>entries (client, assetType)](#apidoc.element.socketstream.api.bundler.entries)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>entryFor (bundle, file, part2)](#apidoc.element.socketstream.api.bundler.entryFor)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>findEntryPoint (client)](#apidoc.element.socketstream.api.bundler.findEntryPoint)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>forEach (fn, that)](#apidoc.element.socketstream.api.bundler.forEach)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>forget ()](#apidoc.element.socketstream.api.bundler.forget)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>formatKb (size)](#apidoc.element.socketstream.api.bundler.formatKb)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>get (client)](#apidoc.element.socketstream.api.bundler.get)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>injectTailIfNeeded (output, opts)](#apidoc.element.socketstream.api.bundler.injectTailIfNeeded)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>load ()](#apidoc.element.socketstream.api.bundler.load)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>loadFile (entry, opts, formatter, cb, errCb)](#apidoc.element.socketstream.api.bundler.loadFile)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>minifyCSS (files)](#apidoc.element.socketstream.api.bundler.minifyCSS)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>minifyJS (files)](#apidoc.element.socketstream.api.bundler.minifyJS)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>minifyJSFile (originalCode, fileName)](#apidoc.element.socketstream.api.bundler.minifyJSFile)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>packAssetSet (assetType, client, postProcess, done)](#apidoc.element.socketstream.api.bundler.packAssetSet)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>sourcePaths (paths)](#apidoc.element.socketstream.api.bundler.sourcePaths)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>startCode (client)](#apidoc.element.socketstream.api.bundler.startCode)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>systemLibs ()](#apidoc.element.socketstream.api.bundler.systemLibs)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>systemModule (name, wrap)](#apidoc.element.socketstream.api.bundler.systemModule)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>systemModules (wrap)](#apidoc.element.socketstream.api.bundler.systemModules)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>unload ()](#apidoc.element.socketstream.api.bundler.unload)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>updateCachedOndemandAssets ()](#apidoc.element.socketstream.api.bundler.updateCachedOndemandAssets)
1.  [function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>wrapModule (modPath, code)](#apidoc.element.socketstream.api.bundler.wrapModule)

#### [module socketstream.api.client](#apidoc.module.socketstream.api.client)
1.  [function <span class="apidocSignatureSpan">socketstream.api.client.</span>send (type, name, content, options)](#apidoc.element.socketstream.api.client.send)
1.  object <span class="apidocSignatureSpan">socketstream.api.client.</span>dirs

#### [module socketstream.api.log](#apidoc.module.socketstream.api.log)
1.  [function <span class="apidocSignatureSpan">socketstream.api.log.</span>clientIssue (client, options, err, more)](#apidoc.element.socketstream.api.log.clientIssue)
1.  [function <span class="apidocSignatureSpan">socketstream.api.log.</span>debug ()](#apidoc.element.socketstream.api.log.debug)
1.  [function <span class="apidocSignatureSpan">socketstream.api.log.</span>error ()](#apidoc.element.socketstream.api.log.error)
1.  [function <span class="apidocSignatureSpan">socketstream.api.log.</span>info ()](#apidoc.element.socketstream.api.log.info)
1.  [function <span class="apidocSignatureSpan">socketstream.api.log.</span>trace ()](#apidoc.element.socketstream.api.log.trace)
1.  [function <span class="apidocSignatureSpan">socketstream.api.log.</span>warn ()](#apidoc.element.socketstream.api.log.warn)

#### [module socketstream.api.require](#apidoc.module.socketstream.api.require)
1.  [function <span class="apidocSignatureSpan">socketstream.api.</span>require (id, contextPath, defaultId)](#apidoc.element.socketstream.api.require.require)
1.  [function <span class="apidocSignatureSpan">socketstream.api.require.</span>forEach (pattern, fn)](#apidoc.element.socketstream.api.require.forEach)
1.  [function <span class="apidocSignatureSpan">socketstream.api.require.</span>resolve (id)](#apidoc.element.socketstream.api.require.resolve)

#### [module socketstream.client](#apidoc.module.socketstream.client)
1.  [function <span class="apidocSignatureSpan">socketstream.client.</span>define (name)](#apidoc.element.socketstream.client.define)
1.  [function <span class="apidocSignatureSpan">socketstream.client.</span>forget ()](#apidoc.element.socketstream.client.forget)
1.  [function <span class="apidocSignatureSpan">socketstream.client.</span>init ()](#apidoc.element.socketstream.client.init)
1.  [function <span class="apidocSignatureSpan">socketstream.client.</span>load ()](#apidoc.element.socketstream.client.load)
1.  [function <span class="apidocSignatureSpan">socketstream.client.</span>packAssets (opts)](#apidoc.element.socketstream.client.packAssets)
1.  [function <span class="apidocSignatureSpan">socketstream.client.</span>reloadCached ()](#apidoc.element.socketstream.client.reloadCached)
1.  [function <span class="apidocSignatureSpan">socketstream.client.</span>reloadClients (changedPath, event)](#apidoc.element.socketstream.client.reloadClients)
1.  [function <span class="apidocSignatureSpan">socketstream.client.</span>servePacked (opts)](#apidoc.element.socketstream.client.servePacked)
1.  [function <span class="apidocSignatureSpan">socketstream.client.</span>set (newOption)](#apidoc.element.socketstream.client.set)
1.  [function <span class="apidocSignatureSpan">socketstream.client.</span>task (client, name, dependents, fn)](#apidoc.element.socketstream.client.task)
1.  [function <span class="apidocSignatureSpan">socketstream.client.</span>unload ()](#apidoc.element.socketstream.client.unload)
1.  object <span class="apidocSignatureSpan">socketstream.client.</span>assets
1.  object <span class="apidocSignatureSpan">socketstream.client.</span>dirs
1.  object <span class="apidocSignatureSpan">socketstream.client.</span>formatters
1.  object <span class="apidocSignatureSpan">socketstream.client.</span>livereload
1.  object <span class="apidocSignatureSpan">socketstream.client.</span>options
1.  object <span class="apidocSignatureSpan">socketstream.client.</span>plugins
1.  object <span class="apidocSignatureSpan">socketstream.client.</span>templateEngine
1.  string <span class="apidocSignatureSpan">socketstream.client.</span>faviconPath

#### [module socketstream.client.assets](#apidoc.module.socketstream.client.assets)
1.  [function <span class="apidocSignatureSpan">socketstream.client.assets.</span>load ()](#apidoc.element.socketstream.client.assets.load)
1.  [function <span class="apidocSignatureSpan">socketstream.client.assets.</span>send (type, name, content, options)](#apidoc.element.socketstream.client.assets.send)
1.  [function <span class="apidocSignatureSpan">socketstream.client.assets.</span>unload ()](#apidoc.element.socketstream.client.assets.unload)
1.  object <span class="apidocSignatureSpan">socketstream.client.</span>assets

#### [module socketstream.client.formatters](#apidoc.module.socketstream.client.formatters)
1.  [function <span class="apidocSignatureSpan">socketstream.client.formatters.</span>add (nameOrModule, config)](#apidoc.element.socketstream.client.formatters.add)
1.  [function <span class="apidocSignatureSpan">socketstream.client.formatters.</span>forget ()](#apidoc.element.socketstream.client.formatters.forget)
1.  [function <span class="apidocSignatureSpan">socketstream.client.formatters.</span>load ()](#apidoc.element.socketstream.client.formatters.load)

#### [module socketstream.client.templateEngine](#apidoc.module.socketstream.client.templateEngine)
1.  [function <span class="apidocSignatureSpan">socketstream.client.templateEngine.</span>forget ()](#apidoc.element.socketstream.client.templateEngine.forget)
1.  [function <span class="apidocSignatureSpan">socketstream.client.templateEngine.</span>generate (bundler, files, cb)](#apidoc.element.socketstream.client.templateEngine.generate)
1.  [function <span class="apidocSignatureSpan">socketstream.client.templateEngine.</span>load ()](#apidoc.element.socketstream.client.templateEngine.load)
1.  [function <span class="apidocSignatureSpan">socketstream.client.templateEngine.</span>use (nameOrModule, dirs, config)](#apidoc.element.socketstream.client.templateEngine.use)

#### [module socketstream.http](#apidoc.module.socketstream.http)
1.  [function <span class="apidocSignatureSpan">socketstream.http.</span>load ()](#apidoc.element.socketstream.http.load)
1.  [function <span class="apidocSignatureSpan">socketstream.http.</span>route (url, fn)](#apidoc.element.socketstream.http.route)
1.  [function <span class="apidocSignatureSpan">socketstream.http.</span>set (newSettings)](#apidoc.element.socketstream.http.set)
1.  [function <span class="apidocSignatureSpan">socketstream.http.</span>unload ()](#apidoc.element.socketstream.http.unload)
1.  object <span class="apidocSignatureSpan">socketstream.http.</span>cached
1.  object <span class="apidocSignatureSpan">socketstream.http.</span>session
1.  object <span class="apidocSignatureSpan">socketstream.http.</span>settings

#### [module socketstream.http.cached](#apidoc.module.socketstream.http.cached)
1.  [function <span class="apidocSignatureSpan">socketstream.http.cached.</span>loadAssets ()](#apidoc.element.socketstream.http.cached.loadAssets)
1.  [function <span class="apidocSignatureSpan">socketstream.http.cached.</span>loadStatic ()](#apidoc.element.socketstream.http.cached.loadStatic)
1.  [function <span class="apidocSignatureSpan">socketstream.http.cached.</span>middleware (req, res, next)](#apidoc.element.socketstream.http.cached.middleware)
1.  [function <span class="apidocSignatureSpan">socketstream.http.cached.</span>route (url, fn, filePath)](#apidoc.element.socketstream.http.cached.route)
1.  [function <span class="apidocSignatureSpan">socketstream.http.cached.</span>send (url, res)](#apidoc.element.socketstream.http.cached.send)
1.  [function <span class="apidocSignatureSpan">socketstream.http.cached.</span>set (url, content, mimeType)](#apidoc.element.socketstream.http.cached.set)

#### [module socketstream.http.session](#apidoc.module.socketstream.http.session)
1.  [function <span class="apidocSignatureSpan">socketstream.http.session.</span>middleware (req, res, next)](#apidoc.element.socketstream.http.session.middleware)

#### [module socketstream.livereload](#apidoc.module.socketstream.livereload)
1.  [function <span class="apidocSignatureSpan">socketstream.livereload.</span>added (changedPath)](#apidoc.element.socketstream.livereload.added)
1.  [function <span class="apidocSignatureSpan">socketstream.livereload.</span>changed (changedPath)](#apidoc.element.socketstream.livereload.changed)
1.  [function <span class="apidocSignatureSpan">socketstream.livereload.</span>removed (changedPath)](#apidoc.element.socketstream.livereload.removed)

#### [module socketstream.publish](#apidoc.module.socketstream.publish)
1.  [function <span class="apidocSignatureSpan">socketstream.publish.</span>api (transport)](#apidoc.element.socketstream.publish.api)
1.  object <span class="apidocSignatureSpan">socketstream.publish.</span>transport

#### [module socketstream.publish.transport](#apidoc.module.socketstream.publish.transport)
1.  [function <span class="apidocSignatureSpan">socketstream.publish.transport.</span>load ()](#apidoc.element.socketstream.publish.transport.load)
1.  [function <span class="apidocSignatureSpan">socketstream.publish.transport.</span>use (nameOrModule, cfg)](#apidoc.element.socketstream.publish.transport.use)

#### [module socketstream.responders](#apidoc.module.socketstream.responders)
1.  [function <span class="apidocSignatureSpan">socketstream.responders.</span>add (nameOrModule, config)](#apidoc.element.socketstream.responders.add)
1.  [function <span class="apidocSignatureSpan">socketstream.responders.</span>clear ()](#apidoc.element.socketstream.responders.clear)
1.  [function <span class="apidocSignatureSpan">socketstream.responders.</span>load ()](#apidoc.element.socketstream.responders.load)

#### [module socketstream.session](#apidoc.module.socketstream.session)
1.  [function <span class="apidocSignatureSpan">socketstream.session.</span>Cookie (options)](#apidoc.element.socketstream.session.Cookie)
1.  [function <span class="apidocSignatureSpan">socketstream.session.</span>MemoryStore ()](#apidoc.element.socketstream.session.MemoryStore)
1.  [function <span class="apidocSignatureSpan">socketstream.session.</span>Session (req, data)](#apidoc.element.socketstream.session.Session)
1.  [function <span class="apidocSignatureSpan">socketstream.session.</span>Store ()](#apidoc.element.socketstream.session.Store)
1.  [function <span class="apidocSignatureSpan">socketstream.session.</span>create ()](#apidoc.element.socketstream.session.create)
1.  [function <span class="apidocSignatureSpan">socketstream.session.</span>extractSocketSessionToken (request)](#apidoc.element.socketstream.session.extractSocketSessionToken)
1.  [function <span class="apidocSignatureSpan">socketstream.session.</span>find (sessionId, socketId, cb)](#apidoc.element.socketstream.session.find)
1.  [function <span class="apidocSignatureSpan">socketstream.session.</span>setStrategy (_strategy)](#apidoc.element.socketstream.session.setStrategy)
1.  object <span class="apidocSignatureSpan">socketstream.session.</span>options
1.  object <span class="apidocSignatureSpan">socketstream.session.</span>store
1.  object <span class="apidocSignatureSpan">socketstream.session.</span>strategy

#### [module socketstream.session.Cookie](#apidoc.module.socketstream.session.Cookie)
1.  [function <span class="apidocSignatureSpan">socketstream.session.</span>Cookie (options)](#apidoc.element.socketstream.session.Cookie.Cookie)

#### [module socketstream.session.Cookie.prototype](#apidoc.module.socketstream.session.Cookie.prototype)
1.  [function <span class="apidocSignatureSpan">socketstream.session.Cookie.prototype.</span>serialize (name, val)](#apidoc.element.socketstream.session.Cookie.prototype.serialize)
1.  [function <span class="apidocSignatureSpan">socketstream.session.Cookie.prototype.</span>toJSON ()](#apidoc.element.socketstream.session.Cookie.prototype.toJSON)
1.  object <span class="apidocSignatureSpan">socketstream.session.Cookie.prototype.</span>data

#### [module socketstream.session.MemoryStore](#apidoc.module.socketstream.session.MemoryStore)
1.  [function <span class="apidocSignatureSpan">socketstream.session.</span>MemoryStore ()](#apidoc.element.socketstream.session.MemoryStore.MemoryStore)

#### [module socketstream.session.MemoryStore.prototype](#apidoc.module.socketstream.session.MemoryStore.prototype)
1.  [function <span class="apidocSignatureSpan">socketstream.session.MemoryStore.prototype.</span>all (callback)](#apidoc.element.socketstream.session.MemoryStore.prototype.all)
1.  [function <span class="apidocSignatureSpan">socketstream.session.MemoryStore.prototype.</span>clear (callback)](#apidoc.element.socketstream.session.MemoryStore.prototype.clear)
1.  [function <span class="apidocSignatureSpan">socketstream.session.MemoryStore.prototype.</span>destroy (sessionId, callback)](#apidoc.element.socketstream.session.MemoryStore.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">socketstream.session.MemoryStore.prototype.</span>get (sessionId, callback)](#apidoc.element.socketstream.session.MemoryStore.prototype.get)
1.  [function <span class="apidocSignatureSpan">socketstream.session.MemoryStore.prototype.</span>length (callback)](#apidoc.element.socketstream.session.MemoryStore.prototype.length)
1.  [function <span class="apidocSignatureSpan">socketstream.session.MemoryStore.prototype.</span>set (sessionId, session, callback)](#apidoc.element.socketstream.session.MemoryStore.prototype.set)
1.  [function <span class="apidocSignatureSpan">socketstream.session.MemoryStore.prototype.</span>touch (sessionId, session, callback)](#apidoc.element.socketstream.session.MemoryStore.prototype.touch)

#### [module socketstream.session.Session](#apidoc.module.socketstream.session.Session)
1.  [function <span class="apidocSignatureSpan">socketstream.session.</span>Session (req, data)](#apidoc.element.socketstream.session.Session.Session)

#### [module socketstream.session.Session.prototype](#apidoc.module.socketstream.session.Session.prototype)
1.  [function <span class="apidocSignatureSpan">socketstream.session.Session.prototype.</span>destroy (fn)](#apidoc.element.socketstream.session.Session.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">socketstream.session.Session.prototype.</span>regenerate (fn)](#apidoc.element.socketstream.session.Session.prototype.regenerate)
1.  [function <span class="apidocSignatureSpan">socketstream.session.Session.prototype.</span>reload (fn)](#apidoc.element.socketstream.session.Session.prototype.reload)
1.  [function <span class="apidocSignatureSpan">socketstream.session.Session.prototype.</span>resetMaxAge ()](#apidoc.element.socketstream.session.Session.prototype.resetMaxAge)
1.  [function <span class="apidocSignatureSpan">socketstream.session.Session.prototype.</span>save (fn)](#apidoc.element.socketstream.session.Session.prototype.save)
1.  [function <span class="apidocSignatureSpan">socketstream.session.Session.prototype.</span>touch ()](#apidoc.element.socketstream.session.Session.prototype.touch)

#### [module socketstream.session.Store](#apidoc.module.socketstream.session.Store)
1.  [function <span class="apidocSignatureSpan">socketstream.session.</span>Store ()](#apidoc.element.socketstream.session.Store.Store)

#### [module socketstream.session.Store.prototype](#apidoc.module.socketstream.session.Store.prototype)
1.  [function <span class="apidocSignatureSpan">socketstream.session.Store.prototype.</span>createSession (req, sess)](#apidoc.element.socketstream.session.Store.prototype.createSession)
1.  [function <span class="apidocSignatureSpan">socketstream.session.Store.prototype.</span>load (sid, fn)](#apidoc.element.socketstream.session.Store.prototype.load)
1.  [function <span class="apidocSignatureSpan">socketstream.session.Store.prototype.</span>regenerate (req, fn)](#apidoc.element.socketstream.session.Store.prototype.regenerate)

#### [module socketstream.session.store](#apidoc.module.socketstream.session.store)
1.  [function <span class="apidocSignatureSpan">socketstream.session.store.</span>get ()](#apidoc.element.socketstream.session.store.get)
1.  [function <span class="apidocSignatureSpan">socketstream.session.store.</span>use (nameOrStore, options)](#apidoc.element.socketstream.session.store.use)

#### [module socketstream.tasks](#apidoc.module.socketstream.tasks)
1.  [function <span class="apidocSignatureSpan">socketstream.tasks.</span>_packTasks (all)](#apidoc.element.socketstream.tasks._packTasks)
1.  [function <span class="apidocSignatureSpan">socketstream.tasks.</span>add (name, dependents, fn)](#apidoc.element.socketstream.tasks.add)
1.  [function <span class="apidocSignatureSpan">socketstream.tasks.</span>defaultTask (name, dependents, fn)](#apidoc.element.socketstream.tasks.defaultTask)
1.  [function <span class="apidocSignatureSpan">socketstream.tasks.</span>defaults ()](#apidoc.element.socketstream.tasks.defaults)
1.  [function <span class="apidocSignatureSpan">socketstream.tasks.</span>forget ()](#apidoc.element.socketstream.tasks.forget)
1.  [function <span class="apidocSignatureSpan">socketstream.tasks.</span>on ()](#apidoc.element.socketstream.tasks.on)
1.  [function <span class="apidocSignatureSpan">socketstream.tasks.</span>plan (args)](#apidoc.element.socketstream.tasks.plan)
1.  [function <span class="apidocSignatureSpan">socketstream.tasks.</span>start (tasks, done)](#apidoc.element.socketstream.tasks.start)
1.  [function <span class="apidocSignatureSpan">socketstream.tasks.</span>unload ()](#apidoc.element.socketstream.tasks.unload)
1.  [function <span class="apidocSignatureSpan">socketstream.tasks.</span>use (gulp)](#apidoc.element.socketstream.tasks.use)
1.  object <span class="apidocSignatureSpan">socketstream.tasks.</span>orchestrator

#### [module socketstream.ws](#apidoc.module.socketstream.ws)
1.  [function <span class="apidocSignatureSpan">socketstream.ws.</span>listen (port, cb)](#apidoc.element.socketstream.ws.listen)
1.  [function <span class="apidocSignatureSpan">socketstream.ws.</span>load (responders, eventTransport)](#apidoc.element.socketstream.ws.load)
1.  [function <span class="apidocSignatureSpan">socketstream.ws.</span>unload ()](#apidoc.element.socketstream.ws.unload)
1.  object <span class="apidocSignatureSpan">socketstream.ws.</span>transport

#### [module socketstream.ws.transport](#apidoc.module.socketstream.ws.transport)
1.  [function <span class="apidocSignatureSpan">socketstream.ws.transport.</span>load ()](#apidoc.element.socketstream.ws.transport.load)
1.  [function <span class="apidocSignatureSpan">socketstream.ws.transport.</span>use (nameOrModule, cfg)](#apidoc.element.socketstream.ws.transport.use)
1.  object <span class="apidocSignatureSpan">socketstream.ws.transport.</span>http
1.  object <span class="apidocSignatureSpan">socketstream.ws.transport.</span>ws



# <a name="apidoc.module.socketstream"></a>[module socketstream](#apidoc.module.socketstream)

#### <a name="apidoc.element.socketstream.api.require"></a>[function <span class="apidocSignatureSpan">socketstream.</span>api.require (id, contextPath, defaultId)](#apidoc.element.socketstream.api.require)
- description and source-code
```javascript
function requires(id, contextPath, defaultId) {
		var context, callback;
		if (typeof defaultId === 'function') {
			callback = defaultId;
			defaultId = null;
		}
		if (contextPath) {
			context = contexts[contextPath];
			if (context === undefined) {
				context = contexts[contextPath] = {
					rel : context,
					prefix: path.join(__dirname, '..', contextPath),
					inContext: function(id) {
						try {
							var p = path.join(context.prefix,id);
							if (require.resolve(p)) { // gives full path
								return require(p);
							}
						} catch(ex) {}
					}
				};
			}
    }

    switch(typeof id) {
      case 'object':
      case 'function':
        if (id) {
          return id; // straight object/function will just resolve straight away
        }
        break;
      case 'string':
        if (context) {
          // builtin modules take first priority
          var inContext = context.inContext(id);
          if (inContext) { return inContext; }

        }

        // if relative base on main script location
        if (id.charAt(0) === '.') {
          var inProject = path.join(ss.root,id);
          if (fs.existsSync(inProject+'.js')) {
            debug('found '+id);
            return require(inProject);
          }
        }

        // getting a packaged module
        var mod = projectOrHereRequire(id,ss.root);
        if (mod) {
          debug('found '+id+' in project or SocketStream');
          return require(mod);
        }
        break;
    }

		if (context && defaultId) {
			// default looked up in context first
			var defaultInContext = context.inContext(defaultId);
			if (defaultInContext) { return defaultInContext; }

			// all bets are off
			mod = projectOrHereRequire(defaultId,ss.root);
			if (mod) {
				debug('found '+defaultId+' in project or SocketStream');
				return require(mod);
			}
		}

		if (callback) {
			return callback({
				id:id
			});
		}
		throw new Error('Cannot find module "' + id + '" in socketstream or project');
	}
```
- example usage
```shell
...



// Entry point for app.js
'use strict';

var ss = require('./lib/socketstream.js'),
  express = ss.api.require('express');

module.exports = function() {
var app = ss.http.middleware = express();

app.listen = function() {
  ss.ws.listen.apply(ss.ws, arguments);
};
...
```

#### <a name="apidoc.element.socketstream.session.Cookie"></a>[function <span class="apidocSignatureSpan">socketstream.</span>session.Cookie (options)](#apidoc.element.socketstream.session.Cookie)
- description and source-code
```javascript
function Cookie(options) {
  this.path = '/';
  this.maxAge = null;
  this.httpOnly = true;
  if (options) {merge(this, options);}
  this.originalMaxAge = undefined === this.originalMaxAge ?
      this.maxAge :
      this.originalMaxAge;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.MemoryStore"></a>[function <span class="apidocSignatureSpan">socketstream.</span>session.MemoryStore ()](#apidoc.element.socketstream.session.MemoryStore)
- description and source-code
```javascript
function MemoryStore() {
  Store.call(this)
  this.sessions = Object.create(null)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.Session"></a>[function <span class="apidocSignatureSpan">socketstream.</span>session.Session (req, data)](#apidoc.element.socketstream.session.Session)
- description and source-code
```javascript
function Session(req, data) {
  Object.defineProperty(this, 'req', { value: req });
  Object.defineProperty(this, 'id', { value: req.sessionID });

  if (typeof data === 'object' && data !== null) {
    // merge data into this, ignoring prototype properties
    for (var prop in data) {
      if (!(prop in this)) {
        this[prop] = data[prop]
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.Store"></a>[function <span class="apidocSignatureSpan">socketstream.</span>session.Store ()](#apidoc.element.socketstream.session.Store)
- description and source-code
```javascript
function Store(){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.set"></a>[function <span class="apidocSignatureSpan">socketstream.</span>set (where, what)](#apidoc.element.socketstream.set)
- description and source-code
```javascript
set = function (where, what) {
  var path = require('path');

  if (where === '*') {
    if (what.root) {
      if (path.isAbsolute(what.root)) {
        exports.root = api.root = what.root;
      } else {
        var scriptBase = path.dirname(process.argv[1]);
        exports.root = api.root = path.join(scriptBase,what.root);
      }
    }

    if (what.client) {
      client.set(what.client);
    }
    if (what.http) {
      http.set(what.http);
    }
    //TODO vars, locals remembered as fallbacks
  }
}
```
- example usage
```shell
...
  app.socketstream = function( fn(req,stream) )

  app.stream = ss.http.stream;
  */
  app.stream = ss.http.stream;

  if (ss.env === 'development') {
app.set('views', ss.client.dirs.views);
// Showing stack errors
app.set('showStackError', true);
// Disable views cache
app.set('view cache', false);

// Environment dependent middleware
// throws cannot find stack
...
```

#### <a name="apidoc.element.socketstream.start"></a>[function <span class="apidocSignatureSpan">socketstream.</span>start ()](#apidoc.element.socketstream.start)
- description and source-code
```javascript
start = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.task"></a>[function <span class="apidocSignatureSpan">socketstream.</span>task (name, dependents, fn)](#apidoc.element.socketstream.task)
- description and source-code
```javascript
function task(name, dependents, fn) {
  orchestrator.add(name, dependents, fn);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.api"></a>[module socketstream.api](#apidoc.module.socketstream.api)

#### <a name="apidoc.element.socketstream.api.add"></a>[function <span class="apidocSignatureSpan">socketstream.api.</span>add (name, fn)](#apidoc.element.socketstream.api.add)
- description and source-code
```javascript
add = function (name, fn) {
  if (api[name]) {
    throw new Error('Unable to register internal API extension \'' + name + '\' as this name has already been taken');
  } else {
    api[name] = fn;
    return true;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.defaultTask"></a>[function <span class="apidocSignatureSpan">socketstream.api.</span>defaultTask (name, dependents, fn)](#apidoc.element.socketstream.api.defaultTask)
- description and source-code
```javascript
function defaultTask(name, dependents, fn) {
  if (!orchestrator.hasTask(name)) {
    orchestrator.add(name, dependents, fn);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.load"></a>[function <span class="apidocSignatureSpan">socketstream.api.</span>load ()](#apidoc.element.socketstream.api.load)
- description and source-code
```javascript
function load() {
  if (!loaded) {
    var addons = [], skipped = [];

    // load addon modules
    api.require.forEach(['socketstream-*','socketstream.*'],function(mod,id) {
      if (typeof mod === 'function') {
        try {
          mod(api);
          addons.push(id);
        } catch(ex) {
          debug('Failed to load '+id+'. ',ex);
        }
      } else {
        skipped.push(id);
      }
    });
    debug('Addons: '+
      addons.length? addons.join(' + ') + ' Loaded. ':' None. '+
      skipped.length? skipped.join(' + ') + ' Skipped. ':'');

    // load assets in cache
    http.load();

    // Load Client Asset Manager
    client.load();

    // Load internal and project responders
    api.server.responders = exports.responders.load();

    api.server.eventTransport = publish.transport.load();

    // Extend the internal API with a publish object you can call from your own server-side code
    api.publish = publish.api(api.server.eventTransport);

    // Bind responders to websocket
    ws.load(api.server.responders, api.server.eventTransport);

    debug('API loaded.');
  }
  loaded = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.require"></a>[function <span class="apidocSignatureSpan">socketstream.api.</span>require (id, contextPath, defaultId)](#apidoc.element.socketstream.api.require)
- description and source-code
```javascript
function requires(id, contextPath, defaultId) {
		var context, callback;
		if (typeof defaultId === 'function') {
			callback = defaultId;
			defaultId = null;
		}
		if (contextPath) {
			context = contexts[contextPath];
			if (context === undefined) {
				context = contexts[contextPath] = {
					rel : context,
					prefix: path.join(__dirname, '..', contextPath),
					inContext: function(id) {
						try {
							var p = path.join(context.prefix,id);
							if (require.resolve(p)) { // gives full path
								return require(p);
							}
						} catch(ex) {}
					}
				};
			}
    }

    switch(typeof id) {
      case 'object':
      case 'function':
        if (id) {
          return id; // straight object/function will just resolve straight away
        }
        break;
      case 'string':
        if (context) {
          // builtin modules take first priority
          var inContext = context.inContext(id);
          if (inContext) { return inContext; }

        }

        // if relative base on main script location
        if (id.charAt(0) === '.') {
          var inProject = path.join(ss.root,id);
          if (fs.existsSync(inProject+'.js')) {
            debug('found '+id);
            return require(inProject);
          }
        }

        // getting a packaged module
        var mod = projectOrHereRequire(id,ss.root);
        if (mod) {
          debug('found '+id+' in project or SocketStream');
          return require(mod);
        }
        break;
    }

		if (context && defaultId) {
			// default looked up in context first
			var defaultInContext = context.inContext(defaultId);
			if (defaultInContext) { return defaultInContext; }

			// all bets are off
			mod = projectOrHereRequire(defaultId,ss.root);
			if (mod) {
				debug('found '+defaultId+' in project or SocketStream');
				return require(mod);
			}
		}

		if (callback) {
			return callback({
				id:id
			});
		}
		throw new Error('Cannot find module "' + id + '" in socketstream or project');
	}
```
- example usage
```shell
...



// Entry point for app.js
'use strict';

var ss = require('./lib/socketstream.js'),
  express = ss.api.require('express');

module.exports = function() {
var app = ss.http.middleware = express();

app.listen = function() {
  ss.ws.listen.apply(ss.ws, arguments);
};
...
```

#### <a name="apidoc.element.socketstream.api.task"></a>[function <span class="apidocSignatureSpan">socketstream.api.</span>task (name, dependents, fn)](#apidoc.element.socketstream.api.task)
- description and source-code
```javascript
function task(name, dependents, fn) {
  orchestrator.add(name, dependents, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.unload"></a>[function <span class="apidocSignatureSpan">socketstream.api.</span>unload ()](#apidoc.element.socketstream.api.unload)
- description and source-code
```javascript
function unload() {
  loaded = false;

  tasks.unload();
  client.unload();
  client.assets.unload();
  http.unload();
  api.server.responders = undefined;
  ws.unload();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.api.bundler"></a>[module socketstream.api.bundler](#apidoc.module.socketstream.api.bundler)

#### <a name="apidoc.element.socketstream.api.bundler.browserifyLoader"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>browserifyLoader ()](#apidoc.element.socketstream.api.bundler.browserifyLoader)
- description and source-code
```javascript
browserifyLoader = function () {
  if (!this.browserifyContent) {
    this.browserifyContent = fs.readFileSync(path.join(__dirname,'browserify.client.js'),'utf8');
  }
  return {
    type: 'mod',
    file: 'loader',
    includeType: 'system',
    names: ['browserify.client.js'],
    content: this.browserifyContent
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.clientFilePath"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>clientFilePath (rel)](#apidoc.element.socketstream.api.bundler.clientFilePath)
- description and source-code
```javascript
clientFilePath = function (rel) {
  if (typeof rel === 'object') {
    // entry object
    rel = rel.file;
  }
  return path.join(ss.root,rel);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.constants"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>constants (client)](#apidoc.element.socketstream.api.bundler.constants)
- description and source-code
```javascript
constants = function (client) {
  var constants = {}, k;

  // mixin system constants
  for(k in system.assets.constants) {
    constants[k] = system.assets.constants[k];
  }

  // mixin client constants
  if (client.constants) {
    for(k in client.constants) {
      constants[k] = describeConstant(k, client.constants[k]);
    }
  }

  function describeConstant(key,value) {
    var desc = { name:key, value:value, type:'constant' };
    // perhaps add, value = function support
    return desc;
  }

  // list of constants
  var list = [];
  for(k in constants) {
    constants[k].content = 'var '+constants[k].name+'='+ JSON.stringify(constants[k].value) +';';
    list.push(constants[k]);
  }
  return list;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.create"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>create (bundler)](#apidoc.element.socketstream.api.bundler.create)
- description and source-code
```javascript
function create(bundler) {
  var created = Object.create(proto);
  if (bundler) {
    for(var key in bundler) {
      created[key] = bundler[key];
    }
  }
  return created;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.define"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>define (client, args)](#apidoc.element.socketstream.api.bundler.define)
- description and source-code
```javascript
function defineBundler(client, args) {

  var name = args[0],
      pathsOrPlugin = args[1],
      bundler;

  if (typeof pathsOrPlugin === "string") {
    bundler = bundlers[name] = ss.require(options.servePacked?'production':args[1],'client/bundler','default')(ss,client,options
);
    bundler.client = client;
    bundler.define(args[2], args[3], args[4], args[5]);
  } else {
    bundler = bundlers[name] = require('./default')(ss,client,options); //TODO production bundler switch
    bundler.client = client;
    bundler.define(args[1],args[2]);
  }
  bundler.useLatestsPackedId();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.destsFor"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>destsFor (client)](#apidoc.element.socketstream.api.bundler.destsFor)
- description and source-code
```javascript
destsFor = function (client) {
  var containerDir = path.join(ss.root, options.dirs.assets);
  var clientDir = path.join(containerDir, client.name);
  var assetsUrl = options.urls.assets;

  return {

    //TODO perhaps mixin the abs versions by SS
    urls: {
      html: assetsUrl + client.name + '/' + client.id + '.html',
      js: assetsUrl + client.name + '/' + client.id + '.js',
      css: assetsUrl + client.name + '/' + client.id + '.css'
    },
    paths: {
      html: path.join(clientDir, client.id + '.html'),
      js: path.join(clientDir, client.id + '.js'),
      css: path.join(clientDir, client.id + '.css')
    },
    relPaths: {
      html: path.join(options.dirs.assets, client.name, client.id + '.html'),
      js: path.join(options.dirs.assets, client.name, client.id + '.js'),
      css: path.join(options.dirs.assets, client.name, client.id + '.css')
    },
    dir: clientDir,
    containerDir: containerDir
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.entries"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>entries (client, assetType)](#apidoc.element.socketstream.api.bundler.entries)
- description and source-code
```javascript
function entries(client, assetType) {

  var _entries = [],
      bundler = getBundler(client),
      includeType,
      bundle;

  switch(assetType) {
    case 'css':
      includeType = 'css';
      bundle = 'css';
      client.paths['css'].forEach(pushMainEntries);
      break;

    case 'js':
    case 'worker':
      var loader = bundler.module('loader');
      var libs = bundler.module('libs');
      var mods = bundler.module.apply(bundler, Object.keys(system.assets.modules));

      _entries = _entries.concat(loader).concat(libs).concat(mods);
      includeType = false;
      bundle = 'js';
      //TODO worker instead of code ?
      client.paths.code.forEach(pushMainEntries);
      if (options.startInBundle) {
        _entries = _entries.concat(bundler.module('start'));
      }
      break;

    case 'tmpl':
      includeType = 'html';
      bundle = 'tmpl';
      client.paths.tmpl.forEach(pushMainEntries);
      break;
  }

  function pushMainEntries(from) {
    var p = path.join(ss.root,from);
    if (!fs.existsSync(p) || fs.statSync(p).isFile()) {
      p = from;
    } else {
      p = path.join(from,'**','*');
    }
    return glob.sync(p, {cwd:ss.root}).forEach(function(file) {
      var extension = path.extname(file);
      extension = extension && extension.substring(1); // argh!
      var assetType = bundle==='tmpl'? 'html':bundle;
      var entry = {file:file,importedBy:from,includeType:includeType,ext:extension,bundle:bundle,assetType:assetType};
      if (isAssetType(entry)) {
        _entries.push(entry);
      }
    });
  }

  function isAssetType(entry) {
    if (ss.client.formatters == null) {
      return false;
    }
    var formatter = ss.client.formatters[entry.ext];
    if (formatter == null) {
      return false;
    }
    if (formatter.assetType === undefined) {
      throw new Error('Unable to render \''+entry.file+'\' as the formatter has no asset type.');
    }
    return formatter.assetType === entry.assetType;
  }

  // entries with blank ones stripped out
  return _entries.filter(function(entry) {
    return !!entry;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.entryFor"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>entryFor (bundle, file, part2)](#apidoc.element.socketstream.api.bundler.entryFor)
- description and source-code
```javascript
entryFor = function (bundle, file, part2) {
  var result = {
    bundle: bundle,
    file:file
  };
  if (part2) {
    if (part2.charAt(0) !== '/') {
      part2 = '/' + part2;
    }
    result.file = file + part2;
  }

  switch(bundle) {
    case 'tmpl':
      result.assetType = 'html';
      break;
    case 'worker':
      result.assetType = 'js';
      break;
  }

  var extension = path.extname(result.file);
  result.ext = extension? extension.substring(1) : (result.assetType || result.bundle);

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.findEntryPoint"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>findEntryPoint (client)](#apidoc.element.socketstream.api.bundler.findEntryPoint)
- description and source-code
```javascript
findEntryPoint = function (client) {

  var firstIndex, // if no entry point, use first index found
      firstFile;  // if no entry and index, use first file found

  function onlyModuleEntry(f) {
    return f.substring(0,6) === 'entry.';
  }
  function onlyModuleIndex(f) {
    return f.substring(0,6) === 'index.';
  }
  function diskToRequire(rel) {
    return '/' + rel.replace(/\\/g,'/');
  }

  for(var i = 0,rel; (rel = client.paths.code[i]); ++i) {
    var p = path.join(ss.root, rel);
    //TODO if not exists error handling
    if (fs.existsSync(p) && fs.statSync(p).isDirectory()) {

      var files = fs.readdirSync(p);
      var entry = files.filter(onlyModuleEntry);
      if (entry.length) {
        return diskToRequire(rel) + '/entry';
      }
      var index = files.filter(onlyModuleIndex);
      if (index && !firstIndex) {
        firstIndex = diskToRequire(rel) + '/';
      }
    }
    else {
      firstFile = diskToRequire(rel);
      firstFile = firstFile.substring(0, firstFile.length - path.extname(firstFile).length);
    }
  }

  return firstIndex || firstFile;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.forEach"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>forEach (fn, that)](#apidoc.element.socketstream.api.bundler.forEach)
- description and source-code
```javascript
forEach = function (fn, that) {
  for(var key in bundlers) {
      var bundler = bundlers[key];
      fn.call(that,bundler,key);
  }
}
```
- example usage
```shell
...
sh.exec('git branch gh-pages origin/gh-pages' + branch, {silent: true})
        }
    });

    grunt.registerMultiTask('shell', 'run shell commands', function() {
        var self = this;

        self.data.forEach(function(cmd) {
cmd = cmd.replace('%version%', grunt.file.readJSON('package.json').version);
grunt.log.ok(cmd);

var result = sh.exec(cmd, { silent: true });

if (result.code !== 0) {
    grunt.fatal(result.output);
...
```

#### <a name="apidoc.element.socketstream.api.bundler.forget"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>forget ()](#apidoc.element.socketstream.api.bundler.forget)
- description and source-code
```javascript
forget = function () {
  bundlerById = {};
  bundlers = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.formatKb"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>formatKb (size)](#apidoc.element.socketstream.api.bundler.formatKb)
- description and source-code
```javascript
function formatKb(size) {
  return '' + (Math.round((size / 1024) * 1000) / 1000) + ' KB';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.get"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>get (client)](#apidoc.element.socketstream.api.bundler.get)
- description and source-code
```javascript
function getBundler(client){
  if (typeof client === "string") { return bundlers[client]; }

  if (client.bundler) { return client.bundler; }

  if (client.ts) {
    if (bundlerById[client.ts]) {
      return bundlerById[client.ts];
    }
  }
  if (typeof client.client === "string") {
    return bundlers[client.client];
  }
  if (typeof client.name === "string") {
    return bundlers[client.name];
  }

  throw new Error('Unknown client '+(client.name || client.client || client.ts) );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.injectTailIfNeeded"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>injectTailIfNeeded (output, opts)](#apidoc.element.socketstream.api.bundler.injectTailIfNeeded)
- description and source-code
```javascript
injectTailIfNeeded = function (output, opts) {
  // If passing optional tails for main view
  if (opts && opts.tail && !options.startInBundle) {
    output = output.replace('</body>', opts.tail + '</body>');
    output = output.replace('</BODY>', opts.tail + '</BODY>');
  }
  return output;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.load"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>load ()](#apidoc.element.socketstream.api.bundler.load)
- description and source-code
```javascript
load = function () {
  var ids = []
  this.forEach(function(bundler) {
    bundlerById[bundler.client.id] = bundler;
    ids.push(bundler.client.id);
    if (bundler.load) {
        bundler.load();
    }
  });
  debug('loaded clients %s', ids.join(' '));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.loadFile"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>loadFile (entry, opts, formatter, cb, errCb)](#apidoc.element.socketstream.api.bundler.loadFile)
- description and source-code
```javascript
function loadFile(entry, opts, formatter, cb, errCb) {
  var type = entry.assetType || entry.bundle;
  formatter = formatter || ss.client.formatters[entry.ext || type];
  if (!formatter) {
    throw new Error('Unsupported file extension \'.' + entry.ext + '\' when we were expecting some type of ' +
      ((type||'unknown').toUpperCase()) + ' file. Please provide a formatter for ' + (entry.file) + ' or move it to /client/static
');
  }
  if (formatter.assetType !== type) {
    throw new Error('Unable to render \'' + entry.file + '\' as this appears to be a ' + (type.toUpperCase()) +
      ' file. Expecting some type of ' + (type.toUpperCase()) + ' file in ' + (path.dirname(entry.file)) + ' instead');
  }

  // Use the formatter to pre-process the asset before bundling
  try {
    return formatter.call(this.clientFilePath(entry.file), opts, cb, errCb);
  } catch (err) {
    return errCb(err);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.minifyCSS"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>minifyCSS (files)](#apidoc.element.socketstream.api.bundler.minifyCSS)
- description and source-code
```javascript
function minifyCSS(files) {
  var origLength = 0;
  var minified = files.map(function(entry){
    origLength += entry.content.length;
    return new CleanCSS().minify(entry.content).styles; // this could also be an async call
  }).join('\n');
  log.info(('  Minified CSS from ' + (formatKb(origLength)) + ' to ' + (formatKb(minified.length))).grey);
  return minified;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.minifyJS"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>minifyJS (files)](#apidoc.element.socketstream.api.bundler.minifyJS)
- description and source-code
```javascript
function minifyJS_(files) {
  var that = this;
  var min = files.map(function(js) {
    return js.options.minified ? js.content : that.minifyJSFile(js.content);
  });
  return min.join('\n');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.minifyJSFile"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>minifyJSFile (originalCode, fileName)](#apidoc.element.socketstream.api.bundler.minifyJSFile)
- description and source-code
```javascript
function minifyJSFile(originalCode, fileName) {
  var ast = uglifyjs.parse(originalCode, { filename:fileName });
  ast.figure_out_scope();
  ast = ast.transform(compressor);

  ast.figure_out_scope();
  ast.compute_char_frequency();
  ast.mangle_names();
  var minifiedCode = ast.print_to_string();
  if (fileName) {
    log.info(('  Minified ' + fileName + ' from ' + (formatKb(originalCode.length)) + ' to ' + (formatKb(minifiedCode.length))).
grey);
  }
  return minifiedCode;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.packAssetSet"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>packAssetSet (assetType, client, postProcess, done)](#apidoc.element.socketstream.api.bundler.packAssetSet)
- description and source-code
```javascript
function packAssetSet(assetType, client, postProcess, done) {
  var bundler = getBundler(client);

  // if this goes away, drop async dependency. manage with orchestrator?
  async.mapSeries(bundler.entries(assetType,system.assets), iterator, andThen);

  function iterator(entry, callback) {
    var options = {
      constants: bundler.constants(),
      locals: bundler.locals(),
      //pathPrefix: entry.importedBy,
      compress: true
    };
    if (typeof entry.content === "string") {
      callback(null, {content:entry.content,options:{}});
    }
    else {
      bundler.asset(entry, options, function(output) {
        //TODO if err, flag has errors
        callback(null, {content:output,options:{}});
      });
    }
  }

  function andThen(err, results) {
    var fileName = bundler.dests.paths[assetType];
    fs.writeFileSync(fileName, postProcess(results.filter(function(f) { return f.content && f.content !== ';'; })));
    log.info('✓'.green, 'Packed', results.length, 'files into', bundler.dests.relPaths[assetType]);
    done();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.sourcePaths"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>sourcePaths (paths)](#apidoc.element.socketstream.api.bundler.sourcePaths)
- description and source-code
```javascript
sourcePaths = function (paths) {

  function relativePath(p, dirType) {
      var relativeStart = p.indexOf('./') === 0 || p.indexOf('../') === 0;
      return relativeStart? prefixPath(options.dirs.client,p) : prefixPath(options.dirs[dirType], p);
  }

  function prefixPath(base,p) {
      base = base.replace(/^\//,'');
      if (p === '*') {
        return base;
      }
      p = p.replace(/\/\*$/,'');
      return path.join(base,p);
  }

  function entries(from, dirType) {
    if (from == null) {
      return [];
    }
    var list = (from instanceof Array)? from : [from];

    return list.map(function(value) {
      return relativePath(value, dirType);
    });
  }

  paths.css = entries(paths.css, 'css');
  paths.code = entries(paths.code, 'code');
  paths.tmpl = entries(paths.tmpl || paths.templates, 'templates');

  if (paths.view) {
    paths.view = relativePath(paths.view, 'views');
  }

  return paths;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.startCode"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>startCode (client)](#apidoc.element.socketstream.api.bundler.startCode)
- description and source-code
```javascript
startCode = function (client) {
  var startCode = system.assets.startCode.map(function(ic) { return ic.content; }),
    entryInit = client.entryInitPath? 'require("' + client.entryInitPath + '");' : options.defaultEntryInit;

  if (typeof options.entryModuleName === 'string' || options.entryModuleName === null) {
    entryInit = options.entryModuleName? 'require("/'+options.entryModuleName+'");' : '';
  }

  startCode.push(entryInit);

  return [{ content: startCode.join('\n'), options: {}, type: 'start', includeType:'initCode' }];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.systemLibs"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>systemLibs ()](#apidoc.element.socketstream.api.bundler.systemLibs)
- description and source-code
```javascript
systemLibs = function () {
  var names = [];
  return {
    type: 'mod',
    file: 'libs',
    includeType: 'system',
    names: names,
    content: system.assets.libs.map(function(lib) { names.push(lib.name); return lib.content; }).join('\n')
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.systemModule"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>systemModule (name, wrap)](#apidoc.element.socketstream.api.bundler.systemModule)
- description and source-code
```javascript
function systemModule(name, wrap) {
  name = name.replace(/\.js$/,'');
  var mod = system.assets.modules[name];
  if (mod) {
    var code = wrap===false? mod.content: ss.bundler.wrapModule(name, mod.content);
    return {
      file: mod.name,
      name: mod.name,
      path: mod.path,
      dir: mod.dir,
      content: code,
      options: mod.options,
      type: mod.type,
      includeType: 'system'
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.systemModules"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>systemModules (wrap)](#apidoc.element.socketstream.api.bundler.systemModules)
- description and source-code
```javascript
systemModules = function (wrap) {
  return Object.keys(system.assets.modules).map(function(name) {
    return systemModule(name,wrap);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.unload"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>unload ()](#apidoc.element.socketstream.api.bundler.unload)
- description and source-code
```javascript
unload = function () {
  for(var n in bundlers) {
    if (bundlers[n].unload) {
      bundlers[n].unload();
      bundlers[n].unload = null;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.updateCachedOndemandAssets"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>updateCachedOndemandAssets ()](#apidoc.element.socketstream.api.bundler.updateCachedOndemandAssets)
- description and source-code
```javascript
function UpdateCachedOndemandAssets() {

  var files = glob.sync('**/*.js', {cwd: path.join(ss.root,options.dirs.code)}); //TODO need root *.js as well
  files.forEach(function(rel) {
    ss.http.cached.route('assets/ondemand/'+ (rel.replace('\\','/')), null, path.join(ss.root, options.dirs.code, rel) );
  },this);

  files = glob.sync('**/*.js', {cwd: path.join(ss.root,options.dirs.workers)}); //TODO need root *.js as well
  files.forEach(function(rel) {
    ss.http.cached.route('assets/workers/'+ (rel.replace('\\','/')), null, path.join(ss.root, options.dirs.workers, rel) );
  },this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.bundler.wrapModule"></a>[function <span class="apidocSignatureSpan">socketstream.api.bundler.</span>wrapModule (modPath, code)](#apidoc.element.socketstream.api.bundler.wrapModule)
- description and source-code
```javascript
wrapModule = function (modPath, code) {
  return 'require.define("' + modPath + '", function (require, module, exports, __dirname, __filename){\n' + code + '\n});'+
  '';
        //TODO  '\n//# sourceMappingURL='+modPath+'.js\n';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.api.client"></a>[module socketstream.api.client](#apidoc.module.socketstream.api.client)

#### <a name="apidoc.element.socketstream.api.client.send"></a>[function <span class="apidocSignatureSpan">socketstream.api.client.</span>send (type, name, content, options)](#apidoc.element.socketstream.api.client.send)
- description and source-code
```javascript
send = function (type, name, content, options) {
  if (options === null || options === undefined) {
    options = {};
  }

  switch (type) {
    case 'const':
    case 'constant':
      //jshint -W093
      return (assets.constants[name] = {value:content,name:name,type:'const',options:options});
    case 'local':
      //jshint -W093
      return (assets.locals[name] = { value:content,name:name,type:type,options:options});
    case 'start':
    case 'code':
      return assets.startCode.push({content:content,options:options, type:'start'});
    case 'lib':
    case 'library':
      return pushUniqueAsset('libs',{
        name: name,
        type: 'lib',
        dir: pathlib.join(__dirname,'libs'),
        path: pathlib.join(__dirname,'libs',name + '.js'),
        content: content,
        options: options
      });
    case 'mod':
    case 'module':
      if (assets.modules[name]) {
        throw new Error('System module name \'' + name + '\' already exists');
      } else {
        name = name.replace(/\.js$/,'');
        assets.modules[name] = {
          name: name,
          type: 'mod',
          dir: pathlib.join(__dirname,'modules'),
          path: pathlib.join(__dirname,'modules',name + '.js'),
          content: content,
          options: options
        };
        return assets.modules[name];
      }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.api.log"></a>[module socketstream.api.log](#apidoc.module.socketstream.api.log)

#### <a name="apidoc.element.socketstream.api.log.clientIssue"></a>[function <span class="apidocSignatureSpan">socketstream.api.log.</span>clientIssue (client, options, err, more)](#apidoc.element.socketstream.api.log.clientIssue)
- description and source-code
```javascript
function clientIssue(client, options, err, more) {
  var info = [''];
  if (options.serveDebugInfo) {
    err.userInfo = info;
  }
  info.push(err.message);
  info.push('client='+client.id);
  if (err.stack) {
    info = info.concat(err.stack.split('\n').splice(1));
  }
  if (more) {
    info.push('more:');
    info.push(JSON.stringify(more));
  }

  var number = nextClientIssue++;

  Object.defineProperty(err, 'userInfoHTML', {
    get: function() {
      return this.userInfo? this.userInfo.join('<br>') : ' issue='+number;
    }
  });
  Object.defineProperty(err, 'userInfoText', {
    get: function() {
      return this.userInfo? this.userInfo.join('\n') : ' issue='+number;
    }
  });

  this.error(('Couldn\'t serve client '+client.name+',').red, 'issue='+number, info.join('\n'));

  return number;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.log.debug"></a>[function <span class="apidocSignatureSpan">socketstream.api.log.</span>debug ()](#apidoc.element.socketstream.api.log.debug)
- description and source-code
```javascript
debug = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.log.error"></a>[function <span class="apidocSignatureSpan">socketstream.api.log.</span>error ()](#apidoc.element.socketstream.api.log.error)
- description and source-code
```javascript
error = function () { [native code] }
```
- example usage
```shell
...
    result = sh.exec('git symbolic-ref HEAD', {silent: true});
    if (result.output.trim() !== 'refs/heads/' + branch) {
        throw new Error('Not on master branch, aborting! Current branch is \'' + result.output.trim() + '\'');
    }

    result = sh.exec('git status --porcelain', {silent: true});
    if (result.output.trim() !== '') {
        grunt.log.error(result.output.trim());
        throw new Error('Working copy is dirty, aborting!');
    }
});

grunt.registerTask('is-gh-pages-branch-exist', 'Check if gh-pages branch exists, if not create it', function() {
    var result,
        branch = this.args[0];
...
```

#### <a name="apidoc.element.socketstream.api.log.info"></a>[function <span class="apidocSignatureSpan">socketstream.api.log.</span>info ()](#apidoc.element.socketstream.api.log.info)
- description and source-code
```javascript
info = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.log.trace"></a>[function <span class="apidocSignatureSpan">socketstream.api.log.</span>trace ()](#apidoc.element.socketstream.api.log.trace)
- description and source-code
```javascript
trace = function () {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.api.log.warn"></a>[function <span class="apidocSignatureSpan">socketstream.api.log.</span>warn ()](#apidoc.element.socketstream.api.log.warn)
- description and source-code
```javascript
warn = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.api.require"></a>[module socketstream.api.require](#apidoc.module.socketstream.api.require)

#### <a name="apidoc.element.socketstream.api.require.require"></a>[function <span class="apidocSignatureSpan">socketstream.api.</span>require (id, contextPath, defaultId)](#apidoc.element.socketstream.api.require.require)
- description and source-code
```javascript
function requires(id, contextPath, defaultId) {
		var context, callback;
		if (typeof defaultId === 'function') {
			callback = defaultId;
			defaultId = null;
		}
		if (contextPath) {
			context = contexts[contextPath];
			if (context === undefined) {
				context = contexts[contextPath] = {
					rel : context,
					prefix: path.join(__dirname, '..', contextPath),
					inContext: function(id) {
						try {
							var p = path.join(context.prefix,id);
							if (require.resolve(p)) { // gives full path
								return require(p);
							}
						} catch(ex) {}
					}
				};
			}
    }

    switch(typeof id) {
      case 'object':
      case 'function':
        if (id) {
          return id; // straight object/function will just resolve straight away
        }
        break;
      case 'string':
        if (context) {
          // builtin modules take first priority
          var inContext = context.inContext(id);
          if (inContext) { return inContext; }

        }

        // if relative base on main script location
        if (id.charAt(0) === '.') {
          var inProject = path.join(ss.root,id);
          if (fs.existsSync(inProject+'.js')) {
            debug('found '+id);
            return require(inProject);
          }
        }

        // getting a packaged module
        var mod = projectOrHereRequire(id,ss.root);
        if (mod) {
          debug('found '+id+' in project or SocketStream');
          return require(mod);
        }
        break;
    }

		if (context && defaultId) {
			// default looked up in context first
			var defaultInContext = context.inContext(defaultId);
			if (defaultInContext) { return defaultInContext; }

			// all bets are off
			mod = projectOrHereRequire(defaultId,ss.root);
			if (mod) {
				debug('found '+defaultId+' in project or SocketStream');
				return require(mod);
			}
		}

		if (callback) {
			return callback({
				id:id
			});
		}
		throw new Error('Cannot find module "' + id + '" in socketstream or project');
	}
```
- example usage
```shell
...



// Entry point for app.js
'use strict';

var ss = require('./lib/socketstream.js'),
  express = ss.api.require('express');

module.exports = function() {
var app = ss.http.middleware = express();

app.listen = function() {
  ss.ws.listen.apply(ss.ws, arguments);
};
...
```

#### <a name="apidoc.element.socketstream.api.require.forEach"></a>[function <span class="apidocSignatureSpan">socketstream.api.require.</span>forEach (pattern, fn)](#apidoc.element.socketstream.api.require.forEach)
- description and source-code
```javascript
function forEach(pattern, fn) {
		var packageJSON = findup('package.json', {cwd:ss.root});
		if (packageJSON) {
			var dependencies = require(packageJSON).dependencies;
			dependencies = dependencies? Object.keys(dependencies) : [];
			var matches = micromatch(dependencies,pattern);
			var mod = {};
			matches.forEach(function(id) {
				if (mod[id] === undefined) {
					try {
						mod[id] = resolve.sync(id, { package: packageJSON, basedir: ss.root});
						debug('matched '+id+' from pattern '+pattern);
						fn(require(mod[id]),id);
					} catch(ex) {
						//TODO debug log failed to use SocketStream Add-On
					}
				}
			});
		}
	}
```
- example usage
```shell
...
sh.exec('git branch gh-pages origin/gh-pages' + branch, {silent: true})
        }
    });

    grunt.registerMultiTask('shell', 'run shell commands', function() {
        var self = this;

        self.data.forEach(function(cmd) {
cmd = cmd.replace('%version%', grunt.file.readJSON('package.json').version);
grunt.log.ok(cmd);

var result = sh.exec(cmd, { silent: true });

if (result.code !== 0) {
    grunt.fatal(result.output);
...
```

#### <a name="apidoc.element.socketstream.api.require.resolve"></a>[function <span class="apidocSignatureSpan">socketstream.api.require.</span>resolve (id)](#apidoc.element.socketstream.api.require.resolve)
- description and source-code
```javascript
function resolves(id) {
		return projectOrHereRequire(id,ss.root);
	}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.client"></a>[module socketstream.client](#apidoc.module.socketstream.client)

#### <a name="apidoc.element.socketstream.client.define"></a>[function <span class="apidocSignatureSpan">socketstream.client.</span>define (name)](#apidoc.element.socketstream.client.define)
- description and source-code
```javascript
define = function (name) {
  if (clients[name]) {
    throw new Error('Client name \'' + name + '\' has already been defined');
  }
  // if a function is used construct a bundler with it otherwise use default bundler
  var client = clients[name] = {
    name: name,
    paths: {},
    uniqueId: shortid.generate(),
    includes: {
      css: true,
      html: true,
      system: true,
      initCode: true
    }
  };
  client.id = client.uniqueId;

  ss.bundler.define(client,arguments);

  return client;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.client.forget"></a>[function <span class="apidocSignatureSpan">socketstream.client.</span>forget ()](#apidoc.element.socketstream.client.forget)
- description and source-code
```javascript
forget = function () {
    clients = {};
    setDefaultOptions(options);
    systemAssets.unload();
    ss.bundler.forget();
    if (this.templateEngine) { this.templateEngine.forget(); this.templateEngine = null; }
    if (this.formatters) { this.formatters.forget(); this.formatters = null; }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.client.init"></a>[function <span class="apidocSignatureSpan">socketstream.client.</span>init ()](#apidoc.element.socketstream.client.init)
- description and source-code
```javascript
init = function () {
  this.templateEngine = this.templateEngine || require('./template_engine')(ss,options);

  if (this.formatters == null) {
    this.formatters = require('./formatters')(ss,options);

    // Load default code formatters
    this.formatters.add('javascript');
    this.formatters.add('css');
    this.formatters.add('html');
    this.formatters.add('map');
  }

  systemAssets.load();

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.client.load"></a>[function <span class="apidocSignatureSpan">socketstream.client.</span>load ()](#apidoc.element.socketstream.client.load)
- description and source-code
```javascript
load = function () {
  if (options.servePacked) {
    ss.bundler.forEach(function(bundler) {
      bundler.useLatestsPackedId();
    });
  }
  ss.bundler.load();
  //TODO convert options.dirs to relative paths stripping the lead '/' if present

  // Cache instances of code formatters and template engines here
  // This may change in the future as I don't like hanging system objects
  // on the 'ss' internal API object, but for now it solves a problem
  // we were having when repl.start() would erase vars cached inside a module
  ss.client.formatters = this.formatters.load();
  ss.client.templateEngines = this.templateEngine.load();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.client.packAssets"></a>[function <span class="apidocSignatureSpan">socketstream.client.</span>packAssets (opts)](#apidoc.element.socketstream.client.packAssets)
- description and source-code
```javascript
packAssets = function (opts) {
  if (opts && typeof opts !== 'object') {
    throw new Error('Options passed to ss.client.packAssets() must be an object');
  }
  options.packedAssets = opts || true;
  options.servePacked = opts || true;
  options.liveReload = false;

  // As it's safe to assume we're running in production mode at this point, if your app is not catching uncaught
  // errors with its own custom error handling code, step in and prevent any exceptions from taking the server down
  if (options.packedAssets && process.listeners('uncaughtException').length === 0) {
    return process.on('uncaughtException', function(err) {
      log.error('Uncaught Exception!'.red);
      return log.error(err.stack);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.client.reloadCached"></a>[function <span class="apidocSignatureSpan">socketstream.client.</span>reloadCached ()](#apidoc.element.socketstream.client.reloadCached)
- description and source-code
```javascript
reloadCached = function () {
  ss.http.cached.loadStatic();
  ss.http.cached.loadAssets();
  ss.bundler.updateCachedOndemandAssets();

  ss.bundler.forEach(function(bundler) {
    bundler.updateCachedDevAssets();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.client.reloadClients"></a>[function <span class="apidocSignatureSpan">socketstream.client.</span>reloadClients (changedPath, event)](#apidoc.element.socketstream.client.reloadClients)
- description and source-code
```javascript
function reloadClients(changedPath, event) {
   var customOnChange = options.onChange || {},
       delayTime = customOnChange.delayTime || 100,
       guardTime = customOnChange.guardTime || 1000;

   function onChangeFiltered(path, event,action) {
       ss.log.info('✎'.green, consoleMessage[action].grey);
       var pubs ='__ss:' + action;
       if (customOnChange.publish) {
           pubs = options.onChange.publish(path, event,action,pubs);
       }
       if (pubs) {
           ss.publish.all(pubs);
       }

       lastRun[action].at = Date.now();
   }

   // reload the browser
   function onChange(changedPath, event) {
     var _ref = path.extname(changedPath),
         action = cssExtensions.indexOf(_ref) >= 0 ? 'updateCSS' : 'reload';
     //first change is with delayTime delay , thereafter only once there has been no further changes for guardTime seconds

     //validate the change
     if (customOnChange.validate) {
         if (!customOnChange.validate(changedPath, event,action)) { return ;} //ignore changes if the app says-so
     }

     //avoid multiple rapid changes
     var delay=delayTime;
     if (lastRun[action].guardTime) { clearTimeout(lastRun[action].guardTime); delay=guardTime;}
     if (lastRun[action].delayTime) { clearTimeout(lastRun[action].delayTime); delay=delayTime;}
     lastRun[action].delayTime = setTimeout(function(){
         onChangeFiltered(changedPath, event, action);
         lastRun[action].guardTime = setTimeout(function(){
             lastRun[action].guardTime=null;
             }, delay);
          lastRun[action].delayTime=null;
         }, delay);

     return Date.now();
   }

   return onChange(changedPath, event);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.client.servePacked"></a>[function <span class="apidocSignatureSpan">socketstream.client.</span>servePacked (opts)](#apidoc.element.socketstream.client.servePacked)
- description and source-code
```javascript
servePacked = function (opts) {
  if (opts && typeof opts !== 'object') {
    throw new Error('Options passed to ss.client.servePacked() must be an object');
  }
  options.servePacked = opts || true;
  options.liveReload = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.client.set"></a>[function <span class="apidocSignatureSpan">socketstream.client.</span>set (newOption)](#apidoc.element.socketstream.client.set)
- description and source-code
```javascript
set = function (newOption) {
  var k, v, y, _results;
  if (typeof newOption !== 'object') {
    throw new Error('ss.client.set() takes an object e.g. {liveReload: false}');
  }
  _results = [];
  for (k in newOption) {
    if (newOption.hasOwnProperty(k)) {
      v = newOption[k];
      if (v instanceof Object) {
        //jshint -W083
        _results.push((function() {
          var _results1, x;
          _results1 = [];
          for (x in v) {
            if (v.hasOwnProperty(x)) {
              y = v[x];

              if (!options[k]) {
                options[k]= {};
              }

              _results1.push(options[k][x] = y);
            }
          }
          return _results1;
        })());
      } else {
        _results.push(options[k] = v);
      }
    }
  }
  return _results;
}
```
- example usage
```shell
...
  app.socketstream = function( fn(req,stream) )

  app.stream = ss.http.stream;
  */
  app.stream = ss.http.stream;

  if (ss.env === 'development') {
app.set('views', ss.client.dirs.views);
// Showing stack errors
app.set('showStackError', true);
// Disable views cache
app.set('view cache', false);

// Environment dependent middleware
// throws cannot find stack
...
```

#### <a name="apidoc.element.socketstream.client.task"></a>[function <span class="apidocSignatureSpan">socketstream.client.</span>task (client, name, dependents, fn)](#apidoc.element.socketstream.client.task)
- description and source-code
```javascript
task = function (client, name, dependents, fn) {
  // should dependents be translated for other client tasks? Perhaps identify global tasks by a prefix or by lookup
  dependents = dependents.map(function(task) {
    return client+':'+task;
  });
  ss.tasks.add(client+':'+name, dependents, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.client.unload"></a>[function <span class="apidocSignatureSpan">socketstream.client.</span>unload ()](#apidoc.element.socketstream.client.unload)
- description and source-code
```javascript
unload = function () {
  ss.client.formatters = {};
  ss.client.templateEngines = {};
  ss.bundler.unload();
  systemAssets.unload();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.client.assets"></a>[module socketstream.client.assets](#apidoc.module.socketstream.client.assets)

#### <a name="apidoc.element.socketstream.client.assets.load"></a>[function <span class="apidocSignatureSpan">socketstream.client.assets.</span>load ()](#apidoc.element.socketstream.client.assets.load)
- description and source-code
```javascript
load = function () {
  if (assets.modules['eventemitter2']) {return;}

  // System Modules. Including main SocketStream client code
  // Load order is not important
  var modDir = pathlib.join(__dirname, '/modules');
  fsUtils.readDirSync(modDir).files.forEach(function(fileName) {
    var code = fs.readFileSync(fileName, 'utf8');
    var sp = fileName.split('.');
    var extension = sp[sp.length - 1];
    var modName = fileName.substr(modDir.length + 1).replace('.js','').replace('.min.js','');
    return send('mod', modName, code, {
      coffee: extension === 'coffee'
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.client.assets.send"></a>[function <span class="apidocSignatureSpan">socketstream.client.assets.</span>send (type, name, content, options)](#apidoc.element.socketstream.client.assets.send)
- description and source-code
```javascript
send = function (type, name, content, options) {
  if (options === null || options === undefined) {
    options = {};
  }

  switch (type) {
    case 'const':
    case 'constant':
      //jshint -W093
      return (assets.constants[name] = {value:content,name:name,type:'const',options:options});
    case 'local':
      //jshint -W093
      return (assets.locals[name] = { value:content,name:name,type:type,options:options});
    case 'start':
    case 'code':
      return assets.startCode.push({content:content,options:options, type:'start'});
    case 'lib':
    case 'library':
      return pushUniqueAsset('libs',{
        name: name,
        type: 'lib',
        dir: pathlib.join(__dirname,'libs'),
        path: pathlib.join(__dirname,'libs',name + '.js'),
        content: content,
        options: options
      });
    case 'mod':
    case 'module':
      if (assets.modules[name]) {
        throw new Error('System module name \'' + name + '\' already exists');
      } else {
        name = name.replace(/\.js$/,'');
        assets.modules[name] = {
          name: name,
          type: 'mod',
          dir: pathlib.join(__dirname,'modules'),
          path: pathlib.join(__dirname,'modules',name + '.js'),
          content: content,
          options: options
        };
        return assets.modules[name];
      }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.client.assets.unload"></a>[function <span class="apidocSignatureSpan">socketstream.client.assets.</span>unload ()](#apidoc.element.socketstream.client.assets.unload)
- description and source-code
```javascript
unload = function () {
  assets.libs = [];
  assets.modules = {};
  assets.constants = {};
  assets.startCode = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.client.formatters"></a>[module socketstream.client.formatters](#apidoc.module.socketstream.client.formatters)

#### <a name="apidoc.element.socketstream.client.formatters.add"></a>[function <span class="apidocSignatureSpan">socketstream.client.formatters.</span>add (nameOrModule, config)](#apidoc.element.socketstream.client.formatters.add)
- description and source-code
```javascript
add = function (nameOrModule, config) {
  var formatter;
  config = config || {};
  switch(typeof nameOrModule) {
    case 'object':
      formatter = nameOrModule.init(ss.root, config, options);
      addCall(formatter);
      break;

    case 'function':
    case 'string':
      var mod = ss.require(nameOrModule, 'client/formatters',function(err) {
        throw new Error('The "'+err.id+'" formatter is not supported by '+
                'SocketStream internally. Please pass a compatible module instead');
      });
      formatter = mod(ss, config, options);
      addCall(formatter,true);
      break;
  }

  return mods.push(formatter);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.client.formatters.forget"></a>[function <span class="apidocSignatureSpan">socketstream.client.formatters.</span>forget ()](#apidoc.element.socketstream.client.formatters.forget)
- description and source-code
```javascript
forget = function () {
  mods.length = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.client.formatters.load"></a>[function <span class="apidocSignatureSpan">socketstream.client.formatters.</span>load ()](#apidoc.element.socketstream.client.formatters.load)
- description and source-code
```javascript
load = function () {
  var byExtension = {};
  mods.forEach(function (mod) {
    return mod.extensions.forEach(function (extension) {
      byExtension[extension] = mod;
    });
  });
  debug('Formatters supported by extension: %s', Object.keys(byExtension).join(','));
  return byExtension;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.client.templateEngine"></a>[module socketstream.client.templateEngine](#apidoc.module.socketstream.client.templateEngine)

#### <a name="apidoc.element.socketstream.client.templateEngine.forget"></a>[function <span class="apidocSignatureSpan">socketstream.client.templateEngine.</span>forget ()](#apidoc.element.socketstream.client.templateEngine.forget)
- description and source-code
```javascript
forget = function () {
  mods.length = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.client.templateEngine.generate"></a>[function <span class="apidocSignatureSpan">socketstream.client.templateEngine.</span>generate (bundler, files, cb)](#apidoc.element.socketstream.client.templateEngine.generate)
- description and source-code
```javascript
generate = function (bundler, files, cb) {
  var prevEngine = null;
  var templates = [];
  if (!(files && files.length > 0)) {
    cb('');
  }
  return files.forEach(function(desc) {
    // Work out which template engine to use, based upon the path (TODO split file.sep)
    var engine = selectEngine(desc.file) || defaultEngine;

    var formatter;
    if (engine.selectFormatter) {
      formatter = engine.selectFormatter(desc.file, ss.client.formatters, null);
    }

    var opts = {
      constants: bundler.constants(),
      locals: bundler.locals()
    };

    return bundler.format(desc,
      opts, formatter, function(output) {

      templates.push(wrapTemplate(output, desc.file, ss.bundler.clientFilePath(desc), opts, options, engine, prevEngine));
      prevEngine = engine;

      // Return if last template
      if (templates.length === files.length) {
        output = templates.join('');
        if (engine !== null && engine.suffix) {
          output += engine.suffix();
        }
        return cb(output);
      }
    }, function(err) {
      ss.log.clientIssue(client,options,err,desc);
      return cb('Couldn\'t format ' + desc.file + err.userInfoHTML);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.client.templateEngine.load"></a>[function <span class="apidocSignatureSpan">socketstream.client.templateEngine.</span>load ()](#apidoc.element.socketstream.client.templateEngine.load)
- description and source-code
```javascript
load = function () {
  var templateEngines = {};
  mods.forEach(function(mod) {
    return mod.dirs.forEach(function(dir) {
      templateEngines[dir] = mod.engine;
      return templateEngines[dir];
    });
  });
  return templateEngines;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.client.templateEngine.use"></a>[function <span class="apidocSignatureSpan">socketstream.client.templateEngine.</span>use (nameOrModule, dirs, config)](#apidoc.element.socketstream.client.templateEngine.use)
- description and source-code
```javascript
use = function (nameOrModule, dirs, config) {
  if (!dirs) {
    dirs = ['.'];
  }
  if (!(dirs instanceof Array)) {
    dirs = [dirs];
  }

  dirs = dirs.map(function(dir) {
    if (dir === '/') {
      return '.';
    }
    if (dir.charAt(0) === '/') {
      return path.join(options.dirs.templates.substring(1), dir.substring(1));
    }
    return path.join(options.dirs.client.substring(1), dir);
  });

  var mod = ss.require(nameOrModule, 'client/template_engines', function(err) {
    throw new Error('The ' + err.id + ' template engine is not supported by SocketStream internally '+
      'or found in the project packages. Please pass a compatible module instead');
  });
  var engine;
  if (typeof mod === 'function') {
    engine = mod(ss, config, options);
  } else {
    engine = mod.init(ss, config, options);
  }
  return mods.push({
    engine: engine,
    dirs: dirs
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.http"></a>[module socketstream.http](#apidoc.module.socketstream.http)

#### <a name="apidoc.element.socketstream.http.load"></a>[function <span class="apidocSignatureSpan">socketstream.http.</span>load ()](#apidoc.element.socketstream.http.load)
- description and source-code
```javascript
load = function () {
  this.cached.loadStatic();
  this.cached.loadAssets();
  debug('http: loaded.');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.http.route"></a>[function <span class="apidocSignatureSpan">socketstream.http.</span>route (url, fn)](#apidoc.element.socketstream.http.route)
- description and source-code
```javascript
route = function (url, fn) {
  if (fn && typeof fn === 'function') {
    this.cached.route(url, fn);
  } else {
    return {
      serveClient: (function(name) {
        this.cached.route(url,function(req, res) {
          return res.serveClient(name);
        });
      }).bind(this)
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.http.set"></a>[function <span class="apidocSignatureSpan">socketstream.http.</span>set (newSettings)](#apidoc.element.socketstream.http.set)
- description and source-code
```javascript
set = function (newSettings) {
  var s = '';

  if (typeof newSettings !== 'object') {
    throw new Error('ss.http.set() takes an object e.g. {static: {maxAge: 60000}}');
  }

  for (s in newSettings) {
    if (newSettings.hasOwnProperty(s)) {
      settings[s] = newSettings[s]
    }
  }
}
```
- example usage
```shell
...
  app.socketstream = function( fn(req,stream) )

  app.stream = ss.http.stream;
  */
  app.stream = ss.http.stream;

  if (ss.env === 'development') {
app.set('views', ss.client.dirs.views);
// Showing stack errors
app.set('showStackError', true);
// Disable views cache
app.set('view cache', false);

// Environment dependent middleware
// throws cannot find stack
...
```

#### <a name="apidoc.element.socketstream.http.unload"></a>[function <span class="apidocSignatureSpan">socketstream.http.</span>unload ()](#apidoc.element.socketstream.http.unload)
- description and source-code
```javascript
unload = function () {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.http.cached"></a>[module socketstream.http.cached](#apidoc.module.socketstream.http.cached)

#### <a name="apidoc.element.socketstream.http.cached.loadAssets"></a>[function <span class="apidocSignatureSpan">socketstream.http.cached.</span>loadAssets ()](#apidoc.element.socketstream.http.cached.loadAssets)
- description and source-code
```javascript
loadAssets = function () {
        var files = glob.sync('**/*',{cwd:ss.client.dirs.assets,nodir:true})
                      .map(assetPathServed)
                      .filter(function(p) { return p; }),
            prefix = '/assets/'; // should this be configurable?

        files.forEach(function(url) {
          route(prefix+url,null,path.join(ss.client.dirs.assets, url));
        });
				debug('route ready for assets %s', Object.keys(files))
	    }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.http.cached.loadStatic"></a>[function <span class="apidocSignatureSpan">socketstream.http.cached.</span>loadStatic ()](#apidoc.element.socketstream.http.cached.loadStatic)
- description and source-code
```javascript
loadStatic = function () {
  var assets = path.relative(ss.client.dirs.static,ss.client.dirs.assets);
  var files = glob.sync('**/*',{cwd:ss.client.dirs.static,nodir:true}).filter(function(p) {
    //TODO exclude directories
    return p.indexOf(assets) !== 0;
  });

  files.forEach(function(url) {
    route(url,null,path.join(ss.client.dirs.static, url));
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.http.cached.middleware"></a>[function <span class="apidocSignatureSpan">socketstream.http.cached.</span>middleware (req, res, next)](#apidoc.element.socketstream.http.cached.middleware)
- description and source-code
```javascript
function cachedMiddleware(req, res, next) {
		var point = getPoint(req);
		// console.log('cmw',point,req.url);
		if (point) {
			return point.handle(req,res,next);
		}
		next();
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.http.cached.route"></a>[function <span class="apidocSignatureSpan">socketstream.http.cached.</span>route (url, fn, filePath)](#apidoc.element.socketstream.http.cached.route)
- description and source-code
```javascript
function route(url, fn, filePath) {
		if (url.charAt(0) !== '/') { url = '/'+url; }
		// console.log('route defined',url);
		var point = getPoint(url);
		if (point) {
			if (fn) { point.handle = fn; }
			if (filePath) { point.filePath = filePath; }
		} else {
			point = new KnownPoint(url, fn, filePath);
			if (!fn) {
				debug('added known point %s pointing to static file %s',url,filePath);
			}
		}
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.http.cached.send"></a>[function <span class="apidocSignatureSpan">socketstream.http.cached.</span>send (url, res)](#apidoc.element.socketstream.http.cached.send)
- description and source-code
```javascript
function sendInternal(url, res) {
			if (url.charAt(0) !== '/') { url = '/'+url; }
			var point = getPoint(url);
			// console.log(url,res,'sent');
			if (point) {
				point.handle(res.req, res);
			} else {
				ss.log.error('Couldn\'t serve', url);
			}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.http.cached.set"></a>[function <span class="apidocSignatureSpan">socketstream.http.cached.</span>set (url, content, mimeType)](#apidoc.element.socketstream.http.cached.set)
- description and source-code
```javascript
function set(url, content, mimeType) {
			if (url.charAt(0) !== '/') { url = '/'+url; }
			var point = getPoint(url) || new KnownPoint(url);
			// console.info('new url:',url, mimeType);
			point.content = content;
			point.mimeType = mimeType;
}
```
- example usage
```shell
...
  app.socketstream = function( fn(req,stream) )

  app.stream = ss.http.stream;
  */
  app.stream = ss.http.stream;

  if (ss.env === 'development') {
app.set('views', ss.client.dirs.views);
// Showing stack errors
app.set('showStackError', true);
// Disable views cache
app.set('view cache', false);

// Environment dependent middleware
// throws cannot find stack
...
```



# <a name="apidoc.module.socketstream.http.session"></a>[module socketstream.http.session](#apidoc.module.socketstream.http.session)

#### <a name="apidoc.element.socketstream.http.session.middleware"></a>[function <span class="apidocSignatureSpan">socketstream.http.session.</span>middleware (req, res, next)](#apidoc.element.socketstream.http.session.middleware)
- description and source-code
```javascript
function sessionMiddleware(req, res, next) {
  return ss.session.strategy.sessionMiddleware? ss.session.strategy.sessionMiddleware(req,res,next) : next();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.livereload"></a>[module socketstream.livereload](#apidoc.module.socketstream.livereload)

#### <a name="apidoc.element.socketstream.livereload.added"></a>[function <span class="apidocSignatureSpan">socketstream.livereload.</span>added (changedPath)](#apidoc.element.socketstream.livereload.added)
- description and source-code
```javascript
added = function (changedPath) {
  return reloadClients(changedPath,'added');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.livereload.changed"></a>[function <span class="apidocSignatureSpan">socketstream.livereload.</span>changed (changedPath)](#apidoc.element.socketstream.livereload.changed)
- description and source-code
```javascript
changed = function (changedPath) {
  return reloadClients(changedPath,'changed');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.livereload.removed"></a>[function <span class="apidocSignatureSpan">socketstream.livereload.</span>removed (changedPath)](#apidoc.element.socketstream.livereload.removed)
- description and source-code
```javascript
removed = function (changedPath) {
  return reloadClients(changedPath,'removed');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.publish"></a>[module socketstream.publish](#apidoc.module.socketstream.publish)

#### <a name="apidoc.element.socketstream.publish.api"></a>[function <span class="apidocSignatureSpan">socketstream.publish.</span>api (transport)](#apidoc.element.socketstream.publish.api)
- description and source-code
```javascript
api = function (transport) {
  var methods = {

<span class="apidocCodeCommentSpan">    /**
     * @ngdoc function
     * @name ss.publish#all
     * @methodOf ss.publish:publish
     * @param {string} name Name of the event
     * @param {any} first First parameter (open ended)
     * @description
     * Publish event to all active client browsers
     */
</span>    all: function() {
      var event = arguments[0],
          params = (2 <= arguments.length ? __slice.call(arguments, 1) : []),
        obj = {
          t: 'all',
          e: event,
          p: params
        };
      transport.send(obj);
      if (!isInternal(event)) {
        return log.info('➙'.cyan, 'event:all'.grey, event);
      }
    },
    socketId: function() {
      var socketId = arguments[0],
          event = arguments[1],
          params = (3 <= arguments.length ? __slice.call(arguments, 2) : []),
          obj = {
            t: 'socketId',
            socketId: socketId,
            e: event,
            p: params
          };
      transport.send(obj);
      return log.info('➙'.cyan, ('event:socketId:' + socketId).grey, event);
    },
    users: function() {
      var users = arguments[0] instanceof Array? arguments[0] : [arguments[0]],
          event = arguments[1],
          params = (3 <= arguments.length ? __slice.call(arguments, 2) : []),
          obj = {
            t: 'user',
            users: users,
            e: event,
            p: params
          };
      transport.send(obj);
      return log.info('➙'.cyan, ('event:users:[' + (users.join(',')) + ']').grey, event);
    },

      /**
       * @ngdoc function
       * @name ss.publish#channel
       * @methodOf ss.publish:publish
       * @param {string|array} channel Name of the channel(s)
       * @param {string} event Name of the event
       * @param {any} first First parameter (open ended)
       * @description
       * Publish event to all active client browsers in given channel
       */
    channels: function() {
      var channels = arguments[0] instanceof Array? arguments[0] : [arguments[0]],
          event = arguments[1],
          params = (3 <= arguments.length ? __slice.call(arguments, 2) : []),
          obj = {
            t: 'channel',
            channels: channels,
            e: event,
            p: params
          };
      transport.send(obj);
      return log.info('➙'.cyan, ('event:channels:[' + (channels.join(',')) + ']').grey, event);
    }
  };

  // Alias 0.2 command
  methods.broadcast = methods.all;
  // Alias singles to plurals
  methods.channel = methods.channels;
  methods.user = methods.users;

  // Return all methods
  return methods;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.publish.transport"></a>[module socketstream.publish.transport](#apidoc.module.socketstream.publish.transport)

#### <a name="apidoc.element.socketstream.publish.transport.load"></a>[function <span class="apidocSignatureSpan">socketstream.publish.transport.</span>load ()](#apidoc.element.socketstream.publish.transport.load)
- description and source-code
```javascript
load = function () {
  if (!transport) {
    this.use('internal');
  }
  return transport(config); //TODO should this be (ss,config) ?
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.publish.transport.use"></a>[function <span class="apidocSignatureSpan">socketstream.publish.transport.</span>use (nameOrModule, cfg)](#apidoc.element.socketstream.publish.transport.use)
- description and source-code
```javascript
use = function (nameOrModule, cfg) {
  var modPath;
  if (!cfg) {
    cfg = {};
  }
  config = cfg;
  transport = (function() {
    if (typeof nameOrModule === 'function') {
      return nameOrModule;
    } else {
      modPath = './transports/' + nameOrModule;
      if (require.resolve(modPath)) {
        return require(modPath);
      } else {
        throw new Error('Unable to find Publish Event Transport \'' + nameOrModule + '\' internally. Please pass a module');
      }
    }
  })();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.responders"></a>[module socketstream.responders](#apidoc.module.socketstream.responders)

#### <a name="apidoc.element.socketstream.responders.add"></a>[function <span class="apidocSignatureSpan">socketstream.responders.</span>add (nameOrModule, config)](#apidoc.element.socketstream.responders.add)
- description and source-code
```javascript
add = function (nameOrModule, config) {
  config = config || null;
  var mod = ss.require(nameOrModule, 'request/responders',function(err) {
        throw new Error('Unable to find the \''+err.id+'\' Request Responder internally');
      });

  try {
    var id = nameOrModule === 'events' && '0' || ++responderCount;
    //jshint -W093
    return (responders[id] = mod(id, config, ss));
  } catch (e) {
    var responderName = responders[id] && responders[id].name || '',
        err = new Error('Unable to initialize Request Responder \'' + responderName + '\'');
    err.stack = e.stack;
    throw e;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.responders.clear"></a>[function <span class="apidocSignatureSpan">socketstream.responders.</span>clear ()](#apidoc.element.socketstream.responders.clear)
- description and source-code
```javascript
clear = function () {
  //jshint -W093
  return (useDefaults = false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.responders.load"></a>[function <span class="apidocSignatureSpan">socketstream.responders.</span>load ()](#apidoc.element.socketstream.responders.load)
- description and source-code
```javascript
load = function () {
  var middlewareStack = middleware.load();
  if (useDefaults) {
    this.add('events');
    this.add('rpc');
  }
  var output = {};
  for (var id in responders) {
    var responder = responders[id];
    output[id] = {
      name: responder.name,
      interfaces: responder.interfaces(middlewareStack)
    };
  }
  return output;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.session"></a>[module socketstream.session](#apidoc.module.socketstream.session)

#### <a name="apidoc.element.socketstream.session.Cookie"></a>[function <span class="apidocSignatureSpan">socketstream.session.</span>Cookie (options)](#apidoc.element.socketstream.session.Cookie)
- description and source-code
```javascript
function Cookie(options) {
  this.path = '/';
  this.maxAge = null;
  this.httpOnly = true;
  if (options) {merge(this, options);}
  this.originalMaxAge = undefined === this.originalMaxAge ?
      this.maxAge :
      this.originalMaxAge;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.MemoryStore"></a>[function <span class="apidocSignatureSpan">socketstream.session.</span>MemoryStore ()](#apidoc.element.socketstream.session.MemoryStore)
- description and source-code
```javascript
function MemoryStore() {
  Store.call(this)
  this.sessions = Object.create(null)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.Session"></a>[function <span class="apidocSignatureSpan">socketstream.session.</span>Session (req, data)](#apidoc.element.socketstream.session.Session)
- description and source-code
```javascript
function Session(req, data) {
  Object.defineProperty(this, 'req', { value: req });
  Object.defineProperty(this, 'id', { value: req.sessionID });

  if (typeof data === 'object' && data !== null) {
    // merge data into this, ignoring prototype properties
    for (var prop in data) {
      if (!(prop in this)) {
        this[prop] = data[prop]
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.Store"></a>[function <span class="apidocSignatureSpan">socketstream.session.</span>Store ()](#apidoc.element.socketstream.session.Store)
- description and source-code
```javascript
function Store(){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.create"></a>[function <span class="apidocSignatureSpan">socketstream.session.</span>create ()](#apidoc.element.socketstream.session.create)
- description and source-code
```javascript
create = function () {
  var sessionId = uuid.v1();
  this.strategy.create(sessionId);
  debug('created session %s',sessionId);
  return sessionId;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.extractSocketSessionToken"></a>[function <span class="apidocSignatureSpan">socketstream.session.</span>extractSocketSessionToken (request)](#apidoc.element.socketstream.session.extractSocketSessionToken)
- description and source-code
```javascript
extractSocketSessionToken = function (request) {
  if (!this.strategy.extractSocketSessionToken) {
    throw new Error('No session strategy defined! Did you forget to "npm install socketstream-cookie-session" ?');
  }
  var id = this.strategy.extractSocketSessionToken(request, this.options);
  debug('extracted session id %s',id);
  return id;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.find"></a>[function <span class="apidocSignatureSpan">socketstream.session.</span>find (sessionId, socketId, cb)](#apidoc.element.socketstream.session.find)
- description and source-code
```javascript
find = function (sessionId, socketId, cb) {
  return api.store.get().load(sessionId, function(err, session) {
    // Create a new session if we don't have this sessionId in memory
    // Note: in production you should be using Redis or another
    // persistent store so this should rarely happen
    if (!session) {
      session = strategy.create(sessionId);
      debug('created session for %s',sessionId);
    } else {
      debug('using existing session for %s',sessionId);
    }

    // Append methods to session object
    session.channel = channels(ss, session, socketId);
    session.setUserId = function(userId, cb) {
      if (!cb) {
        cb = function() {};
      }
      if (userId) {
        this.userId = userId;
        this._bindToSocket();
      } else if (this.userId) {  // if null (i.e. user has signed out)
        subscriptions.user.remove(this.userId, socketId);
        delete this.userId;
      }
      return this.save(cb);
    };

    // Bind username and any channel subscriptions to this socketID on each request
    session._bindToSocket = function() {
      if (session.userId) {
        subscriptions.user.add(session.userId, socketId);
      }
      if ((session.channels) && session.channels.length > 0) {
        session.channel._bindToSocket();
      }
      return this;
    };
    session.save = function(cb) {
      return sessionStore.set(sessionId, session, cb);
    };
    session._bindToSocket();
    return cb(session);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.setStrategy"></a>[function <span class="apidocSignatureSpan">socketstream.session.</span>setStrategy (_strategy)](#apidoc.element.socketstream.session.setStrategy)
- description and source-code
```javascript
setStrategy = function (_strategy) {
  this.strategy = strategy = _strategy;
  debug('session strategy defined.');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.session.Cookie"></a>[module socketstream.session.Cookie](#apidoc.module.socketstream.session.Cookie)

#### <a name="apidoc.element.socketstream.session.Cookie.Cookie"></a>[function <span class="apidocSignatureSpan">socketstream.session.</span>Cookie (options)](#apidoc.element.socketstream.session.Cookie.Cookie)
- description and source-code
```javascript
function Cookie(options) {
  this.path = '/';
  this.maxAge = null;
  this.httpOnly = true;
  if (options) {merge(this, options);}
  this.originalMaxAge = undefined === this.originalMaxAge ?
      this.maxAge :
      this.originalMaxAge;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.session.Cookie.prototype"></a>[module socketstream.session.Cookie.prototype](#apidoc.module.socketstream.session.Cookie.prototype)

#### <a name="apidoc.element.socketstream.session.Cookie.prototype.serialize"></a>[function <span class="apidocSignatureSpan">socketstream.session.Cookie.prototype.</span>serialize (name, val)](#apidoc.element.socketstream.session.Cookie.prototype.serialize)
- description and source-code
```javascript
serialize = function (name, val){
  return cookie.serialize(name, val, this.data);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.Cookie.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">socketstream.session.Cookie.prototype.</span>toJSON ()](#apidoc.element.socketstream.session.Cookie.prototype.toJSON)
- description and source-code
```javascript
toJSON = function (){
  return this.data;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.session.MemoryStore"></a>[module socketstream.session.MemoryStore](#apidoc.module.socketstream.session.MemoryStore)

#### <a name="apidoc.element.socketstream.session.MemoryStore.MemoryStore"></a>[function <span class="apidocSignatureSpan">socketstream.session.</span>MemoryStore ()](#apidoc.element.socketstream.session.MemoryStore.MemoryStore)
- description and source-code
```javascript
function MemoryStore() {
  Store.call(this)
  this.sessions = Object.create(null)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.session.MemoryStore.prototype"></a>[module socketstream.session.MemoryStore.prototype](#apidoc.module.socketstream.session.MemoryStore.prototype)

#### <a name="apidoc.element.socketstream.session.MemoryStore.prototype.all"></a>[function <span class="apidocSignatureSpan">socketstream.session.MemoryStore.prototype.</span>all (callback)](#apidoc.element.socketstream.session.MemoryStore.prototype.all)
- description and source-code
```javascript
function all(callback) {
  var sessionIds = Object.keys(this.sessions)
  var sessions = Object.create(null)

  for (var i = 0; i < sessionIds.length; i++) {
    var sessionId = sessionIds[i]
    var session = getSession(this.sessions, sessionId)

    if (session) {
      sessions[sessionId] = session;
    }
  }

  if (callback) {
     defer(callback, null, sessions);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.MemoryStore.prototype.clear"></a>[function <span class="apidocSignatureSpan">socketstream.session.MemoryStore.prototype.</span>clear (callback)](#apidoc.element.socketstream.session.MemoryStore.prototype.clear)
- description and source-code
```javascript
function clear(callback) {
  this.sessions = Object.create(null)
  if (callback) {
     defer(callback);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.MemoryStore.prototype.destroy"></a>[function <span class="apidocSignatureSpan">socketstream.session.MemoryStore.prototype.</span>destroy (sessionId, callback)](#apidoc.element.socketstream.session.MemoryStore.prototype.destroy)
- description and source-code
```javascript
function destroy(sessionId, callback) {
  delete this.sessions[sessionId]
  if (callback) {
     defer(callback);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.MemoryStore.prototype.get"></a>[function <span class="apidocSignatureSpan">socketstream.session.MemoryStore.prototype.</span>get (sessionId, callback)](#apidoc.element.socketstream.session.MemoryStore.prototype.get)
- description and source-code
```javascript
function get(sessionId, callback) {
  defer(callback, null, getSession(this.sessions, sessionId))
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.MemoryStore.prototype.length"></a>[function <span class="apidocSignatureSpan">socketstream.session.MemoryStore.prototype.</span>length (callback)](#apidoc.element.socketstream.session.MemoryStore.prototype.length)
- description and source-code
```javascript
function length(callback) {
  this.all(function (err, sessions) {
    if (err) { return callback(err); }
    callback(null, Object.keys(sessions).length)
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.MemoryStore.prototype.set"></a>[function <span class="apidocSignatureSpan">socketstream.session.MemoryStore.prototype.</span>set (sessionId, session, callback)](#apidoc.element.socketstream.session.MemoryStore.prototype.set)
- description and source-code
```javascript
function set(sessionId, session, callback) {
  this.sessions[sessionId] = JSON.stringify(session)
  if (callback) {
     defer(callback);
  }
}
```
- example usage
```shell
...
  app.socketstream = function( fn(req,stream) )

  app.stream = ss.http.stream;
  */
  app.stream = ss.http.stream;

  if (ss.env === 'development') {
app.set('views', ss.client.dirs.views);
// Showing stack errors
app.set('showStackError', true);
// Disable views cache
app.set('view cache', false);

// Environment dependent middleware
// throws cannot find stack
...
```

#### <a name="apidoc.element.socketstream.session.MemoryStore.prototype.touch"></a>[function <span class="apidocSignatureSpan">socketstream.session.MemoryStore.prototype.</span>touch (sessionId, session, callback)](#apidoc.element.socketstream.session.MemoryStore.prototype.touch)
- description and source-code
```javascript
function touch(sessionId, session, callback) {
  var currentSession = getSession(this.sessions, sessionId)

  if (currentSession) {
    // update expiration
    currentSession.cookie = session.cookie
    this.sessions[sessionId] = JSON.stringify(currentSession)
  }

  if (callback) {
     defer(callback);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.session.Session"></a>[module socketstream.session.Session](#apidoc.module.socketstream.session.Session)

#### <a name="apidoc.element.socketstream.session.Session.Session"></a>[function <span class="apidocSignatureSpan">socketstream.session.</span>Session (req, data)](#apidoc.element.socketstream.session.Session.Session)
- description and source-code
```javascript
function Session(req, data) {
  Object.defineProperty(this, 'req', { value: req });
  Object.defineProperty(this, 'id', { value: req.sessionID });

  if (typeof data === 'object' && data !== null) {
    // merge data into this, ignoring prototype properties
    for (var prop in data) {
      if (!(prop in this)) {
        this[prop] = data[prop]
      }
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.session.Session.prototype"></a>[module socketstream.session.Session.prototype](#apidoc.module.socketstream.session.Session.prototype)

#### <a name="apidoc.element.socketstream.session.Session.prototype.destroy"></a>[function <span class="apidocSignatureSpan">socketstream.session.Session.prototype.</span>destroy (fn)](#apidoc.element.socketstream.session.Session.prototype.destroy)
- description and source-code
```javascript
destroy = function (fn){
  delete this.req.session;
  this.req.sessionStore.destroy(this.id, fn);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.Session.prototype.regenerate"></a>[function <span class="apidocSignatureSpan">socketstream.session.Session.prototype.</span>regenerate (fn)](#apidoc.element.socketstream.session.Session.prototype.regenerate)
- description and source-code
```javascript
regenerate = function (fn){
  this.req.sessionStore.regenerate(this.req, fn);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.Session.prototype.reload"></a>[function <span class="apidocSignatureSpan">socketstream.session.Session.prototype.</span>reload (fn)](#apidoc.element.socketstream.session.Session.prototype.reload)
- description and source-code
```javascript
reload = function (fn){
  var req = this.req
    , store = this.req.sessionStore;
  store.get(this.id, function(err, sess){
    if (err) {return fn(err);}
    if (!sess) {return fn(new Error('failed to load session'));}
    store.createSession(req, sess);
    fn();
  });
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.Session.prototype.resetMaxAge"></a>[function <span class="apidocSignatureSpan">socketstream.session.Session.prototype.</span>resetMaxAge ()](#apidoc.element.socketstream.session.Session.prototype.resetMaxAge)
- description and source-code
```javascript
resetMaxAge = function (){
  this.cookie.maxAge = this.cookie.originalMaxAge;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.Session.prototype.save"></a>[function <span class="apidocSignatureSpan">socketstream.session.Session.prototype.</span>save (fn)](#apidoc.element.socketstream.session.Session.prototype.save)
- description and source-code
```javascript
save = function (fn){
  this.req.sessionStore.set(this.id, this, fn || function(){});
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.Session.prototype.touch"></a>[function <span class="apidocSignatureSpan">socketstream.session.Session.prototype.</span>touch ()](#apidoc.element.socketstream.session.Session.prototype.touch)
- description and source-code
```javascript
touch = function (){
  return this.resetMaxAge();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.session.Store"></a>[module socketstream.session.Store](#apidoc.module.socketstream.session.Store)

#### <a name="apidoc.element.socketstream.session.Store.Store"></a>[function <span class="apidocSignatureSpan">socketstream.session.</span>Store ()](#apidoc.element.socketstream.session.Store.Store)
- description and source-code
```javascript
function Store(){}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.session.Store.prototype"></a>[module socketstream.session.Store.prototype](#apidoc.module.socketstream.session.Store.prototype)

#### <a name="apidoc.element.socketstream.session.Store.prototype.createSession"></a>[function <span class="apidocSignatureSpan">socketstream.session.Store.prototype.</span>createSession (req, sess)](#apidoc.element.socketstream.session.Store.prototype.createSession)
- description and source-code
```javascript
createSession = function (req, sess){
  var expires = sess.cookie.expires
    , orig = sess.cookie.originalMaxAge;
  sess.cookie = new Cookie(sess.cookie);
  if ('string' === typeof expires) { sess.cookie.expires = new Date(expires); }
  sess.cookie.originalMaxAge = orig;
  req.session = new Session(req, sess);
  return req.session;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.Store.prototype.load"></a>[function <span class="apidocSignatureSpan">socketstream.session.Store.prototype.</span>load (sid, fn)](#apidoc.element.socketstream.session.Store.prototype.load)
- description and source-code
```javascript
load = function (sid, fn){
  var self = this;
  this.get(sid, function(err, sess){
    if (err) { debug('failed to get %s',sid); return fn(err); }
    if (!sess) { debug('no session for %s',sid); return fn(); }
    var req = { sessionID: sid, sessionStore: self };
    sess = self.createSession(req, sess); // recreate prototypes on persisted data
    fn(null, sess);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.Store.prototype.regenerate"></a>[function <span class="apidocSignatureSpan">socketstream.session.Store.prototype.</span>regenerate (req, fn)](#apidoc.element.socketstream.session.Store.prototype.regenerate)
- description and source-code
```javascript
regenerate = function (req, fn){
  var self = this;
  this.destroy(req.sessionID, function(err){
    self.generate(req);
    fn(err);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.session.store"></a>[module socketstream.session.store](#apidoc.module.socketstream.session.store)

#### <a name="apidoc.element.socketstream.session.store.get"></a>[function <span class="apidocSignatureSpan">socketstream.session.store.</span>get ()](#apidoc.element.socketstream.session.store.get)
- description and source-code
```javascript
get = function () {
  if (sessionStore == null) {
    // notify user that this store is not
    // meant for a production environment
    if ('production' === ss.env) {
      ss.log.warn(warning);
    }
    // Define default session store (no default impl for now, is set in session strategy addon socketstream-cookie-session)
    sessionStore = new api.MemoryStore();
    debug('Using MemoryStore for ss.session.store');
  }
  return sessionStore;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.session.store.use"></a>[function <span class="apidocSignatureSpan">socketstream.session.store.</span>use (nameOrStore, options)](#apidoc.element.socketstream.session.store.use)
- description and source-code
```javascript
use = function (nameOrStore, options) {
  var RedisStore;
  debug('Using %s Store for ss.session.store',nameOrStore==='redis'?'Redis':'Custom');
  // Allow any Connect Session Store *instance* to be used
  //jshint -W093
  return (sessionStore = nameOrStore === 'redis' ?
    (RedisStore = ss.require('connect-redis')(api), new RedisStore(options)) :
    nameOrStore);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.tasks"></a>[module socketstream.tasks](#apidoc.module.socketstream.tasks)

#### <a name="apidoc.element.socketstream.tasks._packTasks"></a>[function <span class="apidocSignatureSpan">socketstream.tasks.</span>_packTasks (all)](#apidoc.element.socketstream.tasks._packTasks)
- description and source-code
```javascript
_packTasks = function (all) {
  var tasks = all? ['load-api']:['pack-prepare','load-api'];
  ss.bundler.forEach(function(bundler){
    if (all) {
      tasks.push(bundler.client.name + ':pack');
    } else if (bundler.packNeeded) {
      tasks.push(bundler.client.name + ':pack-needed');
      tasks.push(bundler.client.name + ':pack');
    } else {
      tasks.push(bundler.client.name + ':pack-unneeded');
    }
  });
  return tasks;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.tasks.add"></a>[function <span class="apidocSignatureSpan">socketstream.tasks.</span>add (name, dependents, fn)](#apidoc.element.socketstream.tasks.add)
- description and source-code
```javascript
function task(name, dependents, fn) {
  orchestrator.add(name, dependents, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.tasks.defaultTask"></a>[function <span class="apidocSignatureSpan">socketstream.tasks.</span>defaultTask (name, dependents, fn)](#apidoc.element.socketstream.tasks.defaultTask)
- description and source-code
```javascript
function defaultTask(name, dependents, fn) {
  if (!orchestrator.hasTask(name)) {
    orchestrator.add(name, dependents, fn);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.tasks.defaults"></a>[function <span class="apidocSignatureSpan">socketstream.tasks.</span>defaults ()](#apidoc.element.socketstream.tasks.defaults)
- description and source-code
```javascript
defaults = function () {
  ss.defaultTask('application', function() {});

  ss.defaultTask('start-server',['application'],function(done) {
    socketstream.ws.listen(ss.http.settings.port || 3000, done);
  });

  ss.defaultTask('load-api', function() {
    ss.load();
  });

  ss.defaultTask('test-socketstream', ['load-api'], function() {
    var sessionID = ss.session.create();

    // jshint loopfunc:true
    for (var id in ss.server.responders) {
      if (ss.server.responders.hasOwnProperty(id)) {
        var responder = ss.server.responders[id];

        if (responder.name && responder.interfaces.internal) {
          var fn = function(){
            var args = Array.prototype.slice.call(arguments),
                cb = args.pop();

            return responder.interfaces.internal(args, {sessionId: sessionID, transport: 'test'}, function(err, params){ cb(params
); });
          };
          ss.add(responder.name, fn); // interesting, potential or hack?
        }
      }
    }
  });

  // task: ondemand
  // Listen out for requests to async load new assets
  ss.defaultTask('serve', function serveOndemand(done) {
    ss.bundler.updateCachedOndemandAssets(); //TODO pipe to cache

    socketstream.ws.listen(ss.http.settings.port || 3000);

    // Send server instance to any registered modules (e.g. console)
    ss.events.emit('server:start', ss.server);

    process.on('exit', function() {
      if (done) {
        done();
      }
      ss.events.emit('server:stop', ss.server);
      if (orchestrator.hasTask('stop-server')) {
          orchestrator.start('stop-server',function() {
            ss.server = null;
          });
      }
    });
  });

  ss.defaultTask('live-assets', function() {
    ss.load();
    //TODO ss.started promise to wait for. resolved when streaming server is started
    ss.bundler.forEach(function(bundler) {
      bundler.updateCachedDevAssets();
    });
  });

  ss.defaultTask('live-reload', function() {
    liveReload(ss, options);
  });

  ss.defaultTask('stop-server', function() {
    if (ss.server.httServer) {
      ss.server.httServer.close(); //TODO do it on ss.ws
      debug('stopped http server.');
    }
  });

  var defaultDeps = [];

  if (options.packedAssets) {
    defaultDeps.push(options.packedAssets.all? 'pack-all':'pack-if-needed');
  } else if (!options.servePacked) {
    defaultDeps.push('live-assets');
  }
  if (options.liveReload) {
    defaultDeps.push('live-reload');
  }
  // if (httpServer)
  defaultDeps.push('serve');

  ss.defaultTask('default',defaultDeps);

  ss.bundler.forEach(function(bundler) {
    var name = bundler.client.name;
    ss.defaultTask(name+':pack-unneeded', function() {
      log.info('✓'.green, ('Serving client \'' + name + '\' using pre-packed assets (ID ' +
          bundler.client.id + ')').grey);
    });
    ss.defaultTask(name+':pack-needed', function() {
      log.info('!'.red, ('Unable to find pre-packed assets for \'' +
          name + '\'. All assets will be repacked').grey);
    });
    ss.defaultTask(name+':pack-prepare', function(done) {
      bundler.client.pack = true;
      log.info(('Pre-packing and minifying the \'' + name + '\' client...').yellow);

      // Prepare folder
      mkdir(bundler.dests.containerDir); //TODO async
      mkdir(bundler.dests.dir);
      if (!(options.packedAssets && options.packedAssets.keepOldFiles)) {
        deleteOldFiles(bundler.dests.dir);
      }
      done();

      //TODO add the tasks to an async queue that can be asserted on in tests
    });

    ss.defaultTask(bundler.client.name+':pack-css', function(done) {
      ss.bundler.packAssetSet('css', bundler.client, bundler.toMinifiedCSS,done);
    });

    ss.defaultTask(bundler.client.name+':pack-js', function(done) {
      //TODO wait for ss.loaded promise to have socketstream-transport defined
      ss.bundler.packAssetSet('js', bundler.client, bundler.toMinifiedJS,done);
    });

    ss.defaultTask(bundler.client.name+':pack-html', function(done) {
      view(ss, bundler.client, options, function(html) {
        fs.writeFileSync(bundler.dests.paths.html, ht ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.tasks.forget"></a>[function <span class="apidocSignatureSpan">socketstream.tasks.</span>forget ()](#apidoc.element.socketstream.tasks.forget)
- description and source-code
```javascript
forget = function () {
  for(var n in orchestrator.tasks) {
    delete orchestrator.tasks[n];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.tasks.on"></a>[function <span class="apidocSignatureSpan">socketstream.tasks.</span>on ()](#apidoc.element.socketstream.tasks.on)
- description and source-code
```javascript
on = function () {
  orchestrator.on.apply(orchestrator,arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.tasks.plan"></a>[function <span class="apidocSignatureSpan">socketstream.tasks.</span>plan (args)](#apidoc.element.socketstream.tasks.plan)
- description and source-code
```javascript
plan = function (args) {
  var plan = {}, httpServer = args[0];
  plan.targets = Array.prototype.slice.call(args);
  if (args.length === 0 || typeof httpServer === 'string' || httpServer instanceof Array) {
    plan.httpServer = null;
  } else {
    plan.httpServer = httpServer;
    plan.targets.shift();
  }
  var last = plan.targets[plan.targets.length-1];
  if (typeof last === 'function') {
    plan.callback = last;
    plan.targets.pop();
  }
  if (plan.targets[0] instanceof Array) {
    plan.targets = plan.targets[0];
  }
  if (plan.targets.length === 0) {
    plan.targets.push('default');
  }

  return plan;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.tasks.start"></a>[function <span class="apidocSignatureSpan">socketstream.tasks.</span>start (tasks, done)](#apidoc.element.socketstream.tasks.start)
- description and source-code
```javascript
start = function (tasks, done) {
  orchestrator.start(tasks, doneIfAllDone);
  return this;

  function doneIfAllDone(err) {
    if (err) {
      log.error('!'.red, 'task failed', err);
    }

    if (!orchestrator.isRunning && done) {
      done(err);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.tasks.unload"></a>[function <span class="apidocSignatureSpan">socketstream.tasks.</span>unload ()](#apidoc.element.socketstream.tasks.unload)
- description and source-code
```javascript
unload = function () {
  liveReload.unload();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.tasks.use"></a>[function <span class="apidocSignatureSpan">socketstream.tasks.</span>use (gulp)](#apidoc.element.socketstream.tasks.use)
- description and source-code
```javascript
use = function (gulp) {
  orchestrator = this.orchestrator = gulp;
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.ws"></a>[module socketstream.ws](#apidoc.module.socketstream.ws)

#### <a name="apidoc.element.socketstream.ws.listen"></a>[function <span class="apidocSignatureSpan">socketstream.ws.</span>listen (port, cb)](#apidoc.element.socketstream.ws.listen)
- description and source-code
```javascript
listen = function (port, cb) {
  ss.load();
  ss.log.info('Starting SocketStream %s in %s mode...'.green, ss.version, ss.env);
  if (Number(ss.version.split('.')[1]) % 2) {
    ss.log.info('This is an unstable version, some features will not be reliable'.yellow);
  }
  return transport.http.listen(port,function() {
    debug('started streaming server.');
    if (cb) {
      return cb();
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.ws.load"></a>[function <span class="apidocSignatureSpan">socketstream.ws.</span>load (responders, eventTransport)](#apidoc.element.socketstream.ws.load)
- description and source-code
```javascript
load = function (responders, eventTransport) {
  var thisTransport = transport.load();

  // Dispatch incoming events to websocket clients
  require('./event_dispatcher')(eventTransport, thisTransport, emitter);

  // Listen to incoming requests and invoke server.request
  for (var id in responders) {
    var responder = responders[id];
    emitter.on(id, responder.interfaces.websocket);
  }

  // Return active WS transport
  return thisTransport;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.ws.unload"></a>[function <span class="apidocSignatureSpan">socketstream.ws.</span>unload ()](#apidoc.element.socketstream.ws.unload)
- description and source-code
```javascript
unload = function () {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socketstream.ws.transport"></a>[module socketstream.ws.transport](#apidoc.module.socketstream.ws.transport)

#### <a name="apidoc.element.socketstream.ws.transport.load"></a>[function <span class="apidocSignatureSpan">socketstream.ws.transport.</span>load ()](#apidoc.element.socketstream.ws.transport.load)
- description and source-code
```javascript
load = function () {
  //TODO error handle missing require from within the sockjs/engineio module
  var transport = ss.require(mid, 'websocket/transports', 'engineio');
  if (typeof transport !== 'function') {
    ss.log.error('Transport for "'+mid+'" must be a function(ss, emitter, config) default:', transport);
  } else {
    return (active = transport(ss, emitter, config));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socketstream.ws.transport.use"></a>[function <span class="apidocSignatureSpan">socketstream.ws.transport.</span>use (nameOrModule, cfg)](#apidoc.element.socketstream.ws.transport.use)
- description and source-code
```javascript
use = function (nameOrModule, cfg) {
  mid = nameOrModule;
  config = cfg || config;

  // log warning
  // if (ss.require.resolve(nameOrModule, 'websocket/transports') == null) {
  //   throw new Error('Unable to find the \'' + nameOrModule + '\' websocket transport internally');
  // }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
