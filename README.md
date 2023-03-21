# gcc-cygport

Cygwin porting script for GCC 12.2.0

## Quick start

To build GCC from source, python 2 and cygport packages are required.
If faced with an error complaining about python 2, remove the line
```
error "python2.cyclass: python2 was sunsetted on 1 January, 2020.  Please use python3 instead."
```
from the file `/usr/share/cygport/cygclass/python2.cygclass`

Now run build.sh, the script should download and build all the prerequisites (MPC, MPFR, GMP and ZSTD libraries) along with the GCC.

