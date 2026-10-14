# Simple Interest — reproducible reference

**Open the live Avarixo utility:** [Simple Interest](https://avarixo.com/simple-interest-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Find uncompounded interest on principal over a specified number of years. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
principal, annual_rate, years = 5000, 0.04, 3
interest = principal * annual_rate * years
print(interest, principal + interest)
```

**Illustrative result:** 600 dollars interest; 5600 dollars total.

## Interpret carefully

Real loans may have changing balances, repayment schedules and day-count conventions. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Simple Interest](https://avarixo.com/simple-interest-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
