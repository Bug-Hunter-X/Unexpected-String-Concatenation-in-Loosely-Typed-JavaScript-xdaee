# Unexpected String Concatenation in JavaScript

This repository demonstrates a common, yet subtle, error in JavaScript stemming from its loose typing system.  When performing arithmetic operations, the type coercion rules can lead to unexpected results, specifically string concatenation when you intend numerical addition.

The `bug.js` file contains the erroneous code, while `bugSolution.js` shows a corrected version.

## Bug Description:

The issue arises from implicitly converting numbers to strings before concatenating.

## Solution:

The solution involves explicit type checking and conversion to ensure numerical operations are performed as intended.

## How to Reproduce the Bug:

1. Clone this repository.
2. Run `bug.js` using Node.js: `node bug.js`
3. Observe the unexpected output.

## How to Solve the Bug:

1. Examine the corrected code in `bugSolution.js`.
2. Run `bugSolution.js` using Node.js: `node bugSolution.js`
3. Observe the corrected output.