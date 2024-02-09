Caesar Cipher Encryptor/Decryptor
This Python script implements a simple Caesar cipher encryptor and decryptor. The Caesar cipher is a substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet.

How to Use
Run the script: python caesar_cipher.py
Choose whether to 'encode' (encrypt) or 'decode' (decrypt).
Enter the message you want to process.
Specify the shift number for the cipher.
Review the result and decide if you want to continue.
Code Overview
The script consists of the following components:

Alphabet Definition:

The script initializes a list containing the English alphabet in both lowercase and uppercase.
Caesar Cipher Function:

The caesar function takes a starting text, shift amount, and cipher direction as parameters.
It iterates through each character in the input text, applies the Caesar cipher, and builds the resulting text accordingly.
User Interaction Loop:

The script uses a loop to repeatedly prompt the user for input.
The user can choose to encode or decode a message, input the text, and specify the shift value.
The result is then displayed, and the user can decide whether to continue or exit.

Example:

Type 'encode' to encrypt, type 'decode' to decrypt:
encode
Type your message:
hello
Type the shift number:
3
Here's the encoded result: khoor

Type 'yes' if you want to go again. Otherwise type 'no'.
yes

Type 'encode' to encrypt, type 'decode' to decrypt:
decode
Type your message:
khoor
Type the shift number:
3
Here's the decoded result: hello

Type 'yes' if you want to go again. Otherwise type 'no'.
no
Goodbye
