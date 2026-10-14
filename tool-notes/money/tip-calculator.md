# Tip Calculator — reproducible reference

**Open the live Avarixo utility:** [Tip Calculator](https://avarixo.com/tip-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Calculate a gratuity and a final bill total from a chosen bill base. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
bill, tip_percentage = 60, 18
tip = bill * tip_percentage / 100
print(round(tip, 2), round(bill + tip, 2))
```

**Illustrative result:** 10.80 dollars tip; 70.80 dollars total.

## Interpret carefully

Check whether service charges or gratuities are already included. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Tip Calculator](https://avarixo.com/tip-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
