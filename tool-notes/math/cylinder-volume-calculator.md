# Cylinder Volume — reproducible reference

**Open the live Avarixo utility:** [Cylinder Volume](https://avarixo.com/cylinder-volume-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Calculate the volume of a right circular cylinder. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
from math import pi
radius_cm, height_cm = 2, 5
volume = pi * radius_cm ** 2 * height_cm
print(round(volume, 2))
```

**Illustrative result:** 62.83 cubic centimeters.

## Interpret carefully

Container wall thickness affects internal capacity; the simple formula assumes a solid geometric cylinder. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Cylinder Volume](https://avarixo.com/cylinder-volume-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
