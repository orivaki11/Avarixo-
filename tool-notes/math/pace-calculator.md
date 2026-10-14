# Pace Calculator — reproducible reference

**Open the live Avarixo utility:** [Pace Calculator](https://avarixo.com/pace-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Turn a running duration and route length into average minutes per kilometer. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
elapsed_minutes, distance_km = 30, 5
pace = elapsed_minutes / distance_km
print(pace)
```

**Illustrative result:** 6 minutes per kilometer.

## Interpret carefully

Average pace assumes a nonzero distance and is not the same as instantaneous speed. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Pace Calculator](https://avarixo.com/pace-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
