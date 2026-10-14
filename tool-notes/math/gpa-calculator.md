# GPA Calculator — reproducible reference

**Open the live Avarixo utility:** [GPA Calculator](https://avarixo.com/gpa-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Calculate a credit-weighted grade-point average. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
courses = [(4.0, 3), (3.0, 3)]  # grade point, credits
gpa = sum(g * c for g, c in courses) / sum(c for _, c in courses)
print(gpa)
```

**Illustrative result:** 3.5 on a 4-point scale.

## Interpret carefully

Schools differ in grade scales, repeated-course treatment and whether ungraded credits count. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo GPA Calculator](https://avarixo.com/gpa-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
