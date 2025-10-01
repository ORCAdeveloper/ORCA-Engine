# 🐋 ORCA Engine - Vanilla

**ORCA Engine** is a lightweight, interactive command-line environment written in Python. It offers a playful yet functional shell experience with colorful output, splash text, and a variety of built-in commands for file handling, time display, system info, calculations, and more.

---

## ✨ Features

- 📟 Terminal interface with colorful, dynamic splash banner  
- ⏱ Uptime tracking and system info display  
- 🧮 Simple inline calculator (`calc`)  
- 🕒 Current time display in US Central timezone (`time`)  
- 📁 Basic file operations:
  - `new` — Create files
  - `open` — View file contents
  - `write` — Append text to files
  - `delete` — Remove files  
- 🌐 HTTP GET requests using `fetch`  
- 📜 File listing (`list`)  
- 🔁 Command help menu (`help`)  
- 🎨 Colorful input/output with dynamic text formatting

---

## 🛠 Requirements

- Python 3.7+
- `pytz`
- `requests`

Install dependencies (if not already available):

```bash
pip install pytz requests
