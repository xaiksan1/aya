<div align="center">
  <a href="https://aya.liriliri.io/" target="_blank">
    <img src="https://aya.liriliri.io/icon.png" width="400">
  </a>
</div>

<h1 align="center">AYA</h1>

<div align="center">

Android ADB desktop app.

<a href="https://www.producthunt.com/posts/aya-1?embed=true&utm_source=badge-featured&utm_medium=badge&utm_souce=badge-aya&#0045;1" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=899538&theme=light&t=1740125747753" alt="AYA - Open&#0032;source&#0032;desktop&#0032;app&#0032;for&#0032;controlling&#0032;android&#0032;devices | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

[![Windows][windows-image]][release-url]
[![macOS][mac-image]][release-url]
[![Linux][linux-image]][release-url]
[![Downloads][download-image]][release-url]
![License][license-image]

</div>

[windows-image]: https://img.shields.io/badge/-Windows-blue?style=flat-square&logo=windows
[mac-image]: https://img.shields.io/badge/-macOS-black?style=flat-square&logo=apple
[linux-image]: https://img.shields.io/badge/-Linux-yellow?style=flat-square&logo=linux
[download-image]: https://img.shields.io/github/downloads/liriliri/aya/total?style=flat-square
[release-url]: https://github.com/liriliri/aya/releases
[license-image]: https://img.shields.io/github/license/liriliri/aya?style=flat-square

<img src="https://aya.liriliri.io/screencast.png" style="width:100%">

[AYA](https://aya.liriliri.io/) is a desktop application for easily controlling android devices, which can be considered as a GUI wrapper for ADB.

## Installation

Click [here](https://github.com/liriliri/aya/releases/) to download and install AYA. Windows x64, Mac arm64, Mac x64 and Linux x86_64 are supported.

### Prerequisites

- Node.js (version 18.x)
- npm (version 9.x)

### Detailed Steps for Installation

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

### Platform-Specific Installation Instructions

#### Windows

1. **Download the installer**: Click [here](https://github.com/liriliri/aya/releases/download/v1.9.0/AYA-1.9.0-win-x64.exe) to download the Windows installer.
2. **Run the installer**: Double-click the downloaded `.exe` file and follow the installation instructions.

#### macOS

1. **Download the installer**: Click [here](https://github.com/liriliri/aya/releases/download/v1.9.0/AYA-1.9.0-mac-x64.dmg) to download the macOS installer.
2. **Run the installer**: Double-click the downloaded `.dmg` file, drag the AYA app to the Applications folder, and follow the installation instructions.

#### Linux

1. **Download the installer**: Click [here](https://github.com/liriliri/aya/releases/download/v1.9.0/AYA-1.9.0-linux-x86_64.AppImage) to download the Linux installer.
2. **Make the file executable**: Open a terminal and run the following command:
   ```sh
   chmod +x AYA-1.9.0-linux-x86_64.AppImage
   ```
3. **Run the installer**: Double-click the `.AppImage` file or run the following command in the terminal:
   ```sh
   ./AYA-1.9.0-linux-x86_64.AppImage
   ```

### Troubleshooting Tips

- If you encounter any issues during installation, make sure you have the required prerequisites installed and try running the commands with elevated privileges (e.g., using `sudo` on macOS and Linux).
- Check the [issue tracker](https://github.com/liriliri/aya/issues) for known issues and solutions.
- If you need further assistance, feel free to open a new issue or ask for help in the [discussion forum](https://github.com/liriliri/aya/discussions).

### Dependency Explanations

The `package.json` file lists all the dependencies required for the project. Here are some key dependencies and their purposes:

- **electron**: The core framework for building cross-platform desktop applications with JavaScript, HTML, and CSS.
- **vite**: A fast build tool and development server for modern web projects.
- **react**: A JavaScript library for building user interfaces.
- **mobx**: A state management library for managing application state.
- **axios**: A promise-based HTTP client for making API requests.
- **protobufjs**: A library for working with Protocol Buffers, a language-neutral, platform-neutral, extensible mechanism for serializing structured data.
- **eslint**: A tool for identifying and fixing problems in JavaScript code.
- **prettier**: An opinionated code formatter for maintaining consistent code style.

## Features

<img src="https://aya.liriliri.io/screenshot.png" style="width:100%">

* Screen mirror
* File explorer
* Application manager
* Process monitor
* Layout inspector
* CPU, memory and FPS monitor
* Logcat viewer
* Interactive shell

For more detailed usage instructions, please read the documentation at [aya.liriliri.io](https://aya.liriliri.io)!

## Related Projects

* [licia](https://github.com/liriliri/licia): Utility library used by AYA.
* [luna](https://github.com/liriliri/luna): UI components used by AYA.
* [vivy](https://github.com/liriliri/vivy): Icon image generation.
* [echo](https://github.com/liriliri/echo): Harmony OS version of AYA.

## Contribution

Read [Contributing Guide](https://aya.liriliri.io/guide/contributing.html) for development setup instructions.
