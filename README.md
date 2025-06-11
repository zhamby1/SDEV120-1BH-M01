# Notes For Module 1
These are notes for the first module in SDEV 120.

## Variables
Variables - Store Data

The type they can store is almost infinite.  They can store numbers, text, images, audio, etc...

In this class we will mainly use numbers and text

Numbers can use all the mathematical operators just like in your math class

- '+' - addition
- '-' - subtration
- '*' - multiplication
- '/' - division

To make a variable, all you have to do is give it a name and a value

In the following example, mynumber is the name of the variable and 6 is it's value:

```
mynumber = 6
```

Once stored, you can use it in other calculations.  The following example takes two variables and adds them together to store it in a third variable.

```
first_number = 10
second_number = 20
sum = first_number + second_number
```
In this case, sum would now be equal to 30.

Variables can also be test, also known as Strings

```
name = "Zach"
```

Strings are surrounded with quotation marks

## General Rules for Variable Naming
1. Do not use numbers at the beginning of a variable name

```
1number = 10   - this would not work and give you an error
```

2. There can be no spacing in between variable names..the programming language will assum that you are trying to execute new code

```
my name = "Zach" - will not work..thinks there are two variables there
```
Instead you should use underscores or camelCase to represent a variable name with two words

```
my_name = "Zach"
myName = "Zach"
```


# Inputs
Inputs are variables that are grabbed from a user (with a prompt) and stored in a variable

The following example would ask a user for their name, and store it in a variable

```
input my_name
    or
my_name = input
```

Then you can take the input and manipulate..such as.....


# Output
Output..in our case, displays something on screen.  Let's use the my_name example above to output it

```
ouput my_name
```
