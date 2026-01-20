

<h1 align="center">🛡️ PyShield</h1>

<p align="center">
  <b>The Ultimate Python Code Protection & Compilation Suite</b>
</p>

<p align="center">
  <img src="images/splashscreen.png" alt="PyShield Logo" width="400"/>
</p>

<p align="center">
  PyShield converts your Python source code (.py) into compiled binary files (.pyd) using Cython,<br/>
  making it extremely difficult to reverse-engineer. It then packages everything into a standalone<br/>
  Windows executable (.exe) that runs without requiring Python installation on the target machine.
</p>

<p align="center">
  <i>Transform your Python scripts into secure, compiled Windows executables with military-grade protection</i>
</p>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-installation">Installation</a> •
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-screenshots">Screenshots</a> •
  <a href="#-contributing">Contributing</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python 3.10+"/>
  <img src="https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License"/>
  <img src="https://img.shields.io/badge/GUI-PyQt6-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="PyQt6"/>
</p>

<p align="center">
  <a href="https://github.com/samay825/PyShield/stargazers">
    <img src="https://img.shields.io/github/stars/samay825/PyShield?style=for-the-badge&logo=github&logoColor=white&label=Stars&color=yellow" alt="Stars"/>
  </a>
  <a href="https://github.com/samay825/PyShield/network/members">
    <img src="https://img.shields.io/github/forks/samay825/PyShield?style=for-the-badge&logo=github&logoColor=white&label=Forks&color=blue" alt="Forks"/>
  </a>
  <a href="https://github.com/samay825/PyShield/watchers">
    <img src="https://img.shields.io/github/watchers/samay825/PyShield?style=for-the-badge&logo=github&logoColor=white&label=Watchers&color=orange" alt="Watchers"/>
  </a>
  <a href="https://github.com/samay825/PyShield/commits">
    <img src="https://img.shields.io/github/last-commit/samay825/PyShield?style=for-the-badge&logo=github&logoColor=white&label=Last%20Commit&color=purple" alt="Last Commit"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/repo-size/samay825/PyShield?style=flat-square&logo=github&label=Repo%20Size" alt="Repo Size"/>
  <img src="https://img.shields.io/github/issues/samay825/PyShield?style=flat-square&logo=github&label=Issues" alt="Issues"/>
  <img src="https://img.shields.io/github/issues-pr/samay825/PyShield?style=flat-square&logo=github&label=Pull%20Requests" alt="PRs"/>
  <img src="https://img.shields.io/github/downloads/samay825/PyShield/total?style=flat-square&logo=github&label=Downloads" alt="Downloads"/>
</p>

<p align="center">
  <a href="https://github.com/samay825/PyShield/releases/tag/v5.0">
    <img src="https://img.shields.io/badge/📦_Download-Latest_Release-blue?style=for-the-badge" alt="Download"/>
  </a>
</p>

---

<p align="center">
  <img src="images/main_window.png" alt="PyShield Main Window" width="800"/>
</p>

---

## ⚠️ Disclaimer

> **PyShield is designed for legitimate software protection purposes only.**
> 
> This tool is intended to help developers:
> - Protect intellectual property and proprietary algorithms
> - Distribute commercial Python applications securely
> - Prevent casual reverse engineering of source code
>
> ❌ **DO NOT** use this tool to hide malicious code, malware, or any software intended to harm users.
> 
> The developer assumes no responsibility for misuse of this software. By using PyShield, you agree to use it ethically and in compliance with all applicable laws.

---

## 🎯 What is PyShield?

**PyShield** is a powerful, all-in-one solution for protecting and distributing Python applications. It combines **Cython compilation** (converting `.py` to binary `.pyd` files) with **PyInstaller packaging** to create secure, standalone Windows executables.

### 🔥 Why PyShield?

| ❌ Problem | ✅ PyShield Solution |
|-----------|---------------------|
| Python source code is easily readable | Compiles to binary `.pyd` files - unreadable! |
| Distributing apps requires Python installed | Creates standalone `.exe` - no Python needed! |
| Complex PyInstaller configuration | One-click automated build with smart detection |
| Selenium/Playwright apps fail after packaging | Auto-bundles browser drivers & browsers |
| Manual dependency management | Intelligent import scanning & bundling |

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🔒 Code Protection
- **Cython Compilation** - Convert `.py` to native `.pyd` binaries
- **Source Code Removal** - No readable Python in final build
- **Anti-Decompilation** - Compiled C extensions are extremely hard to reverse
- **Obfuscation** - Additional code protection layer

</td>
<td width="50%">

### 📦 EXE Generation
- **One-Click Build** - Automated PyInstaller integration
- **UAC Admin Support** - Request elevated privileges
- **Custom Icons** - Brand your executables
- **Version Info** - Embed metadata in EXE

</td>
</tr>
<tr>
<td width="50%">

### 🔍 Smart Detection
- **Auto Import Scanning** - Detects all dependencies automatically
- **80+ Framework Support** - PyQt, Tkinter, Selenium, Playwright, AI/ML
- **Browser Bundling** - Auto-bundle WebDrivers & Playwright browsers
- **Data File Detection** - Include images, configs, assets

</td>
<td width="50%">

### 🎨 Modern Interface
- **Beautiful Dark Theme** - Professional, easy on the eyes
- **Real-time Build Logs** - Track every step of the process
- **Drag & Drop Support** - Simple project selection
- **Splash Screen** - Polished user experience

</td>
</tr>
</table>

---

## 🌐 Supported Frameworks

PyShield automatically detects and properly bundles these frameworks:

<p align="center">
  <img src="https://img.shields.io/badge/PyQt5-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="PyQt5"/>
  <img src="https://img.shields.io/badge/PyQt6-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="PyQt6"/>
  <img src="https://img.shields.io/badge/Tkinter-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Tkinter"/>
  <img src="https://img.shields.io/badge/PySide6-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="PySide6"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium"/>
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" alt="Playwright"/>
  <img src="https://img.shields.io/badge/Requests-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Requests"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>
</p>

---

## 📋 System Requirements

| Requirement | Details | Download Link |
|-------------|---------|---------------|
| **Operating System** | Windows 10/11 (64-bit) | - |
| **Python** | Version 3.10 or higher | [Download Python](https://www.python.org/ftp/python/3.14.2/python-3.14.2-amd64.exe) |
| **Visual Studio Build Tools** | 2019 or newer with C++ | [Download Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/) |

---

## 🚀 Installation

### 📌 Step 1: Install Python 3.10+

<details>
<summary><b>📥 Click to expand Python installation guide</b></summary>

<br>

1. **Download Python** from the official website:
   
   <p align="center">
     <a href="https://www.python.org/ftp/python/3.14.2/python-3.14.2-amd64.exe">
       <img src="https://img.shields.io/badge/Download-Python%203.14.2-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Download Python"/>
     </a>
   </p>

2. **Run the installer** with these settings:

   ```
   ┌─────────────────────────────────────────────────────────────┐
   │                    Python 3.14.2 Setup                      │
   │                                                             │
   │  ☑️ Install launcher for all users (recommended)           
   │  ☑️ Add python.exe to PATH  ⬅️ IMPORTANT! CHECK THIS!      
   │                                                             │
   │              [ Install Now ]    [ Customize ]               │
   └─────────────────────────────────────────────────────────────┘
   ```

   > ⚠️ **CRITICAL:** You MUST check **"Add python.exe to PATH"** or PyShield won't work!

3. **Verify installation** - Open Command Prompt (Win + R, type `cmd`):
   
   ```bash
   python --version
   ```
   
   ✅ Expected output: `Python 3.14.2.x` (or your installed version)
   
   ```bash
   pip --version
   ```
   
   ✅ Expected output: `pip 24.x.x from ...`

</details>

---

### 📌 Step 2: Install Visual Studio Build Tools

<details>
<summary><b>🔧 Click to expand Build Tools installation guide</b></summary>

<br>

Visual Studio Build Tools provides the **C++ compiler** required for Cython to convert Python to native binaries.

1. **Download Build Tools:**
   
   <p align="center">
     <a href="https://visualstudio.microsoft.com/visual-cpp-build-tools/">
       <img src="https://img.shields.io/badge/Download-VS%20Build%20Tools-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white" alt="Download Build Tools"/>
     </a>
   </p>

2. **Run the installer** and select the following:

   ```
   ┌─────────────────────────────────────────────────────────────┐
   │           Visual Studio Installer - Workloads               │
   │                                                             │
   │  ☑️ Desktop development with C++     ⬅️ SELECT THIS!       │
   │     └── MSVC v143 - VS 2022 C++ x64/x86 build tools         │
   │     └── Windows 11 SDK (10.0.22621.0)                       │
   │     └── C++ CMake tools for Windows                         │
   │                                                             │
   │  📦 Installation size: ~6.5 GB                              
   │                                                             │
   │                    [ Install ]                              │
   └─────────────────────────────────────────────────────────────┘
   ```

3. **Wait for installation** - This may take 10-30 minutes depending on your internet speed

4. **Restart your computer** after installation completes

5. **Verify installation** - Open Developer Command Prompt for VS 2022 in your windows 10/11:
   
   ```bash
   cl
   ```
   
   ✅ If you see "Microsoft (R) C/C++ Optimizing Compiler Version..." you're ready!
   
   ❌ If you see "'cl' is not recognized", try opening **"Developer Command Prompt for VS"** from Start Menu

</details>

---

### 📌 Step 3: Download PyShield

<p align="center">
  <a href="https://github.com/samay825/PyShield/releases/tag/v5.0">
    <img src="https://img.shields.io/badge/⬇️_DOWNLOAD-PyShield_v5.0-00C853?style=for-the-badge&logo=github&logoColor=white" alt="Download"/>
  </a>
</p>

<table align="center">
<tr>
<th align="center">📦 Download Option</th>
<th align="center">📝 Description</th>
<th align="center">🔗 Link</th>
</tr>
<tr>
<td align="center"><b>🚀 EXE (Recommended)</b></td>
<td>Ready-to-run Windows executable<br/><sub>No Python installation required!</sub></td>
<td align="center"><a href="https://release-assets.githubusercontent.com/github-production-release-asset/1138223948/f822dc42-5b87-4d56-a0a3-3273a8712979?sp=r&sv=2018-11-09&sr=b&spr=https&se=2026-01-20T13%3A43%3A20Z&rscd=attachment%3B+filename%3DPyShield_v5.0.0.zip&rsct=application%2Foctet-stream&skoid=96c2d410-5711-43a1-aedd-ab1947aa7ab0&sktid=398a6654-997b-47e9-b12b-9515b896b4de&skt=2026-01-20T12%3A43%3A06Z&ske=2026-01-20T13%3A43%3A20Z&sks=b&skv=2018-11-09&sig=lBYRehEfEwB2IIyPw3ETUF4gTYkIgDsTP7xT2G3LFDo%3D&jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmVsZWFzZS1hc3NldHMuZ2l0aHVidXNlcmNvbnRlbnQuY29tIiwia2V5Ijoia2V5MSIsImV4cCI6MTc2ODkxNTU3MiwibmJmIjoxNzY4OTEzNzcyLCJwYXRoIjoicmVsZWFzZWFzc2V0cHJvZHVjdGlvbi5ibG9iLmNvcmUud2luZG93cy5uZXQifQ.UMs621itIDCGXzIErrLOpi8Ng3iKXz7Uc_AxNRCmr1Y&response-content-disposition=attachment%3B%20filename%3DPyShield_v5.0.0.zip&response-content-type=application%2Foctet-stream"><img src="https://img.shields.io/badge/Download-EXE-blue?style=flat-square&logo=windows" alt="EXE"/></a></td>
</tr>
<tr>
<td align="center"><b>📁 Source Code</b></td>
<td>Full source code (for developers)<br/><sub>Requires Python & Build Tools</sub></td>
<td align="center"><a href="https://github.com/samay825/PyShield/archive/refs/tags/v5.0.zip"><img src="https://img.shields.io/badge/Download-ZIP-green?style=flat-square&logo=github" alt="ZIP"/></a></td>
</tr>
</table>

<br/>


<details>
<summary><b>👨‍💻 Option A: How to use this ?</b></summary>

<br/>

---

### 📌 Step 4: Launch PyShield

```bash
run .exe 
```

🎉 **PyShield is now ready to use!**

---

## ⚡ Quick Start

### Using the GUI

```
┌─────────────────────────────────────────────────────────────────┐
│  🛡️ PyShield v5.0                                    ─ □ ✕     │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  📁 Project Path                                                
│  ┌─────────────────────────────────────────────────┐ [Browse]   │
│  │ C:\Users\You\MyPythonProject                    │            │
│  └─────────────────────────────────────────────────┘            │
│                                                                 │
│  ⚙️ Build Options                                               
│  ┌─────────────────────────────────────────────────────────┐    │
│  │ ☑️ Enable Cython Compilation (.py → .pyd)                
│  │ ☑️ Create Standalone EXE                                  
│  │ ☐ Request UAC Admin Privileges                              
│  │ ☐ Show Console Window                                        
│  └─────────────────────────────────────────────────────────┘    │
│                                                                 │
│  🎨 Icon: [shield.ico]                        [Change Icon]     
│                                                                 │
│              ┌──────────────────────┐                           │
│              │    🚀 BUILD NOW      │                           
│              └──────────────────────┘                           │
│                                                                 │
│  📋 Build Log                                                   
│  ┌─────────────────────────────────────────────────────────┐    │
│  │ [16:30:01] ✓ Scanning project imports...                │    
│  │ [16:30:02] ✓ Detected 15 Python files                   │    
│  │ [16:30:03] ✓ Compiling main.py → main.pyd               │    │
│  │ [16:30:05] ✓ Compiling utils.py → utils.pyd             │    │
│  │ [16:30:08] ✓ Creating executable...                     │    │
│  │ [16:30:45] 🎉 BUILD SUCCESSFUL!                         │    │
│  └─────────────────────────────────────────────────────────┘     
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### Build Steps

1. **Select Project** → Choose your Python project folder
2. **Configure Options** → Enable/disable features as needed
3. **Click Build** → Watch the real-time build progress
4. **Get Your EXE** → Find it in the `dist/` folder

---

## 🛠️ Configuration Options

| Option | Description | Default |
|--------|-------------|---------|
| `Cython Compilation` | Convert .py files to .pyd binaries | ✅ Enabled |
| `Create EXE` | Generate standalone executable | ✅ Enabled |
| `UAC Admin` | Request admin privileges on launch | ❌ Disabled |
| `Console Window` | Show/hide console window | ❌ Hidden |
| `Custom Icon` | Use custom .ico file for EXE | shield.ico |
| `One-File Mode` | Bundle everything into single EXE | ❌ Disabled |

---

## 🔧 Troubleshooting

<details>
<summary><b>❌ "Python not found" or "'python' is not recognized"</b></summary>

**Cause:** Python is not in your system PATH.

**Solution:**
1. Uninstall Python completely
2. Download Python again from [python.org](https://www.python.org/ftp/python/3.14.2/python-3.14.2-amd64.exe)
3. During installation, ✅ CHECK **"Add python.exe to PATH"**
4. Restart your computer
5. Open new Command Prompt and verify: `python --version`

</details>

<details>
<summary><b>❌ "Unable to find vcvarsall.bat" or Cython compilation fails</b></summary>

**Cause:** Visual Studio Build Tools not installed or missing C++ components.

**Solution:**
1. Download [VS Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/)
2. Run installer and select **"Desktop development with C++"**
3. Make sure these components are checked:
   - MSVC v143 - VS 2022 C++ x64/x86 build tools
   - Windows 11 SDK
4. Restart your computer after installation

</details>

<details>
<summary><b>❌ Build completes but EXE crashes on startup</b></summary>

**Cause:** Missing dependencies or imports not detected.

**Solution:**
1. Check build logs for any warnings
2. Ensure all data files (images, configs) are in project folder
3. Test running from source first: `python main.py`
4. Check if antivirus is blocking the EXE

</details>

<details>
<summary><b>❌ Selenium/Playwright "driver not found" in EXE</b></summary>

**Cause:** Browser drivers not bundled with the EXE.

**Solution:**
PyShield automatically bundles drivers, but ensure:
1. Drivers are installed via `pip install webdriver-manager` (Selenium)
2. Browsers are installed via `playwright install` (Playwright)
3. Rebuild the project

</details>

---

## 🤝 Contributing

Contributions are what make the open-source community amazing! Any contributions you make are **greatly appreciated**.

### How to Contribute

1. 🍴 **Fork** the repository
2. 🌿 **Create** your feature branch
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. 💻 **Commit** your changes
   ```bash
   git commit -m "Add some AmazingFeature"
   ```
4. 📤 **Push** to the branch
   ```bash
   git push origin feature/AmazingFeature
   ```
5. 🔃 **Open** a Pull Request

### Development Setup

```bash
# Clone your fork
git clone https://github.com/samay825/PyShield.git
cd PyShield

# Create dev environment
python -m venv .venv
.\.venv\Scripts\Activate.ps1

# Install dev dependencies
pip install -r requirements.txt
pip install pytest black flake8

# Run tests
pytest tests/

# Format code
black src/
```

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2026 Samay825

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files...
```

---

## 💖 Support the Project

If PyShield helped you protect your Python code, consider supporting the project:

<p align="center">
  <a href="https://github.com/samay825/PyShield/stargazers">
    <img src="https://img.shields.io/badge/⭐-Star%20this%20repo-yellow?style=for-the-badge" alt="Star"/>
  </a>
  <a href="https://github.com/samay825/PyShield/issues/new?template=bug_report.md">
    <img src="https://img.shields.io/badge/🐛-Report%20a%20Bug-red?style=for-the-badge" alt="Bug"/>
  </a>
  <a href="https://github.com/samay825/PyShield/issues/new?template=feature_request.md">
    <img src="https://img.shields.io/badge/💡-Request%20Feature-blue?style=for-the-badge" alt="Feature"/>
  </a>
</p>

---

## 🙏 Acknowledgments

Special thanks to these amazing projects that make PyShield possible:

- [**Cython**](https://cython.org/) - C-Extensions for Python
- [**PyInstaller**](https://pyinstaller.org/) - Freeze Python applications
- [**PyQt6**](https://www.riverbankcomputing.com/software/pyqt/) - Python Qt bindings
- [**Python**](https://www.python.org/) - The best programming language

---

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-❤️-red?style=for-the-badge" alt="Made with Love"/>
  <img src="https://img.shields.io/badge/Powered%20by-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Built%20with-Coffee-brown?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white" alt="Coffee"/>
</p>

<p align="center">
  <b>Made with ❤️ by <a href="https://github.com/samay825">Samay825</a></b>
</p>

<p align="center">
  <sub>⭐ Star this repo if you found it helpful!</sub>
</p>








