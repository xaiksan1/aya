# Build Instructions for AYA

This document provides detailed build instructions for the AYA project, including prerequisites, commands to run, and troubleshooting tips. It also includes platform-specific build instructions for Windows, macOS, and Linux, as well as explanations of the purpose of each dependency listed in the `package.json` file.

## Prerequisites

- Node.js (version 18.x)
- npm (version 9.x)

## Detailed Build Instructions

1. **Clone the repository**:
   ```sh
   git clone https://github.com/liriliri/aya.git
   cd aya
   ```

2. **Install dependencies**:
   ```sh
   npm install
   ```

3. **Run the application in development mode**:
   ```sh
   npm run dev
   ```

4. **Build the application**:
   ```sh
   npm run build
   ```

5. **Package the application**:
   ```sh
   npm run pack
   ```

## Platform-Specific Build Instructions

### Windows

1. **Download the installer**: Click [here](https://github.com/liriliri/aya/releases/download/v1.9.0/AYA-1.9.0-win-x64.exe) to download the Windows installer.
2. **Run the installer**: Double-click the downloaded `.exe` file and follow the installation instructions.

### macOS

1. **Download the installer**: Click [here](https://github.com/liriliri/aya/releases/download/v1.9.0/AYA-1.9.0-mac-x64.dmg) to download the macOS installer.
2. **Run the installer**: Double-click the downloaded `.dmg` file, drag the AYA app to the Applications folder, and follow the installation instructions.

### Linux

1. **Download the installer**: Click [here](https://github.com/liriliri/aya/releases/download/v1.9.0/AYA-1.9.0-linux-x86_64.AppImage) to download the Linux installer.
2. **Make the file executable**: Open a terminal and run the following command:
   ```sh
   chmod +x AYA-1.9.0-linux-x86_64.AppImage
   ```
3. **Run the installer**: Double-click the `.AppImage` file or run the following command in the terminal:
   ```sh
   ./AYA-1.9.0-linux-x86_64.AppImage
   ```

## Troubleshooting Tips

- If you encounter any issues during the build process, make sure you have the required prerequisites installed and try running the commands with elevated privileges (e.g., using `sudo` on macOS and Linux).
- Check the [issue tracker](https://github.com/liriliri/aya/issues) for known issues and solutions.
- If you need further assistance, feel free to open a new issue or ask for help in the [discussion forum](https://github.com/liriliri/aya/discussions).

## Dependency Explanations

The `package.json` file lists all the dependencies required for the project. Here are some key dependencies and their purposes:

- **electron**: The core framework for building cross-platform desktop applications with JavaScript, HTML, and CSS.
- **vite**: A fast build tool and development server for modern web projects.
- **react**: A JavaScript library for building user interfaces.
- **mobx**: A state management library for managing application state.
- **axios**: A promise-based HTTP client for making API requests.
- **protobufjs**: A library for working with Protocol Buffers, a language-neutral, platform-neutral, extensible mechanism for serializing structured data.
- **eslint**: A tool for identifying and fixing problems in JavaScript code.
- **prettier**: An opinionated code formatter for maintaining consistent code style.
