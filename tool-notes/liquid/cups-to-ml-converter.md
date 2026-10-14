# Cups to ML — reproducible reference

**Open the live Avarixo utility:** [Cups to ML](https://avarixo.com/cups-to-ml-converter/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## When to convert

Useful for recipes, beverage quantities and container capacities when regional conventions are identified. The input uses **U.S. customary cups** and the result uses **milliliters**; check these units before comparing values.

## Conversion rule

Multiply the input in U.S. customary cups by 236.5882365 to obtain milliliters.

## Python 3 worked check

```python
value = 2
converted = value * 236.5882365
print(round(converted, 6))
```

**Example:** 2 U.S. customary cups ≈ **473.176473 milliliters**. The code rounds its printed result for display only.

## Accuracy notes

The example uses U.S. customary volume units; an imperial gallon or an international 'cup' may have a different definition. Fluid ounces measure volume rather than mass. Confirm the resulting number with the [interactive Avarixo Cups to ML](https://avarixo.com/cups-to-ml-converter/), especially if rounding or unit selection matters for a real task.

*Independent reference example; not a substitute for instrument calibration or professional specifications.*
