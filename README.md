#Introduction
This is my build of st terminal. It patched to be effective but not cumbersome. 

It supports opening/copying links using rofi and copying previous commands. You can zoom in/out using Alt+Shift+J/K, copy and paste with Alt+c/v.

# What is ST?
As described by suckless:

> st - simple terminal
> --------------------
> st is a simple terminal emulator for X which sucks less.
> 
> 
> Requirements
> ------------
> In order to build st you need the Xlib header files.
> 
> 
> Installation
> ------------
> Edit config.mk to match your local setup (st is installed into
> the /usr/local namespace by default).
> 
> Afterwards enter the following command to build and install st (if
> necessary as root):
> 
>     make clean install
> 
> 
> Running st
> ----------
> If you did not install st with make clean install, you must compile
> the st terminfo entry with the following command:
> 
>     tic -sx st.info
> 
> See the man page for additional details.
> 
> Credits
> -------
> Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.
> 

# Dependencies
* rofi [https://github.com/adi1090x/rofi](https://github.com/adi1090x/rofi)
* rofi-dmenu [https://aur.archlinux.org/packages/rofi-dmenu/](https://aur.archlinux.org/packages/rofi-dmenu/)
* xdotool
* xdg-utils

# Patches
* alpha
* GruvBox-Dark
* AnySize
* ScrollBack
* ExternalPipe

# Running st
You can either open another terminal and type `st&` or you can get an application launcher like [rofi](https://github.com/davatorium/rofi) or [dmenu](https://tools.suckless.org/dmenu/) to do that for you.
