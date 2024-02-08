# Spreadsheet
#### Excel analog, work with formulas and cells, search for cyclic dependencies

## Features:
- Cyclic search
- Formula calculation
- Cell references
- Cell Validation

## Build
Additional components need to be downloaded for the build:

- ANTLR - https://www.antlr.org/download/antlr-4.13.1-complete.jar
- ANTLR Runtime - https://www.antlr.org/download/antlr4-cpp-runtime-4.13.1-source.zip

Place these components in the project folder so that the structure looks like this:
    .
    ├── antlr-4.13.1-complete.jar
    ├── antlr4_runtime
    ├── cell.cpp
    ├── cell.h
    ├── CMakeLists.txt
    ├── ...

Example of building a cmake project on a Linux:

    mkdir ./build
    cd ./build
    cmake ../
    cmake --build .

