AES
===

This details the implementation of the AES (Advanced Encryption Standard) algorithm in C programming language.

# Usage Guide

First, you need to compile the source files. This can be done using a compiler like GCC. Use the following command to compile:

`gcc gmult.c aes.c main.c -o aes`

After successful compilation, execute the program:

```bash
./aes
Input for plaintext:
00 11 22 33 44 55 66 77 88 99 aa bb cc dd ee ff
Output for ciphered text:
8e a2 b7 ca 51 67 45 bf ea fc 49 90 4b 49 60 89
Decrypted text (post inverse cipher):
00 11 22 33 44 55 66 77 88 99 aa bb cc dd ee ff
```