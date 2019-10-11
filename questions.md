# Questions

## What's `stdint.h`?

stdint.h is a header file in the C standard library introduced in the C99 standard library section 7.18 to allow programmers to write more portable code by providing a set of typedefs that specify exact-width integer types, together with the defined minimum and maximum allowable values for each type, using macros .

## What's the point of using `uint8_t`, `uint32_t`, `int32_t`, and `uint16_t` in a program?

These functions are a cross-platform implementation of a standard data type.

## How many bytes is a `BYTE`, a `DWORD`, a `LONG`, and a `WORD`, respectively?

BYTE is 1 byte long, DWORD is 4 bytes, LONG, is 4 bytes and WORD is 2 bytes long.

## What (in ASCII, decimal, or hexadecimal) must the first two bytes of any BMP file be? Leading bytes used to identify file formats (with high probability) are generally called "magic numbers."

bfType, the file type; must be BM.

## What's the difference between `bfSize` and `biSize`?

biSize is the number of bytes required by the structure and bfSize is the size of the bitmap file in bytes.

## What does it mean if `biHeight` is negative?

If biHeight is negative, the bitmap is a top-down DIB and its origin is the upper-left corner.

## What field in `BITMAPINFOHEADER` specifies the BMP's color depth (i.e., bits per pixel)?

biBitCount.

## Why might `fopen` return `NULL` in `copy.c`?

If the infile is non-existent.

## Why is the third argument to `fread` always `1` in our code?

Because we are reading only 1 file.

## What value does `copy.c` assign to `padding` if `bi.biWidth` is `3`?

3.

## What does `fseek` do?

fseek allows for rewind or fast-forward within a file.

## What is `SEEK_CUR`?

SEEK_CUR is a parameter in fseek which moves file pointer position to a given location.
