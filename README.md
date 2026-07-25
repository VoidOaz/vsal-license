# Veteran Source-Available License (VSAL)

[![License: VSAL v1.2](https://img.shields.io/badge/License-VSAL_v1.2-blue.svg)](https://github.com/VoidOaz/vsal-license)
[![Status: Active](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()
[![Auditable](https://img.shields.io/badge/Code-100%25_Auditable-orange.svg)]()

**VSAL (Veteran Source-Available License)** is a modern, transparent, and balanced source-available software license designed specifically for backend software, server infrastructure, and Minecraft platform plugins (Paper/Purpur, Velocity/BungeeCord, core utilities, and beyond).

It bridges the gap between **100% Code Transparency** and **Commercial Protection**.

---

## 🌟 Key Features & Philosophy

Unlike restrictive proprietary licenses or permissive open-source licenses (MIT/GPL), **VSAL v1.2** addresses real-world software distribution challenges:

- **🔍 100% Source-Code Auditability** — Complete transparency for security researchers and system administrators to verify the absence of backdoors, malicious code, or covert telemetry.
- **🔒 Commercial Execution Protection** — Running compiled binaries in production environments requires an authorized commercial license or explicit agreement.
- **🛡️ Privacy-First Verification** — Asynchronous license checks use cryptographic salted SHA-256 hashes for IP validation. No plain IP addresses, personal data, or player database tracking.
- **🤝 Responsible Vulnerability Disclosure** — A 30-day private disclosure period for security bugs, shortened to 7 days for active zero-day exploits in the wild.
- **💻 Reproducible Builds** — Permits local self-compilation strictly for debugging, education, and verifying that official binaries match the public source code.
- **📜 Perpetual Inspection Rights** — Reviewers and auditors retain perpetual rights to inspect public source code releases for historical auditing.

---

## 📂 Available Templates

This repository provides ready-to-use license templates in multiple languages:

| File | Language |
| :--- | :--- |
| [`LICENSE.md`](./LICENSE.md) | 🇬🇧 English (Canonical) |
| [`LICENSE-TR.md`](./LICENSE-TR.md) | 🇹🇷 Turkish |
| [`LICENSE-ZH.md`](./LICENSE-ZH.md) | 🇨🇳 Chinese (Simplified) |
| [`LICENSE-ID.md`](./LICENSE-ID.md) | 🇮🇩 Indonesian |
| [`LICENSE-KO.md`](./LICENSE-KO.md) | 🇰🇷 Korean |
| [`LICENSE-FR.md`](./LICENSE-FR.md) | 🇫🇷 French |

---

## 🛠️ How to Apply VSAL v1.2 to Your Project

1. Copy the **full text** of [`LICENSE-TEMPLATE.md`](./LICENSE-TEMPLATE.md) into a file named `LICENSE.md` in your repository root.
2. Replace the placeholders:
   - `[YEAR]` → Current year (e.g., `2026`)
   - `[COPYRIGHT HOLDER / AUTHOR NAME]` → Your name or legal entity (e.g., `Berkay Kesgin (VoidOaz)`)
   - `[JURISDICTION / COUNTRY]` → Your legal jurisdiction (e.g., `Turkey`, `United States`, `Germany`)
3. Add the **VSAL Badge** to your project's `README.md`:

```markdown
[![License: VSAL v1.2](https://img.shields.io/badge/License-VSAL_v1.2-blue.svg)](https://github.com/VoidOaz/vsal-license)
