# Lain-Theme
# 🌐 Wired - Lain Themed Cyberpunk Conky Setup (Dotfile)

Welcome to the Wired. This repository contains my personal Conky configuration file inspired by the anime **Serial Experiments Lain**. It features a custom system monitor panel with a Braille ASCII art portrait of Lain and clean system stats. 

While designed primarily with the **XFCE Desktop Environment** in mind, this configuration can be used on any Linux distribution or desktop environment supporting Conky.

> *"No matter where you are, everyone is always connected."*

---


## 📂 Repository Structure
- `lain_wid-eng.conf`: The main configuration file for the custom system monitor panel on the left.

---

## 🚀 Installation & Setup

1. Install Conky on your system using your package manager. For example, on Debian/Ubuntu-based systems:

    sudo apt install conky-all

2. Create the configuration directory in your home folder if it doesn't exist:

    mkdir -p ~/.config/conky/

3. Download and move the `lain_wid-eng.conf` file from this repository into `~/.config/conky/`.

4. Run Conky via terminal to test it, or add it to your system's **Startup Applications / Autostart** to launch it automatically on boot:

    conky -c ~/.config/conky/lain_wid-eng.conf

---

## 🌐 Connection
*"Let's all love Lain!"* If you find this configuration useful or cool, feel free to drop a ⭐ to this repository!
