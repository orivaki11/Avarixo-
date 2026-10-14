# CM to Inches — reproducible reference

**Open the live Avarixo utility:** [CM to Inches](https://avarixo.com/cm-to-inches-converter/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## When to convert

Useful for comparing dimensions in international product specifications, construction plans and distance records. The input uses **centimeters** and the result uses **inches**; check these units before comparing values.

## Conversion rule

Multiply the input in centimeters by 0.3937007874 to obtain inches.

## Python 3 worked check

```python
value = 30.48
converted = value * 0.3937007874
print(round(converted, 6))
```

**Example:** 30.48 centimeters ≈ **12 inches**. The code rounds its printed result for display only.

## Accuracy notes

The conversion uses international length definitions (one inch is exactly 0.0254 meter). The original instrument's precision limits how many result digits are meaningful. Confirm the resulting number with the [interactive Avarixo CM to Inches](https://avarixo.com/cm-to-inches-converter/), especially if rounding or unit selection matters for a real task.

*Independent reference example; not a substitute for instrument calibration or professional specifications.*
