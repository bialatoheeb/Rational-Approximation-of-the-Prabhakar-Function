# Rational-Approximation-of-the-Prabhakar-Function

This jupyter notebook implements a rational approximation of the Prabhakar function (three parameter Mittag Leffler function). For a detailed discussion of the approximation method, we refer the reader to [1].

The notebook test.ipynb contains several test with some known functions and equalities, and others that compare our results with the optimal parabolic contour (OPC) algorithm of Garrappa [2].  

The [mittag_leffler.py and ml_internal.py](https://github.com/khinsen/mittag-leffler/tree/master) describes the implementation of the OPC algorithm which was written in python by Konrad Hinsen. The scripts are used just for comparison purposes in this project and the copyright remains with the original author.

The notebook rational_approximation_2_prabhakar_function.ipynb contains several assertions which might not be exhaustive, we implore the reader/user to call  our attention to any further assertions found. All contributions are gladly welcomed. 


Copyright (c) 2023 Toheeb A. Biala (biala4mat@gmail.com), Y. O. Afolabi and I. O. Sarumi 


### References
1. Y. O. Afolabi, T. A. Biala, I. O. Sarumi and B. A. Wade, [`Global-Pad\'e Approximation of the Three-Parameter Mittag-Leffler Function: Generalized Derivation and Numerical Implementation Issues`](https://link.springer.com/article/10.1007/s42967-024-00472-0?utm_source=rct_congratemailt&utm_medium=email&utm_campaign=nonoa_20250220&utm_content=10.1007%2Fs42967-024-00472-0), Communications on Applied Mathematics and Computation, (2025).
2. R. Garrappa, [`Numerical evaluation of two and three parameter mittag- leffler functions`](https://epubs.siam.org/doi/10.1137/140971191), SIAM Journal on Numerical Analysis 53 (3) (2015) 1350–1369.

