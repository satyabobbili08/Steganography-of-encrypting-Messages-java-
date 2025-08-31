# Steganography of Encrypted Messages inside Valid QR Codes-

## 📌 Project Overview
This project implements a secure **steganographic system** that embeds encrypted messages (payloads) inside valid **QR codes** without affecting their readability. Unlike traditional methods, the system allows a QR code to carry both:
- A **normal message** (visible to everyone), and
- A **hidden encrypted payload** (accessible only with a secret key).

This dual-message approach enhances **data confidentiality**, misleads adversaries with decoy information, and ensures robustness against noise and distortions.

---

## 🎯 Key Features
- Embeds encrypted payloads inside QR codes while keeping them scannable.
- Normal (public) message and hidden (secure) payload are **independent**.
- **Multi-Level Encryption Algorithm (MLEA)** secures payloads.
- **SQPEE (Steganalysis QR Payload Embedding and Extraction)** ensures reliable embedding and retrieval.
- User authentication and message management (register, login, send, view).
- Database integration for secure storage and retrieval of messages.

---

## 🛠️ Tech Stack
- **Programming Language:** Core Java  
- **Backend:** JDBC, Servlets  
- **Frontend:** HTML, CSS, JavaScript, JSP  
- **Database:** MySQL  
- **IDE/Tools:** Eclipse  
- **Other:** QR Code Generator API, Custom Encryption Algorithms (MLEA, SQPEE)  

---

## ⚙️ System Modules
- **User Module**: Register, login, send/receive messages.  
- **Admin Module**: Manage users, view accepted messages.  
- **QR Code Module**: Generate QR codes with embedded payloads.  
- **Encryption Module**: Secure payloads before embedding.  
- **Extraction Module**: Decrypt and retrieve hidden payloads.  

---

## 🖥️ System Requirements
**Hardware**  
- Processor: Intel i3 or higher  
- RAM: 2 GB minimum  
- Hard Disk: 500 GB  
- Monitor: 15" LED  

**Software**  
- OS: Windows 10  
- Language: Java  
- Server-side: Servlets, JSP  
- Database: MySQL  
- IDE: Eclipse  

---

## 🚀 How It Works
1. User composes a message + payload.  
2. Payload is encrypted using **MLEA**.  
3. Encrypted payload is embedded into a QR code using **SQPEE**.  
4. QR code can be scanned by anyone:
   - Ordinary message is visible to all.  
   - Hidden encrypted payload is retrievable only with the secret key.  

---

## 📖 Advantages
- Provides stronger security compared to existing methods.  
- Prevents data leakage by misleading adversaries.  
- Efficient in terms of storage and processing.  

---

## 📂 Project Structure
