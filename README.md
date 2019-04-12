# JK2SourceCode
Full Source Code of Jedi Knight II ready to use (1.02, 1.03 and 1.04 versions)

# Features
* JK2 1.02, 1.03 and 1.04 version projects
* Main Compilers (`cpp.exe`, `lcc.exe`, `q3asm.exe`, `rcc.exe`)
* Configured Batch Compilers (`game.bat`, `cgame.bat`, `ui.bat`)

# Notes
This first upload only aim to get the main game-code QVM's ready to use.
* Server Side `jk2mpgame.qvm`
* Client Side `cgame.qvm`
* User Interface `ui.qvm`

# Instructions
To get the main QVM's for each version, you just need to join to a jk2 version folder and choose what you want to compile, For example: to compile the server-side part, enter to the `game` folder and run `game.bat`, then read the console output, if everything is ok you should see something like `writing to jk2mpgame.qvm`. After that, back to the `base` folder and QVM's will store in the `vm` folder. 

# Requirements
* Windows XP SP2 or higher
* Visual Studio C++ 2008 or higher

# Notes
This repository aims to make mods for JK2 with unmodified base, if you want to compile binaries you should use **Visual C++ 6.0**. I also tell you there are a current project called [JK2MV](https://github.com/mvdevs/jk2mv) _(engine code)_ and [MVSDK](https://github.com/mvdevs/mvsdk) _(game code)_ which supports all three game versions and comes with various features and optimizations.

# Legal
The initial release for the game-code was released in 2002 in the `JK2 Editing Tools`. These tools are released "as is" and are unsupported by Raven Software, Activision or LucasArts.

The full release was in 2013 and can be found on SourceForge, posted by James Monroe and Rich Whitehouse. Thanks to Raven Software for making this available to us.

> GNU GENERAL PUBLIC LICENSE
> Version 2, June 1991
> 
> Copyright (C) 1989, 1991 Free Software Foundation, Inc.,
> 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA
> Everyone is permitted to copy and distribute verbatim copies
> of this license document, but changing it is not allowed.
