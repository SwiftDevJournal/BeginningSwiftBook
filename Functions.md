# Functions

Functions are the verbs in a Swift program.

## Parts of a Function

A function has the following parts:

* It starts with the keyword `func`.
* The name of the function. It must start with a letter. There can be no spaces in the function name.
* A list of arguments the functions takes. A function may have no arguments.
* The return type of the function.
* The body of the function in braces.

## The Simplest Function

The simplest function is a function that takes no arguments, returns nothing, and does nothing.

	func doNothing() {

	}
	
Swift convention is for the first word of a function name to be lowercase and the other words to be uppercase.

## Returning a Value

To have a function return a value, enter the characters `->` followed by the type of data to return.

	func three() -> Int {
		return 3
	}

Functions that return a value have a `return` statement that returns the value.

Let's call the function.

	let x = 3

## Function Arguments

Function arguments go in parentheses after the name of the function. A function argument has three parts.

* The name of the argument
* A colon
* The data type of the argument

Let's look at a simple function that takes one argument.

	func triple(value: Int) -> Int {
		return value * 3
	}

The `triple` function takes one argument, the value to triple. The value is an integer along with the return value.

	let tripleFour = triple(value: 4)
	
## Multiple Function Arguments

If your function takes multiple arguments, use commas to separate the arguments. 

	func multiply(x: Int, y: Int) -> Int {
		return x * y
	}

The function multiplies x by y and returns the product. Let's call the function.

	let z = multiply(x, y)
	