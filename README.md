> This project is no longer maintained. The repository is archived.

# ControlPCbotV2

This is a script for remote control of your PC via a Telegram bot.

## Features and Capabilities

- ⚡ **Power management**: Shutdown and restart your computer
- 📸 **Screenshots**: Capture and send screenshots of your screen
- 📁 **File manager**: Full-featured file manager with folder archiving
- 🛑 **Process management**: View and terminate running processes
- 🔊 **Volume control**: Adjust system volume
- ⌨️ **Keyboard emulation**: Enter text and special key combinations
- 🖱 **Mouse emulation**: Full mouse control and clicking
- 🔒 **System lock**: Quickly lock your workstation
- 💻 **CMD commands**: Execute commands and receive results
- 📝 **Logging**: Keep a log of all executed commands
- 🚀 **Autorun**: Automatically start the bot when the system boots

## Setup and Launch

### Requirements
- Python 3.10
- Windows 7/8/10/11

### Installation Instructions

1. Clone the repository and edit `config.py` and `start.bat` as needed.
2. Install the dependencies:
```
pip install -r requirements.txt
```
3. Launch the bot:
```
python main.py
```
It is recommended to enable autorun via `/autorun`.

### Commands:
- `/menu` - Show the main control menu
- `/cmd [command]` - Execute a command in CMD (for example: /cmd ipconfig)

## New Version
A new version with a more user-friendly interface and a ready-to-use .exe application is available in the ControlPCbotV3 branch. However, it is not yet finished, and I do not plan to continue its development.