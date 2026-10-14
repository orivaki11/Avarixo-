# Grams to Pounds — reproducible reference

**Open the live Avarixo utility:** [Grams to Pounds](https://avarixo.com/grams-to-pounds-converter/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## When to convert

Useful for checking product weights, parcel limits, ingredient masses and gym measurements. The input uses **grams** and the result uses **avoirdupois pounds**; check these units before comparing values.

## Conversion rule

Multiply the input in grams by 0.0022046226218 to obtain avoirdupois pounds.

## Python 3 worked check

```python
value = 500
converted = value * 0.0022046226218
print(round(converted, 6))
```

**Example:** 500 grams ≈ **1.1023113109 avoirdupois pounds**. The code rounds its printed result for display only.

## Accuracy notes

The example uses avoirdupois mass units. A mass ounce is different from a fluid ounce; the defined international pound is 0.45359237 kilogram. Confirm the resulting number with the [interactive Avarixo Grams to Pounds](https://avarixo.com/grams-to-pounds-converter/), especially if rounding or unit selection matters for a real task.

*Independent reference example; not a substitute for instrument calibration or professional specifications.*
