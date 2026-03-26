#  Network Port Scanner GUI

A lightweight and fast TCP port scanner with a graphical user interface built using Python and Tkinter.
Built using socket programming and multithreading with real-time scanning updates.

---

##  Features

* Simple GUI – enter target host, start port, and end port
* Multithreaded scanning – up to 500 concurrent threads for fast performance
* Service detection – identifies common services like HTTP, HTTPS, SSH, FTP, etc.
* Real-time updates – live progress bar and status display
* Stop functionality – safely stop scanning anytime
* Save results – export open ports to a `.txt` file
* Cross-platform – works on Windows, macOS, and Linux

---

##  Requirements

* Python 3.7 or higher
* Tkinter (comes pre-installed with Python)

---

##  Installation

```bash
git clone https://github.com/Srijeeta977/network-port-scanner-gui.git
cd network-port-scanner-gui
```

---

##  Usage

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

---

##  Sample Output

```
Target: 192.168.1.1 (192.168.1.1)
Range: 1-1024

[+] Port 22 (SSH) is open
[+] Port 25 (SMTP) is open
[+] Port 23 (Telnet) is open
[+] Port 53 (DNS) is open
[+] Port 80 (HTTP) is open
[+] Port 119 (Unknown) is open
[+] Port 143 (IMAP) is open
[+] Port 110 (POP3) is open
[+] Port 465 (Unknown) is open
[+] Port 563 (Unknown) is open
[+] Port 587 (Unknown) is open
[+] Port 993 (Unknown) is open
[+] Port 995 (Unknown) is open

Scan complete.
Open ports found: 13
```

---

##  Detected Services

Common ports are labeled automatically:

| Port | Service |
| ---- | ------- |
| 21   | FTP     |
| 22   | SSH     |
| 23   | Telnet  |
| 25   | SMTP    |
| 53   | DNS     |
| 80   | HTTP    |
| 110  | POP3    |
| 143  | IMAP    |
| 443  | HTTPS   |
| 3306 | MySQL   |
| 3389 | RDP     |

Other ports are marked as **Unknown**.

---

##  Project Structure

```
network-port-scanner-gui/
├── portscannergui.py
├── README.md
```

---

##  Disclaimer

This tool is for educational purposes only.
Do NOT scan systems without proper authorization.

---

##  Author

Srijeeta Dutta
