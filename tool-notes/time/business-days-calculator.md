# Business Days — reproducible reference

**Open the live Avarixo utility:** [Business Days](https://avarixo.com/business-days-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Count Monday-through-Friday weekdays over a date interval with the end date excluded. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
from datetime import date, timedelta
start = date(2026, 10, 12)
weekdays = sum((start + timedelta(days=i)).weekday() < 5 for i in range(7))
print(weekdays)
```

**Illustrative result:** 5 weekdays across a Monday-through-Sunday span.

## Interpret carefully

Public holidays and regional workweek rules are not included in this basic check. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Business Days](https://avarixo.com/business-days-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
