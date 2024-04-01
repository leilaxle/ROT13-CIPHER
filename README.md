# ROT13 Cipher

## Overview

This Python script provides a simple implementation of the ROT13 cipher, a type of substitution cipher that replaces each letter in a message with the letter 13 positions ahead or behind it in the alphabet.

## Features

- **Encryption**: Encrypts a message using the ROT13 cipher.
- **Decryption**: Decrypts an encrypted message using the ROT13 cipher.
- **Case Preservation**: Preserves the case of letters during encryption and decryption.
- **Handling of Non-Alphabetic Characters**: Handles non-alphabetic characters in the input message by leaving them unchanged.

## Usage

To use the ROT13 cipher, follow these steps:

1. Ensure you have Python installed on your system.
2. Clone this repository or download the `main.py` file.
3. Run the `main.py` file using Python.
4. Modify the `message` variable inside the `main()` function to encrypt and decrypt different messages.
5. Execute the script to see the original, encrypted, and decrypted messages.

## Example

```python
message = "This is an example message to encrypt using the ROT13 cipher!"
shift = 13
encrypted_message = encrypt(message, shift)
decrypted_message = decrypt(encrypted_message, shift)

print("Original Message:", message)
print("Encrypted Message:", encrypted_message)
print("Decrypted Message:", decrypted_message)

This will output:
Original Message: This is an example message to encrypt using the ROT13 cipher!
Encrypted Message: Guvf vf na rknzcyr zrffntr gb rapelcg hfvat gur EBG13 puvyqre!
Decrypted Message: This is an example message to encrypt using the ROT13 cipher!
