# Hourly to Salary — reproducible reference

**Open the live Avarixo utility:** [Hourly to Salary](https://avarixo.com/hourly-to-salary-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Annualize gross hourly compensation at an assumed weekly work schedule. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
hourly_rate, paid_hours_per_week, paid_weeks = 25, 40, 52
annual_gross = hourly_rate * paid_hours_per_week * paid_weeks
print(annual_gross)
```

**Illustrative result:** 52000 dollars gross per year.

## Interpret carefully

Unpaid leave, overtime, bonuses, taxes and benefits are not accounted for. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Hourly to Salary](https://avarixo.com/hourly-to-salary-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
