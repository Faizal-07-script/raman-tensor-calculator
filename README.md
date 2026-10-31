# Raman Tensor Calculator — Version 5

[Open the calculator](https://faizal-07-script.github.io/raman-tensor-calculator/)
· [Full website and documentation](https://faizal-07-script.github.io/rotation-raman-tensor-calculation/)

This website opens directly in the calculator. Choose the crystal, surface,
in-plane direction and polarization. Use **Review inputs** to check X, Y, Z and
the frame matrix, then **Run calculation**.

The results include polar plots, the final intensity equation and numbered
matrix steps. English explanations and new symbol definitions appear on the
left; the complete mathematics appears on the right. The two columns stack
on narrow screens. Silicon (500), VV, is the starting example.

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
