# Test_PrintF
This directory contains my practice files for the printf project

# PSEUDOCODE
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
