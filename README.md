# JK2 Source Code
Full Source Code of Jedi Knight II: Jedi Outcast ready to use (1.02, 1.03 and 1.04 versions)

# Features
* JK2 1.02, 1.03 and 1.04 version projects (Singleplayer and Multiplayer)
* Main Compilers Binaries (`cpp.exe`, `lcc.exe`, `q3asm.exe`, `rcc.exe`)
* Configured Batch Scripts for MP (`game.bat`, `cgame.bat`, `ui.bat`, `buildvms.bat`)

# Notes for Multiplayer
This upload is mainly intended to provide the game-code QVMs ready to use.
* Server Side `jk2mpgame.qvm`
* Client Side `cgame.qvm`
* User Interface `ui.qvm`

To get them you just need to open version folder you want and choose the desired module. Example: to compile the server-side part, enter to the `game` folder and run `game.bat`, then read the console output for success or errors, if everything is ok you should see something like `writing to jk2mpgame.qvm`. After that, back to the `base` folder and the QVM file will store in the `vm` folder. If you want build all QVM modules just run `buildvms.bat` from CODE-mp folder.

# Requirements
* Windows XP SP2 or higher
* Visual Studio C++ 2008 or higher

_For newer Visual Studio versions you must open the `.dsw` file and use the convertion tool to get the `.sln` project file._

# Notes
This repository aims to make mods for JK2 Multiplayer with unmodified code-base, if you want to compile binaries (.exe, .dll, etc...) you should use **Visual C++ 6.0** from back in the days. For upgraded and safe & stable code-base is highly recommended to use the community project [JK2MV](https://github.com/mvdevs/jk2mv) _(engine code)_ and [MVSDK](https://github.com/mvdevs/mvsdk) _(game code)_ which supports all three game versions and comes with various features and optimizations.

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
