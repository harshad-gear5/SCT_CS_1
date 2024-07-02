 SCT_CS_1
The repository consists Skill Craft Technology intern's task 1: Caesar cipher algorith
<br> - Author- Harshad zambre
<br>

 Caesar Cipher Encryption and Decryption

This project provides a simple implementation of the Caesar Cipher algorithm for encrypting and decrypting messages. The Caesar Cipher is one of the oldest and simplest methods of encryption, where each letter in the plaintext is shifted a fixed number of places down or up the alphabet.

 Features

- Encryption**: The script takes a message and a shift value as input and outputs the encrypted message. Each letter is shifted by the specified number of places in the alphabet. Uppercase and lowercase letters are handled separately, preserving the case of each letter.
- **Decryption**: The script can also decrypt a message that was encrypted using the Caesar Cipher. By shifting the letters back by the same number of places, the original message is recovered.

 How It Works

1. Input Message**: The user inputs a message to be encrypted or decrypted.
2. Shift Value**: The user specifies the shift value, which determines how many places each letter in the message will be shifted.
3. Encryption Process**: 
   - For each letter in the message, the script determines its position in the alphabet.
   - The script then shifts the letter by the specified number of places, wrapping around the alphabet if necessary.
   - Spaces and non-alphabetic characters are left unchanged.
4. Decryption Process**: The decryption function uses the same process as encryption but with the shift value negated, effectively reversing the shift.

 Applications

The Caesar Cipher is primarily a teaching tool in cryptography. It illustrates the concept of encryption and decryption and forms the basis for understanding more complex encryption algorithms. Despite its simplicity and vulnerability to attacks, it demonstrates key principles of data security.



