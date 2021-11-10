# proxmox-lxc-locale-fix
Fixing the Locale errors in Proxmox LXC´s

This is the Script to fix the Errors occuring while using Proxmox LXC's. 


Just execute this:

wget https://raw.githubusercontent.com/justusk18s/proxmox-lxc-locale-fix/main/fix-locale.sh && sudo bash fix-locale.sh

After executing the file, just reboot the container and the problem shouldn´t happen again.

If you don´t speak German, or don´t want German as your Container language, just chande every de_DE to your Country code in the UTF8 format.
