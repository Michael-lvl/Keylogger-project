# Keylogger Project!

## Overview

This Python script captures keyboard input and logs it to a file (`keylog.txt`) in real-time!.

## Technologies

* Python 3
* pynput
* venv (virtual environment for safe development)

## How to Use

1. Create and activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

2. Install dependencies:

   ```bash
   pip install pynput
   ```

3. Run the keylogger:

   ```bash
   python3 keylogger.py
   ```

4. Press `Ctrl+C` to stop logging*

5. View the log file:

   ```bash
   cat keylog.txt
   ```

## Disclaimer

This project is for "educational and ethical use only.
It runs only with user consent and stores logs locally.
Do not deploy this on any system you do not own or have permission to test.
