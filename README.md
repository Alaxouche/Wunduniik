![Logo](https://i.redd.it/1tfaz3eeas191.png)

# Wunduniik

A Skyrim SE Heavy Modlist Installer.

## Summary
- [Preamble](#preamble)
- [System Requirement & Necessary Tools](#system-requirement-and-necessary-tools)
  - [Pc Minimum And Recommanded Components](#pc-minimum-and-recommanded-components)
  - [Necessary And Useful Applications](#necessary-and-useful-applications)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
  - [Wabbajack Installation](#wabbajack-installation)
  - [Post-Installation](post-installation)
    - [Load Order Sorting](load-order-sorting)
    - [BethINI]
    - [ENB](enb)
- [Using The List](using-the-list)
  - [Starting The List](starting-the-list)
  - [Configuring MCM](configuring-mcm)
- [Updating The List]
- [Removing The List]
- [FAQ]
  - [Fix a Crash]
  - [Reporting an Issue]
  - [Wide and Ultrawide Screens Options]
  - [Performance Options]
    - [Tweaking/Swithing ENB]
    - [Ini Configuration]
    - [Mod Configuration]
- [Credits And Thanks]
- [Contact Me]

## Preamble

**This modlist is currently __ONLY__ for SE!!**

**This modlist is focused mostly on graphics and textures**

*"I decided to create this modlist because people kept asking how I got Skyrim to look so good. I know that when you begin, it can be hard to mod correctly and you can quickly be lost, but following this guide will help you build the Skyrim of your dreams! This very extended and detailed modlist will help you understand modding \minimizing bugs and conflicts to allow for a completely immersive gameplay experience. This is how I think the game is perfect, but if you think something could be better, the choice is yours. For each graphic mod I use 2K resolution, but you should install a range between 1K and 4K (8K sometimes, if your PC can handle it). I don't recommend installing less than 1K resolution textures."*

This modlist is an heavy +1200 mods list based on **my** personnal preferences. It improves almost everything from the vanilla game to make it looks more like a 2022 game than a 2011 game. Keep in ming that the list is more like a vanilla rework than a list adding new quests, new lands...
Wunduniik is a draconic word meaning "Traveler". I chose this one as I think that when you travel, you discover new cultures, architectures... things can look a lot different. I think this modlsit will provide you the same feeling, because you will almost discover a new game.

## System Requirement and Necessary Tools

### Pc Minimum And Recommanded Components

As Wunduniik is a modlist modlist based on graphics, you must have a good GPU.

Minimum Specs:
- CPU: I5 10th Gen or AMD Equivalent
- RAM: 16GB DDR4
- GPU: a 8GB GPU such as a GTX 1080, RTX 2070...
- Storage: a 500GB SSD is the best, but a HDD will do the work
- Screen: FHD Screen in 60Hz (keep in mind that having higher resolution will decrease performances so you must have a good pc)

In comparison here are my specs:
- CPU: I7-7700
- RAM: Corsair Vengeance 16GB DDR4
- GPU: GTX 1070 (Overcloaked)
- Storage: 500GB SSD
- Screen: FHD Screen in 60Hz

### Necessary And Useful Applications

For the modlist to work you must have some apps:
Please ensure you have .NET v5.0 or higher installed. Download the **desktop app installer and console app x64** from Microsoft here https://dotnet.microsoft.com/download/dotnet/5.0/runtime, and also [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe).

To help you with the INIs configuration, I highly recommand to have installed [Notepad ++](https://notepab-plus-plus.biz)

## Installation

### Pre-Installation

Before installing the modlist, here are some things you **must** do:
- Uninstall your game. Re-Install it in a custom folder outside C:\Progam Files... (for exemple i installed it in C:\Games) and also make sure it is installed in the     disk with more free space!
- Change Skyrim so it does not automatically update (Important!).
- Downgrade your game from v1.6.xxx to v1.5.97 using the [Unofficial Downgrade Patcher](https://www.nexusmods.com/skyrimspecialedition/mods/57618)
- Install Mod Organizer 2 in a custom location (but still in the disk with more free space!), such as C:\Modding

The next steps are optional **but** useful if you want to edit the list so if you want to skip, you can:

- Download the following applications:
  - [SSEEdit](https://www.nexusmods.com/skyrimspecialedition/mods/164)
  - [LOOT](https://www.nexusmods.com/skyrimspecialedition/mods/1918)
  - [BethINI](https://www.nexusmods.com/skyrimspecialedition/mods/4875)
  - [Wrye Bash](https://www.nexusmods.com/skyrimspecialedition/mods/6837)
  - [DynDOLOD 3.0](https://www.nexusmods.com/skyrimspecialedition/mods/68518)
  - [ZEdit](https://github.com/z-edit/zedit/releases)
  - [SSELODGen](https://www.nexusmods.com/skyrimspecialedition/mods/6642/)
  - [Synthesis](https://github.com/Mutagen-Modding/Synthesis/releases)
- Install them on the Modding file we just created. Your Modding folder should look like this now:

![image](https://i.redd.it/x6vy7rvu8u191.png)

### Wabbajack Installation

### Post Installation

#### Load Order Sorting

If needed (or if you added new mods with plugins), it's highly recommanded that you sort your modlist. To do so, launch Mod Organizer 2, and add as executable `LOOT.exe`. Now run LOOT to the executable list. To help you, I already made some configurations for a correct Load Order. Here is the [OOT Settings](https://drive.google.com/file/d/1-zJu53bN4NCCfUx9K3jNiD_4oXQYMCot/view?usp=sharing) I use. Extract its content in "Your Disk"\Users\"Your User Profile"\AppData\Local\LOOT\games\Skyrim Special Edition. (Tip: to get access to Appdata if you can't see it, in your files explorer, go to options, Display, and tick "display hidden files and folders").

#### ENB

Wunduniik was designed and set up to be used with [Rudy ENB for Cathedral Weathers - Zangdar Edit](https://www.nexusmods.com/skyrimspecialedition/mods/39113) last version, but you can change it if you don't like it.

Also to help you with the ENB management, I strongly advise you the [ENB Organizer](https://www.nexusmods.com/skyrim/mods/67077). It will allow you to prepare presets of ENBs you can easely switch as it will remember the files used and their configurations. Here is how you may use/set up it:

## Using The List

### Starting The List

Open `Mod Organizer.exe` and launch `SKSE` through the executables. As the modlist is quite big , depending on your pc, it may take some time to load the game. **THIS IS NORMAL DON'T PANIC!** Also I advise you to add Modding folder and Skyrim folder as exeptions in your Antivirus, it may cause some issues and even crashes.

### Configuring MCM

MCM have been configured thanks to [MCM Recorder](https://www.nexusmods.com/skyrimspecialedition/mods/61719). However if you don't like my settings, it's up top you to change them, but with the amount of MCM, it may take some time. Here is my configuration for (almost) all MCM:

