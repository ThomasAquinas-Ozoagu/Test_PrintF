# Test_PrintF
This directory contains my practice files for the printf project

# PSEUDOCODE v1
  Create a function
    void _printf(int argc, char* argv[])
  create int count = 0
  cylce through argv[1]
    if a-z or A-Z _putchar()
    if % check next character
      if d _print_int(argv[count + 1])
      if s _print_str(argv[count + 2])
      //for every new identify, increase count by 1 to print the next argument using the correct formating function
      //after printing each argument, program control returns to cycling through the first argument which is the main string.
      Remember to consider \n, \t and others.

# NOTES
1. To handle multiple arguments, use variadic functions
2.   To achieve the above, add the header stdarg.h
3.   This involves va_list, va_start & va_arg
4. Format specifiers
5.   %d: int
6.   %u unsigned decimal int
7.   %f float
8.   %s null-terminated string
9.   %c char
10.   %x hexadecimal lowercase
11.   %X hexadecimal uppercase
12. Buffer: final formatted output
13.   Using Buffers improves performance by reducing number of write operations
14.   Wait tll buffer is filled or till \n is encountered before printing
15.   Force buffer to std out with fflush(stdout)
16.   d

# PSEUDOCODE v2
