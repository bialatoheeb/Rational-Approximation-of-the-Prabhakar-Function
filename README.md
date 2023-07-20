# Rational-Approximation-of-Prabhakar-Function

This python script implements a rational approximation of the Prabhakar function (three parameter Mittag Leffler function). For a detailed discussion of the approximation method, we refer the reader to [1].

The notebook test.ipynb contains several test with some known functions and equalities, and others that compare our results with the optimal parabolic contour (OPC) algorithm of Garrappa [2].  

The mittag_leffler.py and ml_internal.py (<https://github.com/khinsen/mittag-leffler/tree/master>) is the OPC algorithm implementation written in python by Konrad Hinsen. The scripts are used just for comparison purposes in this project and the copyright of the scripts remains with the original author.

The notebook rational_approximation_2_prabhakar_function.ipynb contains several assertions which might not be exhaustive, we implore the reader/user to call  our attention to any further assertions that the code might require. All contributions are welcome. 


Copyright (c) 2023 Toheeb A. Biala (biala4mat@gmail.com), Y. O. Afolabi and I. O. Sarumi 


### References
1. Y. O. Afolabi, T. A. Biala, I. O. Sarumi and B. A. Wade, `Global-Type Rational Approximations of the Three-Parameter Mittag-Leffler Functions Based on Polynomial Bases Functions` Submitted
2. R. Garrappa, `Numerical evaluation of two and three parameter mittag- leffler functions`, SIAM Journal on Numerical Analysis 53 (3) (2015) 1350–1369.

