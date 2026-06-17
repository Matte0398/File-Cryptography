# File-Cryptography

Python utility that uses the Fernet symmetric encryption library to encrypt and decrypt files.

This project was created as a learning exercise to practice basic file encryption and decryption workflows in Python.

## Notes

The script works only with the following files, which are defined directly in the source code:

``` text
original_file = "original_file.txt"
file_to_encrypt = "encrypted_file.txt"
file_decrypted = "decrypted_file.txt"
```

## Requirements

- Python 3
- cryptography

## Installation

``` python
pip install cryptography
```

## Usage

``` python
python file_cryptography.py [mode]
```

#### Mode:

``` text
encrypt
decrypt
```

## Example

``` python
python file_cryptography.py decrypt
