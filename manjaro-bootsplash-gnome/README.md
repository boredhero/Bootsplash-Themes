# Manjaro-bootsplash-gnome
Kernel Bootsplash theme for manjaro Linux using gnome linux logo

> learn more about in kernel bootsplash [here](https://lists.freedesktop.org/archives/dri-devel/2017-December/160242.html)

# Installation:

- run `bootsplash-manjaro-gnome.sh` to generate STL model.
- run `makepkg` to create Arch package and install it with `pacman -U $package_name`
- append `bootsplash-manjaro-gnome` hook in the end of HOOKS string of `/etc/mkinitcpio.conf`
- add `quiet bootsplash.bootfile=bootsplash-themes/manjaro-gnome/bootsplash` into `GRUB_CMDLINE_LINUX` string in `/etc/default/grub`
- run `sudo mkinitcpio -p linux415` (or linux416)
- run `sudo update-grub`