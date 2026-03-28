# Keyvok: Offline Password Vault for Windows
**High-Entropy Security. Zero-Cloud Privacy.**

Keyvok is a professional-grade, local-first password manager built for users who demand absolute control over their digital security. By combining a native **C++ core** with a modern **Microsoft WebView2** interface, Keyvok provides a seamless user experience without ever "phoning home" or requiring an internet connection.

[**Visit Official Website**](https://keyvok.com) | [**Interactive UI Preview**](https://github.com/Radiant-Software/Keyvok/blob/main/ui.min.html)

---

### 🛡️ Security Architecture
Keyvok is designed with a "Zero-Trust Cloud" philosophy. Your data never leaves your machine.

* **Encryption:** Leverages **Windows Data Protection API (DPAPI)**, ensuring your database is cryptographically tied to your specific Windows User Profile.
* **Storage:** Powered by a hardened, local **SQLite** engine.
* **Entropy:** Supports **144-bit entropy** for master keys, exceeding standard industry recommendations for long-term data persistence.
* **Privacy:** No accounts, no subscriptions, and no telemetry. Your vault is truly private.

---

### 📥 Verified Downloads (v1.0.0)
As a security utility, we provide SHA-256 checksums for every official release. Please verify your installer before execution.

| Edition | Official Link | SHA-256 Checksum |
| :--- | :--- | :--- |
| **Keyvok Lite** | [Download EXE](https://keyvok.com/download/Keyvok-Lite-Setup-x64.exe) | `PASTE_LITE_HASH_HERE` |
| **Keyvok** | [Website Purchase](https://keyvok.com) | `PASTE_HASH_HERE` |

> **Verification Command (PowerShell):**
> `Get-FileHash .\Keyvok-Lite-Setup-x64.exe -Algorithm SHA256`

---

### 🖥️ Technical Specifications
* **Binary Size:** ~1.6MB (C++ Optimized)
* **OS:** Windows 10 (1809+) or Windows 11 (x64).
* **Runtime:** [Microsoft Edge WebView2](https://go.microsoft.com/fwlink/p/?LinkId=2124703) (Official Microsoft Installer).
    * *Note: Our installer automatically detects and assists with the WebView2 setup if it is missing from your system.*

---

### 📦 Installation via WinGet
For automated deployment and updates via the Windows Package Manager:
```powershell
winget install RadiantSoftware.Keyvok
