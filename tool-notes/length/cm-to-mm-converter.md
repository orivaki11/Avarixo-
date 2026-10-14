# CM to MM — reproducible reference

**Open the live Avarixo utility:** [CM to MM](https://avarixo.com/cm-to-mm-converter/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## When to convert

Useful for comparing dimensions in international product specifications, construction plans and distance records. The input uses **centimeters** and the result uses **millimeters**; check these units before comparing values.

## Conversion rule

Multiply the input in centimeters by 10 to obtain millimeters.

## Python 3 worked check

```python
value = 30.48
converted = value * 10
print(round(converted, 6))
```

**Example:** 30.48 centimeters ≈ **304.8 millimeters**. The code rounds its printed result for display only.

## Accuracy notes

The conversion uses international length definitions (one inch is exactly 0.0254 meter). The original instrument's precision limits how many result digits are meaningful. Confirm the resulting number with the [interactive Avarixo CM to MM](https://avarixo.com/cm-to-mm-converter/), especially if rounding or unit selection matters for a real task.

*Independent reference example; not a substitute for instrument calibration or professional specifications.*
