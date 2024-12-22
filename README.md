# Python: Handling ZeroDivisionError in Average Calculation

This repository demonstrates a common error in Python: the `ZeroDivisionError` that can occur when calculating the average of a list of numbers. The `bug.py` file shows the flawed function, while `bugSolution.py` provides a corrected version.

The original function fails to handle empty lists or lists containing zero values, leading to division by zero. The solution adds checks to gracefully handle these scenarios and return a meaningful result.