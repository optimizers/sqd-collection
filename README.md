# A Collection of Symmetric and Quasi-Definite Systems

This data set may be cited by referencing:

[![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.16630.svg)](http://dx.doi.org/10.5281/zenodo.16630)

This is a collection of [symmetric and quasi-definite](http://dx.doi.org/10.1137/0805005) linear systems in [MatrixMarket](http://math.nist.gov/MatrixMarket/formats.html#MMformat) format.

The systems arise from some of the [CUTE](https://github.com/mpf/Optimization-Test-Problems) quadratic optimization problems, and are output during the iterations of [an interior-point method](https://github.com/dpo/nlpy/blob/master/nlpy/optimize/solvers/cqp.py). As the iteration number grows, the system becomes more ill conditioned.

The [2x2 and 3x3 formulations](http://dx.doi.org/10.1137/120890600) of each system are given with accompanying right-hand side.

## Reference

D. Orban. Limited-Memory LDL<sup>T</sup> Factorization of Symmetric
Quasi-Definite Matrices with Application to Constrained Optimization. Cahier
du GERAD G-2013-87. GERAD, Montreal, Canada.
<br>
[Technical Report](https://www.gerad.ca/papers/G-2013-87.pdf).
<br>
[Published version, Numerical Algorithms, November 2014](http://link.springer.com/article/10.1007/s11075-014-9933-x).
