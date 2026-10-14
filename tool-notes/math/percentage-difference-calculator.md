# Percentage Difference — reproducible reference

**Open the live Avarixo utility:** [Percentage Difference](https://avarixo.com/percentage-difference-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Use the mean magnitude of two positive values as a symmetric comparison base. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
a, b = 80, 100
pct_difference = abs(a - b) / ((abs(a) + abs(b)) / 2) * 100
print(round(pct_difference, 2))
```

**Illustrative result:** 22.22% symmetric difference.

## Interpret carefully

Some fields define percentage difference with another denominator; label your convention. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Percentage Difference](https://avarixo.com/percentage-difference-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
