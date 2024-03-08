# CMake cache variables to build LLVM

With this feel free to either search the docs, or most probably the source files :(
as many of them are not documented and you have to see the CMakeLists.txt on the repo tree

As a tip use git grep or any kink of search into files

Also use `cmake ... -LA` to see set and unset cache variables


## General
- CMAKE_ADDR2LINE
- CMAKE_AR
- CMAKE_ASM_COMPILER
- CMAKE_ASM_COMPILER_AR
- CMAKE_ASM_COMPILER_CLANG_SCAN_DEPS

- CMAKE_CXX_STANDARD

## LLVM

- LLVM_ENABLE_LTO

## clang

- CLANG_DEFAULT_CXX_STDLIB
- CLANG_DEFAULT_LINKER
- CLANG_DEFAULT_OBJCOPY
- CLANG_DEFAULT_UNWINDLIB
- CLANG_DEFAULT_RTLIB

## libc++

- LIBCXX_HARDENING_MODE

