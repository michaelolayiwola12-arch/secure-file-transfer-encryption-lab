![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Project-blue)
![OpenSSL](https://img.shields.io/badge/OpenSSL-Encyption-green)
![Linux](https://img.shields.io/badge/Linux-Terminal-yellow)
![PacketTracer](https://img.shields.io/badge/Cisco-PacketTracer-red)

# Explore File and Data Encryption – Cybersecurity Project

# Project Overview

This project demonstrates practical cybersecurity concepts involving:

File encryption and decryption

FTP authentication analysis

Secure file handling

Cryptographic operations using OpenSSL

Security weaknesses in legacy protocols

Confidential data protection

The project was completed in a simulated enterprise environment using Cisco Packet Tracer and Linux-based cybersecurity tools.

# Objectives

# Part 1 – Discover FTP Credentials

Decrypt encrypted FTP credentials

Authenticate to an FTP server securely

# Part 2 – Upload Confidential Data

Verify encrypted files

Upload encrypted files using FTP

Analyze transfer security risks

# Part 3 – Discover Additional Credentials

Decrypt another user’s encrypted login details

Validate secure credential handling

# Part 4 – Download Confidential Files

Download encrypted files from a remote FTP server

Analyze risks of insecure transfer protocols

# Part 5 – Decrypt Sensitive Data

Recover encrypted customer information

Perform AES-256-CBC decryption using OpenSSL

# Technologies Used & Technology	Purpose

Cisco Packet Tracer -	Network simulation

OpenSSL -	Encryption & decryption

Linux Terminal -	Command-line operations

FTP	- File transfer

AES-256-CBC	- Symmetric encryption

PBKDF2	- Password-based key derivation

VirtualBox	- Virtualized lab environment

# Key Cybersecurity Concepts Demonstrated

Encryption vs Integrity

Secure authentication

File confidentiality

Password-based cryptography

Network protocol weaknesses

FTP insecurity analysis

Secure file transfer concepts

Threat awareness

# Security Weaknesses Identified

FTP is Insecure

FTP transmits Usernames, Passwords, Commands, and Session metadata in plaintext.

This makes FTP vulnerable to Packet sniffing, Credential theft, Man-in-the-middle attacks, Session hijacking, and Weak Key Distribution

Sharing encryption keys via email introduces security risks including interception and unauthorized access.

# Security Recommendations
Replace FTP with SFTP or FTPS

Implement Multi-Factor Authentication (MFA)

Use authenticated encryption (AES-GCM)

Deploy SIEM monitoring

Apply least privilege access controls

Use secure key management systems

# OpenSSL Commands

Decrypt Encrypted Credentials

echo 'ENCRYPTED_TEXT' | openssl aes-256-cbc -pbkdf2 -a -d

Decrypt Encrypted File

openssl aes-256-cbc -pbkdf2 -a -d -in clientinfo.enc -out clientinfo.txt

# Skills Demonstrated

Cryptography

OpenSSL Operations

Linux Administration

Secure File Handling

Network Security

Cybersecurity Documentation

Threat Analysis

Security Assessment

# Project Outcome

This project strengthened practical understanding of:

Encryption workflows

Secure data handling

Authentication security

Network protocol analysis

Enterprise cybersecurity operations

👨‍💻 Author

Michael Olayiwola

Cybersecurity Professional | SOC Analyst | Digital Forensics Enthusiast
