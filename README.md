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
## IDE
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
## JavaScript Fundamentals
Let’s learn the fundamentals of script building.

<a href="https://javascript.info/hello-world">Hello, world!</a>
<a href="https://javascript.info/structure">Code structure</a>
<a href="https://javascript.info/strict-mode">The modern mode, "use strict"</a>
<a href="https://javascript.info/variables">Variables</a>
<a href="https://javascript.info/types">Data types</a>
<a href="https://javascript.info/alert-prompt-confirm">Interaction: alert, prompt, confirm</a>
<a href="https://javascript.info/type-conversions">Type Conversions</a>
<a href="https://javascript.info/operators">Basic operators, maths</a>
<a href="https://javascript.info/comparison">Comparisons</a>
<a href="https://javascript.info/ifelse">Conditional branching: if, '?'</a>
<a href="https://javascript.info/logical-operators">Logical operators</a>
<a href="https://javascript.info/nullish-coalescing-operator">Nullish coalescing operator '??'</a>
<a href="https://javascript.info/while-for">Loops: while and for</a>
<a href="https://javascript.info/switch">The "switch" statement</a>
<a href="https://javascript.info/function-basics">Functions</a>
<a href="https://javascript.info/function-expressions">Function expressions</a>
<a href="https://javascript.info/arrow-functions-basics">Arrow functions, the basics</a>
<a href="https://javascript.info/javascript-specials">JavaScript specials</a>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Hello, world!
```
<script src="/js/script1.js"></script>
<script src="/js/script2.js"></script>
…
```

### Summary
We can use a <script> tag to add JavaScript code to a page.
The type and language attributes are not required.
A script in an external file can be inserted with <script src="path/to/script.js"></script>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Code structure
The first thing we’ll study is the building blocks of code.

### Statements
Statements are syntax constructs and commands that perform actions.

We’ve already seen a statement, alert('Hello, world!'), which shows the message “Hello, world!”.

We can have as many statements in our code as we want. Statements can be separated with a semicolon.

For example, here we split “Hello World” into two alerts:
```
alert('Hello'); alert('World');
```
Usually, statements are written on separate lines to make the code more readable:
```
alert('Hello');
alert('World');
```
### Semicolons
A semicolon may be omitted in most cases when a line break exists.

This would also work:
```
alert('Hello')
alert('World')
```
Here, JavaScript interprets the line break as an “implicit” semicolon. This is called an automatic semicolon insertion.

In most cases, a newline implies a semicolon. But “in most cases” does not mean “always”!

There are cases when a newline does not mean a semicolon. For example:
```
alert(3 +
1
+ 2);
```
The code outputs 6 because JavaScript does not insert semicolons here. It is intuitively obvious that if the line ends with a plus "+", then it is an “incomplete expression”, so a semicolon there would be incorrect. And in this case, that works as intended.

But there are situations where JavaScript “fails” to assume a semicolon where it is really needed.

Errors which occur in such cases are quite hard to find and fix.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## The modern mode, "use strict"
For a long time, JavaScript evolved without compatibility issues. New features were added to the 
language while old functionality didn’t change.

That had the benefit of never breaking existing code. But the downside was that any mistake or an imperfect 
decision made by JavaScript’s creators got stuck in the language forever.

This was the case until 2009 when ECMAScript 5 (ES5) appeared. It added new features to the language and 
modified some of the existing ones. To keep the old code working, most such modifications are off by default. 
You need to explicitly enable them with a special directive: "use strict".

### “use strict”
The directive looks like a string: "use strict" or 'use strict'. When it is located at the top of a script, 
the whole script works the “modern” way.

### For example:
```
"use strict";
// this code works the modern way
...
```
Quite soon we’re going to learn functions (a way to group commands), so let’s note in advance that 
"use strict" can be put at the beginning of a function. Doing that enables strict mode in that 
function only. But usually people use it for the whole script.

### Ensure that “use strict” is at the top
Please make sure that "use strict" is at the top of your scripts, otherwise strict mode may not be enabled.

Strict mode isn’t enabled here:
```
alert("some code");
// "use strict" below is ignored--it must be at the top
"use strict";
// strict mode is not activated
```
Only comments may appear above "use strict"

#### There’s no way to cancel use strict
There is no directive like "no use strict" that reverts the engine to old behavior.

Once we enter strict mode, there’s no going back.

### Browser console
When you use a developer console to run code, please note that it doesn’t use strict by default.

Sometimes, when use strict makes a difference, you’ll get incorrect results.

So, how to actually use strict in the console?

First, you can try to press Shift+Enter to input multiple lines, and put use strict on top, like this:
```
'use strict'; <Shift+Enter for a newline>
//  ...your code
<Enter to run>
```
It works in most browsers, namely Firefox and Chrome.

If it doesn’t, e.g. in an old browser, there’s an ugly, but reliable way to ensure use strict. Put it inside this kind of wrapper:
```
(function() {
  'use strict';

  // ...your code here...
})()
```
### Should we “use strict”?
The question may sound obvious, but it’s not so.

One could recommend to start scripts with "use strict"… But you know what’s cool?

Modern JavaScript supports “classes” and “modules” – advanced language structures (we’ll surely get to them), that enable use strict automatically. So we don’t need to add the "use strict" directive, if we use them.

So, for now "use strict"; is a welcome guest at the top of your scripts. Later, when your code is all in classes and modules, you may omit it.

As of now, we’ve got to know about use strict in general.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Variables
Most of the time, a JavaScript application needs to work with information. Here are two examples:

1. An online shop – the information might include goods being sold and a shopping cart.
2. A chat application – the information might include users, messages, and much more.

Variables are used to store this information.

### A variable
A variable is a “named storage” for data. We can use variables to store goodies, visitors, and other data.

To create a variable in JavaScript, use the let keyword.

The statement below creates (in other words: declares) a variable with the name “message”:

```
let message;
```

Now, we can put some data into it by using the assignment operator =:

```
let message;

message = 'Hello'; // store the string 'Hello' in the variable named message
```

The string is now saved into the memory area associated with the variable. We can access it using the variable name:

```
let message;
message = 'Hello!';

alert(message); // shows the variable content
```

To be concise, we can combine the variable declaration and assignment into a single line:

```
let message = 'Hello!'; // define the variable and assign the value

alert(message); // Hello!
```

We can also declare multiple variables in one line:

```
let user = 'John', age = 25, message = 'Hello';
```

That might seem shorter, but we don’t recommend it. For the sake of better readability, please use a single line per variable.

The multiline variant is a bit longer, but easier to read:

```
let user = 'John';
let age = 25;
let message = 'Hello';
``

Some people also define multiple variables in this multiline style:

```
let user = 'John',
  age = 25,
  message = 'Hello';
```

…Or even in the “comma-first” style:

```
let user = 'John'
  , age = 25
  , message = 'Hello';
```

Technically, all these variants do the same thing. So, it’s a matter of personal taste and aesthetics.

```
var instead of let
```

In older scripts, you may also find another keyword: var instead of let:

```
var message = 'Hello';
```
The var keyword is almost the same as let. It also declares a variable but in a slightly different, “old-school” way.

There are subtle differences between let and var, but they do not matter to us yet. We’ll cover them 
in detail in the chapter The old "var".

### A real-life analogy
We can easily grasp the concept of a “variable” if we imagine it as a “box” for data, with a uniquely-
named sticker on it.

For instance, the variable message can be imagined as a box labelled "message" with the value "Hello!"
in it:
<!-- image here -->
We can put any value in the box.

We can also change it as many times as we want:
```
let message;
message = 'Hello!';
message = 'World!'; // value changed
alert(message);
```

We can also declare two variables and copy data from one into the other.

```
let hello = 'Hello world!';
let message;
// copy 'Hello world' from hello into message
message = hello;
// now two variables hold the same data
alert(hello); // Hello world!
alert(message); // Hello world!
```

### Variable naming
There are two limitations on variable names in JavaScript:

1. The name must contain only letters, digits, or the symbols $ and _.
2. The first character must not be a digit.

Examples of valid names:
```
let userName;
let test123;
```

When the name contains multiple words, camelCase is commonly used. That is: words go one after another,
with each word except the first starting with a capital letter: myVeryLongName.

What’s interesting – the dollar sign '$' and the underscore '_' can also be used in names. They are regular
symbols, just like letters, without any special meaning.

#### These names are valid:
```
let $ = 1; // declared a variable with the name "$"
let _ = 2; // and now a variable with the name "_"

alert($ + _); // 3
```
Examples of incorrect variable names:
```
let 1a; // cannot start with a digit

let my-name; // hyphens '-' aren't allowed in the name
```
#### Case matters
Variables named apple and APPLE are two different variables.


### Constants
To declare a constant (unchanging) variable, use const instead of let:
```
const myBirthday = '18.04.1982';
```
Variables declared using const are called “constants”. They cannot be reassigned. An attempt to do so would cause an error:
```
const myBirthday = '18.04.1982';

myBirthday = '01.01.2001'; // error, can't reassign the constant!
```

#### Uppercase constants
There is a widespread practice to use constants as aliases for difficult-to-remember values that are known before execution.

Such constants are named using capital letters and underscores.

For instance, let’s make constants for colors in so-called “web” (hexadecimal) format:
```
const COLOR_RED = "#F00";
const COLOR_GREEN = "#0F0";
const COLOR_BLUE = "#00F";
const COLOR_ORANGE = "#FF7F00";

// ...when we need to pick a color
let color = COLOR_ORANGE;
alert(color); // #FF7F00
```

#### Benefits:

COLOR_ORANGE is much easier to remember than "#FF7F00".
It is much easier to mistype "#FF7F00" than COLOR_ORANGE.
When reading the code, COLOR_ORANGE is much more meaningful than #FF7F00.
When should we use capitals for a constant and when should we name it normally? Let’s make that clear.

Being a “constant” just means that a variable’s value never changes. But some constants are known before execution (like a hexadecimal value for red) and some constants are calculated in run-time, during the execution, but do not change after their initial assignment.

For instance:
```
const pageLoadTime = /* time taken by a webpage to load */;
```
The value of pageLoadTime is not known before the page load, so it’s named normally. But it’s still a
constant because it doesn’t change after the assignment.

In other words, capital-named constants are only used as aliases for “hard-coded” values.

#### Name things right

### Summary
We can declare variables to store data by using the var, let, or const keywords.

  - let – is a modern variable declaration.
  - var – is an old-school variable declaration. Normally we don’t use it at all, but we’ll cover subtle
          differences from let in the chapter The old "var", just in case you need them.
  - const – is like let, but the value of the variable can’t be changed.

Variables should be named in a way that allows us to easily understand what’s inside them.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Data types
A value in JavaScript is always of a certain type. For example, a string or a number.

There are eight basic data types in JavaScript. Here, we’ll cover them in general and in the next chapters we’ll talk about each of them in detail.

We can put any type in a variable. For example, a variable can at one moment be a string and then store a number:
```
// no error
let message = "hello";
message = 123456;
```
Programming languages that allow such things, such as JavaScript, are called “dynamically typed”, meaning that there exist data types, but variables are not bound to any of them.

### Number
```
let n = 123;
n = 12.345;
```

The number type represents both integer and floating point numbers.

There are many operations for numbers, e.g. multiplication *, division /, addition +, subtraction -, and so on.

Besides regular numbers, there are so-called “special numeric values” which also belong to this data type:
Infinity, -Infinity and NaN.

Infinity represents the mathematical Infinity ∞. It is a special value that’s greater than any number.

We can get it as a result of division by zero:
```
alert( 1 / 0 ); // Infinity
```
Or just reference it directly:
```
alert( Infinity ); // Infinity
```
NaN represents a computational error. It is a result of an incorrect or an undefined mathematical operation, for instance:
```
alert( "not a number" / 2 ); // NaN, such division is erroneous
```
NaN is sticky. Any further mathematical operation on NaN returns NaN:
```
alert( NaN + 1 ); // NaN
alert( 3 * NaN ); // NaN
alert( "not a number" / 2 - 1 ); // NaN
```
So, if there’s a NaN somewhere in a mathematical expression, it propagates to the whole result
(there’s only one exception to that: NaN ** 0 is 1).

### BigInt
In JavaScript, the “number” type cannot safely represent integer values larger than (253-1) (that’s
9007199254740991), or less than -(253-1) for negatives.

To be really precise, the “number” type can store larger integers (up to 1.7976931348623157 * 10308),
but outside of the safe integer range ±(253-1) there’ll be a precision error, because not all digits
fit into the fixed 64-bit storage. So an “approximate” value may be stored.

For example, these two numbers (right above the safe range) are the same:
```
console.log(9007199254740991 + 1); // 9007199254740992
console.log(9007199254740991 + 2); // 9007199254740992
```
So to say, all odd integers greater than (253-1) can’t be stored at all in the “number” type.

For most purposes ±(253-1) range is quite enough, but sometimes we need the entire range of really big integers, e.g. for cryptography or microsecond-precision timestamps.

BigInt type was recently added to the language to represent integers of arbitrary length.

A BigInt value is created by appending n to the end of an integer:
```
// the "n" at the end means it's a BigInt
const bigInt = 1234567890123456789012345678901234567890n;
```
As BigInt numbers are rarely needed, we don’t cover them here, but devoted them a separate chapter BigInt.
Read it when you need such big numbers.

### String
A string in JavaScript must be surrounded by quotes.
```
let str = "Hello";
let str2 = 'Single quotes are ok too';
let phrase = `can embed another ${str}`;
```
In JavaScript, there are 3 types of quotes.

1. Double quotes: "Hello".
2. Single quotes: 'Hello'.
3. Backticks: `Hello`.

Double and single quotes are “simple” quotes. There’s practically no difference between them in JavaScript.

Backticks are “extended functionality” quotes. They allow us to embed variables and expressions into
a string by wrapping them in ${…}, for example:

```
let name = "John";
// embed a variable
alert( `Hello, ${name}!` ); // Hello, John!
// embed an expression
alert( `the result is ${1 + 2}` ); // the result is 3
```
The expression inside ${…} is evaluated and the result becomes a part of the string. We can put
anything in there: a variable like name or an arithmetical expression like 1 + 2 or something more complex.

Please note that this can only be done in backticks. Other quotes don’t have this embedding functionality!
```
alert( "the result is ${1 + 2}" ); // the result is ${1 + 2} (double quotes do nothing)
```
We’ll cover strings more thoroughly in the chapter Strings.

There is no character type.

In some languages, there is a special “character” type for a single character. For example, in the C
language and in Java it is called “char”.

In JavaScript, there is no such type. There’s only one type: string. A string may consist of zero characters
(be empty), one character or many of them.

### Boolean (logical type)

The boolean type has only two values: true and false.

This type is commonly used to store yes/no values: true means “yes, correct”, and false means “no, incorrect”.

For instance:
```
let nameFieldChecked = true; // yes, name field is checked
let ageFieldChecked = false; // no, age field is not checked
```
Boolean values also come as a result of comparisons:
```
let isGreater = 4 > 1;

alert( isGreater ); // true (the comparison result is "yes")
```
We’ll cover booleans more deeply in the chapter Logical operators.

### The “null” value
The special null value does not belong to any of the types described above.

It forms a separate type of its own which contains only the null value:
```
let age = null;
```
In JavaScript, null is not a “reference to a non-existing object” or a “null pointer” like in some other languages.

It’s just a special value which represents “nothing”, “empty” or “value unknown”.

The code above states that age is unknown.

The “undefined” value
The special value undefined also stands apart. It makes a type of its own, just like null.

The meaning of undefined is “value is not assigned”.

If a variable is declared, but not assigned, then its value is undefined:
let age;

alert(age); // shows "undefined"
```

Technically, it is possible to explicitly assign undefined to a variable:

```
let age = 100;

// change the value to undefined
age = undefined;

alert(age); // "undefined"
```

…But we don’t recommend doing that. Normally, one uses null to assign an “empty” or “unknown” value to a variable, while undefined is reserved as a default initial value for unassigned things.

### Objects and Symbols
The object type is special.

All other types are called “primitive” because their values can contain only a single thing (be it a string or a number or whatever). In contrast, objects are used to store collections of data and more complex entities.

Being that important, objects deserve a special treatment. We’ll deal with them later in the chapter Objects, after we learn more about primitives.

The symbol type is used to create unique identifiers for objects. We have to mention it here for the sake of completeness, but also postpone the details till we know objects.

### The typeof operator
The typeof operator returns the type of the operand. It’s useful when we want to process values of different types differently or just want to do a quick check.

A call to typeof x returns a string with the type name:

```
typeof undefined // "undefined"
typeof 0 // "number"
typeof 10n // "bigint"
typeof true // "boolean"
typeof "foo" // "string"
typeof Symbol("id") // "symbol"
typeof Math // "object"  (1)
typeof null // "object"  (2)
typeof alert // "function"  (3)
```
The last three lines may need additional explanation:

  1. Math is a built-in object that provides mathematical operations. We will learn it in the chapter
     Numbers. Here, it serves just as an example of an object.
     
  2 The result of typeof null is "object". That’s an officially recognized error in typeof, coming from 
    very early days of JavaScript and kept for compatibility. Definitely, null is not an object. It is a 
    special value with a separate type of its own. The behavior of typeof is wrong here.

  3. The result of typeof alert is "function", because alert is a function. We’ll study functions in the
     next chapters where we’ll also see that there’s no special “function” type in JavaScript. Functions
     belong to the object type. But typeof treats them differently, returning "function". That also comes
     from the early days of JavaScript. Technically, such behavior isn’t correct, but can be convenient in practice.

#### The typeof(x) syntax
You may also come across another syntax: typeof(x). It’s the same as typeof x.

To put it clear: typeof is an operator, not a function. The parentheses here aren’t a part of typeof. It’s the kind of parentheses used for mathematical grouping.

Usually, such parentheses contain a mathematical expression, such as (2 + 2), but here they contain only one argument (x). Syntactically, they allow to avoid a space between the typeof operator and its argument, and some people like it.

Some people prefer typeof(x), although the typeof x syntax is much more common.

### Summary
There are 8 basic data types in JavaScript.

#### Seven primitive data types:
  - number for numbers of any kind: integer or floating-point, integers are limited by ±(253-1).
  - bigint for integer numbers of arbitrary length.
  - string for strings. A string may have zero or more characters, there’s no separate single-character type.
  - boolean for true/false.
  - null for unknown values – a standalone type that has a single value null.
  - undefined for unassigned values – a standalone type that has a single value undefined.
  - symbol for unique identifiers.
And one non-primitive data type:
  - object for more complex data structures.

The typeof operator allows us to see which type is stored in a variable.
  - Usually used as typeof x, but typeof(x) is also possible.
  - Returns a string with the name of the type, like "string".
  - For null returns "object" – this is an error in the language, it’s not actually an object.

Backticks embed the expression inside ${...} into the string.
```
let name = "Ilya";

// the expression is a number 1
alert( `hello ${1}` ); // hello 1

// the expression is a string "name"
alert( `hello ${"name"}` ); // hello name

// the expression is a variable, embed it
alert( `hello ${name}` ); // hello Ilya
```
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Interaction: alert, prompt, confirm
As we’ll be using the browser as our demo environment, let’s see a couple of functions to interact 
with the user: alert, prompt and confirm.

### alert
This one we’ve seen already. It shows a message and waits for the user to press “OK”.

For example:
```
alert("Hello");
```
The mini-window with the message is called a modal window. The word “modal” means that the visitor can’t interact with the rest of the page, press other buttons, etc, until they have dealt with the window. In this case – until they press “OK”.

### prompt
The function prompt accepts two arguments:
```
result = prompt(title, [default]);
```
It shows a modal window with a text message, an input field for the visitor, and the buttons OK/Cancel.

### title - The text to show the visitor.
### default - An optional second parameter, the initial value for the input field.

### The square brackets in syntax [...]
The square brackets around default in the syntax above denote that the parameter is optional, not required.
The visitor can type something in the prompt input field and press OK. Then we get that text in the result. Or they can cancel the input by pressing Cancel or hitting the Esc key, then we get null as the result.

The call to prompt returns the text from the input field or null if the input was canceled.

For instance:
```
let age = prompt('How old are you?', 100);
alert(`You are ${age} years old!`); // You are 100 years old!
```
In IE: always supply a default
The second parameter is optional, but if we don’t supply it, Internet Explorer will insert the text 
"undefined" into the prompt.

Run this code in Internet Explorer to see:
```
let test = prompt("Test");
```
So, for prompts to look good in IE, we recommend always providing the second argument:
```
let test = prompt("Test", ''); // <-- for IE
```
### confirm
The syntax:
```
result = confirm(question);
```
The function confirm shows a modal window with a question and two buttons: OK and Cancel.
The result is true if OK is pressed and false otherwise.

For example:
```
let isBoss = confirm("Are you the boss?");
alert( isBoss ); // true if OK is pressed
```
### Summary
We covered 3 browser-specific functions to interact with visitors:

### alert
shows a message.
### prompt
shows a message asking the user to input text. It returns the text or, if Cancel button or Esc is 
clicked, null.
### confirm
shows a message and waits for the user to press “OK” or “Cancel”. It returns true for OK and false 
for Cancel/Esc.
All these methods are modal: they pause script execution and don’t allow the visitor to interact with the rest of the page until the window has been dismissed.

There are two limitations shared by all the methods above:
  1. The exact location of the modal window is determined by the browser. Usually, it’s in the center.
  2. The exact look of the window also depends on the browser. We can’t modify it.

That is the price for simplicity. There are other ways to show nicer windows and richer interaction 
with the visitor, but if “bells and whistles” do not matter much, these methods work just fine.

Example:
JavaScript-code:
```
let name = prompt("What is your name?", "");
alert(name);
```
The full page:
```
<!DOCTYPE html>
<html>
<body>
  <script>
    'use strict';
    let name = prompt("What is your name?", "");
    alert(name);
  </script>
</body>
</html>
```
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Type Conversions
Most of the time, operators and functions automatically convert the values given to them to the right type.

For example, alert automatically converts any value to a string to show it. Mathematical operations 
convert values to numbers.

There are also cases when we need to explicitly convert a value to the expected type.

Not talking about objects yet
In this chapter, we won’t cover objects. For now, we’ll just be talking about primitives.

Later, after we learn about objects, in the chapter Object to primitive conversion we’ll see how objects fit in.

### String Conversion
String conversion happens when we need the string form of a value.

For example, alert(value) does it to show the value.

We can also call the String(value) function to convert a value to a string:
```
let value = true;
alert(typeof value); // boolean
value = String(value); // now value is a string "true"
alert(typeof value); // string
```
String conversion is mostly obvious. A false becomes "false", null becomes "null", etc.

### Numeric Conversion
Numeric conversion in mathematical functions and expressions happens automatically.

For example, when division / is applied to non-numbers:
```
alert( "6" / "2" ); // 3, strings are converted to numbers
```
We can use the Number(value) function to explicitly convert a value to a number:
```
let str = "123";
alert(typeof str); // string
let num = Number(str); // becomes a number 123
alert(typeof num); // number
```
Explicit conversion is usually required when we read a value from a string-based source like a 
text form but expect a number to be entered.

If the string is not a valid number, the result of such a conversion is NaN. For instance:
```
let age = Number("an arbitrary string instead of a number");
alert(age); // NaN, conversion failed
```
#### Numeric conversion rules:
| Value     |  Becomes… |
| :---------: | :----------------------------------------------------------------- |
| undefined |      NaN |
| null	    |        0 |
| true and false | 1 and 0 |
|string          | Whitespaces (includes spaces, tabs \t, newlines \n etc.) from the start and end are removed. If the remaining string is empty, the result is 0. Otherwise, the number is “read” from the string. An error gives NaN. |

Examples:
```
alert( Number("   123   ") ); // 123
alert( Number("123z") );      // NaN (error reading a number at "z")
alert( Number(true) );        // 1
alert( Number(false) );       // 0
```
Please note that null and undefined behave differently here: null becomes zero while undefined becomes NaN.

Most mathematical operators also perform such conversion, we’ll see that in the next chapter.

### Boolean Conversion
Boolean conversion is the simplest one.

It happens in logical operations (later we’ll meet condition tests and other similar things) but can also be performed explicitly with a call to Boolean(value).

The conversion rule:

Values that are intuitively “empty”, like 0, an empty string, null, undefined, and NaN, become false.
Other values become true.
For instance:
```
alert( Boolean(1) ); // true
alert( Boolean(0) ); // false

alert( Boolean("hello") ); // true
alert( Boolean("") ); // false
```
Please note: the string with zero "0" is true
```
alert( Boolean("0") ); // true
alert( Boolean(" ") ); // spaces, also true (any non-empty string is true)
```
### Summary
The three most widely used type conversions are to string, to number, and to boolean.

String Conversion – Occurs when we output something. Can be performed with String(value). The 
conversion to string is usually obvious for primitive values.

Numeric Conversion – Occurs in math operations. Can be performed with Number(value).

The conversion follows the rules:

| Value |	Becomes… |
|-------|----------|
| undefined	| NaN |
| null | 0 |
| true / false | 1 / 0 |
| string | The string is read “as is”, whitespaces (includes spaces, tabs \t, newlines \n etc.) from both sides are ignored. An empty string becomes 0. An error gives NaN. |

Boolean Conversion – Occurs in logical operations. Can be performed with Boolean(value).

#### Follows the rules:

| Value |	Becomes… |
|:-----:|:----------|
|0, null, undefined, NaN, "" | false |
|any other value | true |

Most of these rules are easy to understand and memorize. The notable exceptions where people usually make
  - undefined is NaN as a number, not 0.
  - "0" and space-only strings like " " are true as a boolean.

Objects aren’t covered here. We’ll return to them later in the chapter Object to primitive conversion 
that is devoted exclusively to objects after we learn more basic things about JavaScript.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Basic operators, maths
We know many operators from school. They are things like addition +, multiplication *, subtraction -, and so on.

In this chapter, we’ll start with simple operators, then concentrate on JavaScript-specific aspects, 
not covered by school arithmetic.

### Terms: “unary”, “binary”, “operand”
Before we move on, let’s grasp some common terminology.

  - An operand – is what operators are applied to. For instance, in the multiplication of 5 * 2 there are 
two operands: the left operand is 5 and the right operand is 2. Sometimes, people call these “arguments” 
instead of “operands”.

  - An operator is unary if it has a single operand. For example, the unary negation - reverses the sign
  of a number:
```
let x = 1;
x = -x;
alert( x ); // -1, unary negation was applied
```
  - An operator is binary if it has two operands. The same minus exists in binary form as well:
```
let x = 1, y = 3;
alert( y - x ); // 2, binary minus subtracts values
```
Formally, in the examples above we have two different operators that share the same symbol: the 
negation operator, a unary operator that reverses the sign, and the subtraction operator, a binary 
operator that subtracts one number from another.

### Maths
The following math operations are supported:

 - Addition +,
 - Subtraction -,
 - Multiplication *,
 - Division /,
 - Remainder %,
 - Exponentiation **.

The first four are straightforward, while % and ** need a few words about them.

### Remainder %
The remainder operator %, despite its appearance, is not related to percents.

The result of a % b is the remainder of the integer division of a by b.

For instance:
```
alert( 5 % 2 ); // 1, the remainder of 5 divided by 2
alert( 8 % 3 ); // 2, the remainder of 8 divided by 3
alert( 8 % 4 ); // 0, the remainder of 8 divided by 4
```
### Exponentiation **
The exponentiation operator a ** b raises a to the power of b.

In school maths, we write that as ab.

For instance:
```
alert( 2 ** 2 ); // 2² = 4
alert( 2 ** 3 ); // 2³ = 8
alert( 2 ** 4 ); // 2⁴ = 16
```
Just like in maths, the exponentiation operator is defined for non-integer numbers as well.

For example, a square root is an exponentiation by ½:
```
alert( 4 ** (1/2) ); // 2 (power of 1/2 is the same as a square root)
alert( 8 ** (1/3) ); // 2 (power of 1/3 is the same as a cubic root)
String concatenation with binary +
```
Let’s meet the features of JavaScript operators that are beyond school arithmetics.

Usually, the plus operator + sums numbers.

But, if the binary + is applied to strings, it merges (concatenates) them:
```
let s = "my" + "string";
alert(s); // mystring
```
Note that if any of the operands is a string, then the other one is converted to a string too.

For example:
```
alert( '1' + 2 ); // "12"
alert( 2 + '1' ); // "21"
```
See, it doesn’t matter whether the first operand is a string or the second one.

Here’s a more complex example:
```
alert(2 + 2 + '1' ); // "41" and not "221"
```
Here, operators work one after another. The first + sums two numbers, so it returns 4, then the 
next + adds the string 1 to it, so it’s like 4 + '1' = '41'.
```
alert('1' + 2 + 2); // "122" and not "14"
```
Here, the first operand is a string, the compiler treats the other two operands as strings too. 
The 2 gets concatenated to '1', so it’s like '1' + 2 = "12" and "12" + 2 = "122".

The binary + is the only operator that supports strings in such a way. Other arithmetic operators 
work only with numbers and always convert their operands to numbers.

Here’s the demo for subtraction and division:
```
alert( 6 - '2' ); // 4, converts '2' to a number
alert( '6' / '2' ); // 3, converts both operands to numbers
```
### Numeric conversion, unary +
The plus + exists in two forms: the binary form that we used above and the unary form.

The unary plus or, in other words, the plus operator + applied to a single value, doesn’t do anything 
to numbers. But if the operand is not a number, the unary plus converts it into a number.

For example:
```
// No effect on numbers
let x = 1;
alert( +x ); // 1

let y = -2;
alert( +y ); // -2

// Converts non-numbers
alert( +true ); // 1
alert( +"" );   // 0
```
It actually does the same thing as Number(...), but is shorter.

The need to convert strings to numbers arises very often. For example, if we are getting values from 
HTML form fields, they are usually strings. What if we want to sum them?

The binary plus would add them as strings:
```
let apples = "2";
let oranges = "3";
alert( apples + oranges ); // "23", the binary plus concatenates strings
```
If we want to treat them as numbers, we need to convert and then sum them:
```
let apples = "2";
let oranges = "3";
// both values converted to numbers before the binary plus
alert( +apples + +oranges ); // 5
// the longer variant
// alert( Number(apples) + Number(oranges) ); // 5
```
From a mathematician’s standpoint, the abundance of pluses may seem strange. But from a programmer’s 
standpoint, there’s nothing special: unary pluses are applied first, they convert strings to numbers, 
and then the binary plus sums them up.

Why are unary pluses applied to values before the binary ones? As we’re going to see, that’s because 
of their higher precedence.

### Operator precedence
If an expression has more than one operator, the execution order is defined by their precedence, 
or, in other words, the default priority order of operators.

From school, we all know that the multiplication in the expression 1 + 2 * 2 should be calculated before 
the addition. That’s exactly the precedence thing. The multiplication is said to have a higher precedence 
than the addition.

Parentheses override any precedence, so if we’re not satisfied with the default order, we can use them to 
change it. For example, write (1 + 2) * 2.

There are many operators in JavaScript. Every operator has a corresponding precedence number. The one 
with the larger number executes first. If the precedence is the same, the execution order is from left 
to right.

Here’s an extract from the precedence table (you don’t need to remember this, but note that unary operators 
are higher than corresponding binary ones):

Precedence	Name	Sign
…	…	…
14	unary plus	+
14	unary negation	-
13	exponentiation	**
12	multiplication	*
12	division	/
11	addition	+
11	subtraction	-
…	…	…
2	assignment	=
…	…	…
As we can see, the “unary plus” has a priority of 14 which is higher than the 11 of “addition” (binary plus). 
That’s why, in the expression "+apples + +oranges", unary pluses work before the addition.

### Assignment
Let’s note that an assignment = is also an operator. It is listed in the precedence table with the very low 
priority of 2.

That’s why, when we assign a variable, like x = 2 * 2 + 1, the calculations are done first and then the = 
is evaluated, storing the result in x.
```
let x = 2 * 2 + 1;
alert( x ); // 5
```
#### Assignment = returns a value
The fact of = being an operator, not a “magical” language construct has an interesting implication.

All operators in JavaScript return a value. That’s obvious for + and -, but also true for =.

The call x = value writes the value into x and then returns it.

Here’s a demo that uses an assignment as part of a more complex expression:
```
let a = 1;
let b = 2;
let c = 3 - (a = b + 1);
alert( a ); // 3
alert( c ); // 0
```
In the example above, the result of expression (a = b + 1) is the value which was assigned to 
a (that is 3). It is then used for further evaluations.

Funny code, isn’t it? We should understand how it works, because sometimes we see it in JavaScript libraries.

Although, please don’t write the code like that. Such tricks definitely don’t make code clearer or readable.

#### Chaining assignments
Another interesting feature is the ability to chain assignments:
```
let a, b, c;
a = b = c = 2 + 2;
alert( a ); // 4
alert( b ); // 4
alert( c ); // 4
```
Chained assignments evaluate from right to left. First, the rightmost expression 2 + 2 is 
evaluated and then assigned to the variables on the left: c, b and a. At the end, all the 
variables share a single value.

Once again, for the purposes of readability it’s better to split such code into a few lines:
```
c = 2 + 2;
b = c;
a = c;
```
That’s easier to read, especially when eye-scanning the code fast.

### Modify-in-place
We often need to apply an operator to a variable and store the new result in that same variable.

For example:
```
let n = 2;
n = n + 5;
n = n * 2;
```
This notation can be shortened using the operators += and *=:
```
let n = 2;
n += 5; // now n = 7 (same as n = n + 5)
n *= 2; // now n = 14 (same as n = n * 2)
alert( n ); // 14
```
Short “modify-and-assign” operators exist for all arithmetical and bitwise operators: /=, -=, etc.

Such operators have the same precedence as a normal assignment, so they run after most other calculations:
```
let n = 2;
n *= 3 + 5; // right part evaluated first, same as n *= 8
alert( n ); // 16
```
### Increment/decrement
Increasing or decreasing a number by one is among the most common numerical operations.

So, there are special operators for it:

Increment ++ increases a variable by 1:
```
let counter = 2;
counter++;        // works the same as counter = counter + 1, but is shorter
alert( counter ); // 3
```
### Decrement -- decreases a variable by 1:
```
let counter = 2;
counter--;        // works the same as counter = counter - 1, but is shorter
alert( counter ); // 1
```
Important:
Increment/decrement can only be applied to variables. Trying to use it on a value like 5++ will give an error.

The operators ++ and -- can be placed either before or after a variable.

When the operator goes after the variable, it is in “postfix form”: counter++.
The “prefix form” is when the operator goes before the variable: ++counter.
Both of these statements do the same thing: increase counter by 1.

Is there any difference? Yes, but we can only see it if we use the returned value of ++/--.

Let’s clarify. As we know, all operators return a value. Increment/decrement is no exception. 
The prefix form returns the new value while the postfix form returns the old value (prior to increment/decrement).

To see the difference, here’s an example:
```
let counter = 1;
let a = ++counter; // (*)
alert(a); // 2
```
In the line (*), the prefix form ++counter increments counter and returns the new value, 2. So, the alert shows 2.

Now, let’s use the postfix form:
```
let counter = 1;
let a = counter++; // (*) changed ++counter to counter++
alert(a); // 1
```
In the line (*), the postfix form counter++ also increments counter but returns the old value (prior 
to increment). So, the alert shows 1.

### To summarize:

If the result of increment/decrement is not used, there is no difference in which form to use:
```
let counter = 0;
counter++;
++counter;
alert( counter ); // 2, the lines above did the same
```
If we’d like to increase a value and immediately use the result of the operator, we need the prefix form:
```
let counter = 0;
alert( ++counter ); // 1
```
If we’d like to increment a value but use its previous value, we need the postfix form:
```
let counter = 0;
alert( counter++ ); // 0
```
Increment/decrement among other operators
The operators ++/-- can be used inside expressions as well. Their precedence is higher than most other arithmetical operations.

For instance:
```
let counter = 1;
alert( 2 * ++counter ); // 4
```
Compare with:
```
let counter = 1;
alert( 2 * counter++ ); // 2, because counter++ returns the "old" value
```
Though technically okay, such notation usually makes code less readable. One line does multiple things – not good.

While reading code, a fast “vertical” eye-scan can easily miss something like counter++ and it won’t be obvious that the variable increased.

We advise a style of “one line – one action”:
```
let counter = 1;
alert( 2 * counter );
counter++;
```
#### Bitwise operators
Bitwise operators treat arguments as 32-bit integer numbers and work on the level of their binary representation.

These operators are not JavaScript-specific. They are supported in most programming languages.

The list of operators:
```
AND ( & )
OR ( | )
XOR ( ^ )
NOT ( ~ )
LEFT SHIFT ( << )
RIGHT SHIFT ( >> )
ZERO-FILL RIGHT SHIFT ( >>> )
```

These operators are used very rarely, when we need to fiddle with numbers on the very lowest (bitwise) level. We won’t need these operators any time soon, as web development has little use of them, but in some special areas, such as cryptography, they are useful. You can read the Bitwise Operators chapter on MDN when a need arises.

#### Comma
The comma operator , is one of the rarest and most unusual operators. Sometimes, it’s used to write shorter code, so we need to know it in order to understand what’s going on.

The comma operator allows us to evaluate several expressions, dividing them with a comma ,. Each of them is evaluated but only the result of the last one is returned.

For example:
```
let a = (1 + 2, 3 + 4);
alert( a ); // 7 (the result of 3 + 4)
```
Here, the first expression 1 + 2 is evaluated and its result is thrown away. Then, 3 + 4 is 
evaluated and returned as the result.

#### Comma has a very low precedence
Please note that the comma operator has very low precedence, lower than =, so parentheses are important in the example above.

Without them: a = 1 + 2, 3 + 4 evaluates + first, summing the numbers into a = 3, 7, then the assignment operator = assigns a = 3, and the rest is ignored. It’s like (a = 1 + 2), 3 + 4.

Why do we need an operator that throws away everything except the last expression?

Sometimes, people use it in more complex constructs to put several actions in one line.

For example:
```
// three operations in one line
for (a = 1, b = 3, c = a * b; a < 10; a++) {
 ...
}
```
Such tricks are used in many JavaScript frameworks. That’s why we’re mentioning them. But usually 
they don’t improve code readability so we should think well before using them

### Tasks
#### The postfix and prefix forms
What are the final values of all variables a, b, c and d after the code below?
```
let a = 1, b = 1;
let c = ++a; // ?
let d = b++; // ?
```
The answer is:
```
a = 2
b = 2
c = 2
d = 1
```
```
let a = 1, b = 1;

alert( ++a ); // 2, prefix form returns the new value
alert( b++ ); // 1, postfix form returns the old value
alert( a ); // 2, incremented once
alert( b ); // 2, incremented once
```

#### Assignment result
What are the values of a and x after the code below?
```
let a = 2;
let x = 1 + (a *= 2);
```
The answer is:
```
a = 4 (multiplied by 2)
x = 5 (calculated as 1 + 4)
```

#### Type conversions
What are results of these expressions?
```
1. "" + 1 + 0
2. "" - 1 + 0
3. true + false
4. 6 / "3"
5. "2" * "3"
6. 4 + 5 + "px"
7. "$" + 4 + 5
8. "4" - 2
9. "4px" - 2
10. "  -9  " + 5
11. "  -9  " - 5
12. null + 1
13. undefined + 1
14. " \t \n" - 2
```
Think well, write down and then compare with the answer.

solution
```
1. "" + 1 + 0 = "10" // (1)
2. "" - 1 + 0 = -1 // (2)
3. true + false = 1
4. 6 / "3" = 2
5. "2" * "3" = 6
6. 4 + 5 + "px" = "9px"
7. "$" + 4 + 5 = "$45"
8. "4" - 2 = 2
9. "4px" - 2 = NaN
10. "  -9  " + 5 = "  -9  5" // (3)
11. "  -9  " - 5 = -14 // (4)
12. null + 1 = 1 // (5)
13. undefined + 1 = NaN // (6)
14. " \t \n" - 2 = -2 // (7)
```
1. The addition with a string "" + 1 converts 1 to a string: "" + 1 = "1", and then we have "1" + 0, the same rule is applied.
2. The subtraction - (like most math operations) only works with numbers, it converts an empty string "" to 0.
3. The addition with a string appends the number 5 to the string.
4. The subtraction always converts to numbers, so it makes " -9 " a number -9 (ignoring spaces around it).
5. null becomes 0 after the numeric conversion.
6. undefined becomes NaN after the numeric conversion.
7. Space characters are trimmed off string start and end when a string is converted to a number. Here
the whole string consists of space characters, such as \t, \n and a “regular” space between them. So,
similarly to an empty string, it becomes 0.

#### Fix the addition
Here’s a code that asks the user for two numbers and shows their sum.

It works incorrectly. The output in the example below is 12 (for default prompt values).

Why? Fix it. The result should be 3.
```
let a = prompt("First number?", 1);
let b = prompt("Second number?", 2);
alert(a + b); // 12
```
solution
The reason is that prompt returns user input as a string.

So variables have values "1" and "2" respectively.
```
let a = "1"; // prompt("First number?", 1);
let b = "2"; // prompt("Second number?", 2);
alert(a + b); // 12
```
What we should do is to convert strings to numbers before +. For example, using Number() or prepending them with +.

For example, right before prompt:
```
let a = +prompt("First number?", 1);
let b = +prompt("Second number?", 2);
alert(a + b); // 3
```
Or in the alert:
```
let a = prompt("First number?", 1);
let b = prompt("Second number?", 2);
alert(+a + +b); // 3
```
Using both unary and binary + in the latest code. Looks funny, doesn’t it?
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Comparisons
We know many comparison operators from maths.

In JavaScript they are written like this:

  - Greater/less than: a > b, a < b.
  - Greater/less than or equals: a >= b, a <= b.
  - Equals: a == b, please note the double equality sign == means the equality test, while a single one a = b means an assignment.
  - Not equals: In maths the notation is ≠, but in JavaScript it’s written as a != b.

In this article we’ll learn more about different types of comparisons, how JavaScript makes them, including important peculiarities.

At the end you’ll find a good recipe to avoid “JavaScript quirks”-related issues.

### Boolean is the result
All comparison operators return a boolean value:

 - true – means “yes”, “correct” or “the truth”.
 - false – means “no”, “wrong” or “not the truth”.
For example:
```
alert( 2 > 1 );  // true (correct)
alert( 2 == 1 ); // false (wrong)
alert( 2 != 1 ); // true (correct)
```
A comparison result can be assigned to a variable, just like any value:
```
let result = 5 > 4; // assign the result of the comparison
alert( result ); // true
```
### String comparison
To see whether a string is greater than another, JavaScript uses the so-called “dictionary” or “lexicographical” order.

In other words, strings are compared letter-by-letter.

For example:
```
alert( 'Z' > 'A' ); // true
alert( 'Glow' > 'Glee' ); // true
alert( 'Bee' > 'Be' ); // true
```
The algorithm to compare two strings is simple:

1. Compare the first character of both strings.
2. If the first character from the first string is greater (or less) than the other string’s, then the first string is greater (or less) than the second. We’re done.
3. Otherwise, if both strings’ first characters are the same, compare the second characters the same way.
4. Repeat until the end of either string.
5. If both strings end at the same length, then they are equal. Otherwise, the longer string is greater.

In the first example above, the comparison 'Z' > 'A' gets to a result at the first step.

The second comparison 'Glow' and 'Glee' needs more steps as strings are compared character-by-character:

1. G is the same as G.
2. l is the same as l.
3. o is greater than e. Stop here. The first string is greater.

#### Not a real dictionary, but Unicode order
The comparison algorithm given above is roughly equivalent to the one used in dictionaries or phone 
books, but it’s not exactly the same.

For instance, case matters. A capital letter "A" is not equal to the lowercase "a". Which one is greater? 
The lowercase "a". Why? Because the lowercase character has a greater index in the internal encoding table 
JavaScript uses (Unicode). We’ll get back to specific details and consequences of this in the chapter Strings.

### Comparison of different types
When comparing values of different types, JavaScript converts the values to numbers.

For example:
```
alert( '2' > 1 ); // true, string '2' becomes a number 2
alert( '01' == 1 ); // true, string '01' becomes a number 1
```
For boolean values, true becomes 1 and false becomes 0.

For example:
```
alert( true == 1 ); // true
alert( false == 0 ); // true
```
#### A funny consequence
It is possible that at the same time:

  - Two values are equal.
  - One of them is true as a boolean and the other one is false as a boolean.

For example:
```
let a = 0;
alert( Boolean(a) ); // false
let b = "0";
alert( Boolean(b) ); // true
alert(a == b); // true!
```
From JavaScript’s standpoint, this result is quite normal. An equality check converts 
values using the numeric conversion (hence "0" becomes 0), while the explicit Boolean 
conversion uses another set of rules.

#### Strict equality
A regular equality check == has a problem. It cannot differentiate 0 from false:
```
alert( 0 == false ); // true
```
The same thing happens with an empty string:
```
alert( '' == false ); // true
```
This happens because operands of different types are converted to numbers by the equality operator ==. An 
empty string, just like false, becomes a zero.

What to do if we’d like to differentiate 0 from false?

A strict equality operator === checks the equality without type conversion.

In other words, if a and b are of different types, then a === b immediately returns false without an 
attempt to convert them.

Let’s try it:
```
alert( 0 === false ); // false, because the types are different
```
There is also a “strict non-equality” operator !== analogous to !=.

The strict equality operator is a bit longer to write, but makes it obvious what’s going on and 
leaves less room for errors.

#### Comparison with null and undefined
There’s a non-intuitive behavior when null or undefined are compared to other values.

For a strict equality check ===
These values are different, because each of them is a different type.
```
alert( null === undefined ); // false
```
For a non-strict check ==
There’s a special rule. These two are a “sweet couple”: they equal each other (in the sense of ==), but 
not any other value.
```
alert( null == undefined ); // true
```
For maths and other comparisons < > <= >=
null/undefined are converted to numbers: null becomes 0, while undefined becomes NaN.

Now let’s see some funny things that happen when we apply these rules. And, what’s more important, 
how to not fall into a trap with them.

#### Strange result: null vs 0
Let’s compare null with a zero:
```
alert( null > 0 );  // (1) false
alert( null == 0 ); // (2) false
alert( null >= 0 ); // (3) true
```
Mathematically, that’s strange. The last result states that “null is greater than or equal to zero”, 
so in one of the comparisons above it must be true, but they are both false.

The reason is that an equality check == and comparisons > < >= <= work differently. Comparisons convert 
null to a number, treating it as 0. That’s why (3) null >= 0 is true and (1) null > 0 is false.

On the other hand, the equality check == for undefined and null is defined such that, without any conversions, 
they equal each other and don’t equal anything else. That’s why (2) null == 0 is false.

#### An incomparable undefined
The value undefined shouldn’t be compared to other values:
```
alert( undefined > 0 ); // false (1)
alert( undefined < 0 ); // false (2)
alert( undefined == 0 ); // false (3)
```
Why does it dislike zero so much? Always false!

We get these results because:

 - Comparisons (1) and (2) return false because undefined gets converted to NaN and NaN is a special numeric
   value which returns false for all comparisons.
 - The equality check (3) returns false because undefined only equals null, undefined, and no other value.

#### Avoid problems
Why did we go over these examples? Should we remember these peculiarities all the time? Well, not really. 
Actually, these tricky things will gradually become familiar over time, but there’s a solid way to avoid 
problems with them:

 - Treat any comparison with undefined/null except the strict equality === with exceptional care.
 - Don’t use comparisons >= > < <= with a variable which may be null/undefined, unless you’re really sure
   of what you’re doing. If a variable can have these values, check for them separately.

### Summary
 - Comparison operators return a boolean value.
 - Strings are compared letter-by-letter in the “dictionary” order.
 - When values of different types are compared, they get converted to numbers (with the exclusion of a
   strict equality check).
 - The values null and undefined are equal == to themselves and each other, but do not equal any other value.
 - Be careful when using comparisons like > or < with variables that can occasionally be null/undefined.
   Checking for null/undefined separately is a good idea.

### Comparisons
What will be the result for these expressions?
```
5 > 4
"apple" > "pineapple"
"2" > "12"
undefined == null
undefined === null
null == "\n0\n"
null === +"\n0\n"
```
solution
```
5 > 4 → true
"apple" > "pineapple" → false
"2" > "12" → true
undefined == null → true
undefined === null → false
null == "\n0\n" → false
null === +"\n0\n" → false
```
Some of the reasons:

1. Obviously, true.
2. Dictionary comparison, hence false. "a" is smaller than "p".
3. Again, dictionary comparison, first char "2" is greater than the first char "1".
4. Values null and undefined equal each other only.
5. Strict equality is strict. Different types from both sides lead to false.
6. Similar to (4), null only equals undefined.
7. Strict equality of different types.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Conditional branching: if, '?'
Sometimes, we need to perform different actions based on different conditions.

To do that, we can use the if statement and the conditional operator ?, that’s also called a “question mark” operator.

### The “if” statement
The if(...) statement evaluates a condition in parentheses and, if the result is true, executes a block of code.

For example:
```
let year = prompt('In which year was ECMAScript-2015 specification published?', '');
if (year == 2015) alert( 'You are right!' );
```
In the example above, the condition is a simple equality check (year == 2015), but it can be much more complex.

If we want to execute more than one statement, we have to wrap our code block inside curly braces:
```
if (year == 2015) {
  alert( "That's correct!" );
  alert( "You're so smart!" );
}
```
We recommend wrapping your code block with curly braces {} every time you use an if statement, even if 
there is only one statement to execute. Doing so improves readability.

### Boolean conversion
The if (…) statement evaluates the expression in its parentheses and converts the result to a boolean.

Let’s recall the conversion rules from the chapter Type Conversions:

 - A number 0, an empty string "", null, undefined, and NaN all become false. Because of that they are 
called “falsy” values.
 - Other values become true, so they are called “truthy”.
So, the code under this condition would never execute:
```
if (0) { // 0 is falsy
  ...
}
```
…and inside this condition – it always will:
```
if (1) { // 1 is truthy
  ...
}
```
We can also pass a pre-evaluated boolean value to if, like this:
```
let cond = (year == 2015); // equality evaluates to true or false
if (cond) {
  ...
}
```
### The “else” clause
The if statement may contain an optional else block. It executes when the condition is falsy.

For example:
```
let year = prompt('In which year was the ECMAScript-2015 specification published?', '');
if (year == 2015) {
  alert( 'You guessed it right!' );
} else {
  alert( 'How can you be so wrong?' ); // any value except 2015
}
```
### Several conditions: “else if”
Sometimes, we’d like to test several variants of a condition. The else if clause lets us do that.

For example:

let year = prompt('In which year was the ECMAScript-2015 specification published?', '');
```
if (year < 2015) {
  alert( 'Too early...' );
} else if (year > 2015) {
  alert( 'Too late' );
} else {
  alert( 'Exactly!' );
}
```
In the code above, JavaScript first checks year < 2015. If that is falsy, it goes to the next condition 
year > 2015. If that is also falsy, it shows the last alert.

There can be more else if blocks. The final else is optional.

### Conditional operator ‘?’
Sometimes, we need to assign a variable depending on a condition.

For instance:
```
let accessAllowed;
let age = prompt('How old are you?', '');
if (age > 18) {
  accessAllowed = true;
} else {
  accessAllowed = false;
}
alert(accessAllowed);
```
The so-called “conditional” or “question mark” operator lets us do that in a shorter and simpler way.

The operator is represented by a question mark ?. Sometimes it’s called “ternary”, because the 
operator has three operands. It is actually the one and only operator in JavaScript which has that many.

The syntax is:
```
let result = condition ? value1 : value2;
```
The condition is evaluated: if it’s truthy then value1 is returned, otherwise – value2.

For example:
```
let accessAllowed = (age > 18) ? true : false;
```
Technically, we can omit the parentheses around age > 18. The question mark operator has a low precedence, 
so it executes after the comparison >.

This example will do the same thing as the previous one:
```
// the comparison operator "age > 18" executes first anyway
// (no need to wrap it into parentheses)
let accessAllowed = age > 18 ? true : false;
```
But parentheses make the code more readable, so we recommend using them.

Please note:
In the example above, you can avoid using the question mark operator because the comparison itself returns 
true/false:
```
// the same
let accessAllowed = age > 18;
```
### Multiple ‘?’
A sequence of question mark operators ? can return a value that depends on more than one condition.

For instance:
```
let age = prompt('age?', 18);
let message = (age < 3) ? 'Hi, baby!' :
  (age < 18) ? 'Hello!' :
  (age < 100) ? 'Greetings!' :
  'What an unusual age!';

alert( message );
```
It may be difficult at first to grasp what’s going on. But after a closer look, we can see that it’s 
just an ordinary sequence of tests:

1. The first question mark checks whether age < 3.
2. If true – it returns 'Hi, baby!'. Otherwise, it continues to the expression after the colon “:”, checking
   age < 18.
4. If that’s true – it returns 'Hello!'. Otherwise, it continues to the expression after the next colon “:”,
   checking age < 100.
5. If that’s true – it returns 'Greetings!'. Otherwise, it continues to the expression after the last colon “:”, returning 'What an unusual age!'.

Here’s how this looks using if..else:
```
if (age < 3) {
  message = 'Hi, baby!';
} else if (age < 18) {
  message = 'Hello!';
} else if (age < 100) {
  message = 'Greetings!';
} else {
  message = 'What an unusual age!';
}
```
### Non-traditional use of ‘?’
Sometimes the question mark ? is used as a replacement for if:
```
let company = prompt('Which company created JavaScript?', '');
(company == 'Netscape') ?
   alert('Right!') : alert('Wrong.');
```
Depending on the condition company == 'Netscape', either the first or the second expression after the ? gets 
executed and shows an alert.

We don’t assign a result to a variable here. Instead, we execute different code depending on the condition.

It’s not recommended to use the question mark operator in this way.

The notation is shorter than the equivalent if statement, which appeals to some programmers. But it is less readable.

Here is the same code using if for comparison:
```
let company = prompt('Which company created JavaScript?', '');
if (company == 'Netscape') {
  alert('Right!');
} else {
  alert('Wrong.');
}
```
Our eyes scan the code vertically. Code blocks which span several lines are easier to understand 
than a long, horizontal instruction set.

The purpose of the question mark operator ? is to return one value or another depending on its condition. Please use it for exactly that. Use if when you need to execute different branches of code.

Tasks
if (a string with zero)
importance: 5
Will alert be shown?
```
if ("0") {
  alert( 'Hello' );
}
```
### The name of JavaScript
Using the if..else construct, write the code which asks: ‘What is the “official” name of JavaScript?’

If the visitor enters “ECMAScript”, then output “Right!”, otherwise – output: “You don’t know? ECMAScript!”
```
<!DOCTYPE html>
<html>
<body>
  <script>
    'use strict';

    let value = prompt('What is the "official" name of JavaScript?', '');

    if (value == 'ECMAScript') {
      alert('Right!');
    } else {
      alert("You don't know? ECMAScript!");
    }
  </script>

</body>
</html>
```
#### Show the sign
importance: 2
Using if..else, write the code which gets a number via prompt and then shows in alert:

1, if the value is greater than zero,
-1, if less than zero,
0, if equals zero.
In this task we assume that the input is always a number.

solution
```
let value = prompt('Type a number', 0);

if (value > 0) {
  alert( 1 );
} else if (value < 0) {
  alert( -1 );
} else {
  alert( 0 );
}
```
#### Rewrite 'if' into '?'
Rewrite this if using the conditional operator '?':
```
let result;

if (a + b < 4) {
  result = 'Below';
} else {
  result = 'Over';
}
```
solution
```
let result = (a + b < 4) ? 'Below' : 'Over';
```
#### Rewrite 'if..else' into '?'
Rewrite if..else using multiple ternary operators '?'.

For readability, it’s recommended to split the code into multiple lines.
```
let message;

if (login == 'Employee') {
  message = 'Hello';
} else if (login == 'Director') {
  message = 'Greetings';
} else if (login == '') {
  message = 'No login';
} else {
  message = '';
}
```
Solution
```
let message = (login == 'Employee') ? 'Hello' :
  (login == 'Director') ? 'Greetings' :
  (login == '') ? 'No login' :
  '';
```

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Logical operators
There are four logical operators in JavaScript: || (OR), && (AND), ! (NOT), ?? (Nullish Coalescing). 
Here we cover the first three, the ?? operator is in the next article.

Although they are called “logical”, they can be applied to values of any type, not only boolean. 
Their result can also be of any type.

Let’s see the details.

### || (OR)
The “OR” operator is represented with two vertical line symbols:
```
result = a || b;
```
In classical programming, the logical OR is meant to manipulate boolean values only. If any of 
its arguments are true, it returns true, otherwise it returns false.

In JavaScript, the operator is a little bit trickier and more powerful. But first, let’s see what 
happens with boolean values.

There are four possible logical combinations:
```
alert( true || true );   // true
alert( false || true );  // true
alert( true || false );  // true
alert( false || false ); // false
```
As we can see, the result is always true except for the case when both operands are false.

If an operand is not a boolean, it’s converted to a boolean for the evaluation.

For instance, the number 1 is treated as true, the number 0 as false:
```
if (1 || 0) { // works just like if( true || false )
  alert( 'truthy!' );
}
```
Most of the time, OR || is used in an if statement to test if any of the given conditions is true.

For example:
```
let hour = 9;

if (hour < 10 || hour > 18) {
  alert( 'The office is closed.' );
}
```
We can pass more conditions:
```
let hour = 12;
let isWeekend = true;

if (hour < 10 || hour > 18 || isWeekend) {
  alert( 'The office is closed.' ); // it is the weekend
}
```
#### OR "||" finds the first truthy value
The logic described above is somewhat classical. Now, let’s bring in the “extra” features of JavaScript.

The extended algorithm works as follows.

Given multiple OR’ed values:

result = value1 || value2 || value3;
The OR || operator does the following:

Evaluates operands from left to right.
For each operand, converts it to boolean. If the result is true, stops and returns the original value of that operand.
If all operands have been evaluated (i.e. all were false), returns the last operand.
A value is returned in its original form, without the conversion.

In other words, a chain of OR || returns the first truthy value or the last one if no truthy value is found.

For instance:
```
alert( 1 || 0 ); // 1 (1 is truthy)

alert( null || 1 ); // 1 (1 is the first truthy value)
alert( null || 0 || 1 ); // 1 (the first truthy value)

alert( undefined || null || 0 ); // 0 (all falsy, returns the last value)
```
This leads to some interesting usage compared to a “pure, classical, boolean-only OR”.

Getting the first truthy value from a list of variables or expressions.

For instance, we have firstName, lastName and nickName variables, all optional (i.e. can be undefined or have falsy values).

Let’s use OR || to choose the one that has the data and show it (or "Anonymous" if nothing set):
```
let firstName = "";
let lastName = "";
let nickName = "SuperCoder";

alert( firstName || lastName || nickName || "Anonymous"); // SuperCoder
```
If all variables were falsy, "Anonymous" would show up.

#### Short-circuit evaluation.

Another feature of OR || operator is the so-called “short-circuit” evaluation.

It means that || processes its arguments until the first truthy value is reached, and then the value 
is returned immediately, without even touching the other argument.

The importance of this feature becomes obvious if an operand isn’t just a value, but an expression 
with a side effect, such as a variable assignment or a function call.

In the example below, only the second message is printed:
```
true || alert("not printed");
false || alert("printed");
```
In the first line, the OR || operator stops the evaluation immediately upon seeing true, so the alert isn’t run.

Sometimes, people use this feature to execute commands only if the condition on the left part is falsy.

#### && (AND)

The AND operator is represented with two ampersands &&:
```
result = a && b;
```
In classical programming, AND returns true if both operands are truthy and false otherwise:
```
alert( true && true );   // true
alert( false && true );  // false
alert( true && false );  // false
alert( false && false ); // false
```
An example with if:
```
let hour = 12;
let minute = 30;

if (hour == 12 && minute == 30) {
  alert( 'The time is 12:30' );
}
```
Just as with OR, any value is allowed as an operand of AND:
```
if (1 && 0) { // evaluated as true && false
  alert( "won't work, because the result is falsy" );
}
```
#### AND “&&” finds the first falsy value
Given multiple AND’ed values:
```
result = value1 && value2 && value3;
```
The AND && operator does the following:

Evaluates operands from left to right.
For each operand, converts it to a boolean. If the result is false, stops and returns the original value of that operand.
If all operands have been evaluated (i.e. all were truthy), returns the last operand.
In other words, AND returns the first falsy value or the last value if none were found.

The rules above are similar to OR. The difference is that AND returns the first falsy value while OR returns the first truthy one.

Examples:
```
// if the first operand is truthy,
// AND returns the second operand:
alert( 1 && 0 ); // 0
alert( 1 && 5 ); // 5

// if the first operand is falsy,
// AND returns it. The second operand is ignored
alert( null && 5 ); // null
alert( 0 && "no matter what" ); // 0
```
We can also pass several values in a row. See how the first falsy one is returned:
```
alert( 1 && 2 && null && 3 ); // null
```
When all values are truthy, the last value is returned:
```
alert( 1 && 2 && 3 ); // 3, the last one
```
#### Precedence of AND && is higher than OR ||
The precedence of AND && operator is higher than OR ||.

So the code a && b || c && d is essentially the same as if the && expressions were in parentheses: (a && b) || (c && d).

Don’t replace if with || or &&
Sometimes, people use the AND && operator as a “shorter way to write if”.

For instance:
```
let x = 1;

(x > 0) && alert( 'Greater than zero!' );
```
The action in the right part of && would execute only if the evaluation reaches it. That is, only if (x > 0) is true.

So we basically have an analogue for:
```
let x = 1;

if (x > 0) alert( 'Greater than zero!' );
```
Although, the variant with && appears shorter, if is more obvious and tends to be a little bit more readable. So we recommend using every construct for its purpose: use if if we want if and use && if we want AND.

#### ! (NOT)
The boolean NOT operator is represented with an exclamation sign !.

The syntax is pretty simple:
```
result = !value;
```

The operator accepts a single argument and does the following:

Converts the operand to boolean type: true/false.
Returns the inverse value.
For instance:
```
alert( !true ); // false
alert( !0 ); // true
```
#### A double NOT !! is sometimes used for converting a value to boolean type:
```
alert( !!"non-empty string" ); // true
alert( !!null ); // false
```
That is, the first NOT converts the value to boolean and returns the inverse, and the second NOT 
inverses it again. In the end, we have a plain value-to-boolean conversion.

There’s a little more verbose way to do the same thing – a built-in Boolean function:
```
alert( Boolean("non-empty string") ); // true
alert( Boolean(null) ); // false
```
The precedence of NOT ! is the highest of all logical operators, so it always executes first, before && or ||.

Tasks
What's the result of OR?
What is the code below going to output?
```
alert( null || 2 || undefined );
```

solution
What's the result of OR'ed alerts?
What will the code below output?
```
alert( alert(1) || 2 || alert(3) );
```
solution
What is the result of AND?
What is this code going to show?
```
alert( 1 && null && 2 );
```
solution
What is the result of AND'ed alerts?
What will this code show?
```
alert( alert(1) && alert(2) );
```
solution
The result of OR AND OR
What will the result be?
```
alert( null || 2 && 3 || 4 );
```
solution
Check the range between
Write an if condition to check that age is between 14 and 90 inclusively.

“Inclusively” means that age can reach the edges 14 or 90.

solution
#### Check the range outside
Write an if condition to check that age is NOT between 14 and 90 inclusively.

Create two variants: the first one using NOT !, the second one – without it.

solution
#### A question about "if"
Which of these alerts are going to execute?

What will the results of the expressions be inside if(...)?
```
if (-1 || 0) alert( 'first' );
if (-1 && 0) alert( 'second' );
if (null || -1 && 1) alert( 'third' );
```
solution

Check the login
Write the code which asks for a login with prompt.

If the visitor enters "Admin", then prompt for a password, if the input is an empty line or Esc – show “Canceled”, if it’s another string – then show “I don’t know you”.

The password is checked as follows:

If it equals “TheMaster”, then show “Welcome!”,
Another string – show “Wrong password”,
For an empty string or cancelled input, show “Canceled”

<!-- image here -->

Please use nested if blocks. Mind the overall readability of the code.

Hint: passing an empty input to a prompt returns an empty string ''. Pressing ESC during a prompt returns null.

Run the demo

solution
```
let userName = prompt("Who's there?", '');

if (userName === 'Admin') {

  let pass = prompt('Password?', '');

  if (pass === 'TheMaster') {
    alert( 'Welcome!' );
  } else if (pass === '' || pass === null) {
    alert( 'Canceled' );
  } else {
    alert( 'Wrong password' );
  }

} else if (userName === '' || userName === null) {
  alert( 'Canceled' );
} else {
  alert( "I don't know you" );
}
```
Note the vertical indents inside the if blocks. They are technically not required, but make the code more readable.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Nullish coalescing operator '??'
A recent addition
This is a recent addition to the language. Old browsers may need polyfills.

The nullish coalescing operator is written as two question marks ??.

As it treats null and undefined similarly, we’ll use a special term here, in this article. For brevity, 
we’ll say that a value is “defined” when it’s neither null nor undefined.

The result of a ?? b is:

  - if a is defined, then a,
  - if a isn’t defined, then b.
  
In other words, ?? returns the first argument if it’s not null/undefined. Otherwise, the second one.

The nullish coalescing operator isn’t anything completely new. It’s just a nice syntax to get the first “defined” value of the two.

We can rewrite result = a ?? b using the operators that we already know, like this:
```
result = (a !== null && a !== undefined) ? a : b;
```
Now it should be absolutely clear what ?? does. Let’s see where it helps.

The common use case for ?? is to provide a default value.

For example, here we show user if its value isn’t null/undefined, otherwise Anonymous:
```
let user;
alert(user ?? "Anonymous"); // Anonymous (user is undefined)
```
Here’s the example with user assigned to a name:
```
let user = "John";
alert(user ?? "Anonymous"); // John (user is not null/undefined)
```
We can also use a sequence of ?? to select the first value from a list that isn’t null/undefined.
Let’s say we have a user’s data in variables firstName, lastName or nickName. All of them may be not defined, if the user decided not to fill in the corresponding values.

We’d like to display the user name using one of these variables, or show “Anonymous” if all of them are null/undefined.

Let’s use the ?? operator for that:
```
let firstName = null;
let lastName = null;
let nickName = "Supercoder";
// shows the first defined value:
alert(firstName ?? lastName ?? nickName ?? "Anonymous"); // Supercoder
```

### Comparison with ||
The OR || operator can be used in the same way as ??, as it was described in the previous chapter.

For example, in the code above we could replace ?? with || and still get the same result:
```
let firstName = null;
let lastName = null;
let nickName = "Supercoder";
// shows the first truthy value:
alert(firstName || lastName || nickName || "Anonymous"); // Supercoder
```
Historically, the OR || operator was there first. It’s been there since the beginning of JavaScript, 
so developers were using it for such purposes for a long time.

On the other hand, the nullish coalescing operator ?? was added to JavaScript only recently, and the 
reason for that was that people weren’t quite happy with ||.

The important difference between them is that:

  - || returns the first truthy value.
  - ?? returns the first defined value.

In other words, || doesn’t distinguish between false, 0, an empty string "" and null/undefined. They 
are all the same – falsy values. If any of these is the first argument of ||, then we’ll get the 
second argument as the result.

In practice though, we may want to use default value only when the variable is null/undefined. 
That is, when the value is really unknown/not set.

For example, consider this:
```
let height = 0;
alert(height || 100); // 100
alert(height ?? 100); // 0
```
  - The height || 100 checks height for being a falsy value, and it’s 0, falsy indeed.
    - so the result of || is the second argument, 100.
  - The height ?? 100 checks height for being null/undefined, and it’s not,
    - so the result is height “as is”, that is 0.

In practice, the zero height is often a valid value, that shouldn’t be replaced with the default. So ?? does just the right thing.

### Precedence
The precedence of the ?? operator is the same as ||. They both equal 3 in the MDN table.

That means that, just like ||, the nullish coalescing operator ?? is evaluated before = and ?, but after most other operations, such as +, *.

So we may need to add parentheses in expressions like this:
```
let height = null;
let width = null;
// important: use parentheses
let area = (height ?? 100) * (width ?? 50);
alert(area); // 5000
```

Otherwise, if we omit parentheses, then as * has the higher precedence than ??, it would execute first, 
leading to incorrect results.
```
// without parentheses
let area = height ?? 100 * width ?? 50;
// ...works this way (not what we want):
let area = height ?? (100 * width) ?? 50;
```

### Using ?? with && or ||
Due to safety reasons, JavaScript forbids using ?? together with && and || operators, unless the 
precedence is explicitly specified with parentheses.

The code below triggers a syntax error:
```
let x = 1 && 2 ?? 3; // Syntax error
```
The limitation is surely debatable, it was added to the language specification with the purpose to 
avoid programming mistakes, when people start to switch from || to ??.

Use explicit parentheses to work around it:
```
let x = (1 && 2) ?? 3; // Works
alert(x); // 2
```

### Summary
  - The nullish coalescing operator ?? provides a short way to choose the first “defined” value from a list.

It’s used to assign default values to variables:
```
// set height=100, if height is null or undefined
height = height ?? 100;
```
  - The operator ?? has a very low precedence, only a bit higher than ? and =, so consider adding parentheses 
    when using it in an expression.

  - It’s forbidden to use it with || or && without explicit parentheses.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Loops: while and for
We often need to repeat actions.

For example, outputting goods from a list one after another or just running the same code for each number from 1 to 10.

Loops are a way to repeat the same code multiple times.

### The for…of and for…in loops
A small announcement for advanced readers.

This article covers only basic loops: while, do..while and for(..;..;..).

If you came to this article searching for other types of loops, here are the pointers:

  - See for…in to loop over object properties.
  - See for…of and iterables for looping over arrays and iterable objects.
Otherwise, please read on.

### The “while” loop
The while loop has the following syntax:
```
while (condition) {
  // code
  // so-called "loop body"
}
```
While the condition is truthy, the code from the loop body is executed.

For instance, the loop below outputs i while i < 3:
```
let i = 0;
while (i < 3) { // shows 0, then 1, then 2
  alert( i );
  i++;
}
```
A single execution of the loop body is called an iteration. The loop in the example above makes three iterations.

If i++ was missing from the example above, the loop would repeat (in theory) forever. In practice, the 
browser provides ways to stop such loops, and in server-side JavaScript, we can kill the process.

Any expression or variable can be a loop condition, not just comparisons: the condition is evaluated 
and converted to a boolean by while.

For instance, a shorter way to write while (i != 0) is while (i):
```
let i = 3;
while (i) { // when i becomes 0, the condition becomes falsy, and the loop stops
  alert( i );
  i--;
}
```

#### Curly braces are not required for a single-line body
If the loop body has a single statement, we can omit the curly braces {…}:
```
let i = 3;
while (i) alert(i--);
```

### The “do…while” loop
The condition check can be moved below the loop body using the do..while syntax:
```
do {
  // loop body
} while (condition);
```
The loop will first execute the body, then check the condition, and, while it’s truthy, execute it again and again.

For example:
```
let i = 0;
do {
  alert( i );
  i++;
} while (i < 3);
```
This form of syntax should only be used when you want the body of the loop to execute at least once regardless of the condition being truthy. Usually, the other form is preferred: while(…) {…}.

### The “for” loop
The for loop is more complex, but it’s also the most commonly used loop.

It looks like this:
```
for (begin; condition; step) {
  // ... loop body ...
}
```
Let’s learn the meaning of these parts by example. The loop below runs alert(i) for i from 0 up to (but not including) 3:
```
for (let i = 0; i < 3; i++) { // shows 0, then 1, then 2
  alert(i);
}
```
Let’s examine the for statement part-by-part:


part
| begin | let i = 0 | Executes once upon entering the loop. |
| condition | i < 3	| Checked before every loop iteration. If false, the loop stops. |
| body | alert(i) | Runs again and again while the condition is truthy. |
| step | i++ | Executes after the body on each iteration. |

The general loop algorithm works like this:
```
Run begin
→ (if condition → run body and run step)
→ (if condition → run body and run step)
→ (if condition → run body and run step)
→ ...
```
That is, begin executes once, and then it iterates: after each condition test, body and step are executed.

If you are new to loops, it could help to go back to the example and reproduce how it runs step-by-step on a piece of paper.

Here’s exactly what happens in our case:
```
// for (let i = 0; i < 3; i++) alert(i)

// run begin
let i = 0
// if condition → run body and run step
if (i < 3) { alert(i); i++ }
// if condition → run body and run step
if (i < 3) { alert(i); i++ }
// if condition → run body and run step
if (i < 3) { alert(i); i++ }
// ...finish, because now i == 3
```
Inline variable declaration
Here, the “counter” variable i is declared right in the loop. This is called an “inline” variable declaration. Such variables are visible only inside the loop.
```
for (let i = 0; i < 3; i++) {
  alert(i); // 0, 1, 2
}
alert(i); // error, no such variable
```
Instead of defining a variable, we could use an existing one:
```
let i = 0;

for (i = 0; i < 3; i++) { // use an existing variable
  alert(i); // 0, 1, 2
}

alert(i); // 3, visible, because declared outside of the loop
```

#### Skipping parts
Any part of for can be skipped.

For example, we can omit begin if we don’t need to do anything at the loop start.

Like here:
```
let i = 0; // we have i already declared and assigned

for (; i < 3; i++) { // no need for "begin"
  alert( i ); // 0, 1, 2
}
```
We can also remove the step part:
```
let i = 0;

for (; i < 3;) {
  alert( i++ );
}
```
This makes the loop identical to while (i < 3).

We can actually remove everything, creating an infinite loop:
```
for (;;) {
  // repeats without limits
}
```
Please note that the two for semicolons ; must be present. Otherwise, there would be a syntax error.

### Breaking the loop
Normally, a loop exits when its condition becomes falsy.

But we can force the exit at any time using the special break directive.

For example, the loop below asks the user for a series of numbers, “breaking” when no number is entered:
```
let sum = 0;

while (true) {
  let value = +prompt("Enter a number", '');
  if (!value) break; // (*)
  sum += value;
}
alert( 'Sum: ' + sum );
```
The break directive is activated at the line (*) if the user enters an empty line or cancels the 
input. It stops the loop immediately, passing control to the first line after the loop. Namely, alert.

The combination “infinite loop + break as needed” is great for situations when a loop’s condition 
must be checked not in the beginning or end of the loop, but in the middle or even in several places 
of its body.

### Continue to the next iteration
The continue directive is a “lighter version” of break. It doesn’t stop the whole loop. Instead, it 
stops the current iteration and forces the loop to start a new one (if the condition allows).

We can use it if we’re done with the current iteration and would like to move on to the next one.

The loop below uses continue to output only odd values:
```
for (let i = 0; i < 10; i++) {

  // if true, skip the remaining part of the body
  if (i % 2 == 0) continue;

  alert(i); // 1, then 3, 5, 7, 9
}
```
For even values of i, the continue directive stops executing the body and passes control to the next 
iteration of for (with the next number). So the alert is only called for odd values.

The continue directive helps decrease nesting
A loop that shows odd values could look like this:
```
for (let i = 0; i < 10; i++) {

  if (i % 2) {
    alert( i );
  }
}
```
From a technical point of view, this is identical to the example above. Surely, we can just wrap the 
code in an if block instead of using continue.

But as a side effect, this created one more level of nesting (the alert call inside the curly braces). 
If the code inside of if is longer than a few lines, that may decrease the overall readability.
No break/continue to the right side of ‘?’
Please note that syntax constructs that are not expressions cannot be used with the ternary operator ?. 
In particular, directives such as break/continue aren’t allowed there.

For example, if we take this code:
```
if (i > 5) {
  alert(i);
} else {
  continue;
}
```
…and rewrite it using a question mark:
```
(i > 5) ? alert(i) : continue; // continue isn't allowed here
```
…it stops working: there’s a syntax error.

This is just another reason not to use the question mark operator ? instead of if.
### Labels for break/continue
Sometimes we need to break out from multiple nested loops at once.

For example, in the code below we loop over i and j, prompting for the coordinates (i, j) from (0,0) to (2,2):
```
for (let i = 0; i < 3; i++) {

  for (let j = 0; j < 3; j++) {

    let input = prompt(`Value at coords (${i},${j})`, '');

    // what if we want to exit from here to Done (below)?
  }
}

alert('Done!');
```
We need a way to stop the process if the user cancels the input.

The ordinary break after input would only break the inner loop. That’s not sufficient – labels, 
come to the rescue!

A label is an identifier with a colon before a loop:
```
labelName: for (...) {
  ...
}
```
The break <labelName> statement in the loop below breaks out to the label:
```
outer: for (let i = 0; i < 3; i++) {

  for (let j = 0; j < 3; j++) {

    let input = prompt(`Value at coords (${i},${j})`, '');

    // if an empty string or canceled, then break out of both loops
    if (!input) break outer; // (*)

    // do something with the value...
  }
}

alert('Done!');
```
In the code above, break outer looks upwards for the label named outer and breaks out of that loop.

So the control goes straight from (*) to alert('Done!').

We can also move the label onto a separate line:
```
outer:
for (let i = 0; i < 3; i++) { ... }
```
The continue directive can also be used with a label. In this case, code execution jumps to the next 
iteration of the labeled loop.

Labels do not allow to “jump” anywhere
Labels do not allow us to jump into an arbitrary place in the code.

For example, it is impossible to do this:
```
break label; // jump to the label below (doesn't work)

label: for (...)
```
A break directive must be inside a code block. Technically, any labelled code block will do, e.g.:
```
label: {
  // ...
  break label; // works
  // ...
}
```
…Although, 99.9% of the time break is used inside loops, as we’ve seen in the examples above.

A continue is only possible from inside a loop.
### Summary
We covered 3 types of loops:

  - while – The condition is checked before each iteration.
  - do..while – The condition is checked after each iteration.
  - for (;;) – The condition is checked before each iteration, additional settings available.

To make an “infinite” loop, usually the while(true) construct is used. Such a loop, just like any 
other, can be stopped with the break directive.

If we don’t want to do anything in the current iteration and would like to forward to the next one, 
we can use the continue directive.

break/continue support labels before the loop. A label is the only way for break/continue to escape 
a nested loop to go to an outer one.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## The "switch" statement
A switch statement can replace multiple if checks.

It gives a more descriptive way to compare a value with multiple variants.

### The syntax
The switch has one or more case blocks and an optional default.

It looks like this:
```
switch(x) {
  case 'value1':  // if (x === 'value1')
    ...
    [break]

  case 'value2':  // if (x === 'value2')
    ...
    [break]

  default:
    ...
    [break]
}
```
  - The value of x is checked for a strict equality to the value from the first case (that is, value1) then to the second (value2) and so on.
  - If the equality is found, switch starts to execute the code starting from the corresponding case, until the nearest break (or until the end of switch).
  - If no case is matched then the default code is executed (if it exists).

### An example
An example of switch (the executed code is highlighted):
```
let a = 2 + 2;

switch (a) {
  case 3:
    alert( 'Too small' );
    break;
  case 4:
    alert( 'Exactly!' );
    break;
  case 5:
    alert( 'Too big' );
    break;
  default:
    alert( "I don't know such values" );
}
```
Here the switch starts to compare a from the first case variant that is 3. The match fails.

Then 4. That’s a match, so the execution starts from case 4 until the nearest break.

If there is no break then the execution continues with the next case without any checks.

An example without break:
```
let a = 2 + 2;

switch (a) {
  case 3:
    alert( 'Too small' );
  case 4:
    alert( 'Exactly!' );
  case 5:
    alert( 'Too big' );
  default:
    alert( "I don't know such values" );
}
```
In the example above we’ll see sequential execution of three alerts:
```
alert( 'Exactly!' );
alert( 'Too big' );
alert( "I don't know such values" );
```
Any expression can be a switch/case argument
Both switch and case allow arbitrary expressions.

For example:
```
let a = "1";
let b = 0;

switch (+a) {
  case b + 1:
    alert("this runs, because +a is 1, exactly equals b+1");
    break;

  default:
    alert("this doesn't run");
}
```
Here +a gives 1, that’s compared with b + 1 in case, and the corresponding code is executed.

### Grouping of “case”
Several variants of case which share the same code can be grouped.

For example, if we want the same code to run for case 3 and case 5:
```
let a = 3;

switch (a) {
  case 4:
    alert('Right!');
    break;

  case 3: // (*) grouped two cases
  case 5:
    alert('Wrong!');
    alert("Why don't you take a math class?");
    break;

  default:
    alert('The result is strange. Really.');
}
```
Now both 3 and 5 show the same message.

The ability to “group” cases is a side effect of how switch/case works without break. Here the execution of case 3 starts from the line (*) and goes through case 5, because there’s no break.

### Type matters
Let’s emphasize that the equality check is always strict. The values must be of the same type to match.

For example, let’s consider the code:
```
let arg = prompt("Enter a value?");
switch (arg) {
  case '0':
  case '1':
    alert( 'One or zero' );
    break;

  case '2':
    alert( 'Two' );
    break;

  case 3:
    alert( 'Never executes!' );
    break;
  default:
    alert( 'An unknown value' );
}
```
1. For 0, 1, the first alert runs.
2. For 2 the second alert runs.
3. But for 3, the result of the prompt is a string "3", which is not strictly equal === to the number 3. 
   So we’ve got a dead code in case 3! The default variant will execute.

#### Tasks
Rewrite the "switch" into an "if"
Write the code using if..else which would correspond to the following switch:
```
switch (browser) {
  case 'Edge':
    alert( "You've got the Edge!" );
    break;

  case 'Chrome':
  case 'Firefox':
  case 'Safari':
  case 'Opera':
    alert( 'Okay we support these browsers too' );
    break;

  default:
    alert( 'We hope that this page looks ok!' );
}
```
solution
To precisely match the functionality of switch, the if must use a strict comparison '==='.

For given strings though, a simple '==' works too.
```
if(browser == 'Edge') {
  alert("You've got the Edge!");
} else if (browser == 'Chrome'
 || browser == 'Firefox'
 || browser == 'Safari'
 || browser == 'Opera') {
  alert( 'Okay we support these browsers too' );
} else {
  alert( 'We hope that this page looks ok!' );
}
```
Please note: the construct browser == 'Chrome' || browser == 'Firefox' … is split into multiple lines for better readability.

But the switch construct is still cleaner and more descriptive.
#### Rewrite "if" into "switch"
Rewrite the code below using a single switch statement:
```
let a = +prompt('a?', '');

if (a == 0) {
  alert( 0 );
}
if (a == 1) {
  alert( 1 );
}

if (a == 2 || a == 3) {
  alert( '2,3' );
}
```
#### solution
The first two checks turn into two case. The third check is split into two cases:
```
let a = +prompt('a?', '');

switch (a) {
  case 0:
    alert( 0 );
    break;

  case 1:
    alert( 1 );
    break;

  case 2:
  case 3:
    alert( '2,3' );
    break;
}
```
Please note: the break at the bottom is not required. But we put it to make the code future-proof.

In the future, there is a chance that we’d want to add one more case, for example case 4. And if 
we forget to add a break before it, at the end of case 3, there will be an error. So that’s a kind of self-insurance.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Functions
Quite often we need to perform a similar action in many places of the script.

For example, we need to show a nice-looking message when a visitor logs in, logs out and maybe somewhere else.

Functions are the main “building blocks” of the program. They allow the code to be called many times without repetition.

We’ve already seen examples of built-in functions, like alert(message), prompt(message, default) and confirm(question). But we can create functions of our own as well.

### Function Declaration
To create a function we can use a function declaration.

It looks like this:
```
function showMessage() {
  alert( 'Hello everyone!' );
}
```
The function keyword goes first, then goes the name of the function, then a list of parameters 
between the parentheses (comma-separated, empty in the example above, we’ll see examples later) 
and finally the code of the function, also named “the function body”, between curly braces.
```
function name(parameter1, parameter2, ... parameterN) {
 // body
}
```
Our new function can be called by its name: showMessage().

For instance:
```
function showMessage() {
  alert( 'Hello everyone!' );
}
showMessage();
showMessage();
```
The call showMessage() executes the code of the function. Here we will see the message two times.

This example clearly demonstrates one of the main purposes of functions: to avoid code duplication.

If we ever need to change the message or the way it is shown, it’s enough to modify the code in one place: the function which outputs it.

### Local variables
A variable declared inside a function is only visible inside that function.

#### For example:
```
function showMessage() {
  let message = "Hello, I'm JavaScript!"; // local variable

  alert( message );
}

showMessage(); // Hello, I'm JavaScript!

alert( message ); // <-- Error! The variable is local to the function
```

### Outer variables
A function can access an outer variable as well, for example:
```
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  alert(message);
}

showMessage(); // Hello, John
```
The function has full access to the outer variable. It can modify it as well.

For instance:
```
let userName = 'John';

function showMessage() {
  userName = "Bob"; // (1) changed the outer variable

  let message = 'Hello, ' + userName;
  alert(message);
}

alert( userName ); // John before the function call

showMessage();

alert( userName ); // Bob, the value was modified by the function
```
The outer variable is only used if there’s no local one.

If a same-named variable is declared inside the function then it shadows the outer one. For instance, in the code below the function uses the local userName. The outer one is ignored:
```
let userName = 'John';

function showMessage() {
  let userName = "Bob"; // declare a local variable

  let message = 'Hello, ' + userName; // Bob
  alert(message);
}

// the function will create and use its own userName
showMessage();

alert( userName ); // John, unchanged, the function did not access the outer variable
```
Global variables
Variables declared outside of any function, such as the outer userName in the code above, are called global.

Global variables are visible from any function (unless shadowed by locals).

It’s a good practice to minimize the use of global variables. Modern code has few or no globals. 
Most variables reside in their functions. Sometimes though, they can be useful to store project-level data.
Parameters
We can pass arbitrary data to functions using parameters.

In the example below, the function has two parameters: from and text.
```
function showMessage(from, text) { // parameters: from, text
  alert(from + ': ' + text);
}

showMessage('Ann', 'Hello!'); // Ann: Hello! (*)
showMessage('Ann', "What's up?"); // Ann: What's up? (**)
```
When the function is called in lines (*) and (**), the given values are copied to local variables from and text. Then the function uses them.

Here’s one more example: we have a variable from and pass it to the function. Please note: the function changes from, but the change is not seen outside, because a function always gets a copy of the value:
```
function showMessage(from, text) {

  from = '*' + from + '*'; // make "from" look nicer

  alert( from + ': ' + text );
}

let from = "Ann";

showMessage(from, "Hello"); // *Ann*: Hello

// the value of "from" is the same, the function modified a local copy
alert( from ); // Ann
```
When a value is passed as a function parameter, it’s also called an argument.

In other words, to put these terms straight:

 - A parameter is the variable listed inside the parentheses in the function declaration (it’s a declaration time term).
 - An argument is the value that is passed to the function when it is called (it’s a call time term).


We declare functions listing their parameters, then call them passing arguments.

In the example above, one might say: “the function showMessage is declared with two parameters, then called with two arguments: from and "Hello"”.

### Default values
If a function is called, but an argument is not provided, then the corresponding value becomes undefined.

For instance, the aforementioned function showMessage(from, text) can be called with a single argument:
```
showMessage("Ann");
```
That’s not an error. Such a call would output "*Ann*: undefined". As the value for text isn’t passed, it becomes undefined.

We can specify the so-called “default” (to use if omitted) value for a parameter in the function declaration, using =:
```
function showMessage(from, text = "no text given") {
  alert( from + ": " + text );
}

showMessage("Ann"); // Ann: no text given
```
Now if the text parameter is not passed, it will get the value "no text given".

The default value also jumps in if the parameter exists, but strictly equals undefined, like this:
```
showMessage("Ann", undefined); // Ann: no text given
```
Here "no text given" is a string, but it can be a more complex expression, which is only evaluated and assigned if the parameter is missing. So, this is also possible:

function showMessage(from, text = anotherFunction()) {
  // anotherFunction() only executed if no text given
  // its result becomes the value of text
}
Evaluation of default parameters
In JavaScript, a default parameter is evaluated every time the function is called without the respective parameter.

In the example above, anotherFunction() isn’t called at all, if the text parameter is provided.

On the other hand, it’s independently called every time when text is missing.

Default parameters in old JavaScript code
Several years ago, JavaScript didn’t support the syntax for default parameters. So people used other ways to specify them.

Nowadays, we can come across them in old scripts.

For example, an explicit check for undefined:
```
function showMessage(from, text) {
  if (text === undefined) {
    text = 'no text given';
  }

  alert( from + ": " + text );
}
```
…Or using the || operator:
```
function showMessage(from, text) {
  // If the value of text is falsy, assign the default value
  // this assumes that text == "" is the same as no text at all
  text = text || 'no text given';
  ...
}
```
### Alternative default parameters
Sometimes it makes sense to assign default values for parameters at a later stage after the function declaration.

We can check if the parameter is passed during the function execution, by comparing it with undefined:
```
function showMessage(text) {
  // ...

  if (text === undefined) { // if the parameter is missing
    text = 'empty message';
  }

  alert(text);
}

showMessage(); // empty message
```

…Or we could use the || operator:

```
function showMessage(text) {

  // if text is undefined or otherwise falsy, set it to 'empty'
  text = text || 'empty';
  ...
}
```
Modern JavaScript engines support the nullish coalescing operator ??, it’s better when most falsy 
values, such as 0, should be considered “normal”:

```
function showCount(count) {
  // if count is undefined or null, show "unknown"
  alert(count ?? "unknown");
}

showCount(0); // 0
showCount(null); // unknown
showCount(); // unknown
```
### Returning a value
A function can return a value back into the calling code as the result.

The simplest example would be a function that sums two values:
```
function sum(a, b) {
  return a + b;
}

let result = sum(1, 2);
alert( result ); // 3
```
The directive return can be in any place of the function. When the execution reaches it, the function stops, 
and the value is returned to the calling code (assigned to result above).

There may be many occurrences of return in a single function. For instance:
```
function checkAge(age) {
  if (age >= 18) {
    return true;
  } else {
    return confirm('Do you have permission from your parents?');
  }
}

let age = prompt('How old are you?', 18);

if ( checkAge(age) ) {
  alert( 'Access granted' );
} else {
  alert( 'Access denied' );
}
```
It is possible to use return without a value. That causes the function to exit immediately.

For example:
```
function showMovie(age) {
  if ( !checkAge(age) ) {
    return;
  }

  alert( "Showing you the movie" ); // (*)
  // ...
}
```

In the code above, if checkAge(age) returns false, then showMovie won’t proceed to the alert.

A function with an empty return or without it returns undefined
If a function does not return a value, it is the same as if it returns undefined:
```
function doNothing() { /* empty */ }

alert( doNothing() === undefined ); // true
```
An empty return is also the same as return undefined:
```
function doNothing() {
  return;
}

alert( doNothing() === undefined ); // true
```

Never add a newline between return and the value
For a long expression in return, it might be tempting to put it on a separate line, like this:
```
return
 (some + long + expression + or + whatever * f(a) + f(b))
 ```
That doesn’t work, because JavaScript assumes a semicolon after return. That’ll work the same as:
```
return;
 (some + long + expression + or + whatever * f(a) + f(b))
```
So, it effectively becomes an empty return.

If we want the returned expression to wrap across multiple lines, we should start it at the same line as return. Or at least put the opening parentheses there as follows:
```
return (
  some + long + expression
  + or +
  whatever * f(a) + f(b)
  )
```
And it will work just as we expect it to.

### Naming a function
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and 
describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. 
There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

 - "get…" – return a value,
 - "calc…" – calculate something,
 - "create…" – create something,
 - "check…" – check something and return a boolean, etc.

Examples of such names:
```
showMessage(..)     // shows a message
getAge(..)          // returns the age (gets it somehow)
calcSum(..)         // calculates a sum and returns the result
createForm(..)      // creates a form (and usually returns it)
checkPermission(..) // checks a permission, returns true/false
```
With prefixes in place, a glance at a function name gives an understanding what kind of work it does 
and what kind of value it returns.

One function – one action
A function should do exactly what is suggested by its name, no more.

Two independent actions usually deserve two functions, even if they are usually called together (in that case we can make a 3rd function that calls those two).

A few examples of breaking this rule:

 - getAge – would be bad if it shows an alert with the age (should only get).
 - createForm – would be bad if it modifies the document, adding a form to it (should only create it and return).
 - checkPermission – would be bad if it displays the access granted/denied message (should only perform the check and return the result).

These examples assume common meanings of prefixes. You and your team are free to agree on other meanings, but usually they’re not much different. In any case, you should have a firm understanding of what a prefix means, what a prefixed function can and cannot do. All same-prefixed functions should obey the rules. And the team should share the knowledge.

Ultrashort function names
Functions that are used very often sometimes have ultrashort names.

For example, the jQuery framework defines a function with $. The Lodash library has its core function named _.

These are exceptions. Generally function names should be concise and descriptive.

### Functions == Comments
Functions should be short and do exactly one thing. If that thing is big, maybe it’s worth it to 
split the function into a few smaller functions. Sometimes following this rule may not be that 
easy, but it’s definitely a good thing.

A separate function is not only easier to test and debug – its very existence is a great comment!

For instance, compare the two functions showPrimes(n) below. Each one outputs prime numbers up to n.

The first variant uses a label:

```
function showPrimes(n) {
  nextPrime: for (let i = 2; i < n; i++) {

    for (let j = 2; j < i; j++) {
      if (i % j == 0) continue nextPrime;
    }

    alert( i ); // a prime
  }
}
```
The second variant uses an additional function isPrime(n) to test for primality:

```
function showPrimes(n) {

  for (let i = 2; i < n; i++) {
    if (!isPrime(i)) continue;

    alert(i);  // a prime
  }
}

function isPrime(n) {
  for (let i = 2; i < n; i++) {
    if ( n % i == 0) return false;
  }
  return true;
}
```

The second variant is easier to understand, isn’t it? Instead of the code piece we see a name of the 
action (isPrime). Sometimes people refer to such code as self-describing.

So, functions can be created even if we don’t intend to reuse them. They structure the code and make it readable.

#### Summary
A function declaration looks like this:
```
function name(parameters, delimited, by, comma) {
  /* code */
}
```
 - Values passed to a function as parameters are copied to its local variables.
 - A function may access outer variables. But it works only from inside out. The code outside of the function doesn’t see its local variables.
 - A function can return a value. If it doesn’t, then its result is undefined.

To make the code clean and easy to understand, it’s recommended to use mainly local variables and parameters in the function, not outer variables.

It is always easier to understand a function which gets parameters, works with them and returns a result than a function which gets no parameters, but modifies outer variables as a side effect.

Function naming:

 - A name should clearly describe what the function does. When we see a function call in the code, a good name instantly gives us an understanding what it does and returns.
 - A function is an action, so function names are usually verbal.
 - There exist many well-known function prefixes like create…, show…, get…, check… and so on. Use them to hint what a function does.

Functions are the main building blocks of scripts. Now we’ve covered the basics, so we actually can 
start creating and using them. But that’s only the beginning of the path. We are going to return to 
them many times, going more deeply into their advanced features.

### Tasks
### Is "else" required?
The following function returns true if the parameter age is greater than 18.

Otherwise it asks for a confirmation and returns its result:
```
function checkAge(age) {
  if (age > 18) {
    return true;
  } else {
    // ...
    return confirm('Did parents allow you?');
  }
}
```
Will the function work differently if else is removed?
```
function checkAge(age) {
  if (age > 18) {
    return true;
  }
  // ...
  return confirm('Did parents allow you?');
}
```
Is there any difference in the behavior of these two variants?

solution
No difference!

In both cases, return confirm('Did parents allow you?') executes exactly when the if condition is falsy.


### Rewrite the function using '?' or '||'
The following function returns true if the parameter age is greater than 18.

Otherwise it asks for a confirmation and returns its result.
```
function checkAge(age) {
  if (age > 18) {
    return true;
  } else {
    // ...
    return confirm('Did parents allow you?');
  }
}
```
Will the function work differently if else is removed?
```
function checkAge(age) {
  if (age > 18) {
    return true;
  }
  // ...
  return confirm('Did parents allow you?');
}
```
Is there any difference in the behavior of these two variants?

#### Rewrite the function using '?' or '||'
The following function returns true if the parameter age is greater than 18.

Otherwise it asks for a confirmation and returns its result.
```
function checkAge(age) {
  if (age > 18) {
    return true;
  } else {
    return confirm('Did parents allow you?');
  }
}
```
Rewrite it, to perform the same, but without if, in a single line.

Make two variants of checkAge:
Using a question mark operator ?
Using OR ||
solution
Using a question mark operator '?':
```
function checkAge(age) {
  return (age > 18) ? true : confirm('Did parents allow you?');
}
```
Using OR || (the shortest variant):
```
function checkAge(age) {
  return (age > 18) || confirm('Did parents allow you?');
}
```
Note that the parentheses around age > 18 are not required here. They exist for better readability.

#### Function min(a, b)
Write a function min(a,b) which returns the least of two numbers a and b.

For instance:
```
min(2, 5) == 2
min(3, -1) == -1
min(1, 1) == 1
```

solution
A solution using if:
```
function min(a, b) {
  if (a < b) {
    return a;
  } else {
    return b;
  }
}
```
A solution with a question mark operator '?':
```
function min(a, b) {
  return a < b ? a : b;
}
```
P.S. In the case of an equality a == b it does not matter what to return.

#### Function pow(x,n)

Write a function pow(x,n) that returns x in power n. Or, in other words, multiplies x by itself n times and returns the result.
```
pow(3, 2) = 3 * 3 = 9
pow(3, 3) = 3 * 3 * 3 = 27
pow(1, 100) = 1 * 1 * ...* 1 = 1
```
Create a web-page that prompts for x and n, and then shows the result of pow(x,n).

Run the demo

P.S. In this task the function should support only natural values of n: integers up from 1.

```
function pow(x, n) {
  let result = x;

  for (let i = 1; i < n; i++) {
    result *= x;
  }

  return result;
}

let x = prompt("x?", '');
let n = prompt("n?", '');

if (n < 1) {
  alert(`Power ${n} is not supported, use a positive integer`);
} else {
  alert( pow(x, n) );
}
```

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Function expressions
In JavaScript, a function is not a “magical language structure”, but a special kind of value.

The syntax that we used before is called a Function Declaration:
```
function sayHi() {
  alert( "Hello" );
}
```
There is another syntax for creating a function that is called a Function Expression.

It allows us to create a new function in the middle of any expression.

For example:
```
let sayHi = function() {
  alert( "Hello" );
};
```
Here we can see a variable sayHi getting a value, the new function, created as function() { alert("Hello"); }.

As the function creation happens in the context of the assignment expression (to the right side 
of =), this is a Function Expression.

Please note, there’s no name after the function keyword. Omitting a name is allowed for Function Expressions.

Here we immediately assign it to the variable, so the meaning of these code samples is the same: 
“create a function and put it into the variable sayHi”.

In more advanced situations, that we’ll come across later, a function may be created and immediately 
called or scheduled for a later execution, not stored anywhere, thus remaining anonymous.

### Function is a value
Let’s reiterate: no matter how the function is created, a function is a value. Both examples above 
store a function in the sayHi variable.

We can even print out that value using alert:
```
function sayHi() {
  alert( "Hello" );
}
alert( sayHi ); // shows the function code
```
Please note that the last line does not run the function, because there are no parentheses after sayHi. 
There are programming languages where any mention of a function name causes its execution, but JavaScript 
is not like that.

In JavaScript, a function is a value, so we can deal with it as a value. The code above shows its string 
representation, which is the source code.

Surely, a function is a special value, in the sense that we can call it like sayHi().

But it’s still a value. So we can work with it like with other kinds of values.

We can copy a function to another variable:
```
function sayHi() {   // (1) create
  alert( "Hello" );
}

let func = sayHi;    // (2) copy

func(); // Hello     // (3) run the copy (it works)!
sayHi(); // Hello    //     this still works too (why wouldn't it)
```

Here’s what happens above in detail:

1. The Function Declaration (1) creates the function and puts it into the variable named sayHi.
2. Line (2) copies it into the variable func. Please note again: there are no parentheses after sayHi. If there were, then func = sayHi() would write the result of the call sayHi() into func, not the function sayHi itself.
3. Now the function can be called as both sayHi() and func().

We could also have used a Function Expression to declare sayHi, in the first line:
```
let sayHi = function() { // (1) create
  alert( "Hello" );
};

let func = sayHi;  //(2)
// ...
```
Everything would work the same.

Why is there a semicolon at the end?
You might wonder, why do Function Expressions have a semicolon ; at the end, but Function Declarations do not:
```
function sayHi() {
  // ...
}

let sayHi = function() {
  // ...
};
```
The answer is simple: a Function Expression is created here as function(…) {…} inside the assignment statement: let sayHi = …;. The semicolon ; is recommended at the end of the statement, it’s not a part of the function syntax.

The semicolon would be there for a simpler assignment, such as let sayHi = 5;, and it’s also there for a function assignment.

### Callback functions
Let’s look at more examples of passing functions as values and using function expressions.

We’ll write a function ask(question, yes, no) with three parameters:

question
Text of the question
yes
Function to run if the answer is “Yes”
no
Function to run if the answer is “No”
The function should ask the question and, depending on the user’s answer, call yes() or no():
```
function ask(question, yes, no) {
  if (confirm(question)) yes()
  else no();
}

function showOk() {
  alert( "You agreed." );
}

function showCancel() {
  alert( "You canceled the execution." );
}

// usage: functions showOk, showCancel are passed as arguments to ask
ask("Do you agree?", showOk, showCancel);
```

In practice, such functions are quite useful. The major difference between a real-life ask and the 
example above is that real-life functions use more complex ways to interact with the user than a 
simple confirm. In the browser, such functions usually draw a nice-looking question window. But 
that’s another story.

The arguments showOk and showCancel of ask are called callback functions or just callbacks.

The idea is that we pass a function and expect it to be “called back” later if necessary. In our 
case, showOk becomes the callback for “yes” answer, and showCancel for “no” answer.

We can use Function Expressions to write an equivalent, shorter function:
```
function ask(question, yes, no) {
  if (confirm(question)) yes()
  else no();
}

ask(
  "Do you agree?",
  function() { alert("You agreed."); },
  function() { alert("You canceled the execution."); }
);
```
Here, functions are declared right inside the ask(...) call. They have no name, and so are called 
anonymous. Such functions are not accessible outside of ask (because they are not assigned to 
variables), but that’s just what we want here.

Such code appears in our scripts very naturally, it’s in the spirit of JavaScript.

A function is a value representing an “action”
Regular values like strings or numbers represent the data.

A function can be perceived as an action.

We can pass it between variables and run when we want.

### Function Expression vs Function Declaration
Let’s formulate the key differences between Function Declarations and Expressions.

First, the syntax: how to differentiate between them in the code.

Function Declaration: a function, declared as a separate statement, in the main code flow:

```
// Function Declaration
function sum(a, b) {
  return a + b;
}
```

Function Expression: a function, created inside an expression or inside another syntax construct. 
Here, the function is created on the right side of the “assignment expression” =:

```
// Function Expression
let sum = function(a, b) {
  return a + b;
};
```

The more subtle difference is when a function is created by the JavaScript engine.

A Function Expression is created when the execution reaches it and is usable only from that moment.

Once the execution flow passes to the right side of the assignment let sum = function… – here we go, 
the function is created and can be used (assigned, called, etc. ) from now on.

Function Declarations are different.

A Function Declaration can be called earlier than it is defined.

For example, a global Function Declaration is visible in the whole script, no matter where it is.

That’s due to internal algorithms. When JavaScript prepares to run the script, it first looks for global 
Function Declarations in it and creates the functions. We can think of it as an “initialization stage”.

And after all Function Declarations are processed, the code is executed. So it has access to these functions.

For example, this works:
```
sayHi("John"); // Hello, John

function sayHi(name) {
  alert( `Hello, ${name}` );
}
```
The Function Declaration sayHi is created when JavaScript is preparing to start the script 
and is visible everywhere in it.

…If it were a Function Expression, then it wouldn’t work:
```
sayHi("John"); // error!

let sayHi = function(name) {  // (*) no magic any more
  alert( `Hello, ${name}` );
};
```
Function Expressions are created when the execution reaches them. That would happen only in the line (*). Too late.

Another special feature of Function Declarations is their block scope.

In strict mode, when a Function Declaration is within a code block, it’s visible everywhere 
inside that block. But not outside of it.

For instance, let’s imagine that we need to declare a function welcome() depending on the age 
variable that we get during runtime. And then we plan to use it some time later.

If we use Function Declaration, it won’t work as intended:

```
let age = prompt("What is your age?", 18);
// conditionally declare a function
if (age < 18) {
  function welcome() {
    alert("Hello!");
  }
} else {
  function welcome() {
    alert("Greetings!");
  }
}
// ...use it later
welcome(); // Error: welcome is not defined
```

That’s because a Function Declaration is only visible inside the code block in which it resides.

Here’s another example:

```
let age = 16; // take 16 as an example
if (age < 18) {
  welcome();               // \   (runs)
                           //  |
  function welcome() {     //  |
    alert("Hello!");       //  |  Function Declaration is available
  }                        //  |  everywhere in the block where it's declared
                           //  |
  welcome();               // /   (runs)
} else {
  function welcome() {
    alert("Greetings!");
  }
}
// Here we're out of curly braces,
// so we can not see Function Declarations made inside of them.
welcome(); // Error: welcome is not defined
```

What can we do to make welcome visible outside of if?

The correct approach would be to use a Function Expression and assign welcome to the variable that is 
declared outside of if and has the proper visibility.

This code works as intended:

```
let age = prompt("What is your age?", 18);
let welcome;
if (age < 18) {
  welcome = function() {
    alert("Hello!");
  };
} else {
  welcome = function() {
    alert("Greetings!");
  };
}
welcome(); // ok now
```

Or we could simplify it even further using a question mark operator ?:

```
let age = prompt("What is your age?", 18);
let welcome = (age < 18) ?
  function() { alert("Hello!"); } :
  function() { alert("Greetings!"); };
welcome(); // ok now
```

When to choose Function Declaration versus Function Expression?
As a rule of thumb, when we need to declare a function, the first thing to consider is Function 
Declaration syntax. It gives more freedom in how to organize our code, because we can call such 
functions before they are declared.

That’s also better for readability, as it’s easier to look up function f(…) {…} in the code than 
let f = function(…) {…};. Function Declarations are more “eye-catching”.

…But if a Function Declaration does not suit us for some reason, or we need a conditional declaration 
(we’ve just seen an example), then Function Expression should be used.

### Summary
 - Functions are values. They can be assigned, copied or declared in any place of the code.
 - If the function is declared as a separate statement in the main code flow, that’s called a “Function Declaration”.
 - If the function is created as a part of an expression, it’s called a “Function Expression”.
 - Function Declarations are processed before the code block is executed. They are visible everywhere in the block.
 - Function Expressions are created when the execution flow reaches them.

In most cases when we need to declare a function, a Function Declaration is preferable, because it is 
visible prior to the declaration itself. That gives us more flexibility in code organization, and is usually more readable.

So we should use a Function Expression only when a Function Declaration is not fit for the task. We’ve 
seen a couple of examples of that in this chapter, and will see more in the future.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Arrow functions, the basics
There’s another very simple and concise syntax for creating functions, that’s often better than Function Expressions.

It’s called “arrow functions”, because it looks like this:
```
let func = (arg1, arg2, ..., argN) => expression;
```
This creates a function func that accepts arguments arg1..argN, then evaluates the expression on the 
right side with their use and returns its result.

In other words, it’s the shorter version of:
```
let func = function(arg1, arg2, ..., argN) {
  return expression;
};
```
Let’s see a concrete example:
```
let sum = (a, b) => a + b;
/* This arrow function is a shorter form of:
let sum = function(a, b) {
  return a + b;
};
*/
alert( sum(1, 2) ); // 3
```
As you can see, (a, b) => a + b means a function that accepts two arguments named a and b. Upon the execution, it evaluates the expression a + b and returns the result.

If we have only one argument, then parentheses around parameters can be omitted, making that even shorter.

For example:
```
let double = n => n * 2;
// roughly the same as: let double = function(n) { return n * 2 }

alert( double(3) ); // 6
```

If there are no arguments, parentheses are empty, but they must be present:
```
let sayHi = () => alert("Hello!");

sayHi();
```
Arrow functions can be used in the same way as Function Expressions.

For instance, to dynamically create a function:
```
let age = prompt("What is your age?", 18);

let welcome = (age < 18) ?
  () => alert('Hello!') :
  () => alert("Greetings!");

welcome()
```

Arrow functions may appear unfamiliar and not very readable at first, but that quickly changes as the eyes get used to the structure.

They are very convenient for simple one-line actions, when we’re just too lazy to write many words.

### Multiline arrow functions
The arrow functions that we’ve seen so far were very simple. They took arguments from the left of =>, evaluated and returned the right-side expression with them.

Sometimes we need a more complex function, with multiple expressions and statements. In that case, we can enclose them in curly braces. The major difference is that curly braces require a return within them to return a value (just like a regular function does).

Like this:
```
let sum = (a, b) => {  // the curly brace opens a multiline function
  let result = a + b;
  return result; // if we use curly braces, then we need an explicit "return"
};

alert( sum(1, 2) ); // 3
```
More to come
Here we praised arrow functions for brevity. But that’s not all!

Arrow functions have other interesting features.

To study them in-depth, we first need to get to know some other aspects of JavaScript, so we’ll return to arrow functions later in the chapter Arrow functions revisited.

For now, we can already use arrow functions for one-line actions and callbacks.

### Summary
Arrow functions are handy for simple actions, especially for one-liners. They come in two flavors:

1. Without curly braces: (...args) => expression – the right side is an expression: the function evaluates it and returns the result. Parentheses can be omitted, if there’s only a single argument, e.g. n => n*2.
2. With curly braces: (...args) => { body } – brackets allow us to write multiple statements inside the function, but we need an explicit return to return something.

#### Rewrite with arrow functions

Replace Function Expressions with arrow functions in the code below:

```
function ask(question, yes, no) {
  if (confirm(question)) yes();
  else no();
}

ask(
  "Do you agree?",
  function() { alert("You agreed."); },
  function() { alert("You canceled the execution."); }
);
```

solution

```
function ask(question, yes, no) {
  if (confirm(question)) yes();
  else no();
}

ask(
  "Do you agree?",
  () => alert("You agreed."),
  () => alert("You canceled the execution.")
);
```
Looks short and clean, right?
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## JavaScript specials
This chapter briefly recaps the features of JavaScript that we’ve learned by now, paying special attention to subtle moments.

### Code structure
Statements are delimited with a semicolon:
```
alert('Hello'); alert('World');
```
Usually, a line-break is also treated as a delimiter, so that would also work:
```
alert('Hello')
alert('World')
```
That’s called “automatic semicolon insertion”. Sometimes it doesn’t work, for instance:
```
alert("There will be an error after this message")

[1, 2].forEach(alert)
```
Most codestyle guides agree that we should put a semicolon after each statement.

Semicolons are not required after code blocks {...} and syntax constructs with them like loops:
```
function f() {
  // no semicolon needed after function declaration
}

for(;;) {
  // no semicolon needed after the loop
}
```
…But even if we can put an “extra” semicolon somewhere, that’s not an error. It will be ignored.

More in: Code structure.

### Strict mode
To fully enable all features of modern JavaScript, we should start scripts with "use strict".
```
'use strict';

...
```
The directive must be at the top of a script or at the beginning of a function body.

Without "use strict", everything still works, but some features behave in the old-fashioned,
 “compatible” way. We’d generally prefer the modern behavior.

Some modern features of the language (like classes that we’ll study in the future) enable strict mode implicitly.

More in: The modern mode, "use strict".

### Variables
Can be declared using:

 - let
 - const (constant, can’t be changed)
 - var (old-style, will see later)

A variable name can include:

 - Letters and digits, but the first character may not be a digit.
 - Characters $ and _ are normal, on par with letters.
 - Non-Latin alphabets and hieroglyphs are also allowed, but commonly not used.

Variables are dynamically typed. They can store any value:
```
let x = 5;
x = "John";
```
There are 8 data types:

 - number for both floating-point and integer numbers,
 - bigint for integer numbers of arbitrary length,
 - string for strings,
 - boolean for logical values: true/false,
 - null – a type with a single value null, meaning “empty” or “does not exist”,
 - undefined – a type with a single value undefined, meaning “not assigned”,
 - object and symbol – for complex data structures and unique identifiers, we haven’t learnt them yet.

The typeof operator returns the type for a value, with two exceptions:
```
typeof null == "object" // error in the language
typeof function(){} == "function" // functions are treated specially
```
More in: Variables and Data types.

### Interaction
We’re using a browser as a working environment, so basic UI functions will be:

prompt(question, [default])
Ask a question, and return either what the visitor entered or null if they clicked “cancel”.
confirm(question)
Ask a question and suggest to choose between Ok and Cancel. The choice is returned as true/false.
alert(message)
Output a message.
All these functions are modal, they pause the code execution and prevent the visitor from interacting with the page until they answer.

For instance:
```
let userName = prompt("Your name?", "Alice");
let isTeaWanted = confirm("Do you want some tea?");

alert( "Visitor: " + userName ); // Alice
alert( "Tea wanted: " + isTeaWanted ); // true
```
More in: Interaction: alert, prompt, confirm.

### Operators
JavaScript supports the following operators:

#### Arithmetical
Regular: * + - /, also % for the remainder and ** for power of a number.

The binary plus + concatenates strings. And if any of the operands is a string, the other one is converted to string too:
```
alert( '1' + 2 ); // '12', string
alert( 1 + '2' ); // '12', string
```

#### Assignments
There is a simple assignment: a = b and combined ones like a *= 2.

#### Bitwise
	Bitwise operators work with 32-bit integers at the lowest, bit-level: see the docs when they are needed.

#### Conditional
The only operator with three parameters: cond ? resultA : resultB. If cond is truthy, returns resultA, otherwise resultB.

#### Logical operators
Logical AND && and OR || perform short-circuit evaluation and then return the value where it stopped (not necessary true/false). Logical NOT ! converts the operand to boolean type and returns the inverse value.

#### Nullish coalescing operator
The ?? operator provides a way to choose a defined value from a list of variables. The result of a ?? b is a unless it’s null/undefined, then b.

#### Comparisons
Equality check == for values of different types converts them to a number (except null and undefined that equal each other and nothing else), so these are equal:
```
alert( 0 == false ); // true
alert( 0 == '' ); // true
```
Other comparisons convert to a number as well.

The strict equality operator === doesn’t do the conversion: different types always mean different values for it.

Values null and undefined are special: they equal == each other and don’t equal anything else.

Greater/less comparisons compare strings character-by-character, other types are converted to a number.

#### Other operators
There are few others, like a comma operator.

More in: Basic operators, maths, Comparisons, Logical operators, Nullish coalescing operator '??'.

### Loops
We covered 3 types of loops:
```
// 1
while (condition) {
  ...
}

// 2
do {
  ...
} while (condition);

// 3
for(let i = 0; i < 10; i++) {
  ...
}
```
The variable declared in for(let...) loop is visible only inside the loop. But we can also omit let and reuse an existing variable.

Directives break/continue allow to exit the whole loop/current iteration. Use labels to break nested loops.

Details in: Loops: while and for.

Later we’ll study more types of loops to deal with objects.

### The “switch” construct
The “switch” construct can replace multiple if checks. It uses === (strict equality) for comparisons.

For instance:
```
let age = prompt('Your age?', 18);

switch (age) {
  case 18:
    alert("Won't work"); // the result of prompt is a string, not a number
    break;

  case "18":
    alert("This works!");
    break;

  default:
    alert("Any value not equal to one above");
}
```
Details in: The "switch" statement.

### Functions
We covered three ways to create a function in JavaScript:
```
Function Declaration: the function in the main code flow

function sum(a, b) {
  let result = a + b;

  return result;
}
```

Function Expression: the function in the context of an expression
```
let sum = function(a, b) {
  let result = a + b;

  return result;
};
```

Arrow functions:
```
// expression on the right side
let sum = (a, b) => a + b;

// or multi-line syntax with { ... }, need return here:
let sum = (a, b) => {
  // ...
  return a + b;
}

// without arguments
let sayHi = () => alert("Hello");

// with a single argument
let double = n => n * 2;
```
 - Functions may have local variables: those declared inside its body or its parameter list. Such variables are only visible inside the function.
 - Parameters can have default values: function sum(a = 1, b = 2) {...}.
 - Functions always return something. If there’s no return statement, then the result is undefined.

Details: see Functions, Arrow functions, the basics.

More to come
That was a brief list of JavaScript features. As of now we’ve studied only basics. Further in the tutorial you’ll find more specials and advanced features of JavaScript.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Code quality
This chapter explains coding practices that we’ll use further in the development.

1. <a href="https://javascript.info/debugging-chrome">Debugging in the browser</a>
2. <a href="https://javascript.info/coding-style">Coding Style</a>
3. <a href="https://javascript.info/comments">Comments</a>
4. <a href="https://javascript.info/ninja-code">Ninja code</a>
5. <a href="https://javascript.info/testing-mocha">Automated testing with Mocha</a>
6. <a href="https://javascript.info/polyfills">Polyfills and transpilers</a>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Debugging in the browser
Before writing more complex code, let’s talk about debugging.

Debugging is the process of finding and fixing errors within a script. All modern browsers and most 
other environments support debugging tools – a special UI in developer tools that makes debugging 
much easier. It also allows to trace the code step by step to see what exactly is going on.

We’ll be using Chrome here, because it has enough features, most other browsers have a similar process.

### The “Sources” panel
Your Chrome version may look a little bit different, but it still should be obvious what’s there.

 - Open the example page in Chrome.
 - Turn on developer tools with F12 (Mac: Cmd+Opt+I).
 - Select the Sources panel.

Here’s what you should see if you are doing it for the first time:



<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->




<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->




<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->




<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->




<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
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

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
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

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
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


### Summary
The global object holds variables that should be available everywhere.

That includes JavaScript built-ins, such as Array and environment-specific values, such as window.innerHeight – the window height in the browser.

The global object has a universal name globalThis.

…But more often is referred by “old-school” environment-specific names, such as window (browser) and global (Node.js).

We should store values in the global object only if they’re truly global for our project. And keep their number at minimum.

In-browser, unless we’re using modules, global functions and variables declared with var become a property of the global object.

To make our code future-proof and easier to understand, we should access properties of the global object directly, as window.x.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->

