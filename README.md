## initial-utilities

# Wzip
It's the one of utilities in UNIX system.
The type of compression used here is a simple form of compression called run-length encoding (RLE). RLE is quite simple: when you encounter n characters of the same type in a row, the compression tool (wzip) will turn that into the number n and a single instance of the character.

## Syntax 

To compress the file file.txt into a -smaller- file.z:
>promt>./wzip file.txt > file.z

## Example

`abbbbccc`

It turn it into:

>2a3b3c


## Details:

- Taking number of arguments from user.
- Compare it and the result of the comparison depends on what will happen next .
- The number of repetitions of a particular letter will be recorded in the `COUNT` variable .
- The `COUNT` and `array` sent to `writeFile`  to out the the count of every letter.




