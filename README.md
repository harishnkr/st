# st - simple terminal
st is a simple terminal emulator for X which sucks less.

Personal fork of ST

## Patches applied
- Xresources customization
- Mousewheel only scroll
- Ligatures support
- Delete key support
- CSI support
- Blinking cursor
- Fixed glyph truncation

## Requirements
In order to build st you need the Xlib header files.



## Installation
Edit config.mk to match your local setup 
st is installed into ~/.local in this fork

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install


## Running st
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

## Credits
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

