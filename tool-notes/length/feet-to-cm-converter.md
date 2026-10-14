# Feet to CM — reproducible reference

**Open the live Avarixo utility:** [Feet to CM](https://avarixo.com/feet-to-cm-converter/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## When to convert

Useful for comparing dimensions in international product specifications, construction plans and distance records. The input uses **feet** and the result uses **centimeters**; check these units before comparing values.

## Conversion rule

Multiply the input in feet by 30.48 to obtain centimeters.

## Python 3 worked check

```python
value = 3
converted = value * 30.48
print(round(converted, 6))
```

**Example:** 3 feet ≈ **91.44 centimeters**. The code rounds its printed result for display only.

## Accuracy notes

The conversion uses international length definitions (one inch is exactly 0.0254 meter). The original instrument's precision limits how many result digits are meaningful. Confirm the resulting number with the [interactive Avarixo Feet to CM](https://avarixo.com/feet-to-cm-converter/), especially if rounding or unit selection matters for a real task.

*Independent reference example; not a substitute for instrument calibration or professional specifications.*
