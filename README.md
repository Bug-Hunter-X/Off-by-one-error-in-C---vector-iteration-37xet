# Off-by-one Error in C++ Vector Iteration

This repository demonstrates a common off-by-one error in C++ when iterating over a `std::vector`. The error arises from incorrectly using the `<=` operator in the loop condition, leading to an attempt to access an element beyond the valid range of the vector.

The `bug.cpp` file contains the erroneous code, while `bugSolution.cpp` provides the corrected version.