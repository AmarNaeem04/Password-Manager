# Password Manager (Tkinter)

A lightweight Python Tkinter password manager that can generate strong passwords, copy them to your clipboard, and store/retrieve credentials (website, email, password) locally using a data.json file.

## Features

- Random strong password generator (letters + numbers + symbols)
- One-click copy to clipboard (via pyperclip)
- Save credentials locally to a JSON file (data.json)
- Search saved credentials by website name
- Basic input validation + error handling (missing fields / missing file)

## Tech Used

Python
Tkinter (GUI)
JSON (local storage)
pyperclip (clipboard support)
Project Files
main.py (your script)
logo.png (UI logo image)
data.json (auto-created when you save your first entry)

## Installation & Setup

- Clone/download this repo
Install dependencies:
```
pip install pyperclip
```
Make sure logo.png is in the same folder as your Python file.

- Run the app:
```python
python main.py
```

## How to Use

Website: enter the site name (e.g., Amazon)

Email/Username: enter your login email (or keep the default)

Click Generate Password to create a password (it’s copied to clipboard automatically)

Click Add Password to save it to data.json

To retrieve details later, type the website and click Search

