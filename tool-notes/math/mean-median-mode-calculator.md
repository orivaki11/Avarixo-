# Mean Median Mode — reproducible reference

**Open the live Avarixo utility:** [Mean Median Mode](https://avarixo.com/mean-median-mode-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Compare arithmetic mean, median and most frequent observation. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
import statistics
values = [2, 2, 3, 9]
print(statistics.mean(values), statistics.median(values), statistics.mode(values))
```

**Illustrative result:** 4, 2.5 and 2 respectively.

## Interpret carefully

Datasets may have more than one mode; a highly skewed distribution can make the mean misleading. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Mean Median Mode](https://avarixo.com/mean-median-mode-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
