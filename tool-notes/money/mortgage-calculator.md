# Mortgage Calculator — reproducible reference

**Open the live Avarixo utility:** [Mortgage Calculator](https://avarixo.com/mortgage-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Estimate the principal-and-interest payment for a fixed-rate amortizing home loan. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
principal = 200000
monthly_rate = 0.06 / 12
months = 30 * 12
payment = principal * monthly_rate / (1 - (1 + monthly_rate) ** (-months))
print(round(payment, 2))
```

**Illustrative result:** 1199.10 dollars per month.

## Interpret carefully

Property taxes, insurance and fees are not represented by this payment formula. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Mortgage Calculator](https://avarixo.com/mortgage-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
