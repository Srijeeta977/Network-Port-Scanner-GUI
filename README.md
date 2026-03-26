# 🔍 Network Port Scanner GUI

A lightweight and fast TCP port scanner with a graphical user interface built using Python and Tkinter.

## 🚀 Features

* Simple GUI – enter target host, start port, and end port
* Multithreaded scanning – supports up to 500 concurrent threads for fast performance
* Service detection – identifies common services like HTTP, HTTPS, SSH, FTP, etc.
* Real-time updates – live progress bar and status display
* Stop functionality – safely stop scanning anytime
* Save results – export open ports to a `.txt` file
* Cross-platform – works on Windows, macOS, and Linux

## 🛠️ Requirements

* Python 3.7 or higher
* Tkinter (comes pre-installed with Python)

## 📦 Installation

```bash
git clone https://github.com/YOUR-USERNAME/network-port-scanner-gui.git
cd network-port-scanner-gui
```

## ▶️ Usage

```bash
python portscannergui.py
```

### Steps:

1. Enter target (IP or hostname)
2. Set port range (default: 1–1024)
3. Click **Start Scan**
4. View open ports in real time
5. Click **Stop** to cancel anytime
6. Save results after completion

## 🔎 Detected Services

Common ports are labeled automatically:

| Port | Service |
| ---- | ------- |
| 21   | FTP     |
| 22   | SSH     |
| 80   | HTTP    |
| 443  | HTTPS   |
| 3306 | MySQL   |
| 3389 | RDP     |

Other ports are marked as **Unknown**.

## 📂 Project Structure

```
network-port-scanner-gui/
├── portscannergui.py
├── README.md
```

## ⚠️ Disclaimer

This tool is for educational purposes only.
Do not scan systems without permission.

## 👨‍💻 Author

Srijeeta Dutta

