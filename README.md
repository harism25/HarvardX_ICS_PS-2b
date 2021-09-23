# HarvardX_ICS_PS-2b
 
Designing and implementing a program, 'Caesar', that encrypts messages using Caesar’s cipher.

Implementing the program and start by accepting a single command-line argument, a non-negative integer. Let’s call it 'k' for example.

If the program is executed without any command-line arguments or with more than one command-line argument,
it prints an error message (of any choice) and returns from main a value of 1 (which signifies an error).

If any of the characters of the command-line argument is not a decimal digit, the program prints the message Usage: ./caesar key and returns from main a value of 1.

Do not assume that 'k' will be less than or equal to 26. The program should work for all non-negative integral values of 'k' less than 2^31 - 26.

The program outputs plaintext: (without a newline) and then prompts the user for a string of plaintext.

The program outputs ciphertext: (without a newline) followed by the plaintext’s corresponding ciphertext,
with each alphabetical character in the plaintext “rotated” by 'k' positions; non-alphabetical characters should be outputted unchanged.

The program preserves case: capitalized letters, though rotated, remain capitalized letters; lowercase letters, though rotated, remain lowercase letters.

After outputting ciphertext, a newline is printed.
The program then exits by returning 0 from main.
