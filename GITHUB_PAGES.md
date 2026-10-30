# GitHub Pages — Version 5

There are two repositories and two published websites:

| Repository | Website |
| --- | --- |
| `rotation-raman-tensor-calculation` | Full website: Home, introduction, tutorials, references and calculator. |
| `raman-tensor-calculator` | Calculator-only website; opens directly in the numbered input form. |

Both workflows publish `dist/`. Enable GitHub Actions as the Pages source in
Settings → Pages. The generated Python downloads and engine must match in
both repositories. The full website is the source used to prepare a release.

After validating and building the full website, prepare the second checkout:

```bash
python scripts/prepare_calculator_site.py --output /path/to/raman-tensor-calculator
```

Commit and publish the tested files in both repositories. Keep the original
reference notebooks attributed. External package versions, notebook-format
numbers and historical source metadata are separate from the program version.
