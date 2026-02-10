---
title: Loops
type: docs
prev: docs/javascript-basics/control-flow.md
next: docs/javascript-basics/arrays.md
weight: 4
---

*(for, while)*

A loop repeats code multiple times without rewriting it.

## for Loop (counted repetition)
for (let i = 1; i <= 5; i++) {
console.log("Jumping Jack #" + i);
}

Explanation:
- let i = 1 starts the counter at 1
- i <= 5 keeps looping while i is 5 or less
- i++ adds 1 each time
- Code inside runs once per number

## while Loop (repeat while condition is true)
let cookies = 3;

while (cookies > 0) {
console.log("Nom! Cookie eaten!");
cookies--;
}

Explanation:
- Start with cookies = 3
- Keep looping while cookies > 0
- cookies-- subtracts 1 each time
- Eventually cookies hits 0, and the loop stops

## Mini-Quiz
1. Which loop is best when you know exactly how many times to repeat?
2. What does cookies-- do?
