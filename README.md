# Libft_42
Explore the essence of C with 📚 42’s libft - a meticulously crafted library that illuminates each function’s purpose and mechanics, simplifying your coding journey. 🛠️✨

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
    1. [Libc Functions](#libc-functions)
    2. [Additional Functions](#additional-functions)
    3. [Bonus Functions](#bonus-functions)
    4. [Personal Functions](#personal-functions)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)


# Introduction

Libft it is a first coding project at 42 school Core Curriculum. The main goal of this project is to recreate various standard C library functions, and some additional ones, which will be used throughout our curriculum at 42. 
This project helps students understand the basic building blocks of the C programming language.

## Features

Libft consists of several sections:

1. **Libc Functions:** Some of the standard C functions
2. **Additional Functions:** Functions 42 deems will be useful for later projects
3. **Bonus Functions:** Functions 42 deems will be useful for linked list manipulation
4. **Personal Functions:** Functions students find personally useful for later projects.

## Libc Functions

We've re-coded some of the functions from the standard C library, namely:

- Memory functions: `memset`, `bzero`, `memcpy`, `memccpy`, `memmove`, `memchr`, `memcmp`
- String manipulation functions: `strlen`, `strdup`, `strcpy`, `strncpy`, `strcat`, `strncat`, `strlcat`, `strchr`, `strrchr`, `strstr`, `strnstr`, `strcmp`, `strncmp`
- Character check functions: `isalpha`, `isdigit`, `isalnum`, `isascii`, `isprint`
- String to integer conversion function: `atoi`

### Additional Functions

Additional functions include:

- `ft_memdel`: Deallocates memory from the input address and sets it to NULL.
- `ft_bzero`: Sets every character in the string to '\0'.
- `ft_striter`: Applies a function to each character of a string.
- `ft_strmap`: Applies a function to each character of a string to create a new string.
- `ft_strmapi`: Applies a function to each character of a string to create a new string, passing the character index.
- `ft_strsub`: Extracts a substring from a string.
- `ft_strjoin`: Concatenates two strings into a new string.
- `ft_strtrim`: Trims leading and trailing whitespace from a string.
- `ft_strsplit`: Splits a string into an array of strings based on a delimiter.
- `ft_itoa`: Converts an integer to a string.
- `ft_putchar`: Outputs a character.
- `ft_putstr`: Outputs a string.
- `ft_putendl`: Outputs a string followed by a newline.
- `ft_putnbr`: Outputs an integer.
- `ft_putchar_fd`: Outputs a character to a file descriptor.
- `ft_putstr_fd`: Outputs a string to a file descriptor.
- `ft_putendl_fd`: Outputs a string followed by a newline to a file descriptor.
- `ft_putnbr_fd`: Outputs an integer to a file descriptor.

Bonus functions are mainly for manipulating linked lists. They include:

- `ft_lstnew`: Creates a new list element.
- `ft_lstdelone`: Deletes a single list element.
- `ft_lstdel`: Deletes an entire list.
- `ft_lstadd`: Adds a new element to the beginning of a list.
- `ft_lstiter`: Applies a function to each element of a list.
- `ft_lstmap`: Applies a function to each element of a list to create a new list.

#### Personal Functions

These are functions that you find useful and decide to include in your library.

## Installation

To get a local copy up and running, follow these steps:

1. Clone the repository to your local machine.
    git clone https://github.com/Miami05/Libft_42.git
2. Navigate to the project directory.
    cd libft
3. Run `make` to compile the library. This will create a `libft.a` file.

## Usage

To use the library in your code:

1. Include `libft.h` in your C files: `#include "libft.h"`.
    #include "libft.h"
2. Compile your files with `libft.a`.
    gcc your_c_file.c -L. -lft -o your_program_name

Example:
![Screenshot from 2024-06-21 14-50-38](https://github.com/Miami05/Libft_42/assets/163139187/746644b9-67e8-4bd7-9bf4-97c0b381d681)
