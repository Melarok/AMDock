[![pypi](https://img.shields.io/pypi/v/AMDock)](https://pypi.org/project/AMDock/)
[![support](https://img.shields.io/badge/support-JetBrains-brightgreen)](https://www.jetbrains.com/?from=gmx_MMPBSA)
[![python](https://img.shields.io/badge/python-v3.x-blue)]()
[![DOI](https://img.shields.io/badge/DOI-10.1186%2Fs13062--020--00267--2-blue)](https://doi.org/10.1186/s13062-020-00267-2)
# AMDock: **A***ssisted* **M***olecular* **Dock***ing with Autodock4 and Autodock Vina*
AMDock (Assisted Molecular Docking) is a user-friendly graphical tool to assist in the docking of protein-ligand 
complexes using Autodock-Vina or AutoDock4. This tool integrates several external programs for processing docking input 
files, define the search space (box) and perform docking under user’s supervision.

## Installation

Create a new conda environment for AMDock and install the required dependencies:

    conda create --name AMDock -c conda-forge -c bioconda python=3.9.\* pymol-open-source openbabel pdb2pqr
    conda activate AMDock
    pip install git+https://github.com/Valdes-Tresanco-MS/AutoDockTools_py3 PyQt5

If you want to install AMDock directly from this repo run:

    pip install git+https://github.com/Melarok/AMDock.git

If you want to make changes to AMDock first clone this repo:
    
    git clone https://github.com/Melarok/AMDock.git

After you've made your changes, run the following command from inside the repo to install AMDock:

    pip install -e .

Before using AMDock, you most install the PyMOL plugin (grid_amdock.py).
If it is not installed automatically follow the instructions:
- Download the grid_amdock.py file from this repo
- Open PyMOL > Plugins > Manager Plugins > Install New Plugin > Choose File and select the grid_amdock.py file
- Restart PyMOL

To open AMDock, type in the terminal:

    AMDock

## Documentation & tutorials

Manual, tutorials and test files are located in the **Doc** folder.
They may be out of date. Please check the wiki https://github.com/Valdes-Tresanco-MS/AMDock-win/wiki

## Cite us

Valdes-Tresanco, M.S., Valdes-Tresanco, M.E., Valiente, P.A. and Moreno E. AMDock: a versatile graphical tool for
assisting molecular docking with Autodock Vina and Autodock4. Biol Direct 15, 12 (2020). https://doi.org/10.1186/s13062-020-00267-2
 
<a href="https://www.scimagojr.com/journalsearch.php?q=5800173376&amp;tip=sid&amp;exact=no" title="SCImago Journal &amp; Country Rank"><img border="0" src="https://www.scimagojr.com/journal_img.php?id=5800173376" alt="SCImago Journal &amp; Country Rank"/></a>

## Support
[<img src="./AMDock/data/jetbrains-variant-4.png" height="100" align="right" />](https://www.jetbrains.com/?from=https://github.com/Valdes-Tresanco-MS/AMDock)
This project is possible thanks to the Open Source license of the 
[JetBrains](https://www.jetbrains.com/?from=https://github.com/Valdes-Tresanco-MS/AMDock) programs.
