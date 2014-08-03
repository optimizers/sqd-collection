# A Collection of Symmetric and Quasi-Definite Systems

This is a collection of [symmetric and quasi-definite](http://dx.doi.org/10.1137/0805005) linear system in [MatrixMarket](http://math.nist.gov/MatrixMarket/formats.html#MMformat) format.

The systems arise from some of the [CUTE](https://github.com/mpf/Optimization-Test-Problems) quadratic optimization problems, and are output during the iterations of [an interior-point method](https://github.com/dpo/nlpy/blob/master/nlpy/optimize/solvers/cqp.py). As the iteration number grows, the system becomes more ill conditioned.

The [2x2 and 3x3 formulations](http://dx.doi.org/10.1137/120890600) of each system are given with accompanying right-hand side.

## Reference

* [D. Orban. Limited-Memory LDL<sup>T</sup> Factorization of Symmetric
  Quasi-Definite Matrices with Application to Constrained Optimization. Cahier
  du GERAD G-2013-87. GERAD, Montreal,
  Canada](http://www.gerad.ca/~orban/_static/go2013.pdf).
