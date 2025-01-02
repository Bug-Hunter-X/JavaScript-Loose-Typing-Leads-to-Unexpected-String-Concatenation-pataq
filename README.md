# JavaScript Loose Typing Bug

This repository demonstrates a common JavaScript bug related to loose typing and the unexpected concatenation of strings and numbers.

The `bug.js` file contains a function that unintentionally concatenates a number and a string due to JavaScript's automatic type coercion. The `bugSolution.js` file offers a solution by explicitly checking data types or using techniques like `parseInt()` to ensure the correct numeric operation.

## How to Reproduce

1. Clone this repository.
2. Run `node bug.js` to see the unexpected output.
3. Run `node bugSolution.js` to see the corrected output.

This example highlights the importance of type checking and careful consideration of data types when writing JavaScript code to prevent unexpected behavior.