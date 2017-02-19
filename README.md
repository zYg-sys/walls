# Walls Cave Survey software

RIP David McKenzie

## Looking for developers!

I (Andy Edwards) have volunteered to help maintain Walls, but I am by no means a C++ or Visual Studio expert, let alone
familiar with the MFC and probably a number of other old libraries it uses.  If you're a caver and C++ developer, please
let me know if you'd be willing to help, even if you only have time to give me tips whenever I hit a snag.

## Quick Start for Developers

* Install the latest version of [Visual Studio](https://www.visualstudio.com/downloads/) (community edition is fine)
* Install the [`nasm` assembler](http://www.nasm.us/) and make sure it's on your `PATH` 
* Install the latest [Windows SDK](https://developer.microsoft.com/en-us/windows/downloads/windows-10-sdk)
* Install the [OpenGL extension headers](https://www.khronos.org/registry/khronos_headers.zip).  These go in the same
directory as gl.h, which is something like `C:\Program Files (x86)\Windows Kits\8.1\Include\um\gl` (depending on the
Windows SDK version)
* Open `Walls.sln`
* Select a build configuration: `Debug_XP` if you're on Windows XP, or `Debug` otherwise.
* Cross your fingers
* Hit F7 to build the solution
* Run the project!
