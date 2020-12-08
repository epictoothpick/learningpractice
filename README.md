# learningpractice

<Plurality.c>
Using structs, arrays, and user created functions in C, I learnt how to call functions, organise my code and run a program that counts votes from user submission, and check for invalid votes if the user does not vote for a candidate that exists.

The limitation in this program is that the number of voters and candidates have to be predefined with a prompt to the user, using the CS50 function get_int, get_string, etc.


<Caesarcipher.c>
Encryption program that takes command line argument and ciphers user input text based on the command line argument.

This program takes command line argument, checks for user input error (must input 2 arguments in the command line, 2nd argument must be a positive integer), and converts it to cipher text. Converting the string command line to integer, this is the number of steps to move the plain text to become cipher text. Using for loops, we iterate over each character (plaintext[i]), accounting for lower case or upper case, keeping the case which the user input in the final output. The final output printed is an array of characters as ciphered text.
