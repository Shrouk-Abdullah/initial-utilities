# initial-utilities

## wzip
It's the one of utilities in UNIX system.

The type of compression used here is a simple form of compression called run-length encoding (RLE). RLE is quite simple: when you encounter n characters of the same type in a row, the compression tool (wzip) will turn that into the number n and a single instance of the character.

If we had a file with the following contents:
>aabbbbccc
The tool would turn it (logically) into:
>2a3b3c



