# Discount Calculator — reproducible reference

**Open the live Avarixo utility:** [Discount Calculator](https://avarixo.com/discount-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Calculate a discounted price from a known original price and percentage reduction. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
original, discount_pct = 80, 15
final_price = original * (1 - discount_pct / 100)
print(final_price)
```

**Illustrative result:** 68 dollars before tax.

## Interpret carefully

Sequential discounts have different percentage bases; two discounts must be applied in order. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Discount Calculator](https://avarixo.com/discount-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
