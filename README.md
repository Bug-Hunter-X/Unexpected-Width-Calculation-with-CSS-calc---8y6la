# CSS calc() Function Bug

This repository demonstrates an uncommon bug related to the CSS `calc()` function and its interaction with percentage and pixel values.  Some browsers exhibit unexpected behavior when calculating widths using expressions like `calc(100% - 20px)`.  This issue is often more pronounced in older browsers or when container widths are themselves dynamically calculated.

The `bug.css` file shows the problematic CSS rule, while `bugSolution.css` offers potential solutions.

**Problem:** Inconsistent width calculations across different browsers due to misinterpretation of the `calc()` function.

**Solution:** Using alternative approaches to achieve the desired width without relying on the potentially buggy `calc()` behavior.

