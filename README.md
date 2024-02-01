# PI_PICO-EasySetup
This is a repo for those students who want to set up Raspberry Pi Pico development environment in VSCode.

## Installation Steps

# Setup Instructions

Follow these instructions to set up your development environment.

## Installation Steps

### 1.Python
- Download Python from the [Windows downloads page](https://www.python.org/downloads/windows/).
- Tick the 'Add Python to PATH' option during installation.

### 2.Git
- Download [Git for Windows](https://git-scm.com/download/win).

## Now you need to TICK!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

### 3.CMake
- Download [CMake (Windows x64 Installer version)](https://cmake.org/download/).
- Tick 'Add CMake to the system PATH for all users'.

### 4.Visual Studio Build Tools
- Navigate to the [Tools for Visual Studio download page](https://visualstudio.microsoft.com/downloads/).
- Use the search bar to find and download 'Build Tools for Visual Studio 2022'.
- Ensure 'C++ Build Tools' is included in your installation.

### 5.GNU ARM Embedded Toolchain
- Download the [GNU ARM Embedded Toolchain (exe version)](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads).
- Select the 'Add path to environment variable' option during the installation process.

### 6.Raspberry Pi Pico Setup (no need to tick):
   - Link for download [Pico Setup Windows x64 installer](https://www.raspberrypi.com/news/raspberry-pi-pico-windows-installer/).
     
### 7.Check all your PATH is right:
   **This is SUPER important**:
   - espacially find the path nmake.exe file in your computer, normally is C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Tools\MSVC\14.38.33130\bin\Hostx64\x64, if your computer is a 64bits based one.
   - open window settings and click system, slide down on your left and click "about", click advanced system settings, double click PATH and add the this PATH and confirm OK.

## After ALL these

- Type 'Pico - Visual Studio Code' in your windows search bar and open. It will configures the necessary environment variables before launching Visual Studio Code.

# Now you can try examples in the Raspberry Pi Pico folder!!!
