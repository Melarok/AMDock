# AMDock: **A***ssisted* **M***olecular* **Dock***ing with Autodock4 and Autodock Vina*
AMDock (Assisted Molecular Docking) is a user-friendly graphical tool to assist in the docking of protein-ligand 
complexes using Autodock-Vina or AutoDock4. This tool integrates several external programs for processing docking input 
files, define the search space (box) and perform docking under user’s supervision.

**Version 1.5.x for Linux** (**Build 1.5.0**)

**DOCUMENTATION**

Manual, tutorials and test files are located in **Doc** folder. (May be out of date. Please check the wiki)

**Cite us**

Valdes-Tresanco, M.S., Valdes-Tresanco, M.E., Valiente, P.A. and Moreno E. AMDock: a versatile graphical tool for
 assisting molecular docking with Autodock Vina and Autodock4. Biol Direct 15, 12 (2020). https://doi.org/10.1186/s13062-020-00267-2
 
 <a href="https://www.scimagojr.com/journalsearch.php?q=5800173376&amp;tip=sid&amp;exact=no" title="SCImago Journal &amp; Country Rank"><img border="0" src="https://www.scimagojr.com/journal_img.php?id=5800173376" alt="SCImago Journal &amp; Country Rank"  /></a>

**INSTALL**

-unzip the *.zip file<br>
-execute `./install.sh` and follow instructions

*If `./install.sh` is not running, change the execution permissions. To do this press 
`right click > permissions > Allow execute this file as a program`*


Before installation, verify that you have PyMOL, PyQt4 and numpy as python
  modules, if not, execute in a terminal<br> 
  `sudo apt install pymol python-qt4 python-numpy openbabel`

Before using the program, check that PyMOL has the AMDock plugin in taskbar.<br>
If it does not appear please follow the instructions:<br>
-open PyMOL > Plugins > Manager Plugins > Settings > Add new directory<br>
PyMOL should automatically have:

`~/.pymol/startup or /home/user_name/.pymol/startup` if not, please select the previous address<br>

after this you must restart PyMol

***Automatically, a file (AMDock.desktop) must be generated that allows its execution from the start menu. If you use
 a linux version where it doesn't appear, you can run it through the terminal:
`installation folder> right click> run a terminal here> (in terminal) ./AMDock.sh`***

**UNINSTALL**

Just search the installation directory and execute `./uninstall.sh` in a terminal and follow instructions

To view the update history, please check Changes_History file

**TUTORIALS**

Please, check the wiki https://github.com/Valdes-Tresanco-MS/AMDock-win/wiki

[<img src="./AMDock/AMDock/images/jetbrains-variant-4.png" height="100" align="right" />](https://www.jetbrains.com/?from=https://github.com/Valdes-Tresanco-MS/AMDock)

## Support
This project is possible thanks to the Open Source license of the 
[JetBrains](https://www.jetbrains.com/?from=https://github.com/Valdes-Tresanco-MS/AMDock
) programs.
