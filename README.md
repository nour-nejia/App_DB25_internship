# DB25 – ECU Configuration File Parsing and Analysis Tool

---

## Overview

**DB25** was developed during my internship at **Ampere Software Technology**.  
It simplifies management and analysis of **Electronic Control Unit (ECU)** configuration files used in vehicles.  
Supported file formats: **BLOB** and **XML**.

---

## Features

- Import and parse XML configuration files  
- Search for specific DIDs  
- Extract BLOB files from the database  
- User-friendly GUI built with CustomTkinter  
- Fast and reliable parsing  
- Portable Windows executable (Nuitka + Inno Setup)

---

## Technologies Used

- **Python**  
- **CustomTkinter**  
- **lxml** & **xml.etree.ElementTree**  
- **Nuitka**  
- **Inno Setup**  
- **Git / GitHub**  
- **Lucidchart**

---

## Installation

### Windows Installer (Recommended)

Download the latest stable release from the Releases page and run the installer:

**https://github.com/nour-nejia/App_DB25_internship/releases/tag/v1.0.0**

1. Download `DB25_installer.exe` from the release page  
2. Run the installer and follow the wizard  
3. Launch DB25 from the Start Menu or Desktop shortcut

### Run from Source

1. Clone the repository:
```bash
git clone https://github.com/nour-nejia/App_DB25_internship.git
cd App_DB25_internship
