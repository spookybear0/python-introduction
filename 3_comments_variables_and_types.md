# Comments, Variables, and Types

## Comments

To create a comment in Python all you have to do is put a hash in front of any text and it will be ignored

Comments can be used to document what code does. It makes code easier to read to future you or anyone else reading your code.

### Example

```py
# This is a commment

# Look! I can do comments inline
x = 1 # Sets the variable x equal to 1
```

## Variables

If you remember from Math, variables are names that hold a value.

This value doesn't have to be a number though.

### Example

```py
x = 10
```

This sets the name `x` to the value `10`

Python supports basic Math operations such as addition, subtraction, multiplication, division and powers.

### Example

```py
x = 1 + 2 # addition
x = 2 - 3 # subtraction
x = x * 2 # multiplication
x = x / 2 # division
x = x ** 2 # power
```

### Variable names

Variable names follow a particular set of rules such as
* It must start with a letter or the underscore character
* It cannot start with a number
* It can only contain alpha-numeric characters and underscores (A-z, 0-9, and _)
* They are case-sensitive (age, Age and AGE are three different variables)

## Types

Variables can be more than just a simple integer.

Remember when we printed "Hello, World!"? Those quotes around the text create a data type called a string, or `str` in Python terms.

Variables can be set to any type and can be used anywhere a "literal" can be used.

```py
hello_world = "Hello, World!"

print(hello_world)
```

### Built-in Data Types

Text Types: `str`

Number Types: `int`, `float` (similar to a decimal), `complex`

Sequence Types: `list`, `tuple`

Mapping Type: `dict`

Set Types: `set`, `frozenset`

Boolean Type: `bool` (can be set to True or False)

Binary Types: `bytes`, `bytearray`, `memoryview`

We will learn more about advanced types later.

## Converting Types

You can convert between different types by "calling" (we will talk about this in a later chapter) the type name.

### Example

Converting a integer to a string.


```py
x = 1

y = str(x) # convert 1 to "1"
```

### Example

Converting a string to an integer

```py
x = "1"

# prints the integer version of "1", which is 1
print(int(x))
```

Luckily the built-in `print` function (will be discussed in a later chapter) accepts any type and converts it to a string automatically.

### Example

Printing an integer

```py
print(1) # Doesn't have to be a string!
```

## Getting the Type of a Variable

You can get the type of a variable with the built-in `type` function

### Example

```py
x = 1

y = str(x)

print(type(x), type(y))

>>> <class 'int'>, <class 'str'>
```

Notice how these are "classes", this is a more advanced concept that will be shown later on.


## Assignment

TODO: