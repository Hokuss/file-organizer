# Automated File Organizer 📂

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![CustomTkinter](https://img.shields.io/badge/GUI-CustomTkinter-darkgreen)
![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)

A sleek, modern desktop application built with Python that automatically sorts your cluttered folders (like Downloads or Desktop) based on customizable, priority-based rules. 

Instead of dealing with complex browser extensions that break dynamic downloads, this tool interacts natively with your OS file system to organize files safely and efficiently.

## ✨ Features

* **Modern Interface:** Built with CustomTkinter, featuring automatic Light/Dark mode syncing with your OS.
* **Smart Rule Engine:** Sort files by their **Extension** (e.g., `.pdf`, `.jpg`) or if their **Name Contains** a specific keyword (e.g., `invoice`).
* **Priority Routing:** Rules are evaluated from top to bottom. Use the intuitive up/down controls to prioritize which rules fire first.
* **Config Profiles:** Save and load different `.json` configuration files (e.g., one profile for your Downloads folder, another for your Work folder).
* **Safe Moving:** Built-in overwrite protection ensures that if a duplicate file name exists in the target folder, the new file is automatically renamed (e.g., `report_1.pdf`) instead of destroying your data.

## 🚀 Installation

1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/yourusername/automated-file-organizer.git](https://github.com/yourusername/automated-file-organizer.git)
