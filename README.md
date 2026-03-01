Post-Quantum Secure File Transfer System

#Overview

This project implements a complete Post-Quantum Cryptography (PQC) secure file transfer system using NIST-standardized algorithms.

It demonstrates how quantum-safe cryptography can be deployed on classical infrastructure.

#Algorithms Used
Post-Quantum Key Exchange

CRYSTALS-Kyber (ML-KEM-768)

Post-Quantum Digital Signatures

CRYSTALS-Dilithium (ML-DSA-65)

Symmetric Encryption

AES-GCM (Hybrid encryption model)

#Features

PQC-based key encapsulation

PQC digital signature generation & verification

Secure file encryption & decryption

End-to-end secure transfer simulation

Performance comparison with RSA

#Tech Stack

Python

liboqs (Open Quantum Safe)

Google Colab (Linux)

Cryptography library

#Why This Matters

Classical algorithms like RSA and ECC are vulnerable to quantum attacks (Shor’s algorithm).
This system demonstrates a quantum-safe alternative ready for future security needs.

#How to Run

Install dependencies:

pip install -r requirements.txt

Run:

python send.py
python receive.py
