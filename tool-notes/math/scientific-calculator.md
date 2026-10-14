# Scientific Calculator — reproducible reference

**Open the live Avarixo utility:** [Scientific Calculator](https://avarixo.com/scientific-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Evaluate a trigonometric function using degrees with an explicit conversion to radians. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
from math import sin, radians
print(round(sin(radians(30)), 6))
```

**Illustrative result:** 0.5.

## Interpret carefully

Degree/radian mode and the logarithm base are common sources of silent errors. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Scientific Calculator](https://avarixo.com/scientific-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
