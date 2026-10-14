# Margin Calculator — reproducible reference

**Open the live Avarixo utility:** [Margin Calculator](https://avarixo.com/margin-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Compute gross profit margin using selling price as the denominator. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
revenue, direct_cost = 100, 60
margin_pct = (revenue - direct_cost) / revenue * 100
print(margin_pct)
```

**Illustrative result:** 40% gross margin.

## Interpret carefully

Margin differs from markup; indirect expenses can reduce net profitability. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Margin Calculator](https://avarixo.com/margin-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
