# Decimal to Fraction — reproducible reference

**Open the live Avarixo utility:** [Decimal to Fraction](https://avarixo.com/decimal-to-fraction-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Represent a terminating decimal as an exact simplified rational number. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
from fractions import Fraction
value = Fraction('0.375')
print(value)
```

**Illustrative result:** 3/8.

## Interpret carefully

Converting from an already rounded decimal may not recover the original exact value. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Decimal to Fraction](https://avarixo.com/decimal-to-fraction-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
