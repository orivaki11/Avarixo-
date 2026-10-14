# Color Picker — reproducible reference

**Open the live Avarixo utility:** [Color Picker](https://avarixo.com/color-picker/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Understand six-digit hexadecimal RGB color notation. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
hex_value = '#4A90E2'
rgb = tuple(int(hex_value[i:i+2], 16) for i in (1, 3, 5))
print(rgb)
```

**Illustrative result:** (74, 144, 226).

## Interpret carefully

Choosing a color does not ensure accessible contrast against surrounding elements. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Color Picker](https://avarixo.com/color-picker/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
