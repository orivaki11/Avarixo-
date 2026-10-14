# Loan Calculator — reproducible reference

**Open the live Avarixo utility:** [Loan Calculator](https://avarixo.com/loan-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Find equal repayments on a fixed-rate amortizing personal loan. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
principal, r, n = 10000, 0.12 / 12, 24
payment = principal * r / (1 - (1 + r) ** (-n))
print(round(payment, 2))
```

**Illustrative result:** About 470.73 dollars monthly.

## Interpret carefully

An APR may include fees and other terms that a simple nominal-rate amortization formula misses. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Loan Calculator](https://avarixo.com/loan-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
