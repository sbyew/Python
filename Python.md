---
"Date :": 9 Jul 2026
---

# Practice
* to enter multi lines in py terminal
```python
>>> if True: #type : at the end
... print("Line one") #tab then continue type
... print("Line two") #tab then Enter to end
...

>>> a='''a #to type a b c in 3-line, enclose these 3 letters in '''
... b
... c'''
```
* use " or ' in case your sentence need to use ' or '
```python
a = "I haven't picked it up"
b = 'Please "eat" this'
```

# boolean
* True or False
* Must start with capital T & F
# comment
# this is single line cmmt

"""
this is multi
line cmmt
"""

# isinstance()
* to check var data type then return True/False (unlike type() which return the type name
```python
myint = 3
print( isinstance(myint, int))  #True
print( isinstance(myint, float)) #False
print(isinstance( myint, (int,float)) #True. This chk whether myint is a int OR float. Note: if just chk for float we will get False
```
# print 
* Note: Dont put a space between print & (

```python
print("Hello World")  

myInt = 7
myfloat = 7.0
print(myint)

myfloat = float(7) # make 7 a float
print(myfloat) # 7.0

a, b = 1, 2
print(a, b) \# 1, 2

print("abc", "efg") #abc efg  \# py auto add space for comma-delimited items
print(a, "abc") #1 abc

a = 1
printf(f'a = {a}')  # will print "a = 1"  , f = format

# string
hello = "hello"
world = "world"
hw = hello + " " + world
printf(hw) # "hello world"
  
```

# type()
```python

a = "melvin"
print(type(a))
```
# Var
Var name cannot start with no.
```python
123Var = 1 # 123Var is an invalid var name
one_two = 12 # py convention is separate word with "_"
Var1 = None
```
 * None - represent nothing, it is _not_ the same as `0`, an empty string `""`, or `False`. Those are actual values — `0` is a number, `""` is an empty piece of text. `None` means there is no value at all. It used to show a var is not init yet

```python
# Set: An unordered collection of unique elements, like `{0.5, 4, 'apple'}`.
my_set_var = {7, 'hello', 8.5}
print('Set:', my_set_var) # Set: {7, 'hello', 8.5}

# Dictionary: A collection of key-value pairs enclosed in curly braces, like `{'name': 'John Doe', 'age': 28}`.
my_dictionary_var = {'name': 'Alice', 'age': 25}
print('Dictionary:', my_dictionary_var) # Dictionary: {'name': 'Alice', 'age': 25}

# Tuple: An immutable ordered collection, enclosed in parentheses, like `('apple', 4.5, 7)`.
my_tuple_var = (7, 'hello', 8.5)
print('Tuple:', my_tuple_var) # Tuple: (7, 'hello', 8.5)

# Range: A sequence of numbers, often used in loops, for example, `range(5)`.
my_range_var = range(5)
print('Range:', my_range_var) # Range: range(0, 5)

# List: An ordered collection of elements that supports different data types.
my_list = [22, 'Hello world', 3.14, True]
print(my_list) # [22, 'Hello world', 3.14, True]

```
