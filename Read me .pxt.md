 Caesar Cipher in Python
This is a simple implementation of the Caesar Cipher, a classic encryption technique where each letter in the text is shifted by a fixed number of positions in the alphabet.

 Features
Encrypts and decrypts alphabetic messages

Preserves case (uppercase/lowercase)

Keeps non-alphabetic characters (spaces, punctuation, numbers) unchanged

Easy to use via command-line input

 How It Works
Each letter in the input message is replaced by another letter shifted by a user-defined number. For example, with a shift of 3:

A → D

B → E

X → A

Z → C

Decryption is done by shifting in the opposite direction (i.e., using a negative shift).

 Example
text
Copy
Edit
Enter message: Hello, World!
Enter shift (0-25): 3
Encrypted message: Khoor, Zruog!
Decrypted message: Hello, World!
 How to Run
Make sure you have Python 3 installed.

Save the code in a file named caesar_cipher.py.

Open a terminal or command prompt and run:
