# Kali Nethunter for Magisk

This module allows you to install the Kali Nethunter chroot systemlessly - see https://github.com/offensive-security/kali-nethunter for further information about kali Nethunter
![Kali NetHunter](https://raw.githubusercontent.com/offensive-security/kali-nethunter/master/images/nethunter-git-logo.png)

## Instructions:
* Install this Magisk Module
* Run Nethunter app - allow 7(!) Root-related permissions prompts
* Click "Kali Chroot Manager"
* Click "Install Kali Chroot"
* Install the full Kali package
* Reboot
* Load Nethunter and allow initialisation
* Enjoy! Kali Terminal/Nethunter services should now work

## Not Working:
* Wi-Fi injection (requires custom kernel/ramdisk)
* HID Interfaces (BadUSB/Duckhunter etc. - also requires custom kernel/ramdisk)

## Uninstall
* Load "Kali Chroot Manager" and click "Remove Chroot" (Reboot and Remove Chroot)
* Uninstall Kali Nethunter Magisk module (Reboot)
* Manually uninstall Nethunter, Kali Terminal and Kali VNC apps

## Note
This is an unofficial build. Credits to all the Offensive Security guys and those working on the Nethunter project.
