# Keyvok: Offline Password Vault for Windows
**High-Entropy Security. Zero-Cloud Privacy.**

Keyvok is a professional-grade, local-first password manager built for users who demand absolute control over their digital security. By combining a native **C++ core** with a modern **Microsoft WebView2** interface, Keyvok provides a seamless user experience without ever "phoning home" or requiring an internet connection.

[**Visit Official Website**](https://keyvok.com) | [**Interactive Web Preview**](https://keyvok.com/preview)

---

### 🛡️ Security Architecture
Keyvok is designed with a "Zero-Trust Cloud" philosophy. Your data never leaves your machine.

* **Encryption:** Leverages **Windows Data Protection API (DPAPI)**, ensuring your database is cryptographically tied to your specific Windows User Profile.
* **Storage:** Powered by a hardened, local **SQLite** engine.
* **Entropy:** Supports up to **144-bit entropy** for master keys, exceeding standard industry recommendations for long-term data persistence.
* **Privacy:** No accounts, no subscriptions, and no telemetry. Your vault is truly private.

---

### 📥 Verified Downloads (v1.0.0)
As a security utility, we provide SHA-256 checksums for every official release. Please verify your installer before execution.

| Edition | Official Link | SHA-256 Checksum |
| :--- | :--- | :--- |
| **Keyvok Lite** | [Download EXE](https://keyvok.com/dl/keyvok_lite_setup.exe) | `PASTE_LITE_HASH_HERE` |
| **Keyvok Pro** | [Customer Portal](https://keyvok.com/account) | `PASTE_PRO_HASH_HERE` |

> **Verification Command (PowerShell):**
> `Get-FileHash .\keyvok_setup.exe -Algorithm SHA256`

---

### 🖥️ System Requirements
* **OS:** Windows 10 (1809+) or Windows 11 (x64).
* **Runtime:** [Microsoft Edge WebView2](https://developer.microsoft.com/en-us/microsoft-edge/webview2/) (Evergreen).
    * *Note: Our installer automatically detects and assists with the WebView2 setup if it is missing from your system.*
* **Memory:** < 64MB RAM during active use.

---

### 📦 Installation via WinGet
For automated deployment and updates via the Windows Package Manager:
```powershell
winget install RadiantSoftware.Keyvok
