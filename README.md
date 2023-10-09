
# NoirBird's IDM Activator (soon, star this repo for updates)

[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)

A simple Python script to activate Internet Download Manager.

**Note: I do NOT condone using cracked software. Please buy [a licence](https://secure.internetdownloadmanager.com/buy_idm.html).**
## Usage

**PowerShell Command (Recommended):**

(Always up to date, Run PowerShell as Administrator)

```ps
iwr -useb https://raw.githubusercontent.com/NoirBird/IDM-Activator/main/powershell-install.ps1 | iex
```

**Python Script:**

```bat
  py NoirBird-IDM-Patcher.py
```

**EXE File:**

```bat
Just open the file LoL
```


## Building

To convert Python file to Executable binary you may use 2 different options:

**Nuitka:**

```bat
  pip install nuitka
  nuitka --mingw64 --onefile --assume-yes-for-downloads --remove-output --output-filename=NBWRPatcher "NoirBird-IDM-Patcher.py"
```

**PyInstaller:**

```bat
  pip install pyinstaller
  pyinstaller -F --uac-admin NoirBird-IDM-Patcher.py
```
