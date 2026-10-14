# Ounces to Grams — reproducible reference

**Open the live Avarixo utility:** [Ounces to Grams](https://avarixo.com/ounces-to-grams-converter/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## When to convert

Useful for checking product weights, parcel limits, ingredient masses and gym measurements. The input uses **ounces** and the result uses **grams**; check these units before comparing values.

## Conversion rule

Multiply the input in ounces by 28.349523125 to obtain grams.

## Python 3 worked check

```python
value = 8
converted = value * 28.349523125
print(round(converted, 6))
```

**Example:** 8 ounces ≈ **226.796185 grams**. The code rounds its printed result for display only.

## Accuracy notes

The example uses avoirdupois mass units. A mass ounce is different from a fluid ounce; the defined international pound is 0.45359237 kilogram. Confirm the resulting number with the [interactive Avarixo Ounces to Grams](https://avarixo.com/ounces-to-grams-converter/), especially if rounding or unit selection matters for a real task.

*Independent reference example; not a substitute for instrument calibration or professional specifications.*
