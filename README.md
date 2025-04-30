# Keylogger Script

This is a simple Python keylogger that records the keys pressed by the user and saves them to a file for later review. This project uses the `pynput` library to monitor keyboard events.

> ⚠️ **Disclaimer**:  
> This keylogger is for educational purposes only. Misuse of this tool is strictly prohibited. Please ensure that you have explicit permission to monitor devices or systems.

---

## 📌 Features

- **Key Press Logging**: Records all key presses and saves them to a file.
- **Esc Key to Stop**: The keylogger can be stopped by pressing the `Esc` key.
- **Logs Key Presses to File**: Pressed keys are written to `keylog.txt`.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- **Python**: Version 3.x or higher.
- **pynput library**: You can install this library using pip:
  
  ```bash
  pip install pynput
  ```

### Running the Script

1. **Clone or Download the Repository**:
   Download or clone the repository containing the keylogger script.

2. **Execute the Script**:
   Run the script with Python:

   ```bash
   python keylogger.py
   ```

   - The script will start listening to keyboard events.
   - Press keys to log them.
   - When you press the `Esc` key, the keylogger will stop.

3. **Check the Logs**:
   The logged keys will be saved in the `keylog.txt` file.

---

## 📂 Project Structure

```plaintext
Keylogger/
├── keylogger.py    # Python script containing the keylogger functionality
└── keylog.txt      # File where the pressed keys are saved
```

---

## 🔒 Legal & Ethical Considerations

- **Usage**: This keylogger is intended for educational purposes only. It should not be used to monitor or record someone else's activities without their consent.
- **Permission**: Always ensure that you have explicit permission before using this tool.
- **Privacy**: Be mindful of privacy laws and regulations in your jurisdiction when using this tool.

