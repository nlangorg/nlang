Neptunium Language Front End
============================

Welcome. This directory and its subdirectories contain the source code for
Nlang, a Neptunium front end for the LLVM compiler infrastructure project.

Like Clang, Nlang can be used not only for compiling but also for creating
different tools. One example is Nlang-Format, the Neptunium source code
formatter.

Furthermore, all tools, utilities, and subprojects have a library structure
with the goal of being easily reusable.

Similarly to Flang, the compiler lowers the produced AST into a custom MLIR
dialect called NIR or Neptunium IR.

Nlang is open source software that is distributed under the Apache License v2.0.
See LICENSE.txt for license information.

Please see the Sphinx documentation provided in docs/ for further assistance
with Nlang, and in particular docs/GettingStarted.rst for getting started with
the project and docs/CMake.rst for a list of the available CMake option.

If you are interested in the internals of the compiler, visit docs/Doxygen.rst
for a guide on building the Doxygen documentation.

Please read BUGS.txt and SECURITY.txt for reporting bugs and vulnerabilities.

