# Python

Notes created from [Python in one video](https://www.youtube.com/watch?v=ihk_Xglr164) by [Code With Harry](https://www.youtube.com/@CodeWithHarry). This module covers:

1. [Hello World](#hello-world-program)
2. [Defining Variables](#defining-variables)
3. [Defining Comments](#defining-comments)
4. [Strings](#strings)
5. [Slicing](#slicing)
6. [Collections](#collections)
7. [Functions](#functions)/
8. [Classes](#classes)
9. [Ending](#ending)

## Hello World Program

```python
print("Hello World")
```

## Defining Variables

To define Variables:

```python
i = 1
s = "a"
f = 0.1
```

## Defining Comments

`# This is a comment`

## Strings

Any alphabet or number if enclosed within inverted commas(" ") are strings.
Or they are array of characters.

### Multiline Strings

They are enclosed within triple quotes(" " "..." " ")

### String Functions

- #### Strip Function

It removes any whitespace between, before and/or after the string.
For Example:

```py
str = "      d a s       "
print(str.strip())
```

>Output:- das

- #### Len Function

It returns the length of string as an integer.
For Example:

```py
str = "GameCoder"
print(len(str))
```

>Output:- 9

- #### Lower Function

It converts the string to lower case.
For Example:

```py
var = "DOWN"
print(var.lower())
```

>Output:- down

- #### Upper Function

Converts the string to upper case.
For example:

```py
var = "up"
print(var.upper())
```

>Output:- UP

- #### Replace Function

It replace all or (if defined)some references of a particular character.

>>Syntax-

`string.replace("oldvalue", "newvalue", count)`

For example:

```py
var = "dasta"
print(var.replace("d", "p"))
```

>Output:- pasta

- #### Format Function

Similar to String.Format() function in C#.
Usage:

```py
str = "this is a {}"
st = "string"
print(str.format(st))
```

>Output:- this is a string

It can be substituted to string interpolation as in C#, just replace dollar($) with 'f' like:

```py
print(f"this is a {st}")
```

>Output:- this is a string

## Slicing

Slicing is the method of taking out an element from an array or list.
For Example:

```python
s = "String"
print(s[0])
```

>Output:-  S

## Collections

Arrays use to store data. These are of 4 types:

1. Lists []
2. Tuples ()
3. Dictionary {}
4. Set

- ### Lists

A mutable collection. It supports [Slicing](#slicing) and [len function](#len-function).

#### List functions

- ##### Append function

Used to add an element at the end of the list. For example:

```py
lt = [1,2,3]
dt = lt.append(4)
print(dt)
```

>Output:- [1,2,3,4]

- ##### Insert function

Similar to [append function](#append-function) but allows to add element at a particular position.

>>Syntax-

`list.insert(index, value)`

For Example:

```py
lt.insert(2, 4)
```

> Output:- [1,2,4,3]

- ##### Remove function

Removes the first ocurrence of the value.
For Example:

```py
lt.remove(4)
```

>Output:- [1,2,3]

- ##### Pop function

Removes the element from the last or (if defined)from a particular index.
For Example:

```py
lt.pop()
```

>Output:- [1,2]

- ##### Clear function

Empties the list.
For Example:

```py
lt.clear()
```

> Output:- []

This can also be achieved by 'del' keyword.

```py
del lt
```

- ### Tuple

Immutable data type. All functions are same as lists.

## Functions

Use "def" keyword to define functions, put a semicolon after defining parameters.
For example:

```py
def funky(a, h):
    return a + b
```

## Classes

To define classes, use "class" keyword and put semicolon after class name.
For Example:

```py
class Main:
    def member():
        print("de")
```

### Constructor

To define constructor:

```py
class rd:
    def __init__():
        print("this is a constructor")
```

---

## Ending

This much is required for ML except numpy and pandas.
