# Intro to CS and Programming Using Python

- Programming is a skill; you have to practice.

## Topics

- Solving problems using computation
- Python Programming Language
- Organizing modular programs
- Some simple but important algorithms
- Algorithmic complexity

## Types of Knowledge

- Declarative knowledge is statements of facts
- Imperative knowledge is a recipe or "how-to"

- Programming is about writing recipes to generate facts.

## We have an Algorithm

- Sequence of simple steps
- Flow of control process that specifies when each step is executed
- A means of determining when to stop.

- Algorithms are recipes/recipes are algorithms
- Computers are machines that execute algorithms

## Two things computers do:

- Performs simple operations; 100s of billions per second
- Remebers results; 100s of gigabytes of storage

## What kinds of calculations?

- Built-in to the machine e.g +
- Ones that you define as the programmer

- A computer will only do what you tell it to do.
- A program is a sequence of definitions and commands. Definitions are evaluated, while commands are executed by the Python interpreter.
- Programs manipulate data objects.
- Objects have a type that defines the kinds of things programs can do to them.

## Objects

- Scalar (cannot be subdivided). 
    * Numbers: 8.3, 2
    * Truth value: True, False
- Non-scalar (have an internal structure that can be accessed)
    * Lists
    * Dictionaries
    * Sequence of characters: "abc"


## Scalar Objects

- int -> represent integers e.g. 5, -100
- float -> represent real numbers e.g. 3.27, 2.0
- bool -> represent Boolean values; True and False
- NoneType -> special and has one value, None.

## Type Conversion (Casting)

- Can convert an object of one type to another

## Expressions

- Combine objects and operators to form expressions
- An expression has a value, which has a type

## Simple operations

- Parentheses tell Python to do these operations first; Like math!
- Operator precedence without parentheses
    * [**]
    * [*/%] executed left to right, as appears in the expression
    * [+-] executed left to right, as appears in the expression

## Variables

- Computer science variables are different from math variables
- Math variables
    * Abstract
    * Can represent many values
- CS variables
    * Is bound to one single value at a given time
    * Can be bound to an expression (but expression evaluates to one value!)


-  In CS, the equal sign is an assignment
- Why give names to values of expressions?
    * To reuse names instead of values
    * Makes code easier to read and modify
- Choose variable names wisely
    * Code needs to be read, by you and others
    * You'll be fine if you start with letters, and underscores, don't start with a number
- Comments are not part of the code executed - used to tell others what your code is doing.

## Change Binding

- Can re-bind variable names using new assignment statements
- Previous values may still be stored in memory but lost the handle for it.


- Lines are evaluated one after the other

## Strings, Input/ Output and Branching

- Think of a str as a sequence of case-sensitive characters.
- Characters can include letters, special characters, spaces, and digits.
- Strings are enclosed in quotation marks or single quotes.
- You should be consistent about either using quotation marks or single quotes in your program.
- You can concatenate and repeat strings.

- len() is a function used to retrieve the length of a string in the parentheses.


## Slicing to get one character in a String

- Square brackets are used to perform indexing into a string to get the value at a certain index/position.

## Slicing to get a SUBSTRING

- Can slice strings using [start: stop: step]
- Get characters at start, up to and including stop-1, taking every step characters.
- If given two numbers, [start: stop], step=1 by default
- You can also omit numbers and leave just colons
- Look at the step first. +ve means go left-to-right; -ve means go right-to-left

## Good Trivial Question

- Reverse a string 

[::-1]

## Immutable Strings

- Strings are "immutable" - cannot be modified
- You can create new objects that are versions of the original one
- Variable name can only be bound to one object.

## Python Input Function

- Input always returns a str, which must be cast if working with numbers

## F-strings

- Available starting with Python 3.6

## Why bool?

- When we get to the flow of control, i.e. branching to different expressions based on values, we need a way of knowing if a condition is true.

## Debug early, debug often

- Write a little and test a little
- Don't write a complete program at once; it introduces too many errors.

