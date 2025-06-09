🛡️ Keylogger Script (Educational Use Only)
📜 Description
This project is a basic Python-based keylogger that records keyboard inputs and stores them in a local text file. The script is designed to run silently in the background on Windows systems.

⚠️ Disclaimer:
This tool is intended only for educational and ethical use, such as monitoring your own device or for learning purposes. Unauthorized use for spying, surveillance, or other malicious intent is strictly prohibited and illegal.

📁 Project Structure

.
├── keylogger.py          # Main script to log keystrokes
└── key_strock.txt        # Output file where all keystrokes are saved

🚀 Features
Records keystrokes including special keys (e.g., enter, delete).
Stores logs with minimal footprint.
Runs hidden in the background on Windows.

⚙️ How It Works
keylogger.py listens for all keyboard events.
On every key release, it logs the keystroke into key_strock.txt.
The console window is hidden during execution using Windows API.

🛠️ Setup Instructions
📌 Prerequisites
Python 3.x

pynput library

📥 Installation
pip install pynput
▶️ Running the Script
⚠️ Run with administrative privileges for proper functionality.

python keylogger.py
The script will start silently and store all keystrokes in:

makefile

C:\Users\Harsha\Desktop\hello\key_strock.txt
📄 Sample Output (key_strock.txt)

delete  delete  r  cmd  enter  ctrl_l  delete  r  r  cmd  t  e  down  enter ...


❗ Important Notes
The file path is hardcoded. Modify the path variable in keylogger.py as needed.
This keylogger is not cross-platform and works only on Windows.
Running hidden scripts can trigger antivirus software — proceed with caution.

🧹 How to Stop the Keylogger
Press Ctrl + C in the terminal (if running in foreground).
Or terminate it from the Task Manager if running hidden.

📚 License
This project is licensed under the MIT License.
