![Repo Size](https://img.shields.io/github/repo-size/roshhellwett/projectegnima?style=for-the-badge)
![Stars](https://img.shields.io/github/stars/roshhellwett/projectegnima?style=for-the-badge)
![Forks](https://img.shields.io/github/forks/roshhellwett/projectegnima?style=for-the-badge)
![Issues](https://img.shields.io/github/issues/roshhellwett/projectegnima?style=for-the-badge)
![C/C++](https://img.shields.io/badge/Language-C%2FC%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B)

# PROJECT EGNIMA

Egnima is a sleek, modular command-line utility written in C/C++ for encoding and decoding text messages. It utilizes a custom XOR cipher paired with alphanumeric keys, providing a lightweight, interactive sandbox for exploring system-level cryptography, data formatting, and modular programming.

---

## ✨ Key Features

### 🔐 Cryptography & Encoding
* **XOR Cipher Engine:** Secures messages using an efficient XOR bitwise operation tied to user-defined alphanumeric keys.
* **Hexadecimal Formatting:** Safely exports and imports encrypted data in a cleanly formatted, space-separated hexadecimal string (e.g., `09 07 0F 0F 0D`), preventing terminal control character errors.
* **Dynamic Byte Tracking:** Built-in debug readouts actively track and verify message byte lengths during both transmission (sender) and reception (receiver).

## ⚡ Core Functionality
* **Interactive Terminal UI:** Features an intuitive, continuous menu-driven interface allowing users to encrypt or decrypt multiple messages without restarting the application.
* **Modular Architecture:** Cleanly separated logic with dedicated `encrypt` (Sender) and `decrypt` (Receiver) header and source files for high maintainability.
* **Modern Build System:** Fully supported by a modern CMake build configuration targeting the C++17 standard for seamless cross-platform compilation.

## 🛠️ Prerequisites

To build and run Project Egnima, you will need:
* **CMake:** Version 3.27 or higher.
* **C++ Compiler:** C++17 compatible compiler (GCC, Clang, or MSVC).
* **Terminal:** Any standard command-line interface.

## 🚀 Build Instructions

Project Egnima uses CMake for cross-platform compilation. Follow these steps to build from source:

1. **Clone the repository:**
```bash
   git clone [https://github.com/roshhellwett/projectegnima.git](https://github.com/roshhellwett/projectegnima.git)
   cd projectegnima
   run the .exe
```

---

## 📂 Project Structure
```
projectegnima/
├── .github/workflows/
│   └── cmake-multi-platform.yml  # CI/CD build configuration
├── CMakeLists.txt                # CMake C++17 build configuration
├── main.cpp                      # Application entry point & interactive UI loop
├── encrypt.h / encrypt.cpp       # Sender module: XOR encryption and Hex formatting
├── decrypt.h / decrypt.cpp       # Receiver module: Hex parsing and XOR decryption
├── projectenigma.exe             # Pre-compiled Windows executable
├── license                       # Open source license documentation
├── security.md                   # Security and vulnerability details
└── readme.md                     # Project documentation
```

---

© 2026 [Zenith Open Source Projects](https://zenithopensourceprojects.vercel.app/). All Rights Reserved. Zenith is a Open Source Project Idea's by @roshhellwett
