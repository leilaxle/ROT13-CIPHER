# ROT13-CIPHER

ROT13 Cipher
This is a simple Python implementation of the ROT13 cipher, a type of substitution cipher that replaces each letter in a message with the letter 13 positions ahead or behind it in the alphabet.

Usage
To use this program, simply run the main.py file. It includes a main() function that demonstrates how to encrypt and decrypt messages using the ROT13 cipher. You can modify the message variable inside the main() function to encrypt and decrypt different messages.

How it Works
The dict1 dictionary maps each alphabet to its corresponding index.
The dict2 dictionary maps each index after a shift to its corresponding alphabet.
The encrypt() function takes a message and a shift value as input, encrypts the message using the ROT13 cipher, and returns the encrypted message.
The decrypt() function takes an encrypted message and a shift value as input, decrypts the message using the ROT13 cipher, and returns the decrypted message.
Example
python
Copy code
message = "this is the rot13 cipher!"
shift = 13
encrypted_message = encrypt(message.upper(), shift)
decrypted_message = decrypt(encrypted_message, shift)
print("Original Message:", message)
print("Encrypted Message:", encrypted_message)
print("Decrypted Message:", decrypted_message)
This will output:

kotlin
Copy code
Original Message: this is the rot13 cipher!
Encrypted Message: GUVF VF GUR EBG13 PUVYRE!
Decrypted Message: THIS IS THE ROT13 CIPHER!
