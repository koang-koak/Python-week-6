# Week 6 Assignment: Error Handling & Debugging

## Files Included
- **safe_tools.py**: Contains `safe_divide`, `safe_number`, and `get_field` functions that handle runtime errors gracefully using `try / except` blocks.
- **README.md**: Overview of the assignment and explanation of `if` check limitations.

## Reflection
An `if` check cannot catch `"abc"` on its own when converting to an integer because `if` conditions only evaluate boolean expressions; they do not intercept runtime exceptions raised by Python's built-in `int()` function. Checking string format manually (like `.isdigit()`) can miss edge cases like negative numbers, whereas a `try / except` block safely handles any invalid input during conversion.