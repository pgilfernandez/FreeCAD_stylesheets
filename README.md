About
-------
version 2.04

QT themes (stylesheet) specially developed for **FreeCAD** (http://www.freecadweb.org/).
They might work with other software that uses QT styling.

Dark style example:
![Dark-Blue stylesheet](/../multimedia/img/stylesheet_dark-blue.png?raw=true "Dark-Blue stylesheet")

Light style example:
![Dark-Blue stylesheet](/../multimedia/img/stylesheet_light-blue.png?raw=true "Dark-Blue stylesheet")

Installation
------
1. Place the .qss files and /images/ folder in the path that fits your OS:
  - **OSX** = /Users/[YOUR_USER_NAME]/Library/Preferences/FreeCAD/Gui/Stylesheets/
  - **WINDOWS** = C:/[INSTALLATION_PATH]/FreeCAD/data/Gui/Stylesheets/
  - **LINUX** = /home/[YOUR_USER_NAME]/.FreeCAD/Gui/Stylesheets/
2. In order to display correctly images that are used inside the stylesheet:
    1. **FreeCAD 0.16** (development builds newer than commit 5b3d50a): that's it, you are done!
    2. **FreeCAD 0.15**: Images used in the theme need full paths to be found by FreeCAD, so you should search the string **qss:images** and replace with the real path of your computer. It should be done with all the .qss files you want to install-use
        - **find** = qss:images
        - **replace** = /Users/myName/Library/Preferences/FreeCAD/Gui/Stylesheets/images

Caveats
------
- **FreeCAD 0.15**
    * full paths to images are needed, that means all these .qss files should be edited per user
    * the "Task panel" is not stylable

Known bugs and TO DOs
------
Please, follow the [link to get updated information](http://forum.freecadweb.org/viewtopic.php?f=10&t=12417&p=99676)

License
------
Copyright (c) 2016 Pablo Gil Fernández.

![Attribution-ShareAlike 4.0 International](http://i.creativecommons.org/l/by-sa/3.0/88x31.png)
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
