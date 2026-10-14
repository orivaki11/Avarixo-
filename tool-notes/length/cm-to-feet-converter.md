# CM to Feet — reproducible reference

**Open the live Avarixo utility:** [CM to Feet](https://avarixo.com/cm-to-feet-converter/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## When to convert

Useful for comparing dimensions in international product specifications, construction plans and distance records. The input uses **centimeters** and the result uses **feet**; check these units before comparing values.

## Conversion rule

Multiply the input in centimeters by 0.03280839895 to obtain feet.

## Python 3 worked check

```python
value = 30.48
converted = value * 0.03280839895
print(round(converted, 6))
```

**Example:** 30.48 centimeters ≈ **1 feet**. The code rounds its printed result for display only.

## Accuracy notes

The conversion uses international length definitions (one inch is exactly 0.0254 meter). The original instrument's precision limits how many result digits are meaningful. Confirm the resulting number with the [interactive Avarixo CM to Feet](https://avarixo.com/cm-to-feet-converter/), especially if rounding or unit selection matters for a real task.

*Independent reference example; not a substitute for instrument calibration or professional specifications.*
