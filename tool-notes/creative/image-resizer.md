# Image Resizer — reproducible reference

**Open the live Avarixo utility:** [Image Resizer](https://avarixo.com/image-resizer/)

**Collection:** [All Avarixo Tools](https://avarixo.com/avarixo-tools/)

## What this solves

Calculate new dimensions when an image is scaled without changing aspect ratio. The code below is a small **independent example**, intended as a sanity check rather than the implementation of the live website.

## Python 3 example

```python
width, height, scale = 1920, 1080, 0.5
print(round(width * scale), round(height * scale))
```

**Illustrative result:** 960 by 540 pixels.

## Interpret carefully

This snippet calculates dimensions, not image compression; increasing pixel count will not restore detail. Change the example inputs and check the magnitude, units, rounding and assumptions. The [Avarixo Image Resizer](https://avarixo.com/image-resizer/) offers a browser interface for trying your own values; review its on-page instructions before relying on a result.

*Documentation note: the values above illustrate a common calculation, not a claim that Avarixo has independently validated the user's input.*
