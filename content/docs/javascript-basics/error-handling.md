---
title: Error Handling
type: docs
prev: docs/javascript-basics/arrays.md
Weight: 6
---

*(try…catch)*

Error handling helps your program respond safely when something goes wrong.

### Missing LEGO Piece Example
If a LEGO piece is missing, you don’t throw the whole set away; you pause, handle the problem, and keep going.

try {
let result = notARealFunction();
} catch (error) {
console.log("Oops! Something went wrong.");
}

Explanation:
- try { ... } means “try running this code”
- If it fails, JavaScript jumps to catch
- catch(error) receives info about what went wrong
- You can show a friendly message instead of crashing

Trampoline Metaphor:
- try = jump
- catch = trampoline catches you
- So you don’t hit the ground (crash)

## Mini-Quiz
1. What is the job of catch?
2. Does try…catch prevent mistakes, or help handle them?
