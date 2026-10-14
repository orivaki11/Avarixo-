# Salary to Hourly — reproducible reference

**Open the live Avarixo utility:** [Salary to Hourly](https://avarixo.com/salary-to-hourly-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Convert gross annual compensation to an illustrative hourly equivalent. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
annual_salary, weeks, hours_per_week = 62400, 52, 40
hourly_equivalent = annual_salary / (weeks * hours_per_week)
print(hourly_equivalent)
```

**Illustrative result:** 30 dollars per hour.

## Interpret carefully

Paid holidays, long hours, overtime and benefits can change real compensation comparisons. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Salary to Hourly](https://avarixo.com/salary-to-hourly-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
