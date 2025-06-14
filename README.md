# CelesteGRUB
GRUB theme I have designed centred around the game Celeste

To install the theme, download the tar.gz file attatched and then extract the directory contained within before running a 'cp -r' or 'mv' command to move it to your grub themes directory, usually located at /boot/grub/themes. For example 'sudo cp -r /home/user/Downloads/CelesteTheme /boot/grub/themes'

Then make sure to edit your /etc/default/grub file and add this to it 'GRUB_THEME="/boot/grub/themes/CelesteTheme/theme.txt"', after this run 'sudo mkconfig -o /boot/grub/grub.cfg' to install.

If you wish to change the background at any point you can do so through the theme.txt file located within the CelesteTheme directory.
