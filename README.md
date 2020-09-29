<p align="center"><img src="https://raw.githubusercontent.com/freedomgateway/fg_branding/master/fg_logo_gold.jpg" alt="drawing" width="300"/></p>

# <p align="center"><b>legacy_fg_bootsplash_theme</b></p>
<p align="center"><b><i>Legacy Kernel Bootsplash theme for Manjaro Linux using the Old Freedom Gateway LLC Logo</i></b></p>
<p align="center"><b><i>This was made for the old Pine64 and Pine64 Pro boards but probably could be re-used on the new ones too!</i></b></p>

---

# Freedom Gateway Bootsplash Theme

# Installation:

- `git clone https://github.com/boredhero/Bootsplash-Themes.git`
- `cd manjaro-bootsplash-freedomgateway`
- run `bootsplash-manjaro-freedomgateway.sh` to generate STL model.
- run `makepkg` to create Arch package and install it with `pacman -U $package_name`
- append `bootsplash-manjaro-freedomgateway` hook in the end of HOOKS string of `/etc/mkinitcpio.conf`
- add `quiet bootsplash.bootfile=bootsplash-themes/manjaro-freedomgateway/bootsplash` into `GRUB_CMDLINE_LINUX` string in `/etc/default/grub`
- run `sudo mkinitcpio -p linux415` (or linux416) (or current kernel version)
- run `sudo update-grub`

## Forked from haipengyu1013/Bootsplash-Themes

> bootsplash themes for the linux kernel 4.14+, based on manjaro team's template

> learn more about in kernel bootsplash [here](https://lists.freedesktop.org/archives/dri-devel/2017-December/160242.html)

## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FBlacksuan19%2FBootsplash-Themes.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FBlacksuan19%2FBootsplash-Themes?ref=badge_large)
