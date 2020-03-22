# Manjaro-bootsplash-freedomgateway
Kernel Bootsplash theme for manjaro Linux using the Freedom Gateway LLC Logo

# Installation:

- `git clone https://github.com/boredhero/Bootsplash-Themes.git`
- `cd manjaro-bootsplash-freedomgateway`
- run `bootsplash-manjaro-freedomgateway.sh` to generate STL model.
- run `makepkg` to create Arch package and install it with `pacman -U $package_name`
- append `bootsplash-manjaro-freedomgateway` hook in the end of HOOKS string of `/etc/mkinitcpio.conf`
- add `quiet bootsplash.bootfile=bootsplash-themes/manjaro-freedomgateway/bootsplash` into `GRUB_CMDLINE_LINUX` string in `/etc/default/grub`
- run `sudo mkinitcpio -p linux415` (or linux416) (or current kernel version)
- run `sudo update-grub`
