# Fraction Calculator — reproducible reference

**Open the live Avarixo utility:** [Fraction Calculator](https://avarixo.com/fraction-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Add fractions accurately, then simplify the resulting rational number. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
from fractions import Fraction
result = Fraction(1, 3) + Fraction(1, 6)
print(result)
```

**Illustrative result:** 1/2.

## Interpret carefully

Denominators cannot be zero; mixed-number notation is a presentation choice. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Fraction Calculator](https://avarixo.com/fraction-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
