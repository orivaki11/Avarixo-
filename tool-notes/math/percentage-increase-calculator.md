# Percentage Increase — reproducible reference

**Open the live Avarixo utility:** [Percentage Increase](https://avarixo.com/percentage-increase-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Express an increase as a percentage of an original positive amount. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
old, new = 50, 60
increase_pct = (new - old) / old * 100
print(increase_pct)
```

**Illustrative result:** 20% increase.

## Interpret carefully

An increase of 20% will not reverse every decrease of 20%; the bases differ. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Percentage Increase](https://avarixo.com/percentage-increase-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
