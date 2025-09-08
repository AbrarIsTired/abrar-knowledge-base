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

# dict: Similar to List but use Key-Value. So Key 1 is Wikipedia, while Key 3 is W3Schools
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


# Naming Variables do follow certain rules:
# -It can only be one word
# -It can use leetters, numbers and the underscore
# -It can't begin with a number
```

**Print**
```python
# We can "Print" or push things onto the Terminal. We can print out datatypes or 
# variables. Whatever we want to "See" the outcome of in the terminal, we Print

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

# We can even use our Math Operators, just like you've seen earlier
print(var_one + var_two) #10
print(2+3) #5

```

**Comments**
```python
# Use the Pound/Hashtag to Comment just like this one!
# Python will ignore anything in these comments
# Later on we will go over Docstrings such as this one:
def add_func():
	"""
	Function Docstrings!
	"""
```

**For Loops & While Loops**
```python
count = 0
while(True):
	print(count)
	count+=1

```