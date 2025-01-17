# JavaScript Loose Comparison Pitfall with Null and Undefined

This repository demonstrates a common error in JavaScript related to loose comparison when handling null and undefined values.

## The Problem

JavaScript's loose equality operator (`==`) performs type coercion before comparison, which can lead to unexpected behavior, especially when dealing with `null` and `undefined`. The example in `bug.js` showcases this issue.

## The Solution

The best practice is to always use the strict equality operator (`===`) when checking for `null` or `undefined`. This avoids type coercion and ensures accurate comparisons. The corrected code is provided in `bugSolution.js`.