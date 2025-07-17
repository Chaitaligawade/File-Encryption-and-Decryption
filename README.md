# File Encryption & Decryption Tool

A simple GUI application for encrypting and decrypting files using Fernet symmetric encryption from the `cryptography` library.

## Features

- Generate secure encryption keys
- Encrypt files of any type
- Decrypt previously encrypted files
- User-friendly graphical interface
- Progress bar visualization

## Requirements

- Python 3.6+
- Required packages:
  - `cryptography`
  - `tkinter`

## Installation

 Install the required packages:
   ```bash
   pip install cryptography
   # File-Encryption-and-Decryption
   
   #Usage
Run the application:

bash
python file_encryptor.py
Interface options:

Generate Key: Creates a new encryption key (saved as key.key)

Encrypt File: Select a file to encrypt (original file will be overwritten)

Decrypt File: Select a file to decrypt (original file will be overwritten)

Exit: Close the application
