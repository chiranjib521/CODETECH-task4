Project Overview: Advanced Encryption Tool
Objective
The Advanced Encryption Tool is a Python-based security application designed to encrypt and decrypt files using AES-256 encryption.
Its primary goal is to ensure the confidentiality of sensitive data and provide a simple interface for users to protect files against unauthorized access.

Key Features
AES-256 Encryption and Decryption

Uses the Fernet implementation of AES for strong encryption.

Ensures that files are securely encrypted and can only be decrypted using the original key.

File Type Support

Works with all file types: text, images, PDFs, and more.

Key Management

Generates a secret key file (secret.key) for secure storage.

Required for both encryption and decryption.

User-Friendly Interface

Menu-driven program for easy encryption and decryption operations.

Guides users step-by-step to secure their files.

Technology Stack
Programming Language: Python

Libraries Used:

cryptography → For AES-256 encryption and decryption

os → For file handling and validation

Working Process
Key Generation

Generates a unique key and saves it to secret.key.

This key is used to encrypt and decrypt files securely.

File Encryption

Reads the original file and encrypts it using AES-256.

Creates a new file with the .enc extension.

File Decryption

Reads the encrypted file and decrypts it using the saved key.

Produces the original file with _decrypted suffix.

Security Benefits
Protects sensitive files from unauthorized access.

AES-256 encryption is industry-standard and highly secure.

Key-based system ensures only authorized users can decrypt files.

Deliverable
A Python-based Advanced Encryption Tool capable of:

Encrypting and decrypting files using AES-256.

Providing a simple, user-friendly interface for secure file handling.



