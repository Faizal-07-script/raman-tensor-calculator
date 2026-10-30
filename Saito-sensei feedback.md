# Saito-sensei’s Feedback — Version 5

Updated 31 October 2026.

| Feedback | Status and where to check |
| --- | --- |
| Print a message after every cell | Done. All 22 cells print “Run completed successfully.”, the cell number, what is ready and the next step. |
| Explain what to enter, especially in the last cells | Done. Each cell has short input and output notes. QUICKSTART.md lists the controls, units and expected starting values. |
| Supply an example that runs without editing the code | Done. Cell 22 loads silicon (500), T2g, d=1, VV and shows its polar plot. Matching input JSON files are included. |
| Show X, Y and Z, and construct the complete transformation matrix | Done. X is selected in the surface; Y is calculated from Z × X. Input review shows all three axes, T, TᵀT and det(T)=+1. |
| Show the preparation before the long intensity calculation | Done. Review inputs checks the geometry, tensors and optical states without running an intensity scan. |
| Number the operations so they can be discussed in a meeting | Done. Input groups and mathematical operations have step numbers. |
| Define symbols before they are used | Done. The explained view defines new symbols beside their first equation. The complete symbol list is also exported. |
| Make the analytical intensity easy to find | Done. The final equation appears beside the plots and in the last mathematical section. The derivation uses the original tensor coefficients, without K/C/D aliases. |
| Compare numerical and analytical results | Automated checks compare the explicit final expressions with the matrix calculation. The silicon benchmark covers 18 cases. A complete, equation-by-equation comparison with all results of Ni-san’s paper is still pending. |
| Ask other people to test the program | Pending independent review. QUICKSTART.md contains the fresh-kernel test and the information each tester should record. Automated checks do not replace a colleague’s run. |
| Ask Kumar-san about program documentation | Pending consultation. The current documentation is ready for review; no consultation or approval is claimed. |

The two websites and Python download use the same scientific functions.
The calculator-only website has the numbered input cards, optional guide,
input review, plots and both mathematical views. The full website also keeps
the introduction, tutorials and references.
