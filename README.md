# Visual Studio Code PopClip Extension

# Introduction #

This extension will send selected text to Visual Studio Code as a new text file. 
It is created for [PopClip 2.](http://pilotmoon.com/popclip/)

## Extension Signing

PopClip will display a warning dialog when you install an extension not digitally signed by Pilotmoon Software.

![Example unsigned warning.](https://raw.github.com/pilotmoon/PopClip-Extensions/master/docs/ext_warning.png)

Please run the following command at the Terminal, then Quit and restart PopClip.
This will allow PopClip to install 3rd party extension.
Run :

    defaults write com.pilotmoon.popclip LoadUnsignedExtensions -bool YES

# How to use #

1.	Make sure you have [PopClip][2] installed.

1.	Run the command above and restart PopClip to make it work.

1.	Download the extention [here](https://github.com/fabburst/PopClip-Extensions/raw/master/VisualStudioCodeText.popclipextz)

1.	Double click the downloaded .popclipextz file to install.
-------------------------------

## Dev Resources

- https://github.com/pilotmoon/PopClip-Extensions

### Example Shell Script Extension:
- [https://github.com/pilotmoon/PopClip-Extensions/tree/master/source/Say
