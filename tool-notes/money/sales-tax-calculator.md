# Sales Tax Calculator — reproducible reference

**Open the live Avarixo utility:** [Sales Tax Calculator](https://avarixo.com/sales-tax-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Compute an illustrative purchase total after a stated sales-tax rate. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
subtotal, tax_rate = 120, 0.08
sales_tax = subtotal * tax_rate
print(round(sales_tax, 2), round(subtotal + sales_tax, 2))
```

**Illustrative result:** 9.60 dollars tax; 129.60 dollars total.

## Interpret carefully

Local rates and tax exemptions vary; some listed prices already include tax. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Sales Tax Calculator](https://avarixo.com/sales-tax-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
