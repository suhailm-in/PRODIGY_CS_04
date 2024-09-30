# Keylogger

This Python script is a basic keylogger that records keystrokes and logs them to a file named `keylog.txt` in the user's home directory. The script is designed for educational purposes and ethical use only. Unauthorized use of this script may violate privacy laws.

## Features

- Logs all keystrokes, including both character keys and special keys (e.g., Enter, Shift, etc.).
- Stores keystrokes in a log file (`keylog.txt`) located in the user's home directory.
- Stops recording when the `esc` key is pressed.
- Automatically installs the `pynput` module if it is not already installed.

# Resources
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Disclaimer](#Disclaimer)

## Requirements

- **Python 3.x** installed on your system.
- `pynput` Python package (the script will install it automatically if not present).

## Installation

### Clone the repository
```bash
git clone https://github.com/suhailm-in/PRODIGY_CS_04.git
```
```bash
cd PRODIGY_CS_04
```

## Usage

1. Run the script using Python:
```bash
python keylogger.py
```
2. The script will start logging keystrokes. You can find the log file in your home directory under the name `keylog.txt`.
3. To stop the keylogger, press the `esc` key.

## Logging

- The keystrokes are stored in `keylog.txt`, located in the user's home directory.
- Regular characters are logged as-is (e.g., `a`, `b`, `1`, etc.).
- Special keys (e.g., Enter, Shift, Ctrl) are logged in square brackets (e.g., `[Key.enter]`, `[Key.shift]`).

## Disclaimer

This script is for educational purposes only. Unauthorized use of this keylogger on any device or system is illegal and unethical. Ensure you have permission before using this script to log keystrokes. The author takes no responsibility for any misuse of this script.


## Developed by
### Suhail M 
Ethical Hacker, Penetration Tester, and AI Researcher in Cybersecurity
<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/suhailm_in" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="suhailm_online" height="30" width="40" /></a>
<a href="https://linkedin.com/in/suhailm-in" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="suhailm-online" height="30" width="40" /></a></p>



