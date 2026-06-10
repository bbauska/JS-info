# JS-info
From https://javascript.info/ giving what you need to learn in the JavaScript language. Not just "good to know" but necessary.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Manuals
MDN (Mozilla) JavaScript Reference is the main manual with examples and other information. It’s great to get in-depth information about individual language functions, methods etc.

You can find it at https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference.

Although, it’s often best to use an internet search instead. Just use “MDN [term]” in the query, e.g. https://google.com/search?q=MDN+parseInt to search for the parseInt function.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Languages “over” JavaScript
The syntax of JavaScript does not suit everyone’s needs. Different people want different features.

That’s to be expected, because projects and requirements are different for everyone.

So, recently a plethora of new languages appeared, which are transpiled (converted) to JavaScript before they run in the browser.

Modern tools make the transpilation very fast and transparent, actually allowing developers to code in another language and auto-converting it “under the hood”.

### Examples of such languages:

### <a href="https://coffeescript.org/">CoffeeScript</a>
is “syntactic sugar” for JavaScript. It introduces shorter syntax, allowing us to write clearer and more precise code. Usually, Ruby devs like it.
### TypeScript
is concentrated on adding “strict data typing” to simplify the development and support of complex systems. It is developed by Microsoft.
### Flow
also adds data typing, but in a different way. Developed by Facebook.
### Dart
is a standalone language that has its own engine that runs in non-browser environments (like mobile apps), but also can be transpiled to JavaScript. Developed by Google.
### Brython
is a Python transpiler to JavaScript that enables the writing of applications in pure Python without JavaScript.
### Kotlin
is a modern, concise and safe programming language that can target the browser or Node.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## IIFE
In the past, as there was only var, and it has no block-level visibility, programmers invented a way to emulate it. 
What they did was called “immediately-invoked function expressions” (abbreviated as IIFE).

That’s not something we should use nowadays, but you can find them in old scripts.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
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
```
let gLet = 5;
alert(window.gLet); // undefined (doesn't become a property of the global object)
```
If a value is so important that you’d like to make it available globally, write it directly as a property:
```
// make current user information global, to let all scripts access it
window.currentUser = {
  name: "John"
};
// somewhere else in code
alert(currentUser.name);  // John
// or, if we have a local variable with the name "currentUser"
// get it from window explicitly (safe!)
alert(window.currentUser.name); // John
```

That said, using global variables is generally discouraged. There should be as few global variables as possible. The code design where a function gets “input” variables and produces certain “outcome” is clearer, less prone to errors and easier to test than if it uses outer or global variables.

## Using for polyfills
We use the global object to test for support of modern language features.

For instance, test if a built-in Promise object exists (it doesn’t in really old browsers):
```
if (!window.Promise) {
  alert("Your browser is really old!");
}
```
If there’s none (say, we’re in an old browser), we can create “polyfills”: add functions that are not supported by the environment, but exist in the modern standard.
```
if (!window.Promise) {
  window.Promise = ... // custom implementation of the modern language feature
}
```


## Summary
The global object holds variables that should be available everywhere.

That includes JavaScript built-ins, such as Array and environment-specific values, such as window.innerHeight – the window height in the browser.

The global object has a universal name globalThis.

…But more often is referred by “old-school” environment-specific names, such as window (browser) and global (Node.js).

We should store values in the global object only if they’re truly global for our project. And keep their number at minimum.

In-browser, unless we’re using modules, global functions and variables declared with var become a property of the global object.

To make our code future-proof and easier to understand, we should access properties of the global object directly, as window.x.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->


