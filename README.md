# Hybrid Encryption and Hashing System (Java)

## Overview
This project implements a Hybrid Encryption and Hashing System that demonstrates how cryptographic techniques can be applied to protect sensitive data and ensure its integrity.
The system combines AES-128 symmetric encryption for confidentiality with SHA-256 hashing for integrity verification.

The application follows a two-stage process:
1. Encryption with hash generation
2. Hash verification followed by decryption

This project focuses on practical implementation of security concepts using Java.

## Features
- Generate a random 128-bit AES secret key
- Encrypt plain text using AES
- Encode encrypted data using Base64
- Generate SHA-256 hash from cipher text
- Verify data integrity by recomputing and comparing hash values
- Decrypt data only if integrity verification passes
- Display a clear summary report of the entire process
- Console-based interactive interface

## Technologies Used
- Java
- Java Cryptography Architecture (JCA)
- AES-128 Encryption
- SHA-256 Hashing
- Base64 Encoding

## System Workflow
1. Generate AES encryption key
2. Accept plain text input from user
3. Encrypt plain text using AES
4. Generate SHA-256 hash from encrypted data
5. Accept cipher text and hash for verification
6. Recompute and compare hash values
7. Decrypt data if integrity check is successful
8. Display summary report

## Project Structure
hybrid-encryption-hashing-java/
├── src/
│   └── HybridEncryptionHashing.java
└── README.md

## How to Run
1. Open the project in any Java IDE (IntelliJ IDEA, NetBeans, or Eclipse)
2. Ensure JDK 17 or a compatible version is installed
3. Run HybridEncryptionHashing.java
4. Follow the console instructions step by step

## Example Use Case
- User enters sensitive information
- System encrypts the data and generates a hash
- User verifies that the encrypted data was not altered
- Data is safely decrypted after successful integrity verification

## Notes
- This project is intended for educational purposes
- Demonstrates secure data handling using cryptographic principles
- No external libraries are required

## Future Improvements
- File encryption support
- Asymmetric encryption integration (RSA)
- Graphical user interface (GUI)
- Secure key storage and management

## License
This project is developed for educational and learning purposes only.
