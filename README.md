# JavaScript-Video-Notes
# A1 task: Beginner’s Series to JavaScript
JavaScript is a programming language to interact with elements on a webpage in a browser like adding a button aor changing a style with code it is a c base language so it kind of looks like java but it nothing to do with java . it is a dynamically typed language. It is the most used programming language in the world huge websites and social media sites uses java script. Its in the browser you can built application with the java script. You can use java script in any platform to built any product. It has unlimited use cases. 
## Java script--Client vs server
- Java script on client-  a web browser put the file in a separate file with .js extension use same script tag but you gonna specify with a src attribute and point it to the script file called source file
To run java script on a server side we need to use node.js. we have to install node.js on the server side and execute by calling node and the script file directly from the command line. Repository of third party packages called npm which contains package of anything we can think of.
Webbrower uses script tags primarily used for building user interfaces  and server uses node.js to be installed and is usually used for buildingweb services.
## Learnt to install vsc and node.js in video 4 and 5
## Learnt the use cases for single quotes, double quote ,%S, $, back tick
## Building a first java script application using node.js. making different folders with files that contains file. Use of single quotes and double quotes.
Code comments in java script are the lines in the code that we can see but doesnot execute
Two types of comment single line and multi lilne comment  //
Multi line comment /*abcde*/
Demo comments: ToDo list could be created so we can come back and do the job.
Ctrl + / it comments a line out and if selected a block it comments the whole block.
## Declaring variables:  three ways
 Var one = 1;  fuction scoped, can be changed in scope, available before declaration.
Let two =2;  block scoped, can be changed in scope, only available after declaration.
Const three = 3; Block scoped. Like let, cannot be changed, only available after declaration.
Demo of declaration of variables: learnt different use case of different varriables (var,let and const).
## Working with strings: string concatenation combines two or more strings, it helps to make test easier to format. It can join a combination of variables and/or actual string called string literals. Concatenation strings will make a new string. Strings are closed with quotes. 
Demo working with string: Learnt the use case of (+) operator. Both number and string uses + operator.

## Using template literals to format string: uses one pair of baclticks, respects line breaks, placeholders insert variable values and expressions.
Template literals demo: concatenation, string, Boolean use cases

## Data type in java script: 
simple type: number, string, Boolean, date, function, array and object
 special type: NaN, null, undefined

## Double equal operator and triple equal operator == and use (===) for type testing.
demo: different use cases of array, number, string, Boolean, object and function.
Math in javascript: addition, substraction, multiplication and division. Increase or decrease a number by 1 (++num19 (--num1) use case of math object for performing trigonometric, logarithmic and other more. 
Demo: basic math operation and use case of math object.
## Converting string to numbers: use case of parseInt()  and 
parseFloat() for floating point numbers, numbers with decimal points.
toString() to convert numbers to numerical strings.
## Video 20
- Converting strings to numbers:  use case of parseInt function with strings. Use case of Template Literals and numbers to string.
parseInt()  for whole numbers 
ParseFloat() for decimals
## Video 21 & 22
- Handling errors with try/catch/finally: 
Exception: Interruption in the inteded execution of code.
Error: Unintended interruption in execution of code.
Throwing an Exception: sending a message that something has gone wrong in the intended execution of code. It can be thrown by javascript or manually.
Uncaught Exceptions:  
Try (Block of code that may throw an exception)
Catch (Block of code that will run if an exception is thrown)
Finally (optional enclosed part of code that will run after the try block or after the catch block)
Demo handling errors: usnig two different exception. String and Boolean.
Throwing (Try..Catch..Finally) exceptions
## Video 23 & 24
-  Dates: How dates work inside Javascript? Date is a central object that contains both date and time.
Time is an object. To create a date object:
const now = new Date();
Months starts with zero(january=0)
setting values:
Demo:
Setting values ###
const now = new Date();
now.setFullYear(2014); // sets year
now.setMonth(3); // April (counting starts at zero)
now.setDate(4); // sets day
now.setHours(4); // 24 hour clock
now.setMinutes(24);
now.setSeconds(46);
console.log(now);
## Video 25 & 26
- ) Boolean logic with if statements:
JavaScript supports the common operators
	< for smaller number or closer to start of the alphabet
	<= for smaller or equal number or closer to start of alphabet
	> for larger number or further from start of the alphabet
	>= for larger or equal number 
JavaScript has two comparison operators:
•	== checks for equality regardless of data type Example: '42' == 42 tests as true
•	=== checks for equal values and data types Example: '42' === 42 tests as false

Not equal operator
	!= checks for non-equality regardless of data type
	!== checks for non-equal values and data types
Demo: String not equals to number. Learnt use case of using double equals and triple equals.(== or ===)
## Video 27 & 28
- Boolean logic with switch and other syntax:
Implicit false values
Strings
•	Empty strings test as false
Objects
•	Null or undefined objects test as false
Numbers
•	0 tests as false
! to reverse the result 
Combining comparisons
And (both sides must be true)
•	(x & y)
•	(x && y)
Or (either side can be true)
•	(x | y)
•	(x || y)
Shortcut operators && and ||
Stops evaluation if the answer is already known
•	(x && y) → y not evaluated if x is false because the answer is false
•	(x || y) → y not evaluated if x is true because the answer is true
Demo: Boolean logic with switch and other syntax:
Use case of switch statement and if statement.
## Video 29 & 30
- Creating array: Arrays allow you to store multiple items in one variable
	List, or collection of values Arrays can contain many different values of different data types
	Each value has an index An index is a unique numerical value that represents the value in the array
	Array Length After an array is created, you can check its length at any time with arrayName.length
Demo creating array:
Array length and array object.
let arrayLength = 5;
let arr1 = [];
let arr2 = Array(arrayLength);
## Video 31 & 32
- populating arrays: Adding Data to an Array

During array creation You can create an array with data in one statement
After array creation You can add data to an array after it's been created This method requires assigning the value to an index Indexes that may already have a value will be overwritten Keeping track of array's length is important if it has a fixed length.
Demo:
Adding data to an array: Learnt to add data to an array. Adding data during and after creation.
let arrayLength = 2;
let arr2 = Array(arrayLength);
arr2[0] = "Value at index 0";
console.log(arr2[0]);
console.log(arr2[1]); // No value present at index
## Video 33 & 34
- Array methods:
Manipulating Arrays
Push and Pop – Affects end of array
	array.push(values) adds one or more values to the end of the array and returns its new length
	array.pop() removes a value from the end of the array and returns the removed value

Shift and Unshift – Affects front of array
	array.shift() removes a value from the front of the array and returns the removed value
	array.unshift(values) adds one or more values to the front of the array and returns its new length
Concat
	Joins two arrays to make a new array

Demo:
Push and Pop
let arr1 = ["A", true, 2];
console.log(arr1.push("new value"));
console.log(arr1);
console.log(arr1.pop()); // Remove last value
console.log(arr1);
Shift and Unshift
let arr1 = ["A", true, 2];
console.log(arr1.unshift("new value"));
console.log(arr1);
console.log(arr1.shift()); // Remove first value
console.log(arr1);
Concat
let arr1 = ["A", true, 2];
let arr2 = ["B", false, 3];
let newArr = arr1.concat(arr2);
let newArr2 = arr2.concat([1, 2, 3]);
console.log(newArr);
console.log(newArr2);
## Video 35 & 36
- loops:
Loops in JavaScript
•	Execute code multiple times
•	Hard coded value
•	Iterate through a list
•	While something is true
Common loop types
	while
	for
	for ... of
Demo:
While loops
const names = ['Justin', 'Sarah', 'Christopher'];
let index = 0;
while (index < names.length) {
  const name = names[index];
  console.log(name);
  index++;
}
For loops
const names = ['Justin', 'Sarah', 'Christopher'];
for (let index = 0; index < names.length; index++) {
  const name = names[index];
  console.log(name);
}
for ... of loops
const names = ['Justin', 'Sarah', 'Christopher'];
for (let name of names) {
  console.log(name);
}
## Video 37 & 38
- Functions:
It is the most powerful tool in the developer's toolbox. They allow you to take a block of code, put a name on it to make it clear what it does, and then call it as often as you need
Define a function with {}
Like variable name conventions
•	Use alphabets, numbers, $, and _
•	No other special characters allowed
Function .name property
•	Returns the name of the function
•	Returns "anonymous" for anonymous functions
Demo Functions:
learnt what different are. Functions Definition, functions Invocation, how to pass a data, what return statements do.
## Video 39 & 40
- Arrow and anonymous functions:
Arrow functions:
Defined by =>
	Sometimes called ‘fat arrow functions’
	Changes to the this context
	Support implicit return values
	Must be assigned to a variable, or immediately used
	Reduction in characters typed

Demo: Array functions in javascript
const add = (a, b) => a + b;
console.log(add(1, 2)); // 3
const subtract = (a, b) => {
  return a - b;
};
console.log(subtract(2, 1)); // 1
## Video 41 & 42
- Javascript object Notation (JSON)
The flexibility of JavaScript allows us to create objects on the fly to suit your needs. One common way to do this is through JavaScript Object Notation or JSON - so common in fact it's become a common standard
¤ major things to know:
	JSON
	JSON format
	Serialize Object to JSON
	Deserialize JSON to Object

Demo:
###// JSON.stringify - object input
console.log("\n ------- ")
let bookJSON = JSON.stringify(book);
console.log(typeof bookJSON);
console.log(bookJSON);

// JSON.stringify - collection input
console.log("\n ------- ")
let myBooksJSON = JSON.stringify(myBooks);
console.log(myBooksJSON);

// JSON.parse - string input
let data = bookJSON;
let parsed = JSON.parse(data);
console.log("\n ------- ")
console.log(parsed);
console.log(Array.isArray(parsed));
console.log("Num items: " + parsed.length);


// JSON.parse - string input
data = myBooksJSON;
parsed = JSON.parse(data);
console.log("\n ------- ");
console.log(parsed);
console.log(Array.isArray(parsed));
console.log("Num items: " + parsed.length);
console.log("Author of 2nd book: " + parsed[1].author);
## Video 43 & 44
- Objects in javascript
JavaScript allows us to do more with objects than simply create data structures. We can create fully functional objects with methods and state. This allows us to better represent information and operations in your code.
	Basics: What are objects
	Syntax: Object definition
	Creation: Literals & constructors
	Properties: Associated variables
	Methods: Associated functions
	"this":

Demo:
Defining simple object in java script:
const blank = {};
console.log("Blank type:", typeof blank);
console.log("Blank value", blank);
Defining objects with Properties
const book = {
  title: "1984",
  author: "George Orwell",
  isAvailable: false
};

console.log("Book type:", typeof book);
console.log("Book value:\n", book);
## Video 45 & 46
- Promises for long running operations:
Calls to databases and other external services can take a while. We need to ensure the application doesn't cease all operations while those complete. By using promises we can allow for better thread management and ensure our application stays responsive and has better performance.
	Common development pattern Cleaner version of callbacks
	Recent versions of JavaScript have built-in Promise object Long running operations typically return a Promise.
Demo:
function promiseTimeout(ms) {
  return new Promise((resolve, reject) => {
    setTimeout(resolve, ms);
  });
}
promiseTimeout(2000)
  .then(() => {
    console.log('done');
    return Promise.resolve(42);
  })
  .then((response) => {
    console.log(response);
  })
  .catch(() => {
    console.log('cool error handling');
  });
This example demonstrates how to create a Promise that resolves after a delay using setTimeout, then chains .then() blocks to handle the result and .catch() for error handling.
## Video 47 & 48
- Async/Await: Make asynchronous code look synchronous
While promises are cleaner, they’re not perfect 
	Can add bloat to code
async/await
	Standard in many languages
	Syntax closer to synchronous code

Demo:
function promiseTimeout(ms) {
    return new Promise((resolve, reject) => {
        setTimeout(resolve, ms);
    });
}
async function simulateLongOperation() {
    await promiseTimeout(1000);
    return 42;
}
async function run() {
    const answer = await simulateLongOperation();
    console.log(answer);
}
This example shows how async/await simplifies asynchronous code. Instead of chaining .then(), it pauses execution with await, making the flow easier to read and maintain. 
## Video 49 & 50
- Package management:
A package is a reusable bundle of code and/or assets like Libraries, Tools, Shared components or an app. Packages can be found on npm. Over 1 million packages can be found on npm and its growing everyday. 
Applications frequently have the same set of core requirements. Rather than creating your own solutions, you can instead bring in packages created by others.

Demo: 
{
  "name": "vsc-demo",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}
Npm install –save-dev prettier. ”devDependencies” with package installed ”prettier” will appear.














