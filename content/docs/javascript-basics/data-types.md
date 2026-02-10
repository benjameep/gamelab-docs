---
title: Data Types
type: docs
prev: docs/javascript-basics/variables.md
next: docs/javascript-basics/control-flow.md
weight: 2
---

*(number, string, boolean, null, undefined, symbol)*

## Definition
A data type tells JavaScript what kind of information a value is.

## Why Data Types Matter

### Beach Ball Example
A beach ball won’t fit in a shoebox. Some actions only work with certain data types.

### Math Class Example
If you want to solve: A + B = C, then A and B should be numbers.
let A = 1;
let B = "NIKE";

This doesn’t work like normal math because "NIKE" is text, not a number.

## The 6 Main Data Types

1) Number: Used for numbers (including decimals)
let score = 100;
let temperature = 98.6;

2) String: Text in quotes
let name = "Andy";
let message = "Welcome to JavaScript!";

3) Boolean: Only true or false
let isGameOver = false;
let isLoggedIn = true;

4) Null: Intentionally empty
let currentPlayer = null;

5) Undefined: Not assigned yet
let result;
console.log(result); // undefined

6) Symbol (Advanced): A unique identifier
let id = Symbol("unique");

## Mini-Quiz
1. What data type is "Hello"?
2. What’s the difference between null and undefined?
