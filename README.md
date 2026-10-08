# Printf

A C implementation of `printf`, developed as part of the 42 curriculum.

The project focuses on variadic functions, formatted output and handling different argument types.

## Supported conversions

* `%c`
* `%s`
* `%p`
* `%d`
* `%i`
* `%u`
* `%x`
* `%X`
* `%%`

The implementation is split into several files to handle the different conversion types.

## Build

```bash
make
```

This creates `libftprintf.a`.

Available Make targets:

```bash
make
make clean
make fclean
make re
```

## Technologies

* C
* Variadic functions
* Make
* GCC
