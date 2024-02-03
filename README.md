# Vigenere Cipher Implementation

This Python script implements the Vigenere cipher for encrypting and decrypting text. The Vigenere cipher is a method of encrypting alphabetic text by using a simple form of polyalphabetic substitution.

## Usage

You can use this script to encrypt and decrypt messages using the Vigenere cipher. Modify the `text` and `custom_key` variables with your desired values.

```python
text = 'diwncis'
custom_key = 'helloworld'

# Encrypt
encrypted_text = encrypt(text, custom_key)
print(f'Encrypted text: {encrypted_text}')

# Decrypt
decrypted_text = decrypt(encrypted_text, custom_key)
print(f'Decrypted text: {decrypted_text}')
```

## Functions

### `vigenere(message, key, direction=1)`

This function performs the Vigenere cipher encryption and decryption. It takes three parameters:
- `message`: The text to be encrypted or decrypted.
- `key`: The key to be used for the Vigenere cipher.
- `direction`: Optional parameter indicating whether to encrypt (default) or decrypt. Use `1` for encryption and `-1` for decryption.

### `encrypt(message, key)`

This function encrypts a given message using the Vigenere cipher.

### `decrypt(message, key)`

This function decrypts a given message encrypted with the Vigenere cipher.

## Example

The provided example demonstrates how to use the script to encrypt and decrypt a message.

```python
text = 'diwncis'
custom_key = 'helloworld'

# Encrypt
encrypted_text = encrypt(text, custom_key)
print(f'Encrypted text: {encrypted_text}')

# Decrypt
decrypted_text = decrypt(encrypted_text, custom_key)
print(f'Decrypted text: {decrypted_text}')
```

Replace the values of `text` and `custom_key` with your own values for experimentation.
