# BrawlCSS
Reimplementation of the Super Smash Bros. Brawl character select screen.

The repository will compile a .rel for the game to be loaded for vanilla Brawl.

WARNING: The code compiled is not a 1:1 recreation of Brawl's code and will have some alterations well needed, this making existing character select screen codes not function as originally intended.

# Planned features
Will be revealed soon.

Source readme.md down below

# BrawlModule
Experimental C++ reimplementation of Super Smash Bros. Brawl module (.rel) files.

This project is primarily aimed at **functional reimplementations** of the modules, not 1:1 binary matches. While some of the files built by this repo may be 1:1 binary matches, that is not the goal or a priority for this project. 

## Requirements ##
 - Git LFS
   - `git lfs install` on windows
 - DevkitPro
 - `devkitPro/msys2/usr/bin` in your system path (optional)
   - lets you run make from CLI instead of an MSYS2 window
 
## Building ##
 - In a CLI window, run the command: `git clone --recursive https://github.com/Sammi-Husky/BrawlModules.git`
 - Run `cd BrawlModules`
 - Run `make`
