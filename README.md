# 🦉 OReport

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OCore-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OReport** — Pentest Report & Findings Generator

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OReport is a penetration-test report and findings generator. It manages findings with CWE tagging and evidence hashing, calculates CVSS 3.1 scores, and renders engagement reports as Markdown, HTML, TXT, JSON or CSV. It can import findings from JSON/CSV and Nessus/Nmap exports and redact client-sensitive data.

---

## ✨ Features

- Findings manager with CWE tagging, affected assets and SHA-256 evidence hashing
- Full CVSS 3.1 calculator with base, temporal and environmental scoring
- Engagement metadata and an auto-generated executive summary with an ASCII risk matrix
- Import from JSON/CSV plus Nessus- and Nmap-style CSV parsers
- Render Markdown, self-contained HTML, TXT, JSON and CSV outputs
- Redaction engine and a scoring dashboard with trend diffing against previous reports

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OReport --new-project "Acme Q4" --client Acme
./OReport --add-finding "SQL Injection" --vector "CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H" --cwe 89
./OReport --render all -o ./out
./OReport --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
