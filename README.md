# Unexpected Behavior with CSS `calc()` Function

This repository demonstrates a common error involving the CSS `calc()` function and provides a solution.

## Bug Description
The `calc()` function in CSS can produce unexpected results if used improperly, particularly when combined with flexbox layouts. Missing spaces around operators or the order of operations can cause incorrect calculations.

## Bug Reproduction
The `bug.css` file shows the incorrect implementation. Observe how the element behaves compared to the expected layout.

## Solution
The `bugSolution.css` file shows the corrected implementation.  Proper spacing and understanding operator precedence within `calc()` ensure correct calculations.

## Note
Always ensure proper spacing around operators within `calc()` to avoid unexpected behavior.  For complex calculations or when dealing with flexbox items, carefully consider the order of operations.