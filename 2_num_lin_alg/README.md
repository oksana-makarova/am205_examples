# Harvard Applied Math 205: Code Examples
## Unit 2: Numerical Linear Algebra

##### norm.py
This program demonstrates how the value of the norm ||x||<sub>p</sub> changes
as a function of p, for an arbitrary vector x.

##### timing\_test.py
This program demonstrates two different timing routines in Python: the
**clock** function for measuring processor time, and **time** function for
measuring wall clock time.

##### lu\_time.py
This program measures the time taken by Python's LU factorization routine,
as a function of the matrix size. (Note that Python's linear algebra routines
are based on the [LAPACK library](http://www.netlib.org/lapack/), a highly
optimized library for dense matrix calculations.)

##### chol\_time.py
The program measures the time taken by Python's Cholesky factorization routine,
as a function of the matrix size.
