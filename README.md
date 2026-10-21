# PLP Week 6 Assignment - Safe Functions

## Files

- `safe_tools.py` — Contains three safe functions: `safe_divide`, `safe_number`, and `get_field`, with error handling using `try` and `except`.
- `README.md` — Describes the assignment files and explains why an `if` check alone cannot catch invalid number input.

## Why can't an if check catch "abc" on its own?

An `if` check can check a condition, but it cannot automatically convert text into an integer. When `int("abc")` is executed, Python raises a `ValueError` because `"abc"` is not a valid whole number. Using `try` and `except ValueError` allows the program to handle this error without crashing.
