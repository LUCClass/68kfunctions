# 68k Functions

## Converting a Hex Number to Binary

You're going to write a function that takes as input a string of hex characters and converts it to an integer.
The first argument to your function will be a pointer to the string to convert.
The second argument will be the number of characters in the string to convert.
An example usage of the function is shown below:

    char str[] = "DEADBEEF";
    int num = hex2int(str,8);

Your function should take its input arguments on the stack and return its result in `D0`.

## Calculating the Length of a String

You're going to write a function that caluclates the length of a string.
Your function takes only one argument---a pointer to the beginning of the string.
An example usage of the function is shown below:

    char str[] = "the quick brown fox jumped over the lazy dog";
    int len = strlen(str);

Your function should take its input argument on the stack and return the result in `D0`.


