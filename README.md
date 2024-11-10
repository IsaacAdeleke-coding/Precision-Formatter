# Precision Formatter

A simple C++ project to convert `double` values to formatted strings with fixed precision. This project demonstrates modular C++ programming by separating declarations, definitions, and main logic into individual files.

## Project Structure

- **DoubleConverter.hpp**: Declares `doubleToString` function.
- **DoubleConverter.cpp**: Defines `doubleToString` function, which converts a `double` to a formatted `string` with configurable precision.
- **main.cpp**: Tests `doubleToString` functionality.

## Usage

```cpp
#include "DoubleConverter.hpp"

int main() {
    double number = 12.34;
    std::cout << doubleToString(number) << std::endl;
    return 0;
}
Compilation
g++ -o main main.cpp DoubleConverter.cpp
./main

Example Output
12.3


