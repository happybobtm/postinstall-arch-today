# Today

## About this script:
This is a post-install script made for arch linux, it install some packages and apply some configs

## Screenshots
### Script
![Script](https://i.imgur.com/6LoDFg1.png)
### Desktop
![Desktop](https://i.imgur.com/k3jk9lb.png)
### Terminal Emulator
![Terminal Emulator](https://i.imgur.com/UVCmcDL.png)
### Spotify
![Spotify](https://i.imgur.com/laf61zr.png)
### GTK
![GTK](https://i.imgur.com/9m3adLA.png)
### Grub
![Grub](https://i.imgur.com/7LUYwTn.gif)

## To use this script you need:
- Sudo
- Git
- Yay


## AMD users
```
nano ~/postinstall-arch-today/install-script.sh
```
#### Uncomment the 7 lines below "#AMD (Radeon)"!


## Runing the Script (Do not run as root)
```
cd ~
git clone https://github.com/happybobtm/postinstall-arch-today.git
sudo chmod u+x ~/postinstall-arch-today/install-script.sh
cd ~/postinstall-arch-today
./install-script.sh
```
## Apply Spotify
### Open your terminal and paste this:
```
spicetify backup apply
```
### Spotify
![Spotify](https://i.imgur.com/laf61zr.png)

## Apply Gtk, Icons and Cursor
### Lxappearance
![GTK](https://i.imgur.com/lDsP3lK.png)
![Icons](https://i.imgur.com/sZIsnfA.png)
![Cursor](https://i.imgur.com/IbxxtWw.png)