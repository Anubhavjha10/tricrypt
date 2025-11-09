# 🔐 TriCrypt: Your Data, Only Yours

**TriCrypt** is a zero-knowledge, client-side encryption tool that guarantees **complete data privacy**.  
All encryption and decryption operations happen entirely **within your browser**, ensuring your passwords, keys, and secrets are **never sent to any server**.

---

## 🌐 Live Demo  
👉 [https://tricrypt.netlify.app/](https://tricrypt.netlify.app/)

---

## 🧠 Overview

TriCrypt provides a secure way to encrypt sensitive information directly in your browser — without storing, logging, or transmitting any data externally.

It’s built on a **three-factor encryption model** (Password + Secret Answer + Secret PIN) that ensures **mathematical privacy** and resistance to brute-force attacks.

---

## ⚙️ Key Features

### 🧩 **Zero-Knowledge Architecture**
- No server access.  
- No data logging or storage.  
- Only you can decrypt your information.

### 💻 **Client-Side Execution**
- 100% browser-based; all code runs locally.  
- Works **offline** once the page is loaded.

### 🔐 **3-Factor Key Derivation**
- Combines:
  - Secret Password  
  - Secret Security Answer  
  - Secret PIN  
- Uses **PBKDF2 (100,000 iterations)** for key derivation.  
- Protected with **AES-256-GCM**, a military-grade encryption standard.

### 🗂️ **Single-File Application**
- The entire project runs from one lightweight HTML file.  
- Easy to deploy and portable across systems.

### 🚀 **Future-Proof**
- Upcoming **TriCrypt API** will support asymmetric encryption (Public/Private Key).  
- Designed for developers to easily implement **end-to-end encryption (E2EE)** in chat, messaging, or file-sharing applications.

---

## 🧰 Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | HTML, TailwindCSS, JavaScript |
| Encryption | AES-256-GCM |
| Key Derivation | PBKDF2 (100,000 iterations) |

---

## 🔒 Security Note

TriCrypt follows the **Zero-Knowledge principle** —  
> *The creator has no way to access or recover your data.*  

If you forget your credentials (password, answer, or PIN), your encrypted data becomes mathematically unrecoverable.  
This design ensures **absolute privacy and user ownership**.

---

## 📬 Feedback & Contributions

Feedback, bug reports, and suggestions are always welcome!  
If you’d like to contribute or integrate TriCrypt’s logic into your own project, feel free to open an issue or pull request.

---

## 🏁 License

This project is released under the **MIT License** — free for personal and commercial use.

---

**Made with ❤️ and a strong belief in data privacy.**
