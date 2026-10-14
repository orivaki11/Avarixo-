# Miles to KM — reproducible reference

**Open the live Avarixo utility:** [Miles to KM](https://avarixo.com/miles-to-km-converter/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## When to convert

Useful for comparing dimensions in international product specifications, construction plans and distance records. The input uses **miles** and the result uses **kilometers**; check these units before comparing values.

## Conversion rule

Multiply the input in miles by 1.609344 to obtain kilometers.

## Python 3 worked check

```python
value = 2
converted = value * 1.609344
print(round(converted, 6))
```

**Example:** 2 miles ≈ **3.218688 kilometers**. The code rounds its printed result for display only.

## Accuracy notes

The conversion uses international length definitions (one inch is exactly 0.0254 meter). The original instrument's precision limits how many result digits are meaningful. Confirm the resulting number with the [interactive Avarixo Miles to KM](https://avarixo.com/miles-to-km-converter/), especially if rounding or unit selection matters for a real task.

*Independent reference example; not a substitute for instrument calibration or professional specifications.*
