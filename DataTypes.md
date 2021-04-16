# Data Types

Every variable in a Swift program must have a data type. This section covers Swift's primitive data types.

## Integers

An integer is a counting number, such as 2, 5, 39, or 481. Use integers for numerical values that you want to perform math operations on, such as adding, substracting, multiplying, and comparing. A phone number is an example of data you would not store as an integer. You don't add two phone numbers.

Swift has two kinds of integers: unsigned and signed. Unsigned integers do not have negative values while signed integers can have negative values.

A signed integer's type name is `Int`. An unsigned integer's type name is `UInt`.

## Floating-Point Numbers

Floating-point numbers can have fractional values, such as 2.6 or 25.942.

Swift has two floating-point data types:`Float` and `Double`. A double can store more decimal places than a float. If you are doing floating-point calculations that require high accuracy, use doubles.

## Boolean

A Boolean value has two possible values: true or false. A Boolean value's type name is `Bool`.

Swift programs generally do not have many Boolean variables. The main use of Boolean values is to check if a condition is true.

# Character

A character stores a single character, such as `R`. Swift programs rarely deal with individual characters. They usually deal with strings, which are a collection of characters. Read the [Strings](Strings) section to learn more about strings.
