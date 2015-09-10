About
------
version 1.7a

QT themes (stylesheet) specially developed for **FreeCAD** (http://www.freecadweb.org/).
It might work with other software that uses QT styling.

Dark style example:
![Dark-Green stylesheet](/../multimedia/img/stylesheet_dark.png?raw=true "Dark-Green stylesheet")

Light style example:
![Dark-Green stylesheet](/../multimedia/img/stylesheet_light.png?raw=true "Dark-Green stylesheet")

Installation
------
1. Place the .qss files and /images/ folder in the path that fits your OS:
  - **OSX** = /Users/[YOUR_USER_NAME]/Library/Preferences/FreeCAD/Gui/Stylesheets/
  - **WINDOWS** = C:/[INSTALLATION_PATH]/FreeCAD/data/Gui/Stylesheets/
  - **LINUX** = /home/[YOUR_USER_NAME]/.FreeCAD/Gui/Stylesheets/
2. In order to display correctly images that are used inside the stylesheet:
    1. If you use **FreeCAD 0.16** (development builds newer than commit 5b3d50a): that's it, you are done!
    2. If you use **FreeCAD 0.15**: Images used in the theme need full paths to be found by FreeCAD, so you should search the string **qss:images** and replace with the real path of your computer. It should be done with all the .qss files you want to install-use
        - **find** = qss:images
        - **replace** = /Users/myName/Library/Preferences/FreeCAD/Gui/Stylesheets/images

Customization
------
If you would like to change the overall look/style of the theme, just find and replace the "palette colors" listed at the start of the file you want to edit:
- background darker
- background dark and slighly darker
- background dark
- background normal and slighly darker
- background normal
- background light
- background ligher
- lists background
- lists background (alternate)
- lists background selection
- foreground
- selection darker
- selection dark
- selection normal
- selection inbetween normal and light
- selection light
- selection lighter

Caveats
------
- **FreeCAD 0.15**
    * full paths to images are needed, that means all these .qss files should be edited per user
    * the "Task panel" is not stylable
- in app icons-buttons are designed in svg but are not stylable, that is, it's not possible to change them... I hope it also changes in the near future

Known bugs and To do
------
Please, follow the [link to get updated information](http://forum.freecadweb.org/viewtopic.php?f=10&t=12417&p=99676)

License
------
Copyright (c) 2015 Pablo Gil Fernández.
The stylesheet uses some code from Colin Duquesnoy generic QT stylesheet

![Attribution-ShareAlike 4.0 International](http://i.creativecommons.org/l/by-sa/3.0/88x31.png)
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
