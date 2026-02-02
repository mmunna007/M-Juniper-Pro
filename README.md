# 🌐 M-Juniper Pro

Professional Juniper Router Configuration Generator for Windows

---

## 📝 Description

**M-Juniper Pro** is a modern Windows desktop application that simplifies the creation of Juniper router configurations. Designed for network engineers, this tool eliminates manual configuration errors and saves time by providing a user-friendly interface to generate production-ready Juniper commands.

### What It Does
- Generates complete Juniper router configurations with BGP, interfaces, and policies
- Supports up to 7 logical systems (INT, GGC, FNA, M-CDN, BDIX, BCDN, PNI)
- Automatically calculates IP addresses from CIDR blocks
- Creates custom export policies with community filters
- Exports configurations to clipboard or file

---

## 🚀 Quick Start

### For End Users
1. Download `M-Juniper-Pro.exe` from [Releases](https://github.com/mmunna007/m-juniper-pro/releases)
2. Run the EXE file (no installation needed)
3. Follow the [User Guide](USER_GUIDE.md) for detailed instructions

### For Developers
```bash
# Clone repository
git clone https://github.com/mmunna007/m-juniper-pro.git
cd m-juniper-pro

# Run application
python juniper_gui_modern.py

# Build executable
python create_icon.py
build_exe.bat
```

---

## ✨ Key Features

- ✅ **No Manual IP Calculation** - Automatic IP address computation from CIDR blocks
- ✅ **Multi-System Support** - Configure 7 logical systems simultaneously
- ✅ **Windows 11 Modern UI** - Clean, intuitive interface
- ✅ **BGP Configuration** - Complete neighbor setup with policies
- ✅ **One-Click Export** - Copy to clipboard or save to file
- ✅ **Custom Policies** - Generate export policies with community filters
- ✅ **Real-time Validation** - Instant error checking and feedback

---

## � Screenshots

### Main Interface
![Main Interface](screenshots/main-interface.png)

*Modern Windows 11-style interface with configuration panel (left) and output panel (right)*

### Logical System Configuration
![Configuration Panel](screenshots/ls-config.png)

*Per-logical system settings with automatic IP calculation, BGP communities, and custom export policies*

### Generated Output
![Generated Configuration](screenshots/output.png)

*Production-ready Juniper commands with proper formatting - ready to copy and deploy*

---

## �📖 Documentation

- **[User Guide](USER_GUIDE.md)** - Complete instructions for using the application
- **[Developer Guide](README_DEV.md)** - Technical details and contribution guidelines *(coming soon)*

---

## 🛠️ Built With

- Python 3.x
- Tkinter (GUI)
- ipaddress (IP calculation)
- PyInstaller (EXE packaging)

---

## 👤 Author

**Monjur Alam Munna**

🔗 GitHub: [@mmunna007](https://github.com/mmunna007/)

---

## 📄 License

GNU License - Free to use for personal and commercial purposes

---

*Making network configuration easier, one router at a time* 🌐
