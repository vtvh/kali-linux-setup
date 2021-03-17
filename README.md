# linux-setup-colemak-kali
Steps by steps to create Linux development environment with Colemak keyboard layout on Kali Linux

## setup keyboard (colemak)
```
setxkbmap us -variant colemak
setxkbmap -option ctrl:nocaps
```

## install snap
https://snapcraft.io/docs/installing-snap-on-kali

## setup ssh key
`ssh-keygen -t rsa -b 4096`
_copy generated key to github https://github.com/settings/keys_

## run this script
```sh
sudo apt install snapd
sudo snap install chromium
sudo snap install code --classic
mkdir ~/_workspace && cd ~/_workspace
#git clone https://github.com/vtvh/linux-setup-colemak
#git clone https://github.com/vtvh/mysettings
git clone git@github.com:vtvh/mysettings.git
git clone git@github.com:vtvh/linux-setup-colemak


```

## Add Colemak keyboard

setxkbmap us -variant colemak

## Change Capslock to Left Control

setxkbmap -option ctrl:nocaps

## Config Alt+H,N,E,I to be Left Down Up Right Arrows

## Config Alt+O to be Delete word



## Install fonts

## Install brew

## Install zsh and ohmyzsh

## Merge zsh sensible config

