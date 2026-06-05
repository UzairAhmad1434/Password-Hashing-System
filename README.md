# Password-Hashing-System# 🔐 Password Hashing System
### Cryptography Semester Project — Python + Flask

![Python](https://img.shields.io/badge/Python-3.12-blue?style=flat&logo=python)
![Flask](https://img.shields.io/badge/Flask-3.0-green?style=flat&logo=flask)
![License](https://img.shields.io/badge/License-MIT-purple?style=flat)
![Status](https://img.shields.io/badge/Status-Complete-success?style=flat)

---

## 📌 About This Project

This is a **Cryptography Semester Project** that demonstrates how password hashing works in real-world applications. The project covers multiple hashing algorithms, real attack simulations, and security best practices — all through an interactive Python CLI and a Flask-powered web interface.

The core idea is simple: **never store plain text passwords**. Instead, store only their hash. This project shows exactly why this matters and how to do it correctly.

---

## 🌐 Live Demo

Run locally at: `http://127.0.0.1:5000`

---

## ✨ Features

- 🔑 **Hash any password** using 6 different algorithms
- 📝 **User Registration** with securely hashed password storage
- 🔓 **Login System** with timing-safe verification
- 💪 **Password Strength Analyzer** with entropy scoring
- ⚡ **Algorithm Benchmark** — speed comparison of all algorithms
- ⚔️ **Attack Demonstrations** — rainbow table, dictionary, brute force, timing attacks
- 🌐 **Web Interface** — professional dark-themed Flask website
- 🛠️ **Admin Panel** — view users, database stats, algorithm breakdown

---

## 🔐 Algorithms Covered

| Algorithm | Speed | Security | Verdict |
|-----------|-------|----------|---------|
| MD5 | 1,764,521 h/s | ❌ Broken | Never use |
| SHA-256 | 326,442 h/s | ⚠️ Weak | Not for passwords |
| SHA-512 | 212,000 h/s | ⚠️ Weak | Not for passwords |
| PBKDF2 | 13 h/s | ✅ Good | NIST Recommended |
| bcrypt | 3 h/s | ✅ Strong | Industry Standard |
| Argon2id | 6 h/s | ✅ Best | Use this in 2024 |

> **Rule:** Slower algorithm = attacker makes fewer guesses = YOU are safer

---

## ⚔️ Attacks Demonstrated

1. **Rainbow Table Attack** — Cracks unsalted MD5 in 0.001ms
2. **Dictionary Attack** — Common passwords cracked instantly
3. **Brute Force Attack** — Short passwords broken in seconds
4. **Timing Attack** — Naive comparison leaks info via response time
5. **bcrypt/Argon2 Resistance** — Shows why slow algorithms win

---

## 📁 Project Structure
