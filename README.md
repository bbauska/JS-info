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
### <a href="https://www.typescriptlang.org/">TypeScript</a>
is concentrated on adding “strict data typing” to simplify the development and support of complex systems. It is developed by Microsoft.
### <a href="https://flow.org/">Flow</a>
also adds data typing, but in a different way. Developed by Facebook.
### <a href="https://www.dartlang.org/">Dart</a>
is a standalone language that has its own engine that runs in non-browser environments (like mobile apps), but also can be transpiled to JavaScript. Developed by Google.
### <a href="https://brython.info/">Brython</a>
is a Python transpiler to JavaScript that enables the writing of applications in pure Python without JavaScript.
### <a href="https://kotlinlang.org/docs/reference/js-overview.html">Kotlin</a>
is a modern, concise and safe programming language that can target the browser or Node.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
IDE
The term IDE (Integrated Development Environment) refers to a powerful editor with many features that usually operates on a “whole project.” As the name suggests, it’s not just an editor, but a full-scale “development environment.”

An IDE loads the project (which can be many files), allows navigation between files, provides autocompletion based on the whole project (not just the open file), and integrates with a version management system (like git), a testing environment, and other “project-level” stuff.

If you haven’t selected an IDE yet, consider the following options:

<a href="https://code.visualstudio.com/">Visual Studio Code (cross-platform, free).</a>
<a href="https://www.jetbrains.com/webstorm/">WebStorm (cross-platform, paid).</a>
For Windows, there’s also “Visual Studio”, not to be confused with “Visual Studio Code”. “Visual Studio” is a 
paid and mighty Windows-only editor, well-suited for the .NET platform. It’s also good at JavaScript. There’s 
also a free version <a href="https://www.visualstudio.com/vs/community/">Visual Studio Community</a>.

Many IDEs are paid, but have a trial period. Their cost is usually negligible compared to a qualified developer’s salary, so just choose the best one for you.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Lightweight editors
“Lightweight editors” are not as powerful as IDEs, but they’re fast, elegant and simple.

They are mainly used to open and edit a file instantly.

The main difference between a “lightweight editor” and an “IDE” is that an IDE works on a project-level, so it loads much more data on start, analyzes the project structure if needed and so on. A lightweight editor is much faster if we need only one file.

In practice, lightweight editors may have a lot of plugins including directory-level syntax analyzers and autocompleters, so there’s no strict border between a lightweight editor and an IDE.

There are many options, for instance:

<a href="https://www.sublimetext.com/">Sublime Text (cross-platform, shareware).</a>
<a href="https://notepad-plus-plus.org/">Notepad++ (Windows, free).</a>
<a href="https://www.vim.org/">Vim</a> and <a href="https://www.gnu.org/software/emacs/">Emacs</a> are also cool if you know how to use them.
The author’s personal opinion:

I’d use <a href="https://code.visualstudio.com/">Visual Studio Code</a> if I develop mostly frontend.
Otherwise, if it’s mostly another language/platform and partially frontend, then consider other editors, 
such as XCode (Mac), Visual Studio (Windows) or Jetbrains family (Webstorm, PHPStorm, RubyMine etc, 
depending on the language).

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Developer console
Code is prone to errors. You will quite likely make errors… Oh, what am I talking about? You are 
absolutely going to make errors, at least if you’re a human, not a robot.

But in the browser, users don’t see errors by default. So, if something goes wrong in the script, we 
won’t see what’s broken and can’t fix it.

To see errors and get a lot of other useful information about scripts, “developer tools” have been 
embedded in browsers.

Most developers lean towards Chrome or Firefox for development because those browsers have the best 
developer tools. Other browsers also provide developer tools, sometimes with special features, but are 
usually playing “catch-up” to Chrome or Firefox. So most developers have a “favorite” browser and switch 
to others if a problem is browser-specific.

Developer tools are potent; they have many features. To start, we’ll learn how to open them, look at errors, and 
run JavaScript commands.

### Google Chrome
Open the page <a href="https://javascript.info/article/devtools/bug.html">bug.html</a>.

There’s an error in the JavaScript code on it. It’s hidden from a regular visitor’s eyes, so let’s open developer tools to see it.

Press F12 or, if you’re on Mac, then Cmd+Opt+J.

The developer tools will open on the Console tab by default.

It looks somewhat like this:

<!-- image goes here -->

### Summary
Developer tools allow us to see errors, run commands, examine variables, and much more.
They can be opened with F12 for most browsers on Windows. Chrome for Mac needs Cmd+Opt+J, Safari: Cmd+Opt+C (need to enable first).
Now we have the environment ready. In the next section, we’ll get down to JavaScript.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
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


