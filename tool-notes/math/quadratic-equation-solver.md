# Quadratic Equation Solver — reproducible reference

**Open the live Avarixo utility:** [Quadratic Equation Solver](https://avarixo.com/quadratic-equation-solver/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Compute roots of a quadratic when the discriminant is nonnegative. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
from math import sqrt
a, b, c = 1, -5, 6
d = b * b - 4 * a * c
roots = ((-b + sqrt(d)) / (2 * a), (-b - sqrt(d)) / (2 * a))
print(roots)
```

**Illustrative result:** 3.0 and 2.0.

## Interpret carefully

For a zero a the equation is not quadratic; a negative discriminant calls for complex roots. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Quadratic Equation Solver](https://avarixo.com/quadratic-equation-solver/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
