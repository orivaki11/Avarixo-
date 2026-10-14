# Average Calculator — reproducible reference

**Open the live Avarixo utility:** [Average Calculator](https://avarixo.com/average-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Find the arithmetic mean of equally weighted numeric observations. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
values = [4, 6, 8]
mean = sum(values) / len(values)
print(mean)
```

**Illustrative result:** 6.

## Interpret carefully

Outliers affect the mean, and an empty observation list has no ordinary mean. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Average Calculator](https://avarixo.com/average-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
