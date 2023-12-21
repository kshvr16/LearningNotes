# Data Types and Operators

-----------------
### 1. Introduction
__Data Types and Operators__
Welcome to this lesson on Data Types and Operators! In this lesson, you will learn how to write basic Python statements using building blocks like the print statement, variables, and different data types.

![Introduction](https://video.udacity-data.com/topher/2021/May/609ec92c_intro-to-python-overarching-diagram-1/intro-to-python-overarching-diagram-1.jpg)

Here are the topics you'll learn about:
- Data Types: Integers, Floats, Booleans, Strings
- Operators: Arithmetic, Assignment, Comparison, Logical
- Built-In Functions, Type Conversion
- Whitespace and Style Guidelines

__Print Statements__
```print ()``` - built-in function that displays input values as text in the output

-----------------
### 2. Arthimetic Operators
__Arthimetic Operators__
- `+` Addition
- `-` Subtraction
- `*` Multiplication
- `/` Division
- `%` Mod (the remainder after dividing)
- `**` Exponentiation (note that ^ does not do this operation, as you might have seen in other languages)
- `//` Divides and rounds down to the nearest integer

The usual order of mathematical operations holds in Python, often referred to as __PEMDAS: *Parentheses, Exponents, Multiplication/Division, Addition/Subtraction*__.
If needed, you can review the order of mathematical operations in this Wikipedia article [Order of Operations](https://en.wikipedia.org/wiki/Order_of_operations).
__Bitwise operators__ are special operators in Python that you can learn more about [here](https://wiki.python.org/moin/BitwiseOperators) if you'd like.

-----------------
### 3. Quiz: Arithmetic Operators

-----------------
### 4. Solution: Arithmetic Operators

-----------------
### 5. Variables and Assignment Operators

__Variables and Assignment Operators__
From this page, you will get your first look at variables in Python. There are three videos in this concept to show you some different cases you might run into!

__Variables I__
Variables are used all the time in Python! Below is the example you saw in the video where we performed the following: `mv_population = 74728`.
Here `mv_population` is a variable, which holds the value of `74728`. This assigns the item on the right to the name on the left, which is actually a little different than mathematical equality, as `74728` does not hold the value of `mv_population`.
In any case, whatever term is on the left side, is now a name for whatever value is on the right side. Once a value has been assigned to a variable name, you can access the value from the variable name.

__Variables II__
In this video you saw that the following two are equivalent in terms of assignment:
```Python
x = 3
y = 4
z = 5
```
and
```Python
x, y, z = 3, 4, 5
```
However, the above isn't a great way to assign variables in most cases, because our variable names should be descriptive of the values they hold.
Besides writing variable names that are descriptive, there are a few things to watch out for when naming variables in Python.
1. __Only use ordinary letters, numbers and underscores in your variable names.__ They can’t have spaces, and need to start with a letter or underscore.
2. __You can’t use reserved words or built-in identifiers__ that have important purposes in Python, which you’ll learn about throughout this course. A list of Python reserved words is can be found in the Python documetation. See [Lexical analysis - Keywords](https://docs.python.org/3/reference/lexical_analysis.html#keywords). Creating names that are descriptive of the values often will help you avoid using any of these words. A quick table of these words is also available below.

__*Keywords in Python*__

| Keyword | Keyword | Keyword | Keyword | Keyword |
| ------ | ------ | ------ | ------ | ------ |
| FALSE | await	| else | import | pass |
| None | break | except | in | raise |
| TRUE | class | finally | is | return |
| and | continue | for | lambda | try |
| as | def | from | nonlocal | while |
| assert | del | global | not | with |
| async | elif | if | or | yield |

3. __Use all lowercase letters and underscores to separate words.__ This is called __snake case__, because we connect the words with underscores.

__*DO THIS*__
```Python
my_height = 58
my_lat = 40
my_long = 105
```

__*NOT THIS*__
```Python
my height = 58
MYLONG = 40
MyLat = 105
```

```
Although the last two of these would work in Python, they are not pythonic ways to name variables.
```

__Assignment Operators__
Below are the assignment operators from the video. You can also use `*=` in a similar way, but this is less common than the operations shown below. You can find some practice with much of what we have already covered [here](https://www.programiz.com/python-programming/operators).

Here are the assignment operators from the video.

| Symbol | Example | Equivalent |
| ------ | ------ | ------ |
| `=` | `x = 2` | `x = 2` |
| `+=` | `x += 2` | `x = x + 2` |
| `-=` | `x -= 2` | `x = x - 2` |

-----------------
### 6. Quiz: Variables and Assignment Operators

-----------------
### 7. Solution: Variables and Assignment Operators

-----------------
### 8. Integers and Floats

