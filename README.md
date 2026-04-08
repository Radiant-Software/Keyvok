# Keyvok: Offline Password Vault for Windows
**High-Entropy Security. Zero-Cloud Privacy.**

Keyvok is a professional-grade, local-first password manager built for users who demand absolute control over their digital security. By combining a native **C++ core** with a modern **Microsoft WebView2** interface, Keyvok provides a seamless user experience without ever "phoning home" or requiring an internet connection.

[**Visit Official Website**](https://keyvok.com)

---

### 🛡️ Security Architecture
Keyvok is designed with a "Zero-Trust Cloud" philosophy. Your data never leaves your machine.

* **Encryption:** Leverages **Windows Data Protection API (DPAPI)**, ensuring your database is cryptographically tied to your specific Windows User Profile.
* **Storage:** Powered by a hardened, local **SQLite** engine.
* **Entropy:** Supports **144-bit entropy** for master keys, exceeding standard industry recommendations for long-term data persistence.
* **Privacy:** Local-only access. No user accounts, no subscriptions, and no telemetry.

---

### 📥 Verified Downloads (v1.0.0)
We provide SHA-256 checksums for every official release. Please verify your installer before execution.

| Edition | SHA-256 Checksum |
| :--- | :--- |
| **Keyvok Lite** | `b2247ccd2b5cfba5c018e2a4e1814fdfeb20ca7294d914a9894fcdb52fff41c3` |
| **Keyvok** | `4b53df8cf30b527615a71c675d213b75901e7cbf422e0146ff9431bcaced5638` |

> **Verification Command (PowerShell):**
> `Get-FileHash .\Keyvok-Lite-Setup-x64.exe -Algorithm SHA256`

* **Integrity:** Binaries are digitally signed by Radiant Software LLC.

---

### 🖥️ Technical Specifications
* **Installer Size:** ~2.5 MB
* **OS:** Windows 10 (1809+) or Windows 11 (x64).
* **Runtime:** [Microsoft Edge WebView2](https://go.microsoft.com/fwlink/p/?LinkId=2124703) (Official Microsoft Installer).
    * *Note: Our installer automatically detects and assists with the WebView2 setup if it is missing from your system.*

---

### 🛡️ License
Keyvok is a proprietary product of **Radiant Software LLC**. 
* **License:** [Proprietary EULA](LICENSE.txt)
* **Terms:** This software is licensed, not sold. Unauthorized redistribution is prohibited.

---

### 📬 Support & Bug Reports
This repository is the primary **Public Issue Tracker** for Keyvok. 
* **Found a bug?** Please [Open a New Issue](https://github.com/Radiant-Software/Keyvok/issues).
* **Feature Request?** We value community feedback for our roadmap.
* **Email Support:** `support [at] keyvok.com`

**Radiant Software LLC**
