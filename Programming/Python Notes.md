**Comments**
```python
# Use the Pound/Hashtag to Comment just like this one!
# Python will ignore anything in these comments
```


**Data Types**
```python
# int: Whole Numbers
5

# float: Decimals Numbers
3.14

# string: Words, Sentences, Letters
"Hello Reader!"

# bool: True or False
True
False

# list: Holds multiple of the datatypes above
this_is_a_list = ["Python", "C++", "R", 12, True, 3.14]

# dict: Similar to List but use Key-Value. So Key 1 is Wikipedia, while Key 3 is W3Schools. Kinda like a nickname or ID for something
this_is_a_dictionary = {1: "Wikipedia", 2: "YouTube", 3:"W3Schools"}

```


**Math Operators** 
```python
# + for Addition
3 + 5 #8

# - for Subtraction
5 - 5 #0

# * for Multiplication
2 * 2 #4
 
# / for Division
4 / 2 #2

# // for Integer Division
25 // 2  #12

# % for Modulo (Remainder)
25 % 2 #1
 
# ** for Exponent
3 ** 3 #27

```

**Variables**
```python
# Variables store Data. We use the = to assign a value to a Variable
my_variable = "I am a Variable! I am of a String Type"
my_second_variable = 4
my_third_variable = 3.14
my_fourth_variable = 3 * 4

# We don't need to declare the type of variable either 
# We can also overwrite them
x = 3
x = "Hello"

# Naming Variables do follow certain rules:
# -It can only be one word (no spaces)
# -It can use letters, numbers and the underscore
# -It can't begin with a number
```

**Casting**
```python
# What we if we want to convert datatypes and variables into different ones

x = 1
print(type(x)) #int

x = float(x)
print(type(x)) #float

x = str(x)
print(type(x)) # str
```

**Basic Function: Print**
```python
# We can "Print" or push things onto the Terminal. We can print out datatypes or variables. Whatever we want to "See" the outcome of in the terminal, we Print

# Printing Data Types
print(5) #5
print(3.14) #3.14
print("Hello World") #Hello World
print(True) #True

# Printing Variables
var_one = 7
var_two = 3
var_three = "Hello World"

print(var_one) #7
print(var_two) #3
print(var_three) #Hello World

# Let's find out the type of data inside our variable
print(type(var_one)) # int

# We can even use our Math Operators
print(var_one + var_two) #10
print(2+3) #5

```

**Basic Function: Input**
```python
# Takes the input ftom the user via terminal/shell and converts it to a string

x = input()
print(x)

y = input("Type something!: ") # Python will ignore whatever is stored and only save what you type into the variable
print(y)
```

**Comparisons**
```python

# To compare values or variables we use these, output will be TRUE or FALSE
`==`Equal to
`!=`Not equal to
`<` Less than
`>` Greater Than
`<=`Less than or Equal to
`>=`Greater than or Equal to

print(45 > 32) # True
print(30 == 32) # False
print("orange" != "Apple") # True

```

**If-Statements**
```python
# Think of these like a word problem, "If _____ is TRUE/FALSE THEN DO _____"
# This is also where we will be using our comparision statements

if(5 > 3):
	print("True!")
	
# In human terms, if 5 is greather then 3, then we print True!, if it's not then nothing happens, but what if we want something TO happen, we use else

if(5 > 3):
	print("True!")
else:
	print("False!")	
	
```