# Standard Deviation — reproducible reference

**Open the live Avarixo utility:** [Standard Deviation](https://avarixo.com/standard-deviation-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Compare observations by their population standard deviation. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
from statistics import pstdev
values = [2, 4, 4, 4, 5, 5, 7, 9]
print(pstdev(values))
```

**Illustrative result:** 2.

## Interpret carefully

Population and sample standard deviations differ; use the correct denominator. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Standard Deviation](https://avarixo.com/standard-deviation-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
