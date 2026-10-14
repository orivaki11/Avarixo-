# Kelvin to Celsius — reproducible reference

**Open the live Avarixo utility:** [Kelvin to Celsius](https://avarixo.com/kelvin-to-celsius-converter/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## When to convert

Useful when comparing weather readings, scientific data or instrument specifications across temperature scales. The input uses **kelvin** and the result uses **degrees Celsius**; check these units before comparing values.

## Conversion rule

Celsius = Kelvin − 273.15

## Python 3 worked check

```python
value = 293.15
converted = value - 273.15
print(round(converted, 6))
```

**Example:** 293.15 kelvin ≈ **20 degrees Celsius**. The code rounds its printed result for display only.

## Accuracy notes

Temperature scales have different zero points. This equation applies to absolute temperature readings; a change in temperature requires the corresponding interval conversion. Kelvin does not use the degree symbol. Confirm the resulting number with the [interactive Avarixo Kelvin to Celsius](https://avarixo.com/kelvin-to-celsius-converter/), especially if rounding or unit selection matters for a real task.

*Independent reference example; not a substitute for instrument calibration or professional specifications.*
