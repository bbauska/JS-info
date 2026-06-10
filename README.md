# JS-info
From https://javascript.info/ giving what you need to learn in the JavaScript language. Not just "good to know" but necessary.

## IIFE
In the past, as there was only var, and it has no block-level visibility, programmers invented a way to emulate it. 
What they did was called “immediately-invoked function expressions” (abbreviated as IIFE).

That’s not something we should use nowadays, but you can find them in old scripts.

### An IIFE looks like this:
```
(function() {
  var message = "Hello";
  alert(message); // Hello
})();
```

## Global object
The global object provides variables and functions that are available anywhere. By default, those that are built into the language or the environment.

In a browser it is named window, for Node.js it is global, for other environments it may have another name.

Recently, globalThis was added to the language, as a standardized name for a global object, that should be supported across all environments. It’s supported in all major browsers.

We’ll use window here, assuming that our environment is a browser. If your script may run in other environments, it’s better to use globalThis instead.

All properties of the global object can be accessed directly:
```
alert("Hello");
// is the same as
window.alert("Hello");
```
In a browser, global functions and variables declared with var (not let/const!) become the property of the global object:
```
var gVar = 5;
alert(window.gVar); // 5 (became a property of the global object)
```
Function declarations have the same effect (statements with function keyword in the main code flow, not function expressions).

Please don’t rely on that! This behavior exists for compatibility reasons. Modern scripts use JavaScript modules where such a thing doesn’t happen.

If we used let instead, such thing wouldn’t happen:

