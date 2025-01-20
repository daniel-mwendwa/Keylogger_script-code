# Keylogger Script-Code

This repository contains a Python-based keylogger script designed for educational purposes. It demonstrates basic keylogging functionality on Windows systems. Use responsibly and only in environments where you have explicit permission.

---

## Features

- Captures keystrokes in real-time.
- Logs keystrokes to a file (`output.txt`).
- Operates discreetly by hiding the console window.

---

## Requirements

- Python 3.x
- Windows OS
- The following Python libraries:
  - `pyWinhook`
  - `pythoncom`
  - `win32console`
  - `win32gui`

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/keylogger-script-code.git
   cd keylogger-script-code
   ```

2. **Install dependencies**:
   ```bash
   pip install pywin32 pyWinhook
   ```

3. **Run the script**:
   ```bash
   python keylogger.py
   ```

---

## How It Works

1. The script hides the console window upon execution for discretion.
2. Keystrokes are captured and logged to `output.txt` located at `C:\output.txt`.
3. Press `Ctrl+C` in the console to terminate the script.

---

## Code Breakdown

- **`onkeyboardevent` function**: Captures keystrokes and writes them to `output.txt`.
- **Hook Manager**: Uses `pyWinhook` to intercept keyboard events.
- **File Operations**: Reads and appends keystrokes to the log file.

---

## Usage Guidelines

- **Legal Compliance**: This script should only be used in scenarios where you have explicit consent, such as personal testing or controlled environments. Unauthorized use is illegal and unethical.
- **Educational Purpose**: The script is intended solely for learning about keylogging techniques.

---

## Disclaimer

This script is provided "as is" without any guarantees or warranties. The authors are not responsible for any misuse or damage caused by this software. Always use responsibly.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Connect with me on Linkedin
- [LinkedIn Profile](https://www.linkedin.com/in/daniel-mwendwa-bsc-a475311b7/)
