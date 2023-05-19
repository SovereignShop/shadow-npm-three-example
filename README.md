# shadow-npm-three-example

This is a (non-working) Three.js app to Demo using shadow-cljs ES Modules.

It throws this error when trying to load the js file:

``` text
in.js:1279 ReferenceError: BufferGeometry$$module$node_modules$three$build$three_module is not defined
    at eval (model_viewer.js:3:13)
    at eval (<anonymous>)
    at goog.globalEval (main.js:430:11)
    at env.evalLoad (main.js:1387:12)
    at main.js:1518:12
```

This reference does exist in `public/js/cljs-runtime/module$node_modules$three$build$three_module.js`  but it is not being loaded.

My npm version is `9.6.5`
