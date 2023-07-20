# Rational-Approximation-of-Prabhakar-Function

The Mscript implements a rational approximation of the Prabhakar function (three parameter Mittag Leffler function). For a detailed discussion of the approximation method, we refer the reader to [1].

The script test_ml.py contains pretty much all the tests that I have run until now. They cover very little of the total functionality of the code. My personal needs are limited to beta=1, gamma=1, and z real, so I might never get around to add decent tests for everything. Contributions are welcome.

The module ml_internal.py contains the parts that I would like to compile using Pythran for speed, but I haven't succeeded yet. Client code should only import module mittag_leffler.


### References
1. Y. O. Afolabi, T. A. Biala, I. O. Sarumi and B. A. Wade, `Global-Type Rational Approximations of the Three-Parameter Mittag-Leffler Functions Based on Polynomial Bases Functions` Submitted

