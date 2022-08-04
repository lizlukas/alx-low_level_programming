stdarg.h is a header in the C standard library of the C programming language that allows functions to accept an indefinite number of arguments.[1] It provides facilities for stepping through a list of function arguments of unknown number and type. C++ provides this functionality in the header cstdarg.

The contents of stdarg.h are typically used in variadic functions, though they may be used in other functions (for example, vprintf) called by variadic functions.
A.2 Variadic Functions
ISO C defines a syntax for declaring a function to take a variable number or type of arguments. (Such functions are referred to as varargs functions or variadic functions.) However, the language itself provides no mechanism for such functions to access their non-required arguments; instead, you use the variable arguments macros defined in stdarg.h.

This section describes how to declare variadic functions, how to write them, and how to call them properly.

Compatibility Note: Many older C dialects provide a similar, but incompatible, mechanism for defining functions with variable numbers of arguments, using varargs.h.
