# HackingTool 🔧

> A fork of [Z4nzu/hackingtool](https://github.com/Z4nzu/hackingtool) — All-in-One Hacking Tool for Linux

![Python](https://img.shields.io/badge/python-3.x-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Platform](https://img.shields.io/badge/platform-Linux-lightgrey.svg)

## ⚠️ Disclaimer

This tool is intended for **educational and ethical penetration testing purposes only**.
Usage of this tool against targets without prior mutual consent is illegal.
The developer assumes no liability and is not responsible for any misuse or damage caused by this program.

## 📋 Features

- Anonymous Surfing
- Information Gathering
- Password Attacks
- Wireless Testing
- SQL Injection Tools
- Phishing Attack Tools
- Web Attack Tools
- Post Exploitation
- Forensics Tools
- Payload Creation
- Exploit Frameworks
- Reverse Engineering
- DDOS Attack Tools
- RAT Tools
- XSS Attack Tools
- Steganography Tools

## 🐧 Supported Distributions

| Distribution | Supported |
|---|---|
| Kali Linux | ✅ |
| Parrot OS | ✅ |
| Ubuntu / Debian | ✅ |
| Arch Linux | ✅ |
| Fedora | ⚠️ Partial |

## 🚀 Installation

### Standard Installation

```bash
git clone https://github.com/your-username/hackingtool.git
cd hackingtool
chmod +x install.sh
sudo bash install.sh
```

### Docker Installation

```bash
docker build -t hackingtool .
docker run -it hackingtool
```

## 🛠️ Usage

```bash
sudo python3 hackingtool.py
```

Navigate through the menu using the numbered options.

> **Personal note:** I primarily use this on Kali Linux inside a VirtualBox VM for CTF practice and home lab exercises. Tested and working well on Kali 2024.1.
>
> **Tip:** If the menu rendering looks off in your terminal, try setting `export TERM=xterm-256color` before running.
>
> **Tip:** Running inside tmux? Add `export PYTHONUNBUFFERED=1` as well to avoid output buffering issues with the interactive menu.
>
> **Tip:** If you get a `ModuleNotFoundError` on first run, try `pip3 install -r requirements.txt --break-system-packages` on newer Debian/Ubuntu-based systems that enforce PEP 668.

## 📁 Project Structure

```
hackingtool/
├── hackingtool.py       # Main entry point
├── tools/               # Tool category modules
│   ├── __init__.py
│   ├── infoGathering.py
│   ├── passwordAttack.py
│   └── ...
├── config/              # Configuration files
├── install.sh           # Installation script
├── requirements.txt     # Python dependencies
└── README.md
```

## 🤝 Contributing

Contributions are welcome! Please read our [Pull Request Template](.github/PULL_REQUEST_TEMPLATE.md) before submitting.

1. Fork the repository
2. Create your feature branch (`git checkout -b feat/new-tool`)
3. Commit your changes (`git commit -m 'feat: add new tool category'`)
4. Push to the branch (`git push origin feat/new-tool`)
5. Open a Pull Request

### Reporting Issues

- 🐛 [Bug Report](.github/ISSUE_TEMPLATE/bug_report.md)
- ✨ [Feature Request](.github/ISSUE_TEMPLATE/feature_request.md)
- 🔧 [Tool Request](.github/ISSUE_TEMPLATE/tool_request.md)

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements
