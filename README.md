# Week 6 Assignment: Safe Tools with try / except

- `safe_tools.py`: three functions, `safe_divide`, `safe_number`, and `get_field`, that use `try` / `except` so the program never crashes on bad input.

An `if` check can't catch `abc` on its own because there's no simple test that says "this text can be turned into a number" before you try it. Python only finds out when `int("abc")` runs and raises a `ValueError`, so `try` / `except` is the way to handle it.