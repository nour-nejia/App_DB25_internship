DB25 – ECU Configuration File Parsing and Analysis Tool
Overview

The DB25 project was developed during my internship at Ampere Software Technology.
It aims to simplify the management and analysis of Electronic Control Unit (ECU) configuration files used in vehicles.
These files, in BLOB or XML format, contain essential information for vehicle diagnostics and configuration.

Features

Import and parse XML configuration files.

Search for specific DIDs.

Extract BLOB files from the database.

User-friendly interface built with CustomTkinter.

Fast and reliable parsing.

Portable executable for Windows (via Nuitka + Inno Setup).

Technologies Used

Python – Core programming language

CustomTkinter – GUI framework

lxml & xml.etree.ElementTree – XML parsing

Nuitka – Python to executable compilation

Inno Setup – Windows installer packaging

Git/GitHub – Version control

Lucidchart – Functional modeling and diagrams

Installation
Windows Installer (Recommended)

You can directly download the latest stable version from the Releases page:
https://github.com/nour-nejia/App_DB25_internship/releases/tag/v1.0.0

Download the installer (DB25_installer.exe) from the release page

Run the installer and follow the installation wizard

Launch DB25 from the Start Menu or Desktop shortcut

Run from Source

Clone the repository:

git clone https://github.com/your-username/DB25.git
cd DB25


Run the application:

python main.py
