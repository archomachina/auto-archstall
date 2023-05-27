

This script, created by (@archomachina), automates the installation and configuration process for Arch Linux with the Btrfs file system. It is designed to streamline the setup of an Arch Linux system with essential packages and optimizations.

The script performs the following tasks:
- Checks if the system is running in UEFI mode and prompts the user to boot into UEFI mode if necessary.
- Sets up the Btrfs file system by creating a new partition, formatting it, and configuring the necessary settings.
- Enables zram for improved memory compression and sets the size to half of the available RAM.
- Installs the microcode for the CPU (intel-ucode) and the GPU driver (NVIDIA in this case).
- Installs systemd-boot as the boot manager and sets up the boot entry for Arch Linux.
- Installs additional packages based on user input, including popular applications and utilities.
- Configures Flatpak and adds the Flathub repository for easy installation of flatpak packages.
- Configures the locale settings and updates the system mirrors for optimal speed.
- Installs the Linux-Btrfs kernel and performs a system update.
- Reboots the system to apply the changes.

This script serves as a convenient tool for automating the initial setup of an Arch Linux system with the Btrfs file system, saving time and effort during the installation process.

Feel free to use and modify this script to suit your needs. Happy Arch Linux installation!
