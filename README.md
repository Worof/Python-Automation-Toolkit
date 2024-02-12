# Python Automation Toolkit 🚀

## Overview 🌟

This project consists of several Python scripts 📜 designed to automate various tasks 🛠️. Each script serves a specific purpose and can be used independently or in combination with others to streamline your workflow.

## Scripts 📚

### 1. File Organizer 🗂️

- **Description**: Organizes files in the current directory into folders based on their file types (e.g., Images 🖼️, Videos 🎬, Documents 📄).
- **New Features**:
  - **Customizable File Extension Mapping**: Specify file extensions for each category via command-line arguments. 🎛️
  - **Dry Run Option**: Simulate file organization without making any actual changes. 🔄
  - **Logging**: Logs actions, providing a detailed report of the files moved. 📋
  - **Interactive Mode**: Make decisions on overwriting existing files, skipping files, or changing the destination folder on the fly. 💡
  - **Security Features**: Prevent accidental moves of sensitive files with confirmation steps for certain types or directories. 🔒
  - **Undo Functionality**: Revert your last file organization operation, restoring files to their original locations. ⏪

- **Usage**: Run the script in a directory to auto-sort all files into categorized folders. Use command-line arguments to customize behavior. 🏃‍♂️

### 2. Water Reminder 💦

- **Description**: Sends random water drinking reminders at different times of the day using Pushbullet. Designed for regular scheduling. ⏲️
- **Dependencies**: Requires `pushbullet.py` library and a valid Pushbullet API key. 🔑
- **Setup**:
  - Place your Pushbullet API key in the script. 🔐
  - Ensure the `Reminder to Drink Water.txt` file with quotes is in the same directory. 📝
  - Run locally or set up on PythonAnywhere for automated scheduling. 🌐

### 3. Image Resizer 📸

- **Description**: Resizes images in the current directory to a specified size and saves them in a designated output folder. 🔄
- **Usage**: Input the desired image size and output folder when prompted. 🎚️

### 4. PDF to Audio Converter 📖🔊

- **Description**: Converts text from PDF files into audio MP3 files, perfect for creating audiobooks or auditory learning. 🎧
- **New Features**:
  - **User Input for File Names**: Specify PDF and output audio file names. ✍️
  - **Voice Customization**: Choose from available voices and accents. 🗣️
  - **Audio Quality Settings**: Set the audio format and bitrate for the output file. 🎚️
- **Usage**: Convert each page of the PDF into spoken words, saving as an MP3 file. 📚➡️🔉
- **Dependencies**: `pdfplumber`, `pyttsx3`, and `tqdm`. 🛠️

### Running on PythonAnywhere 🐍☁️

Set up the Water Reminder script on PythonAnywhere for continuous, scheduled execution:

1. **Create an Account**: Sign up for [PythonAnywhere]. 📝
2. **Upload Your Script**: Including the `water_reminder.py` and the reminder text file. 📤
3. **Install Dependencies**: Use the Bash console to install required libraries. 📦
4. **Schedule the Script**: For your desired frequency. 🕒

## Contributing 🤝

Contributions are welcome! Fork the repository and submit a pull request with your changes. Let's make automation even easier together! 💪
