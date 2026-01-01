# Caesar Cipher

A Python implementation of the classic Caesar Cipher, a substitution cipher where each letter in the plaintext is shifted a certain number of places down the alphabet.

## Features
- **Encryption:** Encrypts messages by shifting characters forward.
- **Decryption:** Decrypts messages by shifting characters backward.
- **Case Preservation:** Maintains uppercase and lowercase formatting.
- **Input Validation:** Ensures shift values are integers between 1 and 25.

## How It Works
The program defines a `caesar` function that takes a text string and a shift integer. It creates a translation table to map the original alphabet to a shifted version (using slicing) and processes the text using Python's `translate()` method.

## Usage

### Encrypt a message
```python
from main import encrypt

encrypted_text = encrypt('freeCodeCamp', 3)
print(encrypted_text) #output: iuhhFrghFdps
