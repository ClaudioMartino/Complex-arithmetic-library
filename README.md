# Complex arithmetic library

A custom complex arithmetic library implemented in c++, for those who cannot rely on [std::complex](https://en.cppreference.com/w/cpp/numeric/complex)

## Getting Started
Add the `complex.hpp` file to your project and start to code using the `Cpx<T>` class.

## Examples
### FFT
The FFT has been implemented. To build and run it:
```
make fft
./fft N
```
Where `N` is the FFT size, it must be a power of 2 (default is 1024). Add the `-DBENCH` flag to measure the execution time, too.

## Test
To run the test routines:
```
make test
./test
```

## Version History
* 0.1
    * Initial Release

