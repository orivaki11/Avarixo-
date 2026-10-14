# Word Counter — reproducible reference

**Open the live Avarixo utility:** [Word Counter](https://avarixo.com/word-counter/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Count space-separated words in a short text example. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
text = 'A quick tool helps writers check their drafts.'
print(len(text.split()))
```

**Illustrative result:** 8 words in this illustrative sentence.

## Interpret carefully

Punctuation, hyphenated words and Unicode tokenization can differ between platforms. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Word Counter](https://avarixo.com/word-counter/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
