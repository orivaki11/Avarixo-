# Compound Interest — reproducible reference

**Open the live Avarixo utility:** [Compound Interest](https://avarixo.com/compound-interest-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Project a hypothetical balance under an unchanged annual percentage rate. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
principal, annual_rate, years = 1000, 0.05, 2
balance = principal * (1 + annual_rate) ** years
print(round(balance, 2))
```

**Illustrative result:** 1102.50 dollars.

## Interpret carefully

A fixed growth rate is an assumption, not a forecast; deposits, taxes and inflation need separate modeling. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Compound Interest](https://avarixo.com/compound-interest-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
