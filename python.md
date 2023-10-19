[Back](./index.html)
# Python

## Intro 

Python is a high level programming language that is commonly used due to its simplicity and readability.
Python is commonly used for servers to create web applications, create workflows, databases, handle big data and perform complex mathematics.
Python works on Windows, Mac, Linux, Raspberry Pi, etc.
Simple syntax that is similar to the English language. 
Download VScode + python
How to setup Python for VSCode in 2023 in 5mins! | Install Python and Setup VSCode for Windows 10 - YouTube

## Syntax 
### Printing
```Python
print(“hello world”)
```
important = for anything string you want to output, you will need double quotation marks.
### Indentation 
for any functions or methods that you want to execute within a loop, the method must be indented within the loop.
Wrong:
```Python
if 4>2:
print (“wrong")
```
Correct:
```Python
if 4>2:
  print (“correct”)
```
### Commenting
comments start with a hashtag (#)
```Python
#this is a comment
```
## Variables 
a variable is a named reference to a value
```Python
x = 5
x = “jeff”
print (x)
```
### Casting
Setting a variable to a specific data type (basic ones)
- int
- float
- str 
- bool	
```Python
x = str(3)
```
  
```Python
x = 7
print (type(x))
```

## Data Types

|Type|Data|
|-|-|
|Text|str|
|Numeric|int, float, complex|
|Sequence|list, tuple, range|
|Mapping|dict|
|Set|set, frozenset|
|Boolean|bool|
|Binary|bytes, bytearray, memoryview|
|None|NoneType|



### Numbers 
There are three numeric types in python: int, float, complex 
```Python
x = 2 #int
y = 7.2 #float
z = 1j #complex
```

### Strings
Strings in python are surrounded by quotation marks or double quotation marks, ‘’ or “”
```Python
x="this is a string"
y='this is too'
```

### Boolean
Boolean represents either true or false
Booleans are often used to set requirements
```Python
print(4>3)
print(3>4)
```
### Operators

|Operator|Name|Example|
|-|-|
|+|addition|x+y|
|-|subtraction|x-y|
|\*|multiplication|x*y|
|/|division|x/y|
|%|modulus|x%y|
|//|floor division|x//y|


|Operator|Example|Same as|
|-|-|-|
|=|x= 5|x=5|
|+=|x +=5|x = x+5|
|-=|x-=5|x=x-5|


Python casting
casting is used when you want to specify a type onto a variable.
Python is object oriented, such that it uses classes to set data types. Python does casting by using constructor functions
int ()
float()
str*()
Example
x = int(3.2) # x will be 3
x = int (“3” # x will be 3
x = int(3) # x will be 3
Python tuple
tuples are used to store multiple items in a single variable
tuple is one of the built in data types in python that can be used to store multiple data
tuples are created using round brackets
example
thistuple = (“adidas”, “nike”, “puma”)
print(thistuple)
Python set
sets also store multiple items in a single variable
sets are created using curly brackets
example
thisset = {“adidas”, “nike”, “puma”}
print(thisset)
Python List
lists are used to store multiple data within one variable 
lists are created using square brackets
example
thislist = [“1”,”2”,”3”]
print(thistlist)
Python loops
while loops
while loops can be executed when the conditions are true
example
x = 2
while x<5:
print(x)
x +=1
for loops
used to iterate over a sequence 
for loop can be executed once for each item in a list, set or array + etc
example
shoes = [“nike”,”adidas”,”puma”]
for x in fruits:
print(x)
Python functions
using def
def myFunction():
print(“hello”)
Python if…else 
this type of conditional statement only runs when a condition is met
for example
a=2
b=3
if a<b:
print(“a<b”)
Python array
arrays are used to store multiple values in a single variable:
computers = [“apple”,”lg”,”dell”]
