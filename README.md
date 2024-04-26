# JavascriptBasics
# JSIntroduction
- JavaScript HTML method: 'getElementById()'
- getElementById(): JavaScript method.
- This method retrieves HTML element by unique ID.
- Used for dynamic content change.
- Example: Button click alters content.
- JavaScript accepts double/single quotes.

- JavaScript can modify HTML attribute values.
- Example: Altering "src" atrribute of <img> tag.
- Button click triggers change in src attribute.
- Functionality akin to turning light on/off.
- Atrribute: src(source)
- Example: Button click switches image source
- Functionality: Turning light on and off.

- JavaScript modifies HTML  element  styles(CSS).
- Example: Adjusting font size
- Button click alters foontSize style property
- Style property: fontSize
- Example: Button click changes font size

- JavaScript hides HTML elements
- Example: Mofdifying display property
- button click hides element.
- Style property: display
- Example: Button click hides element

- JavaScript enables revealing hidden HTML elements.
- Example: Modifying display property
- Button click reveals hidden element
- Style property: display
- Example: Button click reveals hidden element
  
# JavaScript Where To 
- <script></script>
- to insert JavaScript code in HTML
  - function : (called for)
  - event
  - external javascript :separates HTML annd code. easy to  read and  maintain. speed up page  loads
  - 
    
# JavaScript Output
- innerHTMl
- documnet.write()
- window.alert()
- console.log()
- only in the browser: window.print()
  
  
# JavaScript Statements
- values, operators, expresssions, keywords, comments
- semicolon
- Keywords: var, let, const, if, switch, for, function, return, try
- 
# JavaScript Syntax
- fixed values - Literals
- variable values - Variables

# JavaScript Comments
- single line: //
- multiline: /*...*/
# JavaScript Variables
- var, let, const
- identified with unique names : identifieIrs
- 
# JavaScript Let
- variables with block  scope
- must be declared before use
- Global scope: declared with var
- var can't have block scope
- 
# JavaScript Const
- cannot be redeclared
# JavaScript Operators
- =, +, *, >
- Arithmetic
- Assignment
- Comparison
- String
- Logical
- Bitwise
- Ternary
- Type
  

# JavaScript Arithmetic
- perfomr mathematical caluculations on numbers
- +, -, *, **,  /, %, ++, --
- operators and operands
-  result of modulo operation = remainder
-  ** = Math.pow(x,2);
# JavaScript Assignment
- =
- +=
- -=
- *=
- **=
- /=
- %=
- <<=
- >>=
- >>>=
- &=
- |=
- ^=
- &&=
- ||=
- 


  

# JavaScript Data Types
1. String
2. Number
3. Bigint
4. Boolean
5. Undefined
6. Null
7. Symbol
8. Object - an object, an array, a date
# JavaScript Functions
- block of code to perform a particular task
- executed when called
- syntax: function functionName(){}
- parameters, arguments: values recieved when being invoked
- 
- 
# JavaScript Objects
- written with curly braces
- name: value

  - a variable without value: undefined (type is also undefined)
  - empty string has both a legal value and a type

 - The () Operator: invokes the function.
 - local variable: inside the function()
 - global variable: outside the function()

# JavaScript Objects
- const objectName = {property1: value1, property2: value2, property3: value3, property4: value4 .....}
- objectName.property1
- objectName[property1]
- objects can have methods. methoods are actions that can be performed on objects.
- stored in properties as function definitions.
- method is a function stored as a property.

  - this refers to the current object
  - 
# JavaScript Events
- things that happen to HTML elements
- JavaScript lets you execute code when events are detected.
-
# JavaScript Strings
- for storing text
- written with quotes
- Template quotes `"strings"`
- text.length = to find length of the string
  - Escape sequences
    - \b - Backspace
    - \f - Form feed
    - \n - new line
    - \r - carriage return
    - \t - horizontal tabulator
    - \v -vertical tabulator
    
- to make a string to object : use the keyword new
- == : conditional opperator. to check if  condition is true
- === : strict. returns true only if datatype and value is equal
  
# JavaScript String Methods
- text.length
- text.charAt(0)
- text.charCodeAt(0)
- name.at(2)
- at() method returns the character at a specified index (position) in a string.
- at() method is a new addition to JavaScript.
- It allows the use of negative indexes while charAt() do not.
- slice() extracts a part of a string and returns the extracted part in a new string.
- - substring() is similar to slice().
- The difference is that start and end values less than 0 are treated as 0 in substring().
- substr() is similar to slice().
- The difference is that the second parameter specifies the length of the extracted part.
- A string is converted to upper case with toUpperCase()
- A string is converted to lower case with toLowerCase()
- concat() joins two or more strings
- The concat() method can be used instead of the plus operator. These two lines do the same
- The trim() method removes whitespace from both sides of a string
- The trimStart() method works like trim(), but removes whitespace only from the start of a string.
- The trimEnd() method works like trim(), but removes whitespace only from the end of a string.
- he padStart() method pads a string from the start.
- It pads a string with another string (multiple times) until it reaches a given length.
- The padEnd() method pads a string from the end.
- It pads a string with another string (multiple times) until it reaches a given length.
- The repeat() method returns a string with a number of copies of a string.
- The repeat() method returns a new string.
- The repeat() method does not change the original string.
- The replace() method replaces a specified value with another value in a string
- The replaceAll() method allows you to specify a regular expression instead of a string to be replaced.
- If the parameter is a regular expression, the global flag (g) must be set, otherwise a TypeError is thrown.
- A string can be converted to an array with the split() method
- 
# JavaScript String Search
 -  String indexOf()
 -  String lastIndexOf()
 -  String search()
 -  The indexOf() method returns the index (position) of the first occurrence of a string in a string, or it returns -1 if the string is not found
 -  The lastIndexOf() method returns the index of the last occurrence of a specified text in a string
 -  The search() method searches a string for a string (or a regular expression) and returns the position of the match
 -  The search() method cannot take a second start position argument.
 -  The indexOf() method cannot take powerful search values (regular expressions)
 -  The match() method returns an array containing the results of matching a string against a string (or a regular expression)
 -  The matchAll() method returns an iterator containing the results of matching a string against a string (or a regular expression)
 -  The includes() method returns true if a string contains a specified value.
 -  The startsWith() method returns true if a string begins with a specified value.
 -  The endsWith() method returns true if a string ends with a specified value.
 -  
# JavaScript Template Strings
- Template Strings use back-ticks (``) rather than the quotes ("") to define a string
- Template Strings allow both single and double quotes inside a string
- Automatic replacing of expressions with real values is called string interpolation.
- Template Strings allow variables in strings
- Template Strings allow expressions in strings
- 
# JavaScript Numbers
- JavaScript has only one type of number. Numbers can be written with or without decimals.
- NaN is a JavaScript reserved word indicating that a number is not a legal number.Trying to do arithmetic with a non-numeric string will result in NaN (Not a Number)
- Infinity (or -Infinity) is the value JavaScript will return if you calculate a number outside the largest possible number.
- JavaScript interprets numeric constants as hexadecimal if they are preceded by 0x.
- 
# JavaScript BigInt
- JavaScript BigInt variables are used to store big integer values that are too big to be represented by a normal JavaScript Number.
- The JavaScript typeof a BigInt is "bigint"
- 
# JavaScript Number Methods
These number methods can be used on all JavaScript numbers:
toString():	Returns a number as a string
toExponential():	Returns a number written in exponential notation
toFixed():	Returns a number written with a number of decimals
toPrecision():	Returns a number written with a specified length
valueOf():	Returns a number as a number
# JavaScript Number Properties
- EPSILON:	The difference between 1 and the smallest number > 1.
- MAX_VALUE:	The largest number possible in JavaScript
- MIN_VALUE:	The smallest number possible in JavaScript
- MAX_SAFE_INTEGER:	The maximum safe integer (253 - 1)
- MIN_SAFE_INTEGER:	The minimum safe integer -(253 - 1)
- POSITIVE_INFINITY:	Infinity (returned on overflow)
- NEGATIVE_INFINITY:	Negative infinity (returned on overflow)
- NaN:	A "Not-a-Number" value

# JavaScript Arrays
- An array is a special variable, which can hold more than one value
- 
# JavaScript Array Methods
- Array length: The length property returns the length (size) of an array
- Array toString(): The JavaScript method toString() converts an array to a string of (comma separated) array values.
- Array at(): The at() method returns an indexed element from an array
- Array join(): The join() method also joins all array elements into a string. It behaves just like toString(), but in addition you can specify the separator
- Array pop(): The pop() method removes the last element from an array
- Array push(): The push() method adds a new element to an array (at the end)
- The shift() method removes the first array element and "shifts" all other elements to a lower index.
- The shift() method returns the value that was "shifted out"
- The unshift() method adds a new element to an array (at the beginning), and "unshifts" older elements
- The length property provides an easy way to append a new element to an array
- The concat() method creates a new array by merging (concatenating) existing arrays
- The concat() method can also take strings as arguments
- The copyWithin() method copies array elements to another position in an array
- Flattening an array is the process of reducing the dimensionality of an array.
- Flattening is useful when you want to convert a multi-dimensional array into a one-dimensional array.
- The flat() method creates a new array with sub-array elements concatenated to a specified depth.
- The splice() method adds new items to an array.
- The slice() method slices out a piece of an array.
- The splice() method can be used to add new items to an arrayThe splice() method can be used to add new items to an array
- The slice() method slices out a piece of an array into a new array
- JavaScript automatically converts an array to a comma separated string when a primitive value is expected.


# JavaScript Array Search
- Array indexOf(): The indexOf() method searches an array for an element value and returns its position.
- Array lastIndexOf(): Array.lastIndexOf() is the same as Array.indexOf(), but returns the position of the last occurrence of the specified element.
- Array includes(): This allows us to check if an element is present in an array (including NaN, unlike indexOf).
- The find() method returns the value of the first array element that passes a test function.
- The findIndex() method returns the index of the first array element that passes a test function.
- findLast() method that will start from the end of an array and return the value of the first element that satisfies a condition.
- The findLastIndex() method finds the index of the last element that satisfies a condition.
- 
# JavaScript Sorting Arrays
- Array sort(): The sort() method sorts an array alphabetically
- Array reverse(): The reverse() method reverses the elements in an array
- Array toSorted(): creates a new array, keeping the original array unchanged
- Array toReversed(): creates a new array, keeping the original array unchanged
- Sorting Objects

- 
# JavaScript Array Iteration
- Array forEach: The forEach() method calls a function (a callback function) once for each array element.
- Array map(): The map() method creates a new array by performing a function on each array element. The map() method does not execute the function for array elements without values.The map() method does not change the original array.
- Array flatMap(): The flatMap() method first maps all elements of an array and then creates a new array by flattening the array.
- Array filter(): The filter() method creates a new array with array elements that pass a test.
- Array reduce(): The reduce() method runs a function on each array element to produce (reduce it to) a single value.
- Array reduceRight(): The reduceRight() method runs a function on each array element to produce (reduce it to) a single value.
- The every() method checks if all array values pass a test.
- The some() method checks if some array values pass a test.
- The Array.from() method returns an Array object from any object with a length property or any iterable object.
- The Array.keys() method returns an Array Iterator object with the keys of an array.
- 
# JavaScript Array Const
- An array declared with const cannot be reassigned
- The keyword const is a little misleading.
- # Const Block Scope
   - An array declared with const has Block Scope.
 
   - 

# JavaScript Date Objects
- By default, JavaScript will use the browser's time zone and display a date as a full text string:
eg
Fri Apr 26 2024 02:15:23 GMT-0400 (Eastern Daylight Time)
- Date objects are created with the new Date() constructor.
- There are 9 ways to create a new date object:
- new Date()
- new Date(date string)
- new Date(year,month)
- new Date(year,month,day)
- new Date(year,month,day,hours)
- new Date(year,month,day,hours,minutes)
- new Date(year,month,day,hours,minutes,seconds)
- new Date(year,month,day,hours,minutes,seconds,ms)
- new Date(milliseconds)
- new Date() creates a date object with the current date and time
- new Date(date string) creates a date object from a date string
- new Date(year, month, ...) creates a date object with a specified date and time
- JavaScript will (by default) output dates using the toString() method.
- When you display a date object in HTML, it is automatically converted to a string, with the toString() method.
- The toDateString() method converts a date to a more readable format
- The toUTCString() method converts a date to a string using the UTC standard
- The toISOString() method converts a date to a string using the ISO standard
- 



# JavaScript Date Formats
- There are generally 3 types of JavaScript date input formats
- ISO Date: "2015-03-25" ("International Standard")
- Short Date: "03/25/2015"
- Long Date: "Mar 25 2015" or "25 Mar 2015"
- ISO format follows a strict standard in JavaScript
- JavaScript will always output the browser's time zone.
- date,parse(): used to convert a valid date string to milliseconds
# JavaScript Get Date Methods
- date objects are created with new Date()
- new Date(): returns a date object with the current date and time
- getFullYear():	Get year as a four digit number (yyyy)
- getMonth():	Get month as a number (0-11)
- getDate():	Get day as a number (1-31)
- getDay():	Get weekday as a number (0-6)
- getHours():	Get hour (0-23)
- getMinutes():	Get minute (0-59
- getSeconds():	Get second (0-59)
- getMilliseconds():	Get millisecond (0-999)
- getTime():	Get time (milliseconds since January 1, 1970)
- date.now():  returns the number of milliseconds since January 1, 1970.
- getUTCDate():	getDate():	Returns the UTC date
- getUTCFullYear():	getFullYear():	Returns the UTC year
- getUTCMonth():	getMonth():	Returns the UTC month
- getUTCDay():	getDay():	Returns the UTC day
- getUTCHours():	getHours():	Returns the UTC hou
- getUTCMinutes():	getMinutes():	Returns the UTC minutes
- getUTCSeconds():	getSeconds():	Returns the UTC seconds
- getUTCMilliseconds():	getMilliseconds():	Returns the UTC milliseconds
- getTimezoneOffset(): returns the difference (in minutes) between local time an UTC time
- 
# JavaScript Set Date Methods
- Set Date methods let you set date values (years, months, days, hours, minutes, seconds, milliseconds) for a Date Object.
- setDate():	Set the day as a number (1-31)
- setFullYear():	Set the year (optionally month and day)
- setHours():	Set the hour (0-23)
- setMilliseconds():	Set the milliseconds (0-999)
- setMinutes():	Set the minutes (0-59)
- setMonth():	Set the month (0-11)
- setSeconds():	Set the seconds (0-59)
- setTime():	Set the time (milliseconds since January 1, 1970)
# JavaScript Math Object
- allows you to perfomr mathematical tasks on numbers.
- is static. has no constructor.
- syntax: Math.property
- Math.E         returns Euler's number
- Math.PI        returns PI
- Math.SQRT2     returns the square root of 2
- Math.SQRT1_2  returns the square root of 1/2
- Math.LN2      returns the natural logarithm of 2
- Math.LN10      returns the natural logarithm of 1
- Math.LOG2E     returns base 2 logarithm of E
- Math.LOG10E    returns base 10 logarithm of E
  # Number to Integer
  - Math.round(x)	Returns x rounded to its nearest intege
  - Math.ceil(x)	Returns x rounded up to its nearest integer
  - Math.floor(x)	Returns x rounded down to its nearest integer
  - Math.trunc(x)	Returns the integer part of x (new in ES6)
  - Math.sign(x) returns if x is negative, null or positive
  - Math.pow(x, y) returns the value of x to the power of y
  - Math.sqrt(x) returns the square root of x
  - Math.abs(x) returns the absolute (positive) value of x
  - Math.sin(x) returns the sine (a value between -1 and 1) of the angle x (given in radians).
  - Angle in radians = Angle in degrees x PI / 180.
  - Math.cos(x) returns the cosine (a value between -1 and 1) of the angle x (given in radians)
  - Math.min() and Math.max() can be used to find the lowest or highest value in a list of arguments
  - Math.random() returns a random number between 0 (inclusive), and 1 (exclusive)
  - Math.log(x) returns the natural logarithm of x
  - Math.log2(x) returns the base 2 logarithm of x
  - Math.log10(x) returns the base 10 logarithm of x
  - abs(x)	Returns the absolute value of x
  - acos(x)	Returns the arccosine of x, in radians
  - acosh(x)	Returns the hyperbolic arccosine of x
  - asin(x)	Returns the arcsine of x, in radians
  - asinh(x)	Returns the hyperbolic arcsine of x
  - atan(x)	Returns the arctangent of x as a numeric value between -PI/2 and PI/2 radians
  - atan2(y, x)	Returns the arctangent of the quotient of its arguments
  - atanh(x)	Returns the hyperbolic arctangent of x
  - cbrt(x)	Returns the cubic root of x
  - ceil(x)	Returns x, rounded upwards to the nearest integer
  - cos(x)	Returns the cosine of x (x is in radians)
  - cosh(x)	Returns the hyperbolic cosine of x
  - exp(x)	Returns the value of Ex
  - floor(x)	Returns x, rounded downwards to the nearest integer
  - log(x)	Returns the natural logarithm (base E) of x
  - max(x, y, z, ..., n)	Returns the number with the highest value
  - min(x, y, z, ..., n)	Returns the number with the lowest value
  - pow(x, y)	Returns the value of x to the power of y
  - random()	Returns a random number between 0 and 1
  - round(x)	Rounds x to the nearest integer
  - sign(x)	Returns if x is negative, null or positive (-1, 0, 1)
  - sin(x)	Returns the sine of x (x is in radians)
  - sinh(x)	Returns the hyperbolic sine of x
  - sqrt(x)	Returns the square root of x
  - tan(x)	Returns the tangent of an angle
  - tanh(x)	Returns the hyperbolic tangent of a number
  - trunc(x)	Returns the integer part of a number (x)
  
# JavaScript Random
- Math.random(): returns a random number between 0 (inclusive),  and 1 (exclusive)
- Math.random() used with Math.floor() can be used to return random integers
- This JavaScript function always returns a random number between min (included) and max (excluded)
- This JavaScript function always returns a random number between min and max (both included)
- 
# JavaScript Booleans
- A JavaScript Boolean represents one of two values: true or false.
- ou will need a data type that can only have one of two values, like
- YES / NO
- ON / OFF
- TRUE / FALSE
- booleans can also be defined as objects with the keyword new
- Comparing two JavaScript objects always return false.
- 
# JavaScript Comparison and Logical Operators
- Comparison and Logical operators are used to test for true or false.
- Comparison operators are used in logical statements to determine equality or difference between variables or values.
- ==	equal to
- ===	equal value and equal type
- !=	not equal
- !==	not equal
- 	>	greater than
- <	less than
- >=	greater than or equal to	
<=	less than or equal to
- Comparison operators can be used in conditional statements to compare values and take action depending on the result
- Logical operators are used to determine the logic between variables or values
- The ?? operator returns the first argument if it is not nullish (null or undefined).
- The ?. operator returns undefined if an object is undefined or null (instead of throwing an error).
- 
# JavaScript if, else, and else if
- Conditional statements are used to perform different actions based on different conditions.
- Use if to specify a block of code to be executed, if a specified condition is true
- Use else to specify a block of code to be executed, if the same condition is false
- Use else if to specify a new condition to test, if the first condition is false
- Use switch to specify many alternative blocks of code to be executed
- 
# JavaScript Switch Statement
- The switch statement is used to perform different actions based on different conditions.
- Use the switch statement to select one of many code blocks to be executed.
- The switch expression is evaluated once.
- The value of the expression is compared with the values of each case.
- If there is a match, the associated block of code is executed.
- If there is no match, the default code block is executed.
- When JavaScript reaches a break keyword, it breaks out of the switch block.
- The default keyword specifies the code to run if there is no case match
- If multiple cases matches a case value, the first case is selected.
- If no matching cases are found, the program continues to the default label.
- If no default label is found, the program continues to the statement(s) after the switch.
-   
# JavaScript For Loop
- Loops can execute a block of code a number of times
- The for statement creates a loop with 3 optional expressions:
for (expression 1; expression 2; expression 3) {
  // code block to be executed
}
Expression 1 is executed (one time) before the execution of the code block.
Expression 2 defines the condition for executing the code block.
- expression 1 to initialize the variable used in the loop (let i = 0)
- expression 2 is used to evaluate the condition of the initial variable
- expression 3 increments the value of the initial variable
- using var, the variable declared in the loop redeclares the variable outside the loop.
- using let, the variable declared in the loop does not redeclare the variable outside the loop.
Expression 3 is executed (every time) after the code block has been executed.
# JavaScript For In
- The JavaScript for in statement loops through the properties of an Object
- The JavaScript for in statement can also loop over the properties of an Array
- he forEach() method calls a function (a callback function) once for each array element
- 
# JavaScript For Of
-  JavaScript for of statement loops through the values of an iterable object.
-  
# JavaScript While Loop
-  JavaScript for of statement loops through the values of an iterable object.
-  The do while loop is a variant of the while loop. This loop will execute the code block once, before checking if the condition is true, then it will repeat the loop as long as the condition is true.
# JavaScript Break and Continue
- The break statement "jumps out" of a loop.
- The continue statement "jumps over" one iteration in the loop.
- The continue statement breaks one iteration (in the loop), if a specified condition occurs, and continues with the next iteration in the loop.
- The break and the continue statements are the only JavaScript statements that can "jump out of" a code block.
- The continue statement (with or without a label reference) can only be used to skip one loop iteration.
- The break statement, without a label reference, can only be used to jump out of a loop or a switch.
- With a label reference, the break statement can be used to jump out of any code block
# JavaScript Iterables
- The JavaScript for..of statement loops through the elements of an iterable object.
- means looping over a sequence of elements.
- use a for..of loop to iterate over the elements of a string
- use a for..of loop to iterate over the elements of an Array
- use a for..of loop to iterate over the elements of a Set
- The iterator protocol defines how to produce a sequence of values from an object.
- An object becomes an iterator when it implements a next() method
- The next() method must return an object with two properties:
- value (the next value)
- done (true or false)
- The iterator protocol defines how to produce a sequence of values from an object.
- An object becomes an iterator when it implements a next() method.
- The next() method must return an object with two properties:
- value (the next value)
- done (true or false)
- A JavaScript iterable is an object that has a Symbol.iterator.
- The Symbol.iterator is a function that returns a next() function.
- An iterable can be iterated over with the code: for (const x of iterable) { }
- The Symbol.iterator method is called automatically by for..of.

- 

# JavaScript Sets
- A JavaScript Set is a collection of unique values.
- Each value can only occur once in a Set.
- How to Create a Set
- Passing an Array to new Set()
- Create a new Set and use add() to add values
- Create a new Set and use add() to add variables
- Pass an Array to the new Set() constructor

- new Set()	Creates a new Set
- add()	Adds a new element to the Set
- delete()	Removes an element from a Set
- has()	Returns true if a value exists
- clear()	Removes all elements from a Set
- forEach()	Invokes a callback for each element
- values()	Returns an Iterator with all the values in a Set
- keys()	Same as values()
- entries()	Returns an Iterator with the [value,value] pairs from a Set
- 
# JavaScript Maps
- Passing an Array to new Map()
- Create a Map and use Map.set()
- The set() method can also be used to change existing Map values
- The get() method gets the value of a key in a Ma
- The size property returns the number of elements in a Map
- The delete() method removes a Map element
- The clear() method removes all the elements from a Map
- The has() method returns true if a key exists in a Map
- The forEach() method invokes a callback for each key/value pair in a Map
- The entries() method returns an iterator object with the [key,values] in a Map
- The keys() method returns an iterator object with the keys in a Map
- The values() method returns an iterator object with the values in a Map
- A primitive data value is a single simple data value with no additional properties and methods.

# JavaScript typeof
- Datatypes: Object
Date
Array
String
Number
Boolean
- 2 data types that cannot contain values:
null
undefined
- In JavaScript, a variable without a value, has the value undefined. The type is also undefined.
- The typeof operator can return one of these primitive types:
string
number
boolean
undefined
- Complex Data
The typeof operator can return one of two complex types:
function
object
The typeof operator returns "object" for objects, arrays, and null.
The typeof operator does not return "object" for functions.
- The typeofoperator is not a variable. It is an operator. Operators ( + - * / ) do not have any data type.
- The constructor property returns the constructor function for all JavaScript variables.
- An empty value has nothing to do with undefined.
- An empty string has both a legal value and a type
- undefined and null are equal in value but different in type
- The instanceof operator returns true if an object is an instance of the specified object
- The void operator evaluates an expression and returns undefined.
- 

# JavaScript Type Conversion
- By the use of a JavaScript function
Automatically by JavaScript itself
- Converting Strings to Numbers: global method Number() converts a variable (or a value) into a number.
  - Number()	Returns a number, converted from its argument
parseFloat()	Parses a string and returns a floating point number
parseInt()	Parses a string and returns an integer
- Converting Numbers to Strings: The unary + operator can be used to convert a variable to a number
- Converting Dates to Numbers: global method String() can convert numbers to strings.
It can be used on any type of numbers, literals, variables, or expressions
The Number method toString() does the same.
toExponential():	Returns a string, with a number rounded and written using exponential notation.
toFixed():	Returns a string, with a number rounded and written with a specified number of decimals.
toPrecision(): Returns a string, with a number written with a specified length
The global method Number() can be used to convert dates to numbers.
The global method String() can convert dates to strings.
- Converting Numbers to Dates: 
- Converting Booleans to Numbers:
- The global method Number() can also convert booleans to numbers.
- The global method String() can convert booleans to strings.
- Converting Numbers to Booleans:
- JavaScript automatically calls the variable's toString() function when you try to "output" an object or a variable
# JavaScript Bitwise Operations

# JavaScript Regular Expressions
- A regular expression is a sequence of characters that forms a search pattern.
- The search pattern can be used for text search and text replace operations.
- A regular expression is a sequence of characters that forms a search pattern.
- The search() method uses an expression to search for a match, and returns the position of the match.
- The replace() method returns a modified string where the pattern is replaced.
- The search() method searches a string for a specified value and returns the position of the match
- Modifiers can be used to perform case-insensitive more global searches
- Brackets are used to find a range of characters
- The test() method is a RegExp expression method.
- It searches a string for a pattern, and returns true or false, depending on the result.
- The exec() method is a RegExp expression method.
- It searches a string for a specified pattern, and returns the found text as an object.
- If no match is found, it returns an empty (null) object.
# JavaScript Operator Precedence
- Operator precedence describes the order in which operations are performed in an arithmetic expression.
- Multiplication (*) and division (/) have higher precedence than addition (+) and subtraction (-).
- 
# JavaScript Errors
- The try statement defines a code block to run (to try).
- The catch statement defines a code block to handle any error.
- The finally statement defines a code block to run regardless of the result.
- The throw statement defines a custom error.
- The try statement allows you to define a block of code to be tested for errors while it is being executed.
- The catch statement allows you to define a block of code to be executed, if an error occurs in the try block.
- The JavaScript statements try and catch come in pairs
- JavaScript will actually create an Error object with two properties: name and message.
- The throw statement allows you to create a custom error.
- Technically you can throw an exception (throw an error).
- The exception can be a JavaScript String, a Number, a Boolean or an Object
- The exception (err) is caught by the catch statement and a custom error message is displayed
- The finally statement lets you execute code, after try and catch, regardless of the result
- A RangeError is thrown if you use a number that is outside the range of legal values.
- A ReferenceError is thrown if you use (reference) a variable that has not been declared
- A TypeError is thrown if an operand or argument is incompatible with the type expected by an operator or function
- A URIError is thrown if you use illegal characters in a URI function
- 
# JavaScript Scope
- Scope determines the accessibility (visibility) of variables.
- JavaScript variables have 3 types of scope:
Block scope
Function scope
Global scope
- JavaScript variables had only Global Scope and Function Scope.
- ES6 introduced two important new JavaScript keywords: let and const.
- These two keywords provide Block Scope in JavaScript.
- Variables declared inside a { } block cannot be accessed from outside the block
- Variables declared with the var keyword can NOT have block scope.
- Variables declared inside a { } block can be accessed from outside the block
- Variables declared within a JavaScript function, are LOCAL to the function
- Local variables have Function Scope:
- They can only be accessed from within the function.
- Variables defined inside a function are not accessible (visible) from outside the function.
- Variables declared with var, let and const are quite similar when declared inside a function.
- A variable declared outside a function, becomes GLOBAL.
- Variables declared Globally (outside any function) have Global Scope.
- Global variables can be accessed from anywhere in a JavaScript program.
- Variables declared with var, let and const are quite similar when declared outside a block.
- In "Strict Mode", undeclared variables are not automatically global.
- Global variables defined with the let keyword do not belong to the window object
- The lifetime of a JavaScript variable starts when it is declared.
- Function (local) variables are deleted when the function is completed.
- Function arguments (parameters) work as local variables inside functions.
# JavaScript Hoisting
-  Variables defined with let and const are hoisted to the top of the block, but not initialized.
-  Using a let variable before it is declared will result in a ReferenceError.
-  The variable is in a "temporal dead zone" from the start of the block until it is declared
-  JavaScript only hoists declarations, not initializations

-  
# JavaScript Use Strict
-  "use strict"; Defines that JavaScript code should be executed in "strict mode"
-  The purpose of "use strict" is to indicate that the code should be executed in "strict mode".
- Strict mode is declared by adding "use strict"; to the beginning of a script or a function.
- Declared at the beginning of a script, it has global scope (all code in the script will execute in strict mode)
- purpose of "use strict" is to indicate that the code should be executed in "strict mode".
- Strict mode is declared by adding "use strict"; to the beginning of a script or a function.
- Declared at the beginning of a script, it has global scope (all code in the script will execute in strict mode)
- Strict mode makes it easier to write "secure" JavaScript.
- Strict mode changes previously accepted "bad syntax" into real errors.
- Using an object, without declaring it, is not allowed
- Deleting a variable (or object) is not allowed.
- Deleting a function is not allowed.
- Duplicating a parameter name is not allowed
- Octal numeric literals are not allowed
- Octal escape characters are not allowed

# The JavaScript this Keyword
-  In JavaScript, the this keyword refers to an object.
-  Which object depends on how this is being invoked (used or called).
-  The this keyword refers to different objects depending on how it is used
-  In JavaScript, the this keyword refers to an object.
-  Which object depends on how this is being invoked (used or called).
-  The this keyword refers to different objects depending on how it is used
-  When used in an object method, this refers to the object.
-  In the example on top of this page, this refers to the person object.
-  Because the fullName method is a method of the person object.
-  When used alone, this refers to the global object.
-  Because this is running in the global scope.
-  In a browser window the global object is [object Window]
-  when used in a function, in strict mode, this is undefined
-  this refers to the HTML element that received the event
-  The call() and apply() methods are predefined JavaScript methods.
-  They can both be used to call an object method with another object as argument
-  With the bind() method, an object can borrow a method from another object.
-  
# JavaScript Arrow Function
- Arrow functions allow us to write shorter function syntax
- The handling of this is also different in arrow functions compared to regular functions.
- In regular functions the this keyword represented the object that called the function, which could be the window, the document, a button or whatever.
- With arrow functions the this keyword always represents the object that defined the arrow function.
# JavaScript Classes
- Use the keyword class to create a class.
- Always add a method named constructor().
- A JavaScript class is not an object.
- It is a template for JavaScript objects.
- The constructor method is a special method:
- It has to have the exact name "constructor"
- It is executed automatically when a new object is created
- It is used to initialize object properties
- Use the keyword class to create a class.
- Always add a constructor() method.
# JavaScript Modules
- JavaScript modules allow you to break up your code into separate files.
- Modules are imported from external files with the import statement.
- Modules with functions or variables can be stored in any external file.
- There are two types of exports: Named Exports and Default Exports.
- You can import modules into a file in two ways, based on if they are named exports or default exports.
- Named exports are constructed using curly braces. Default exports are not.

# JavaScript JSON
- JSON is a format for storing and transporting data.
- JSON is often used when data is sent from a server to a web page.
- JSON stands for JavaScript Object Notation
- JSON is a lightweight data interchange format
- JSON is language independent *
- JSON is "self-describing" and easy to understand
- The JSON format is syntactically identical to the code for creating JavaScript objects.
- JSON data is written as name/value pairs, just like JavaScript object properties
- A name/value pair consists of a field name (in double quotes), followed by a colon, followed by a value
- JSON objects are written inside curly braces.
- JSON arrays are written inside square brackets.
- A common use of JSON is to read data from a web server, and display the data in a web page.
- 
# JavaScript Debugging
- Programming code might contain syntax errors, or logical errors.
- Many of these errors are difficult to diagnose.
- Searching for (and fixing) errors in programming code is called code debugging.
- Built-in debuggers can be turned on and off, forcing errors to be reported to the user.
- If your browser supports debugging, you can use console.log() to display JavaScript values in the debugger window.
- Setting Breakpoints
- The debugger keyword stops the execution of JavaScript, and calls (if available) the debugging function.
- This has the same function as setting a breakpoint in the debugger.
- Normally, you activate debugging in your browser with F12, and select "Console" in the debugger menu.
# JavaScript Style Guide
- Coding conventions are style guidelines for programming. They typically cover:
- Naming and declaration rules for variables and functions.
- Rules for the use of white space, indentation, and comments.
- Programming practices and principles.
- Coding conventions secure quality:
Improve code readability
Make code maintenance easier
- 
# JavaScript Best Practices
- Minimize the use of global variables.
- This includes all data types, objects, and functions.
- Global variables and functions can be overwritten by other scripts.
- All variables used in a function should be declared as local variables.
- Local variables must be declared with the var, the let, or the const keyword, otherwise they will become global variables.
# JavaScript Common Mistakes
- Accidentally Using the Assignment Operator
- Expecting Loose Comparison
- Confusing Addition & Concatenation
- Misunderstanding Floats
- Breaking a JavaScript String
- Misplacing Semicolon
- Breaking a Return Statement
  
# JavaScript Performance
- Reduce Activity in Loops
- Reduce DOM Access
- Reduce DOM Size
- Avoid Unnecessary Variables
- Delay JavaScript Loading
- Avoid Using with
  
# JavaScript Reserved Words
- In JavaScript you cannot use the reserved words as variables, labels, or function names
- JavaScript is often used together with Java. You should avoid using some Java objects and properties as JavaScript identifiers
- avoid using the name of all HTML event handlers.
