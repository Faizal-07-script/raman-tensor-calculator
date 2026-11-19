# Raman Tensor Calculator — Version 5

[Open the calculator](https://faizal-07-script.github.io/raman-tensor-calculator/)
· [Full website and documentation](https://faizal-07-script.github.io/rotation-raman-tensor-calculation/)

This website opens directly in the calculator. Choose the crystal, surface
(hkl) for the normal Z, in-plane X reference [uvw], and polarization. In
**A · Input review**, select **Check current inputs** to check the axes,
rotated tensors and Jones states. Select **Run calculation** for
**B · Polar plots** and **C · Step-by-step calculation**.
The calculator starts with a blank result pane. The standard scan plots
unnormalized intensity in 0.5° steps.

The results include polar plots, the final intensity equation and numbered
matrix steps. English explanations and new symbol definitions appear on the
left; the complete mathematics appears on the right. The two columns stack
on narrow screens. Silicon (500), VV, is the starting example.

For orthorhombic Ag, **Sum Ag Component Intensities** adds a plot and CSV
column for I(xx) + I(yy) + I(zz), following the supplied slide.

The Python notebook is **261024 - Raman Tensor Rotation Ver 5.0**.
The scientific engine and downloads match the full website. Run its 22 cells
in order; each cell prints a completion message. The program ZIP includes
the input examples, documentation and both mathematical export views.

Source and reference notes are available in the full website and the notebook.
See `Saito-sensei feedback.md` for completed work and pending independent review.

## Update

Prepare and test the full release first. From that checkout, run:

```bash
python scripts/prepare_calculator_site.py --output /path/to/raman-tensor-calculator
```

Commit the resulting files in this repository. GitHub Pages publishes `dist/`.
