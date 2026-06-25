# 🌌 Void-Tool
`Void-Tool` is a powerful, terminal-based multitool built in Python featuring an immersive `Rich` TUI (Text User Interface) dashboard. It unifies essential diagnostics, intelligence gathering, network testing, and utility functions into a singular CLI experience.

> **⚠️ Disclaimer:** This tool is intended strictly for educational purposes, authorized security testing, and personal network diagnostics. Do not use it against systems or data you do not explicitly own or have permission to test.

---

## ⚡ Key Features

The ecosystem is split into structured, easy-to-navigate modules:

* **🔍 OSINT & Research:** Email verification utilities, account reset helpers, and rapid public-source lookups.
* **🌐 IP & Network Diagnostics:** Geolocation lookups, WHOIS-style registration parsing, active port scanners, and multi-protocol ping utilities.
* **💬 Server & Bot Management:** Helpers for managing automation webhooks, server configuration auditing, and Discord structural backups.
* **🔐 Crypto & Utilities:** Secure password generators, cryptographic hashing suites, and local temp-file management.
* **🎨 Customization:** Includes 13+ selectable UI themes to match your terminal workspace style.

---

## ⚙️ Installation

### Prerequisites
* Python 3.9 or higher installed on your machine.
* An active internet connection (required for real-time web lookups and internal module checks).

### Quick Start (Windows)
1. Download the latest release `.zip` file from the repository and extract it.
2. Double-click `setup.bat` to automatically verify environments and install necessary dependencies.
3. Run `start.bat` to launch the terminal application dashboard.

### Manual Installation (Linux / macOS / Windows CLI)
Clone the repository and install dependencies using `pip`:

```bash
# Clone the repository
git clone [https://github.com/yourusername/Void-Tools.git](https://github.com/yourusername/Void-Tools.git)
cd Void-Tools

# Install required packages
pip install -r requirements.txt

# Run the utility
python main.py
