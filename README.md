The printf function sends formatted output to stdout. A custom _printf() for learning purposes was developed by cohort #14, An all females cohort, the first of its kind. By students Prudence Maseko and Adebola Oluwadare. _printf() function format string is a character string, beginning and ending in its initial shift state, if any. These arguments are placed using the percentage '%' operator

The available convertion specifiers are:

%c: Prints a single character. %s: Prints a string of characters. %d: Prints integers. %i: Prints integers. %b: Prints the binary representation of an unsigned decimal. %u: Prints unsigned integers %p: Prints address of pointer %x: Prints the hexadecial representation of an unsigned decimal in lowercase letters %X:Prints the hexadecial representation of an unsigned decimal in uppercase letters %r: Prints a reversed string %R: Prints the Rot13 interpretation of a string Usage All the files are to be compiled on Ubuntu 14.04 LTS Compile your code with gcc -Wall -Werror -Wextra -pedantic .c

File Descriptions
_printf.c

contains the fucntion _printf, which uses the prototype int _printf(const char *format, ...);. The format string is composed of zero or more directives. See man 3 printf for more detail. _printf will return the number of characters printed (excluding the null byte used to end output to strings) and will write output to stdout, the standard output stream.
_putchar.c

contains the function _putchar, which writes a character to stdout.
holberton.h *contains all function prototypes used for _printf.

man_3_printf

manual page for the custom _printf function.
functions.c functions1.c functions2.c

contains all function of each specifier used for _printf.
all function have its own description inside the file.
handle_print.c

contains arguments types used for _printf.
get_flags.c

contains all function for each flag use for _printf.
utils.c

contains some necessary functionalities for _printf.
ger_width.c

contains functions to get width for spcifics spcifiers.
writee_handlers.c

contains write functions.
