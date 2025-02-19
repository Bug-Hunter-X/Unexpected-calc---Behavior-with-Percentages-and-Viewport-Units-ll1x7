# Unexpected calc() Behavior with Percentages and Viewport Units

This repository demonstrates an issue with the CSS `calc()` function when used with percentages and viewport units (like `vw` or `vh`). The calculated value is not what one would expect based on the formula used.

## Bug Description
The CSS property `calc()` is not working as expected when used with percentages and viewport units. The calculated value is incorrect, leading to unexpected layout issues.

## Bug Reproduction
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the unexpected layout caused by the incorrect calculation.

## Solution
The solution involves using a more robust approach that does not rely on combining percentages and viewport units with `calc()`. Alternatively, calculate the value using JavaScript to get the intended result.
