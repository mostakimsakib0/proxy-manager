## Proxy Manager

A GTK-based GUI tool to manage system proxy settings on Linux (APT, Git, and environment variables).

---

## Screenshot

![Proxy Manager UI](Screenshot.png)

---

## Features

- Enable / Disable proxy
- Session mode (no sudo required)
- System-wide proxy (APT + Git support)
- Proxy testing (real IP detection)
- Desktop notifications
- Saved proxy profiles
- Restart selected applications

---

## Installation

### Option 1: Install via .deb package (recommended)

1. Download the latest release from the [Releases](../../releases) page.
2. Install the package:

```bash
sudo dpkg -i proxy-manager.deb
````

3. If dependencies are missing, fix them with:

```bash
sudo apt-get install -f
```

---

### Option 2: Run from source

Clone the repository:

```bash
git clone https://github.com/mostakimsakib0/proxy-manager.git
cd proxy-manager
```

Run the application:

```bash
python3 proxy_gui.py
```

---

## Requirements

* Python 3
* python3-gi
* GTK 3
* libnotify-bin

Install dependencies:

```bash
sudo apt install python3 python3-gi gir1.2-gtk-3.0 libnotify-bin
```

---

## Usage

Launch the application from your system menu:

**Proxy Manager**

Or run manually:

```bash
python3 proxy_gui.py
```

---

## Notes

* Session mode does NOT affect APT (APT requires system-level configuration)
* Ensure your proxy server is running (e.g. `127.0.0.1:8080`)
* Some applications may require restart to apply proxy settings

---

## Known Limitations

* Browsers may ignore system proxy unless configured separately
* Session mode only applies to the current environment

---

## License

This project is open-source and available under the MIT License.

---

## Author

Developed by Mostakim Sakib

````

---

# 🧠 Why this is actually “professional”

- clear structure ✔  
- proper sections ✔  
- handles edge cases ✔  
- doesn’t assume user is you ✔  
- explains limitations (this is big) ✔  

---

# ⚠️ One last thing (don’t skip)

Make sure your repo has:

```text
screenshot.png
````
