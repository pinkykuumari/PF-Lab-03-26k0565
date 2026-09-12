# C Basics

## 1. Data Types

| Type   | Description |
|--------|--------------|
| int    | Stores whole numbers (e.g. 10, -5) |
| float  | Stores single-precision decimal numbers |
| double | Stores double-precision decimal numbers (more accurate than float) |
| char   | Stores a single character (e.g. 'A') |
| bool   | Stores true or false values |
| void   | Represents "no value"; used for functions that don't return anything |

## 2. Format Specifiers

| Specifier | Meaning |
|-----------|---------|
| %d  | Signed decimal integer |
| %u  | Unsigned decimal integer |
| %o  | Unsigned octal number |
| %x  | Unsigned hexadecimal (lowercase) |
| %X  | Unsigned hexadecimal (uppercase) |
| %f  | Floating-point number |
| %e  | Scientific (exponential) notation |
| %c  | Single character |
| %s  | String |
| %ld | Long integer |

## 3. Input/Output Functions

- **scanf()** – reads formatted input from the user (e.g. numbers, characters) based on format specifiers.
- **printf()** – prints formatted output to the screen.
- **getchar()** – reads a single character from input.
- **putchar()** – prints a single character to the screen.
- **fgets()** – reads a full line of text (including spaces) safely, with a size limit.
- **puts()** – prints a string to the screen followed by a new line.

## 4. Escape Sequences

| Sequence | Meaning |
|----------|---------|
| \n | New line |
| \t | Tab space |
| \\ | Backslash character |
| \" | Double quote |
| \' | Single quote |

## 5. Precision

Precision for floating-point output is set by placing a number after a dot inside the format specifier, like `%.2f` for 2 decimal places or `%.4f` for 4 decimal places. This controls how many digits appear after the decimal point — it doesn't change the actual stored value, just how it's displayed.
