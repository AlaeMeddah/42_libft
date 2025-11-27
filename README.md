# Libft -- My First C Library

Libft is the first project of the 42 cursus.\
The goal is to recreate essential C standard library functions, as well
as additional utilities, and compile them into a reusable static
library: **libft.a**.

## 📌 What This Project Is

Libft is a collection of functions written in C that includes:

### Mandatory Part

Re-implemented libc functions: - Character checks (`isalpha`, `isdigit`,
etc.) - String functions (`strlen`, `strlcpy`, `strchr`, etc.) - Memory
functions (`memset`, `memcpy`, `memmove`, etc.) - Conversions (`atoi`) -
Allocators (`calloc`, `strdup`)

Additional utilities: - `ft_substr`, `ft_strjoin`, `ft_strtrim` -
`ft_split` - `ft_itoa` - `ft_strmapi`, `ft_striteri` - `ft_putchar_fd`,
`ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

### Bonus Part

If the mandatory part is perfect: - Linked list structure `t_list` -
Functions like `ft_lstnew`, `ft_lstadd_front/back`, `ft_lstclear`,
`ft_lstmap`, etc.

## 🛠️ Compilation

A Makefile builds the library with:

    cc -Wall -Wextra -Werror

Main rules: - `make` → builds libft.a\
- `make bonus` → adds bonus list functions\
- `make clean` / `fclean` / `re`

## 📚 What I Learned

-   How common C library functions work internally\
-   Memory allocation, pointers, and preventing leaks\
-   Implementing and managing linked lists\
-   Creating a static library with `ar`\
-   Writing norm-compliant, organized C code\
-   Using Makefiles to automate compilation

## ✅ Summary

Libft taught me core C programming skills and gave me a foundation for
all future 42 projects.\
It is now a tool I can reuse in upcoming projects.
