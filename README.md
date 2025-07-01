# OCLint - https://oclint.org

[![GitHub Actions Status](https://github.com/oclint/oclint/workflows/Builds/badge.svg?branch=master)](https://github.com/oclint/oclint/actions)

OCLint is a static code analysis tool for improving quality and reducing defects
by inspecting C, C++ and Objective-C code.

It looks for potential problems that aren't visible to compilers, for example:

* Possible bugs - empty if/else/try/catch/finally statements
* Unused code - unused local variables and parameters
* Complicated code - high cyclomatic complexity, NPath complexity and high NCSS
* Redundant code - redundant if statement and useless parentheses
* Code smells - long method and long parameter list
* Bad practices - inverted logic and parameter reassignment
* ...

For more information, visit https://oclint.org

Make sure you have install cmake, ninja ,zstd
```
brew install cmake
brew install ninja
brew install zstd
```

Clone the repository branch that supports Xcode 16 on arm64 Mac
```
git clone -b support_Xcode16 https://github.com/Lianghuajian/oclint.git oclint 

cd oclint/oclint-scripts && ./make && cd ..
```
