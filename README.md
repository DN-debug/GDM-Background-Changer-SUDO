
# GDM-Background-Changer-SUDO

Change your GDM background easily using GDM-Background-Changer. This version of GDM-Background-Changer or gbc uses SUDO for authentication. The user interaction is done
using Zenity.
## How to use?
Follow the steps below to use this changer on your system.
Note: This is only for Arch-based systems.

For Setup
```bash
  git clone https://github.com/DN-debug/GDM-Background-Changer-SUDO.git gcb-sudo
  cd gcb-sudo
  sudo ./install.sh
```
For Cleanup
```bash
  sudo rm -f /usr/local/bin/gdm-background-changer /usr/local/bin/frontend-gbc 
  sudo rm -r /usr/share/applications/gdm-background-changer.desktop
```
To test it, launch the Application-Menu and search for GDM-Background-Changer.
Launch and try it!

Note: If you would like to use the DOAS version of this script
then visit [GDM-Background-Changer-DOAS](https://github.com/DN-debug/GDM-Background-Changer-DOAS)
## Credits

- Major credit to Thiago Silva, as this is a shameless fork of his work - [change-gdm-background](https://github.com/thiggy01/change-gdm-background)


## Feedback & Contribution

If you have any feedback/suggestions/issues then
please create the respective PRs/issue-tickets. 

