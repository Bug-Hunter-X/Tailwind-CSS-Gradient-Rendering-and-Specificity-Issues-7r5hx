# Tailwind CSS Gradient and Specificity Bug

This repository demonstrates an uncommon bug in Tailwind CSS related to gradient rendering and CSS specificity issues.

## Bug Description
The `bg-gradient-to-r` utility class might not render correctly in older browsers or if there's a CSS specificity conflict. This can result in the gradient not appearing or appearing incorrectly.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in a browser.
3. Observe the gradient's rendering (or lack thereof).
4. Compare the rendering with `bugSolution.html` to see the corrected implementation. 

## Solution
The solution involves addressing the potential browser compatibility issues and resolving the CSS specificity conflict by using more specific selectors or adjusting the CSS order.  See `bugSolution.html` for the corrected code.