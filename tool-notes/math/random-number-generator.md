# Random Number Generator — reproducible reference

**Open the live Avarixo utility:** [Random Number Generator](https://avarixo.com/random-number-generator/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Draw an integer from a specified inclusive range. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
import secrets
minimum, maximum = 1, 6
value = minimum + secrets.randbelow(maximum - minimum + 1)
print(value)
```

**Illustrative result:** A random integer from 1 through 6 inclusive.

## Interpret carefully

An unpredictable result has no fixed answer; requirements for regulated draws may differ from ordinary generators. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Random Number Generator](https://avarixo.com/random-number-generator/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
