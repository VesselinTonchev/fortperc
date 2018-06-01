# fortperc

See generated documentation [here](https://anjohan.github.io/fortperc/html/).

This library contains various useful functions for doing percolation in Fortran.

[`src/hk.f90`](https://github.com/anjohan/fortperc/blob/master/src/hk.f90) contains a Fortran implementation of the Hoshen-Kopelman algorithm, inspired by Tobin Fricke's C implementation at https://gist.github.com/tobin/909424.

[`src/percolation.f90`](https://github.com/anjohan/fortperc/blob/master/src/percolation.f90) contains subroutines/functions which calculate common quantities in percolation, such as the size distribution of clusters, the density of the percolating cluster, etc.