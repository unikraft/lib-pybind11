# pybind11 for Unikraft
This is the port of pybind11 for Unikraft as external library.
 
## Build
pybind11 depends on the following libraries, that need to be added to `Makefile` in
this order:
 
* `pthreads`, e.g. `pthread-embedded`
* C++ libraries: `compiler-rt`, `libcxx`, `libcxxabi`, `libunwind`
* `libc`, e.g. `newlib`
* `python3`
