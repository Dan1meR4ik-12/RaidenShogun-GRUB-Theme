# RaidenShogun GRUB Theme

![screenshot](https://github.com/user-attachments/assets/7292d348-3c21-415c-afd2-e9ab2a942299)

## Theme Description
Raiden Shogun from Genshin Impact GRUB theme. Here is EN and RU version also for Ventoy and .psd file for your own customization.

## Installation
1. Download & Unzip

2. Copy `RaidenShogun_en` (or another folder) into grub themes directory
```shell
sudo cp -r RaidenShogun_en /usr/share/grub/themes/
```

3. Edit `/etc/default/grub`:
Add the theme to the bottom of the text file
```shell
GRUB_THEME="/usr/share/grub/themes/RaidenShogun_en/theme.txt"
```

4. Update grub
```shell
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

5. Reboot the computer
