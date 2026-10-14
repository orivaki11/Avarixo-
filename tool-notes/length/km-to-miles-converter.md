# KM to Miles — reproducible reference

**Open the live Avarixo utility:** [KM to Miles](https://avarixo.com/km-to-miles-converter/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## When to convert

Useful for comparing dimensions in international product specifications, construction plans and distance records. The input uses **kilometers** and the result uses **miles**; check these units before comparing values.

## Conversion rule

Multiply the input in kilometers by 0.62137119224 to obtain miles.

## Python 3 worked check

```python
value = 5
converted = value * 0.62137119224
print(round(converted, 6))
```

**Example:** 5 kilometers ≈ **3.1068559612 miles**. The code rounds its printed result for display only.

## Accuracy notes

The conversion uses international length definitions (one inch is exactly 0.0254 meter). The original instrument's precision limits how many result digits are meaningful. Confirm the resulting number with the [interactive Avarixo KM to Miles](https://avarixo.com/km-to-miles-converter/), especially if rounding or unit selection matters for a real task.

*Independent reference example; not a substitute for instrument calibration or professional specifications.*
