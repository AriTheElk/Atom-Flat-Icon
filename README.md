# Flat icon for Atom.io Editor
![Atom Icon](atom_light/atom_png/256x256.png)
![Atom Icon](atom_dark/atom_png/256x256.png)
![Atom Icon](atom_colored/atom_png/256x256.png)
 ![File Icon](file_png/256x256.png)

## ... why?
I can't be the only one turned off by the atrocious Atom.io icon that sat on my OS X dock alongside some of the beautiful icons of 10.10 (Yosemite). So I decided to try my hand at creating a suitable replacement icon that went along with the rest of my OS. Although it was originally made for Yosemite, it can be used on any OS as a nice replacement of the default green icon.

## Installation
### OS X
Open terminal and enter the below command for the desired icon
#### Light
    wget -O /Applications/Atom.app/Contents/Resources/atom.icns https://raw.github.com/iGARET/Atom-Flat-Icon/master/atom_light/atom.icns
#### Dark
    wget -O /Applications/Atom.app/Contents/Resources/atom.icns https://raw.github.com/iGARET/Atom-Flat-Icon/master/atom_dark/atom.icns
#### Colored
    wget -O /Applications/Atom.app/Contents/Resources/atom.icns https://raw.github.com/iGARET/Atom-Flat-Icon/master/atom_colored/atom.icns
#### File Icon
    wget -O /Applications/Atom.app/Contents/Resources/file.icns https://raw.github.com/iGARET/Atom-Flat-Icon/master/file.icns

If you do not have wget install, you can install it by running `brew install wget`. If you don't have brew installed, you really should.


### Windows
I don't use windows, because it doesn't fit with my UNIX-powered development workflow. But I found a [tutorial here](http://www.wikihow.com/Change-the-Icon-for-an-Exe-File) that looks like it works (albeit a longer solution than on Mac, but what do you expect from windows?)

### Linux
[Installing custom icons on Linux](http://askubuntu.com/a/80634)

## License
The Atom Flat Icon is released for free under the [CC BY-NC 4.0 license](http://creativecommons.org/licenses/by-nc/4.0/).

## Credits
- Icon created by @iGaret.
- The amazing [Atom](http://atom.io) editor!
