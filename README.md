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

# JavaScript Array Methods

# JavaScript Array Search

# JavaScript Sorting Arrays

# JavaScript Array Iteration

# JavaScript Array Const

# JavaScript Date Objects

# JavaScript Date Formats

# JavaScript Get Date Methods

# JavaScript Set Date Methods

# JavaScript Math Object

# JavaScript Random

# JavaScript Booleans

# JavaScript Comparison and Logical Operators

# JavaScript if, else, and else if

# JavaScript Switch Statement

# JavaScript For Loop

# JavaScript For In

# JavaScript For Of

# JavaScript While Loop

# JavaScript Break and Continue

# JavaScript Iterables

# JavaScript Sets

# JavaScript Maps

# JavaScript typeof

# JavaScript Type Conversion

# JavaScript Bitwise Operations

# JavaScript Regular Expressions

# JavaScript Operator Precedence

# JavaScript Errors

# JavaScript Scope

# JavaScript Hoisting

# JavaScript Use Strict

# The JavaScript this Keyword

# JavaScript Arrow Function

# JavaScript Classes

# JavaScript Modules

# JavaScript JSON

# JavaScript Debugging

# JavaScript Style Guide

# JavaScript Best Practices

# JavaScript Common Mistakes

# JavaScript Performance

# JavaScript Reserved Words
