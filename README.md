This repository demonstrates a common off-by-one error in C++ when accessing elements in a std::vector. The bug.cpp file contains the erroneous code, while bugSolution.cpp provides the corrected version.  The error results in undefined behavior due to accessing memory beyond the allocated vector size. The solution addresses this by carefully adjusting the loop condition to prevent out-of-bounds access.