# Config
Important: the config files assume the user is called "jen"


These are my config files for my Arch window manager. I am using Xorg, i3 and i3blocks.

I can clone these files to setup a fresh install with the right configuration.


To get the server and i3 running you need

sudo pacman -S xorg-server xorg-xinit i3-gaps i3blocks


To get xorg to run when calling #startx

Copy .xinitrc    to ~/.xinitrc


To see anything you probably need to install some fonts

sudo pacman -S ttf-dejavu ttf-font-awesome noto-fonts


To hear anything you will need 

sudo pacman -S pulseaudio alsa-utils


To make the gtk theme nicer

sudo pacman -S arc-gtk-theme


My default stuff

sudo pacman -S rxvt-unicode feh dmenu


To use my configurations

Copy .Xresources to ~/.Xresources

Copy i3/         to ~/.config/i3/

Copy i3blocks/   to ~/.config/i3blocks/

Copy gtk-3.0/    to ~/.config/gtk-3.0/

Copy .gtkrc-2.0  to ~/.gtkrc-2.0


