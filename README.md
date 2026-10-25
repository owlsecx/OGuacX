# 🦉 OGuacX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OWeb-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OGuacX** — Apache Guacamole Gateway Configuration Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OGuacX — Apache Guacamole Gateway Configuration Auditor. It provides stdlib parsers: Java .properties, user-mapping.xml, guacd.conf (INI), JDBC SQL schema / data dumps, nginx / Apache reverse-proxy snippets, Tomcat server.xml, logback.xml, GUACAMOLE_HOME layouts. Built-in demo/self-test paths and severity gates help validate detections without touching production when those flags are used.

---

## ✨ Features

- Stdlib parsers: Java .properties, user-mapping.xml, guacd.conf (INI), JDBC SQL schema / data dumps, nginx / Apache reverse-proxy snippets, Tomcat server.xml, logback.xml, GUACAMOLE_HOME layouts
- Session API timeout, request size, ban (brute-force) extension, TOTP / Duo MFA presence, header-auth, QuickConnect, JSON auth secret, extension-priority
- guacd TLS / bind exposure, guacd.conf [ssl] keys
- Connection hardening — RDP security / ignore-cert, SSH host-key / private-key, VNC & telnet cleartext, clipboard, SFTP / drive, recordings & key logging
- Default guacadmin (XML + SQL hash), cleartext / MD5 user-mapping passwords, JDBC passwords & TLS modes
- LDAP encryption, OIDC / SAML / CAS endpoints

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OGuacX                                     # interactive menu
./OGuacX --scan -r /path/to/root
./OGuacX --demo
./OGuacX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
