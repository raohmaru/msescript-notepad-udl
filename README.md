# Magic Set Editor 2 syntax highlighting for Notepad++
Provides syntax highlight and automatic completion for Magic Set Editor 2 scripts, using Notepad++'s [User Defined Language](http://udl20.weebly.com/).

Since MSE2 scripts have no kwown extension, you need to set manually the language (through menu option "Language > MSE Script").

## Installation
1. Download UDL file [MSE_Script.xml](https://raw.githubusercontent.com/raohmaru/msescript-notepad-udl/master/MSE_Script.xml).
2. Open Notepad++.
3. Go to "Language > Define your language...".
4. Click on "Import..." button, browse to the location where MSE_Script.xml was saved and open it.
5. Restart Notepad++.

### Install Auto-completion File
1. Close Notepad++.
2. Download the auto-completion file [MSEScript.xml](https://raw.githubusercontent.com/raohmaru/msescript-notepad-udl/master/api/MSEScript.xml).
3. Move the downloaded file to the folder "autoCompletion" of the Notepad++ installation folder.
4. Open a MSE2 script file with Notepad++ and check if auto-completion is working by typing the name of a [built-in function](https://mseverse.miraheze.org/wiki/Dev:Script_functions_by_category).

### Usage
Open a MSE2 script file and enable the syntax highlight by selecting "Language > MSEScript".

## License
Released under The MIT License (MIT).
