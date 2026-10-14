# Percentage Calculator — reproducible reference

**Open the live Avarixo utility:** [Percentage Calculator](https://avarixo.com/percentage-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Express one amount as a percentage of a nonzero whole. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
part, whole = 18, 60
percentage = 100 * part / whole
print(percentage)
```

**Illustrative result:** 30%.

## Interpret carefully

The denominator is the reference base; percentage points are not relative percentage change. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Percentage Calculator](https://avarixo.com/percentage-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
