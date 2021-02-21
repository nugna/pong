# Pong
A simple Pong game written in C++ with SFML.

## Requirements
- C++14
- SFML (x32 version)

## Install Game
- Open Terminal and change the current working directory to the location where you want the cloned directory to be made.
- Download the repository using the [instruction](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).
- To compile and run it requires [SFML](https://www.sfml-dev.org/) already installed.
Steps can be found [here](https://www.sfml-dev.org/tutorials/2.5/#getting-started).

### How to build in Visual Studio

After opening the project, go to **"Project -> Properties..."**:
- Select **"All configurations"** in **"Configuration"** section;
- In **"C/C++ -> General -> Additional include directories"** section append the "include" directory of SFML library;
- In **"Linker -> General -> Additional library directories"** section append the "lib" directory of SFML library;
- Select **Debug** in **Configuration** section;
- At the beginning of the **"Linker -> Input -> Additional dependencies"** section append the string:
```bash
sfml-graphics-d.lib;sfml-window-d.lib;sfml-system-d.lib;sfml-network-d.lib;sfml-audio-d.lib;
```
