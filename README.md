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

dbox is a universal package manager interface that works inside Distrobox containers.
It allows you to manage packages across multiple distributions — such as those using apt, dnf, pacman, yay, apk, zypper, xbps, and more — using a single, unified command syntax.
🔍 Why not just use Distrobox?

Distrobox lets you run full Linux distributions in containers.
However, to manage packages in those containers, you must:

    Manually enter each container

    Know which package manager to use

    Type the appropriate command

    Exit again

Example:

distrobox-enter arch
yay -S firefox
exit

This gets repetitive and inefficient — especially when working with multiple containers or scripting.
🚀 What does dbox do?

dbox automates and simplifies package management inside Distrobox containers:

    ✅ Automatically starts (or creates) the correct container

    ✅ Uses a clean, unified syntax:

    dbox apt install firefox
    dbox pacman -S vlc
    dbox yay -Rns gimp

    ✅ Only runs inside Distrobox containers

    ✅ Automates install/remove/update commands

    ✅ Greatly simplifies multi-distro workflows

🤝 Summary

    🧠 Distrobox gives you isolated containers
    ⚙️ dbox makes package management inside them easy and universal

Perfect for developers, power users, and sysadmins who work across many Linux distributions.
✅ Supported Package Managers

- apt  
- apt-get  
- apk  
- dnf  
- pacman  
- yay  
- zypper  
- xbps

🖥️ Recommended Desktop Environments

To enable shortcut and desktop integration features, use a DE that supports .desktop files:

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

To initialize containers and enable desktop shortcut support:

dbox init




```
