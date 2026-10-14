# LBS to KG — reproducible reference

**Open the live Avarixo utility:** [LBS to KG](https://avarixo.com/lbs-to-kg-converter/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## When to convert

Useful for checking product weights, parcel limits, ingredient masses and gym measurements. The input uses **avoirdupois pounds** and the result uses **kilograms**; check these units before comparing values.

## Conversion rule

Multiply the input in avoirdupois pounds by 0.45359237 to obtain kilograms.

## Python 3 worked check

```python
value = 5
converted = value * 0.45359237
print(round(converted, 6))
```

**Example:** 5 avoirdupois pounds ≈ **2.26796185 kilograms**. The code rounds its printed result for display only.

## Accuracy notes

The example uses avoirdupois mass units. A mass ounce is different from a fluid ounce; the defined international pound is 0.45359237 kilogram. Confirm the resulting number with the [interactive Avarixo LBS to KG](https://avarixo.com/lbs-to-kg-converter/), especially if rounding or unit selection matters for a real task.

*Independent reference example; not a substitute for instrument calibration or professional specifications.*
