# My build of dwm.

The build of dwm I created for my [Arch](https://archlinux.org) install on my Thinkpad T480, this is my only linux based machine that I use outside my homelab.

## Patches

Patches I use, links to the exact version.

- [Full Gaps](https://dwm.suckless.org/patches/fullgaps/dwm-fullgaps-6.4.diff)

## Installation

.dotfiles can be found when I actually get round to making that repo.

Prequisits
```bash
sudo pacman -Syu xorg-server  xorg-xsetroot
```

Don't forget to chown! (change filepath if you have set it to another location
```bash
sudo chown -R $USER:$USER ~/suckless/dwm
```

Clone & Install
```bash
git clone https://github.com/Kitchvx/dwm.git ~/suckless/dwm
cd dwm
sudo make clean install
```


