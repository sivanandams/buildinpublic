---
title: 
description: 
aliases: 
tags: 
draft: "true"
date: 2024-07-18
---
- **Repetition**: The formula (celsius * 9/5) + 32 is repeated multiple times.
- **Maintenance**: If the formula needs to be changed, you have to update it in every place.
- **Readability**: The code is cluttered and harder to read.

```
#Part1
celsius1 = 25

fahrenheit1 = (celsius1 * 9/5) + 32

print(f"{celsius1}°C is {fahrenheit1}F")
```

```
#part2
celsius2 = 30

fahrenheit2 = (celsius2 * 9/5) + 32

print(f"{celsius2}°C is {fahrenheit2}F")
```

##### How to create a function?

*def name (arguments):*
*statement1*
*statement2*
*.*
*.*
*return value*

- Name -> Function name -> An identifier by which the function is called
- Arguments -> Contains a list of values passed to the function
- Function body -> statement1, 2... -> This is executed each time the function is called
- Return value -> Ends function call & sends data back to the program

##### Function Definition
**def** is a keyword that marks the start of the function header.

**function_name** to uniquely identify the function. Function naming follows the same rules of writing identifiers in Python.

**parameter** is the value passed to the function. They are optional.

**:** (colon) to mark the end of the function header.

**function body** is a block of code that performs some task and all the statements in function body must have the same indentation level (usually 4 spaces).

**"""docstring"""** documentation string is used to describe what the function does.

**return** is a keyword to return a value from the function.. A return statement with no arguments is the same as return None.

Note: While defining a function, we use two keywords, def (mandatory) and return (optional)

