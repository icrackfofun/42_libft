# 42_libft

> My custom implementation of the C standard library, developed as part of the 42 curriculum.

## 📚 About

Libft is a foundational project at [42 School](https://42.fr/) where students reimplement key standard C library functions from scratch, reinforcing understanding of memory management, pointers, and low-level programming. The final output is a static library called `libft.a` that can be reused in other C projects.

## 🛠️ Features

This library includes reimplementations of the following:

### Part 1 – libc functions
- `memset`, `bzero`, `memcpy`, `memmove`, `memchr`, `memcmp`
- `strlen`, `strlcpy`, `strlcat`, `strchr`, `strrchr`, `strncmp`, `strnstr`
- `atoi`, `isdigit`, `isalpha`, `isalnum`, `isascii`, `isprint`, `toupper`, `tolower`
- `calloc`, `strdup`

### Part 2 – Additional functions
- `substr`, `strjoin`, `strtrim`, `split`
- `itoa`, `strmapi`, `striteri`
- `putchar_fd`, `putstr_fd`, `putendl_fd`, `putnbr_fd`

### Bonus – Linked list functions
- `lstnew`, `lstadd_front`, `lstadd_back`, `lstsize`, `lstlast`
- `lstdelone`, `lstclear`, `lstiter`, `lstmap`

> All functions are prefixed with `ft_` to avoid name conflicts with standard library functions.

## 🧱 Build the Library

```bash
make
