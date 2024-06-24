# LinuXP

LinuXP is a custom Linux distribution project inspired by the look and feel of Windows XP, built on the solid foundation of Debian. The goal is to create a 1:1 recreation of the Windows XP experience, including both the user interface and the installation process.

## Project Overview

- **Objective**: To create a Debian-based Linux distribution that exactly replicates the Windows XP user interface and experience.
- **Desktop Environment**: XFCE customized to look like Windows XP.
- **Installer**: Both text-based and graphical installers will be customized to mimic the Windows XP setup process.
- **SKU Selection**: The final version will include an SKU selection similar to Windows XP editions.
- **Wallpapers**: All original Windows XP wallpapers, including high-quality versions like "Autumn," will be included.
- **Auto Configuration**: XFCE will be automatically configured using [xfce-winxp-tc](https://github.com/rozniak/xfce-winxp-tc).
- **Programs**: All programs that haven't been recreated by rozniak will be included and run with Wine, and they will automatically appear in the Start menu as .desktop files.

## Installation Process

The installation process is designed to mimic the classic Windows XP setup experience:

1. **Boot from Installation Media**:
   - Insert the installation media and initiate the process.

2. **Text-Based Interface**:
   - You will be presented with two options: 
     1. Install Windows XP
     2. Repair an existing installation (***maybe***, *I don't know what I'd put here since Repair an existing installation isn't really feasible*)
     3. Quit setup
   - To install Windows XP, press Enter. You will then see an agreement that you must accept to continue.
   - Create or select a partition and choose a file system (ext4 or FAT32, etc.).
   - The hard disk will be checked for errors and space requirements, then Windows XP will be installed.

3. **Graphical Phase**:
   - After the text-based setup is finished, the computer will reboot and start the graphical phase of the setup from the hard disk.
   - Continue copying files.
   - Set up the initial configuration, including setting up user accounts and configuring the network.

4. **Out-Of-Box Experience (OOBE)**:
   - After installation, the OOBE will guide you through the initial configuration and customizing settings.

## Current Status

This repository is currently a placeholder. Development work has not yet started. The project aims to create a faithful recreation of the Windows XP experience using Debian.

## Credits

- [xfce-winxp-tc](https://github.com/rozniak/xfce-winxp-tc) by Rory Fewell [(rozniak)](https://github.com/rozniak): Windows XP Total Conversion for XFCE.

## License

MIT
