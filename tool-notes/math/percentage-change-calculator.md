# Percentage Change — reproducible reference

**Open the live Avarixo utility:** [Percentage Change](https://avarixo.com/percentage-change-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Compute a signed relative change from an original baseline. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
old, new = 80, 100
change_pct = (new - old) / abs(old) * 100
print(change_pct)
```

**Illustrative result:** +25% relative to the baseline.

## Interpret carefully

A zero baseline makes this expression undefined; changes from negative values need a stated convention. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Percentage Change](https://avarixo.com/percentage-change-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
