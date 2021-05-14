# Error Handling & Debugging 
## ORDER OF EXECUTION  
Single threaded languages make use of only one CPU at a time, meaning only one thing can happen at a time. Other languages are multi-threaded, meaning that many processes can happen at the same time. However, since those processes are often inter-related or inter-dependent, it requires a great deal of communication between the processors. If that communication happens incorrectly or out of order, the system can crash.
Synchronous refers to things happening in a specific order. In a relay race, the first person has to finish and hand off the baton (or reach the end of the pool, etc.) before the next person can start.
Asynchronous means that a process can happen out of order. How is that possible? A process can be started, put to the side, and resumed later, or a process can be running in the background, such as when the process is waiting for a response from an external source. 

## EXECUT.ION CONTEXTS 

There are three types of execution context in JavaScript.

- Global Execution Context — This is the default or base execution context. The code that is not inside any function is in the global execution context. It performs two things: it creates a global object which is a window object (in the case of browsers) and sets the value of this to equal to the global object. There can only be one global execution context in a program.
- Functional Execution Context — Every time a function is invoked, a brand new execution context is created for that function. Each function has its own execution context, but it’s created when the function is invoked or called. There can be any number of function execution contexts. Whenever a new execution context is created, it goes through a series of steps in a defined order which I will discuss later in this article.
- Eval Function Execution Context — Code executed inside an eval function also gets its own execution context, but as eval isn’t usually used by JavaScript developers.
## the stack 
stack is a data structure that has way more limitations, compared to arrays. We can add items to a stack only by adding them on top. And we can only remove the item on top of the stack. Think about it like a pile of books. You can only add books on top, and you can only  

## EXECUTION CONTEXT & HOISTING  
  Javascript (JS) is an interpreted language, still has its own form of a compiler, run in what’s known as the Javascript engine.

  ### Execution Context 

  An environment in which the javascript code runs is what form an execution context.
The execution context decides what particular piece of code has access to variables, functions, objects, etc. 

## UNDERSTANDING SCOPE 


Scope in JavaScript refers to the current context of code, which determines the accessibility of variables to JavaScript. The two types of scope are local and global: Global variables are those declared outside of a block. Local variables are those declared inside of a block 


## UNDERSTANDING ERRORS 
The first step to understanding JavaScript errors is to understand where they come from. Most JavaScript errors that occur in the wild are automatically generated from the JavaScript engine. There are many types of errors but they typically fall into one of 3 classes.

- TypeError
One of the most common classes of error, this occurs when some value is not the type it’s expected to be. Frequently this happens when calling something like a function that actually isn’t a function because it is “undefined” or some other value.
- SyntaxError
These errors occur when the JavaScript engine is parsing a script and encounters syntactically invalid code. If a JavaScript file contains a syntax error, none of the code in the file will execute.
- ReferenceError
These occur when code refers to a value that does not exist in the current scope

## ERROR OBJECTS 

JavaScript interpreters throw an Error object, when a script error (exception) occurs. In some cases when the error is caused by a DOM operation, JavaScript interpreters throw an 

### Error types

- EvalError
Creates an instance representing an error that occurs regarding the global function eval().
- RangeError
Creates an instance representing an error that occurs when a numeric variable or parameter is outside of its valid range. 
- ReferenceError
Creates an instance representing an error that occurs when de-referencing an invalid reference. 
- URIError
Creates an instance representing an error that occurs when encodeURI() or decodeURI() are passed invalid parameters. 
- AggregateError
Creates an instance representing several errors wrapped in a single error when multiple errors need to be reported by an operation, for example by Promise.any(). 
- InternalError 
Creates an instance representing an error that occurs when an internal error in the JavaScript engine is thrown. E.g. "too much recursion". 
## HOW TO DEAL WITH ERRORS 
 
 JavaScript supports a compact set of statements, specifically control flow statements, that you can use to incorporate a great deal of interactivity in your application. This chapter provides an overview of these statements.

The JavaScript reference contains exhaustive details about the statements in this chapter. The semicolon (;) character is used to separate statements in JavaScript code.

Any JavaScript expression is also a statement. See Expressions and operators for complete information about expressions. 

## A DEBUGGING WORKFLOW 

The process for debugging is different for the two phases of the Data Connector workflow.

Debugging the interactive phase

The interactive phase occurs in the user’s browser, which means that the Javascript surrounding this phase can be debugged using the browser’s developer tools.

Debugging the fetch table phase

The fetch table phase is executed in a NodeJS context within the Intelligence Server (IServer), which means that debugging cannot be handled as normal using the browser’s developer tools and must be handled differently.

To detect whether the Data Connector's Javascript is being executed within the browser or within the NodeJS context in the IServer, you need to inspect the user agent. If the user-agent contains node.js, you can assume the code is currently being executed within the NodeJS context 
 

