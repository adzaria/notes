[back to index](../README.md)

# Lexicon

## Routines

A *routine* describes any sequence of instructions in a program, or the main program itself.

## Subroutines

A *subroutine* is an encapsulated set of instructions that can be invoqued from different places in a program.

## Procedures

A *procedure* is an **action-oriented** subroutine that can take one or mulitple parameters and does not return any value.

## Functions

A *function* is a **value-oriented** subroutine that can take one or mulitple parameters and return one or multiple values.

Note: the term function comes from mathematics, but a function would map more to an mathematic "application".

### Pure functions
A *pure function* has the following characteristics.
- It is deterministic. It has the same output for a given input.
- It does not cause any side-effects. it does not alter any state outside its scope, nor does it have any observable interaction with the outside world apart from returning a value.

### Idempotent functions
An *idempotent function* has the following characteristics:
- It can be applied multiple times without changing the result beyond the initial application.
- It is deterministic. It has the same output for a given input.
- It can cause side effects and modify a state.

### Variadic functions
A *variadic function* takes an undefined number of arguments.

### Higher-order functions
A *higher-order function* is a function that takes one or more functions as an arguments and/or returns one or more functions as its result.

### First-class functions
A *first-class function* is a function that can be passed as an argument to other functions, returned by another function and assigned as a value to a variable.

### Lambda functions
A *lambda function* (or *anonymous function*) is a function defined without a name. They are often used for short-term use and can be passed as arguments to higher-order functions.

### Recursive functions
A *recursive function* is a function that calls itself. Some languages support *tail call optimization* to avoid a stack overflow.
*Tail call optimization* is the process of optimizing recursive functions by reusing the same stack frame for each recursive call. Usually this happens when the recursive call is the last instruction in the function.

### Closure functions
A *closure* is a function that retains access to the lexical environment of its parent function, even after the parent function has returned. 
The scope of the parent function is enclosed (or captured) in the closure.
Closures are used maintain state between function calls and/or to enclose private variables.

### Thunk function
A *thunk* function is a function that wraps another function to delay its evaluation.

### Trampoline
A *trampoline* is a function that repeatedly invokes a thunk until it returns a value.
It can be used to avoid stack overflow when dealing with recursive functions in languages that don't support tail optimization.

### Currying
*Currying* or *partial application* is the process of transforming a function that takes multiple arguments into a function that takes one argument and returns another function that takes the next argument, and so on.

The purpose of currying is:
- Re-usability: To partially apply arguments to a function. 
- Composition: To create a chain of simple functions and compose them together.
- Performance: To take advantage of lazy evaluation.

### Memoization
*Memoization* is the process of caching the result of a function call based on its input. It is used to speed up the execution of a function by avoiding unnecessary computations.

### Lazy evaluation
*Lazy evaluation* is the process of delaying the evaluation of an expression until its value is needed.

## Classes

In OOP, a *class* is a blueprint for creating objects. It has the following characteristics:
- It has attributes (data members)
- It has behaviors (member functions, or methods)
- Its members are encapsulated (private, protected, public)
- It can have a constructor
- It supports instantiation
- It supports inheritance
- It supports polymorphism
- It supports abstraction

Alan Kay, the inventor of the term "object-oriented programming", said that OOP is about messaging, and that objects are just a way to group messaging.

## Objects

In OOP, an *object* is an instance of a class. It has the following characteristics:
- It is an instance of a class
- It encapsulate state and behaviour
- It has its own identity (memory address)
- It interacts through messaging
- Objects of different classes can be treated as objects of a common superclass, especially if they share the same interface. This is known as polymorphism, which allows objects to be used interchangeably, provided they adhere to a specified contract or interface.

---

# Todo

Modules / Classes / Prototypes
Parrallel / Concurrent
Lexical environment
Scope
name space / 

### Paradigms
Declarative / Imperative / Point-free style
*Point-free style* is a style of programming where function definitions do not make use of the function's arguments.


<p><br/></p>

[back to index](../README.md)
