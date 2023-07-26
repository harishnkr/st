# st - simple terminal
st is a simple terminal emulator for X which sucks less.

Personal fork of ST

## Patches applied
- Xresources customization
- Mousewheel only scroll
- CSI support
- Blinking cursor
- Bold text is not the brighter colour variant
- Changed backspace and delete key
- Glyph wide support
- Ligature Support
- Undercurl
- Font2 

## TODO

The following problems cannot be satisfied in the current terminal but I personally find it to be a deal breaker with respect to a terminal emulator:

- Vertical glyph problems (maybe its because of not applying the boxdraw patch.)
- Utilising 2 types of font on the same screen for different styles
- Strikethrough support

 I would love to fix these problems in the near future hence this terminal will be utilised only as a fallback tool.

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

