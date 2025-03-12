# GNOME-New-File-Templates

A collection of commands to enhance GNOME Files by providing a set of file templates for the "New File" creation functionality. GNOME Files allows you to quickly create new files based on templates stored in your `~/Templates` directory. This repository includes commands to set up a variety of template files for common file types.

## Overview

GNOME Files supports a feature where new documents can be created from templates stored in the `~/Templates` folder. This repository offers two options for setting up your templates:

- **Appending New Templates:** Add new templates to your existing `~/Templates` directory without altering any of your current files.
- **Reinitializing Templates:** Overwrite your current templates by completely resetting the `~/Templates` directory with the provided set of files.

## Installation

### Option 1: Append New Templates (Without Overwriting Existing Files)
If you already use your `~/Templates` folder and simply want to add these new templates, run the following commands in your terminal:

```bash
mkdir -p ~/Templates
touch ~/Templates/python.py
touch ~/Templates/index.html
touch ~/Templates/index.js
touch ~/Templates/style.css
touch ~/Templates/data.json
touch ~/Templates/document.csv
touch ~/Templates/example.svg
touch ~/Templates/README.md
touch ~/Templates/script.sh
touch ~/Templates/config.yml
touch ~/Templates/notes.txt
touch ~/Templates/Makefile
touch ~/Templates/Dockerfile
touch ~/Templates/LICENSE
touch ~/Templates/package.json
touch ~/Templates/.env
touch ~/Templates/requirements.txt
touch ~/Templates/test.py
touch ~/Templates/test.js
touch ~/Templates/test.html
```

### Option 2: Reinitialize Templates (Overwrite Existing Files)
If you prefer to start fresh and replace your current templates with this new set, run the following commands. This will remove your existing `~/Templates` directory and recreate it with the new files:

```bash
rm -rf ~/Templates
mkdir -p ~/Templates
touch ~/Templates/python.py
touch ~/Templates/index.html
touch ~/Templates/index.js
touch ~/Templates/style.css
touch ~/Templates/data.json
touch ~/Templates/document.csv
touch ~/Templates/example.svg
touch ~/Templates/README.md
touch ~/Templates/script.sh
touch ~/Templates/config.yml
touch ~/Templates/notes.txt
touch ~/Templates/Makefile
touch ~/Templates/Dockerfile
touch ~/Templates/LICENSE
touch ~/Templates/package.json
touch ~/Templates/.env
touch ~/Templates/requirements.txt
touch ~/Templates/test.py
touch ~/Templates/test.js
touch ~/Templates/test.html
```

## Usage

After installing the templates using one of the options above, follow these steps:

1. **Open GNOME Files.**
2. **Navigate to the directory** where you want to create a new file.
3. **Right-click** and choose **"New Document"** from the context menu.
4. **Select the desired template** from the list that appears.
5. A new file based on the selected template will be created automatically.
