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
  - [Post-Installation](#post-installation)
    - [Load Order Sorting](#load-order-sorting)
    - [BethINI and INIs](#bethini-and-inis)
    - [ENB](#enb)
- [Using The List](#using-the-list)
  - [Starting The List](#starting-the-list)
  - [Configuring MCM](#configuring-mcm)
- [Updating The List](#updating-the-list)
- [Editing The List](#editing-the-list)
- [Removing The List](#removing-the-list)
- [FAQ](#faq)
  - [Fix a Crash](#fix-a-crash)
  - [Reporting an Issue](#reporting-an-issue)
  - [Wide and Ultrawide Screens Options](#wide-and-ultrawide-screens-options)
  - [Performance Options](#performance-options)
    - [Tweaking and Swithing ENB](#tweaking-and-switching-enb)
    - [INI Configuration](#ini-configuration)
    - [Mods Configuration](#mods-configuration)
- [Credits And Thanks](#credits-and-thanks)
- [Contact Me](#contact-me)

## Preamble

**This modlist is currently __ONLY__ for SE!!**

**This modlist is focused mostly on graphics and textures**

*"I decided to create this modlist because people kept asking how I got Skyrim to look so good. I know that when you begin, it can be hard to mod correctly and you can quickly be lost, but following this guide will help you build the Skyrim of your dreams! This very extended and detailed modlist will help you understand modding \minimizing bugs and conflicts to allow for a completely immersive gameplay experience. This is how I think the game is perfect, but if you think something could be better, the choice is yours. For each graphic mod I use 2K resolution, but you should install a range between 1K and 4K (8K sometimes, if your PC can handle it). I don't recommend installing less than 1K resolution textures."*

This modlist is an heavy +1200 mods list based on **my** personnal preferences. It improves almost everything from the vanilla game to make it looks more like a 2022 game than a 2011 game. Keep in ming that the list is more like a vanilla rework than a list adding new quests, new lands...
Wunduniik is a draconic word meaning "Traveler". I chose this one as I think that when you travel, you discover new cultures, architectures... things can look a lot different. I think this modlsit will provide you the same feeling, because you will almost discover a new game.

# Disclaimer

### YOU MUST READ THE INTEGRITY OF THIS README TO MAKE SURE THE LIST WILL WORK. IF YOU DON'T READ IT WON'T WORK. THE LIST WAS MADE TO TOTALLY CHANGE THE GAME IN A NON-LORE FRIENDLY WAY. IF YOU HAVE ANY SUGGESTION, BUG REPORT OR ISSUE WITH THE LIST, PLEASE INFORM ME IN MY DISCORD SERVER.

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
- Wunduniik makes use of **Stock Game System**, so every files contained in my Game folder will be installed for you.
- Install Mod Organizer 2 in a custom location (but still in the disk with more free space!), such as C:\Modding

### Wabbajack Installation

### Post Installation

#### Load Order Sorting

If needed (or if you added new mods with plugins), it's highly recommanded that you sort your modlist. To do so, launch Mod Organizer 2, and add as executable `LOOT.exe`. Now run LOOT to the executable list. To help you, I already made some configurations for a correct Load Order. Here is the [LOOT Settings](https://drive.google.com/file/d/1-zJu53bN4NCCfUx9K3jNiD_4oXQYMCot/view?usp=sharing) I use. Extract its content in "Your Disk"\Users\"Your User Profile"\AppData\Local\LOOT\games\Skyrim Special Edition. 

Tip: to get access to Appdata if you can't see it, in your files explorer, go to options, Display, and tick "display hidden files and folders":

![image](https://i.redd.it/9gy3rgdmgu191.png)

#### BethINI and INIs

BethINI is a really useful tool to edit your `Skyrim.ini`, `SkyrimCustom.ini` and `SkyrimPrefs.ini`. I already provided you my INIs, but some lines might not be set up correctly for your computer. Here are the lines you must check before starting your game:
- SkyrimPrefs.ini:
  - [Display]
    - iSize H=1080 -> Change this with your screen resolution Height
    - iSize W=1920 -> Change this with your screen resolution Width
    
      Those 2 lines can be changed directly through the Skyrim Launcher or BethINI
  - [Launcher]
    - sD3DDevice="NVIDIA GeForce GTX 1070" -> Change this with you GPU name
- Skyrim.ini:
  - [Display]
    - sScreenShotBaseName=C:\Games\The Elder Scrolls - Skyrim - Special Edition\Screenshots\Screenshots -> Create a folder called `Screenshots` and replace this line         with the path leading to the new folder. Also you can change this using BethINI.


#### ENB

Wunduniik was designed and set up to be used with [Rudy ENB for Cathedral Weathers - Zangdar Edit](https://www.nexusmods.com/skyrimspecialedition/mods/39113) last version, but you can change it if you don't like it.

Also to help you with the ENB management, I strongly advise you the [ENB Organizer](https://www.nexusmods.com/skyrim/mods/67077). It will allow you to prepare presets of ENBs you can easely switch as it will remember the files used and their configurations. Here is how you may use/set up it:

## Using The List

### Starting The List

Open `Mod Organizer.exe` and launch `SKSE` through the executables. As the modlist is quite big , depending on your pc, it may take some time to load the game. **THIS IS NORMAL DON'T PANIC!** Also I advise you to add Modding folder and Skyrim folder as exeptions in your Antivirus, it may cause some issues and even crashes.

### Configuring MCM

MCM have been configured thanks to [MCM Recorder](https://www.nexusmods.com/skyrimspecialedition/mods/61719). However if you don't like my settings, it's up top you to change them, but with the amount of MCM, it may take some time. Here is my configuration for (almost) all MCM:

## Updating the List

If this Modlist receives an update, please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your saves will be kept, but please check each update changelog to see if the update is save compatible. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the overwrite existing Modlist button.

## Editing the List

I know some of you will surely find things to change because of personnal preferences. To help you with the edition of the list, I added some symbols to retreive what kind of mods are on the list:
- **Mods tagged with ():** those mods are regular Fomods, with only add-ons and options, no patches for other mods.
- **Mods tagged with []:** those mods are Fomods that include patches for other mods, and they may also include add-ons and options.
- **Mods Tagged with {}:** those mods are mods not published on the Nexus. 

## Removing the List

To uninstall the list simply delete the MO2 folder. As Wunduniik uses the Stock Game system, which copies a game installation within it's installation folder, it is entirely self contained.

## FAQ

This section is for now empty, but will fill up with the question that will be asked. 

### Fix a Crash

If you are playing with my modlist (or any other) and for some reasons, the game crashes, don't panic. It can happen. The first thing we want to know is why doest it crash. To find out, normally once you will go back to Mod organizer 2, the `Overwrite` folder will contain a new folder called ".NetScriptFramework". Expand it until you see a `Crash.txt` file. We will take an example:

![image](https://i.redd.it/tlssuy3elu191.png)

We can see on this crash log that in the `Possible Relevant Objects`, the plugins *etheral_elven_overhaul.esp* and *JK's Temple of Mara....esp* are mentioned a lot. This means they may be the cause of the crashes. So just disable the corresponding plugins and restart your game. If it doesn't crash again, we fixed it, however if it crashes again, follow again the steps. If after that you just can't fix your crashes, you can ask me or the modding helpers in my discord server.

### Reporting an Issue

If, during your playthrough, you encounter any bug, incompatibily, that may disturb your gameplay/immersion, I invite you to head over my discord server and to share the bug you found in the dedicated channel, so I can try to fix it for a future update. We are working together to make this modlist always better!

### Wide and Ultrawide Screens Options

If you play on a wide or ultrawide screen (32:9, 21:9), you may need to fix the UI, because it won't be scaled up to your screen ratio. You may want to install [Nordic UI 32 by 9 and 21 by 9 aspect ratio patch](https://www.nexusmods.com/skyrimspecialedition/mods/53909) that will scale the UI of Nordic UI to you screen. If you find anything else not scaled up properly with the UI, let me know.

### Performance Options

#### Tweaking and Switching ENB

It is possible that the ENB I use in this list don't suit you, or is too performance heavy for your list. In that case here is what you can do:
- Switch with a more performance friendly ENB, such as [Re-Engaged ENB](https://www.nexusmods.com/skyrimspecialedition/mods/1089)
- You can disable Complex Grass in the `ENBSeries.ini` file, to get back some perfs
- You can change those settings in the `ENBSeries.ini` file:
  - [EFFECT]
    - EnableDepthOfField=false
    - EnableNormalMappingShadows=false
  - [SSAO_GAME]
    - AOAmount=0.0
    - AOAmountInterior=0.0
  - [SSAO_SSIL]
    - UseSelfIntersecting=false
    - SourceTexturesScale=0.25
    - SamplingQuality=1
  - [COMPLEXFIRELIGHTS]
    - EnableShadow=false
  - [COMPLEXPARTICLELIGHTS]
    - EnableShadow=false
    - EnableNormalMappingShadows=false
  - [REFLECTION]
    - Quality=-1
  - [UNDERWATER]
    - HighQualityCaustics=false
  - [WATER]
    - EnableTessellation=false

#### INI Configuration

It is also possible that some of your INI settings are really unoptimized and may take some performances for nothing. Open `BethINI` and make sure the settings are like this:
- Shadow Resolution: 2048
- Ambient Occlusion: Either use this or the ENB version. The ENB version is more intensive. Do not have both turned on.
- Remove Shadows: I really don’t recommend turning this on, but if you must then you can.

#### Mods Configuration

As I already said it, the modlist is exclusively in 2K. This means that every files, including effects such as mists, dadelion seeds, ripples... are in 2K. You can lower them, as well as some clutter retextures, in 1K if you estimate that 2K is not necessary. You may not find a big difference between 1K and 2K for those files. Also, you can change some settings in the Fomods ([Editing the Modlist](#editing-the-modlist)).

**If you have more questions, I invite you to join my Discord Server (Link in [Contact Me](#contact-me))!!**

## Credits and Thanks

- First thanks to **You** for downloading the list and reading this. The modlist is alive because of you.
- Thanks to Halgari and everyone the Wabbajack Team, without whom this list would surely never have seen the daylight.
- thanks to Althro and the Animonculory Team for their support and feedbacks, you should also check out their [incredible list](https://www.wabbajack.org/modlist/Animonculory/AVO).
- Thanks to AvatarV who helped me a lot with the Trailer video for the list.
- And of course thanks to every modders whose mods I used for the list.

## Contact Me

[![Discord][discord-icon]][discord-link]

[discord-icon]: https://i.redd.it/gpbq94pahz191.png
[discord-link]: https://discord.gg/2BWpEdxwNf

[![Nexus][nexus-icon]][nexus-link]

[nexus-icon]: https://i.redd.it/evvafm26hz191.png
[nexus-link]: https://www.nexusmods.com/users/57127132
