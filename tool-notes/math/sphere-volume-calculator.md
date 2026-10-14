# Sphere Volume — reproducible reference

**Open the live Avarixo utility:** [Sphere Volume](https://avarixo.com/sphere-volume-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Find the volume of a sphere from its radius. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
from math import pi
r = 3
print(round((4 / 3) * pi * r ** 3, 2))
```

**Illustrative result:** 113.10 cubic units.

## Interpret carefully

Radius is half the diameter; doubling radius multiplies volume eightfold. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Sphere Volume](https://avarixo.com/sphere-volume-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
