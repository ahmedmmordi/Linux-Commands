# Most Common Commands for Linux

## System Updates and Package Management
- sudo apt update && sudo apt upgrade
- sudo dpkg -i PACKAGE_NAME
- dpkg --list
- sudo apt --fix-broken install
- sudo apt-get check
- sudo apt autoremove
- sudo apt clean
- sudo apt search PACKAGE_NAME
- sudo apt show PACKAGE_NAME
- sudo apt install PACKAGE_NAME
- sudo apt remove PACKAGE_NAME
- sudo snap list
- sudo snap install PACKAGE_NAME
- sudo snap remove PACKAGE_NAME

## Hardware Information
### General Hardware
- sudo lshw
- sudo lshw -short -c memory
- sudo lshw -C memory

### CPU Information
- lscpu
- cat /proc/cpuinfo

### RAM Information
- free -h
- sudo dmidecode --type memory
- sudo hwinfo --memory

### Disk Information
- df -h
- lsblk
- sudo fdisk -l

### GPU Information
- lspci | grep -i vga
- nvidia-smi
- sudo dmesg | grep nvidia

## System Logs
- sudo dmesg | grep -i error

## General System Utilities
- sudo hostnamectl set-hostname Ahmed
- where
- --version
- ls
- cd ..
- cd PATH
- mkdir
- touch
- rm
- rf
- whoami
- echo "Hello World.."
- history
- clear
- alias NAME='COMMAND'
- unalias NAME
- date
- who
- kill

# **Warning**
Always be cautious when executing commands in the terminal. Some commands can make significant changes to your system or files. Before using any command, ensure you understand its function and potential impact. Here are some tips:
> - **Research**: Look up what a command does and its options. Verify its purpose and any associated risks.
> - **Backup**: Ensure you have recent backups of important data before running commands that alter files or system settings.
> - **Review**: Double-check commands before execution, especially those that delete or modify files.
> - **Test**: If possible, test commands in a safe environment or with non-critical data to avoid unintended consequences.
>
> Use this guide as a reference, but always use discretion and seek additional information when in doubt.
