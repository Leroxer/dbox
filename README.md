```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║    ██████╗ ██████╗  ██████╗ ██╗  ██╗                         ║
║    ██╔══██╗██╔══██╗██╔═══██╗╚██╗██╔╝                         ║
║    ██║  ██║██████╔╝██║   ██║ ╚███╔╝                          ║
║    ██║  ██║██╔══██╗██║   ██║ ██╔██╗                          ║
║    ██████╔╝██████╔╝╚██████╔╝██╔╝ ██╗                         ║
║    ╚═════╝ ╚═════╝  ╚═════╝ ╚═╝  ╚═╝                         ║
║                                                              ║
║           Universal Linux Package Manager                    ║
║                         v0.1                                 ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝

📦 What is dbox?

dbox is a universal command-line interface (CLI) tool that runs on your host system's terminal and automates package management inside Distrobox containers.

It lets you manage packages across multiple Linux distributions (e.g. apt, pacman, yay, dnf, apk, zypper, xbps, etc.) using a single, unified command syntax — no need to manually enter each container.
🔍 Why not just use Distrobox directly?

With Distrobox, to install a package, you typically:

distrobox-enter arch
yay -S firefox
exit

That’s fine for one-off tasks, but inefficient for repeated use, scripts, or managing many containers.
🚀 What does dbox do?

With dbox, you can:

    ✅ Run all commands directly from your host terminal

    ✅ Automatically start (or create) the correct Distrobox container 🐳

    ✅ Use one unified syntax for different package managers 💻

    ✅ Save time by avoiding manual container entry and exit ⏱️

    ✅ Automate installs, removals, and updates inside containers ⚙️

Example usage:

dbox apt install firefox        # installs Firefox in the apt-based container
dbox pacman -S vlc             # installs VLC in the pacman-based container
dbox yay -Rns gimp             # removes GIMP via yay inside Arch-based container

🤝 Summary

    🧠 Distrobox gives you isolated Linux containers
    ⚙️ dbox makes package management in them fast, unified, and automatic — from the host terminal

Ideal for:

    Developers

    Linux power users

    System administrators

    Anyone using multiple distros via Distrobox

✅ Supported Package Managers

    apt

    apt-get

    apk

    dnf

    pacman

    yay

    zypper

    xbps

🖥️ Recommended Desktop Environments

To enable .desktop shortcut and menu integration, it's best to use:

    GNOME

    KDE Plasma

    XFCE

    LXQt

    MATE

    Cinnamon

    Budgie

⚙️ Installation

sudo curl -o /usr/local/bin/dbox https://raw.githubusercontent.com/Leroxer/dbox/main/dbox
sudo chmod +x /usr/local/bin/dbox

🔧 First-Time Setup

Initialize the system and create container presets:

dbox init


```
