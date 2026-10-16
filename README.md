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

Pentest report & findings generator (CVSS 3.1, MD/HTML/JSON export)

---

## ✨ Features

- Findings manager — add / edit / delete / clone, CWE tagging, affected assets, references, status, evidence files hashed (SHA-256) — never embedded
- Full CVSS 3.1 calculator — vector parser with strict validation, base / temporal / environmental scores, sub-scores and qualitative severity rating
- Engagement metadata — client, scope (in / out), dates, methodology, team, rules of engagement
- Executive summary generator from finding stats, severity distribution bars, likelihood × impact ASCII risk matrix, overall posture rating
- Import findings from JSON / CSV, plus graceful Nessus-style and Nmap-style CSV parsers
- Render Markdown, self-contained HTML (inline CSS, no external assets), plain TXT, JSON and a CSV findings register — with location chooser
- Scoring dashboard — severity counts, SLA and remediation timeline, diff vs previous report
- Redaction engine — mask IPs, e-mails, secrets, tokens, hashes and hostnames for client-safe export
- Full CLI (--new-project, --add-finding, --import, --render md|html|json|txt|csv, --cvss VECTOR, ...)

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OReport
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
