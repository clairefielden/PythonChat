# 🔐 Cybersecurity Assignment

## Overview
This project demonstrates the fundamentals of **secure client–server communication** by combining:

- **Hashing** for message integrity  
- **Diffie–Hellman key exchange** for secure symmetric key generation  
- **DES encryption** for confidentiality  

It was developed as part of a cybersecurity module to explore how cryptographic primitives can be integrated into a working Java system.

---

## ✨ Features
- **Client–Server Architecture**  
  - Login and account creation  
  - Secure message exchange between client and server  

- **Cryptographic Components**  
  - **Diffie–Hellman** for key exchange  
  - **DES** for encryption and decryption  
  - **Hashing** (SHA family) for message integrity verification  

- **Utilities & Data Handling**  
  - Byte array conversion and reassembly  
  - Base64 encoding/decoding for safe transmission  
  - Key serialization and storage  

---

## 🛠 Tech Stack
- **Language:** Java  
- **Cryptography:** Java Cryptography Architecture (JCA)  
- **Algorithms:** Diffie–Hellman, DES, SHA hashing  
- **Tools:** Wireshark (for packet capture and verification)  

---

## 🚀 Getting Started

### Prerequisites
- Java 8+  
- Git  

### Installation & Running
```bash
# Clone the repository
git clone https://github.com/clairefielden/CybersecurityAssignment.git
cd CybersecurityAssignment

# Compile all classes
javac *.java

# Run the server
java Server

# Run the client (in another terminal/session)
java Client
