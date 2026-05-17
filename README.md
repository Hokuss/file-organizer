# Automated File Organizer 📂

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![CustomTkinter](https://img.shields.io/badge/GUI-CustomTkinter-darkgreen)
![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)

A sleek, modern desktop application built with Python that automatically sorts your cluttered folders (like Downloads or Desktop) based on customizable, priority-based rules.

Instead of dealing with complex browser extensions that break dynamic downloads, this tool interacts natively with your OS file system to organize files safely and efficiently.

## ✨ Features

- **Modern Interface:** Built with CustomTkinter, featuring automatic Light/Dark mode syncing with your OS.
- **Smart Rule Engine:** Sort files by their **Extension** (e.g., `.pdf`, `.jpg`) or if their **Name Contains** a specific keyword (e.g., `invoice`).
- **Priority Routing:** Rules are evaluated from top to bottom. Use the intuitive up/down controls to prioritize which rules fire first.
- **Config Profiles:** Save and load different `.json` configuration files (e.g., one profile for your Downloads folder, another for your Work folder).
- **Safe Moving:** Built-in overwrite protection ensures that if a duplicate file name exists in the target folder, the new file is automatically renamed (e.g., `report_1.pdf`) instead of destroying your data.

## 🚀 Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Hokuss/file-organizer
   ```

2. Navigate into the project directory:
   ```bash
   cd automated-file-organizer
   ```

3. Install the required GUI library:
   ```bash
   pip install customtkinter
   ```

## 🖥️ Usage

1. Run the application:
   ```bash
   python gui_organizer.py
   ```

2. **Set Folders:** Click `Browse` to select the "Source Folder" (the messy folder) and the "Target Folder" (where the clean subfolders should be created).

3. **Add Rules:** Select a match type, enter a value (like `.mp4`), and type the name of the subfolder it should be moved into (like `Videos`).

4. **Sort/Prioritize:** Use the `▲` and `▼` buttons on each rule card to change the priority.

5. Click **▶ RUN ORGANIZER**.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check out the [issues page](https://github.com/yourusername/automated-file-organizer/issues) if you want to contribute to this project.

## 📜 License

This project is licensed under the **GNU General Public License v3.0 (GPLv3)**.

This is a copyleft license. If you modify this software or use it as a starting point for a larger project, you are required to release your derivative work under the same open-source GPLv3 license. See the `LICENSE` file for full details.
