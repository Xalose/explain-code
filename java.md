[Back](./index.html)

# Introduction
Java is an Object-oriented programming language
# Basics
### Outputting to console
```Java
System.out.println("This can be a string, or a number like "+13);
```
### Primitives

|Data Type|Size|Description|
|-|-|-|
|byte|1 byte|Stores whole numbers from -128 to 127|
|short|2 bytes|Stores whole numbers from -32,768 to 32,767|
|int|4 bytes|Stores whole numbers from -2,147,483,648 to 2,147,483,647|
|long|8 bytes|Stores whole numbers from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807|
|float|4 bytes|Stores fractional numbers. Sufficient for storing 6 to 7 decimal digits|
|double|8 bytes|Stores fractional numbers. Sufficient for storing 15 decimal digits|
|boolean|1 bit|Stores true or false values|
|char|2 bytes|Stores a single character/letter or ASCII values|

### Operators

|Operator|Name|Description|Example|
| - | - | - | - |
|+|Addition|Adds together two values|x + y|
|-|Subtraction|Subtracts one value from another|x - y|
|*|Multiplication|Multiplies two values|x * y|
|/|Division|Divides one value by another|x / y|
|%|Modulus|Returns the division remainder|x % y|
|++|Increment|Increases the value of a variable by 1|++x|
|--|Decrement|Decreases the value of a variable by 1|--x|

### If, Else If, Else
```Java
if (condition1) {
  // block of code to be executed if condition1 is true
} else if (condition2) {
  // block of code to be executed if the condition1 is false and condition2 is true
} else {
  // block of code to be executed if the condition1 is false and condition2 is false
}
```

### While loop
```Java
while (condition) {
  // code block to be executed
}
```

### For loop
```Java
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
```
# Methods
A method is a block of code which only runs when it is called.

You can pass data, known as parameters, into a method.

Methods are used to perform certain actions, and they are also known as functions.
# Classes
