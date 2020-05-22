# Config
These are my config files for my Arch window manager. I am using Xorg, i3 and i3blocks.
I can clone these files to setup a fresh install with the right configuration.

To get the server and i3 running you need
sudo pacman -S xorg-server xorg-xinit i3-gaps i3blocks

To see anything you probably need to install some fonts
sudo pacman -S ttf-dejavu ttf-font-awesome 

Copy .Xresources to ~/.Xresources

Copy i3/         to ~/.config/i3/

Copy i3blocks/   to ~/.config/i3blocks/

You will also need to install 
sudo pacman -S ttf-dejavu rxvt-unicode xorg-server xorg-xinit feh pulseaudio alsa-utils

