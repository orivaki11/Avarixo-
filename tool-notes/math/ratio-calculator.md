# Ratio Calculator — reproducible reference

**Open the live Avarixo utility:** [Ratio Calculator](https://avarixo.com/ratio-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Simplify a two-part integer ratio with the greatest common divisor. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
from math import gcd
a, b = 12, 18
g = gcd(a, b)
print(f'{a // g}:{b // g}')
```

**Illustrative result:** 2:3.

## Interpret carefully

A ratio changes meaning when the order of its quantities is reversed. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Ratio Calculator](https://avarixo.com/ratio-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
