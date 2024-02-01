# PI_PICO-EasySetup
This is a repo for those students who want to set up Raspberry Pi Pico development environment in VSCode.

## Installation Steps

1. **GNU ARM Embedded Toolchain**:
   - Link for download the [GNU ARM Embedded Toolchain (exe version)](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads).
   - tick 'Add path to environment variable'.

2. **CMake**:
   - Link for download [CMake (Windows x64 Installer version)](https://cmake.org/download/).
   - tick 'Add CMake to the system PATH for all users'.

3. **Visual Studio Build Tools**:
   - Link for download [Tools for Visual Studio download page](https://visualstudio.microsoft.com/downloads/).
   - Download 'Build Tools for Visual Studio 2022' by search it in the download search bar
   - tick 'C++ Build Tools' in your installation.

4. **Python**:
   - Link for download Python from the [Windows downloads page](https://www.python.org/downloads/windows/).
   - tick the option 'Add Python to PATH'.

5. **Git**:
   - Link for download [Git for Windows](https://git-scm.com/download/win).

6. **Raspberry Pi Pico Setup**:
   - Link for download [Pico Setup Windows x64 installer](https://www.raspberrypi.com/news/raspberry-pi-pico-windows-installer/).
     
7. **Check all your PATH is right**:
   **This is SUPER important**:
   - espacially find the path nmake.exe file in your computer, normally is C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Tools\MSVC\14.38.33130\bin\Hostx64\x64, if your computer is a 64bits based one.
   - open window settings and click system, slide down on your left and click "about", click advanced system settings, double click PATH and add the this PATH and confirm OK.


   

## After ALL these

- Type 'Pico - Visual Studio Code' in your windows search bar and open.it will configures the necessary environment variables before launching Visual Studio Code.

# Now you can try examples in the Raspberry Pi Pico folder!!!
