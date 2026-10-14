# Hours Calculator — reproducible reference

**Open the live Avarixo utility:** [Hours Calculator](https://avarixo.com/hours-calculator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Subtract start and end times and deduct an unpaid break. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
from datetime import datetime, timedelta
start = datetime(2026, 10, 13, 9, 15)
finish = datetime(2026, 10, 13, 17, 45)
paid = (finish - start) - timedelta(minutes=30)
print(paid)
```

**Illustrative result:** 8:00:00 of paid work duration.

## Interpret carefully

Cross-midnight shifts and daylight-saving transitions require dates and time zones. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Hours Calculator](https://avarixo.com/hours-calculator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
