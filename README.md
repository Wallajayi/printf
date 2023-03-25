_PRINTF

About This Project:

-----------------------------------------------------------

* This is a recreation of the C standard library function printf.
* The function writes output to standard output.
* This project involves most of the major concepts of C programming language.
* The project calls in various variadic functions.
* The project was done as a team work with 2 contributors - Ajayi Awwal and Sokhohlo Sali, with the intention of learning more about team colaboration using Git and also enabling work flow with so many files.

Description:
--------------------------------------------

The function _printf uses the PROTOTYPE int _printf(const char *format, ...);. The format string is composed of zero or more directives. See man 3 printf for more detail. _printf will return the number of characters printed (excluding the null byte used to end output to strings) and will write output to stdout, the standard output stream. The function writes under the control of a format string that specifies how subsequent arguments (accessed via the variable-length argument facilities of stdarg) are converted for output.


Usage:
------------------------------------------
* Prints a string to the standard output, returning the number of characters if succesful 0r -1 on error.
* To use the _printf function,compile all .c files in the repository and include the header main.h with any main function.
* Calling :_printf("format string", arguments...) format string contain either conversion specifiers,flags,length modfiers,field width,precision and regular characters.

