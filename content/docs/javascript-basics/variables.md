---
title: Variables
type: docs
prev: docs/javascript-basics/
next: docs/javascript-basics/data-types.md
weight: 1
---

*(var, let, const)*

## Definition
A variable is a named place to store data so you can use it later.

## What Variables Are
Think of a variable as a box with a label:
- The label is the variable name
- The thing inside the box is the value

### Shoe Rack Example
If you’re cleaning a room, shoes need a place to go.
- Shoe rack = the variable
- Shoes = the value
Later, when you need your shoes, you know exactly where to find them.

## Code Example
Step 1: Create a variable (no value yet)
let dadsBirthday;

What this means:
- let tells JavaScript: “I’m creating a variable.”
- dadsBirthday is the variable name.
- No value has been placed inside yet, so it’s currently undefined.

Step 2: Store a value in it
let dadsBirthday = "June 22, 1998";

What this means:
- The variable is created AND filled with a value.
- "June 22, 1998" is a string (text in quotes).
- Now whenever you need the birthday, you can use dadsBirthday instead of retyping the date.

## Variable Rules
Use let, const, or var
- **Correct:** let score = 10;

Names must start with a letter, _, or $
- **Correct:** age, _count, $price
- *Incorrect:* 1score

No spaces
- **Correct:** playerScore
- *Incorrect:* player score

Case matters
score and Score are different variables

Use clear names
- **Correct:** playerLives
- *Incorrect:* x

Don’t use reserved JavaScript words
- *Incorrect:* let, if, function

## Mini-Quiz
1. What is a variable, in one sentence?
2. Which variable name is valid: 1score or playerScore?
