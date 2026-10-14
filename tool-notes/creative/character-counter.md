# Character Counter — reproducible reference

**Open the live Avarixo utility:** [Character Counter](https://avarixo.com/character-counter/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Count Python Unicode code points for an illustrative text. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
text = 'Hello!'
print(len(text))
```

**Illustrative result:** 6 Python code points.

## Interpret carefully

Visible grapheme clusters and platform-specific UTF-16 counts can disagree for emoji or combining characters. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Character Counter](https://avarixo.com/character-counter/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
