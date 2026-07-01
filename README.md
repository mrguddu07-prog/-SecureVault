# 🔐 SecureVault — Password Manager

<div align="center">

![SecureVault Banner](https://img.shields.io/badge/SecureVault-Password%20Manager-00ff88?style=for-the-badge&logo=lock&logoColor=black)

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![G S WebX](https://img.shields.io/badge/Brand-G%20S%20WebX-00c8ff?style=flat-square)](https://github.com/mrguddu07-prog)

**A fully functional, browser-based Password Manager with AES-256 encryption simulation, strength analysis, and a sleek dark-mode vault dashboard.**

</div>

---

## 📸 Screenshots

| Vault Dashboard | Edit & Strength Check |
|---|---|
| ![Dashboard](screenshots/dashboard.png) | ![Edit](screenshots/edit.png) |

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔒 **Master Password Auth** | Vault locked behind master credentials (Argon2id concept) |
| 🛡️ **AES-256 Encryption** | All passwords encrypted before storage |
| 💪 **Strength Checker** | Real-time Weak / Medium / Strong analysis |
| ⚡ **Password Generator** | 16-char secure passwords with symbols, digits & cases |
| 🗂️ **Category Vault** | Social, Email, Banking, Work, Other |
| 👁️ **Reveal / Hide** | Toggle password visibility per entry |
| 📋 **Copy to Clipboard** | One-click password copy |
| 📤 **Export Vault** | Download all entries as JSON backup |
| 🔍 **Search & Filter** | Search by site name or username |
| 📊 **Security Stats** | Track saved, strong, and weak passwords |

---

## 🧠 Cybersecurity Concepts

```
AES-256-GCM        →  Symmetric encryption for password storage
Argon2id / PBKDF2  →  Key derivation from master password
Password Entropy   →  Strength scoring based on charset & length
Secure Storage     →  LocalStorage with encrypted values
Zero-Knowledge     →  Master password never stored in plaintext
```

---

## 🚀 Getting Started

### Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/mrguddu07-prog/SecureVault.git

# 2. Navigate into the folder
cd SecureVault

# 3. Open in browser
# Just double-click password-manager.html
# OR use Live Server in VS Code
```

> No installations, no dependencies. Pure HTML + CSS + JS. 🎯

### Demo Credentials

```
Username : guddu
Password : Admin@1234
```

---

## 📁 Project Structure

```
SecureVault/
│
├── password-manager.html   # Main application (single file)
├── README.md               # Project documentation
└── screenshots/            # UI screenshots
    ├── dashboard.png
    └── edit.png
```

---

## 🔧 Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | App structure & layout |
| **CSS3** | Dark-mode UI, animations, responsive grid |
| **Vanilla JavaScript** | Logic, encryption, DOM manipulation |
| **LocalStorage API** | Client-side encrypted storage |
| **JetBrains Mono** | Monospace font for terminal aesthetic |
| **Google Fonts (Inter)** | Clean UI typography |

---

## 📌 How It Works

```
1. USER ENTERS MASTER PASSWORD
         ↓
2. VAULT UNLOCKS (credentials verified)
         ↓
3. ADD PASSWORD ENTRY
         ↓
4. PASSWORD → ENCRYPTED → STORED in LocalStorage
         ↓
5. DASHBOARD SHOWS MASKED ENTRIES
         ↓
6. REVEAL / COPY → DECRYPTS ON DEMAND
         ↓
7. LOCK VAULT → SESSION CLEARED
```

---

## ⚠️ Disclaimer

> This project is built for **educational and portfolio purposes** to demonstrate cybersecurity concepts. For production use, implement true AES-256-GCM with a proper key derivation function (Argon2id/PBKDF2) and never store plaintext credentials.

## 🤖 AI Disclosure

> AI was used for **minor assistance** during development. The core logic, design decisions, feature planning, and implementation are entirely my own work.

---

## 👨‍💻 Author

**Guddu Kumar**
BCA (Cyber Security) — Dev Bhoomi Uttarakhand University, Dehradun

[![GitHub](https://img.shields.io/badge/GitHub-mrguddu07--prog-181717?style=flat-square&logo=github)](https://github.com/mrguddu07-prog)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com)

---

<div align="center">

**Made with 🔐 by GUDDU (https://github.com/mrguddu07-prog)**

⭐ Star this repo if you found it useful!

</div>
