# EasyArduinoCLI

EasyArduinoCLI is a C++ application designed to make using Arduino-CLI more user-friendly and faster, especially for beginners. It provides an easy interface for interacting with Arduino projects via the command line, simplifying tasks like managing boards, uploading sketches, and installing libraries.

## Features
- **User-Friendly Interface**: Simplifies Arduino-CLI commands into a more approachable interface.
- **Fast Setup and Execution**: Speeds up common tasks, reducing setup time.
- **Beginner-Friendly**: Ideal for new users who want to use Arduino-CLI without a steep learning curve.
- **Support for Multiple Arduino Boards**: Manage and upload code to various Arduino boards.
- **Windows-Only**: Optimized for Windows environments.

## Installation

1. **Download and Install**:
   - Download the latest release from the [releases page](https://github.com/IntelliMCA/EasyArduinoCLI/releases).
   - Extract the contents of the ZIP file to a folder on your system.

2. **Set up Arduino-CLI**:
   - Make sure you have Arduino-CLI installed on your system. If not, follow the [Arduino-CLI setup guide](https://github.com/arduino/arduino-cli) to install and configure it.

3. **Run EasyArduinoCLI**:
   - Open the command prompt (CMD) in the folder where you extracted EasyArduinoCLI.
   - Run the application with the following command:
     ```bash
     ACli <command>
     ```

## Usage

1. **Configure Arduino-CLI**: If you haven’t already configured Arduino-CLI, make sure to do so by following the setup guide. You will need to configure your boards and libraries before using EasyArduinoCLI.

2. **Running Commands**:
   You can run the following commands with EasyArduinoCLI:
   - `EasyArduinoCLI board list`: List all connected Arduino boards.
   - `EasyArduinoCLI upload <path_to_sketch>`: Upload an Arduino sketch to the selected board.
   - `EasyArduinoCLI install <library>`: Install a library for your project.

   Example usage:
   ```bash
   ACli upload C:\path\to\your\sketch.ino
   ```

   or

   ```bash
   ACli upload C:\path\to\your\sketch.cpp
   ```

4. **Help Command**: To get a list of all available commands, run:
```bash
ACli --help
```

###
If you'd like to contribute to the development of EasyArduinoCLI, feel free to fork the repository, open an issue, or submit a pull request. Contributions are welcome!

### License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/IntelliMCA/EasyArduinoCLI/LICENSE ) file for details.

