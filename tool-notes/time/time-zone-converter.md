# Time Zone Converter — reproducible reference

**Open the live Avarixo utility:** [Time Zone Converter](https://avarixo.com/time-zone-converter/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Translate the same instant between UTC and a named IANA time zone. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
from datetime import datetime, timezone
from zoneinfo import ZoneInfo
utc = datetime(2026, 10, 14, 14, 0, tzinfo=timezone.utc)
print(utc.astimezone(ZoneInfo('America/New_York')).strftime('%H:%M %Z'))
```

**Illustrative result:** 10:00 EDT on October 14, 2026.

## Interpret carefully

Daylight-saving changes mean a fixed numeric offset is not an all-year substitute for a named zone. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Time Zone Converter](https://avarixo.com/time-zone-converter/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
