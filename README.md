# Command-line-password-manager

# Overview

- This password manager allows users to:

- Encrypt and store passwords for various websites/apps.

- Securely derive an encryption key from a master password using PBKDF2-HMAC-SHA256.

- Store data in a local JSON file with a unique cryptographic salt.

- Decrypt and display passwords only after successful authentication.

- Use the Fernet encryption protocol to ensure data confidentiality.

