# Atom-1.43.0-x64
My works related to Atom text editor version 1.43.0 for machine x64

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [Atom shortcuts.](#shortcuts)
4. [Open file using `atom` command in Command Prompt.](#atom)
5. [GitHub notes.](#github)
6. [GitHub repository calculation.](#calculation)

<a name="introduction"></a>
## 1. Introduction.
<img src="atom.jpg" height="200"> 
Atom is a free and open-source text and source code editor for macOS, Linux, and Microsoft Windows with support for plug-ins written in Node.js, and embedded Git Control, developed by GitHub. Atom is a desktop application built using web technologies. Most of the extending packages have free software licenses and are community-built and maintained. Atom is based on Electron (formerly known as Atom Shell), a framework that enables cross-platform desktop applications using Chromium and Node.js. It is written in CoffeeScript and Less.

<a name="references"></a>
## 2. Official references websites.
Official Atom website : https://atom.io <br />
Official Atom packages : https://atom.io/packages <br />
Official Insomnia documentation : https://support.insomnia.rest <br />

Stack Overflow question and answer site : https://stackoverflow.com <br />

**_Atom packages_** <br />
File Icons : https://atom.io/packages/file-icons <br />
PlatformIO IDE Terminal : https://atom.io/packages/platformio-ide-terminal <br />

**_Atom questions and answers by Stack overflow_** <br />
How to open the terminal in Atom? : https://stackoverflow.com/questions/43013195/how-to-open-the-terminal-in-atom <br />
How to open atom using a “atom .” command in terminal? : https://stackoverflow.com/questions/37312828/how-to-open-atom-using-a-atom-command-in-terminal <br />

<a name="shortcuts"></a>
## 3. Atom shortcuts.

**_Folder management_** <br />
**[ Ctrl ]** + **[ Shift ]** + **[ O ]** : open folder from the local machine  <br />

**_File management_** <br />
**[ A ]** : adding new file
**[ Backspace ]** : delete file
**[ Fn ]** + **[ F2 ]** : rename file

**_Settings management_** <br />
**[ Ctrl ]** + **[ , ]** : open Settings menu <br />

**_Terminal management_** <br />
**[ Ctrl ]** + **[ \` ]** : open terminal in Atom after installed terminal package called `platformio-ide-terminal` <br />
**[ Ctrl ]** + **[ Shift ]** + **[ P ]** : open command palette

**_Atom runner management (package)_** <br />
**[ Alt ]** + **[ R ]** : launch the runner for the active window
**[ Shift ]** + **[ Alt ]** + **[ R ]** : run the currently selected text in the active window
**[ Ctrl ]** + **[ Shift ]** + **[ C ]** : kill a currently running process
**[ Esc ]** : close the runner window

<a name="atom"></a>
## 4. Open file using `atom` command in Command Prompt.

If there is an error saying that `atom is not recognized as an internal or external command` after typing `atom` in the Command Prompt. First press **[ ⊞ ]** + **[ R ]** on your keyboard, then type `SystemPropertiesAdvanced.exe` and press **[ Enter ]** on your keyboard, the `System Properties` will then appear on your monitor screen, then press **[ N ]** on your keyboard, hover your mouse to the text `Path` under User variables for your local machine username, press **[ Tab ]**, then press **[ E ]**, then press **[ Tab ]**, and then press **[ N ]**, then type in the location of your atom bin folder, in this case, `C:\Users\username\AppData\Local\atom\bin` and press **[ Enter ]** and press **[ Enter ]** again to exit from `Edit environment variable` menu, then hover your mouse to the `OK` button on the `Environment Variables` interface and **[ Mouse Right Click ]** on it, then hover your mouse to the `OK` button on the `System Properties` interface and **[ Mouse Right Click ]** on it. You now can use the `atom` command on your Command Prompt to open any file you wish to work with.

<a name="github"></a>
## 5. GitHub notes.
Clone the current GitHub remote repository contents into local machine.
```
$ git clone https://github.com/syakirharis25/Atom-1.43.0-x64.git
$ cd Atom-1.43.0-x64/
$ git remote -v
$ git status
```

<a name="calculation"></a>
## 6. GitHub repository calculation.
```
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Markdown                         1              9              0             33
-------------------------------------------------------------------------------
```
Refer to : https://github.com/syakirharis25/cloc
