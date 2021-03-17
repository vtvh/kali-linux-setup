# linux-setup-colemak
Steps to create Linux development environment with Colemake layout

## setup ssh key
ssh-keygen -t rsa -b 4096
### copy generated key to github https://github.com/settings/keys

## run this script
```sh
sudo apt install snapd
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

