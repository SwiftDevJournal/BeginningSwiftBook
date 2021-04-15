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

## Function Arguments

Function arguments go in parentheses after the name of the function. A function argument has three parts.

* The name of the argument
* A colon
* The data type of the argument

Let's look at a simple function that takes one argument.

	func greet(name: String) {
		print(“Hello, " + "\(name)”)
	}

The `greet` function takes one argument, the name of the person to greet. The name is a string.

The function prints the string `Hello, ` followed by the name of the person. To print the name of a variable, you must start with the backslash character followed by the variable name in parentheses.

## Calling a Function

To call a function in your code, type the name of the function and put the arguments in parentheses.

	greet(name: "Godfrey")
	
## Multiple Function Arguments

If your function takes multiple arguments, use commas to separate the arguments. Let's add a `greeting` argument to the `greet` function.

	func greet(greeting: String, name: String) {
		print("\(greeting)" + ", " + "\(name)")
	}
	
Let's call the function.

	greet(greeting: "Hi", name: "Charlene")
	
## Returning a Value

To have a function return a value, enter the characters `->` followed by the type of data to return.

	func triple(value: Int) -> Int {
		return value * 3
	}

Functions that return a value require a `return` statement that returns the value.

Let's call the function.

	let tripleOfFour - triple(value: 4)
	
