# Manjaro Linux OS Installation Guide 🚀

![Manjaro Logo](https://manjaro.org/assets/images/logo.svg)

Welcome to the Manjaro Linux OS Installation repository! This guide provides a step-by-step approach to installing Manjaro Linux, a user-friendly and powerful operating system based on the Arch Linux platform. Whether you're a beginner or an experienced user, this guide will help you navigate the installation process smoothly.

## Table of Contents

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Downloading Manjaro](#downloading-manjaro)
4. [Creating Installation Media](#creating-installation-media)
5. [Booting from USB](#booting-from-usb)
6. [Installation Steps](#installation-steps)
7. [Post-Installation Configuration](#post-installation-configuration)
8. [Useful Resources](#useful-resources)
9. [Releases](#releases)
10. [Contributing](#contributing)
11. [License](#license)

## Introduction

Manjaro Linux is designed to be easy to use while providing access to powerful features. It offers a rolling release model, which means you always get the latest updates and features without needing to reinstall. This guide will take you through the installation process step-by-step, ensuring a smooth experience.

## Prerequisites

Before you start, make sure you have the following:

- A computer or laptop.
- A USB drive (at least 4 GB).
- A stable internet connection.
- Backup of your important data.

## Downloading Manjaro

To get started, download the latest version of Manjaro Linux from the official site. You can find the releases [here](https://github.com/mdshuvo25/Manjaro-Linux-OS-installation-/releases). 

Once you have downloaded the ISO file, you are ready to create your installation media.

## Creating Installation Media

You can create a bootable USB drive using various tools. Here are some popular options:

### For Windows

1. **Rufus**: A simple tool to create bootable USB drives.
   - Download Rufus from [here](https://rufus.ie/).
   - Open Rufus and select your USB drive.
   - Choose the Manjaro ISO file you downloaded.
   - Click "Start" to create the bootable USB.

### For macOS

1. **Etcher**: A user-friendly application for creating bootable USB drives.
   - Download Etcher from [https://www.balena.io/etcher/](https://www.balena.io/etcher/).
   - Open Etcher and select the Manjaro ISO file.
   - Choose your USB drive and click "Flash!" to create the bootable USB.

### For Linux

1. **dd Command**: A powerful command-line tool to create bootable USB drives.
   - Open a terminal.
   - Use the following command (replace `/dev/sdX` with your USB drive identifier):
     ```bash
     sudo dd if=path/to/manjaro.iso of=/dev/sdX bs=4M status=progress
     ```
   - Wait for the process to complete.

## Booting from USB

Once you have created your bootable USB drive, follow these steps to boot from it:

1. Restart your computer.
2. Enter the BIOS/UEFI settings (usually by pressing F2, F10, or DEL during startup).
3. Change the boot order to prioritize USB drives.
4. Save changes and exit the BIOS/UEFI settings.

Your computer should now boot from the USB drive, and you will see the Manjaro welcome screen.

## Installation Steps

1. **Select Boot Option**: Choose "Boot Manjaro" from the menu.
2. **Language Selection**: Select your preferred language and click "Next."
3. **Connect to the Internet**: If prompted, connect to a Wi-Fi network.
4. **Prepare Disk**: Choose "Erase disk" for a clean installation or "Manual partitioning" for advanced users.
5. **Select Time Zone**: Choose your time zone from the map.
6. **Create User Account**: Enter your name, username, and password.
7. **Install**: Click "Install" to start the installation process.

Once the installation is complete, you will see a prompt to restart your computer. Remove the USB drive when prompted.

## Post-Installation Configuration

After installation, you may want to configure your system:

- **Update System**: Open a terminal and run:
  ```bash
  sudo pacman -Syu
  ```
- **Install Additional Software**: Use the package manager to install software you need.
- **Customize Settings**: Adjust system settings to your liking.

## Useful Resources

- [Manjaro Official Documentation](https://manjaro.org/documentation/)
- [Manjaro Forum](https://forum.manjaro.org/)
- [Arch Wiki](https://wiki.archlinux.org/)

## Releases

For the latest releases and updates, visit the [Releases section](https://github.com/mdshuvo25/Manjaro-Linux-OS-installation-/releases). You can download the latest files and execute them as needed.

## Contributing

We welcome contributions! If you want to improve this guide, feel free to submit a pull request. Please ensure your changes are well-documented.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for using Manjaro Linux! We hope this guide helps you get started with your new operating system. Enjoy your journey with Manjaro!