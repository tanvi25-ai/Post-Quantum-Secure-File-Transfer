# Post-Quantum Secure File Transfer System

## Overview

This project implements a complete Post-Quantum Cryptography (PQC) secure file transfer system using NIST-standardized algorithms.

It demonstrates how quantum-safe cryptography can be deployed on classical infrastructure.

---

## Algorithms Used

### Post-Quantum Key Exchange
CRYSTALS-Kyber (ML-KEM-768)

### Post-Quantum Digital Signatures
CRYSTALS-Dilithium (ML-DSA-65)

### Symmetric Encryption
AES-GCM (Hybrid encryption model)

---

## Features

- PQC-based key encapsulation
- PQC digital signature generation and verification
- Secure file encryption and decryption
- End-to-end secure transfer simulation
- Performance comparison with RSA

---

## Tech Stack

- Python
- liboqs (Open Quantum Safe)
- Cryptography library
- Google Colab (Linux environment)

---

## Why This Matters

Classical algorithms like RSA and ECC are vulnerable to quantum attacks (Shor’s algorithm).  
This system demonstrates a quantum-safe alternative ready for future security needs.

---

## How to Run

This project is implemented in Google Colab.

### 1. Install dependencies
pip install -r requirements.txt


### 2. Open the notebook
PQC_implementation.ipynb


### 3. Run all cells sequentially to execute:

- Post-Quantum key exchange
- Digital signature generation and verification
- Secure file encryption and decryption
- Performance comparison with RSA

**Note:** The project was developed and tested in a Linux-based Google Colab environment.

## Demo Output
<img width="1902" height="788" alt="image" src="https://github.com/user-attachments/assets/6ec59210-0a8b-4c70-90d5-082ec2188984" />
<img width="1911" height="858" alt="image" src="https://github.com/user-attachments/assets/1cf31c18-bf0c-422f-a762-64a18b0f4aab" />


