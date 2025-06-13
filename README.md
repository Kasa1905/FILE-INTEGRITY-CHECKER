# FILE-INTEGRITY-CHECKER
====================================
*COMPANY*: CODETECH IT SOLUTIONS  
====================================
*NAME*: KAUSHIK SAMBE  
====================================
*INTERN ID*: CT04DG899  
====================================
*DOMAIN*: Cyber Security & Ethical Hacking  
====================================
*DURATION*: 4 WEEKS  
====================================
*MENTOR*: NEELA SANTOSH 
=====================================

## Key_logger.py

### Overview

`Key_logger.py` is a Python script that records all keystrokes made on the keyboard. It uses the `pynput` library to listen for keyboard events and logs them to a file named `log.txt`. This tool is intended for educational and ethical use in the context of cybersecurity and ethical hacking.

### Features

- Captures all keystrokes, including letters, numbers, symbols, and special keys (space, enter, tab, etc.).
- Logs keystrokes to a file (`log.txt`) for later analysis.
- Handles both regular and special keys gracefully.

### How It Works

- The script sets up a keyboard listener using `pynput`.
- Each key press is processed by the `handle_key_press` function.
- Regular characters are written directly to the log file.
- Special keys are logged in a readable format (e.g., `[space]`, `[enter]`).

### Usage

1. **Install Dependencies**  
   Make sure you have the `pynput` library installed:
   ```bash
   pip install pynput
   ```

2. **Run the Script**  
   Execute the script using Python:
   ```bash
   python Key_logger.py
   ```

3. **View Logs**  
   All captured keystrokes will be saved in `log.txt` in the same directory.

### Ethical Considerations

- This keylogger is intended for educational purposes only.
- Use this tool responsibly and only on systems you own or have explicit permission to test.
- Misuse of this tool can lead to legal consequences.

### Disclaimer

This script is for educational and ethical testing purposes only. Unauthorized use of keyloggers is illegal and unethical. Always obtain proper authorization before running this script on any system.

---