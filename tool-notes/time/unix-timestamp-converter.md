# Unix Timestamp Converter — reproducible reference

**Open the live Avarixo utility:** [Unix Timestamp Converter](https://avarixo.com/unix-timestamp-converter/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Interpret a POSIX timestamp in UTC. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
from datetime import datetime, timezone
print(datetime.fromtimestamp(86400, tz=timezone.utc).isoformat())
```

**Illustrative result:** 1970-01-02T00:00:00+00:00.

## Interpret carefully

A number expressed in milliseconds is one thousand times a seconds-based timestamp. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Unix Timestamp Converter](https://avarixo.com/unix-timestamp-converter/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
