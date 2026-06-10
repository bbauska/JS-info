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
| string	The string is read “as is”, whitespaces (includes spaces, tabs \t, newlines \n etc.) from both sides are ignored. An empty string becomes 0. An error gives NaN. |

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

