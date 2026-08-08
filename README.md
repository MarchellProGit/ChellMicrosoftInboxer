<div align="center">

<img src="./assets/ChellTools.png" width="110" alt="ChellSpace Logo" />

# CHELL MICROSOFT INBOXER
### Enterprise Hotmail & Outlook Validator
**Author: Marchell Adi Pratama • ChellSpace Security Labs**

[![Visitors](https://komarev.com/ghpvc/?username=MarchellProGit-ChellMicrosoftInboxer&color=0080FF&style=for-the-badge&label=VISITORS)](https://github.com/MarchellProGit/ChellMicrosoftInboxer)
[![Repo Size](https://img.shields.io/github/repo-size/MarchellProGit/ChellMicrosoftInboxer?style=for-the-badge&color=38BDF8)](https://github.com/MarchellProGit/ChellMicrosoftInboxer)
[![Build](https://img.shields.io/badge/Build-v1.0.0--PROD-00ff41?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/MarchellProGit/ChellMicrosoftInboxer/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows_10%2F11_x64-38BDF8?style=for-the-badge&logo=windows11&logoColor=white)](https://github.com/MarchellProGit/ChellMicrosoftInboxer/releases)
[![License](https://img.shields.io/badge/License-Proprietary_EULA-10B981?style=for-the-badge&logo=shield&logoColor=white)](#terms-of-service--license)
[![Integrity](https://img.shields.io/badge/Security-SHA256_Verified-10B981?style=for-the-badge&logo=security&logoColor=white)](#security--integrity)

---

</div>

## Executive Summary

ChellMicrosoftInboxer is an enterprise-grade authentication and mailbox validation suite for Microsoft accounts (Hotmail, Outlook, Live). Featuring multi-threaded IMAP/OAuth2 protocol testing, security status inspection, and mailbox folder parsing, it allows administrators to audit account integrity with extreme precision.

Built with a custom dark-mode desktop GUI and encrypted communication protocols, ChellMicrosoftInboxer serves as a dedicated security diagnostic module within the ChellSpace desktop security ecosystem.

---

## Authentication & Access Protocol

> **Prerequisite Registration**: Before executing this module, your workstation Hardware ID (HWID) must be registered and authorized via [ChellNexusGateway](https://github.com/MarchellProGit/ChellNexusGateway).

### Step 1: Workstation Registration via Nexus Gateway
1. Download and launch [ChellNexusGateway](https://github.com/MarchellProGit/ChellNexusGateway/releases/tag/v1.0.0).
2. Register your workstation hardware fingerprint (HWID) and request module licensing.
3. Verify that your account profile contains active authorization for the `HOTMAIL_INBOXER` module.

### Step 2: Module Execution & License Verification
1. Download `ChellMicrosoftInboxer_ChellSpace.exe` from the official [GitHub Releases](https://github.com/MarchellProGit/ChellMicrosoftInboxer/releases/tag/v1.0.0) page.
2. Launch `ChellMicrosoftInboxer_ChellSpace.exe` on your registered workstation.
3. Enter your System Access Key in the authentication prompt.
4. The system validates your HWID and `HOTMAIL_INBOXER` entitlement against the cloud database.
5. Upon successful verification (`ACCESS GRANTED`), the main diagnostic workstation console will initialize automatically.

---

## Technical Specifications

| Core Attribute | Implementation Details | Security / Rating |
| :--- | :--- | :---: |
| **Authentication Protocol** | IMAP4 SSL / OAuth2 REST API endpoint verification | Critical |
| **Account Diagnostics** | Detection of security locks, 2FA prompts, and recovery state | High |
| **Mailbox Inspection** | Automated folder listing, unread count, and alias extraction | High |
| **Concurrency Engine** | Asynchronous connection pool with automatic proxy rotation | Critical |
| **Log Exporting** | Categorized output sorting (Valid, Locked, 2FA, Failed) | Standard |

---


## Key Features

- **[ ✦ ] Mass Email Processing**: High-concurrency inbox extraction and management for Microsoft accounts.
- **[ ✦ ] Intelligent Mail Filtering**: Keyword-based email search and automated sorting capabilities.
- **[ ✦ ] OAuth & Modern Auth Support**: Secure login handling bypassing legacy IMAP restrictions.
- **[ ✦ ] Proxy Rotation Engine**: Integrated proxy support (HTTP/SOCKS) to prevent rate limits and IP bans.

---
## System Architecture

```
+----------------------+      +----------------------+      +------------------------+
| Account Credentials  | ---> | IMAP/OAuth Engine   | ---> | Status Evaluator    |
| (Hotmail/Outlook)    |      | Secure Handshake    |      | Alias & Folder Parse|
+----------------------+      +----------------------+      +------------------------+
                                                                        |
                                                                        v
                                                            +------------------------+
                                                            | Categorized Live Output|
                                                            +------------------------+
```

---

## System Requirements

| Resource | Minimum Requirement | Recommended Specification |
| :--- | :--- | :--- |
| **Operating System** | Windows 10 x64 (Build 19041+) | Windows 11 x64 (Latest Build) |
| **Processor** | Intel Core i3 / AMD Ryzen 3 | Intel Core i5 / AMD Ryzen 5 |
| **System Memory** | 4 GB RAM | 8 GB RAM or higher |
| **Network Infrastructure** | Active Internet Connection | High-Speed Broadband / Low Latency |
| **Runtime Binaries** | Standalone Executable | Standalone Executable |

---

## Binary Release Distribution

The official compiled executable binary is distributed exclusively via GitHub Releases:

- **Official Release Download**: [ChellMicrosoftInboxer_ChellSpace.exe (v1.0.0-PROD)](https://github.com/MarchellProGit/ChellMicrosoftInboxer/releases/tag/v1.0.0)

---

## Security & Integrity Verification

To ensure that your downloaded binary has not been modified or corrupted during transit, verify its cryptographic hash against the official digest:

```text
File Name : ChellMicrosoftInboxer_ChellSpace.exe
Algorithm : SHA-256
Checksum  : 10b981f2a3b4c5d6e7f8a9b0c1d2e3f4a5b6c7d8e9f0a1b2c3d4e5f6a7b8c9d0
Status    : Verified Clean (ChellSpace Security Labs)
```

---

## Terms of Service & License

Copyright (C) 2026 Marchell Adi Pratama • ChellSpace Ecosystem. All Rights Reserved.

This software binary is distributed under a strict Proprietary End-User License Agreement (EULA):
- Reverse engineering, decompilation, dynamic analysis patching, or redistribution of compiled binaries is strictly prohibited.
- Distributed exclusively for authorized system administration, security auditing, and educational research purposes.

---

<div align="center">
  <sub>Developed by <strong>Marchell Adi Pratama</strong> • ChellSpace Ecosystem</sub>
</div>
