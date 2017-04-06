# api documentation for  [baconjs (v0.7.92)](https://github.com/baconjs/bacon.js)  [![npm package](https://img.shields.io/npm/v/npmdoc-baconjs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-baconjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-baconjs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-baconjs)
#### A small functional reactive programming lib for JavaScript.

[![NPM](https://nodei.co/npm/baconjs.png?downloads=true)](https://www.npmjs.com/package/baconjs)

[![apidoc](https://npmdoc.github.io/node-npmdoc-baconjs/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-baconjs_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-baconjs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-baconjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-baconjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Juha Paananen",
        "email": "juha.paananen@gmail.com",
        "url": "https://twitter.com/raimohanska"
    },
    "bugs": {
        "url": "https://github.com/baconjs/bacon.js/issues"
    },
    "contributors": [
        {
            "name": "Daniel K",
            "email": "x.flowwolf@gmail.com",
            "url": "https://twitter.com/xflowwolf"
        }
    ],
    "dependencies": {},
    "description": "A small functional reactive programming lib for JavaScript.",
    "devDependencies": {
        "babel": "^5.8.23",
        "benchmark": "1.0.0",
        "bluebird": "^2",
        "bower-json": "^0.6.0",
        "browserify": "^11.2.0",
        "browserstack-runner": "^0.3.8",
        "chai": "^3.3.0",
        "coffee-script": "^1.9.1",
        "coffeeify": "^1.0.0",
        "coffeelint": "^1.9.2",
        "es6-promise": "^3.0.2",
        "escodegen": "^1.6.1",
        "esprima": "^2.0.0",
        "estraverse": "^1.9.1",
        "git-rev": "^0.2.1",
        "github": "^0.2.4",
        "grunt": "0.4",
        "grunt-cli": "0.1.13",
        "grunt-coffeelint": "0.0.13",
        "grunt-contrib-clean": "^0.6.0",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-eslint": "^17.2.0",
        "grunt-shell": "^1.1.2",
        "jasmine-node": "^1.14.5",
        "jquery": "^2.1.4",
        "jsstana": "^0.1.5",
        "lodash": "^4.0.0",
        "mocha": "^2.1.0",
        "rxjs": "^5.2.0",
        "shelljs": "^0.5.3",
        "sinon": "^1.12.2",
        "uglify-js": "^2.4.16",
        "when": "^3.6.4",
        "zen-observable": "^0.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "30dee0d9f841cc71b59f67bdced7c13008b485f3",
        "tarball": "https://registry.npmjs.org/baconjs/-/baconjs-0.7.92.tgz"
    },
    "gitHead": "cecb2b5740a7716e5bbddbcd25df9dd970458072",
    "homepage": "https://github.com/baconjs/bacon.js",
    "keywords": [
        "bacon.js",
        "bacon",
        "frp",
        "functional",
        "reactive",
        "programming",
        "stream",
        "streams",
        "EventStream",
        "Rx",
        "RxJs",
        "Observable"
    ],
    "license": "MIT",
    "main": "dist/Bacon.js",
    "maintainers": [
        {
            "name": "raimohanska",
            "email": "juha.paananen@gmail.com"
        },
        {
            "name": "pnex2000",
            "email": "pnex2000@gmail.com"
        }
    ],
    "name": "baconjs",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/baconjs/bacon.js.git"
    },
    "scripts": {
        "pre-publish": "grunt",
        "test": "./runtests"
    },
    "version": "0.7.92"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module baconjs](#apidoc.module.baconjs)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Bus ()](#apidoc.element.baconjs.Bus)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>CompositeUnsubscribe ()](#apidoc.element.baconjs.CompositeUnsubscribe)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Desc (context, method, args)](#apidoc.element.baconjs.Desc)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Dispatcher (_subscribe, _handleEvent)](#apidoc.element.baconjs.Dispatcher)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>End ()](#apidoc.element.baconjs.End)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Error (error)](#apidoc.element.baconjs.Error)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Event ()](#apidoc.element.baconjs.Event)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>EventStream (desc, subscribe, handler)](#apidoc.element.baconjs.EventStream)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Initial (valueF, eager)](#apidoc.element.baconjs.Initial)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Next (valueF, eager)](#apidoc.element.baconjs.Next)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Observable (desc)](#apidoc.element.baconjs.Observable)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Property (desc, subscribe, handler)](#apidoc.element.baconjs.Property)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>combineAsArray ()](#apidoc.element.baconjs.combineAsArray)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>combineTemplate (template)](#apidoc.element.baconjs.combineTemplate)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>combineWith ()](#apidoc.element.baconjs.combineWith)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>constant (value)](#apidoc.element.baconjs.constant)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>fromArray (values)](#apidoc.element.baconjs.fromArray)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>fromBinder (binder)](#apidoc.element.baconjs.fromBinder)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>fromCallback (f)](#apidoc.element.baconjs.fromCallback)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>fromESObservable (_observable)](#apidoc.element.baconjs.fromESObservable)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>fromEvent (target, eventName, eventTransformer)](#apidoc.element.baconjs.fromEvent)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>fromEventTarget (target, eventName, eventTransformer)](#apidoc.element.baconjs.fromEventTarget)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>fromNodeCallback (f)](#apidoc.element.baconjs.fromNodeCallback)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>fromPoll (delay, poll)](#apidoc.element.baconjs.fromPoll)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>fromPromise (promise, abort)](#apidoc.element.baconjs.fromPromise)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>groupSimultaneous ()](#apidoc.element.baconjs.groupSimultaneous)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>interval (delay)](#apidoc.element.baconjs.interval)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>later (delay, value)](#apidoc.element.baconjs.later)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>mergeAll ()](#apidoc.element.baconjs.mergeAll)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>never ()](#apidoc.element.baconjs.never)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>onValues ()](#apidoc.element.baconjs.onValues)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>once (value)](#apidoc.element.baconjs.once)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>repeat (generator)](#apidoc.element.baconjs.repeat)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>repeatedly (delay, values)](#apidoc.element.baconjs.repeatedly)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>retry (options)](#apidoc.element.baconjs.retry)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>sequentially (delay, values)](#apidoc.element.baconjs.sequentially)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>spy (spy)](#apidoc.element.baconjs.spy)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>try (f)](#apidoc.element.baconjs.try)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>update (initial)](#apidoc.element.baconjs.update)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>when ()](#apidoc.element.baconjs.when)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>zipAsArray ()](#apidoc.element.baconjs.zipAsArray)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>zipWith ()](#apidoc.element.baconjs.zipWith)
1.  object <span class="apidocSignatureSpan">baconjs.</span>Bacon
1.  object <span class="apidocSignatureSpan">baconjs.</span>Bus.prototype
1.  object <span class="apidocSignatureSpan">baconjs.</span>CompositeUnsubscribe.prototype
1.  object <span class="apidocSignatureSpan">baconjs.</span>Desc.prototype
1.  object <span class="apidocSignatureSpan">baconjs.</span>Dispatcher.prototype
1.  object <span class="apidocSignatureSpan">baconjs.</span>End.prototype
1.  object <span class="apidocSignatureSpan">baconjs.</span>Error.prototype
1.  object <span class="apidocSignatureSpan">baconjs.</span>Event.prototype
1.  object <span class="apidocSignatureSpan">baconjs.</span>EventStream.prototype
1.  object <span class="apidocSignatureSpan">baconjs.</span>Initial.prototype
1.  object <span class="apidocSignatureSpan">baconjs.</span>Next.prototype
1.  object <span class="apidocSignatureSpan">baconjs.</span>Observable.prototype
1.  object <span class="apidocSignatureSpan">baconjs.</span>Property.prototype
1.  object <span class="apidocSignatureSpan">baconjs.</span>UpdateBarrier
1.  object <span class="apidocSignatureSpan">baconjs.</span>_
1.  object <span class="apidocSignatureSpan">baconjs.</span>scheduler
1.  string <span class="apidocSignatureSpan">baconjs.</span>more
1.  string <span class="apidocSignatureSpan">baconjs.</span>noMore
1.  string <span class="apidocSignatureSpan">baconjs.</span>version

#### [module baconjs.Bus](#apidoc.module.baconjs.Bus)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Bus ()](#apidoc.element.baconjs.Bus.Bus)

#### [module baconjs.Bus.prototype](#apidoc.module.baconjs.Bus.prototype)
1.  [function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>end ()](#apidoc.element.baconjs.Bus.prototype.end)
1.  [function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>error (error)](#apidoc.element.baconjs.Bus.prototype.error)
1.  [function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>guardedSink (input)](#apidoc.element.baconjs.Bus.prototype.guardedSink)
1.  [function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>plug (input)](#apidoc.element.baconjs.Bus.prototype.plug)
1.  [function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>push (value)](#apidoc.element.baconjs.Bus.prototype.push)
1.  [function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>subscribeAll (newSink)](#apidoc.element.baconjs.Bus.prototype.subscribeAll)
1.  [function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>subscribeInput (subscription)](#apidoc.element.baconjs.Bus.prototype.subscribeInput)
1.  [function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>unsubAll ()](#apidoc.element.baconjs.Bus.prototype.unsubAll)
1.  [function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>unsubscribeInput (input)](#apidoc.element.baconjs.Bus.prototype.unsubscribeInput)

#### [module baconjs.CompositeUnsubscribe](#apidoc.module.baconjs.CompositeUnsubscribe)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>CompositeUnsubscribe ()](#apidoc.element.baconjs.CompositeUnsubscribe.CompositeUnsubscribe)

#### [module baconjs.CompositeUnsubscribe.prototype](#apidoc.module.baconjs.CompositeUnsubscribe.prototype)
1.  [function <span class="apidocSignatureSpan">baconjs.CompositeUnsubscribe.prototype.</span>add (subscription)](#apidoc.element.baconjs.CompositeUnsubscribe.prototype.add)
1.  [function <span class="apidocSignatureSpan">baconjs.CompositeUnsubscribe.prototype.</span>count ()](#apidoc.element.baconjs.CompositeUnsubscribe.prototype.count)
1.  [function <span class="apidocSignatureSpan">baconjs.CompositeUnsubscribe.prototype.</span>empty ()](#apidoc.element.baconjs.CompositeUnsubscribe.prototype.empty)
1.  [function <span class="apidocSignatureSpan">baconjs.CompositeUnsubscribe.prototype.</span>remove (unsub)](#apidoc.element.baconjs.CompositeUnsubscribe.prototype.remove)
1.  [function <span class="apidocSignatureSpan">baconjs.CompositeUnsubscribe.prototype.</span>unsubscribe ()](#apidoc.element.baconjs.CompositeUnsubscribe.prototype.unsubscribe)

#### [module baconjs.Desc](#apidoc.module.baconjs.Desc)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Desc (context, method, args)](#apidoc.element.baconjs.Desc.Desc)
1.  object <span class="apidocSignatureSpan">baconjs.Desc.</span>empty

#### [module baconjs.Desc.prototype](#apidoc.module.baconjs.Desc.prototype)
1.  boolean <span class="apidocSignatureSpan">baconjs.Desc.prototype.</span>_isDesc
1.  [function <span class="apidocSignatureSpan">baconjs.Desc.prototype.</span>deps ()](#apidoc.element.baconjs.Desc.prototype.deps)
1.  [function <span class="apidocSignatureSpan">baconjs.Desc.prototype.</span>toString ()](#apidoc.element.baconjs.Desc.prototype.toString)

#### [module baconjs.Dispatcher](#apidoc.module.baconjs.Dispatcher)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Dispatcher (_subscribe, _handleEvent)](#apidoc.element.baconjs.Dispatcher.Dispatcher)

#### [module baconjs.Dispatcher.prototype](#apidoc.module.baconjs.Dispatcher.prototype)
1.  [function <span class="apidocSignatureSpan">baconjs.Dispatcher.prototype.</span>handleEvent (event)](#apidoc.element.baconjs.Dispatcher.prototype.handleEvent)
1.  [function <span class="apidocSignatureSpan">baconjs.Dispatcher.prototype.</span>hasSubscribers ()](#apidoc.element.baconjs.Dispatcher.prototype.hasSubscribers)
1.  [function <span class="apidocSignatureSpan">baconjs.Dispatcher.prototype.</span>push (event)](#apidoc.element.baconjs.Dispatcher.prototype.push)
1.  [function <span class="apidocSignatureSpan">baconjs.Dispatcher.prototype.</span>pushIt (event)](#apidoc.element.baconjs.Dispatcher.prototype.pushIt)
1.  [function <span class="apidocSignatureSpan">baconjs.Dispatcher.prototype.</span>pushToSubscriptions (event)](#apidoc.element.baconjs.Dispatcher.prototype.pushToSubscriptions)
1.  [function <span class="apidocSignatureSpan">baconjs.Dispatcher.prototype.</span>removeSub (subscription)](#apidoc.element.baconjs.Dispatcher.prototype.removeSub)
1.  [function <span class="apidocSignatureSpan">baconjs.Dispatcher.prototype.</span>subscribe (sink)](#apidoc.element.baconjs.Dispatcher.prototype.subscribe)
1.  [function <span class="apidocSignatureSpan">baconjs.Dispatcher.prototype.</span>unsubscribeFromSource ()](#apidoc.element.baconjs.Dispatcher.prototype.unsubscribeFromSource)

#### [module baconjs.End](#apidoc.module.baconjs.End)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>End ()](#apidoc.element.baconjs.End.End)

#### [module baconjs.End.prototype](#apidoc.module.baconjs.End.prototype)
1.  [function <span class="apidocSignatureSpan">baconjs.End.prototype.</span>apply ()](#apidoc.element.baconjs.End.prototype.apply)
1.  [function <span class="apidocSignatureSpan">baconjs.End.prototype.</span>fmap ()](#apidoc.element.baconjs.End.prototype.fmap)
1.  [function <span class="apidocSignatureSpan">baconjs.End.prototype.</span>isEnd ()](#apidoc.element.baconjs.End.prototype.isEnd)
1.  [function <span class="apidocSignatureSpan">baconjs.End.prototype.</span>toString ()](#apidoc.element.baconjs.End.prototype.toString)

#### [module baconjs.Error](#apidoc.module.baconjs.Error)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Error (error)](#apidoc.element.baconjs.Error.Error)

#### [module baconjs.Error.prototype](#apidoc.module.baconjs.Error.prototype)
1.  [function <span class="apidocSignatureSpan">baconjs.Error.prototype.</span>apply ()](#apidoc.element.baconjs.Error.prototype.apply)
1.  [function <span class="apidocSignatureSpan">baconjs.Error.prototype.</span>fmap ()](#apidoc.element.baconjs.Error.prototype.fmap)
1.  [function <span class="apidocSignatureSpan">baconjs.Error.prototype.</span>isError ()](#apidoc.element.baconjs.Error.prototype.isError)
1.  [function <span class="apidocSignatureSpan">baconjs.Error.prototype.</span>toString ()](#apidoc.element.baconjs.Error.prototype.toString)

#### [module baconjs.Event](#apidoc.module.baconjs.Event)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Event ()](#apidoc.element.baconjs.Event.Event)

#### [module baconjs.Event.prototype](#apidoc.module.baconjs.Event.prototype)
1.  boolean <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>_isEvent
1.  [function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>filter ()](#apidoc.element.baconjs.Event.prototype.filter)
1.  [function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>hasValue ()](#apidoc.element.baconjs.Event.prototype.hasValue)
1.  [function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>inspect ()](#apidoc.element.baconjs.Event.prototype.inspect)
1.  [function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>isEnd ()](#apidoc.element.baconjs.Event.prototype.isEnd)
1.  [function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>isError ()](#apidoc.element.baconjs.Event.prototype.isError)
1.  [function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>isEvent ()](#apidoc.element.baconjs.Event.prototype.isEvent)
1.  [function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>isInitial ()](#apidoc.element.baconjs.Event.prototype.isInitial)
1.  [function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>isNext ()](#apidoc.element.baconjs.Event.prototype.isNext)
1.  [function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>log ()](#apidoc.element.baconjs.Event.prototype.log)

#### [module baconjs.EventStream](#apidoc.module.baconjs.EventStream)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>EventStream (desc, subscribe, handler)](#apidoc.element.baconjs.EventStream.EventStream)

#### [module baconjs.EventStream.prototype](#apidoc.module.baconjs.EventStream.prototype)
1.  boolean <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>_isEventStream
1.  [function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>buffer (delay)](#apidoc.element.baconjs.EventStream.prototype.buffer)
1.  [function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>bufferWithCount (count)](#apidoc.element.baconjs.EventStream.prototype.bufferWithCount)
1.  [function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>bufferWithTime (delay)](#apidoc.element.baconjs.EventStream.prototype.bufferWithTime)
1.  [function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>bufferWithTimeOrCount (delay, count)](#apidoc.element.baconjs.EventStream.prototype.bufferWithTimeOrCount)
1.  [function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>concat (right)](#apidoc.element.baconjs.EventStream.prototype.concat)
1.  [function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>delayChanges (desc, f)](#apidoc.element.baconjs.EventStream.prototype.delayChanges)
1.  [function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>flatScan (seed, f)](#apidoc.element.baconjs.EventStream.prototype.flatScan)
1.  [function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>holdWhen (valve)](#apidoc.element.baconjs.EventStream.prototype.holdWhen)
1.  [function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>merge (right)](#apidoc.element.baconjs.EventStream.prototype.merge)
1.  [function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>sampledBy (sampler, combinator)](#apidoc.element.baconjs.EventStream.prototype.sampledBy)
1.  [function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>skipUntil (starter)](#apidoc.element.baconjs.EventStream.prototype.skipUntil)
1.  [function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>skipWhile (f)](#apidoc.element.baconjs.EventStream.prototype.skipWhile)
1.  [function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>startWith (seed)](#apidoc.element.baconjs.EventStream.prototype.startWith)
1.  [function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>takeUntil (stopper)](#apidoc.element.baconjs.EventStream.prototype.takeUntil)
1.  [function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>toEventStream ()](#apidoc.element.baconjs.EventStream.prototype.toEventStream)
1.  [function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>toProperty (initValue_)](#apidoc.element.baconjs.EventStream.prototype.toProperty)
1.  [function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>withHandler (handler)](#apidoc.element.baconjs.EventStream.prototype.withHandler)

#### [module baconjs.Initial](#apidoc.module.baconjs.Initial)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Initial (valueF, eager)](#apidoc.element.baconjs.Initial.Initial)

#### [module baconjs.Initial.prototype](#apidoc.module.baconjs.Initial.prototype)
1.  boolean <span class="apidocSignatureSpan">baconjs.Initial.prototype.</span>_isInitial
1.  [function <span class="apidocSignatureSpan">baconjs.Initial.prototype.</span>apply (value)](#apidoc.element.baconjs.Initial.prototype.apply)
1.  [function <span class="apidocSignatureSpan">baconjs.Initial.prototype.</span>isInitial ()](#apidoc.element.baconjs.Initial.prototype.isInitial)
1.  [function <span class="apidocSignatureSpan">baconjs.Initial.prototype.</span>isNext ()](#apidoc.element.baconjs.Initial.prototype.isNext)
1.  [function <span class="apidocSignatureSpan">baconjs.Initial.prototype.</span>toNext ()](#apidoc.element.baconjs.Initial.prototype.toNext)

#### [module baconjs.Next](#apidoc.module.baconjs.Next)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Next (valueF, eager)](#apidoc.element.baconjs.Next.Next)

#### [module baconjs.Next.prototype](#apidoc.module.baconjs.Next.prototype)
1.  boolean <span class="apidocSignatureSpan">baconjs.Next.prototype.</span>_isNext
1.  [function <span class="apidocSignatureSpan">baconjs.Next.prototype.</span>apply (value)](#apidoc.element.baconjs.Next.prototype.apply)
1.  [function <span class="apidocSignatureSpan">baconjs.Next.prototype.</span>filter (f)](#apidoc.element.baconjs.Next.prototype.filter)
1.  [function <span class="apidocSignatureSpan">baconjs.Next.prototype.</span>fmap (f)](#apidoc.element.baconjs.Next.prototype.fmap)
1.  [function <span class="apidocSignatureSpan">baconjs.Next.prototype.</span>hasValue ()](#apidoc.element.baconjs.Next.prototype.hasValue)
1.  [function <span class="apidocSignatureSpan">baconjs.Next.prototype.</span>isNext ()](#apidoc.element.baconjs.Next.prototype.isNext)
1.  [function <span class="apidocSignatureSpan">baconjs.Next.prototype.</span>log ()](#apidoc.element.baconjs.Next.prototype.log)
1.  [function <span class="apidocSignatureSpan">baconjs.Next.prototype.</span>toString ()](#apidoc.element.baconjs.Next.prototype.toString)
1.  [function <span class="apidocSignatureSpan">baconjs.Next.prototype.</span>value ()](#apidoc.element.baconjs.Next.prototype.value)

#### [module baconjs.Observable](#apidoc.module.baconjs.Observable)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Observable (desc)](#apidoc.element.baconjs.Observable.Observable)

#### [module baconjs.Observable.prototype](#apidoc.module.baconjs.Observable.prototype)
1.  boolean <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>_isObservable
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>assign ()](#apidoc.element.baconjs.Observable.prototype.assign)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>awaiting (other)](#apidoc.element.baconjs.Observable.prototype.awaiting)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>bufferingThrottle (minimumInterval)](#apidoc.element.baconjs.Observable.prototype.bufferingThrottle)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>combine (other, f)](#apidoc.element.baconjs.Observable.prototype.combine)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>debounce (delay)](#apidoc.element.baconjs.Observable.prototype.debounce)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>debounceImmediate (delay)](#apidoc.element.baconjs.Observable.prototype.debounceImmediate)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>decode (cases)](#apidoc.element.baconjs.Observable.prototype.decode)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>delay (delay)](#apidoc.element.baconjs.Observable.prototype.delay)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>deps ()](#apidoc.element.baconjs.Observable.prototype.deps)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>diff (start, f)](#apidoc.element.baconjs.Observable.prototype.diff)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>doAction ()](#apidoc.element.baconjs.Observable.prototype.doAction)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>doEnd ()](#apidoc.element.baconjs.Observable.prototype.doEnd)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>doError ()](#apidoc.element.baconjs.Observable.prototype.doError)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>doLog ()](#apidoc.element.baconjs.Observable.prototype.doLog)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>endOnError (f)](#apidoc.element.baconjs.Observable.prototype.endOnError)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>errors ()](#apidoc.element.baconjs.Observable.prototype.errors)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>filter (f)](#apidoc.element.baconjs.Observable.prototype.filter)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>first ()](#apidoc.element.baconjs.Observable.prototype.first)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>firstToPromise (PromiseCtr)](#apidoc.element.baconjs.Observable.prototype.firstToPromise)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>flatMap ()](#apidoc.element.baconjs.Observable.prototype.flatMap)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>flatMapConcat ()](#apidoc.element.baconjs.Observable.prototype.flatMapConcat)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>flatMapError (fn)](#apidoc.element.baconjs.Observable.prototype.flatMapError)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>flatMapFirst ()](#apidoc.element.baconjs.Observable.prototype.flatMapFirst)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>flatMapLatest ()](#apidoc.element.baconjs.Observable.prototype.flatMapLatest)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>flatMapWithConcurrencyLimit (limit)](#apidoc.element.baconjs.Observable.prototype.flatMapWithConcurrencyLimit)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>fold (seed, f)](#apidoc.element.baconjs.Observable.prototype.fold)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>forEach ()](#apidoc.element.baconjs.Observable.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>groupBy (keyF)](#apidoc.element.baconjs.Observable.prototype.groupBy)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>inspect ()](#apidoc.element.baconjs.Observable.prototype.inspect)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>internalDeps ()](#apidoc.element.baconjs.Observable.prototype.internalDeps)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>last ()](#apidoc.element.baconjs.Observable.prototype.last)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>log ()](#apidoc.element.baconjs.Observable.prototype.log)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>map (p)](#apidoc.element.baconjs.Observable.prototype.map)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>mapEnd ()](#apidoc.element.baconjs.Observable.prototype.mapEnd)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>mapError ()](#apidoc.element.baconjs.Observable.prototype.mapError)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>name (name)](#apidoc.element.baconjs.Observable.prototype.name)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>not ()](#apidoc.element.baconjs.Observable.prototype.not)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>onEnd ()](#apidoc.element.baconjs.Observable.prototype.onEnd)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>onError ()](#apidoc.element.baconjs.Observable.prototype.onError)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>onValue ()](#apidoc.element.baconjs.Observable.prototype.onValue)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>onValues (f)](#apidoc.element.baconjs.Observable.prototype.onValues)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>reduce (seed, f)](#apidoc.element.baconjs.Observable.prototype.reduce)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>scan (seed, f)](#apidoc.element.baconjs.Observable.prototype.scan)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>skip (count)](#apidoc.element.baconjs.Observable.prototype.skip)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>skipDuplicates ()](#apidoc.element.baconjs.Observable.prototype.skipDuplicates)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>skipErrors ()](#apidoc.element.baconjs.Observable.prototype.skipErrors)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>slidingWindow (n)](#apidoc.element.baconjs.Observable.prototype.slidingWindow)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>subscribe (sink)](#apidoc.element.baconjs.Observable.prototype.subscribe)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>subscribeInternal (sink)](#apidoc.element.baconjs.Observable.prototype.subscribeInternal)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>take (count)](#apidoc.element.baconjs.Observable.prototype.take)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>takeWhile (f)](#apidoc.element.baconjs.Observable.prototype.takeWhile)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>throttle (delay)](#apidoc.element.baconjs.Observable.prototype.throttle)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>toESObservable ()](#apidoc.element.baconjs.Observable.prototype.toESObservable)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>toPromise (PromiseCtr)](#apidoc.element.baconjs.Observable.prototype.toPromise)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>toString ()](#apidoc.element.baconjs.Observable.prototype.toString)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>withDescription ()](#apidoc.element.baconjs.Observable.prototype.withDescription)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>withStateMachine (initState, f)](#apidoc.element.baconjs.Observable.prototype.withStateMachine)
1.  [function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>zip (other, f)](#apidoc.element.baconjs.Observable.prototype.zip)

#### [module baconjs.Property](#apidoc.module.baconjs.Property)
1.  [function <span class="apidocSignatureSpan">baconjs.</span>Property (desc, subscribe, handler)](#apidoc.element.baconjs.Property.Property)

#### [module baconjs.Property.prototype](#apidoc.module.baconjs.Property.prototype)
1.  boolean <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>_isProperty
1.  [function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>and (other)](#apidoc.element.baconjs.Property.prototype.and)
1.  [function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>bufferingThrottle ()](#apidoc.element.baconjs.Property.prototype.bufferingThrottle)
1.  [function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>changes ()](#apidoc.element.baconjs.Property.prototype.changes)
1.  [function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>delayChanges (desc, f)](#apidoc.element.baconjs.Property.prototype.delayChanges)
1.  [function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>or (other)](#apidoc.element.baconjs.Property.prototype.or)
1.  [function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>sample (interval)](#apidoc.element.baconjs.Property.prototype.sample)
1.  [function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>sampledBy (sampler, combinator)](#apidoc.element.baconjs.Property.prototype.sampledBy)
1.  [function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>startWith (seed)](#apidoc.element.baconjs.Property.prototype.startWith)
1.  [function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>takeUntil (stopper)](#apidoc.element.baconjs.Property.prototype.takeUntil)
1.  [function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>toEventStream ()](#apidoc.element.baconjs.Property.prototype.toEventStream)
1.  [function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>toProperty ()](#apidoc.element.baconjs.Property.prototype.toProperty)
1.  [function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>withHandler (handler)](#apidoc.element.baconjs.Property.prototype.withHandler)

#### [module baconjs.UpdateBarrier](#apidoc.module.baconjs.UpdateBarrier)
1.  [function <span class="apidocSignatureSpan">baconjs.UpdateBarrier.</span>afterTransaction (f)](#apidoc.element.baconjs.UpdateBarrier.afterTransaction)
1.  [function <span class="apidocSignatureSpan">baconjs.UpdateBarrier.</span>currentEventId ()](#apidoc.element.baconjs.UpdateBarrier.currentEventId)
1.  [function <span class="apidocSignatureSpan">baconjs.UpdateBarrier.</span>hasWaiters ()](#apidoc.element.baconjs.UpdateBarrier.hasWaiters)
1.  [function <span class="apidocSignatureSpan">baconjs.UpdateBarrier.</span>inTransaction (event, context, f, args)](#apidoc.element.baconjs.UpdateBarrier.inTransaction)
1.  [function <span class="apidocSignatureSpan">baconjs.UpdateBarrier.</span>whenDoneWith (obs, f)](#apidoc.element.baconjs.UpdateBarrier.whenDoneWith)
1.  [function <span class="apidocSignatureSpan">baconjs.UpdateBarrier.</span>wrappedSubscribe (obs, sink)](#apidoc.element.baconjs.UpdateBarrier.wrappedSubscribe)

#### [module baconjs._](#apidoc.module.baconjs._)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>all (xs)](#apidoc.element.baconjs._.all)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>always (x)](#apidoc.element.baconjs._.always)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>any (xs)](#apidoc.element.baconjs._.any)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>bind (fn, me)](#apidoc.element.baconjs._.bind)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>cached (f)](#apidoc.element.baconjs._.cached)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>contains (xs, x)](#apidoc.element.baconjs._.contains)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>each (xs, f)](#apidoc.element.baconjs._.each)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>empty (xs)](#apidoc.element.baconjs._.empty)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>filter (f, xs)](#apidoc.element.baconjs._.filter)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>flatMap (f, xs)](#apidoc.element.baconjs._.flatMap)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>fold (xs, seed, f)](#apidoc.element.baconjs._.fold)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>head (xs)](#apidoc.element.baconjs._.head)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>id (x)](#apidoc.element.baconjs._.id)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>indexOf (xs, x)](#apidoc.element.baconjs._.indexOf)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>indexWhere (xs, f)](#apidoc.element.baconjs._.indexWhere)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>isFunction (f)](#apidoc.element.baconjs._.isFunction)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>last (xs)](#apidoc.element.baconjs._.last)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>map (f, xs)](#apidoc.element.baconjs._.map)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>negate (f)](#apidoc.element.baconjs._.negate)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>remove (x, xs)](#apidoc.element.baconjs._.remove)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>tail (xs)](#apidoc.element.baconjs._.tail)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>toArray (xs)](#apidoc.element.baconjs._.toArray)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>toString (obj)](#apidoc.element.baconjs._.toString)
1.  [function <span class="apidocSignatureSpan">baconjs._.</span>without (x, xs)](#apidoc.element.baconjs._.without)

#### [module baconjs.scheduler](#apidoc.module.baconjs.scheduler)
1.  [function <span class="apidocSignatureSpan">baconjs.scheduler.</span>clearInterval (id)](#apidoc.element.baconjs.scheduler.clearInterval)
1.  [function <span class="apidocSignatureSpan">baconjs.scheduler.</span>clearTimeout (id)](#apidoc.element.baconjs.scheduler.clearTimeout)
1.  [function <span class="apidocSignatureSpan">baconjs.scheduler.</span>now ()](#apidoc.element.baconjs.scheduler.now)
1.  [function <span class="apidocSignatureSpan">baconjs.scheduler.</span>setInterval (f, i)](#apidoc.element.baconjs.scheduler.setInterval)
1.  [function <span class="apidocSignatureSpan">baconjs.scheduler.</span>setTimeout (f, d)](#apidoc.element.baconjs.scheduler.setTimeout)



# <a name="apidoc.module.baconjs"></a>[module baconjs](#apidoc.module.baconjs)

#### <a name="apidoc.element.baconjs.Bus"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Bus ()](#apidoc.element.baconjs.Bus)
- description and source-code
```javascript
function Bus() {
  if (!(this instanceof Bus)) {
    return new Bus();
  }

  this.unsubAll = _.bind(this.unsubAll, this);
  this.subscribeAll = _.bind(this.subscribeAll, this);
  this.guardedSink = _.bind(this.guardedSink, this);

  this.sink = undefined;
  this.subscriptions = [];
  this.ended = false;
  EventStream.call(this, new Bacon.Desc(Bacon, "Bus", []), this.subscribeAll);
}
```
- example usage
```shell
...
['property.changes'](#property-changes) creates a stream of changes to the ['Property'](#property). The stream *does not* include
an event for the current value of the Property at the time this method was called.

<a name="property-toeventstream"></a>
['property.toEventStream()'](#property-toeventstream "property.toEventStream(@ : Property[A]) : EventStream[A]") creates an EventStream
 based on this Property. The stream contains also an event for the current
value of this Property at the time this method was called.

['new Bacon.Bus()'](#new-bacon-bus) creates a pushable/pluggable stream (see [Bus](#bus) section below)

Pro tip: you can also put Errors into streams created with the
constructors above, by using an ['Bacon.Error'](#bacon-error) object instead of a plain
value.

Bacon.fromBinder for custom streams
-----------------------------------
...
```

#### <a name="apidoc.element.baconjs.CompositeUnsubscribe"></a>[function <span class="apidocSignatureSpan">baconjs.</span>CompositeUnsubscribe ()](#apidoc.element.baconjs.CompositeUnsubscribe)
- description and source-code
```javascript
function CompositeUnsubscribe() {
  var ss = arguments.length <= 0 || arguments[0] === undefined ? [] : arguments[0];

  this.unsubscribe = _.bind(this.unsubscribe, this);
  this.unsubscribed = false;
  this.subscriptions = [];
  this.starting = [];
  for (var i = 0, s; i < ss.length; i++) {
    s = ss[i];
    this.add(s);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Desc"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Desc (context, method, args)](#apidoc.element.baconjs.Desc)
- description and source-code
```javascript
function Desc(context, method, args) {
  this.context = context;
  this.method = method;
  this.args = args;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Dispatcher"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Dispatcher (_subscribe, _handleEvent)](#apidoc.element.baconjs.Dispatcher)
- description and source-code
```javascript
function Dispatcher(_subscribe, _handleEvent) {
  this._subscribe = _subscribe;
  this._handleEvent = _handleEvent;
  this.subscribe = _.bind(this.subscribe, this);
  this.handleEvent = _.bind(this.handleEvent, this);
  this.pushing = false;
  this.ended = false;
  this.prevError = undefined;
  this.unsubSrc = undefined;
  this.subscriptions = [];
  this.queue = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.End"></a>[function <span class="apidocSignatureSpan">baconjs.</span>End ()](#apidoc.element.baconjs.End)
- description and source-code
```javascript
function End() {
  if (!(this instanceof End)) {
    return new End();
  }
  Event.call(this);
}
```
- example usage
```shell
...
$("#my-div").asEventStream("click", function(event, args) { return args[0] })
'''

<a name="bacon-frompromise"></a>
['Bacon.fromPromise(promise [, abort] [, eventTransformer])'](#bacon-frompromise "Bacon.fromPromise(promise : Promise[A] [, abort
 : boolean][, eventTransformer]) : EventStream[A]") creates an EventStream from a Promise object such as JQuery Ajax.
This stream will contain a single value or an error, followed immediately by stream end.
You can use the optional abort flag (i.e. ´fromPromise(p, true)´ to have the 'abort' method of the given promise be called when
all subscribers have been removed from the created stream.
You can also pass an optional function that transforms the promise value into Events. The default is to transform the value into
 '[new Bacon.Next(value), new Bacon.End()]'.
Check out this [example](https://github.com/raimohanska/baconjs-examples/blob/master/resources/public/index.html).

<a name="bacon-fromevent"></a>
['Bacon.fromEvent(target, eventName [, eventTransformer])'](#bacon-fromevent "Bacon.fromEvent(target : EventTarget | EventEmitter
, eventName : String [, eventTransformer]) : EventStream") creates an EventStream from events
on a DOM EventTarget or Node.JS EventEmitter object, or an object that supports event listeners using 'on'/'off' methods.
You can also pass an optional function that transforms the emitted
events' parameters.
...
```

#### <a name="apidoc.element.baconjs.Error"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Error (error)](#apidoc.element.baconjs.Error)
- description and source-code
```javascript
function Error(error) {
  if (!(this instanceof Error)) {
    return new Error(error);
  }
  this.error = error;
  Event.call(this);
}
```
- example usage
```shell
...
when there are subscribers to the stream. Polling ends permanently when
'f' returns ['Bacon.End'](#bacon-end).

<a name="bacon-once"></a>
['Bacon.once(value)'](#bacon-once "Bacon.once(value : Event[A] | A) : EventStream[A]") creates an EventStream that delivers the
given
single value for the first subscriber. The stream will end immediately
after this value. You can also send an ['Bacon.Error'](#bacon-error) event instead of a
value: 'Bacon.once(new Bacon.Error("fail"))'.

<a name="bacon-fromarray"></a>
['Bacon.fromArray(values)'](#bacon-fromarray "Bacon.fromArray(values : Array[Event[A] | A]) : EventStream[A]") creates an EventStream
 that delivers the given
series of values (given as array) to the first subscriber. The stream ends after these
values have been delivered. You can also send ['Bacon.Error'](#bacon-error) events, or
any combination of pure values and error events like this:
'Bacon.fromArray([1, new Bacon.Error()])
...
```

#### <a name="apidoc.element.baconjs.Event"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Event ()](#apidoc.element.baconjs.Event)
- description and source-code
```javascript
function Event() {
  this.id = ++eventIdCounter;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.EventStream"></a>[function <span class="apidocSignatureSpan">baconjs.</span>EventStream (desc, subscribe, handler)](#apidoc.element.baconjs.EventStream)
- description and source-code
```javascript
function EventStream(desc, subscribe, handler) {
  if (!(this instanceof EventStream)) {
    return new EventStream(desc, subscribe, handler);
  }
  if (_.isFunction(desc)) {
    handler = subscribe;
    subscribe = desc;
    desc = Desc.empty;
  }
  Observable.call(this, desc);
  assertFunction(subscribe);
  this.dispatcher = new Dispatcher(subscribe, handler);
  registerObs(this);
}
```
- example usage
```shell
...
['Bacon.never()'](#bacon-never "Bacon.never() : EventStream") creates an EventStream that immediately ends.

<a name="bacon-later"></a>
['Bacon.later(delay, value)'](#bacon-later "Bacon.later(delay : Number, value : A) : EventStream[A]") creates a single-element stream
 that
produces given value after given delay (milliseconds).

<a name="new-bacon-eventstream"></a>
['new Bacon.EventStream(subscribe)'](#new-bacon-eventstream "new Bacon.EventStream(subscribe)") creates an ['EventStream'](#eventstream
) with the given subscribe function.

['property.changes'](#property-changes) creates a stream of changes to the ['Property'](#property). The stream *does not* include
an event for the current value of the Property at the time this method was called.

<a name="property-toeventstream"></a>
['property.toEventStream()'](#property-toeventstream "property.toEventStream(@ : Property[A]) : EventStream[A]") creates an EventStream
 based on this Property. The stream contains also an event for the current
value of this Property at the time this method was called.
...
```

#### <a name="apidoc.element.baconjs.Initial"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Initial (valueF, eager)](#apidoc.element.baconjs.Initial)
- description and source-code
```javascript
function Initial(valueF, eager) {
  if (!(this instanceof Initial)) {
    return new Initial(valueF, eager);
  }
  Next.call(this, valueF, eager);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Next"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Next (valueF, eager)](#apidoc.element.baconjs.Next)
- description and source-code
```javascript
function Next(valueF, eager) {
  if (!(this instanceof Next)) {
    return new Next(valueF, eager);
  }

  Event.call(this);

  if (!eager && _.isFunction(valueF) || (valueF != null ? valueF._isNext : void 0)) {
    this.valueF = valueF;
    this.valueInternal = void 0;
  } else {
    this.valueF = void 0;
    this.valueInternal = valueF;
  }
}
```
- example usage
```shell
...
$("#my-div").asEventStream("click", function(event, args) { return args[0] })
'''

<a name="bacon-frompromise"></a>
['Bacon.fromPromise(promise [, abort] [, eventTransformer])'](#bacon-frompromise "Bacon.fromPromise(promise : Promise[A] [, abort
 : boolean][, eventTransformer]) : EventStream[A]") creates an EventStream from a Promise object such as JQuery Ajax.
This stream will contain a single value or an error, followed immediately by stream end.
You can use the optional abort flag (i.e. ´fromPromise(p, true)´ to have the 'abort' method of the given promise be called when
all subscribers have been removed from the created stream.
You can also pass an optional function that transforms the promise value into Events. The default is to transform the value into
 '[new Bacon.Next(value), new Bacon.End()]'.
Check out this [example](https://github.com/raimohanska/baconjs-examples/blob/master/resources/public/index.html).

<a name="bacon-fromevent"></a>
['Bacon.fromEvent(target, eventName [, eventTransformer])'](#bacon-fromevent "Bacon.fromEvent(target : EventTarget | EventEmitter
, eventName : String [, eventTransformer]) : EventStream") creates an EventStream from events
on a DOM EventTarget or Node.JS EventEmitter object, or an object that supports event listeners using 'on'/'off' methods.
You can also pass an optional function that transforms the emitted
events' parameters.
...
```

#### <a name="apidoc.element.baconjs.Observable"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Observable (desc)](#apidoc.element.baconjs.Observable)
- description and source-code
```javascript
function Observable(desc) {
  this.desc = desc;
  this.id = ++idCounter;
  this.initialDesc = this.desc;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Property"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Property (desc, subscribe, handler)](#apidoc.element.baconjs.Property)
- description and source-code
```javascript
function Property(desc, subscribe, handler) {
  Observable.call(this, desc);
  assertFunction(subscribe);
  this.dispatcher = new PropertyDispatcher(this, subscribe, handler);
  registerObs(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.combineAsArray"></a>[function <span class="apidocSignatureSpan">baconjs.</span>combineAsArray ()](#apidoc.element.baconjs.combineAsArray)
- description and source-code
```javascript
combineAsArray = function () {
  var streams = argumentsToObservables(arguments);
  if (streams.length) {
    var sources = [];
    for (var i = 0; i < streams.length; i++) {
      var stream = isObservable(streams[i]) ? streams[i] : Bacon.constant(streams[i]);
      sources.push(new Source(stream, true));
    }
    return withDesc(new Bacon.Desc(Bacon, "combineAsArray", streams), Bacon.when(sources, function () {
      for (var _len9 = arguments.length, xs = Array(_len9), _key9 = 0; _key9 < _len9; _key9++) {
        xs[_key9] = arguments[_key9];
      }

      return xs;
    }).toProperty());
  } else {
    return Bacon.constant([]);
  }
}
```
- example usage
```shell
...
given value will be used as the initial value. If the property has an
initial value of its own, the given value will be ignored.

Combining multiple streams and properties
-----------------------------------------

<a name="bacon-combineasarray"></a>
['Bacon.combineAsArray(streams)'](#bacon-combineasarray "Bacon.combineAsArray(streams)") combines Properties, EventStreams and
constant values so that the result Property will have an array of all
property values as its value. The input array may contain both Properties
and EventStreams. In the latter case, the stream is first converted into
a Property and then combined with the other properties.

<a name="bacon-combineasarray-multiple-streams"></a>
['Bacon.combineAsArray(s1, s2...)'](#bacon-combineasarray-multiple-streams "Bacon.combineAsArray(s1, s2...)") just like above, but
 with streams
...
```

#### <a name="apidoc.element.baconjs.combineTemplate"></a>[function <span class="apidocSignatureSpan">baconjs.</span>combineTemplate (template)](#apidoc.element.baconjs.combineTemplate)
- description and source-code
```javascript
combineTemplate = function (template) {
  function current(ctxStack) {
    return ctxStack[ctxStack.length - 1];
  }
  function setValue(ctxStack, key, value) {
    current(ctxStack)[key] = value;
    return value;
  }
  function applyStreamValue(key, index) {
    return function (ctxStack, values) {
      return setValue(ctxStack, key, values[index]);
    };
  }
  function constantValue(key, value) {
    return function (ctxStack) {
      return setValue(ctxStack, key, value);
    };
  }

  function mkContext(template) {
    return isArray(template) ? [] : {};
  }

  function pushContext(key, value) {
    return function (ctxStack) {
      var newContext = mkContext(value);
      setValue(ctxStack, key, newContext);
      return ctxStack.push(newContext);
    };
  }

  function compile(key, value) {
    if (isObservable(value)) {
      streams.push(value);
      return funcs.push(applyStreamValue(key, streams.length - 1));
    } else if (value && (value.constructor == Object || value.constructor == Array)) {
      var popContext = function (ctxStack) {
        return ctxStack.pop();
      };
      funcs.push(pushContext(key, value));
      compileTemplate(value);
      return funcs.push(popContext);
    } else {
      return funcs.push(constantValue(key, value));
    }
  }

  function combinator(values) {
    var rootContext = mkContext(template);
    var ctxStack = [rootContext];
    for (var i = 0, f; i < funcs.length; i++) {
      f = funcs[i];
      f(ctxStack, values);
    }
    return rootContext;
  }

  function compileTemplate(template) {
    return _.each(template, compile);
  }

  var funcs = [];
  var streams = [];

  compileTemplate(template);

  return withDesc(new Bacon.Desc(Bacon, "combineTemplate", [template]), Bacon.combineAsArray(streams).map(combinator));
}
```
- example usage
```shell
...
<a name="bacon-combinewith-streams-array-f-last"></a>
['Bacon.combineWith(streams, f)'](#bacon-combinewith-streams-array-f-last "Bacon.combineWith(streams, f)") like above

<a name="bacon-combinewith-f-last"></a>
['Bacon.combineWith(stream1, stream2..., f)'](#bacon-combinewith-f-last "Bacon.combineWith(stream1, stream2 ..., f)") like above

<a name="bacon-combinetemplate"></a>
['Bacon.combineTemplate(template)'](#bacon-combinetemplate "Bacon.combineTemplate(template)") combines Properties, EventStreams
and
constant values using a template
object. For instance, assuming you've got streams or properties named
'password', 'username', 'firstname' and 'lastname', you can do

'''js
var password, username, firstname, lastname; // <- properties or streams
var loginInfo = Bacon.combineTemplate({
...
```

#### <a name="apidoc.element.baconjs.combineWith"></a>[function <span class="apidocSignatureSpan">baconjs.</span>combineWith ()](#apidoc.element.baconjs.combineWith)
- description and source-code
```javascript
combineWith = function () {
  var _argumentsToObservablesAndFunction = argumentsToObservablesAndFunction(arguments);

  var streams = _argumentsToObservablesAndFunction[0];
  var f = _argumentsToObservablesAndFunction[1];

  var desc = new Bacon.Desc(Bacon, "combineWith", [f].concat(streams));
  return withDesc(desc, Bacon.combineAsArray(streams).map(function (values) {
    return f.apply(undefined, values);
  }));
}
```
- example usage
```shell
...
stream = Bacon.once(2)
constant = 3
Bacon.combineAsArray(property, stream, constant)
# produces the value [1,2,3]
'''

<a name="bacon-combinewith"></a>
['Bacon.combineWith(f, stream1, stream2...)'](#bacon-combinewith "Bacon.combineWith(f, stream1, stream2 ...)") combines given *n
* Properties,
EventStreams and constant values using the given n-ary function 'f(v1, v2 ...)'.
To calculate the current sum of three numeric Properties, you can do

'''js
function sum3(x,y,z) { return x + y + z }
Bacon.combineWith(sum3, p1, p2, p3)
'''
...
```

#### <a name="apidoc.element.baconjs.constant"></a>[function <span class="apidocSignatureSpan">baconjs.</span>constant (value)](#apidoc.element.baconjs.constant)
- description and source-code
```javascript
constant = function (value) {
  return new Property(new Bacon.Desc(Bacon, "constant", [value]), function (sink) {
    sink(initialEvent(value));
    sink(endEvent());
    return nop;
  });
}
```
- example usage
```shell
...
second.

You can also give any number of arguments to ['fromCallback'](#bacon-fromcallback), which will be
passed to the function. These arguments can be simple variables, Bacon
EventStreams or Properties. For example the following will output "Bacon rules":

'''js
bacon = Bacon.constant('bacon')
Bacon.fromCallback(function(a, b, callback) {
  callback(a + ' ' + b);
}, bacon, 'rules').log();
'''

<a name="bacon-fromcallback-object"></a>
['Bacon.fromCallback(object, methodName [, args...])'](#bacon-fromcallback-object "Bacon.fromCallback(object, methodName [, args
...]) : EventStream[A]") a variant of fromCallback which calls the named method of a given object.
...
```

#### <a name="apidoc.element.baconjs.fromArray"></a>[function <span class="apidocSignatureSpan">baconjs.</span>fromArray (values)](#apidoc.element.baconjs.fromArray)
- description and source-code
```javascript
fromArray = function (values) {
  assertArray(values);
  if (!values.length) {
    return withDesc(new Bacon.Desc(Bacon, "fromArray", values), Bacon.never());
  } else {
    var i = 0;
    return new EventStream(new Bacon.Desc(Bacon, "fromArray", [values]), function (sink) {
      var unsubd = false;
      var reply = Bacon.more;
      var pushing = false;
      var pushNeeded = false;
      var push = function () {
        pushNeeded = true;
        if (pushing) {
          return;
        }
        pushing = true;
        while (pushNeeded) {
          pushNeeded = false;
          if (reply !== Bacon.noMore && !unsubd) {
            var value = values[i++];
            reply = sink(toEvent(value));
            if (reply !== Bacon.noMore) {
              if (i === values.length) {
                sink(endEvent());
              } else {
                UpdateBarrier.afterTransaction(push);
              }
            }
          }
        }
        pushing = false;
        return pushing;
      };

      push();
      return function () {
        unsubd = true;
        return unsubd;
      };
    });
  }
}
```
- example usage
```shell
...
<a name="bacon-once"></a>
['Bacon.once(value)'](#bacon-once "Bacon.once(value : Event[A] | A) : EventStream[A]") creates an EventStream that delivers the
given
single value for the first subscriber. The stream will end immediately
after this value. You can also send an ['Bacon.Error'](#bacon-error) event instead of a
value: 'Bacon.once(new Bacon.Error("fail"))'.

<a name="bacon-fromarray"></a>
['Bacon.fromArray(values)'](#bacon-fromarray "Bacon.fromArray(values : Array[Event[A] | A]) : EventStream[A]") creates an EventStream
 that delivers the given
series of values (given as array) to the first subscriber. The stream ends after these
values have been delivered. You can also send ['Bacon.Error'](#bacon-error) events, or
any combination of pure values and error events like this:
'Bacon.fromArray([1, new Bacon.Error()])

<a name="bacon-interval"></a>
['Bacon.interval(interval, value)'](#bacon-interval "Bacon.interval(interval : Number, value : A) : EventStream[A]") repeats the
 single element
...
```

#### <a name="apidoc.element.baconjs.fromBinder"></a>[function <span class="apidocSignatureSpan">baconjs.</span>fromBinder (binder)](#apidoc.element.baconjs.fromBinder)
- description and source-code
```javascript
fromBinder = function (binder) {
  var eventTransformer = arguments.length <= 1 || arguments[1] === undefined ? _.id : arguments[1];

  var desc = new Bacon.Desc(Bacon, "fromBinder", [binder, eventTransformer]);
  return new EventStream(desc, function (sink) {
    var unbound = false;
    var shouldUnbind = false;
    var unbind = function () {
      if (!unbound) {
        if (typeof unbinder !== "undefined" && unbinder !== null) {
          unbinder();
          return unbound = true;
        } else {
          return shouldUnbind = true;
        }
      }
    };
    var unbinder = binder(function () {
      var ref;

      for (var _len7 = arguments.length, args = Array(_len7), _key7 = 0; _key7 < _len7; _key7++) {
        args[_key7] = arguments[_key7];
      }

      var value = eventTransformer.apply(this, args);
      if (!(isArray(value) && ((ref = _.last(value)) != null ? ref._isEvent : undefined))) {
        value = [value];
      }
      var reply = Bacon.more;
      for (var i = 0, event; i < value.length; i++) {
        event = value[i];
        reply = sink(event = toEvent(event));
        if (reply === Bacon.noMore || event.isEnd()) {
          unbind();
          return reply;
        }
      }
      return reply;
    });
    if (shouldUnbind) {
      unbind();
    }
    return unbind;
  });
}
```
- example usage
```shell
...

Bacon.fromBinder for custom streams
-----------------------------------

If none of the factory methods above apply, you may of course roll your own EventStream by using ['Bacon.fromBinder'](#bacon-frombinder
).

<a name="bacon-frombinder"></a>
['Bacon.fromBinder(subscribe)'](#bacon-frombinder "Bacon.fromBinder(subscribe)") The parameter 'subscribe' is a function that accepts
 a 'sink' which is a function that your 'subscribe' function can "push" events to.

For example:

'''js
var stream = Bacon.fromBinder(function(sink) {
sink("first value")
sink([new Bacon.Next("2nd"), new Bacon.Next("3rd")])
...
```

#### <a name="apidoc.element.baconjs.fromCallback"></a>[function <span class="apidocSignatureSpan">baconjs.</span>fromCallback (f)](#apidoc.element.baconjs.fromCallback)
- description and source-code
```javascript
fromCallback = function (f) {
  for (var _len2 = arguments.length, args = Array(_len2 > 1 ? _len2 - 1 : 0), _key2 = 1; _key2 < _len2; _key2++) {
    args[_key2 - 1] = arguments[_key2];
  }

  if (typeof f === "object" && args.length) {
    var context = f;
    var methodName = args[0];
    f = function () {
      return context[methodName].apply(context, arguments);
    };
    args = args.slice(1);
  }
  return wrapped.apply(undefined, [f].concat(args));
}
```
- example usage
```shell
...
events' parameters.

'''js
Bacon.fromEvent(document.body, "click").onValue(function() { alert("Bacon!") })
'''

<a name="bacon-fromcallback"></a>
['Bacon.fromCallback(f [, args...])'](#bacon-fromcallback "Bacon.fromCallback(f : (A -> void) -> void [, args...]) : EventStream
[A]") creates an EventStream from a function that
accepts a callback. The function is supposed to call its callback just
once. For example:

'''js
Bacon.fromCallback(function(callback) {
setTimeout(function() {
  callback("Bacon!")
...
```

#### <a name="apidoc.element.baconjs.fromESObservable"></a>[function <span class="apidocSignatureSpan">baconjs.</span>fromESObservable (_observable)](#apidoc.element.baconjs.fromESObservable)
- description and source-code
```javascript
fromESObservable = function (_observable) {
  var observable;
  if (_observable[symbol("observable")]) {
    observable = _observable[symbol("observable")]();
  } else {
    observable = _observable;
  }

  var desc = new Bacon.Desc(Bacon, "fromESObservable", [observable]);
  return new Bacon.EventStream(desc, function (sink) {
    var cancel = observable.subscribe({
      error: function () {
        sink(new Bacon.Error());
        sink(new Bacon.End());
      },
      next: function (value) {
        sink(new Bacon.Next(value, true));
      },
      complete: function () {
        sink(new Bacon.End());
      }
    });

    if (cancel.unsubscribe) {
      return function () {
        cancel.unsubscribe();
      };
    } else {
      return cancel;
    }
  });
}
```
- example usage
```shell
...
    fs = require('fs');
var read = Bacon.fromNodeCallback(fs.readFile, 'input.txt');
read.onError(function(error) { console.log("Reading failed: " + error); });
read.onValue(function(value) { console.log("Read contents: " + value); });
'''

<a name="bacon-fromesobservable"></a>
['Bacon.fromESObservable(observable)'](#bacon-fromesobservable "Bacon.fromESObservable(observable : ESObservable[A]) : EventStream
[A]") creates an EventStream from an
[ES Observable](https://github.com/tc39/proposal-observable). Input can be any
ES Observable implementation including RxJS and Kefir.

<a name="bacon-fromnodecallback-object"></a>
['Bacon.fromNodeCallback(object, methodName [, args...])'](#bacon-fromnodecallback-object "Bacon.fromNodeCallback(object, methodName
 [, args...])") a variant of fromNodeCallback which calls the named method of a given object.

<a name="bacon-frompoll"></a>
...
```

#### <a name="apidoc.element.baconjs.fromEvent"></a>[function <span class="apidocSignatureSpan">baconjs.</span>fromEvent (target, eventName, eventTransformer)](#apidoc.element.baconjs.fromEvent)
- description and source-code
```javascript
fromEvent = function (target, eventName, eventTransformer) {
  var _findHandlerMethods = findHandlerMethods(target);

  var sub = _findHandlerMethods[0];
  var unsub = _findHandlerMethods[1];

  var desc = new Bacon.Desc(Bacon, "fromEvent", [target, eventName]);
  return withDesc(desc, Bacon.fromBinder(function (handler) {
    sub.call(target, eventName, handler);
    return function () {
      return unsub.call(target, eventName, handler);
    };
  }, eventTransformer));
}
```
- example usage
```shell
...
['Bacon.fromPromise(promise [, abort] [, eventTransformer])'](#bacon-frompromise "Bacon.fromPromise(promise : Promise[A] [, abort
 : boolean][, eventTransformer]) : EventStream[A]") creates an EventStream from a Promise object such as JQuery Ajax.
This stream will contain a single value or an error, followed immediately by stream end.
You can use the optional abort flag (i.e. ´fromPromise(p, true)´ to have the 'abort' method of the given promise be called when
all subscribers have been removed from the created stream.
You can also pass an optional function that transforms the promise value into Events. The default is to transform the value into
 '[new Bacon.Next(value), new Bacon.End()]'.
Check out this [example](https://github.com/raimohanska/baconjs-examples/blob/master/resources/public/index.html).

<a name="bacon-fromevent"></a>
['Bacon.fromEvent(target, eventName [, eventTransformer])'](#bacon-fromevent "Bacon.fromEvent(target : EventTarget | EventEmitter
, eventName : String [, eventTransformer]) : EventStream") creates an EventStream from events
on a DOM EventTarget or Node.JS EventEmitter object, or an object that supports event listeners using 'on'/'off' methods.
You can also pass an optional function that transforms the emitted
events' parameters.

'''js
Bacon.fromEvent(document.body, "click").onValue(function() { alert("Bacon!") })
'''
...
```

#### <a name="apidoc.element.baconjs.fromEventTarget"></a>[function <span class="apidocSignatureSpan">baconjs.</span>fromEventTarget (target, eventName, eventTransformer)](#apidoc.element.baconjs.fromEventTarget)
- description and source-code
```javascript
fromEventTarget = function (target, eventName, eventTransformer) {
  var _findHandlerMethods = findHandlerMethods(target);

  var sub = _findHandlerMethods[0];
  var unsub = _findHandlerMethods[1];

  var desc = new Bacon.Desc(Bacon, "fromEvent", [target, eventName]);
  return withDesc(desc, Bacon.fromBinder(function (handler) {
    sub.call(target, eventName, handler);
    return function () {
      return unsub.call(target, eventName, handler);
    };
  }, eventTransformer));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.fromNodeCallback"></a>[function <span class="apidocSignatureSpan">baconjs.</span>fromNodeCallback (f)](#apidoc.element.baconjs.fromNodeCallback)
- description and source-code
```javascript
fromNodeCallback = function (f) {
  for (var _len2 = arguments.length, args = Array(_len2 > 1 ? _len2 - 1 : 0), _key2 = 1; _key2 < _len2; _key2++) {
    args[_key2 - 1] = arguments[_key2];
  }

  if (typeof f === "object" && args.length) {
    var context = f;
    var methodName = args[0];
    f = function () {
      return context[methodName].apply(context, arguments);
    };
    args = args.slice(1);
  }
  return wrapped.apply(undefined, [f].concat(args));
}
```
- example usage
```shell
...
}, bacon, 'rules').log();
'''

<a name="bacon-fromcallback-object"></a>
['Bacon.fromCallback(object, methodName [, args...])'](#bacon-fromcallback-object "Bacon.fromCallback(object, methodName [, args
...]) : EventStream[A]") a variant of fromCallback which calls the named method of a given object.

<a name="bacon-fromnodecallback"></a>
['Bacon.fromNodeCallback(f [, args...])'](#bacon-fromnodecallback "Bacon.fromNodeCallback(f : (E -> A -> void) -> void [, args...]) :
EventStream[A]") behaves the same way as ['Bacon.fromCallback'](#bacon-fromcallback),
except that it expects the callback to be called in the Node.js convention:
'callback(error, data)', where error is null if everything is fine. For example:

'''js
var Bacon = require('baconjs').Bacon,
    fs = require('fs');
var read = Bacon.fromNodeCallback(fs.readFile, 'input.txt');
...
```

#### <a name="apidoc.element.baconjs.fromPoll"></a>[function <span class="apidocSignatureSpan">baconjs.</span>fromPoll (delay, poll)](#apidoc.element.baconjs.fromPoll)
- description and source-code
```javascript
fromPoll = function (delay, poll) {
  var desc = new Bacon.Desc(Bacon, "fromPoll", [delay, poll]);
  return withDesc(desc, Bacon.fromBinder(function (handler) {
    var id = Bacon.scheduler.setInterval(handler, delay);
    return function () {
      return Bacon.scheduler.clearInterval(id);
    };
  }, poll));
}
```
- example usage
```shell
...
[ES Observable](https://github.com/tc39/proposal-observable). Input can be any
ES Observable implementation including RxJS and Kefir.

<a name="bacon-fromnodecallback-object"></a>
['Bacon.fromNodeCallback(object, methodName [, args...])'](#bacon-fromnodecallback-object "Bacon.fromNodeCallback(object, methodName
 [, args...])") a variant of fromNodeCallback which calls the named method of a given object.

<a name="bacon-frompoll"></a>
['Bacon.fromPoll(interval, f)'](#bacon-frompoll "Bacon.fromPoll(interval : Number, f : -> Event[A]) : EventStream[A]") polls given
 function with given interval.
Function should return Events: either ['Bacon.Next'](#bacon-next) or ['Bacon.End'](#bacon-end). Polling occurs only
when there are subscribers to the stream. Polling ends permanently when
'f' returns ['Bacon.End'](#bacon-end).

<a name="bacon-once"></a>
['Bacon.once(value)'](#bacon-once "Bacon.once(value : Event[A] | A) : EventStream[A]") creates an EventStream that delivers the
given
single value for the first subscriber. The stream will end immediately
...
```

#### <a name="apidoc.element.baconjs.fromPromise"></a>[function <span class="apidocSignatureSpan">baconjs.</span>fromPromise (promise, abort)](#apidoc.element.baconjs.fromPromise)
- description and source-code
```javascript
fromPromise = function (promise, abort) {
  var eventTransformer = arguments.length <= 2 || arguments[2] === undefined ? valueAndEnd : arguments[2];

  return withDesc(new Bacon.Desc(Bacon, "fromPromise", [promise]), Bacon.fromBinder(function (handler) {
    var bound = promise.then(handler, function (e) {
      return handler(new Error(e));
    });
    if (bound && typeof bound.done === "function") {
      bound.done();
    }

    if (abort) {
      return function () {
        if (typeof promise.abort === "function") {
          return promise.abort();
        }
      };
    } else {
      return function () {};
    }
  }, eventTransformer));
}
```
- example usage
```shell
...
'''js
$("#my-div").asEventStream("click", ".more-specific-selector")
$("#my-div").asEventStream("click", ".more-specific-selector", function(event, args) { return args[0] })
$("#my-div").asEventStream("click", function(event, args) { return args[0] })
'''

<a name="bacon-frompromise"></a>
['Bacon.fromPromise(promise [, abort] [, eventTransformer])'](#bacon-frompromise "Bacon.fromPromise(promise : Promise[A] [, abort
 : boolean][, eventTransformer]) : EventStream[A]") creates an EventStream from a Promise object such as JQuery Ajax.
This stream will contain a single value or an error, followed immediately by stream end.
You can use the optional abort flag (i.e. ´fromPromise(p, true)´ to have the 'abort' method of the given promise be called when
all subscribers have been removed from the created stream.
You can also pass an optional function that transforms the promise value into Events. The default is to transform the value into
 '[new Bacon.Next(value), new Bacon.End()]'.
Check out this [example](https://github.com/raimohanska/baconjs-examples/blob/master/resources/public/index.html).

<a name="bacon-fromevent"></a>
['Bacon.fromEvent(target, eventName [, eventTransformer])'](#bacon-fromevent "Bacon.fromEvent(target : EventTarget | EventEmitter
, eventName : String [, eventTransformer]) : EventStream") creates an EventStream from events
...
```

#### <a name="apidoc.element.baconjs.groupSimultaneous"></a>[function <span class="apidocSignatureSpan">baconjs.</span>groupSimultaneous ()](#apidoc.element.baconjs.groupSimultaneous)
- description and source-code
```javascript
groupSimultaneous = function () {
  for (var _len5 = arguments.length, streams = Array(_len5), _key5 = 0; _key5 < _len5; _key5++) {
    streams[_key5] = arguments[_key5];
  }

  if (streams.length === 1 && isArray(streams[0])) {
    streams = streams[0];
  }
  var sources = (function () {
    var result = [];
    for (var i = 0, s; i < streams.length; i++) {
      s = streams[i];
      result.push(new BufferingSource(s));
    }
    return result;
  })();
  return withDesc(new Bacon.Desc(Bacon, "groupSimultaneous", streams), Bacon.when(sources, function () {
    for (var _len6 = arguments.length, xs = Array(_len6), _key6 = 0; _key6 < _len6; _key6++) {
      xs[_key6] = arguments[_key6];
    }

    return xs;
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.interval"></a>[function <span class="apidocSignatureSpan">baconjs.</span>interval (delay)](#apidoc.element.baconjs.interval)
- description and source-code
```javascript
interval = function (delay) {
  var value = arguments.length <= 1 || arguments[1] === undefined ? {} : arguments[1];

  return withDesc(new Bacon.Desc(Bacon, "interval", [delay, value]), Bacon.fromPoll(delay, function () {
    return nextEvent(value);
  }));
}
```
- example usage
```shell
...
['Bacon.fromArray(values)'](#bacon-fromarray "Bacon.fromArray(values : Array[Event[A] | A]) : EventStream[A]") creates an EventStream
 that delivers the given
series of values (given as array) to the first subscriber. The stream ends after these
values have been delivered. You can also send ['Bacon.Error'](#bacon-error) events, or
any combination of pure values and error events like this:
'Bacon.fromArray([1, new Bacon.Error()])

<a name="bacon-interval"></a>
['Bacon.interval(interval, value)'](#bacon-interval "Bacon.interval(interval : Number, value : A) : EventStream[A]") repeats the
 single element
indefinitely with the given interval (in milliseconds)

<a name="bacon-sequentially"></a>
['Bacon.sequentially(interval, values)'](#bacon-sequentially "Bacon.sequentially(interval : Number, values : Array[A]) : EventStream
[A]") creates a stream containing given
values (given as array). Delivered with given interval in milliseconds.

<a name="bacon-repeatedly"></a>
...
```

#### <a name="apidoc.element.baconjs.later"></a>[function <span class="apidocSignatureSpan">baconjs.</span>later (delay, value)](#apidoc.element.baconjs.later)
- description and source-code
```javascript
later = function (delay, value) {
  return withDesc(new Bacon.Desc(Bacon, "later", [delay, value]), Bacon.fromBinder(function (sink) {
    var sender = function () {
      return sink([value, endEvent()]);
    };
    var id = Bacon.scheduler.setTimeout(sender, delay);
    return function () {
      return Bacon.scheduler.clearTimeout(id);
    };
  }));
}
```
- example usage
```shell
...

The example will produce values 0, 1 and 2.

<a name="bacon-never"></a>
['Bacon.never()'](#bacon-never "Bacon.never() : EventStream") creates an EventStream that immediately ends.

<a name="bacon-later"></a>
['Bacon.later(delay, value)'](#bacon-later "Bacon.later(delay : Number, value : A) : EventStream[A]") creates a single-element stream
 that
produces given value after given delay (milliseconds).

<a name="new-bacon-eventstream"></a>
['new Bacon.EventStream(subscribe)'](#new-bacon-eventstream "new Bacon.EventStream(subscribe)") creates an ['EventStream'](#eventstream
) with the given subscribe function.

['property.changes'](#property-changes) creates a stream of changes to the ['Property'](#property). The stream *does not* include
an event for the current value of the Property at the time this method was called.
...
```

#### <a name="apidoc.element.baconjs.mergeAll"></a>[function <span class="apidocSignatureSpan">baconjs.</span>mergeAll ()](#apidoc.element.baconjs.mergeAll)
- description and source-code
```javascript
mergeAll = function () {
  var streams = argumentsToObservables(arguments);
  if (streams.length) {
    return new EventStream(new Bacon.Desc(Bacon, "mergeAll", streams), function (sink) {
      var ends = 0;
      var smartSink = function (obs) {
        return function (unsubBoth) {
          return obs.dispatcher.subscribe(function (event) {
            if (event.isEnd()) {
              ends++;
              if (ends === streams.length) {
                return sink(endEvent());
              } else {
                return Bacon.more;
              }
            } else {
              var reply = sink(event);
              if (reply === Bacon.noMore) {
                unsubBoth();
              }
              return reply;
            }
          });
        };
      };
      var sinks = _.map(smartSink, streams);
      return new Bacon.CompositeUnsubscribe(sinks).unsubscribe;
    });
  } else {
    return Bacon.never();
  }
}
```
- example usage
```shell
...
If you need the result as an ['EventStream'](#eventstream) you might want to use ['property.changes()'](#property-changes)

'''js
Bacon.combineWith(function(v1,v2) { .. }, stream1, stream2).changes()
'''

<a name="bacon-mergeall"></a>
['Bacon.mergeAll(streams)'](#bacon-mergeall "Bacon.mergeAll(streams)") merges given array of EventStreams.
'Bacon.mergeAll(stream1, stream2 ...)' merges given EventStreams.

<a name="bacon-zipasarray"></a>
['Bacon.zipAsArray(streams)'](#bacon-zipasarray "Bacon.zipAsArray(streams)") zips the array of EventStreams / Properties in to a
 new
EventStream that will have an array of values from each source as
its value. Zipping means that events from each source are combined
pairwise so that the 1st event from each source is published first, then
...
```

#### <a name="apidoc.element.baconjs.never"></a>[function <span class="apidocSignatureSpan">baconjs.</span>never ()](#apidoc.element.baconjs.never)
- description and source-code
```javascript
never = function () {
  return new EventStream(describe(Bacon, "never"), function (sink) {
    sink(endEvent());
    return nop;
  });
}
```
- example usage
```shell
...
  }
}).log()
'''

The example will produce values 0, 1 and 2.

<a name="bacon-never"></a>
['Bacon.never()'](#bacon-never "Bacon.never() : EventStream") creates an EventStream that immediately ends.

<a name="bacon-later"></a>
['Bacon.later(delay, value)'](#bacon-later "Bacon.later(delay : Number, value : A) : EventStream[A]") creates a single-element stream
 that
produces given value after given delay (milliseconds).

<a name="new-bacon-eventstream"></a>
['new Bacon.EventStream(subscribe)'](#new-bacon-eventstream "new Bacon.EventStream(subscribe)") creates an ['EventStream'](#eventstream
) with the given subscribe function.
...
```

#### <a name="apidoc.element.baconjs.onValues"></a>[function <span class="apidocSignatureSpan">baconjs.</span>onValues ()](#apidoc.element.baconjs.onValues)
- description and source-code
```javascript
onValues = function () {
  return Bacon.combineAsArray(Array.prototype.slice.call(arguments, 0, arguments.length - 1)).onValues(arguments[arguments.length
 - 1]);
}
```
- example usage
```shell
...
received, instead of ['Event'](#event) objects.
The [Function Construction rules](#function-construction-rules) below apply here.
Just like 'subscribe', this method returns a function for unsubscribing.
'stream.onValue' and 'property.onValue' behave similarly, except that the latter also
pushes the initial value of the property, in case there is one.

<a name="observable-onvalues"></a>
['observable.onValues(f)'](#observable-onvalues "observable.onValues(f)") like ['onValue'](#stream-onvalue), but splits the value
 (assuming its an
array) as function arguments to 'f'.

<a name="observable-onerror"></a>
['observable.onError(f)'](#observable-onerror "observable.onError(@ : Observable[A], f : Error -> void) : Unsubscriber") subscribes
 a callback to error events. The function will be called for each error in the stream.
Just like 'subscribe', this method returns a function for unsubscribing.

<a name="observable-onend"></a>
...
```

#### <a name="apidoc.element.baconjs.once"></a>[function <span class="apidocSignatureSpan">baconjs.</span>once (value)](#apidoc.element.baconjs.once)
- description and source-code
```javascript
once = function (value) {
  return new EventStream(new Desc(Bacon, "once", [value]), function (sink) {
    sink(toEvent(value));
    sink(endEvent());
    return nop;
  });
}
```
- example usage
```shell
...
<a name="bacon-frompoll"></a>
['Bacon.fromPoll(interval, f)'](#bacon-frompoll "Bacon.fromPoll(interval : Number, f : -> Event[A]) : EventStream[A]") polls given
 function with given interval.
Function should return Events: either ['Bacon.Next'](#bacon-next) or ['Bacon.End'](#bacon-end). Polling occurs only
when there are subscribers to the stream. Polling ends permanently when
'f' returns ['Bacon.End'](#bacon-end).

<a name="bacon-once"></a>
['Bacon.once(value)'](#bacon-once "Bacon.once(value : Event[A] | A) : EventStream[A]") creates an EventStream that delivers the
given
single value for the first subscriber. The stream will end immediately
after this value. You can also send an ['Bacon.Error'](#bacon-error) event instead of a
value: 'Bacon.once(new Bacon.Error("fail"))'.

<a name="bacon-fromarray"></a>
['Bacon.fromArray(values)'](#bacon-fromarray "Bacon.fromArray(values : Array[Event[A] | A]) : EventStream[A]") creates an EventStream
 that delivers the given
series of values (given as array) to the first subscriber. The stream ends after these
...
```

#### <a name="apidoc.element.baconjs.repeat"></a>[function <span class="apidocSignatureSpan">baconjs.</span>repeat (generator)](#apidoc.element.baconjs.repeat)
- description and source-code
```javascript
repeat = function (generator) {
  var index = 0;
  return Bacon.fromBinder(function (sink) {
    var flag = false;
    var reply = Bacon.more;
    var unsub = function () {};
    function handleEvent(event) {
      if (event.isEnd()) {
        if (!flag) {
          return flag = true;
        } else {
          return subscribeNext();
        }
      } else {
        return reply = sink(event);
      }
    };
    function subscribeNext() {
      var next;
      flag = true;
      while (flag && reply !== Bacon.noMore) {
        next = generator(index++);
        flag = false;
        if (next) {
          unsub = next.subscribeInternal(handleEvent);
        } else {
          sink(endEvent());
        }
      }
      return flag = true;
    };
    subscribeNext();
    return function () {
      return unsub();
    };
  });
}
```
- example usage
```shell
...

<a name="bacon-repeatedly"></a>
['Bacon.repeatedly(interval, values)'](#bacon-repeatedly "Bacon.repeatedly(interval : Number, values : Array[A]) : EventStream[A
]") repeats given elements indefinitely
with given interval in milliseconds. For example, 'repeatedly(10, [1,2,3])'
would lead to '1,2,3,1,2,3...' to be repeated indefinitely.

<a name="bacon-repeat"></a>
['Bacon.repeat(fn)'](#bacon-repeat "Bacon.repeat(fn: Number -> Observable[A]): EventStream[A]") Calls generator function which is
 expected to return an observable. The returned EventStream contains
values and errors from the spawned observable. When the spawned observable ends, the generator is called
again to spawn a new observable.

This is repeated until the generator returns a falsy value
(such as 'undefined' or 'false').

The generator function is called with one argument — iteration number starting from '0'.
...
```

#### <a name="apidoc.element.baconjs.repeatedly"></a>[function <span class="apidocSignatureSpan">baconjs.</span>repeatedly (delay, values)](#apidoc.element.baconjs.repeatedly)
- description and source-code
```javascript
repeatedly = function (delay, values) {
  var index = 0;
  return withDesc(new Bacon.Desc(Bacon, "repeatedly", [delay, values]), Bacon.fromPoll(delay, function () {
    return values[index++ % values.length];
  }));
}
```
- example usage
```shell
...
indefinitely with the given interval (in milliseconds)

<a name="bacon-sequentially"></a>
['Bacon.sequentially(interval, values)'](#bacon-sequentially "Bacon.sequentially(interval : Number, values : Array[A]) : EventStream
[A]") creates a stream containing given
values (given as array). Delivered with given interval in milliseconds.

<a name="bacon-repeatedly"></a>
['Bacon.repeatedly(interval, values)'](#bacon-repeatedly "Bacon.repeatedly(interval : Number, values : Array[A]) : EventStream[A
]") repeats given elements indefinitely
with given interval in milliseconds. For example, 'repeatedly(10, [1,2,3])'
would lead to '1,2,3,1,2,3...' to be repeated indefinitely.

<a name="bacon-repeat"></a>
['Bacon.repeat(fn)'](#bacon-repeat "Bacon.repeat(fn: Number -> Observable[A]): EventStream[A]") Calls generator function which is
 expected to return an observable. The returned EventStream contains
values and errors from the spawned observable. When the spawned observable ends, the generator is called
again to spawn a new observable.
...
```

#### <a name="apidoc.element.baconjs.retry"></a>[function <span class="apidocSignatureSpan">baconjs.</span>retry (options)](#apidoc.element.baconjs.retry)
- description and source-code
```javascript
retry = function (options) {
  if (!_.isFunction(options.source)) {
    throw new Exception("'source' option has to be a function");
  }
  var source = options.source;
  var retries = options.retries || 0;
  var retriesDone = 0;
  var delay = options.delay || function () {
    return 0;
  };
  var isRetryable = options.isRetryable || function () {
    return true;
  };
  var finished = false;
  var error = null;

  return withDesc(new Bacon.Desc(Bacon, "retry", [options]), Bacon.repeat(function (count) {
    function valueStream() {
      return source(count).endOnError().withHandler(function (event) {
        if (event.isError()) {
          error = event;
          if (!(isRetryable(error.error) && (retries === 0 || retriesDone < retries))) {
            finished = true;
            return this.push(event);
          }
        } else {
          if (event.hasValue()) {
            error = null;
            finished = true;
          }
          return this.push(event);
        }
      });
    }

    if (finished) {
      return null;
    } else if (error) {
      var context = {
        error: error.error,
        retriesDone: retriesDone
      };
      var pause = Bacon.later(delay(context)).filter(false);
      retriesDone++;
      return pause.concat(Bacon.once().flatMap(valueStream));
    } else {
      return valueStream();
    }
  }));
}
```
- example usage
```shell
...

Bacon.js doesn't currently generate any ['Error'](#bacon-error) events itself (except when
converting errors using Bacon.fromPromise). Error
events definitely would be generated by streams derived from IO sources
such as AJAX calls.

<a name="bacon-retry"></a>
['Bacon.retry(options)'](#bacon-retry "Bacon.retry(options)") is used to retry the call when there is an ['Error'](#bacon-error)
event in the stream produced by the 'source' function.

The two required option parameters are:

* 'source', a function that produces an Observable. The function gets attempt number (starting from zero) as its argument.
* 'retries', the number of times to retry the 'source' function _in addition to the initial attempt_. Use the value o (zero) for
 retrying indefinitely.

Additionally, one may pass in one or both of the following callbacks:
...
```

#### <a name="apidoc.element.baconjs.sequentially"></a>[function <span class="apidocSignatureSpan">baconjs.</span>sequentially (delay, values)](#apidoc.element.baconjs.sequentially)
- description and source-code
```javascript
sequentially = function (delay, values) {
  var index = 0;
  return withDesc(new Bacon.Desc(Bacon, "sequentially", [delay, values]), Bacon.fromPoll(delay, function () {
    var value = values[index++];
    if (index < values.length) {
      return value;
    } else if (index === values.length) {
      return [value, endEvent()];
    } else {
      return endEvent();
    }
  }));
}
```
- example usage
```shell
...
'Bacon.fromArray([1, new Bacon.Error()])

<a name="bacon-interval"></a>
['Bacon.interval(interval, value)'](#bacon-interval "Bacon.interval(interval : Number, value : A) : EventStream[A]") repeats the
 single element
indefinitely with the given interval (in milliseconds)

<a name="bacon-sequentially"></a>
['Bacon.sequentially(interval, values)'](#bacon-sequentially "Bacon.sequentially(interval : Number, values : Array[A]) : EventStream
[A]") creates a stream containing given
values (given as array). Delivered with given interval in milliseconds.

<a name="bacon-repeatedly"></a>
['Bacon.repeatedly(interval, values)'](#bacon-repeatedly "Bacon.repeatedly(interval : Number, values : Array[A]) : EventStream[A
]") repeats given elements indefinitely
with given interval in milliseconds. For example, 'repeatedly(10, [1,2,3])'
would lead to '1,2,3,1,2,3...' to be repeated indefinitely.
...
```

#### <a name="apidoc.element.baconjs.spy"></a>[function <span class="apidocSignatureSpan">baconjs.</span>spy (spy)](#apidoc.element.baconjs.spy)
- description and source-code
```javascript
spy = function (spy) {
  return spies.push(spy);
}
```
- example usage
```shell
...
For example, for 'Bacon.fromArray([1,2,3]).desc' you'd get

    { context: Bacon, method: "fromArray", args: [[1,2,3]] }

Notice that this is a field, not a function.

<a name="bacon-spy"></a>
['Bacon.spy(f)'](#bacon-spy "Bacon.spy(f)")
Adds your function as a "spy" that will get notified on all new Observables.
This will allow a visualization/analytis tool to spy on all Bacon activity.

Cleaning up
-----------

As described above, a subscriber can signal the loss of interest in new events
...
```

#### <a name="apidoc.element.baconjs.try"></a>[function <span class="apidocSignatureSpan">baconjs.</span>try (f)](#apidoc.element.baconjs.try)
- description and source-code
```javascript
try = function (f) {
  return function (value) {
    try {
      return Bacon.once(f(value));
    } catch (e) {
      return new Bacon.Error(e);
    }
  };
}
```
- example usage
```shell
...
'''

Note also that Bacon.js combinators do not catch errors that are thrown.
Especially ['map'](#observable-map) doesn't do so. If you want to map things
and wrap caught errors into Error events, you can do the following:

'''js
wrapped = source.flatMap(Bacon.try(dangerousOperation))
'''

For example, you can use 'Bacon.try' to handle JSON parse errors:

'''js
var jsonStream = Bacon
.once('{"this is invalid json"')
...
```

#### <a name="apidoc.element.baconjs.update"></a>[function <span class="apidocSignatureSpan">baconjs.</span>update (initial)](#apidoc.element.baconjs.update)
- description and source-code
```javascript
update = function (initial) {
  function lateBindFirst(f) {
    return function () {
      for (var _len22 = arguments.length, args = Array(_len22), _key22 = 0; _key22 < _len22; _key22++) {
        args[_key22] = arguments[_key22];
      }

      return function (i) {
        return f.apply(undefined, [i].concat(args));
      };
    };
  }

  for (var _len21 = arguments.length, patterns = Array(_len21 > 1 ? _len21 - 1 : 0), _key21 = 1; _key21 < _len21; _key21++) {
    patterns[_key21 - 1] = arguments[_key21];
  }

  var i = patterns.length - 1;
  while (i > 0) {
    if (!(patterns[i] instanceof Function)) {
      patterns[i] = _.always(patterns[i]);
    }
    patterns[i] = lateBindFirst(patterns[i]);
    i = i - 2;
  }
  return withDesc(new Bacon.Desc(Bacon, "update", [initial].concat(patterns)), Bacon.when.apply(Bacon, patterns).scan(initial, function
 (x, f) {
    return f(x);
  }));
}
```
- example usage
```shell
...
convert it into an EventStream using ['property.changes()'](#property-changes) or ['property.toEventStream()'](#property-toeventstream
)

<a name="bacon-update"></a>
['Bacon.update'](#bacon-update "Bacon.update") creates a Property from an initial value and updates the value based on multiple
inputs.
The inputs are defined similarly to ['Bacon.when'](#bacon-when), like this:

'''js
var result = Bacon.update(
  initial,
  [x,y,z], function(previous,x,y,z) { ... },
  [x,y],   function(previous,x,y) { ... })
'''

As input, each function above will get the previous value of the 'result' Property, along with values from the listed Observables
.
The value returned by the function will be used as the next value of 'result'.
...
```

#### <a name="apidoc.element.baconjs.when"></a>[function <span class="apidocSignatureSpan">baconjs.</span>when ()](#apidoc.element.baconjs.when)
- description and source-code
```javascript
when = function () {
  if (arguments.length === 0) {
    return Bacon.never();
  }
  var len = arguments.length;
  var usage = "when: expecting arguments in the form (Observable+,function)+";

  assert(usage, len % 2 === 0);
  var sources = [];
  var pats = [];
  var i = 0;
  var patterns = [];
  while (i < len) {
    patterns[i] = arguments[i];
    patterns[i + 1] = arguments[i + 1];
    var patSources = _.toArray(arguments[i]);
    var f = constantToFunction(arguments[i + 1]);
    var pat = { f: f, ixs: [] };
    var triggerFound = false;
    for (var j = 0, s; j < patSources.length; j++) {
      s = patSources[j];
      var index = _.indexOf(sources, s);
      if (!triggerFound) {
        triggerFound = Source.isTrigger(s);
      }
      if (index < 0) {
        sources.push(s);
        index = sources.length - 1;
      }
      for (var k = 0, ix; k < pat.ixs.length; k++) {
        ix = pat.ixs[k];
        if (ix.index === index) {
          ix.count++;
        }
      }
      pat.ixs.push({ index: index, count: 1 });
    }

    assert("At least one EventStream required", triggerFound || !patSources.length);

    if (patSources.length > 0) {
      pats.push(pat);
    }
    i = i + 2;
  }

  if (!sources.length) {
    return Bacon.never();
  }

  sources = _.map(Source.fromObservable, sources);
  var needsBarrier = _.any(sources, function (s) {
    return s.flatten;
  }) && containsDuplicateDeps(_.map(function (s) {
    return s.obs;
  }, sources));

  var desc = new Bacon.Desc(Bacon, "when", patterns);
  var resultStream = new EventStream(desc, function (sink) {
    var triggers = [];
    var ends = false;
    var match = function (p) {
      for (var i1 = 0, i; i1 < p.ixs.length; i1++) {
        i = p.ixs[i1];
        if (!sources[i.index].hasAtLeast(i.count)) {
          return false;
        }
      }
      return true;
    };
    var cannotSync = function (source) {
      return !source.sync || source.ended;
    };
    var cannotMatch = function (p) {
      for (var i1 = 0, i; i1 < p.ixs.length; i1++) {
        i = p.ixs[i1];
        if (!sources[i.index].mayHave(i.count)) {
          return true;
        }
      }
    };
    var nonFlattened = function (trigger) {
      return !trigger.source.flatten;
    };
    var part = function (source) {
      return function (unsubAll) {
        var flushLater = function () {
          return UpdateBarrier.whenDoneWith(resultStream, flush);
        };
        var flushWhileTriggers = function () {
          if (triggers.length > 0) {
            var reply = Bacon.more;
            var trigger = triggers.pop();
            for (var i1 = 0, p; i1 < pats.length; i1++) {
              p = pats[i1];
              if (match(p)) {
                var events = (function () {
                  var result = [];
                  for (var i2 = 0, i; i2 < p.ixs.length; i2++) {
                    i = p.ixs[i2];
                    result.push(sources[i.index].consume());
                  }
                  return result;
                })();
                reply = sink(trigger.e.apply(function () {
                  var _p;

                  var values = (function () {
                    var result = [];
                    for (var i2 = 0, event; i2 < events.length; i2++) {
                      event = events[i2];
                      result.push(event.value());
                    }
                    return result;
                  })();

                  return (_p = p).f.apply(_p, values);
                }));
                if (triggers.length) {
                  triggers = _.filter(nonFlattened, triggers);
                }
                if (reply === Bacon.noMore) {
                  return reply;
                } else {
                  return flushWhileTriggers();
                }
              }
            }
          } else {
            return Bacon.more;
          }
        };
        var flush = function () {
          var reply = flushWhileTriggers();
          if (ends) {
            if (_.all(sources, cannotSync) || _.all(pats, cannotMatch)) { ...
```
- example usage
```shell
...
<a name="bacon-when"></a>
['Bacon.when'](#bacon-when "Bacon.when") Consider implementing a game with discrete time ticks. We want to
handle key-events synchronized on tick-events, with at most one key
event handled per tick. If there are no key events, we want to just
process a tick.

'''js
  Bacon.when(
    [tick, keyEvent], function(_, k) { handleKeyEvent(k); return handleTick(); },
    [tick], handleTick)
'''

Order is important here. If the [tick] patterns had been written
first, this would have been tried first, and preferred at each tick.
...
```

#### <a name="apidoc.element.baconjs.zipAsArray"></a>[function <span class="apidocSignatureSpan">baconjs.</span>zipAsArray ()](#apidoc.element.baconjs.zipAsArray)
- description and source-code
```javascript
zipAsArray = function () {
  for (var _len23 = arguments.length, args = Array(_len23), _key23 = 0; _key23 < _len23; _key23++) {
    args[_key23] = arguments[_key23];
  }

  var streams = argumentsToObservables(args);
  return withDesc(new Bacon.Desc(Bacon, "zipAsArray", streams), Bacon.zipWith(streams, function () {
    for (var _len24 = arguments.length, xs = Array(_len24), _key24 = 0; _key24 < _len24; _key24++) {
      xs[_key24] = arguments[_key24];
    }

    return xs;
  }));
}
```
- example usage
```shell
...
'''

<a name="bacon-mergeall"></a>
['Bacon.mergeAll(streams)'](#bacon-mergeall "Bacon.mergeAll(streams)") merges given array of EventStreams.
'Bacon.mergeAll(stream1, stream2 ...)' merges given EventStreams.

<a name="bacon-zipasarray"></a>
['Bacon.zipAsArray(streams)'](#bacon-zipasarray "Bacon.zipAsArray(streams)") zips the array of EventStreams / Properties in to a
 new
EventStream that will have an array of values from each source as
its value. Zipping means that events from each source are combined
pairwise so that the 1st event from each source is published first, then
the 2nd event from each. The results will be published as soon as there
is a value from each source.

Be careful not to have too much "drift" between streams. If one stream
...
```

#### <a name="apidoc.element.baconjs.zipWith"></a>[function <span class="apidocSignatureSpan">baconjs.</span>zipWith ()](#apidoc.element.baconjs.zipWith)
- description and source-code
```javascript
zipWith = function () {
  for (var _len25 = arguments.length, args = Array(_len25), _key25 = 0; _key25 < _len25; _key25++) {
    args[_key25] = arguments[_key25];
  }

  var observablesAndFunction = argumentsToObservablesAndFunction(args);
  var streams = observablesAndFunction[0];
  var f = observablesAndFunction[1];

  streams = _.map(function (s) {
    return s.toEventStream();
  }, streams);
  return withDesc(new Bacon.Desc(Bacon, "zipWith", [f].concat(streams)), Bacon.when(streams, f));
}
```
- example usage
```shell
...
'''

<a name="bacon-zipasarray-multiple-streams"></a>
['Bacon.zipAsArray(stream1, stream2...)'](#bacon-zipasarray-multiple-streams "Bacon.zipAsArray(stream1, stream2...)") just like
above, but with sources
provided as a list of arguments as opposed to a single array.

<a name="bacon-zipwith"></a>
['Bacon.zipWith(streams, f)'](#bacon-zipwith "Bacon.zipWith(streams, f)") like ['zipAsArray'](#bacon-zipasarray) but uses the given
 n-ary
function to combine the n values from n sources, instead of returning them in an Array.

<a name="bacon-zipwith-f-first"></a>
['Bacon.zipWith(f, streams)'](#bacon-zipwith-f-first "Bacon.zipWith(f, streams)") like ['zipAsArray'](#bacon-zipasarray) but uses
 the given n-ary
function to combine the n values from n sources, instead of returning them in an Array.

<a name="bacon-zipwith-f-first-varargs"></a>
...
```



# <a name="apidoc.module.baconjs.Bus"></a>[module baconjs.Bus](#apidoc.module.baconjs.Bus)

#### <a name="apidoc.element.baconjs.Bus.Bus"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Bus ()](#apidoc.element.baconjs.Bus.Bus)
- description and source-code
```javascript
function Bus() {
  if (!(this instanceof Bus)) {
    return new Bus();
  }

  this.unsubAll = _.bind(this.unsubAll, this);
  this.subscribeAll = _.bind(this.subscribeAll, this);
  this.guardedSink = _.bind(this.guardedSink, this);

  this.sink = undefined;
  this.subscriptions = [];
  this.ended = false;
  EventStream.call(this, new Bacon.Desc(Bacon, "Bus", []), this.subscribeAll);
}
```
- example usage
```shell
...
['property.changes'](#property-changes) creates a stream of changes to the ['Property'](#property). The stream *does not* include
an event for the current value of the Property at the time this method was called.

<a name="property-toeventstream"></a>
['property.toEventStream()'](#property-toeventstream "property.toEventStream(@ : Property[A]) : EventStream[A]") creates an EventStream
 based on this Property. The stream contains also an event for the current
value of this Property at the time this method was called.

['new Bacon.Bus()'](#new-bacon-bus) creates a pushable/pluggable stream (see [Bus](#bus) section below)

Pro tip: you can also put Errors into streams created with the
constructors above, by using an ['Bacon.Error'](#bacon-error) object instead of a plain
value.

Bacon.fromBinder for custom streams
-----------------------------------
...
```



# <a name="apidoc.module.baconjs.Bus.prototype"></a>[module baconjs.Bus.prototype](#apidoc.module.baconjs.Bus.prototype)

#### <a name="apidoc.element.baconjs.Bus.prototype.end"></a>[function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>end ()](#apidoc.element.baconjs.Bus.prototype.end)
- description and source-code
```javascript
end = function () {
  this.ended = true;
  this.unsubAll();
  if (typeof this.sink === "function") {
    return this.sink(endEvent());
  }
}
```
- example usage
```shell
...
<a name="new-bacon-bus"></a>
['new Bacon.Bus()'](#new-bacon-bus "new Bacon.Bus()") returns a new Bus.

<a name="bus-push"></a>
['bus.push(x)'](#bus-push "bus.push(@ : Bus[A], x : A)") pushes the given value to the stream.

<a name="bus-end"></a>
['bus.end()'](#bus-end "bus.end(@ : Bus[A])") ends the stream. Sends an End event to all subscribers.
After this call, there'll be no more events to the subscribers.
Also, the ['bus.push'](#bus-push) and ['bus.plug'](#bus-plug) methods have no effect.

<a name="bus-error"></a>
['bus.error(e)'](#bus-error "bus.error(@ : Bus[A], e : Error)") sends an Error with given message to all subscribers

<a name="bus-plug"></a>
...
```

#### <a name="apidoc.element.baconjs.Bus.prototype.error"></a>[function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>error (error)](#apidoc.element.baconjs.Bus.prototype.error)
- description and source-code
```javascript
error = function (error) {
  if (typeof this.sink === "function") {
    return this.sink(new Error(error));
  }
}
```
- example usage
```shell
...

<a name="bus-end"></a>
['bus.end()'](#bus-end "bus.end(@ : Bus[A])") ends the stream. Sends an End event to all subscribers.
After this call, there'll be no more events to the subscribers.
Also, the ['bus.push'](#bus-push) and ['bus.plug'](#bus-plug) methods have no effect.

<a name="bus-error"></a>
['bus.error(e)'](#bus-error "bus.error(@ : Bus[A], e : Error)") sends an Error with given message to all subscribers

<a name="bus-plug"></a>
['bus.plug(stream)'](#bus-plug "bus.plug(@ : Bus[A], stream : EventStream[A])") plugs the given stream to the Bus. All events from
the given stream will be delivered to the subscribers of the Bus.
Returns a function that can be used to unplug the same stream.

The plug method practically allows you to merge in other streams after
...
```

#### <a name="apidoc.element.baconjs.Bus.prototype.guardedSink"></a>[function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>guardedSink (input)](#apidoc.element.baconjs.Bus.prototype.guardedSink)
- description and source-code
```javascript
guardedSink = function (input) {
  var _this8 = this;

  return function (event) {
    if (event.isEnd()) {
      _this8.unsubscribeInput(input);
      return Bacon.noMore;
    } else {
      return _this8.sink(event);
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Bus.prototype.plug"></a>[function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>plug (input)](#apidoc.element.baconjs.Bus.prototype.plug)
- description and source-code
```javascript
plug = function (input) {
  var _this9 = this;

  assertObservable(input);
  if (this.ended) {
    return;
  }
  var sub = { input: input };
  this.subscriptions.push(sub);
  if (typeof this.sink !== "undefined") {
    this.subscribeInput(sub);
  }
  return function () {
    return _this9.unsubscribeInput(input);
  };
}
```
- example usage
```shell
...
After this call, there'll be no more events to the subscribers.
Also, the ['bus.push'](#bus-push) and ['bus.plug'](#bus-plug) methods have no effect.

<a name="bus-error"></a>
['bus.error(e)'](#bus-error "bus.error(@ : Bus[A], e : Error)") sends an Error with given message to all subscribers

<a name="bus-plug"></a>
['bus.plug(stream)'](#bus-plug "bus.plug(@ : Bus[A], stream : EventStream[A])") plugs the given stream to the Bus. All events from
the given stream will be delivered to the subscribers of the Bus.
Returns a function that can be used to unplug the same stream.

The plug method practically allows you to merge in other streams after
the creation of the Bus. I've found Bus quite useful as an event broadcast
mechanism in the
[Worzone](https://github.com/raimohanska/worzone) game, for instance.
...
```

#### <a name="apidoc.element.baconjs.Bus.prototype.push"></a>[function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>push (value)](#apidoc.element.baconjs.Bus.prototype.push)
- description and source-code
```javascript
push = function (value) {
  if (!this.ended && typeof this.sink === "function") {
    return this.sink(nextEvent(value));
  }
}
```
- example usage
```shell
...
['observable.withHandler(f)'](#observable-withhandler "observable.withHandler(f)") lets you do more custom event handling: you
get all events to your function and you can output any number of events
and end the stream if you choose. For example, to send an error and end
the stream in case a value is below zero:

'''js
if (event.hasValue() && event.value() < 0) {
  this.push(new Bacon.Error("Value below zero"));
  return this.push(end());
} else {
  return this.push(event);
}
'''

Note that it's important to return the value from 'this.push' so that
...
```

#### <a name="apidoc.element.baconjs.Bus.prototype.subscribeAll"></a>[function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>subscribeAll (newSink)](#apidoc.element.baconjs.Bus.prototype.subscribeAll)
- description and source-code
```javascript
subscribeAll = function (newSink) {
  if (this.ended) {
    newSink(endEvent());
  } else {
    this.sink = newSink;
    var iterable = cloneArray(this.subscriptions);
    for (var i = 0, subscription; i < iterable.length; i++) {
      subscription = iterable[i];
      this.subscribeInput(subscription);
    }
  }
  return this.unsubAll;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Bus.prototype.subscribeInput"></a>[function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>subscribeInput (subscription)](#apidoc.element.baconjs.Bus.prototype.subscribeInput)
- description and source-code
```javascript
subscribeInput = function (subscription) {
  subscription.unsub = subscription.input.dispatcher.subscribe(this.guardedSink(subscription.input));
  return subscription.unsub;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Bus.prototype.unsubAll"></a>[function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>unsubAll ()](#apidoc.element.baconjs.Bus.prototype.unsubAll)
- description and source-code
```javascript
unsubAll = function () {
  var iterable = this.subscriptions;
  for (var i = 0, sub; i < iterable.length; i++) {
    sub = iterable[i];
    if (typeof sub.unsub === "function") {
      sub.unsub();
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Bus.prototype.unsubscribeInput"></a>[function <span class="apidocSignatureSpan">baconjs.Bus.prototype.</span>unsubscribeInput (input)](#apidoc.element.baconjs.Bus.prototype.unsubscribeInput)
- description and source-code
```javascript
unsubscribeInput = function (input) {
  var iterable = this.subscriptions;
  for (var i = 0, sub; i < iterable.length; i++) {
    sub = iterable[i];
    if (sub.input === input) {
      if (typeof sub.unsub === "function") {
        sub.unsub();
      }
      this.subscriptions.splice(i, 1);
      return;
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.baconjs.CompositeUnsubscribe"></a>[module baconjs.CompositeUnsubscribe](#apidoc.module.baconjs.CompositeUnsubscribe)

#### <a name="apidoc.element.baconjs.CompositeUnsubscribe.CompositeUnsubscribe"></a>[function <span class="apidocSignatureSpan">baconjs.</span>CompositeUnsubscribe ()](#apidoc.element.baconjs.CompositeUnsubscribe.CompositeUnsubscribe)
- description and source-code
```javascript
function CompositeUnsubscribe() {
  var ss = arguments.length <= 0 || arguments[0] === undefined ? [] : arguments[0];

  this.unsubscribe = _.bind(this.unsubscribe, this);
  this.unsubscribed = false;
  this.subscriptions = [];
  this.starting = [];
  for (var i = 0, s; i < ss.length; i++) {
    s = ss[i];
    this.add(s);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.baconjs.CompositeUnsubscribe.prototype"></a>[module baconjs.CompositeUnsubscribe.prototype](#apidoc.module.baconjs.CompositeUnsubscribe.prototype)

#### <a name="apidoc.element.baconjs.CompositeUnsubscribe.prototype.add"></a>[function <span class="apidocSignatureSpan">baconjs.CompositeUnsubscribe.prototype.</span>add (subscription)](#apidoc.element.baconjs.CompositeUnsubscribe.prototype.add)
- description and source-code
```javascript
add = function (subscription) {
  var _this2 = this;

  if (this.unsubscribed) {
    return;
  }
  var ended = false;
  var unsub = nop;
  this.starting.push(subscription);
  var unsubMe = function () {
    if (_this2.unsubscribed) {
      return;
    }
    ended = true;
    _this2.remove(unsub);
    return _.remove(subscription, _this2.starting);
  };
  unsub = subscription(this.unsubscribe, unsubMe);
  if (!(this.unsubscribed || ended)) {
    this.subscriptions.push(unsub);
  } else {
    unsub();
  }
  _.remove(subscription, this.starting);
  return unsub;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.CompositeUnsubscribe.prototype.count"></a>[function <span class="apidocSignatureSpan">baconjs.CompositeUnsubscribe.prototype.</span>count ()](#apidoc.element.baconjs.CompositeUnsubscribe.prototype.count)
- description and source-code
```javascript
count = function () {
  if (this.unsubscribed) {
    return 0;
  }
  return this.subscriptions.length + this.starting.length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.CompositeUnsubscribe.prototype.empty"></a>[function <span class="apidocSignatureSpan">baconjs.CompositeUnsubscribe.prototype.</span>empty ()](#apidoc.element.baconjs.CompositeUnsubscribe.prototype.empty)
- description and source-code
```javascript
empty = function () {
  return this.count() === 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.CompositeUnsubscribe.prototype.remove"></a>[function <span class="apidocSignatureSpan">baconjs.CompositeUnsubscribe.prototype.</span>remove (unsub)](#apidoc.element.baconjs.CompositeUnsubscribe.prototype.remove)
- description and source-code
```javascript
remove = function (unsub) {
  if (this.unsubscribed) {
    return;
  }
  if (_.remove(unsub, this.subscriptions) !== undefined) {
    return unsub();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.CompositeUnsubscribe.prototype.unsubscribe"></a>[function <span class="apidocSignatureSpan">baconjs.CompositeUnsubscribe.prototype.</span>unsubscribe ()](#apidoc.element.baconjs.CompositeUnsubscribe.prototype.unsubscribe)
- description and source-code
```javascript
unsubscribe = function () {
  if (this.unsubscribed) {
    return;
  }
  this.unsubscribed = true;
  var iterable = this.subscriptions;
  for (var i = 0; i < iterable.length; i++) {
    iterable[i]();
  }
  this.subscriptions = [];
  this.starting = [];
  return [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.baconjs.Desc"></a>[module baconjs.Desc](#apidoc.module.baconjs.Desc)

#### <a name="apidoc.element.baconjs.Desc.Desc"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Desc (context, method, args)](#apidoc.element.baconjs.Desc.Desc)
- description and source-code
```javascript
function Desc(context, method, args) {
  this.context = context;
  this.method = method;
  this.args = args;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.baconjs.Desc.prototype"></a>[module baconjs.Desc.prototype](#apidoc.module.baconjs.Desc.prototype)

#### <a name="apidoc.element.baconjs.Desc.prototype.deps"></a>[function <span class="apidocSignatureSpan">baconjs.Desc.prototype.</span>deps ()](#apidoc.element.baconjs.Desc.prototype.deps)
- description and source-code
```javascript
deps = function () {
  if (!this.cached) {
    this.cached = findDeps([this.context].concat(this.args));
  }
  return this.cached;
}
```
- example usage
```shell
...

<a name="observable-tostring"></a>
['observable.toString'](#observable-tostring "observable.toString") Returns a textual description of the Observable. For instance
,
'Bacon.once(1).map(function() {}))' would return "Bacon.once(1).map(function)".


<a name="observable-deps"></a>
['observable.deps'](#observable-deps "observable.deps") Returns the an array of dependencies that the Observable has. For instance
, for 'a.map(function() {}).deps()', would return '[a]'.
This method returns the "visible" dependencies only, skipping internal details.  This method is thus suitable for visualization
tools.
Internally, many combinator functions depend on other combinators to create intermediate Observables that the result will actually
 depend on.
The ['deps'](#observable-deps) method will skip these internal dependencies.

<a name="observable-internaldeps"></a>
['observable.internalDeps'](#observable-internaldeps "observable.internalDeps") Returns the true dependencies of the observable,
including the intermediate "hidden" Observables.
This method is for Bacon.js internal purposes but could be useful for debugging/analysis tools as well.
...
```

#### <a name="apidoc.element.baconjs.Desc.prototype.toString"></a>[function <span class="apidocSignatureSpan">baconjs.Desc.prototype.</span>toString ()](#apidoc.element.baconjs.Desc.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return _.toString(this.context) + "." + _.toString(this.method) + "(" + _.map(_.toString, this.args) + ")";
}
```
- example usage
```shell
...
use this data recursively to create a string representation for the observable. This method
is probably useful for Bacon core / library / plugin development only.

For example:

    var src = Bacon.once(1)
    var obs = src.map(function(x) { return -x })
    console.log(obs.toString())
    --> Bacon.once(1).map(function)
    obs.withDescription(src, "times", -1)
    console.log(obs.toString())
    --> Bacon.once(1).times(-1)

<a name="observable-groupby"></a>
['observable.groupBy(keyF [, limitF])'](#observable-groupby "observable.groupBy(@ : Observable[A], keyF[, limitF]) : Observable[
Observable[A]]") Groups stream events to new streams by 'keyF'. Optional 'limitF' can be provided to limit grouped
...
```



# <a name="apidoc.module.baconjs.Dispatcher"></a>[module baconjs.Dispatcher](#apidoc.module.baconjs.Dispatcher)

#### <a name="apidoc.element.baconjs.Dispatcher.Dispatcher"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Dispatcher (_subscribe, _handleEvent)](#apidoc.element.baconjs.Dispatcher.Dispatcher)
- description and source-code
```javascript
function Dispatcher(_subscribe, _handleEvent) {
  this._subscribe = _subscribe;
  this._handleEvent = _handleEvent;
  this.subscribe = _.bind(this.subscribe, this);
  this.handleEvent = _.bind(this.handleEvent, this);
  this.pushing = false;
  this.ended = false;
  this.prevError = undefined;
  this.unsubSrc = undefined;
  this.subscriptions = [];
  this.queue = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.baconjs.Dispatcher.prototype"></a>[module baconjs.Dispatcher.prototype](#apidoc.module.baconjs.Dispatcher.prototype)

#### <a name="apidoc.element.baconjs.Dispatcher.prototype.handleEvent"></a>[function <span class="apidocSignatureSpan">baconjs.Dispatcher.prototype.</span>handleEvent (event)](#apidoc.element.baconjs.Dispatcher.prototype.handleEvent)
- description and source-code
```javascript
handleEvent = function (event) {
  if (this._handleEvent) {
    return this._handleEvent(event);
  } else {
    return this.push(event);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Dispatcher.prototype.hasSubscribers"></a>[function <span class="apidocSignatureSpan">baconjs.Dispatcher.prototype.</span>hasSubscribers ()](#apidoc.element.baconjs.Dispatcher.prototype.hasSubscribers)
- description and source-code
```javascript
hasSubscribers = function () {
  return this.subscriptions.length > 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Dispatcher.prototype.push"></a>[function <span class="apidocSignatureSpan">baconjs.Dispatcher.prototype.</span>push (event)](#apidoc.element.baconjs.Dispatcher.prototype.push)
- description and source-code
```javascript
push = function (event) {
  if (event.isEnd()) {
    this.ended = true;
  }
  return UpdateBarrier.inTransaction(event, this, this.pushIt, [event]);
}
```
- example usage
```shell
...
['observable.withHandler(f)'](#observable-withhandler "observable.withHandler(f)") lets you do more custom event handling: you
get all events to your function and you can output any number of events
and end the stream if you choose. For example, to send an error and end
the stream in case a value is below zero:

'''js
if (event.hasValue() && event.value() < 0) {
  this.push(new Bacon.Error("Value below zero"));
  return this.push(end());
} else {
  return this.push(event);
}
'''

Note that it's important to return the value from 'this.push' so that
...
```

#### <a name="apidoc.element.baconjs.Dispatcher.prototype.pushIt"></a>[function <span class="apidocSignatureSpan">baconjs.Dispatcher.prototype.</span>pushIt (event)](#apidoc.element.baconjs.Dispatcher.prototype.pushIt)
- description and source-code
```javascript
pushIt = function (event) {
  if (!this.pushing) {
    if (event === this.prevError) {
      return;
    }
    if (event.isError()) {
      this.prevError = event;
    }
    this.pushing = true;
    this.pushToSubscriptions(event);
    this.pushing = false;
    while (this.queue.length) {
      event = this.queue.shift();
      this.push(event);
    }
    if (this.hasSubscribers()) {
      return Bacon.more;
    } else {
      this.unsubscribeFromSource();
      return Bacon.noMore;
    }
  } else {
    this.queue.push(event);
    return Bacon.more;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Dispatcher.prototype.pushToSubscriptions"></a>[function <span class="apidocSignatureSpan">baconjs.Dispatcher.prototype.</span>pushToSubscriptions (event)](#apidoc.element.baconjs.Dispatcher.prototype.pushToSubscriptions)
- description and source-code
```javascript
pushToSubscriptions = function (event) {
  try {
    var tmp = this.subscriptions;
    var len = tmp.length;
    for (var i = 0; i < len; i++) {
      var sub = tmp[i];
      var reply = sub.sink(event);
      if (reply === Bacon.noMore || event.isEnd()) {
        this.removeSub(sub);
      }
    }
    return true;
  } catch (error) {
    this.pushing = false;
    this.queue = [];
    throw error;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Dispatcher.prototype.removeSub"></a>[function <span class="apidocSignatureSpan">baconjs.Dispatcher.prototype.</span>removeSub (subscription)](#apidoc.element.baconjs.Dispatcher.prototype.removeSub)
- description and source-code
```javascript
removeSub = function (subscription) {
  this.subscriptions = _.without(subscription, this.subscriptions);
  return this.subscriptions;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Dispatcher.prototype.subscribe"></a>[function <span class="apidocSignatureSpan">baconjs.Dispatcher.prototype.</span>subscribe (sink)](#apidoc.element.baconjs.Dispatcher.prototype.subscribe)
- description and source-code
```javascript
subscribe = function (sink) {
  var subscription;
  if (this.ended) {
    sink(endEvent());
    return nop;
  } else {
    assertFunction(sink);
    subscription = {
      sink: sink
    };
    this.subscriptions.push(subscription);
    if (this.subscriptions.length === 1) {
      this.unsubSrc = this._subscribe(this.handleEvent);
      assertFunction(this.unsubSrc);
    }
    return (function (_this) {
      return function () {
        _this.removeSub(subscription);
        if (!_this.hasSubscribers()) {
          return _this.unsubscribeFromSource();
        }
      };
    })(this);
  }
}
```
- example usage
```shell
...
---------------------------------------------

Both EventStream and Property share the Observable interface, and hence share a lot of methods.
Methods typically return observables so that methods can be chained; exceptions are noted.
Common methods are listed below.

<a name="observable-subscribe"></a>
['observable.subscribe(f)'](#observable-subscribe "observable.subscribe(f)") subscribes given handler function to event stream.
Function will receive Event objects (see below).
The subscribe() call returns a 'unsubscribe' function that you can call to unsubscribe.
You can also unsubscribe by returning ['Bacon.noMore'](#bacon-nomore) from the handler function as a reply
to an Event.
'stream.subscribe' and 'property.subscribe' behave similarly, except that the latter also
pushes the initial value of the property, in case there is one.

<a name="observable-onvalue"></a>
...
```

#### <a name="apidoc.element.baconjs.Dispatcher.prototype.unsubscribeFromSource"></a>[function <span class="apidocSignatureSpan">baconjs.Dispatcher.prototype.</span>unsubscribeFromSource ()](#apidoc.element.baconjs.Dispatcher.prototype.unsubscribeFromSource)
- description and source-code
```javascript
unsubscribeFromSource = function () {
  if (this.unsubSrc) {
    this.unsubSrc();
  }
  this.unsubSrc = undefined;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.baconjs.End"></a>[module baconjs.End](#apidoc.module.baconjs.End)

#### <a name="apidoc.element.baconjs.End.End"></a>[function <span class="apidocSignatureSpan">baconjs.</span>End ()](#apidoc.element.baconjs.End.End)
- description and source-code
```javascript
function End() {
  if (!(this instanceof End)) {
    return new End();
  }
  Event.call(this);
}
```
- example usage
```shell
...
$("#my-div").asEventStream("click", function(event, args) { return args[0] })
'''

<a name="bacon-frompromise"></a>
['Bacon.fromPromise(promise [, abort] [, eventTransformer])'](#bacon-frompromise "Bacon.fromPromise(promise : Promise[A] [, abort
 : boolean][, eventTransformer]) : EventStream[A]") creates an EventStream from a Promise object such as JQuery Ajax.
This stream will contain a single value or an error, followed immediately by stream end.
You can use the optional abort flag (i.e. ´fromPromise(p, true)´ to have the 'abort' method of the given promise be called when
all subscribers have been removed from the created stream.
You can also pass an optional function that transforms the promise value into Events. The default is to transform the value into
 '[new Bacon.Next(value), new Bacon.End()]'.
Check out this [example](https://github.com/raimohanska/baconjs-examples/blob/master/resources/public/index.html).

<a name="bacon-fromevent"></a>
['Bacon.fromEvent(target, eventName [, eventTransformer])'](#bacon-fromevent "Bacon.fromEvent(target : EventTarget | EventEmitter
, eventName : String [, eventTransformer]) : EventStream") creates an EventStream from events
on a DOM EventTarget or Node.JS EventEmitter object, or an object that supports event listeners using 'on'/'off' methods.
You can also pass an optional function that transforms the emitted
events' parameters.
...
```



# <a name="apidoc.module.baconjs.End.prototype"></a>[module baconjs.End.prototype](#apidoc.module.baconjs.End.prototype)

#### <a name="apidoc.element.baconjs.End.prototype.apply"></a>[function <span class="apidocSignatureSpan">baconjs.End.prototype.</span>apply ()](#apidoc.element.baconjs.End.prototype.apply)
- description and source-code
```javascript
apply = function () {
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.End.prototype.fmap"></a>[function <span class="apidocSignatureSpan">baconjs.End.prototype.</span>fmap ()](#apidoc.element.baconjs.End.prototype.fmap)
- description and source-code
```javascript
fmap = function () {
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.End.prototype.isEnd"></a>[function <span class="apidocSignatureSpan">baconjs.End.prototype.</span>isEnd ()](#apidoc.element.baconjs.End.prototype.isEnd)
- description and source-code
```javascript
isEnd = function () {
  return true;
}
```
- example usage
```shell
...
numbers in the stream and output the value on stream end:

'''js
Bacon.fromArray([1,2,3])
  .withStateMachine(0, function(sum, event) {
    if (event.hasValue())
      return [sum + event.value(), []]
    else if (event.isEnd())
      return [undefined, [new Bacon.Next(sum), event]]
    else
      return [sum, [event]]
  })
'''

<a name="observable-decode"></a>
...
```

#### <a name="apidoc.element.baconjs.End.prototype.toString"></a>[function <span class="apidocSignatureSpan">baconjs.End.prototype.</span>toString ()](#apidoc.element.baconjs.End.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return "<end>";
}
```
- example usage
```shell
...
use this data recursively to create a string representation for the observable. This method
is probably useful for Bacon core / library / plugin development only.

For example:

    var src = Bacon.once(1)
    var obs = src.map(function(x) { return -x })
    console.log(obs.toString())
    --> Bacon.once(1).map(function)
    obs.withDescription(src, "times", -1)
    console.log(obs.toString())
    --> Bacon.once(1).times(-1)

<a name="observable-groupby"></a>
['observable.groupBy(keyF [, limitF])'](#observable-groupby "observable.groupBy(@ : Observable[A], keyF[, limitF]) : Observable[
Observable[A]]") Groups stream events to new streams by 'keyF'. Optional 'limitF' can be provided to limit grouped
...
```



# <a name="apidoc.module.baconjs.Error"></a>[module baconjs.Error](#apidoc.module.baconjs.Error)

#### <a name="apidoc.element.baconjs.Error.Error"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Error (error)](#apidoc.element.baconjs.Error.Error)
- description and source-code
```javascript
function Error(error) {
  if (!(this instanceof Error)) {
    return new Error(error);
  }
  this.error = error;
  Event.call(this);
}
```
- example usage
```shell
...
when there are subscribers to the stream. Polling ends permanently when
'f' returns ['Bacon.End'](#bacon-end).

<a name="bacon-once"></a>
['Bacon.once(value)'](#bacon-once "Bacon.once(value : Event[A] | A) : EventStream[A]") creates an EventStream that delivers the
given
single value for the first subscriber. The stream will end immediately
after this value. You can also send an ['Bacon.Error'](#bacon-error) event instead of a
value: 'Bacon.once(new Bacon.Error("fail"))'.

<a name="bacon-fromarray"></a>
['Bacon.fromArray(values)'](#bacon-fromarray "Bacon.fromArray(values : Array[Event[A] | A]) : EventStream[A]") creates an EventStream
 that delivers the given
series of values (given as array) to the first subscriber. The stream ends after these
values have been delivered. You can also send ['Bacon.Error'](#bacon-error) events, or
any combination of pure values and error events like this:
'Bacon.fromArray([1, new Bacon.Error()])
...
```



# <a name="apidoc.module.baconjs.Error.prototype"></a>[module baconjs.Error.prototype](#apidoc.module.baconjs.Error.prototype)

#### <a name="apidoc.element.baconjs.Error.prototype.apply"></a>[function <span class="apidocSignatureSpan">baconjs.Error.prototype.</span>apply ()](#apidoc.element.baconjs.Error.prototype.apply)
- description and source-code
```javascript
apply = function () {
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Error.prototype.fmap"></a>[function <span class="apidocSignatureSpan">baconjs.Error.prototype.</span>fmap ()](#apidoc.element.baconjs.Error.prototype.fmap)
- description and source-code
```javascript
fmap = function () {
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Error.prototype.isError"></a>[function <span class="apidocSignatureSpan">baconjs.Error.prototype.</span>isError ()](#apidoc.element.baconjs.Error.prototype.isError)
- description and source-code
```javascript
isError = function () {
  return true;
}
```
- example usage
```shell
...
<a name="event-isnext"></a>
['event.isNext()'](#event-isnext "event.isNext(@ : Event[A]) : Bool") true for Next events

<a name="event-isinitial"></a>
['event.isInitial()'](#event-isinitial "event.isInitial(@ : Event[A]) : Bool") true for Initial events

<a name="event-iserror"></a>
['event.isError()'](#event-iserror "event.isError()") true for Error events

<a name="event-isend"></a>
['event.isEnd()'](#event-isend "event.isEnd()") true for End events

<a name="event-error"></a>
['event.error'](#event-error "event.error") the error value of Error events
...
```

#### <a name="apidoc.element.baconjs.Error.prototype.toString"></a>[function <span class="apidocSignatureSpan">baconjs.Error.prototype.</span>toString ()](#apidoc.element.baconjs.Error.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return "<error> " + _.toString(this.error);
}
```
- example usage
```shell
...
use this data recursively to create a string representation for the observable. This method
is probably useful for Bacon core / library / plugin development only.

For example:

    var src = Bacon.once(1)
    var obs = src.map(function(x) { return -x })
    console.log(obs.toString())
    --> Bacon.once(1).map(function)
    obs.withDescription(src, "times", -1)
    console.log(obs.toString())
    --> Bacon.once(1).times(-1)

<a name="observable-groupby"></a>
['observable.groupBy(keyF [, limitF])'](#observable-groupby "observable.groupBy(@ : Observable[A], keyF[, limitF]) : Observable[
Observable[A]]") Groups stream events to new streams by 'keyF'. Optional 'limitF' can be provided to limit grouped
...
```



# <a name="apidoc.module.baconjs.Event"></a>[module baconjs.Event](#apidoc.module.baconjs.Event)

#### <a name="apidoc.element.baconjs.Event.Event"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Event ()](#apidoc.element.baconjs.Event.Event)
- description and source-code
```javascript
function Event() {
  this.id = ++eventIdCounter;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.baconjs.Event.prototype"></a>[module baconjs.Event.prototype](#apidoc.module.baconjs.Event.prototype)

#### <a name="apidoc.element.baconjs.Event.prototype.filter"></a>[function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>filter ()](#apidoc.element.baconjs.Event.prototype.filter)
- description and source-code
```javascript
filter = function () {
  return true;
}
```
- example usage
```shell
...
<a name="observable-mapend"></a>
['observable.mapEnd(f)'](#observable-mapend "observable.mapEnd(@ : Observable[A], f : -> Observable[A]) : Observable[A]") Adds an
 extra ['Next'](#bacon-next) event just before End. The value is created
by calling the given function when the source stream ends. Instead of a
function, a static value can be used. You can omit the argument to
produce a Next event with 'undefined' value.

<a name="observable-filter"></a>
['observable.filter(f)'](#observable-filter "observable.filter(@ : Observable[A], f : A -> Bool) : Observable[A]") filters values
 using given predicate function.
Instead of a function, you can use a constant value ('true' to include all, 'false' to exclude all) or a
property extractor string (like ".isValuable") instead. Just like with
['map'](#observable-map), indeed.

<a name="observable-filter-property"></a>
['observable.filter(property)'](#observable-filter-property "observable.filter(property)") filters values based on the value of
a
property. Event will be included in output [if and only if](http://en.wikipedia.org/wiki/If_and_only_if) the property holds 'true
'
...
```

#### <a name="apidoc.element.baconjs.Event.prototype.hasValue"></a>[function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>hasValue ()](#apidoc.element.baconjs.Event.prototype.hasValue)
- description and source-code
```javascript
hasValue = function () {
  return false;
}
```
- example usage
```shell
...
returns an array containing the next state and an array of output
events. Here's an example where we calculate the total sum of all
numbers in the stream and output the value on stream end:

'''js
Bacon.fromArray([1,2,3])
  .withStateMachine(0, function(sum, event) {
    if (event.hasValue())
      return [sum + event.value(), []]
    else if (event.isEnd())
      return [undefined, [new Bacon.Next(sum), event]]
    else
      return [sum, [event]]
  })
'''
...
```

#### <a name="apidoc.element.baconjs.Event.prototype.inspect"></a>[function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>inspect ()](#apidoc.element.baconjs.Event.prototype.inspect)
- description and source-code
```javascript
inspect = function () {
  return this.toString();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Event.prototype.isEnd"></a>[function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>isEnd ()](#apidoc.element.baconjs.Event.prototype.isEnd)
- description and source-code
```javascript
isEnd = function () {
  return false;
}
```
- example usage
```shell
...
numbers in the stream and output the value on stream end:

'''js
Bacon.fromArray([1,2,3])
  .withStateMachine(0, function(sum, event) {
    if (event.hasValue())
      return [sum + event.value(), []]
    else if (event.isEnd())
      return [undefined, [new Bacon.Next(sum), event]]
    else
      return [sum, [event]]
  })
'''

<a name="observable-decode"></a>
...
```

#### <a name="apidoc.element.baconjs.Event.prototype.isError"></a>[function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>isError ()](#apidoc.element.baconjs.Event.prototype.isError)
- description and source-code
```javascript
isError = function () {
  return false;
}
```
- example usage
```shell
...
<a name="event-isnext"></a>
['event.isNext()'](#event-isnext "event.isNext(@ : Event[A]) : Bool") true for Next events

<a name="event-isinitial"></a>
['event.isInitial()'](#event-isinitial "event.isInitial(@ : Event[A]) : Bool") true for Initial events

<a name="event-iserror"></a>
['event.isError()'](#event-iserror "event.isError()") true for Error events

<a name="event-isend"></a>
['event.isEnd()'](#event-isend "event.isEnd()") true for End events

<a name="event-error"></a>
['event.error'](#event-error "event.error") the error value of Error events
...
```

#### <a name="apidoc.element.baconjs.Event.prototype.isEvent"></a>[function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>isEvent ()](#apidoc.element.baconjs.Event.prototype.isEvent)
- description and source-code
```javascript
isEvent = function () {
  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Event.prototype.isInitial"></a>[function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>isInitial ()](#apidoc.element.baconjs.Event.prototype.isInitial)
- description and source-code
```javascript
isInitial = function () {
  return false;
}
```
- example usage
```shell
...
<a name="event-hasvalue"></a>
['event.hasValue()'](#event-hasvalue "event.hasValue(@ : Event[A]) : Bool") returns true for events of type Initial and Next

<a name="event-isnext"></a>
['event.isNext()'](#event-isnext "event.isNext(@ : Event[A]) : Bool") true for Next events

<a name="event-isinitial"></a>
['event.isInitial()'](#event-isinitial "event.isInitial(@ : Event[A]) : Bool") true for Initial events

<a name="event-iserror"></a>
['event.isError()'](#event-iserror "event.isError()") true for Error events

<a name="event-isend"></a>
['event.isEnd()'](#event-isend "event.isEnd()") true for End events
...
```

#### <a name="apidoc.element.baconjs.Event.prototype.isNext"></a>[function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>isNext ()](#apidoc.element.baconjs.Event.prototype.isNext)
- description and source-code
```javascript
isNext = function () {
  return false;
}
```
- example usage
```shell
...
<a name="event-value"></a>
['event.value()'](#event-value "event.value(@ : Event[A]) : A") returns the value associated with a Next or Initial event

<a name="event-hasvalue"></a>
['event.hasValue()'](#event-hasvalue "event.hasValue(@ : Event[A]) : Bool") returns true for events of type Initial and Next

<a name="event-isnext"></a>
['event.isNext()'](#event-isnext "event.isNext(@ : Event[A]) : Bool") true for Next events

<a name="event-isinitial"></a>
['event.isInitial()'](#event-isinitial "event.isInitial(@ : Event[A]) : Bool") true for Initial events

<a name="event-iserror"></a>
['event.isError()'](#event-iserror "event.isError()") true for Error events
...
```

#### <a name="apidoc.element.baconjs.Event.prototype.log"></a>[function <span class="apidocSignatureSpan">baconjs.Event.prototype.</span>log ()](#apidoc.element.baconjs.Event.prototype.log)
- description and source-code
```javascript
log = function () {
  return this.toString();
}
```
- example usage
```shell
...
passed to the function. These arguments can be simple variables, Bacon
EventStreams or Properties. For example the following will output "Bacon rules":

'''js
bacon = Bacon.constant('bacon')
Bacon.fromCallback(function(a, b, callback) {
  callback(a + ' ' + b);
}, bacon, 'rules').log();
'''

<a name="bacon-fromcallback-object"></a>
['Bacon.fromCallback(object, methodName [, args...])'](#bacon-fromcallback-object "Bacon.fromCallback(object, methodName [, args
...]) : EventStream[A]") a variant of fromCallback which calls the named method of a given object.

<a name="bacon-fromnodecallback"></a>
['Bacon.fromNodeCallback(f [, args...])'](#bacon-fromnodecallback "Bacon.fromNodeCallback(f : (E -> A -> void) -> void [, args...]) :
EventStream[A]") behaves the same way as ['Bacon.fromCallback'](#bacon-fromcallback),
...
```



# <a name="apidoc.module.baconjs.EventStream"></a>[module baconjs.EventStream](#apidoc.module.baconjs.EventStream)

#### <a name="apidoc.element.baconjs.EventStream.EventStream"></a>[function <span class="apidocSignatureSpan">baconjs.</span>EventStream (desc, subscribe, handler)](#apidoc.element.baconjs.EventStream.EventStream)
- description and source-code
```javascript
function EventStream(desc, subscribe, handler) {
  if (!(this instanceof EventStream)) {
    return new EventStream(desc, subscribe, handler);
  }
  if (_.isFunction(desc)) {
    handler = subscribe;
    subscribe = desc;
    desc = Desc.empty;
  }
  Observable.call(this, desc);
  assertFunction(subscribe);
  this.dispatcher = new Dispatcher(subscribe, handler);
  registerObs(this);
}
```
- example usage
```shell
...
['Bacon.never()'](#bacon-never "Bacon.never() : EventStream") creates an EventStream that immediately ends.

<a name="bacon-later"></a>
['Bacon.later(delay, value)'](#bacon-later "Bacon.later(delay : Number, value : A) : EventStream[A]") creates a single-element stream
 that
produces given value after given delay (milliseconds).

<a name="new-bacon-eventstream"></a>
['new Bacon.EventStream(subscribe)'](#new-bacon-eventstream "new Bacon.EventStream(subscribe)") creates an ['EventStream'](#eventstream
) with the given subscribe function.

['property.changes'](#property-changes) creates a stream of changes to the ['Property'](#property). The stream *does not* include
an event for the current value of the Property at the time this method was called.

<a name="property-toeventstream"></a>
['property.toEventStream()'](#property-toeventstream "property.toEventStream(@ : Property[A]) : EventStream[A]") creates an EventStream
 based on this Property. The stream contains also an event for the current
value of this Property at the time this method was called.
...
```



# <a name="apidoc.module.baconjs.EventStream.prototype"></a>[module baconjs.EventStream.prototype](#apidoc.module.baconjs.EventStream.prototype)

#### <a name="apidoc.element.baconjs.EventStream.prototype.buffer"></a>[function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>buffer (delay)](#apidoc.element.baconjs.EventStream.prototype.buffer)
- description and source-code
```javascript
buffer = function (delay) {
  var onInput = arguments.length <= 1 || arguments[1] === undefined ? nop : arguments[1];
  var onFlush = arguments.length <= 2 || arguments[2] === undefined ? nop : arguments[2];

  var buffer = {
    scheduled: null,
    end: undefined,
    values: [],
    flush: function () {
      if (this.scheduled) {
        Bacon.scheduler.clearTimeout(this.scheduled);
        this.scheduled = null;
      }
      if (this.values.length > 0) {
        var valuesToPush = this.values;
        this.values = [];
        var reply = this.push(nextEvent(valuesToPush));
        if (this.end != null) {
          return this.push(this.end);
        } else if (reply !== Bacon.noMore) {
          return onFlush(this);
        }
      } else {
        if (this.end != null) {
          return this.push(this.end);
        }
      }
    },
    schedule: function () {
      var _this6 = this;

      if (!this.scheduled) {
        return this.scheduled = delay(function () {
          return _this6.flush();
        });
      }
    }
  };
  var reply = Bacon.more;
  if (!_.isFunction(delay)) {
    var delayMs = delay;
    delay = function (f) {
      return Bacon.scheduler.setTimeout(f, delayMs);
    };
  }
  return withDesc(new Bacon.Desc(this, "buffer", []), this.withHandler(function (event) {
    var _this7 = this;

    buffer.push = function (event) {
      return _this7.push(event);
    };
    if (event.isError()) {
      reply = this.push(event);
    } else if (event.isEnd()) {
      buffer.end = event;
      if (!buffer.scheduled) {
        buffer.flush();
      }
    } else {
      buffer.values.push(event.value());

      onInput(buffer);
    }
    return reply;
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.EventStream.prototype.bufferWithCount"></a>[function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>bufferWithCount (count)](#apidoc.element.baconjs.EventStream.prototype.bufferWithCount)
- description and source-code
```javascript
bufferWithCount = function (count) {
  return withDesc(new Bacon.Desc(this, "bufferWithCount", [count]), this.bufferWithTimeOrCount(undefined, count));
}
```
- example usage
```shell
...
stream.bufferWithTime(10):

'''js
stream.bufferWithTime(function(f) { setTimeout(f, 10) })
'''

<a name="stream-bufferwithcount"></a>
['stream.bufferWithCount(count)'](#stream-bufferwithcount "stream.bufferWithCount(count)") buffers stream events with given count
.
The buffer is flushed when it contains the given number of elements. So, if
you buffer a stream of '[1, 2, 3, 4, 5]' with count '2', you'll get output
events with values '[1, 2]', '[3, 4]' and '[5]'.

<a name="stream-bufferwithtimeorcount"></a>
['stream.bufferWithTimeOrCount(delay, count)'](#stream-bufferwithtimeorcount "stream.bufferWithTimeOrCount(delay, count)") buffers
 stream events and
flushes when either the buffer contains the given number elements or the
...
```

#### <a name="apidoc.element.baconjs.EventStream.prototype.bufferWithTime"></a>[function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>bufferWithTime (delay)](#apidoc.element.baconjs.EventStream.prototype.bufferWithTime)
- description and source-code
```javascript
bufferWithTime = function (delay) {
  return withDesc(new Bacon.Desc(this, "bufferWithTime", [delay]), this.bufferWithTimeOrCount(delay, Number.MAX_VALUE));
}
```
- example usage
```shell
...

<a name="stream-skipuntil"></a>
['stream.skipUntil(stream2)'](#stream-skipuntil "stream.skipUntil(stream2)") skips elements from 'stream' until a Next event
appears in 'stream2'. In other words, starts delivering values
from 'stream' after first event appears in 'stream2'.

<a name="stream-bufferwithtime"></a>
['stream.bufferWithTime(delay)'](#stream-bufferwithtime "stream.bufferWithTime(delay)") buffers stream events with given delay.
The buffer is flushed at most once in the given delay. So, if your input
contains [1,2,3,4,5,6,7], then you might get two events containing [1,2,3,4]
and [5,6,7] respectively, given that the flush occurs between numbers 4 and 5.

<a name="stream-bufferwithtime-f"></a>
['stream.bufferWithTime(f)'](#stream-bufferwithtime-f "stream.bufferWithTime(f)") works with a given "defer-function" instead
of a delay. Here's a simple example, which is equivalent to
...
```

#### <a name="apidoc.element.baconjs.EventStream.prototype.bufferWithTimeOrCount"></a>[function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>bufferWithTimeOrCount (delay, count)](#apidoc.element.baconjs.EventStream.prototype.bufferWithTimeOrCount)
- description and source-code
```javascript
bufferWithTimeOrCount = function (delay, count) {
  var flushOrSchedule = function (buffer) {
    if (buffer.values.length === count) {
      return buffer.flush();
    } else if (delay !== undefined) {
      return buffer.schedule();
    }
  };
  var desc = new Bacon.Desc(this, "bufferWithTimeOrCount", [delay, count]);
  return withDesc(desc, this.buffer(delay, flushOrSchedule, flushOrSchedule));
}
```
- example usage
```shell
...
<a name="stream-bufferwithcount"></a>
['stream.bufferWithCount(count)'](#stream-bufferwithcount "stream.bufferWithCount(count)") buffers stream events with given count
.
The buffer is flushed when it contains the given number of elements. So, if
you buffer a stream of '[1, 2, 3, 4, 5]' with count '2', you'll get output
events with values '[1, 2]', '[3, 4]' and '[5]'.

<a name="stream-bufferwithtimeorcount"></a>
['stream.bufferWithTimeOrCount(delay, count)'](#stream-bufferwithtimeorcount "stream.bufferWithTimeOrCount(delay, count)") buffers
 stream events and
flushes when either the buffer contains the given number elements or the
given amount of milliseconds has passed since last buffered event.

<a name="stream-toproperty"></a>
['stream.toProperty()'](#stream-toproperty "stream.toProperty(@ : EventStream[A]) : Property[A]") creates a Property based on the
EventStream. Without arguments, you'll get a Property without an initial value.
The Property will get its first actual value from the stream, and after that it'll
...
```

#### <a name="apidoc.element.baconjs.EventStream.prototype.concat"></a>[function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>concat (right)](#apidoc.element.baconjs.EventStream.prototype.concat)
- description and source-code
```javascript
concat = function (right) {
  var left = this;
  return new EventStream(new Bacon.Desc(left, "concat", [right]), function (sink) {
    var unsubRight = nop;
    var unsubLeft = left.dispatcher.subscribe(function (e) {
      if (e.isEnd()) {
        unsubRight = right.dispatcher.subscribe(sink);
        return unsubRight;
      } else {
        return sink(e);
      }
    });
    return function () {
      return unsubLeft(), unsubRight();
    };
  });
}
```
- example usage
```shell
...
EventStream
-----------

<a name="bacon-eventstream"></a>
['Bacon.EventStream'](#bacon-eventstream "Bacon.EventStream") a stream of events. See methods below.

<a name="stream-concat"></a>
['stream.concat(otherStream)'](#stream-concat "stream.concat(otherStream)") concatenates two streams into one stream so that
it will deliver events from 'stream' until it ends and then deliver
events from 'otherStream'. This means too that events from 'stream2',
occurring before the end of 'stream' will not be included in the result
stream.

<a name="stream-merge"></a>
['stream.merge(otherStream)'](#stream-merge "stream.merge(otherStream)") merges two streams into one stream that delivers events
 from both
...
```

#### <a name="apidoc.element.baconjs.EventStream.prototype.delayChanges"></a>[function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>delayChanges (desc, f)](#apidoc.element.baconjs.EventStream.prototype.delayChanges)
- description and source-code
```javascript
delayChanges = function (desc, f) {
  return withDesc(desc, f(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.EventStream.prototype.flatScan"></a>[function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>flatScan (seed, f)](#apidoc.element.baconjs.EventStream.prototype.flatScan)
- description and source-code
```javascript
flatScan = function (seed, f) {
  var current = seed;
  return this.flatMapConcat(function (next) {
    return makeObservable(f(current, next)).doAction(function (updated) {
      return current = updated;
    });
  }).toProperty(seed);
}
```
- example usage
```shell
...

<a name="stream-toproperty-initialValue"></a>
['stream.toProperty(initialValue)'](#stream-toproperty-initialValue "stream.toProperty(initialValue)") creates a Property based
on the
EventStream with the given initial value that will be used as the current value until
the first value comes from the stream.

<a name="stream-flatscan"></a>
['stream.flatScan(seed, f)'](#stream-flatscan "stream.flatScan(seed, f) : Property[A]") scans stream with given seed value and accumulator
 function, resulting to a Property.
Difference to ['scan'](#observable-scan) is that the function 'f' can return an ['EventStream'](#eventstream) or a ['Property'](#
property) instead
of a pure value, meaning that you can use ['flatScan'](#stream-flatscan) for asynchronous updates of state. It serializes
updates so that that the next update will be queued until the previous one has completed.

Property
--------
...
```

#### <a name="apidoc.element.baconjs.EventStream.prototype.holdWhen"></a>[function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>holdWhen (valve)](#apidoc.element.baconjs.EventStream.prototype.holdWhen)
- description and source-code
```javascript
holdWhen = function (valve) {
  var onHold = false;
  var bufferedValues = [];
  var src = this;
  var srcIsEnded = false;
  return new EventStream(new Bacon.Desc(this, "holdWhen", [valve]), function (sink) {
    var composite = new CompositeUnsubscribe();
    var subscribed = false;
    var endIfBothEnded = function (unsub) {
      if (typeof unsub === "function") {
        unsub();
      }
      if (composite.empty() && subscribed) {
        return sink(endEvent());
      }
    };
    composite.add(function (unsubAll, unsubMe) {
      return valve.subscribeInternal(function (event) {
        if (event.hasValue()) {
          onHold = event.value();
          if (!onHold) {
            var toSend = bufferedValues;
            bufferedValues = [];
            return (function () {
              var result = [];
              for (var i = 0, value; i < toSend.length; i++) {
                value = toSend[i];
                result.push(sink(nextEvent(value)));
              }
              if (srcIsEnded) {
                result.push(sink(endEvent()));
                unsubMe();
              }
              return result;
            })();
          }
        } else if (event.isEnd()) {
          return endIfBothEnded(unsubMe);
        } else {
          return sink(event);
        }
      });
    });
    composite.add(function (unsubAll, unsubMe) {
      return src.subscribeInternal(function (event) {
        if (onHold && event.hasValue()) {
          return bufferedValues.push(event.value());
        } else if (event.isEnd() && bufferedValues.length) {
          srcIsEnded = true;
          return endIfBothEnded(unsubMe);
        } else {
          return sink(event);
        }
      });
    });
    subscribed = true;
    endIfBothEnded();
    return composite.unsubscribe;
  });
}
```
- example usage
```shell
...
occurring before the end of 'stream' will not be included in the result
stream.

<a name="stream-merge"></a>
['stream.merge(otherStream)'](#stream-merge "stream.merge(otherStream)") merges two streams into one stream that delivers events
 from both

<a name="stream-holdwhen"></a>
['stream.holdWhen(valve)'](#stream-holdwhen "stream.holdWhen(@ : EventStream[A], valve : Observable[B]) : EventStream[A]") pauses
 and buffers the event stream if last event in valve is truthy.
All buffered events are released when valve becomes falsy.

<a name="stream-startwith"></a>
['stream.startWith(value)'](#stream-startwith "stream.startWith(value)") adds a starting value to the stream, i.e. concats a
single-element stream contains ['value'](#event-value) with this stream.

<a name="stream-skipwhile"></a>
...
```

#### <a name="apidoc.element.baconjs.EventStream.prototype.merge"></a>[function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>merge (right)](#apidoc.element.baconjs.EventStream.prototype.merge)
- description and source-code
```javascript
merge = function (right) {
  assertEventStream(right);
  var left = this;
  return withDesc(new Bacon.Desc(left, "merge", [right]), Bacon.mergeAll(this, right));
}
```
- example usage
```shell
...
filter and combine these streams in a multitude of ways (see API below). The methods ['map'](#observable-map),
['filter'](#observable-filter), for example, are similar to same functions in functional list programming
(like [Underscore](http://underscorejs.org/)). So, if you say

'''js
var plus = $("#plus").asEventStream("click").map(1)
var minus = $("#minus").asEventStream("click").map(-1)
var both = plus.merge(minus)
'''

.. you'll have a stream that will output the number 1 when the "plus" button is clicked
and another stream outputting -1 when the "minus" button is clicked. The 'both' stream will
be a merged stream containing events from both the plus and minus streams. This allows
you to subscribe to both streams with one handler:
...
```

#### <a name="apidoc.element.baconjs.EventStream.prototype.sampledBy"></a>[function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>sampledBy (sampler, combinator)](#apidoc.element.baconjs.EventStream.prototype.sampledBy)
- description and source-code
```javascript
sampledBy = function (sampler, combinator) {
  return withDesc(new Bacon.Desc(this, "sampledBy", [sampler, combinator]), this.toProperty().sampledBy(sampler, combinator));
}
```
- example usage
```shell
...
the input values. If keyCode was a function, the result stream would
contain the values returned by the function.
The [Function Construction rules](#function-construction-rules) below apply here.
The ['map'](#observable-map) method, among many others, uses [lazy evaluation](#lazy-evaluation).

<a name="stream-map"></a>
['stream.map(property)'](#stream-map "stream.map(property)") maps the stream events to the current value of
the given property. This is equivalent to ['property.sampledBy(stream)'](#property-sampledby).

<a name="observable-maperror"></a>
['observable.mapError(f)'](#observable-maperror "observable.mapError(@ : Observable[A], f : E -> A) : Observable[A]") maps errors
 using given function. More
specifically, feeds the "error" field of the error event to the function
and produces a ['Next'](#bacon-next) event based on the return value.
The [Function Construction rules](#function-construction-rules) below apply here.
You can omit the argument to produce a ['Next'](#bacon-next) event with 'undefined' value.
...
```

#### <a name="apidoc.element.baconjs.EventStream.prototype.skipUntil"></a>[function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>skipUntil (starter)](#apidoc.element.baconjs.EventStream.prototype.skipUntil)
- description and source-code
```javascript
skipUntil = function (starter) {
  var started = starter.take(1).map(true).toProperty(false);
  return withDesc(new Bacon.Desc(this, "skipUntil", [starter]), this.filter(started));
}
```
- example usage
```shell
...
The [Function Construction rules](#function-construction-rules) below apply here.

<a name="stream-skipwhile-property"></a>
['stream.skipWhile(property)'](#stream-skipwhile-property "stream.skipWhile(property)") skips elements until the value of the given
 Property is falsy once, and then
lets all events pass through.

<a name="stream-skipuntil"></a>
['stream.skipUntil(stream2)'](#stream-skipuntil "stream.skipUntil(stream2)") skips elements from 'stream' until a Next event
appears in 'stream2'. In other words, starts delivering values
from 'stream' after first event appears in 'stream2'.

<a name="stream-bufferwithtime"></a>
['stream.bufferWithTime(delay)'](#stream-bufferwithtime "stream.bufferWithTime(delay)") buffers stream events with given delay.
The buffer is flushed at most once in the given delay. So, if your input
contains [1,2,3,4,5,6,7], then you might get two events containing [1,2,3,4]
...
```

#### <a name="apidoc.element.baconjs.EventStream.prototype.skipWhile"></a>[function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>skipWhile (f)](#apidoc.element.baconjs.EventStream.prototype.skipWhile)
- description and source-code
```javascript
skipWhile = function (f) {
  assertObservableIsProperty(f);
  var ok = false;

  for (var _len19 = arguments.length, args = Array(_len19 > 1 ? _len19 - 1 : 0), _key19 = 1; _key19 < _len19; _key19++) {
    args[_key19 - 1] = arguments[_key19];
  }

  return convertArgsToFunction(this, f, args, function (f) {
    return withDesc(new Bacon.Desc(this, "skipWhile", [f]), this.withHandler(function (event) {
      if (ok || !event.hasValue() || !f(event.value())) {
        if (event.hasValue()) {
          ok = true;
        }
        return this.push(event);
      } else {
        return Bacon.more;
      }
    }));
  });
}
```
- example usage
```shell
...
All buffered events are released when valve becomes falsy.

<a name="stream-startwith"></a>
['stream.startWith(value)'](#stream-startwith "stream.startWith(value)") adds a starting value to the stream, i.e. concats a
single-element stream contains ['value'](#event-value) with this stream.

<a name="stream-skipwhile"></a>
['stream.skipWhile(f)'](#stream-skipwhile "stream.skipWhile(f)") skips elements until the given predicate function returns falsy
 once, and then
lets all events pass through.
The [Function Construction rules](#function-construction-rules) below apply here.

<a name="stream-skipwhile-property"></a>
['stream.skipWhile(property)'](#stream-skipwhile-property "stream.skipWhile(property)") skips elements until the value of the given
 Property is falsy once, and then
lets all events pass through.
...
```

#### <a name="apidoc.element.baconjs.EventStream.prototype.startWith"></a>[function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>startWith (seed)](#apidoc.element.baconjs.EventStream.prototype.startWith)
- description and source-code
```javascript
startWith = function (seed) {
  return withDesc(new Bacon.Desc(this, "startWith", [seed]), Bacon.once(seed).concat(this));
}
```
- example usage
```shell
...
['stream.merge(otherStream)'](#stream-merge "stream.merge(otherStream)") merges two streams into one stream that delivers events
 from both

<a name="stream-holdwhen"></a>
['stream.holdWhen(valve)'](#stream-holdwhen "stream.holdWhen(@ : EventStream[A], valve : Observable[B]) : EventStream[A]") pauses
 and buffers the event stream if last event in valve is truthy.
All buffered events are released when valve becomes falsy.

<a name="stream-startwith"></a>
['stream.startWith(value)'](#stream-startwith "stream.startWith(value)") adds a starting value to the stream, i.e. concats a
single-element stream contains ['value'](#event-value) with this stream.

<a name="stream-skipwhile"></a>
['stream.skipWhile(f)'](#stream-skipwhile "stream.skipWhile(f)") skips elements until the given predicate function returns falsy
 once, and then
lets all events pass through.
The [Function Construction rules](#function-construction-rules) below apply here.
...
```

#### <a name="apidoc.element.baconjs.EventStream.prototype.takeUntil"></a>[function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>takeUntil (stopper)](#apidoc.element.baconjs.EventStream.prototype.takeUntil)
- description and source-code
```javascript
takeUntil = function (stopper) {
  var endMarker = {};
  return withDesc(new Bacon.Desc(this, "takeUntil", [stopper]), Bacon.groupSimultaneous(this.mapEnd(endMarker), stopper.skipErrors
()).withHandler(function (event) {
    if (!event.hasValue()) {
      return this.push(event);
    } else {
      var _event$value = event.value();

      var data = _event$value[0];
      var stopper = _event$value[1];

      if (stopper.length) {
        return this.push(endEvent());
      } else {
        var reply = Bacon.more;
        for (var i = 0, value; i < data.length; i++) {
          value = data[i];
          if (value === endMarker) {
            reply = this.push(endEvent());
          } else {
            reply = this.push(nextEvent(value));
          }
        }
        return reply;
      }
    }
  }));
}
```
- example usage
```shell
...

<a name="observable-take"></a>
['observable.take(n)'](#observable-take "observable.take(@ : Observable[A], n : Number) : Observable[A]") takes at most n values
 from the stream and then ends the stream. If the stream has
fewer than n values then it is unaffected.
Equal to ['Bacon.never()'](#bacon-never) if 'n <= 0'.

<a name="observable-takeuntil"></a>
['observable.takeUntil(stream)'](#observable-takeuntil "observable.takeUntil(@ : Observable[A], stream : EventStream[B]) : Observable
[A]") takes elements from source until a Next event appears in the other stream.
If other stream ends without value, it is ignored.

<a name="observable-takewhile"></a>
['observable.takeWhile(f)'](#observable-takewhile "observable.takeWhile(@ : Observable[A], f : A -> Bool) : Observable[A]") takes
 while given predicate function holds true, and then ends.
[Function Construction rules](#function-construction-rules) apply.

<a name="observable-takewhile-property"></a>
...
```

#### <a name="apidoc.element.baconjs.EventStream.prototype.toEventStream"></a>[function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>toEventStream ()](#apidoc.element.baconjs.EventStream.prototype.toEventStream)
- description and source-code
```javascript
toEventStream = function () {
  return this;
}
```
- example usage
```shell
...
<a name="new-bacon-eventstream"></a>
['new Bacon.EventStream(subscribe)'](#new-bacon-eventstream "new Bacon.EventStream(subscribe)") creates an ['EventStream'](#eventstream
) with the given subscribe function.

['property.changes'](#property-changes) creates a stream of changes to the ['Property'](#property). The stream *does not* include
an event for the current value of the Property at the time this method was called.

<a name="property-toeventstream"></a>
['property.toEventStream()'](#property-toeventstream "property.toEventStream(@ : Property[A]) : EventStream[A]") creates an EventStream
 based on this Property. The stream contains also an event for the current
value of this Property at the time this method was called.

['new Bacon.Bus()'](#new-bacon-bus) creates a pushable/pluggable stream (see [Bus](#bus) section below)

Pro tip: you can also put Errors into streams created with the
constructors above, by using an ['Bacon.Error'](#bacon-error) object instead of a plain
value.
...
```

#### <a name="apidoc.element.baconjs.EventStream.prototype.toProperty"></a>[function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>toProperty (initValue_)](#apidoc.element.baconjs.EventStream.prototype.toProperty)
- description and source-code
```javascript
toProperty = function (initValue_) {
  var initValue = arguments.length === 0 ? None : toOption(function () {
    return initValue_;
  });
  var disp = this.dispatcher;
  var desc = new Bacon.Desc(this, "toProperty", [initValue_]);
  return new Property(desc, function (sink) {
    var initSent = false;
    var subbed = false;
    var unsub = nop;
    var reply = Bacon.more;
    var sendInit = function () {
      if (!initSent) {
        return initValue.forEach(function (value) {
          initSent = true;
          reply = sink(new Initial(value));
          if (reply === Bacon.noMore) {
            unsub();
            unsub = nop;
            return nop;
          }
        });
      }
    };

    unsub = disp.subscribe(function (event) {
      if (event.hasValue()) {
        if (event.isInitial() && !subbed) {
          initValue = new Some(function () {
            return event.value();
          });
          return Bacon.more;
        } else {
          if (!event.isInitial()) {
            sendInit();
          }
          initSent = true;
          initValue = new Some(event);
          return sink(event);
        }
      } else {
        if (event.isEnd()) {
          reply = sendInit();
        }
        if (reply !== Bacon.noMore) {
          return sink(event);
        }
      }
    });
    subbed = true;
    sendInit();
    return unsub;
  });
}
```
- example usage
```shell
...

<a name="stream-bufferwithtimeorcount"></a>
['stream.bufferWithTimeOrCount(delay, count)'](#stream-bufferwithtimeorcount "stream.bufferWithTimeOrCount(delay, count)") buffers
 stream events and
flushes when either the buffer contains the given number elements or the
given amount of milliseconds has passed since last buffered event.

<a name="stream-toproperty"></a>
['stream.toProperty()'](#stream-toproperty "stream.toProperty(@ : EventStream[A]) : Property[A]") creates a Property based on the
EventStream. Without arguments, you'll get a Property without an initial value.
The Property will get its first actual value from the stream, and after that it'll
always have a current value.

<a name="stream-toproperty-initialValue"></a>
['stream.toProperty(initialValue)'](#stream-toproperty-initialValue "stream.toProperty(initialValue)") creates a Property based
on the
EventStream with the given initial value that will be used as the current value until
...
```

#### <a name="apidoc.element.baconjs.EventStream.prototype.withHandler"></a>[function <span class="apidocSignatureSpan">baconjs.EventStream.prototype.</span>withHandler (handler)](#apidoc.element.baconjs.EventStream.prototype.withHandler)
- description and source-code
```javascript
withHandler = function (handler) {
  return new EventStream(new Bacon.Desc(this, "withHandler", [handler]), this.dispatcher.subscribe, handler);
}
```
- example usage
```shell
...
<a name="observable-endonerror-f"></a>
['observable.endOnError(f)'](#observable-endonerror-f "observable.endOnError(f)") ends the 'Observable' on first ['Error'](#bacon
-error) event for which
the given predicate function returns true. The error is included in the
output of the returned 'Observable'. The [Function Construction rules](#function-construction-rules) apply, so
you can do for example '.endOnError(".serious")'.

<a name="observable-withhandler"></a>
['observable.withHandler(f)'](#observable-withhandler "observable.withHandler(f)") lets you do more custom event handling: you
get all events to your function and you can output any number of events
and end the stream if you choose. For example, to send an error and end
the stream in case a value is below zero:

'''js
if (event.hasValue() && event.value() < 0) {
this.push(new Bacon.Error("Value below zero"));
...
```



# <a name="apidoc.module.baconjs.Initial"></a>[module baconjs.Initial](#apidoc.module.baconjs.Initial)

#### <a name="apidoc.element.baconjs.Initial.Initial"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Initial (valueF, eager)](#apidoc.element.baconjs.Initial.Initial)
- description and source-code
```javascript
function Initial(valueF, eager) {
  if (!(this instanceof Initial)) {
    return new Initial(valueF, eager);
  }
  Next.call(this, valueF, eager);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.baconjs.Initial.prototype"></a>[module baconjs.Initial.prototype](#apidoc.module.baconjs.Initial.prototype)

#### <a name="apidoc.element.baconjs.Initial.prototype.apply"></a>[function <span class="apidocSignatureSpan">baconjs.Initial.prototype.</span>apply (value)](#apidoc.element.baconjs.Initial.prototype.apply)
- description and source-code
```javascript
apply = function (value) {
  return new Initial(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Initial.prototype.isInitial"></a>[function <span class="apidocSignatureSpan">baconjs.Initial.prototype.</span>isInitial ()](#apidoc.element.baconjs.Initial.prototype.isInitial)
- description and source-code
```javascript
isInitial = function () {
  return true;
}
```
- example usage
```shell
...
<a name="event-hasvalue"></a>
['event.hasValue()'](#event-hasvalue "event.hasValue(@ : Event[A]) : Bool") returns true for events of type Initial and Next

<a name="event-isnext"></a>
['event.isNext()'](#event-isnext "event.isNext(@ : Event[A]) : Bool") true for Next events

<a name="event-isinitial"></a>
['event.isInitial()'](#event-isinitial "event.isInitial(@ : Event[A]) : Bool") true for Initial events

<a name="event-iserror"></a>
['event.isError()'](#event-iserror "event.isError()") true for Error events

<a name="event-isend"></a>
['event.isEnd()'](#event-isend "event.isEnd()") true for End events
...
```

#### <a name="apidoc.element.baconjs.Initial.prototype.isNext"></a>[function <span class="apidocSignatureSpan">baconjs.Initial.prototype.</span>isNext ()](#apidoc.element.baconjs.Initial.prototype.isNext)
- description and source-code
```javascript
isNext = function () {
  return false;
}
```
- example usage
```shell
...
<a name="event-value"></a>
['event.value()'](#event-value "event.value(@ : Event[A]) : A") returns the value associated with a Next or Initial event

<a name="event-hasvalue"></a>
['event.hasValue()'](#event-hasvalue "event.hasValue(@ : Event[A]) : Bool") returns true for events of type Initial and Next

<a name="event-isnext"></a>
['event.isNext()'](#event-isnext "event.isNext(@ : Event[A]) : Bool") true for Next events

<a name="event-isinitial"></a>
['event.isInitial()'](#event-isinitial "event.isInitial(@ : Event[A]) : Bool") true for Initial events

<a name="event-iserror"></a>
['event.isError()'](#event-iserror "event.isError()") true for Error events
...
```

#### <a name="apidoc.element.baconjs.Initial.prototype.toNext"></a>[function <span class="apidocSignatureSpan">baconjs.Initial.prototype.</span>toNext ()](#apidoc.element.baconjs.Initial.prototype.toNext)
- description and source-code
```javascript
toNext = function () {
  return new Next(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.baconjs.Next"></a>[module baconjs.Next](#apidoc.module.baconjs.Next)

#### <a name="apidoc.element.baconjs.Next.Next"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Next (valueF, eager)](#apidoc.element.baconjs.Next.Next)
- description and source-code
```javascript
function Next(valueF, eager) {
  if (!(this instanceof Next)) {
    return new Next(valueF, eager);
  }

  Event.call(this);

  if (!eager && _.isFunction(valueF) || (valueF != null ? valueF._isNext : void 0)) {
    this.valueF = valueF;
    this.valueInternal = void 0;
  } else {
    this.valueF = void 0;
    this.valueInternal = valueF;
  }
}
```
- example usage
```shell
...
$("#my-div").asEventStream("click", function(event, args) { return args[0] })
'''

<a name="bacon-frompromise"></a>
['Bacon.fromPromise(promise [, abort] [, eventTransformer])'](#bacon-frompromise "Bacon.fromPromise(promise : Promise[A] [, abort
 : boolean][, eventTransformer]) : EventStream[A]") creates an EventStream from a Promise object such as JQuery Ajax.
This stream will contain a single value or an error, followed immediately by stream end.
You can use the optional abort flag (i.e. ´fromPromise(p, true)´ to have the 'abort' method of the given promise be called when
all subscribers have been removed from the created stream.
You can also pass an optional function that transforms the promise value into Events. The default is to transform the value into
 '[new Bacon.Next(value), new Bacon.End()]'.
Check out this [example](https://github.com/raimohanska/baconjs-examples/blob/master/resources/public/index.html).

<a name="bacon-fromevent"></a>
['Bacon.fromEvent(target, eventName [, eventTransformer])'](#bacon-fromevent "Bacon.fromEvent(target : EventTarget | EventEmitter
, eventName : String [, eventTransformer]) : EventStream") creates an EventStream from events
on a DOM EventTarget or Node.JS EventEmitter object, or an object that supports event listeners using 'on'/'off' methods.
You can also pass an optional function that transforms the emitted
events' parameters.
...
```



# <a name="apidoc.module.baconjs.Next.prototype"></a>[module baconjs.Next.prototype](#apidoc.module.baconjs.Next.prototype)

#### <a name="apidoc.element.baconjs.Next.prototype.apply"></a>[function <span class="apidocSignatureSpan">baconjs.Next.prototype.</span>apply (value)](#apidoc.element.baconjs.Next.prototype.apply)
- description and source-code
```javascript
apply = function (value) {
  return new Next(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Next.prototype.filter"></a>[function <span class="apidocSignatureSpan">baconjs.Next.prototype.</span>filter (f)](#apidoc.element.baconjs.Next.prototype.filter)
- description and source-code
```javascript
filter = function (f) {
  return f(this.value());
}
```
- example usage
```shell
...
<a name="observable-mapend"></a>
['observable.mapEnd(f)'](#observable-mapend "observable.mapEnd(@ : Observable[A], f : -> Observable[A]) : Observable[A]") Adds an
 extra ['Next'](#bacon-next) event just before End. The value is created
by calling the given function when the source stream ends. Instead of a
function, a static value can be used. You can omit the argument to
produce a Next event with 'undefined' value.

<a name="observable-filter"></a>
['observable.filter(f)'](#observable-filter "observable.filter(@ : Observable[A], f : A -> Bool) : Observable[A]") filters values
 using given predicate function.
Instead of a function, you can use a constant value ('true' to include all, 'false' to exclude all) or a
property extractor string (like ".isValuable") instead. Just like with
['map'](#observable-map), indeed.

<a name="observable-filter-property"></a>
['observable.filter(property)'](#observable-filter-property "observable.filter(property)") filters values based on the value of
a
property. Event will be included in output [if and only if](http://en.wikipedia.org/wiki/If_and_only_if) the property holds 'true
'
...
```

#### <a name="apidoc.element.baconjs.Next.prototype.fmap"></a>[function <span class="apidocSignatureSpan">baconjs.Next.prototype.</span>fmap (f)](#apidoc.element.baconjs.Next.prototype.fmap)
- description and source-code
```javascript
fmap = function (f) {
  var event, value;
  if (this.valueInternal) {
    value = this.valueInternal;
    return this.apply(function () {
      return f(value);
    });
  } else {
    event = this;
    return this.apply(function () {
      return f(event.value());
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Next.prototype.hasValue"></a>[function <span class="apidocSignatureSpan">baconjs.Next.prototype.</span>hasValue ()](#apidoc.element.baconjs.Next.prototype.hasValue)
- description and source-code
```javascript
hasValue = function () {
  return true;
}
```
- example usage
```shell
...
returns an array containing the next state and an array of output
events. Here's an example where we calculate the total sum of all
numbers in the stream and output the value on stream end:

'''js
Bacon.fromArray([1,2,3])
  .withStateMachine(0, function(sum, event) {
    if (event.hasValue())
      return [sum + event.value(), []]
    else if (event.isEnd())
      return [undefined, [new Bacon.Next(sum), event]]
    else
      return [sum, [event]]
  })
'''
...
```

#### <a name="apidoc.element.baconjs.Next.prototype.isNext"></a>[function <span class="apidocSignatureSpan">baconjs.Next.prototype.</span>isNext ()](#apidoc.element.baconjs.Next.prototype.isNext)
- description and source-code
```javascript
isNext = function () {
  return true;
}
```
- example usage
```shell
...
<a name="event-value"></a>
['event.value()'](#event-value "event.value(@ : Event[A]) : A") returns the value associated with a Next or Initial event

<a name="event-hasvalue"></a>
['event.hasValue()'](#event-hasvalue "event.hasValue(@ : Event[A]) : Bool") returns true for events of type Initial and Next

<a name="event-isnext"></a>
['event.isNext()'](#event-isnext "event.isNext(@ : Event[A]) : Bool") true for Next events

<a name="event-isinitial"></a>
['event.isInitial()'](#event-isinitial "event.isInitial(@ : Event[A]) : Bool") true for Initial events

<a name="event-iserror"></a>
['event.isError()'](#event-iserror "event.isError()") true for Error events
...
```

#### <a name="apidoc.element.baconjs.Next.prototype.log"></a>[function <span class="apidocSignatureSpan">baconjs.Next.prototype.</span>log ()](#apidoc.element.baconjs.Next.prototype.log)
- description and source-code
```javascript
log = function () {
  return this.value();
}
```
- example usage
```shell
...
passed to the function. These arguments can be simple variables, Bacon
EventStreams or Properties. For example the following will output "Bacon rules":

'''js
bacon = Bacon.constant('bacon')
Bacon.fromCallback(function(a, b, callback) {
  callback(a + ' ' + b);
}, bacon, 'rules').log();
'''

<a name="bacon-fromcallback-object"></a>
['Bacon.fromCallback(object, methodName [, args...])'](#bacon-fromcallback-object "Bacon.fromCallback(object, methodName [, args
...]) : EventStream[A]") a variant of fromCallback which calls the named method of a given object.

<a name="bacon-fromnodecallback"></a>
['Bacon.fromNodeCallback(f [, args...])'](#bacon-fromnodecallback "Bacon.fromNodeCallback(f : (E -> A -> void) -> void [, args...]) :
EventStream[A]") behaves the same way as ['Bacon.fromCallback'](#bacon-fromcallback),
...
```

#### <a name="apidoc.element.baconjs.Next.prototype.toString"></a>[function <span class="apidocSignatureSpan">baconjs.Next.prototype.</span>toString ()](#apidoc.element.baconjs.Next.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return _.toString(this.value());
}
```
- example usage
```shell
...
use this data recursively to create a string representation for the observable. This method
is probably useful for Bacon core / library / plugin development only.

For example:

    var src = Bacon.once(1)
    var obs = src.map(function(x) { return -x })
    console.log(obs.toString())
    --> Bacon.once(1).map(function)
    obs.withDescription(src, "times", -1)
    console.log(obs.toString())
    --> Bacon.once(1).times(-1)

<a name="observable-groupby"></a>
['observable.groupBy(keyF [, limitF])'](#observable-groupby "observable.groupBy(@ : Observable[A], keyF[, limitF]) : Observable[
Observable[A]]") Groups stream events to new streams by 'keyF'. Optional 'limitF' can be provided to limit grouped
...
```

#### <a name="apidoc.element.baconjs.Next.prototype.value"></a>[function <span class="apidocSignatureSpan">baconjs.Next.prototype.</span>value ()](#apidoc.element.baconjs.Next.prototype.value)
- description and source-code
```javascript
value = function () {
  var ref;
  if ((ref = this.valueF) != null ? ref._isNext : void 0) {
    this.valueInternal = this.valueF.value();
    this.valueF = void 0;
  } else if (this.valueF) {
    this.valueInternal = this.valueF();
    this.valueF = void 0;
  }
  return this.valueInternal;
}
```
- example usage
```shell
...
events. Here's an example where we calculate the total sum of all
numbers in the stream and output the value on stream end:

'''js
Bacon.fromArray([1,2,3])
  .withStateMachine(0, function(sum, event) {
    if (event.hasValue())
      return [sum + event.value(), []]
    else if (event.isEnd())
      return [undefined, [new Bacon.Next(sum), event]]
    else
      return [sum, [event]]
  })
'''
...
```



# <a name="apidoc.module.baconjs.Observable"></a>[module baconjs.Observable](#apidoc.module.baconjs.Observable)

#### <a name="apidoc.element.baconjs.Observable.Observable"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Observable (desc)](#apidoc.element.baconjs.Observable.Observable)
- description and source-code
```javascript
function Observable(desc) {
  this.desc = desc;
  this.id = ++idCounter;
  this.initialDesc = this.desc;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.baconjs.Observable.prototype"></a>[module baconjs.Observable.prototype](#apidoc.module.baconjs.Observable.prototype)

#### <a name="apidoc.element.baconjs.Observable.prototype.assign"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>assign ()](#apidoc.element.baconjs.Observable.prototype.assign)
- description and source-code
```javascript
assign = function () {
  var f = makeFunctionArgs(arguments);
  return this.subscribe(function (event) {
    if (event.hasValue()) {
      return f(event.value());
    }
  });
}
```
- example usage
```shell
...
seed value and on each event in the source stream applies the accumulator function to the current
property value and the new value from the stream.

Properties can be very conveniently used for assigning values and attributes to DOM elements with JQuery.
Here we assign the value of a property as the text of a span element whenever it changes:

'''js
property.assign($("span"), "text")
'''

Hiding and showing the same span depending on the content of the property value is equally straightforward

'''js
function hiddenForEmptyValue(value) { return value == "" ? "hidden" : "visible" }
property.map(hiddenForEmptyValue).assign($("span"), "css", "visibility")
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.awaiting"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>awaiting (other)](#apidoc.element.baconjs.Observable.prototype.awaiting)
- description and source-code
```javascript
awaiting = function (other) {
  var desc = new Bacon.Desc(this, "awaiting", [other]);
  return withDesc(desc, Bacon.groupSimultaneous(this, other).map(function (values) {
    return values[1].length === 0;
  }).toProperty(false).skipDuplicates());
}
```
- example usage
```shell
...
'''js
property.decode({1 : { type: "mike" }, 2 : { type: "other", whoThen : who }})
'''

The return value of ['decode'](#observable-decode) is always a ['Property'](#property).

<a name="observable-awaiting"></a>
['observable.awaiting(otherObservable)'](#observable-awaiting "observable.awaiting(otherObservable)") creates a Property that indicates
 whether
'observable' is awaiting 'otherObservable', i.e. has produced a value after the latest
value from 'otherObservable'. This is handy for keeping track whether we are
currently awaiting an AJAX response:

'''js
var showAjaxIndicator = ajaxRequest.awaiting(ajaxResponse)
'''
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.bufferingThrottle"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>bufferingThrottle (minimumInterval)](#apidoc.element.baconjs.Observable.prototype.bufferingThrottle)
- description and source-code
```javascript
bufferingThrottle = function (minimumInterval) {
  var desc = new Bacon.Desc(this, "bufferingThrottle", [minimumInterval]);
  return withDesc(desc, this.flatMapConcat(function (x) {
    return Bacon.once(x).concat(Bacon.later(minimumInterval).filter(false));
  }));
}
```
- example usage
```shell
...

'''
source:                      asdf----asdf----
source.debounceImmediate(2): a-d-----a-d-----
'''

<a name="observable-bufferingthrottle"></a>
['observable.bufferingThrottle(minimumInterval)'](#observable-bufferingthrottle "observable.bufferingThrottle(@ : Observable[A],
minimumInterval) : EventStream[A]") throttles the observable using a buffer so that at most one value event in minimumInteval is
 issued.
Unlike ['throttle'](#observable-throttle), it doesn't discard the excessive events but buffers them instead, outputting
them with a rate of at most one value per minimumInterval.

Example:

'''js
var throttled = source.bufferingThrottle(2)
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.combine"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>combine (other, f)](#apidoc.element.baconjs.Observable.prototype.combine)
- description and source-code
```javascript
combine = function (other, f) {
  var combinator = toCombinator(f);
  var desc = new Bacon.Desc(this, "combine", [other, f]);
  return withDesc(desc, Bacon.combineAsArray(this, other).map(function (values) {
    return combinator(values[0], values[1]);
  }));
}
```
- example usage
```shell
...
['observable.doLog()'](#observable-dolog "observable.doLog()") logs each value of the Observable to the console. doLog() behaves
 like ['log'](#observable-log)
but does not subscribe to the event stream. You can think of doLog() as a
logger function that – unlike log() – is safe to use in production. doLog() is
safe, because it does not cause the same surprising side-effects as log()
does.

<a name="observable-combine"></a>
['observable.combine(property2, f)'](#observable-combine "observable.combine(property2, f)") combines the latest values of the two
streams or properties using a two-arg function. Similarly to ['scan'](#observable-scan), you can use a
method name instead, so you could do 'a.combine(b, ".concat")' for two
properties with array value. The result is a Property.

<a name="observable-withstatemachine"></a>
['observable.withStateMachine(initState, f)'](#observable-withstatemachine "observable.withStateMachine(initState, f)") lets you
 run a state machine
on an observable. Give it an initial state object and a state
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.debounce"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>debounce (delay)](#apidoc.element.baconjs.Observable.prototype.debounce)
- description and source-code
```javascript
debounce = function (delay) {
  return this.delayChanges(new Bacon.Desc(this, "debounce", [delay]), function (changes) {
    return changes.flatMapLatest(function (value) {
      return Bacon.later(delay, value);
    });
  });
}
```
- example usage
```shell
...

'''
source:    asdf----asdf----
throttled: --s--f----s--f--
'''

<a name="observable-debounce"></a>
['observable.debounce(delay)'](#observable-debounce "observable.debounce(delay)") throttles stream/property by given amount
of milliseconds, but so that event is only emitted after the given
"quiet period". Does not affect emitting the initial value of a Property.
The difference of ['throttle'](#observable-throttle) and ['debounce'](#observable-debounce) is the same as it is in the
same methods in jQuery.

Example:
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.debounceImmediate"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>debounceImmediate (delay)](#apidoc.element.baconjs.Observable.prototype.debounceImmediate)
- description and source-code
```javascript
debounceImmediate = function (delay) {
  return this.delayChanges(new Bacon.Desc(this, "debounceImmediate", [delay]), function (changes) {
    return changes.flatMapFirst(function (value) {
      return Bacon.once(value).concat(Bacon.later(delay).filter(false));
    });
  });
}
```
- example usage
```shell
...

'''
source:             asdf----asdf----
source.debounce(2): -----f-------f--
'''

<a name="observable-debounceimmediate"></a>
['observable.debounceImmediate(delay)'](#observable-debounceimmediate "observable.debounceImmediate(delay)") passes the first event
 in the
stream through, but after that, only passes events after a given number
of milliseconds have passed since previous output.

Example:

'''
source:                      asdf----asdf----
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.decode"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>decode (cases)](#apidoc.element.baconjs.Observable.prototype.decode)
- description and source-code
```javascript
decode = function (cases) {
  return withDesc(new Bacon.Desc(this, "decode", [cases]), this.combine(Bacon.combineTemplate(cases), function (key, values) {
    return values[key];
  }));
}
```
- example usage
```shell
...
      return [undefined, [new Bacon.Next(sum), event]]
    else
      return [sum, [event]]
  })
'''

<a name="observable-decode"></a>
['observable.decode(mapping)'](#observable-decode "observable.decode(mapping)") decodes input using the given mapping. Is a
bit like a switch-case or the decode function in Oracle SQL. For
example, the following would map the value 1 into the string "mike"
and the value 2 into the value of the 'who' property.

'''js
property.decode({1 : "mike", 2 : who})
'''
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.delay"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>delay (delay)](#apidoc.element.baconjs.Observable.prototype.delay)
- description and source-code
```javascript
delay = function (delay) {
  return this.delayChanges(new Bacon.Desc(this, "delay", [delay]), function (changes) {
    return changes.flatMap(function (value) {
      return Bacon.later(delay, value);
    });
  });
}
```
- example usage
```shell
...

*Note:* 'neverEndingStream.last()' creates the stream which doesn't produce any events and never ends.

<a name="observable-skip"></a>
['observable.skip(n)'](#observable-skip "observable.skip(n)") skips the first n elements from the stream

<a name="observable-delay"></a>
['observable.delay(delay)'](#observable-delay "observable.delay(delay)") delays the stream/property by given amount of milliseconds
. Does not delay the initial value of a ['Property'](#property).

'''js
var delayed = source.delay(2)
'''

'''
source:    asdf----asdf----
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.deps"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>deps ()](#apidoc.element.baconjs.Observable.prototype.deps)
- description and source-code
```javascript
deps = function () {
  return this.desc.deps();
}
```
- example usage
```shell
...

<a name="observable-tostring"></a>
['observable.toString'](#observable-tostring "observable.toString") Returns a textual description of the Observable. For instance
,
'Bacon.once(1).map(function() {}))' would return "Bacon.once(1).map(function)".


<a name="observable-deps"></a>
['observable.deps'](#observable-deps "observable.deps") Returns the an array of dependencies that the Observable has. For instance
, for 'a.map(function() {}).deps()', would return '[a]'.
This method returns the "visible" dependencies only, skipping internal details.  This method is thus suitable for visualization
tools.
Internally, many combinator functions depend on other combinators to create intermediate Observables that the result will actually
 depend on.
The ['deps'](#observable-deps) method will skip these internal dependencies.

<a name="observable-internaldeps"></a>
['observable.internalDeps'](#observable-internaldeps "observable.internalDeps") Returns the true dependencies of the observable,
including the intermediate "hidden" Observables.
This method is for Bacon.js internal purposes but could be useful for debugging/analysis tools as well.
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.diff"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>diff (start, f)](#apidoc.element.baconjs.Observable.prototype.diff)
- description and source-code
```javascript
diff = function (start, f) {
  f = toCombinator(f);
  return withDesc(new Bacon.Desc(this, "diff", [start, f]), this.scan([start], function (prevTuple, next) {
    return [next, f(prevTuple[0], next)];
  }).filter(function (tuple) {
    return tuple.length === 2;
  }).map(function (tuple) {
    return tuple[1];
  }));
}
```
- example usage
```shell
...
value, i.e. the value just before the observable ends. Returns a
['Property'](#property).

<a name="observable-reduce"></a>
['observable.reduce(seed, f)'](#observable-reduce "observable.reduce(seed,f)") synonym for ['fold'](#observable-fold).

<a name="observable-diff"></a>
['observable.diff(start, f)'](#observable-diff "observable.diff(start, f)") returns a Property that represents the result of a comparison
between the previous and current value of the Observable. For the initial value of the Observable,
the previous value will be the given start.

Example:

'''js
var distance = function (a,b) { return Math.abs(b - a) }
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.doAction"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>doAction ()](#apidoc.element.baconjs.Observable.prototype.doAction)
- description and source-code
```javascript
doAction = function () {
  var f = makeFunctionArgs(arguments);
  return withDesc(new Bacon.Desc(this, "doAction", [f]), this.withHandler(function (event) {
    if (event.hasValue()) {
      f(event.value());
    }
    return this.push(event);
  }));
}
```
- example usage
```shell
...

'''
source:    asdf----asdf----
throttled: a-s-d-f-a-s-d-f-
'''

<a name="observable-doaction"></a>
['observable.doAction(f)'](#observable-doaction "observable.doAction(f)") returns a stream/property where the function f
is executed for each value, before dispatching to subscribers. This is
useful for debugging, but also for stuff like calling the
'preventDefault()' method for events. In fact, you can
also use a property-extractor string instead of a function, as in
'".preventDefault"'.

<a name="observable-doerror"></a>
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.doEnd"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>doEnd ()](#apidoc.element.baconjs.Observable.prototype.doEnd)
- description and source-code
```javascript
doEnd = function () {
  var f = makeFunctionArgs(arguments);
  return withDesc(new Bacon.Desc(this, "doEnd", [f]), this.withHandler(function (event) {
    if (event.isEnd()) {
      f();
    }
    return this.push(event);
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Observable.prototype.doError"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>doError ()](#apidoc.element.baconjs.Observable.prototype.doError)
- description and source-code
```javascript
doError = function () {
  var f = makeFunctionArgs(arguments);
  return withDesc(new Bacon.Desc(this, "doError", [f]), this.withHandler(function (event) {
    if (event.isError()) {
      f(event.error);
    }
    return this.push(event);
  }));
}
```
- example usage
```shell
...
is executed for each value, before dispatching to subscribers. This is
useful for debugging, but also for stuff like calling the
'preventDefault()' method for events. In fact, you can
also use a property-extractor string instead of a function, as in
'".preventDefault"'.

<a name="observable-doerror"></a>
['observable.doError(f)'](#observable-doerror "observable.doError(f)") returns a stream/property where the function f
is executed for each error, before dispatching to subscribers.
That is, same as ['doAction'](#observable-doaction) but for errors.

<a name="observable-not"></a>
['observable.not()'](#observable-not "observable.not(@ : Obserable[A]) : Observable[Bool]") returns a stream/property that inverts
 boolean values

<a name="observable-flatmap"></a>
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.doLog"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>doLog ()](#apidoc.element.baconjs.Observable.prototype.doLog)
- description and source-code
```javascript
doLog = function () {
  for (var _len15 = arguments.length, args = Array(_len15), _key15 = 0; _key15 < _len15; _key15++) {
    args[_key15] = arguments[_key15];
  }

  return withDesc(new Bacon.Desc(this, "doLog", args), this.withHandler(function (event) {
    if (typeof console !== "undefined" && console !== null && typeof console.log === "function") {
      console.log.apply(console, args.concat([event.log()]));
    }
    return this.push(event);
  }));
}
```
- example usage
```shell
...
or just

'''js
myStream.log()
'''

<a name="observable-dolog"></a>
['observable.doLog()'](#observable-dolog "observable.doLog()") logs each value of the Observable to the console. doLog() behaves
 like ['log'](#observable-log)
but does not subscribe to the event stream. You can think of doLog() as a
logger function that – unlike log() – is safe to use in production. doLog() is
safe, because it does not cause the same surprising side-effects as log()
does.

<a name="observable-combine"></a>
['observable.combine(property2, f)'](#observable-combine "observable.combine(property2, f)") combines the latest values of the two
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.endOnError"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>endOnError (f)](#apidoc.element.baconjs.Observable.prototype.endOnError)
- description and source-code
```javascript
endOnError = function (f) {
  if (!(typeof f !== "undefined" && f !== null)) {
    f = true;
  }

  for (var _len16 = arguments.length, args = Array(_len16 > 1 ? _len16 - 1 : 0), _key16 = 1; _key16 < _len16; _key16++) {
    args[_key16 - 1] = arguments[_key16];
  }

  return convertArgsToFunction(this, f, args, function (f) {
    return withDesc(new Bacon.Desc(this, "endOnError", []), this.withHandler(function (event) {
      if (event.isError() && f(event.error)) {
        this.push(event);
        return this.push(endEvent());
      } else {
        return this.push(event);
      }
    }));
  });
}
```
- example usage
```shell
...
currently awaiting an AJAX response:

'''js
var showAjaxIndicator = ajaxRequest.awaiting(ajaxResponse)
'''

<a name="observable-endonerror"></a>
['observable.endOnError()'](#observable-endonerror "observable.endOnError()") ends the 'Observable' on first ['Error'](#bacon-error
) event. The
error is included in the output of the returned 'Observable'.

<a name="observable-endonerror-f"></a>
['observable.endOnError(f)'](#observable-endonerror-f "observable.endOnError(f)") ends the 'Observable' on first ['Error'](#bacon
-error) event for which
the given predicate function returns true. The error is included in the
output of the returned 'Observable'. The [Function Construction rules](#function-construction-rules) apply, so
you can do for example '.endOnError(".serious")'.
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.errors"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>errors ()](#apidoc.element.baconjs.Observable.prototype.errors)
- description and source-code
```javascript
errors = function () {
  return withDesc(new Bacon.Desc(this, "errors", []), this.filter(function () {
    return false;
  }));
}
```
- example usage
```shell
...
['observable.mapError(f)'](#observable-maperror "observable.mapError(@ : Observable[A], f : E -> A) : Observable[A]") maps errors
 using given function. More
specifically, feeds the "error" field of the error event to the function
and produces a ['Next'](#bacon-next) event based on the return value.
The [Function Construction rules](#function-construction-rules) below apply here.
You can omit the argument to produce a ['Next'](#bacon-next) event with 'undefined' value.

<a name="observable-errors"></a>
['observable.errors()'](#observable-errors "observable.errors(@ : Observable[A]) : Observable[A]") returns a stream containing ['
Error'](#bacon-error) events only.
Same as filtering with a function that always returns false.

<a name="observable-skiperrors"></a>
['observable.skipErrors()'](#observable-skiperrors "observable.skipErrors(@ : Observable[A]) : Observable[A]") skips all errors.

<a name="observable-mapend"></a>
['observable.mapEnd(f)'](#observable-mapend "observable.mapEnd(@ : Observable[A], f : -> Observable[A]) : Observable[A]") Adds an
 extra ['Next'](#bacon-next) event just before End. The value is created
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.filter"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>filter (f)](#apidoc.element.baconjs.Observable.prototype.filter)
- description and source-code
```javascript
filter = function (f) {
  assertObservableIsProperty(f);

  for (var _len10 = arguments.length, args = Array(_len10 > 1 ? _len10 - 1 : 0), _key10 = 1; _key10 < _len10; _key10++) {
    args[_key10 - 1] = arguments[_key10];
  }

  return convertArgsToFunction(this, f, args, function (f) {
    return withDesc(new Bacon.Desc(this, "filter", [f]), this.withHandler(function (event) {
      if (event.filter(f)) {
        return this.push(event);
      } else {
        return Bacon.more;
      }
    }));
  });
}
```
- example usage
```shell
...
<a name="observable-mapend"></a>
['observable.mapEnd(f)'](#observable-mapend "observable.mapEnd(@ : Observable[A], f : -> Observable[A]) : Observable[A]") Adds an
 extra ['Next'](#bacon-next) event just before End. The value is created
by calling the given function when the source stream ends. Instead of a
function, a static value can be used. You can omit the argument to
produce a Next event with 'undefined' value.

<a name="observable-filter"></a>
['observable.filter(f)'](#observable-filter "observable.filter(@ : Observable[A], f : A -> Bool) : Observable[A]") filters values
 using given predicate function.
Instead of a function, you can use a constant value ('true' to include all, 'false' to exclude all) or a
property extractor string (like ".isValuable") instead. Just like with
['map'](#observable-map), indeed.

<a name="observable-filter-property"></a>
['observable.filter(property)'](#observable-filter-property "observable.filter(property)") filters values based on the value of
a
property. Event will be included in output [if and only if](http://en.wikipedia.org/wiki/If_and_only_if) the property holds 'true
'
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.first"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>first ()](#apidoc.element.baconjs.Observable.prototype.first)
- description and source-code
```javascript
first = function () {
  return withDesc(new Bacon.Desc(this, "first", []), this.take(1));
}
```
- example usage
```shell
...
['observable.takeWhile(f)'](#observable-takewhile "observable.takeWhile(@ : Observable[A], f : A -> Bool) : Observable[A]") takes
 while given predicate function holds true, and then ends.
[Function Construction rules](#function-construction-rules) apply.

<a name="observable-takewhile-property"></a>
['observable.takeWhile(property)'](#observable-takewhile-property "observable.takeWhile(property)") takes values while the value
 of a property holds true, and then ends.

<a name="observable-first"></a>
['observable.first()'](#observable-first "observable.first(@ : Observable[A]) : Observable[A]") takes the first element from the
 stream. Essentially 'observable.take(1)'.

<a name="observable-last"></a>
['observable.last()'](#observable-last "observable.last(@ : Observable[A]) : Observable[A]") takes the last element from the stream
. None, if stream is empty.

*Note:* 'neverEndingStream.last()' creates the stream which doesn't produce any events and never ends.

<a name="observable-skip"></a>
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.firstToPromise"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>firstToPromise (PromiseCtr)](#apidoc.element.baconjs.Observable.prototype.firstToPromise)
- description and source-code
```javascript
firstToPromise = function (PromiseCtr) {
  var _this12 = this;

  if (typeof PromiseCtr !== "function") {
    if (typeof Promise === "function") {
      PromiseCtr = Promise;
    } else {
      throw new Exception("There isn't default Promise, use shim or parameter");
    }
  }

  return new PromiseCtr(function (resolve, reject) {
    return _this12.subscribe(function (event) {
      if (event.hasValue()) {
        resolve(event.value());
      }
      if (event.isError()) {
        reject(event.error);
      }

      return Bacon.noMore;
    });
  });
}
```
- example usage
```shell
...
<a name="observable-topromise"></a>
['observable.toPromise([PromiseCtr])'](#observable-topromise "observable.toPromise(@ : Observable[A] [, PromiseCtr]) : Promise[A
]") returns a Promise which will be resolved with the last event coming from an Observable.
The global ES6 promise implementation will be used unless a promise constructor is given.
Use a shim if you need to support legacy browsers or platforms.
[caniuse promises](http://caniuse.com/#feat=promises).

<a name="observable-firsttopromise"></a>
['observable.firstToPromise([PromiseCtr])'](#observable-firsttopromise "observable.firstToPromise(@ : Observable[A] [, PromiseCtr
]) : Promise[A]") returns a Promise which will be resolved with the first event coming from an Observable.
Like ['toPromise'](#observable-topromise), the global ES6 promise implementation will be used unless a promise
constructor is given.

<a name="observable-toesobservable"></a>
['observable.toESObservable()'](#observable-toesobservable "observable.toESObservable() : ESObservable[A]") Aliased as 'observable
[Symbol.observable]()'. Returns an
[ES Observable](https://github.com/zenparsing/es-observable) containing the
events from Bacon observable. This allows Bacon observables to be used with
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.flatMap"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>flatMap ()](#apidoc.element.baconjs.Observable.prototype.flatMap)
- description and source-code
```javascript
flatMap = function () {
  return flatMap_(this, makeSpawner(arguments));
}
```
- example usage
```shell
...
is executed for each error, before dispatching to subscribers.
That is, same as ['doAction'](#observable-doaction) but for errors.

<a name="observable-not"></a>
['observable.not()'](#observable-not "observable.not(@ : Obserable[A]) : Observable[Bool]") returns a stream/property that inverts
 boolean values

<a name="observable-flatmap"></a>
['observable.flatMap(f)'](#observable-flatmap "observable.flatMap(@ : Observable[A], f : A -> Observable[B] | Event[B] | B) : EventStream
[B]") for each element in the source stream, spawn a new
stream using the function 'f'. Collect events from each of the spawned
streams into the result ['EventStream'](#eventstream). Note that instead of a function, you can provide a
stream/property too. Also, the return value of function 'f' can be either an
'Observable' (stream/property) or a constant value. The result of
['flatMap'](#observable-flatmap) is always an ['EventStream'](#eventstream).

The [Function Construction rules](#function-construction-rules) below apply here.
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.flatMapConcat"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>flatMapConcat ()](#apidoc.element.baconjs.Observable.prototype.flatMapConcat)
- description and source-code
```javascript
flatMapConcat = function () {
  var desc = new Bacon.Desc(this, "flatMapConcat", Array.prototype.slice.call(arguments, 0));
  return withDesc(desc, this.flatMapWithConcurrencyLimit.apply(this, [1].concat(_slice.call(arguments))));
}
```
- example usage
```shell
...
['observable.flatMapWithConcurrencyLimit(limit, f)'](#observable-flatmapwithconcurrencylimit "observable.flatMapWithConcurrencyLimit
(@ : Observable[A], limit : Number, f : A -> Observable[B] | Event[B] | B) : EventStream[B]") a super method of *flatMap* family
. It limits the number of open spawned streams and buffers incoming events.
['flatMapConcat'](#observable-flatmapconcat) is 'flatMapWithConcurrencyLimit(1)' (only one input active),
and ['flatMap'](#observable-flatmap) is 'flatMapWithConcurrencyLimit ∞' (all inputs are piped to output).

The [Function Construction rules](#function-construction-rules) below apply here.

<a name="observable-flatmapconcat"></a>
['observable.flatMapConcat(f)'](#observable-flatmapconcat "observable.flatMapConcat(@ : Observable[A], f : A -> Observable[B] |
Event[B] | B) : EventStream[B]") a ['flatMapWithConcurrencyLimit'](#observable-flatmapwithconcurrencylimit) with limit of 1.

The [Function Construction rules](#function-construction-rules) below apply here.

<a name="observable-scan"></a>
['observable.scan(seed, f)'](#observable-scan "observable.scan(seed, f) : Property[A]") scans stream/property with given seed value
 and
accumulator function, resulting to a Property. For example, you might
use zero as seed and a "plus" function as the accumulator to create
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.flatMapError"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>flatMapError (fn)](#apidoc.element.baconjs.Observable.prototype.flatMapError)
- description and source-code
```javascript
flatMapError = function (fn) {
  var desc = new Bacon.Desc(this, "flatMapError", [fn]);
  return withDesc(desc, this.mapError(function (err) {
    return new Error(err);
  }).flatMap(function (x) {
    if (x instanceof Error) {
      return fn(x.error);
    } else {
      return Bacon.once(x);
    }
  }));
}
```
- example usage
```shell
...
<a name="observable-flatmapfirst"></a>
['observable.flatMapFirst(f)'](#observable-flatmapfirst "observable.flatMapFirst(f)") like ['flatMap'](#observable-flatmap), but
 only spawns a new
stream if the previously spawned stream has ended.

The [Function Construction rules](#function-construction-rules) below apply here.

<a name="observable-flatmaperror"></a>
['observable.flatMapError(f)'](#observable-flatmaperror "observable.flatMapError(f)") like ['flatMap'](#observable-flatmap), but
 is applied only on ['Error'](#bacon-error) events. Returned values go into the
value stream, unless an error event is returned. As an example, one type of error could result in a retry and another just
passed through, which can be implemented using flatMapError.

<a name="observable-flatmapwithconcurrencylimit"></a>
['observable.flatMapWithConcurrencyLimit(limit, f)'](#observable-flatmapwithconcurrencylimit "observable.flatMapWithConcurrencyLimit
(@ : Observable[A], limit : Number, f : A -> Observable[B] | Event[B] | B) : EventStream[B]") a super method of *flatMap* family
. It limits the number of open spawned streams and buffers incoming events.
['flatMapConcat'](#observable-flatmapconcat) is 'flatMapWithConcurrencyLimit(1)' (only one input active),
and ['flatMap'](#observable-flatmap) is 'flatMapWithConcurrencyLimit ∞' (all inputs are piped to output).
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.flatMapFirst"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>flatMapFirst ()](#apidoc.element.baconjs.Observable.prototype.flatMapFirst)
- description and source-code
```javascript
flatMapFirst = function () {
  return flatMap_(this, makeSpawner(arguments), true);
}
```
- example usage
```shell
...
all spawned streams, only includes them from the latest spawned stream.
You can think this as switching from stream to stream.
Note that instead of a function, you can provide a stream/property too.

The [Function Construction rules](#function-construction-rules) below apply here.

<a name="observable-flatmapfirst"></a>
['observable.flatMapFirst(f)'](#observable-flatmapfirst "observable.flatMapFirst(f)") like ['flatMap'](#observable-flatmap), but
 only spawns a new
stream if the previously spawned stream has ended.

The [Function Construction rules](#function-construction-rules) below apply here.

<a name="observable-flatmaperror"></a>
['observable.flatMapError(f)'](#observable-flatmaperror "observable.flatMapError(f)") like ['flatMap'](#observable-flatmap), but
 is applied only on ['Error'](#bacon-error) events. Returned values go into the
value stream, unless an error event is returned. As an example, one type of error could result in a retry and another just
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.flatMapLatest"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>flatMapLatest ()](#apidoc.element.baconjs.Observable.prototype.flatMapLatest)
- description and source-code
```javascript
flatMapLatest = function () {
  var f = makeSpawner(arguments);
  var stream = this.toEventStream();
  return withDesc(new Bacon.Desc(this, "flatMapLatest", [f]), stream.flatMap(function (value) {
    return makeObservable(f(value)).takeUntil(stream);
  }));
}
```
- example usage
```shell
...
'''js
stream.flatMap(function(text) {
    return (text != "") ? parseInt(text) : Bacon.never()
})
'''

<a name="observable-flatmaplatest"></a>
['observable.flatMapLatest(f)'](#observable-flatmaplatest "observable.flatMapLatest(f)") like ['flatMap'](#observable-flatmap),
but instead of including events from
all spawned streams, only includes them from the latest spawned stream.
You can think this as switching from stream to stream.
Note that instead of a function, you can provide a stream/property too.

The [Function Construction rules](#function-construction-rules) below apply here.

<a name="observable-flatmapfirst"></a>
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.flatMapWithConcurrencyLimit"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>flatMapWithConcurrencyLimit (limit)](#apidoc.element.baconjs.Observable.prototype.flatMapWithConcurrencyLimit)
- description and source-code
```javascript
flatMapWithConcurrencyLimit = function (limit) {
  for (var _len11 = arguments.length, args = Array(_len11 > 1 ? _len11 - 1 : 0), _key11 = 1; _key11 < _len11; _key11++) {
    args[_key11 - 1] = arguments[_key11];
  }

  var desc = new Bacon.Desc(this, "flatMapWithConcurrencyLimit", [limit].concat(args));
  return withDesc(desc, flatMap_(this, makeSpawner(args), false, limit));
}
```
- example usage
```shell
...

<a name="observable-flatmaperror"></a>
['observable.flatMapError(f)'](#observable-flatmaperror "observable.flatMapError(f)") like ['flatMap'](#observable-flatmap), but
 is applied only on ['Error'](#bacon-error) events. Returned values go into the
value stream, unless an error event is returned. As an example, one type of error could result in a retry and another just
passed through, which can be implemented using flatMapError.

<a name="observable-flatmapwithconcurrencylimit"></a>
['observable.flatMapWithConcurrencyLimit(limit, f)'](#observable-flatmapwithconcurrencylimit "observable.flatMapWithConcurrencyLimit
(@ : Observable[A], limit : Number, f : A -> Observable[B] | Event[B] | B) : EventStream[B]") a super method of *flatMap* family
. It limits the number of open spawned streams and buffers incoming events.
['flatMapConcat'](#observable-flatmapconcat) is 'flatMapWithConcurrencyLimit(1)' (only one input active),
and ['flatMap'](#observable-flatmap) is 'flatMapWithConcurrencyLimit ∞' (all inputs are piped to output).

The [Function Construction rules](#function-construction-rules) below apply here.

<a name="observable-flatmapconcat"></a>
['observable.flatMapConcat(f)'](#observable-flatmapconcat "observable.flatMapConcat(@ : Observable[A], f : A -> Observable[B] |
Event[B] | B) : EventStream[B]") a ['flatMapWithConcurrencyLimit'](#observable-flatmapwithconcurrencylimit) with limit of 1.
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.fold"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>fold (seed, f)](#apidoc.element.baconjs.Observable.prototype.fold)
- description and source-code
```javascript
fold = function (seed, f) {
  return withDesc(new Bacon.Desc(this, "fold", [seed, f]), this.scan(seed, f).sampledBy(this.filter(false).mapEnd().toProperty()));
}
```
- example usage
```shell
...
initial value when scan is applied. If there's no initial value, this works
identically to EventStream.scan: the 'seed' will be the initial value of
'r'. However, if 'r' already has a current/initial value 'x', the
seed won't be output as is. Instead, the initial value of 'r' will be 'f(seed, x)'. This makes sense,
because there can only be 1 initial value for a Property at a time.

<a name="observable-fold"></a>
['observable.fold(seed, f)'](#observable-fold "observable.fold(seed, f) : Property[A]") is like ['scan'](#observable-scan) but only
 emits the final
value, i.e. the value just before the observable ends. Returns a
['Property'](#property).

<a name="observable-reduce"></a>
['observable.reduce(seed, f)'](#observable-reduce "observable.reduce(seed,f)") synonym for ['fold'](#observable-fold).

<a name="observable-diff"></a>
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.forEach"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>forEach ()](#apidoc.element.baconjs.Observable.prototype.forEach)
- description and source-code
```javascript
forEach = function () {
  var f = makeFunctionArgs(arguments);
  return this.subscribe(function (event) {
    if (event.hasValue()) {
      return f(event.value());
    }
  });
}
```
- example usage
```shell
...

var fs = require("fs");
var shell = require('shelljs');

var testModules = fs.readdirSync("spec/specs")
    .map(function(name) { return name.substring(0, name.length - 7)})

testModules.forEach(function(moduleName) {
  var result = shell.exec("./runtests " + moduleName)
  if (result.code != 0)
    process.exit(result.code)
})
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.groupBy"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>groupBy (keyF)](#apidoc.element.baconjs.Observable.prototype.groupBy)
- description and source-code
```javascript
groupBy = function (keyF) {
  var limitF = arguments.length <= 1 || arguments[1] === undefined ? Bacon._.id : arguments[1];

  var streams = {};
  var src = this;
  return src.filter(function (x) {
    return !streams[keyF(x)];
  }).map(function (x) {
    var key = keyF(x);
    var similar = src.filter(function (x) {
      return keyF(x) === key;
    });
    var data = Bacon.once(x).concat(similar);
    var limited = limitF(data, x).withHandler(function (event) {
      this.push(event);
      if (event.isEnd()) {
        return delete streams[key];
      }
    });
    streams[key] = limited;
    return limited;
  });
}
```
- example usage
```shell
...
console.log(obs.toString())
--> Bacon.once(1).map(function)
obs.withDescription(src, "times", -1)
console.log(obs.toString())
--> Bacon.once(1).times(-1)

<a name="observable-groupby"></a>
['observable.groupBy(keyF [, limitF])'](#observable-groupby "observable.groupBy(@ : Observable[A], keyF[, limitF]) : Observable[
Observable[A]]") Groups stream events to new streams by 'keyF'. Optional 'limitF' can be provided to limit grouped
stream life. Stream transformed by 'limitF' is passed on if provided. 'limitF' gets grouped stream
and the original event causing the stream to start as parameters.

Calculator for grouped consecutive values until group is cancelled:

var events = [
  {id: 1, type: "add", val: 3 },
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.inspect"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>inspect ()](#apidoc.element.baconjs.Observable.prototype.inspect)
- description and source-code
```javascript
inspect = function () {
  if (this._name) {
    return this._name;
  } else {
    return this.desc.toString();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Observable.prototype.internalDeps"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>internalDeps ()](#apidoc.element.baconjs.Observable.prototype.internalDeps)
- description and source-code
```javascript
internalDeps = function () {
  return this.initialDesc.deps();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Observable.prototype.last"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>last ()](#apidoc.element.baconjs.Observable.prototype.last)
- description and source-code
```javascript
last = function () {
  var lastEvent;

  return withDesc(new Bacon.Desc(this, "last", []), this.withHandler(function (event) {
    if (event.isEnd()) {
      if (lastEvent) {
        this.push(lastEvent);
      }
      this.push(endEvent());
      return Bacon.noMore;
    } else {
      lastEvent = event;
    }
  }));
}
```
- example usage
```shell
...
<a name="observable-takewhile-property"></a>
['observable.takeWhile(property)'](#observable-takewhile-property "observable.takeWhile(property)") takes values while the value
 of a property holds true, and then ends.

<a name="observable-first"></a>
['observable.first()'](#observable-first "observable.first(@ : Observable[A]) : Observable[A]") takes the first element from the
 stream. Essentially 'observable.take(1)'.

<a name="observable-last"></a>
['observable.last()'](#observable-last "observable.last(@ : Observable[A]) : Observable[A]") takes the last element from the stream
. None, if stream is empty.

*Note:* 'neverEndingStream.last()' creates the stream which doesn't produce any events and never ends.

<a name="observable-skip"></a>
['observable.skip(n)'](#observable-skip "observable.skip(n)") skips the first n elements from the stream

<a name="observable-delay"></a>
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.log"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>log ()](#apidoc.element.baconjs.Observable.prototype.log)
- description and source-code
```javascript
log = function () {
  for (var _len18 = arguments.length, args = Array(_len18), _key18 = 0; _key18 < _len18; _key18++) {
    args[_key18] = arguments[_key18];
  }

  this.subscribe(function (event) {
    if (typeof console !== "undefined" && typeof console.log === "function") {
      console.log.apply(console, args.concat([event.log()]));
    }
  });
  return this;
}
```
- example usage
```shell
...
passed to the function. These arguments can be simple variables, Bacon
EventStreams or Properties. For example the following will output "Bacon rules":

'''js
bacon = Bacon.constant('bacon')
Bacon.fromCallback(function(a, b, callback) {
  callback(a + ' ' + b);
}, bacon, 'rules').log();
'''

<a name="bacon-fromcallback-object"></a>
['Bacon.fromCallback(object, methodName [, args...])'](#bacon-fromcallback-object "Bacon.fromCallback(object, methodName [, args
...]) : EventStream[A]") a variant of fromCallback which calls the named method of a given object.

<a name="bacon-fromnodecallback"></a>
['Bacon.fromNodeCallback(f [, args...])'](#bacon-fromnodecallback "Bacon.fromNodeCallback(f : (E -> A -> void) -> void [, args...]) :
EventStream[A]") behaves the same way as ['Bacon.fromCallback'](#bacon-fromcallback),
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.map"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>map (p)](#apidoc.element.baconjs.Observable.prototype.map)
- description and source-code
```javascript
map = function (p) {
  if (p && p._isProperty) {
    return p.sampledBy(this, former);
  } else {
    for (var _len17 = arguments.length, args = Array(_len17 > 1 ? _len17 - 1 : 0), _key17 = 1; _key17 < _len17; _key17++) {
      args[_key17 - 1] = arguments[_key17];
    }

    return convertArgsToFunction(this, p, args, function (f) {
      return withDesc(new Bacon.Desc(this, "map", [f]), this.withHandler(function (event) {
        return this.push(event.fmap(f));
      }));
    });
  }
}
```
- example usage
```shell
...

But you can do neater stuff too. The Bacon of bacon.js is in that you can transform,
filter and combine these streams in a multitude of ways (see API below). The methods ['map'](#observable-map),
['filter'](#observable-filter), for example, are similar to same functions in functional list programming
(like [Underscore](http://underscorejs.org/)). So, if you say

'''js
var plus = $("#plus").asEventStream("click").map(1)
var minus = $("#minus").asEventStream("click").map(-1)
var both = plus.merge(minus)
'''

.. you'll have a stream that will output the number 1 when the "plus" button is clicked
and another stream outputting -1 when the "minus" button is clicked. The 'both' stream will
be a merged stream containing events from both the plus and minus streams. This allows
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.mapEnd"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>mapEnd ()](#apidoc.element.baconjs.Observable.prototype.mapEnd)
- description and source-code
```javascript
mapEnd = function () {
  var f = makeFunctionArgs(arguments);
  return withDesc(new Bacon.Desc(this, "mapEnd", [f]), this.withHandler(function (event) {
    if (event.isEnd()) {
      this.push(nextEvent(f(event)));
      this.push(endEvent());
      return Bacon.noMore;
    } else {
      return this.push(event);
    }
  }));
}
```
- example usage
```shell
...
['observable.errors()'](#observable-errors "observable.errors(@ : Observable[A]) : Observable[A]") returns a stream containing ['
Error'](#bacon-error) events only.
Same as filtering with a function that always returns false.

<a name="observable-skiperrors"></a>
['observable.skipErrors()'](#observable-skiperrors "observable.skipErrors(@ : Observable[A]) : Observable[A]") skips all errors.

<a name="observable-mapend"></a>
['observable.mapEnd(f)'](#observable-mapend "observable.mapEnd(@ : Observable[A], f : -> Observable[A]) : Observable[A]") Adds an
 extra ['Next'](#bacon-next) event just before End. The value is created
by calling the given function when the source stream ends. Instead of a
function, a static value can be used. You can omit the argument to
produce a Next event with 'undefined' value.

<a name="observable-filter"></a>
['observable.filter(f)'](#observable-filter "observable.filter(@ : Observable[A], f : A -> Bool) : Observable[A]") filters values
 using given predicate function.
Instead of a function, you can use a constant value ('true' to include all, 'false' to exclude all) or a
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.mapError"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>mapError ()](#apidoc.element.baconjs.Observable.prototype.mapError)
- description and source-code
```javascript
mapError = function () {
  var f = makeFunctionArgs(arguments);
  return withDesc(new Bacon.Desc(this, "mapError", [f]), this.withHandler(function (event) {
    if (event.isError()) {
      return this.push(nextEvent(f(event.error)));
    } else {
      return this.push(event);
    }
  }));
}
```
- example usage
```shell
...
The ['map'](#observable-map) method, among many others, uses [lazy evaluation](#lazy-evaluation).

<a name="stream-map"></a>
['stream.map(property)'](#stream-map "stream.map(property)") maps the stream events to the current value of
the given property. This is equivalent to ['property.sampledBy(stream)'](#property-sampledby).

<a name="observable-maperror"></a>
['observable.mapError(f)'](#observable-maperror "observable.mapError(@ : Observable[A], f : E -> A) : Observable[A]") maps errors
 using given function. More
specifically, feeds the "error" field of the error event to the function
and produces a ['Next'](#bacon-next) event based on the return value.
The [Function Construction rules](#function-construction-rules) below apply here.
You can omit the argument to produce a ['Next'](#bacon-next) event with 'undefined' value.

<a name="observable-errors"></a>
['observable.errors()'](#observable-errors "observable.errors(@ : Observable[A]) : Observable[A]") returns a stream containing ['
Error'](#bacon-error) events only.
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.name"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>name (name)](#apidoc.element.baconjs.Observable.prototype.name)
- description and source-code
```javascript
name = function (name) {
  this._name = name;
  return this;
}
```
- example usage
```shell
...
'''

Note that it's important to return the value from 'this.push' so that
the connection to the underlying stream will be closed when no more
events are needed.

<a name="observable-name"></a>
['observable.name(newName)'](#observable-name "observable.name(@ : Observable[A], newName : String) : Observable[A]") sets the name
 of the observable. Overrides the default
implementation of ['toString'](#observable-tostring) and 'inspect'.
Returns itself.

<a name="observable-withdescription"></a>
['observable.withDescription(param...)'](#observable-withdescription "observable.withDescription(@ : Observable[A], param...) :
Observable[A]") Sets the structured description of the observable. The ['toString'](#observable-tostring) and 'inspect' methods
use this data recursively to create a string representation for the observable. This method
is probably useful for Bacon core / library / plugin development only.
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.not"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>not ()](#apidoc.element.baconjs.Observable.prototype.not)
- description and source-code
```javascript
not = function () {
  return withDesc(new Bacon.Desc(this, "not", []), this.map(function (x) {
    return !x;
  }));
}
```
- example usage
```shell
...

<a name="observable-doerror"></a>
['observable.doError(f)'](#observable-doerror "observable.doError(f)") returns a stream/property where the function f
is executed for each error, before dispatching to subscribers.
That is, same as ['doAction'](#observable-doaction) but for errors.

<a name="observable-not"></a>
['observable.not()'](#observable-not "observable.not(@ : Obserable[A]) : Observable[Bool]") returns a stream/property that inverts
 boolean values

<a name="observable-flatmap"></a>
['observable.flatMap(f)'](#observable-flatmap "observable.flatMap(@ : Observable[A], f : A -> Observable[B] | Event[B] | B) : EventStream
[B]") for each element in the source stream, spawn a new
stream using the function 'f'. Collect events from each of the spawned
streams into the result ['EventStream'](#eventstream). Note that instead of a function, you can provide a
stream/property too. Also, the return value of function 'f' can be either an
'Observable' (stream/property) or a constant value. The result of
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.onEnd"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>onEnd ()](#apidoc.element.baconjs.Observable.prototype.onEnd)
- description and source-code
```javascript
onEnd = function () {
  var f = makeFunctionArgs(arguments);
  return this.subscribe(function (event) {
    if (event.isEnd()) {
      return f();
    }
  });
}
```
- example usage
```shell
...
array) as function arguments to 'f'.

<a name="observable-onerror"></a>
['observable.onError(f)'](#observable-onerror "observable.onError(@ : Observable[A], f : Error -> void) : Unsubscriber") subscribes
 a callback to error events. The function will be called for each error in the stream.
Just like 'subscribe', this method returns a function for unsubscribing.

<a name="observable-onend"></a>
['observable.onEnd(f)'](#observable-onend "observable.onEnd(f : -> void) : Unsubscriber") subscribes a callback to stream end. The
 function will be called when the stream ends.
Just like 'subscribe', this method returns a function for unsubscribing.

<a name="observable-topromise"></a>
['observable.toPromise([PromiseCtr])'](#observable-topromise "observable.toPromise(@ : Observable[A] [, PromiseCtr]) : Promise[A
]") returns a Promise which will be resolved with the last event coming from an Observable.
The global ES6 promise implementation will be used unless a promise constructor is given.
Use a shim if you need to support legacy browsers or platforms.
[caniuse promises](http://caniuse.com/#feat=promises).
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.onError"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>onError ()](#apidoc.element.baconjs.Observable.prototype.onError)
- description and source-code
```javascript
onError = function () {
  var f = makeFunctionArgs(arguments);
  return this.subscribe(function (event) {
    if (event.isError()) {
      return f(event.error);
    }
  });
}
```
- example usage
```shell
...
except that it expects the callback to be called in the Node.js convention:
'callback(error, data)', where error is null if everything is fine. For example:

'''js
var Bacon = require('baconjs').Bacon,
    fs = require('fs');
var read = Bacon.fromNodeCallback(fs.readFile, 'input.txt');
read.onError(function(error) { console.log("Reading failed: " + error); });
read.onValue(function(value) { console.log("Read contents: " + value); });
'''

<a name="bacon-fromesobservable"></a>
['Bacon.fromESObservable(observable)'](#bacon-fromesobservable "Bacon.fromESObservable(observable : ESObservable[A]) : EventStream
[A]") creates an EventStream from an
[ES Observable](https://github.com/tc39/proposal-observable). Input can be any
ES Observable implementation including RxJS and Kefir.
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.onValue"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>onValue ()](#apidoc.element.baconjs.Observable.prototype.onValue)
- description and source-code
```javascript
onValue = function () {
  var f = makeFunctionArgs(arguments);
  return this.subscribe(function (event) {
    if (event.hasValue()) {
      return f(event.value());
    }
  });
}
```
- example usage
```shell
...
'''

Each EventStream represents a stream of events. It is an Observable object, meaning
that you can listen to events in the stream using, for instance, the ['onValue'](#stream-onvalue) method
with a callback. Like this:

'''js
clicks.onValue(function() { alert("you clicked the h1 element") })
'''

But you can do neater stuff too. The Bacon of bacon.js is in that you can transform,
filter and combine these streams in a multitude of ways (see API below). The methods ['map'](#observable-map),
['filter'](#observable-filter), for example, are similar to same functions in functional list programming
(like [Underscore](http://underscorejs.org/)). So, if you say
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.onValues"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>onValues (f)](#apidoc.element.baconjs.Observable.prototype.onValues)
- description and source-code
```javascript
onValues = function (f) {
  return this.onValue(function (args) {
    return f.apply(undefined, args);
  });
}
```
- example usage
```shell
...
received, instead of ['Event'](#event) objects.
The [Function Construction rules](#function-construction-rules) below apply here.
Just like 'subscribe', this method returns a function for unsubscribing.
'stream.onValue' and 'property.onValue' behave similarly, except that the latter also
pushes the initial value of the property, in case there is one.

<a name="observable-onvalues"></a>
['observable.onValues(f)'](#observable-onvalues "observable.onValues(f)") like ['onValue'](#stream-onvalue), but splits the value
 (assuming its an
array) as function arguments to 'f'.

<a name="observable-onerror"></a>
['observable.onError(f)'](#observable-onerror "observable.onError(@ : Observable[A], f : Error -> void) : Unsubscriber") subscribes
 a callback to error events. The function will be called for each error in the stream.
Just like 'subscribe', this method returns a function for unsubscribing.

<a name="observable-onend"></a>
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.reduce"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>reduce (seed, f)](#apidoc.element.baconjs.Observable.prototype.reduce)
- description and source-code
```javascript
reduce = function (seed, f) {
  return withDesc(new Bacon.Desc(this, "fold", [seed, f]), this.scan(seed, f).sampledBy(this.filter(false).mapEnd().toProperty()));
}
```
- example usage
```shell
...

<a name="observable-fold"></a>
['observable.fold(seed, f)'](#observable-fold "observable.fold(seed, f) : Property[A]") is like ['scan'](#observable-scan) but only
 emits the final
value, i.e. the value just before the observable ends. Returns a
['Property'](#property).

<a name="observable-reduce"></a>
['observable.reduce(seed, f)'](#observable-reduce "observable.reduce(seed,f)") synonym for ['fold'](#observable-fold).

<a name="observable-diff"></a>
['observable.diff(start, f)'](#observable-diff "observable.diff(start, f)") returns a Property that represents the result of a comparison
between the previous and current value of the Observable. For the initial value of the Observable,
the previous value will be the given start.

Example:
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.scan"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>scan (seed, f)](#apidoc.element.baconjs.Observable.prototype.scan)
- description and source-code
```javascript
scan = function (seed, f) {
  var _this10 = this;

  var resultProperty;
  f = toCombinator(f);
  var acc = toOption(seed);
  var initHandled = false;
  var subscribe = function (sink) {
    var initSent = false;
    var unsub = nop;
    var reply = Bacon.more;
    var sendInit = function () {
      if (!initSent) {
        return acc.forEach(function (value) {
          initSent = initHandled = true;
          reply = sink(new Initial(function () {
            return value;
          }));
          if (reply === Bacon.noMore) {
            unsub();
            unsub = nop;
            return unsub;
          }
        });
      }
    };
    unsub = _this10.dispatcher.subscribe(function (event) {
      if (event.hasValue()) {
        if (initHandled && event.isInitial()) {
          return Bacon.more;
        } else {
            if (!event.isInitial()) {
              sendInit();
            }
            initSent = initHandled = true;
            var prev = acc.getOrElse(undefined);
            var next = f(prev, event.value());

            acc = new Some(next);
            return sink(event.apply(function () {
              return next;
            }));
          }
      } else {
        if (event.isEnd()) {
          reply = sendInit();
        }
        if (reply !== Bacon.noMore) {
          return sink(event);
        }
      }
    });
    UpdateBarrier.whenDoneWith(resultProperty, sendInit);
    return unsub;
  };
  resultProperty = new Property(new Bacon.Desc(this, "scan", [seed, f]), subscribe);
  return resultProperty;
}
```
- example usage
```shell
...
EventStream, but has a "current value". So things that change and have a current state are
Properties, while things that consist of discrete events are EventStreams. You could think
mouse clicks as an EventStream and mouse position as a Property. You can create Properties from
an EventStream with ['scan'](#observable-scan) or ['toProperty'](#stream-toproperty) methods. So, let's say

'''js
function add(x, y) { return x + y }
var counter = both.scan(0, add)
counter.onValue(function(sum) { $("#sum").text(sum) })
'''

The 'counter' property will contain the sum of the values in the 'both' stream, so it's practically
a counter that can be increased and decreased using the plus and minus buttons. The ['scan'](#observable-scan) method
was used here to calculate the "current sum" of events in the 'both' stream, by giving a "seed value"
'0' and an "accumulator function" 'add'. The scan method creates a property that starts with the given
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.skip"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>skip (count)](#apidoc.element.baconjs.Observable.prototype.skip)
- description and source-code
```javascript
skip = function (count) {
  return withDesc(new Bacon.Desc(this, "skip", [count]), this.withHandler(function (event) {
    if (!event.hasValue()) {
      return this.push(event);
    } else if (count > 0) {
      count--;
      return Bacon.more;
    } else {
      return this.push(event);
    }
  }));
}
```
- example usage
```shell
...

<a name="observable-last"></a>
['observable.last()'](#observable-last "observable.last(@ : Observable[A]) : Observable[A]") takes the last element from the stream
. None, if stream is empty.

*Note:* 'neverEndingStream.last()' creates the stream which doesn't produce any events and never ends.

<a name="observable-skip"></a>
['observable.skip(n)'](#observable-skip "observable.skip(n)") skips the first n elements from the stream

<a name="observable-delay"></a>
['observable.delay(delay)'](#observable-delay "observable.delay(delay)") delays the stream/property by given amount of milliseconds
. Does not delay the initial value of a ['Property'](#property).

'''js
var delayed = source.delay(2)
'''
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.skipDuplicates"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>skipDuplicates ()](#apidoc.element.baconjs.Observable.prototype.skipDuplicates)
- description and source-code
```javascript
skipDuplicates = function () {
  var isEqual = arguments.length <= 0 || arguments[0] === undefined ? equals : arguments[0];

  var desc = new Bacon.Desc(this, "skipDuplicates", []);
  return withDesc(desc, this.withStateMachine(None, function (prev, event) {
    if (!event.hasValue()) {
      return [prev, [event]];
    } else if (event.isInitial() || isNone(prev) || !isEqual(prev.get(), event.value())) {
      return [new Some(event.value()), [event]];
    } else {
      return [prev, []];
    }
  }));
}
```
- example usage
```shell
...

<a name="observable-filter-property"></a>
['observable.filter(property)'](#observable-filter-property "observable.filter(property)") filters values based on the value of
a
property. Event will be included in output [if and only if](http://en.wikipedia.org/wiki/If_and_only_if) the property holds 'true
'
at the time of the event.

<a name="observable-skipduplicates"></a>
['observable.skipDuplicates(isEqual)'](#observable-skipduplicates "observable.skipDuplicates([isEqual])") drops consecutive equal
 elements. So,
from '[1, 2, 2, 1]' you'd get '[1, 2, 1]'. Uses the '===' operator for equality
checking by default. If the isEqual argument is supplied, checks by calling
isEqual(oldValue, newValue). For instance, to do a deep comparison,you can
use the isEqual function from [underscore.js](http://underscorejs.org/)
like 'stream.skipDuplicates(_.isEqual)'.

<a name="observable-take"></a>
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.skipErrors"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>skipErrors ()](#apidoc.element.baconjs.Observable.prototype.skipErrors)
- description and source-code
```javascript
skipErrors = function () {
  return withDesc(new Bacon.Desc(this, "skipErrors", []), this.withHandler(function (event) {
    if (event.isError()) {
      return Bacon.more;
    } else {
      return this.push(event);
    }
  }));
}
```
- example usage
```shell
...
You can omit the argument to produce a ['Next'](#bacon-next) event with 'undefined' value.

<a name="observable-errors"></a>
['observable.errors()'](#observable-errors "observable.errors(@ : Observable[A]) : Observable[A]") returns a stream containing ['
Error'](#bacon-error) events only.
Same as filtering with a function that always returns false.

<a name="observable-skiperrors"></a>
['observable.skipErrors()'](#observable-skiperrors "observable.skipErrors(@ : Observable[A]) : Observable[A]") skips all errors.

<a name="observable-mapend"></a>
['observable.mapEnd(f)'](#observable-mapend "observable.mapEnd(@ : Observable[A], f : -> Observable[A]) : Observable[A]") Adds an
 extra ['Next'](#bacon-next) event just before End. The value is created
by calling the given function when the source stream ends. Instead of a
function, a static value can be used. You can omit the argument to
produce a Next event with 'undefined' value.
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.slidingWindow"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>slidingWindow (n)](#apidoc.element.baconjs.Observable.prototype.slidingWindow)
- description and source-code
```javascript
slidingWindow = function (n) {
  var minValues = arguments.length <= 1 || arguments[1] === undefined ? 0 : arguments[1];

  return withDesc(new Bacon.Desc(this, "slidingWindow", [n, minValues]), this.scan([], function (window, value) {
    return window.concat([value]).slice(-n);
  }).filter(function (values) {
    return values.length >= minValues;
  }));
}
```
- example usage
```shell
...

# produces values 4, 6
'''

See also ['zipWith'](#bacon-zipwith) and ['zipAsArray'](#bacon-zipasarray) for zipping more than 2 sources.

<a name="observable-slidingwindow"></a>
['observable.slidingWindow(max [, min])'](#observable-slidingwindow "observable.slidingWindow(max[, min])") returns a Property that
 represents a
"sliding window" into the history of the values of the Observable. The
result Property will have a value that is an array containing the last 'n'
values of the original observable, where 'n' is at most the value of the
'max' argument, and at least the value of the 'min' argument. If the
'min' argument is omitted, there's no lower limit of values.

For example, if you have a stream 's' with value a sequence 1 - 2 - 3 - 4 - 5, the
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.subscribe"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>subscribe (sink)](#apidoc.element.baconjs.Observable.prototype.subscribe)
- description and source-code
```javascript
subscribe = function (sink) {
  return UpdateBarrier.wrappedSubscribe(this, sink);
}
```
- example usage
```shell
...
---------------------------------------------

Both EventStream and Property share the Observable interface, and hence share a lot of methods.
Methods typically return observables so that methods can be chained; exceptions are noted.
Common methods are listed below.

<a name="observable-subscribe"></a>
['observable.subscribe(f)'](#observable-subscribe "observable.subscribe(f)") subscribes given handler function to event stream.
Function will receive Event objects (see below).
The subscribe() call returns a 'unsubscribe' function that you can call to unsubscribe.
You can also unsubscribe by returning ['Bacon.noMore'](#bacon-nomore) from the handler function as a reply
to an Event.
'stream.subscribe' and 'property.subscribe' behave similarly, except that the latter also
pushes the initial value of the property, in case there is one.

<a name="observable-onvalue"></a>
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.subscribeInternal"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>subscribeInternal (sink)](#apidoc.element.baconjs.Observable.prototype.subscribeInternal)
- description and source-code
```javascript
subscribeInternal = function (sink) {
  return this.dispatcher.subscribe(sink);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Observable.prototype.take"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>take (count)](#apidoc.element.baconjs.Observable.prototype.take)
- description and source-code
```javascript
take = function (count) {
  if (count <= 0) {
    return Bacon.never();
  }
  return withDesc(new Bacon.Desc(this, "take", [count]), this.withHandler(function (event) {
    if (!event.hasValue()) {
      return this.push(event);
    } else {
      count--;
      if (count > 0) {
        return this.push(event);
      } else {
        if (count === 0) {
          this.push(event);
        }
        this.push(endEvent());
        return Bacon.noMore;
      }
    }
  }));
}
```
- example usage
```shell
...
from '[1, 2, 2, 1]' you'd get '[1, 2, 1]'. Uses the '===' operator for equality
checking by default. If the isEqual argument is supplied, checks by calling
isEqual(oldValue, newValue). For instance, to do a deep comparison,you can
use the isEqual function from [underscore.js](http://underscorejs.org/)
like 'stream.skipDuplicates(_.isEqual)'.

<a name="observable-take"></a>
['observable.take(n)'](#observable-take "observable.take(@ : Observable[A], n : Number) : Observable[A]") takes at most n values
 from the stream and then ends the stream. If the stream has
fewer than n values then it is unaffected.
Equal to ['Bacon.never()'](#bacon-never) if 'n <= 0'.

<a name="observable-takeuntil"></a>
['observable.takeUntil(stream)'](#observable-takeuntil "observable.takeUntil(@ : Observable[A], stream : EventStream[B]) : Observable
[A]") takes elements from source until a Next event appears in the other stream.
If other stream ends without value, it is ignored.
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.takeWhile"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>takeWhile (f)](#apidoc.element.baconjs.Observable.prototype.takeWhile)
- description and source-code
```javascript
takeWhile = function (f) {
  assertObservableIsProperty(f);

  for (var _len20 = arguments.length, args = Array(_len20 > 1 ? _len20 - 1 : 0), _key20 = 1; _key20 < _len20; _key20++) {
    args[_key20 - 1] = arguments[_key20];
  }

  return convertArgsToFunction(this, f, args, function (f) {
    return withDesc(new Bacon.Desc(this, "takeWhile", [f]), this.withHandler(function (event) {
      if (event.filter(f)) {
        return this.push(event);
      } else {
        this.push(endEvent());
        return Bacon.noMore;
      }
    }));
  });
}
```
- example usage
```shell
...
Equal to ['Bacon.never()'](#bacon-never) if 'n <= 0'.

<a name="observable-takeuntil"></a>
['observable.takeUntil(stream)'](#observable-takeuntil "observable.takeUntil(@ : Observable[A], stream : EventStream[B]) : Observable
[A]") takes elements from source until a Next event appears in the other stream.
If other stream ends without value, it is ignored.

<a name="observable-takewhile"></a>
['observable.takeWhile(f)'](#observable-takewhile "observable.takeWhile(@ : Observable[A], f : A -> Bool) : Observable[A]") takes
 while given predicate function holds true, and then ends.
[Function Construction rules](#function-construction-rules) apply.

<a name="observable-takewhile-property"></a>
['observable.takeWhile(property)'](#observable-takewhile-property "observable.takeWhile(property)") takes values while the value
 of a property holds true, and then ends.

<a name="observable-first"></a>
['observable.first()'](#observable-first "observable.first(@ : Observable[A]) : Observable[A]") takes the first element from the
 stream. Essentially 'observable.take(1)'.
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.throttle"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>throttle (delay)](#apidoc.element.baconjs.Observable.prototype.throttle)
- description and source-code
```javascript
throttle = function (delay) {
  return this.delayChanges(new Bacon.Desc(this, "throttle", [delay]), function (changes) {
    return changes.bufferWithTime(delay).map(function (values) {
      return values[values.length - 1];
    });
  });
}
```
- example usage
```shell
...

'''
source:    asdf----asdf----
delayed:   --asdf----asdf--
'''

<a name="observable-throttle"></a>
['observable.throttle(delay)'](#observable-throttle "observable.throttle(delay)") throttles stream/property by given amount
of milliseconds. Events are emitted with the minimum interval of
['delay'](#observable-delay). The implementation is based on ['stream.bufferWithTime'](#stream-bufferwithtime).
Does not affect emitting the initial value of a ['Property'](#property).

Example:

'''js
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.toESObservable"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>toESObservable ()](#apidoc.element.baconjs.Observable.prototype.toESObservable)
- description and source-code
```javascript
toESObservable = function () {
  return new ESObservable(this);
}
```
- example usage
```shell
...

<a name="observable-firsttopromise"></a>
['observable.firstToPromise([PromiseCtr])'](#observable-firsttopromise "observable.firstToPromise(@ : Observable[A] [, PromiseCtr
]) : Promise[A]") returns a Promise which will be resolved with the first event coming from an Observable.
Like ['toPromise'](#observable-topromise), the global ES6 promise implementation will be used unless a promise
constructor is given.

<a name="observable-toesobservable"></a>
['observable.toESObservable()'](#observable-toesobservable "observable.toESObservable() : ESObservable[A]") Aliased as 'observable
[Symbol.observable]()'. Returns an
[ES Observable](https://github.com/zenparsing/es-observable) containing the
events from Bacon observable. This allows Bacon observables to be used with
'Observable.from' and provides interoperability with other ES observable
implementations such as RxJS and Kefir.

<a name="observable-map"></a>
['observable.map(f)'](#observable-map "observable.map(@ : Observable[A], f : A -> B) : Observable[B]") maps values using given function
, returning a new
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.toPromise"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>toPromise (PromiseCtr)](#apidoc.element.baconjs.Observable.prototype.toPromise)
- description and source-code
```javascript
toPromise = function (PromiseCtr) {
  return this.last().firstToPromise(PromiseCtr);
}
```
- example usage
```shell
...
Just like 'subscribe', this method returns a function for unsubscribing.

<a name="observable-onend"></a>
['observable.onEnd(f)'](#observable-onend "observable.onEnd(f : -> void) : Unsubscriber") subscribes a callback to stream end. The
 function will be called when the stream ends.
Just like 'subscribe', this method returns a function for unsubscribing.

<a name="observable-topromise"></a>
['observable.toPromise([PromiseCtr])'](#observable-topromise "observable.toPromise(@ : Observable[A] [, PromiseCtr]) : Promise[A
]") returns a Promise which will be resolved with the last event coming from an Observable.
The global ES6 promise implementation will be used unless a promise constructor is given.
Use a shim if you need to support legacy browsers or platforms.
[caniuse promises](http://caniuse.com/#feat=promises).

<a name="observable-firsttopromise"></a>
['observable.firstToPromise([PromiseCtr])'](#observable-firsttopromise "observable.firstToPromise(@ : Observable[A] [, PromiseCtr
]) : Promise[A]") returns a Promise which will be resolved with the first event coming from an Observable.
Like ['toPromise'](#observable-topromise), the global ES6 promise implementation will be used unless a promise
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.toString"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>toString ()](#apidoc.element.baconjs.Observable.prototype.toString)
- description and source-code
```javascript
toString = function () {
  if (this._name) {
    return this._name;
  } else {
    return this.desc.toString();
  }
}
```
- example usage
```shell
...
use this data recursively to create a string representation for the observable. This method
is probably useful for Bacon core / library / plugin development only.

For example:

    var src = Bacon.once(1)
    var obs = src.map(function(x) { return -x })
    console.log(obs.toString())
    --> Bacon.once(1).map(function)
    obs.withDescription(src, "times", -1)
    console.log(obs.toString())
    --> Bacon.once(1).times(-1)

<a name="observable-groupby"></a>
['observable.groupBy(keyF [, limitF])'](#observable-groupby "observable.groupBy(@ : Observable[A], keyF[, limitF]) : Observable[
Observable[A]]") Groups stream events to new streams by 'keyF'. Optional 'limitF' can be provided to limit grouped
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.withDescription"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>withDescription ()](#apidoc.element.baconjs.Observable.prototype.withDescription)
- description and source-code
```javascript
withDescription = function () {
  this.desc = describe.apply(undefined, arguments);
  return this;
}
```
- example usage
```shell
...

<a name="observable-name"></a>
['observable.name(newName)'](#observable-name "observable.name(@ : Observable[A], newName : String) : Observable[A]") sets the name
 of the observable. Overrides the default
implementation of ['toString'](#observable-tostring) and 'inspect'.
Returns itself.

<a name="observable-withdescription"></a>
['observable.withDescription(param...)'](#observable-withdescription "observable.withDescription(@ : Observable[A], param...) :
Observable[A]") Sets the structured description of the observable. The ['toString'](#observable-tostring) and 'inspect' methods
use this data recursively to create a string representation for the observable. This method
is probably useful for Bacon core / library / plugin development only.

For example:

var src = Bacon.once(1)
var obs = src.map(function(x) { return -x })
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.withStateMachine"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>withStateMachine (initState, f)](#apidoc.element.baconjs.Observable.prototype.withStateMachine)
- description and source-code
```javascript
withStateMachine = function (initState, f) {
  var state = initState;
  var desc = new Bacon.Desc(this, "withStateMachine", [initState, f]);
  return withDesc(desc, this.withHandler(function (event) {
    var fromF = f(state, event);
    var newState = fromF[0];
    var outputs = fromF[1];

    state = newState;
    var reply = Bacon.more;
    for (var i = 0, output; i < outputs.length; i++) {
      output = outputs[i];
      reply = this.push(output);
      if (reply === Bacon.noMore) {
        return reply;
      }
    }
    return reply;
  }));
}
```
- example usage
```shell
...
<a name="observable-combine"></a>
['observable.combine(property2, f)'](#observable-combine "observable.combine(property2, f)") combines the latest values of the two
streams or properties using a two-arg function. Similarly to ['scan'](#observable-scan), you can use a
method name instead, so you could do 'a.combine(b, ".concat")' for two
properties with array value. The result is a Property.

<a name="observable-withstatemachine"></a>
['observable.withStateMachine(initState, f)'](#observable-withstatemachine "observable.withStateMachine(initState, f)") lets you
 run a state machine
on an observable. Give it an initial state object and a state
transformation function that processes each incoming event and
returns an array containing the next state and an array of output
events. Here's an example where we calculate the total sum of all
numbers in the stream and output the value on stream end:

'''js
...
```

#### <a name="apidoc.element.baconjs.Observable.prototype.zip"></a>[function <span class="apidocSignatureSpan">baconjs.Observable.prototype.</span>zip (other, f)](#apidoc.element.baconjs.Observable.prototype.zip)
- description and source-code
```javascript
zip = function (other, f) {
  return withDesc(new Bacon.Desc(this, "zip", [other]), Bacon.zipWith([this, other], f || Array));
}
```
- example usage
```shell
...
This would result to following elements in the result stream:

    1 - 0 = 1
    2 - 1 = 1
    3 - 2 = 1

<a name="observable-zip"></a>
['observable.zip(other [, f])'](#observable-zip "observable.zip(other [, f])") return an EventStream with elements
pair-wise lined up with events from this and the other EventStream or Property.
A zipped stream will publish only when it has a value from each
source and will only produce values up to when any single source ends.

The given function 'f' is used to create the result value from value in the two
sources. If no function is given, the values are zipped into an array.
...
```



# <a name="apidoc.module.baconjs.Property"></a>[module baconjs.Property](#apidoc.module.baconjs.Property)

#### <a name="apidoc.element.baconjs.Property.Property"></a>[function <span class="apidocSignatureSpan">baconjs.</span>Property (desc, subscribe, handler)](#apidoc.element.baconjs.Property.Property)
- description and source-code
```javascript
function Property(desc, subscribe, handler) {
  Observable.call(this, desc);
  assertFunction(subscribe);
  this.dispatcher = new PropertyDispatcher(this, subscribe, handler);
  registerObs(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.baconjs.Property.prototype"></a>[module baconjs.Property.prototype](#apidoc.module.baconjs.Property.prototype)

#### <a name="apidoc.element.baconjs.Property.prototype.and"></a>[function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>and (other)](#apidoc.element.baconjs.Property.prototype.and)
- description and source-code
```javascript
and = function (other) {
  return withDesc(new Bacon.Desc(this, "and", [other]), this.combine(other, function (x, y) {
    return x && y;
  }));
}
```
- example usage
```shell
...

<a name="property-changes"></a>
['property.changes()'](#property-changes "property.changes()") returns an ['EventStream'](#eventstream) of property value changes
.
Returns exactly the same events as the property itself, except any Initial
events. Note that ['property.changes()'](#property-changes) does NOT skip duplicate values, use .skipDuplicates() for that.

<a name="property-and"></a>
['property.and(other)'](#property-and "property.and(other)") combines properties with the '&&' operator.

<a name="property-or"></a>
['property.or(other)'](#property-or "property.or(other)") combines properties with the '||' operator.

<a name="property-startwith"></a>
['property.startWith(value)'](#property-startwith "property.startWith(value)") adds an initial "default" value for the
Property. If the Property doesn't have an initial value of it's own, the
...
```

#### <a name="apidoc.element.baconjs.Property.prototype.bufferingThrottle"></a>[function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>bufferingThrottle ()](#apidoc.element.baconjs.Property.prototype.bufferingThrottle)
- description and source-code
```javascript
bufferingThrottle = function () {
  return Bacon.Observable.prototype.bufferingThrottle.apply(this, arguments).toProperty();
}
```
- example usage
```shell
...

'''
source:                      asdf----asdf----
source.debounceImmediate(2): a-d-----a-d-----
'''

<a name="observable-bufferingthrottle"></a>
['observable.bufferingThrottle(minimumInterval)'](#observable-bufferingthrottle "observable.bufferingThrottle(@ : Observable[A],
minimumInterval) : EventStream[A]") throttles the observable using a buffer so that at most one value event in minimumInteval is
 issued.
Unlike ['throttle'](#observable-throttle), it doesn't discard the excessive events but buffers them instead, outputting
them with a rate of at most one value per minimumInterval.

Example:

'''js
var throttled = source.bufferingThrottle(2)
...
```

#### <a name="apidoc.element.baconjs.Property.prototype.changes"></a>[function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>changes ()](#apidoc.element.baconjs.Property.prototype.changes)
- description and source-code
```javascript
changes = function () {
  var _this4 = this;

  return new EventStream(new Bacon.Desc(this, "changes", []), function (sink) {
    return _this4.dispatcher.subscribe(function (event) {
      if (!event.isInitial()) {
        return sink(event);
      }
    });
  });
}
```
- example usage
```shell
...
<a name="property-sampledby-f"></a>
['property.sampledBy(streamOrProperty, f)'](#property-sampledby-f "property.sampledBy(streamOrProperty, f)") samples the property
 on stream
events. The result values will be formed using the given function
'f(propertyValue, samplerValue)'. You can use a method name (such as
".concat") instead of a function too.

<a name="property-changes"></a>
['property.changes()'](#property-changes "property.changes()") returns an ['EventStream'](#eventstream) of property value changes
.
Returns exactly the same events as the property itself, except any Initial
events. Note that ['property.changes()'](#property-changes) does NOT skip duplicate values, use .skipDuplicates() for that.

<a name="property-and"></a>
['property.and(other)'](#property-and "property.and(other)") combines properties with the '&&' operator.

<a name="property-or"></a>
...
```

#### <a name="apidoc.element.baconjs.Property.prototype.delayChanges"></a>[function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>delayChanges (desc, f)](#apidoc.element.baconjs.Property.prototype.delayChanges)
- description and source-code
```javascript
delayChanges = function (desc, f) {
  return withDesc(desc, addPropertyInitValueToStream(this, f(this.changes())));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.Property.prototype.or"></a>[function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>or (other)](#apidoc.element.baconjs.Property.prototype.or)
- description and source-code
```javascript
or = function (other) {
  return withDesc(new Bacon.Desc(this, "or", [other]), this.combine(other, function (x, y) {
    return x || y;
  }));
}
```
- example usage
```shell
...
Returns exactly the same events as the property itself, except any Initial
events. Note that ['property.changes()'](#property-changes) does NOT skip duplicate values, use .skipDuplicates() for that.

<a name="property-and"></a>
['property.and(other)'](#property-and "property.and(other)") combines properties with the '&&' operator.

<a name="property-or"></a>
['property.or(other)'](#property-or "property.or(other)") combines properties with the '||' operator.

<a name="property-startwith"></a>
['property.startWith(value)'](#property-startwith "property.startWith(value)") adds an initial "default" value for the
Property. If the Property doesn't have an initial value of it's own, the
given value will be used as the initial value. If the property has an
initial value of its own, the given value will be ignored.
...
```

#### <a name="apidoc.element.baconjs.Property.prototype.sample"></a>[function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>sample (interval)](#apidoc.element.baconjs.Property.prototype.sample)
- description and source-code
```javascript
sample = function (interval) {
  return withDesc(new Bacon.Desc(this, "sample", [interval]), this.sampledBy(Bacon.interval(interval, {})));
}
```
- example usage
```shell
...
myProperty.assign($("#my-button"), "toggle")
'''

Note that the ['assign'](#property-assign) method is actually just a synonym for ['onValue'](#property-onvalue) and
the [function construction rules](#function-construction-rules) below apply to both.

<a name="property-sample"></a>
['property.sample(interval)'](#property-sample "property.sample(interval)") creates an EventStream by sampling the
property value at given interval (in milliseconds)

<a name="property-sampledby"></a>
['property.sampledBy(stream)'](#property-sampledby "property.sampledBy(stream)") creates an EventStream by sampling the
property value at each event from the given stream. The result
EventStream will contain the property value at each event in the source
stream.
...
```

#### <a name="apidoc.element.baconjs.Property.prototype.sampledBy"></a>[function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>sampledBy (sampler, combinator)](#apidoc.element.baconjs.Property.prototype.sampledBy)
- description and source-code
```javascript
sampledBy = function (sampler, combinator) {
  var lazy = false;
  if (typeof combinator !== "undefined" && combinator !== null) {
    combinator = toCombinator(combinator);
  } else {
    lazy = true;
    combinator = function (f) {
      return f.value();
    };
  }
  var thisSource = new Source(this, false, lazy);
  var samplerSource = new Source(sampler, true, lazy);
  var stream = Bacon.when([thisSource, samplerSource], combinator);
  var result = sampler._isProperty ? stream.toProperty() : stream;
  return withDesc(new Bacon.Desc(this, "sampledBy", [sampler, combinator]), result);
}
```
- example usage
```shell
...
the input values. If keyCode was a function, the result stream would
contain the values returned by the function.
The [Function Construction rules](#function-construction-rules) below apply here.
The ['map'](#observable-map) method, among many others, uses [lazy evaluation](#lazy-evaluation).

<a name="stream-map"></a>
['stream.map(property)'](#stream-map "stream.map(property)") maps the stream events to the current value of
the given property. This is equivalent to ['property.sampledBy(stream)'](#property-sampledby).

<a name="observable-maperror"></a>
['observable.mapError(f)'](#observable-maperror "observable.mapError(@ : Observable[A], f : E -> A) : Observable[A]") maps errors
 using given function. More
specifically, feeds the "error" field of the error event to the function
and produces a ['Next'](#bacon-next) event based on the return value.
The [Function Construction rules](#function-construction-rules) below apply here.
You can omit the argument to produce a ['Next'](#bacon-next) event with 'undefined' value.
...
```

#### <a name="apidoc.element.baconjs.Property.prototype.startWith"></a>[function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>startWith (seed)](#apidoc.element.baconjs.Property.prototype.startWith)
- description and source-code
```javascript
startWith = function (seed) {
  return withDesc(new Bacon.Desc(this, "startWith", [seed]), this.scan(seed, function (prev, next) {
    return next;
  }));
}
```
- example usage
```shell
...
['stream.merge(otherStream)'](#stream-merge "stream.merge(otherStream)") merges two streams into one stream that delivers events
 from both

<a name="stream-holdwhen"></a>
['stream.holdWhen(valve)'](#stream-holdwhen "stream.holdWhen(@ : EventStream[A], valve : Observable[B]) : EventStream[A]") pauses
 and buffers the event stream if last event in valve is truthy.
All buffered events are released when valve becomes falsy.

<a name="stream-startwith"></a>
['stream.startWith(value)'](#stream-startwith "stream.startWith(value)") adds a starting value to the stream, i.e. concats a
single-element stream contains ['value'](#event-value) with this stream.

<a name="stream-skipwhile"></a>
['stream.skipWhile(f)'](#stream-skipwhile "stream.skipWhile(f)") skips elements until the given predicate function returns falsy
 once, and then
lets all events pass through.
The [Function Construction rules](#function-construction-rules) below apply here.
...
```

#### <a name="apidoc.element.baconjs.Property.prototype.takeUntil"></a>[function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>takeUntil (stopper)](#apidoc.element.baconjs.Property.prototype.takeUntil)
- description and source-code
```javascript
takeUntil = function (stopper) {
  var changes = this.changes().takeUntil(stopper);
  return withDesc(new Bacon.Desc(this, "takeUntil", [stopper]), addPropertyInitValueToStream(this, changes));
}
```
- example usage
```shell
...

<a name="observable-take"></a>
['observable.take(n)'](#observable-take "observable.take(@ : Observable[A], n : Number) : Observable[A]") takes at most n values
 from the stream and then ends the stream. If the stream has
fewer than n values then it is unaffected.
Equal to ['Bacon.never()'](#bacon-never) if 'n <= 0'.

<a name="observable-takeuntil"></a>
['observable.takeUntil(stream)'](#observable-takeuntil "observable.takeUntil(@ : Observable[A], stream : EventStream[B]) : Observable
[A]") takes elements from source until a Next event appears in the other stream.
If other stream ends without value, it is ignored.

<a name="observable-takewhile"></a>
['observable.takeWhile(f)'](#observable-takewhile "observable.takeWhile(@ : Observable[A], f : A -> Bool) : Observable[A]") takes
 while given predicate function holds true, and then ends.
[Function Construction rules](#function-construction-rules) apply.

<a name="observable-takewhile-property"></a>
...
```

#### <a name="apidoc.element.baconjs.Property.prototype.toEventStream"></a>[function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>toEventStream ()](#apidoc.element.baconjs.Property.prototype.toEventStream)
- description and source-code
```javascript
toEventStream = function () {
  var _this5 = this;

  return new EventStream(new Bacon.Desc(this, "toEventStream", []), function (sink) {
    return _this5.dispatcher.subscribe(function (event) {
      if (event.isInitial()) {
        event = event.toNext();
      }
      return sink(event);
    });
  });
}
```
- example usage
```shell
...
<a name="new-bacon-eventstream"></a>
['new Bacon.EventStream(subscribe)'](#new-bacon-eventstream "new Bacon.EventStream(subscribe)") creates an ['EventStream'](#eventstream
) with the given subscribe function.

['property.changes'](#property-changes) creates a stream of changes to the ['Property'](#property). The stream *does not* include
an event for the current value of the Property at the time this method was called.

<a name="property-toeventstream"></a>
['property.toEventStream()'](#property-toeventstream "property.toEventStream(@ : Property[A]) : EventStream[A]") creates an EventStream
 based on this Property. The stream contains also an event for the current
value of this Property at the time this method was called.

['new Bacon.Bus()'](#new-bacon-bus) creates a pushable/pluggable stream (see [Bus](#bus) section below)

Pro tip: you can also put Errors into streams created with the
constructors above, by using an ['Bacon.Error'](#bacon-error) object instead of a plain
value.
...
```

#### <a name="apidoc.element.baconjs.Property.prototype.toProperty"></a>[function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>toProperty ()](#apidoc.element.baconjs.Property.prototype.toProperty)
- description and source-code
```javascript
toProperty = function () {
  assertNoArguments(arguments);
  return this;
}
```
- example usage
```shell
...

<a name="stream-bufferwithtimeorcount"></a>
['stream.bufferWithTimeOrCount(delay, count)'](#stream-bufferwithtimeorcount "stream.bufferWithTimeOrCount(delay, count)") buffers
 stream events and
flushes when either the buffer contains the given number elements or the
given amount of milliseconds has passed since last buffered event.

<a name="stream-toproperty"></a>
['stream.toProperty()'](#stream-toproperty "stream.toProperty(@ : EventStream[A]) : Property[A]") creates a Property based on the
EventStream. Without arguments, you'll get a Property without an initial value.
The Property will get its first actual value from the stream, and after that it'll
always have a current value.

<a name="stream-toproperty-initialValue"></a>
['stream.toProperty(initialValue)'](#stream-toproperty-initialValue "stream.toProperty(initialValue)") creates a Property based
on the
EventStream with the given initial value that will be used as the current value until
...
```

#### <a name="apidoc.element.baconjs.Property.prototype.withHandler"></a>[function <span class="apidocSignatureSpan">baconjs.Property.prototype.</span>withHandler (handler)](#apidoc.element.baconjs.Property.prototype.withHandler)
- description and source-code
```javascript
withHandler = function (handler) {
  return new Property(new Bacon.Desc(this, "withHandler", [handler]), this.dispatcher.subscribe, handler);
}
```
- example usage
```shell
...
<a name="observable-endonerror-f"></a>
['observable.endOnError(f)'](#observable-endonerror-f "observable.endOnError(f)") ends the 'Observable' on first ['Error'](#bacon
-error) event for which
the given predicate function returns true. The error is included in the
output of the returned 'Observable'. The [Function Construction rules](#function-construction-rules) apply, so
you can do for example '.endOnError(".serious")'.

<a name="observable-withhandler"></a>
['observable.withHandler(f)'](#observable-withhandler "observable.withHandler(f)") lets you do more custom event handling: you
get all events to your function and you can output any number of events
and end the stream if you choose. For example, to send an error and end
the stream in case a value is below zero:

'''js
if (event.hasValue() && event.value() < 0) {
this.push(new Bacon.Error("Value below zero"));
...
```



# <a name="apidoc.module.baconjs.UpdateBarrier"></a>[module baconjs.UpdateBarrier](#apidoc.module.baconjs.UpdateBarrier)

#### <a name="apidoc.element.baconjs.UpdateBarrier.afterTransaction"></a>[function <span class="apidocSignatureSpan">baconjs.UpdateBarrier.</span>afterTransaction (f)](#apidoc.element.baconjs.UpdateBarrier.afterTransaction)
- description and source-code
```javascript
afterTransaction = function (f) {
  if (rootEvent) {
    return afters.push(f);
  } else {
    return f();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.UpdateBarrier.currentEventId"></a>[function <span class="apidocSignatureSpan">baconjs.UpdateBarrier.</span>currentEventId ()](#apidoc.element.baconjs.UpdateBarrier.currentEventId)
- description and source-code
```javascript
currentEventId = function () {
  return rootEvent ? rootEvent.id : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.UpdateBarrier.hasWaiters"></a>[function <span class="apidocSignatureSpan">baconjs.UpdateBarrier.</span>hasWaiters ()](#apidoc.element.baconjs.UpdateBarrier.hasWaiters)
- description and source-code
```javascript
hasWaiters = function () {
  return waiterObs.length > 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.UpdateBarrier.inTransaction"></a>[function <span class="apidocSignatureSpan">baconjs.UpdateBarrier.</span>inTransaction (event, context, f, args)](#apidoc.element.baconjs.UpdateBarrier.inTransaction)
- description and source-code
```javascript
inTransaction = function (event, context, f, args) {
  if (rootEvent) {
    return f.apply(context, args);
  } else {
    rootEvent = event;
    try {
      var result = f.apply(context, args);

      flush();
    } finally {
      rootEvent = undefined;
      while (aftersIndex < afters.length) {
        var after = afters[aftersIndex];
        aftersIndex++;
        after();
      }
      aftersIndex = 0;
      afters = [];
    }
    return result;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.UpdateBarrier.whenDoneWith"></a>[function <span class="apidocSignatureSpan">baconjs.UpdateBarrier.</span>whenDoneWith (obs, f)](#apidoc.element.baconjs.UpdateBarrier.whenDoneWith)
- description and source-code
```javascript
whenDoneWith = function (obs, f) {
  if (rootEvent) {
    var obsWaiters = waiters[obs.id];
    if (!(typeof obsWaiters !== "undefined" && obsWaiters !== null)) {
      obsWaiters = waiters[obs.id] = [f];
      return waiterObs.push(obs);
    } else {
      return obsWaiters.push(f);
    }
  } else {
    return f();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.UpdateBarrier.wrappedSubscribe"></a>[function <span class="apidocSignatureSpan">baconjs.UpdateBarrier.</span>wrappedSubscribe (obs, sink)](#apidoc.element.baconjs.UpdateBarrier.wrappedSubscribe)
- description and source-code
```javascript
wrappedSubscribe = function (obs, sink) {
  var unsubd = false;
  var shouldUnsub = false;
  var doUnsub = function () {
    shouldUnsub = true;
    return shouldUnsub;
  };
  var unsub = function () {
    unsubd = true;
    return doUnsub();
  };
  doUnsub = obs.dispatcher.subscribe(function (event) {
    return afterTransaction(function () {
      if (!unsubd) {
        var reply = sink(event);
        if (reply === Bacon.noMore) {
          return unsub();
        }
      }
    });
  });
  if (shouldUnsub) {
    doUnsub();
  }
  return unsub;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.baconjs._"></a>[module baconjs._](#apidoc.module.baconjs._)

#### <a name="apidoc.element.baconjs._.all"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>all (xs)](#apidoc.element.baconjs._.all)
- description and source-code
```javascript
all = function (xs) {
  var f = arguments.length <= 1 || arguments[1] === undefined ? _.id : arguments[1];

  for (var i = 0, x; i < xs.length; i++) {
    x = xs[i];
    if (!f(x)) {
      return false;
    }
  }
  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs._.always"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>always (x)](#apidoc.element.baconjs._.always)
- description and source-code
```javascript
always = function (x) {
  return function () {
    return x;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs._.any"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>any (xs)](#apidoc.element.baconjs._.any)
- description and source-code
```javascript
any = function (xs) {
  var f = arguments.length <= 1 || arguments[1] === undefined ? _.id : arguments[1];

  for (var i = 0, x; i < xs.length; i++) {
    x = xs[i];
    if (f(x)) {
      return true;
    }
  }
  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs._.bind"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>bind (fn, me)](#apidoc.element.baconjs._.bind)
- description and source-code
```javascript
bind = function (fn, me) {
  return function () {
    return fn.apply(me, arguments);
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs._.cached"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>cached (f)](#apidoc.element.baconjs._.cached)
- description and source-code
```javascript
cached = function (f) {
  var value = None;
  return function () {
    if (typeof value !== "undefined" && value !== null ? value._isNone : undefined) {
      value = f();
      f = undefined;
    }
    return value;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs._.contains"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>contains (xs, x)](#apidoc.element.baconjs._.contains)
- description and source-code
```javascript
contains = function (xs, x) {
  return _.indexOf(xs, x) !== -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs._.each"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>each (xs, f)](#apidoc.element.baconjs._.each)
- description and source-code
```javascript
each = function (xs, f) {
  for (var key in xs) {
    if (Object.prototype.hasOwnProperty.call(xs, key)) {
      var value = xs[key];
      f(key, value);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs._.empty"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>empty (xs)](#apidoc.element.baconjs._.empty)
- description and source-code
```javascript
empty = function (xs) {
  return xs.length === 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs._.filter"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>filter (f, xs)](#apidoc.element.baconjs._.filter)
- description and source-code
```javascript
filter = function (f, xs) {
  var filtered = [];
  for (var i = 0, x; i < xs.length; i++) {
    x = xs[i];
    if (f(x)) {
      filtered.push(x);
    }
  }
  return filtered;
}
```
- example usage
```shell
...
<a name="observable-mapend"></a>
['observable.mapEnd(f)'](#observable-mapend "observable.mapEnd(@ : Observable[A], f : -> Observable[A]) : Observable[A]") Adds an
 extra ['Next'](#bacon-next) event just before End. The value is created
by calling the given function when the source stream ends. Instead of a
function, a static value can be used. You can omit the argument to
produce a Next event with 'undefined' value.

<a name="observable-filter"></a>
['observable.filter(f)'](#observable-filter "observable.filter(@ : Observable[A], f : A -> Bool) : Observable[A]") filters values
 using given predicate function.
Instead of a function, you can use a constant value ('true' to include all, 'false' to exclude all) or a
property extractor string (like ".isValuable") instead. Just like with
['map'](#observable-map), indeed.

<a name="observable-filter-property"></a>
['observable.filter(property)'](#observable-filter-property "observable.filter(property)") filters values based on the value of
a
property. Event will be included in output [if and only if](http://en.wikipedia.org/wiki/If_and_only_if) the property holds 'true
'
...
```

#### <a name="apidoc.element.baconjs._.flatMap"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>flatMap (f, xs)](#apidoc.element.baconjs._.flatMap)
- description and source-code
```javascript
flatMap = function (f, xs) {
  return _.fold(xs, [], function (ys, x) {
    return ys.concat(f(x));
  });
}
```
- example usage
```shell
...
is executed for each error, before dispatching to subscribers.
That is, same as ['doAction'](#observable-doaction) but for errors.

<a name="observable-not"></a>
['observable.not()'](#observable-not "observable.not(@ : Obserable[A]) : Observable[Bool]") returns a stream/property that inverts
 boolean values

<a name="observable-flatmap"></a>
['observable.flatMap(f)'](#observable-flatmap "observable.flatMap(@ : Observable[A], f : A -> Observable[B] | Event[B] | B) : EventStream
[B]") for each element in the source stream, spawn a new
stream using the function 'f'. Collect events from each of the spawned
streams into the result ['EventStream'](#eventstream). Note that instead of a function, you can provide a
stream/property too. Also, the return value of function 'f' can be either an
'Observable' (stream/property) or a constant value. The result of
['flatMap'](#observable-flatmap) is always an ['EventStream'](#eventstream).

The [Function Construction rules](#function-construction-rules) below apply here.
...
```

#### <a name="apidoc.element.baconjs._.fold"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>fold (xs, seed, f)](#apidoc.element.baconjs._.fold)
- description and source-code
```javascript
fold = function (xs, seed, f) {
  for (var i = 0, x; i < xs.length; i++) {
    x = xs[i];
    seed = f(seed, x);
  }
  return seed;
}
```
- example usage
```shell
...
initial value when scan is applied. If there's no initial value, this works
identically to EventStream.scan: the 'seed' will be the initial value of
'r'. However, if 'r' already has a current/initial value 'x', the
seed won't be output as is. Instead, the initial value of 'r' will be 'f(seed, x)'. This makes sense,
because there can only be 1 initial value for a Property at a time.

<a name="observable-fold"></a>
['observable.fold(seed, f)'](#observable-fold "observable.fold(seed, f) : Property[A]") is like ['scan'](#observable-scan) but only
 emits the final
value, i.e. the value just before the observable ends. Returns a
['Property'](#property).

<a name="observable-reduce"></a>
['observable.reduce(seed, f)'](#observable-reduce "observable.reduce(seed,f)") synonym for ['fold'](#observable-fold).

<a name="observable-diff"></a>
...
```

#### <a name="apidoc.element.baconjs._.head"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>head (xs)](#apidoc.element.baconjs._.head)
- description and source-code
```javascript
head = function (xs) {
  return xs[0];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs._.id"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>id (x)](#apidoc.element.baconjs._.id)
- description and source-code
```javascript
id = function (x) {
  return x;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs._.indexOf"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>indexOf (xs, x)](#apidoc.element.baconjs._.indexOf)
- description and source-code
```javascript
indexOf = function (xs, x) {
  return xs.indexOf(x);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs._.indexWhere"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>indexWhere (xs, f)](#apidoc.element.baconjs._.indexWhere)
- description and source-code
```javascript
indexWhere = function (xs, f) {
  for (var i = 0, y; i < xs.length; i++) {
    y = xs[i];
    if (f(y)) {
      return i;
    }
  }
  return -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs._.isFunction"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>isFunction (f)](#apidoc.element.baconjs._.isFunction)
- description and source-code
```javascript
isFunction = function (f) {
  return typeof f === "function";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs._.last"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>last (xs)](#apidoc.element.baconjs._.last)
- description and source-code
```javascript
last = function (xs) {
  return xs[xs.length - 1];
}
```
- example usage
```shell
...
<a name="observable-takewhile-property"></a>
['observable.takeWhile(property)'](#observable-takewhile-property "observable.takeWhile(property)") takes values while the value
 of a property holds true, and then ends.

<a name="observable-first"></a>
['observable.first()'](#observable-first "observable.first(@ : Observable[A]) : Observable[A]") takes the first element from the
 stream. Essentially 'observable.take(1)'.

<a name="observable-last"></a>
['observable.last()'](#observable-last "observable.last(@ : Observable[A]) : Observable[A]") takes the last element from the stream
. None, if stream is empty.

*Note:* 'neverEndingStream.last()' creates the stream which doesn't produce any events and never ends.

<a name="observable-skip"></a>
['observable.skip(n)'](#observable-skip "observable.skip(n)") skips the first n elements from the stream

<a name="observable-delay"></a>
...
```

#### <a name="apidoc.element.baconjs._.map"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>map (f, xs)](#apidoc.element.baconjs._.map)
- description and source-code
```javascript
map = function (f, xs) {
  return (function () {
    var result = [];
    for (var i = 0, x; i < xs.length; i++) {
      x = xs[i];
      result.push(f(x));
    }
    return result;
  })();
}
```
- example usage
```shell
...

But you can do neater stuff too. The Bacon of bacon.js is in that you can transform,
filter and combine these streams in a multitude of ways (see API below). The methods ['map'](#observable-map),
['filter'](#observable-filter), for example, are similar to same functions in functional list programming
(like [Underscore](http://underscorejs.org/)). So, if you say

'''js
var plus = $("#plus").asEventStream("click").map(1)
var minus = $("#minus").asEventStream("click").map(-1)
var both = plus.merge(minus)
'''

.. you'll have a stream that will output the number 1 when the "plus" button is clicked
and another stream outputting -1 when the "minus" button is clicked. The 'both' stream will
be a merged stream containing events from both the plus and minus streams. This allows
...
```

#### <a name="apidoc.element.baconjs._.negate"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>negate (f)](#apidoc.element.baconjs._.negate)
- description and source-code
```javascript
negate = function (f) {
  return function (x) {
    return !f(x);
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs._.remove"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>remove (x, xs)](#apidoc.element.baconjs._.remove)
- description and source-code
```javascript
remove = function (x, xs) {
  var i = _.indexOf(xs, x);
  if (i >= 0) {
    return xs.splice(i, 1);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs._.tail"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>tail (xs)](#apidoc.element.baconjs._.tail)
- description and source-code
```javascript
tail = function (xs) {
  return xs.slice(1, xs.length);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs._.toArray"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>toArray (xs)](#apidoc.element.baconjs._.toArray)
- description and source-code
```javascript
toArray = function (xs) {
  return isArray(xs) ? xs : [xs];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs._.toString"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>toString (obj)](#apidoc.element.baconjs._.toString)
- description and source-code
```javascript
toString = function (obj) {
  var internals, key, value;
  var hasProp = ({}).hasOwnProperty;
  try {
    recursionDepth++;
    if (obj == null) {
      return "undefined";
    } else if (_.isFunction(obj)) {
      return "function";
    } else if (isArray(obj)) {
      if (recursionDepth > 5) {
        return "[..]";
      }
      return "[" + _.map(_.toString, obj).toString() + "]";
    } else if ((obj != null ? obj.toString : void 0) != null && obj.toString !== Object.prototype.toString) {
      return obj.toString();
    } else if (typeof obj === "object") {
      if (recursionDepth > 5) {
        return "{..}";
      }
      internals = (function () {
        var results = [];
        for (key in obj) {
          if (!hasProp.call(obj, key)) continue;
          value = (function () {
            var error;
            try {
              return obj[key];
            } catch (error) {
              return error;
            }
          })();
          results.push(_.toString(key) + ":" + _.toString(value));
        }
        return results;
      })();
      return "{" + internals + "}";
    } else {
      return obj;
    }
  } finally {
    recursionDepth--;
  }
}
```
- example usage
```shell
...
use this data recursively to create a string representation for the observable. This method
is probably useful for Bacon core / library / plugin development only.

For example:

    var src = Bacon.once(1)
    var obs = src.map(function(x) { return -x })
    console.log(obs.toString())
    --> Bacon.once(1).map(function)
    obs.withDescription(src, "times", -1)
    console.log(obs.toString())
    --> Bacon.once(1).times(-1)

<a name="observable-groupby"></a>
['observable.groupBy(keyF [, limitF])'](#observable-groupby "observable.groupBy(@ : Observable[A], keyF[, limitF]) : Observable[
Observable[A]]") Groups stream events to new streams by 'keyF'. Optional 'limitF' can be provided to limit grouped
...
```

#### <a name="apidoc.element.baconjs._.without"></a>[function <span class="apidocSignatureSpan">baconjs._.</span>without (x, xs)](#apidoc.element.baconjs._.without)
- description and source-code
```javascript
without = function (x, xs) {
  return _.filter(function (y) {
    return y !== x;
  }, xs);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.baconjs.scheduler"></a>[module baconjs.scheduler](#apidoc.module.baconjs.scheduler)

#### <a name="apidoc.element.baconjs.scheduler.clearInterval"></a>[function <span class="apidocSignatureSpan">baconjs.scheduler.</span>clearInterval (id)](#apidoc.element.baconjs.scheduler.clearInterval)
- description and source-code
```javascript
clearInterval = function (id) {
  return clearInterval(id);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.scheduler.clearTimeout"></a>[function <span class="apidocSignatureSpan">baconjs.scheduler.</span>clearTimeout (id)](#apidoc.element.baconjs.scheduler.clearTimeout)
- description and source-code
```javascript
clearTimeout = function (id) {
  return clearTimeout(id);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.scheduler.now"></a>[function <span class="apidocSignatureSpan">baconjs.scheduler.</span>now ()](#apidoc.element.baconjs.scheduler.now)
- description and source-code
```javascript
now = function () {
  return new Date().getTime();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.scheduler.setInterval"></a>[function <span class="apidocSignatureSpan">baconjs.scheduler.</span>setInterval (f, i)](#apidoc.element.baconjs.scheduler.setInterval)
- description and source-code
```javascript
setInterval = function (f, i) {
  return setInterval(f, i);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.baconjs.scheduler.setTimeout"></a>[function <span class="apidocSignatureSpan">baconjs.scheduler.</span>setTimeout (f, d)](#apidoc.element.baconjs.scheduler.setTimeout)
- description and source-code
```javascript
setTimeout = function (f, d) {
  return setTimeout(f, d);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
