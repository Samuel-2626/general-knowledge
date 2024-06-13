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

## Iteration

- While loops can repeat code inside indefinitely! Sometimes they need your intervention to end the program.

- For loops only repeat for however long the sequence is. The loop variables takes on these values in order.

## Loops over strings, Guess-and-check, and Binary

- break STATEMENT
    * Immediately exits whatever loop it is in
    * Skips remaining expressions in code block
    * Exits only innermost loop!

- The sequence of values in a for loop isn't limited to numbers

* Challenge:
- Assume you are given a string of lowercase letters in a variable s. Guess how many unique letters there are in the string. For example, if s = "abca", then your code prints 3.


- Booleans can be used as signals that something happened; we call them Boolean flags.

## Decomposition, Abstraction, and Functions

- Apply abstraction (black box) and decomposition (split into self-contained parts) to programming.
- Coder achieves abstraction with a function (or procedure).
- A function lets us capture code within a black box.
    * Once we create function, it will produce an output from inputs, while hiding details of how it does the computation.
- A function has specifications, captured using docstrings.
- Think of a docstring as a "contract" between the coder and user.
    * If user provides input that satisfies stated conditions, function will produce output according to specs, including side effects.
- Modules are used to:
    * Break up code into logical pieces
    * Keep code organized
    * Keep code coherent (readable and understandable)
- Decomposition relies on abstraction to enable the construction of complex modules from simpler ones.
- Reusable pieces of code, called functions or procedures.
- A function is just some code written in a special, reusable way.
- Defining a function tells Python some code now exists in memory.
- Functions are only useful when they are run ("called" or "invoked").
- You write a function once but you can run it many times!
- Function characteristics
    * Has a name
    * Has parameters (0 or more)
        - The inputs
    * Has a docstring (optional but recommended)
        - A comment delineated by """ (triple quotes) that provides a specification for the function - contract relating output to input.
    * Has a body, a set of instructions to execute when the function is called.
    * Returns something.
        - Keyword return
- How to think about writing a function
    * What is the problem?
        - Use this to write the function name and specs
    * How to solve the problem?
        - Think about what value you need to give back
    * Can you make the code cleaner?
- Solve a simpler problem first
    * Add functionality to the code later
- Test code often; use prints to debug

