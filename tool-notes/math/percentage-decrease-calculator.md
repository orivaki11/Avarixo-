# Percentage Decrease — reproducible reference

**Open the live Avarixo utility:** [Percentage Decrease](https://avarixo.com/percentage-decrease-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Measure a decrease as a fraction of an original positive amount. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
original, reduced = 200, 150
decrease_pct = (original - reduced) / original * 100
print(decrease_pct)
```

**Illustrative result:** 25% decrease.

## Interpret carefully

A falling percentage and a fall in percentage points are different calculations. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Percentage Decrease](https://avarixo.com/percentage-decrease-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
