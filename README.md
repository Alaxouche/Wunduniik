![Logo](https://i.redd.it/jvzzn99stzua1.png)

---

<h3 align="center">
  <a href="https://discord.gg/2BWpEdxwNf/"><img alt="Discord"src="https://www.freepnglogos.com/uploads/discord-logo-png/discord-logo-logodownload-download-logotipos-1.png" width="50" height="50"></a> ︱
  <a href="https://www.nexusmods.com/skyrimspecialedition/mods/84347"><img alt="Nexus" src="https://raw.githubusercontent.com/github/explore/781dbc058383a2ee8259ebbab057292f16172d5e/topics/nexus-mods/nexus-mods.png" width="50" height="50"></a> ︱
  <a href="https://www.patreon.com/alaxouche"><img alt="Patreon" src="https://decentered.co.uk/wp-content/uploads/2019/12/patreon-logo-png-badge-7.png" width="50" height="50"></a> ︱
  <a href="https://ko-fi.com/alaxouche"><img alt="Ko-Fi" src="https://uploads-ssl.webflow.com/5c14e387dab576fe667689cf/61e1116779fc0a9bd5bdbcc7_Frame%206.png" width="50" height="50"></a>
</h3>
<hr>

# Wunduniik

A Skyrim Special Edition Wabbajack Modlist Installer.

## Summary
- [Preamble](#preamble)
- [System Requirement & Necessary Tools](#system-requirement-and-necessary-tools)
  - [Pc Minimum And Recommanded Components](#pc-minimum-and-recommanded-components)
  - [Necessary And Useful Applications](#necessary-and-useful-applications)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Necessary Tweaks](#necessary-tweaks)
    - [Accounts & Websites](#accounts-and-websites)
  - [Wabbajack Installation](#wabbajack-installation)
  - [Problems With Installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Load Order Sorting](#load-order-sorting)
    - [BethINI and INIs](#bethini-and-inis)
    - [ENB](#enb)
    - [DLSS](#dlss)
      - [What is DLSS](#what-is-dlss)
      - [Installing and Configuring DLSS](#installing-and-configuring-dlss)
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

This modlist is a heavy +1900 mods list based on **my** personnal preferences. It improves almost everything from the vanilla game to make it looks more like a 2023 game than a 2011 game. Keep in mind that the list is more like a vanilla rework than a list adding new quests, new lands...
Wunduniik is a draconic word meaning "Traveler". I chose this one as I think that when you travel, you discover new cultures, architectures... things can look a lot different. I think this modlist will provide you the same feeling, because you will almost discover a new game.

# Disclaimer

### YOU MUST READ THE INTEGRITY OF THIS README TO MAKE SURE THE LIST WILL WORK. IF YOU DON'T READ IT WON'T WORK. THE LIST WAS MADE TO TOTALLY CHANGE THE GAME IN A NON-LORE FRIENDLY WAY. IF YOU HAVE ANY SUGGESTION, BUG REPORT OR ISSUE WITH THE LIST, PLEASE INFORM ME IN MY DISCORD SERVER.

## System Requirement and Necessary Tools

### Pc Minimum And Recommanded Components

As Wunduniik is a modlist modlist based on graphics, you must have a good GPU.
#### YOU NEED 321 GB free to download the modlist!

Minimum Specs:

| CPU | GPU |  RAM  | Storage | Screen | FPS |
| ------------- |------------- | ----- | ----- | ----------- | ---------- |
| I5-7600k | Nvidia GTX 1080 | 16GB RAM DDR4 | 500 GB SATA II SSD | FHD 60Hz Screen | 38 |

Recommended Specs:

| CPU | GPU |  RAM  | Storage | Screen | FPS |
| ------------- |------------- | ----- | ----- | ----------- | ---------- |
| I7-9700k | Nvidia RTX 3060TI | 32GB RAM DDR5 | 1 TB SATA III/M.2 SSD | FHD 144Hz Screen | 60 |

In comparison here are my specs:

| CPU | GPU |  RAM  | Storage | Screen | FPS |
| ------------- |------------- | ----- | ----- | ----------- | ---------- |
| I7-7700 | Nvidia RTX 3060TI | 16GB RAM DDR4 | 1TB SATA III SSD | FHD 60Hz Screen | 48 |

### Necessary And Useful Applications

For the modlist to work you must have some apps:
Please ensure you have .NET v5.0 or higher installed. Download the **desktop app installer and console app x64** from Microsoft here https://dotnet.microsoft.com/download/dotnet/5.0/runtime, and also [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe).

![image](https://raw.githubusercontent.com/Lost-Outpost/lost-legacy/main/images/microsoft-net-5-0-installation.png)

To help you with the INIs configuration, I highly recommand to have installed Sublime Text](https://www.sublimetext.com/)

### PageFile Configuration

  1. Press **Windows + R** on your keyboard
  2. Type **sysdm.cpl ,3**
  3. press **Enter**
  4. Under the Performance section, press **'Settings'**
  5. Click the **Advanced** tab at the top
  6. at the Virtual memory section press **'Change...'**
  7. Disable **'Automatically manage paging file size for all drives'**
  8. Click **"Custom size:"**
  9. Set a custom size for the drive Skyrim is installed on with a minimum of at least **20480MB** (40960MB if higher)
  10. Click Set
  11. Click apply & OK
  12. Press Yes to restart
  13. Restart your computer.

#### THIS IS NOT OPTIONAL, YOU CANNOT SKIP THIS STEP EVEN IF YOU HAVE 256 GB OF RAM.

## Installation

Installing Wunduniik is not hard and, if you have nexus premium, is more of a waiting game. If you are updating, you can safely skip to updating.

### Pre-Installation

#### Necessary Tweaks

Before installing the modlist, here are some things you **must** do:
1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop & Console x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.

#### Accounts and Websites

So the Wabbajack Installation happens without problem, you must connect/create a few accounts for the following websites:
- [Loverslab](https://www.loverslab.com/)
- [Nexus Mod](https://www.nexusmods.com/) (Premium Recommended for faster installation)
- [Vector Plexis](https://vectorplexis.com/)

### Wabbajack Installation

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

Downloading and installing Wunduniik can take a while depending on your internet connection and computer. To install the list, complete the following.

Now you can follow the next steps in order to download and install Wunduniik Modlist properly:
1. Open Wabbajack and click on browse modlists.
2. Press the download button on Wunduniik and wait for it to download.
3. Set the installation folder to be somewhere like C:\Games\Wunduniik. Do not install it to your desktop or downloads folder.
4. The download location does not need to be on an SSD but it makes installing a bit faster.
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. The installation is now complete. You can move on to the next section. If you have issues with installation, you can refer to Wabbajack Installation Issues

### Even if Wabbajack say installation complete, this doesn't mean you have finished. You _Must_ follow the rest of the installation guide in order to have the list working properly. Otherwise you will have big issues.

#### Problems With Installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.
Here are the files that commonly fail you can download from there:
- [Marsh Trees](https://drive.google.com/file/d/1rlbyhbo4P9zN7fOGAaFPA1FkIIODdDvc)
- [Real Wheat Fields](https://drive.google.com/file/d/1aA15AVXDubSoizOnLeNm19TsnbvtpRZn)

### Post Installation
  
#### Load Order Sorting

- x is not a whitelisted download:
  - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.
  	 
- Wabbajack could not find my game folder:
	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.


#### BethINI and INIs

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

BethINI is a really useful tool to edit your `Skyrim.ini`, `SkyrimCustom.ini` and `SkyrimPrefs.ini`. I already provided you my INIs, but some lines might not be set up correctly for your computer. Here are the lines you must check before starting your game:
- SkyrimPrefs.ini:
  - [Display]
    - iSize H=1080 -> Change this with your screen resolution Height
    - iSize W=1920 -> Change this with your screen resolution Width
    
      Those 2 lines can be changed directly through the Skyrim Launcher or BethINI
  - [Launcher]
    - sD3DDevice="NVIDIA GeForce RTX 3060TI" -> Change this with you GPU name
- Skyrim.ini:
  - [Display]
    - sScreenShotBaseName=C:\Games\The Elder Scrolls - Skyrim - Special Edition\Screenshots\Screenshots -> Create a folder called `Screenshots` and replace this line         with the path leading to the new folder. Also you can change this using BethINI.

#### Changing screen resolution

It is recommended to check the ini files in Beth-Ini to make sure that your screen resolution matches what the files are set to. To do this, complete the following.

1. Close Mod Organizer 2.
2. Navigate to the tools folder and launch `BethIni`
3. In the `Basic` section on the first page, make sure the screen resolution matches.
4. In the `General` section, make sure the `Screenshots Directory` is set to where you want your screenshots to go.
5. Navigate back to the basic tab.
6. Press `Save`

***

#### ENB

Wunduniik was designed and set up to be used with Cabbage ENB for NAT III Weather, but you can change it if you don't like it.

Also to help you with the ENB management, I strongly advise you the [ENB Organizer](https://www.nexusmods.com/skyrim/mods/67077). It will allow you to prepare presets of ENBs you can easily switch as it will remember the files used and their configurations. Here is how you may use/set up it:

1. Launch ENB Organizer through Mod Organizer 2:

![image](https://i.redd.it/bejqj491l7291.png)

2. Browse to the preset section:

![image](https://i.redd.it/0ju9g2a3l7291.png)

3. Select one of the different ENB presets available for the list (all are compatible with the list's weather mod, Cathedral Weather):

![image](https://i.redd.it/tnpyve3el7291.png)

4. If you want to add your presets, follow the instructions directly on the [ENB Organizer](https://www.nexusmods.com/skyrim/mods/67077) mod page.

#### DLSS

For a performance matter, I highly recommend you to install the [DLSS mod support for ENB](https://www.patreon.com/PureDark), that is paywalled (that's why I can't use it in the list directly) as it's still in development. 

##### What is DLSS?

DLSS is an upscaling method use by Nvidia cards (there are equivalents for AMD and Intels) that works by lowering your game resolution and then upscaling it to the original resolution using AI. This means that if you play originally on a 2K resolution, DLSS will lower for example to FHD and then using AI upscale, imitate the 2K resolution. 
This method tricks the graphic card so this means you will have a significant amount of performance gain with minimal visual loss. With ENB Support, you can gain up to 20-30fps on good machines.

##### Installing and configuring DLSS

Begin by downloading the latest version of DLSS for Skyrim SE from PureDark's Patreon. Install it in Mod Organizer 2 like a regular mod: in Mod Organizer 2, do `Ctrl + M`. A pop-up will appear. Navigate to your files and find the DLSS mod archive (.7z or .zip) you just installed. Click open, and click ok. Congratulation, you just installed DLSS!

Now we will focus on how to configure it: Right click on the mod, click `open in Explorer...` and then navigate to SKSE/Plugins/ and then open `SkyrimUpscaler.ini`.
Change the following settings:
- For Nvidia Card Users:
  - mUpscaleType = 1 -> 0
  - mQualityLevel = 2 -> 1
- For AMD Card Users:
  - mQualityLevel = 2 -> 1 
- For Intel Card Users:
  - mUpscaleType = 1 -> 2
  - mQualityLevel = 2 -> 1

Save the changes. Now in order to make it work properly, you need to disable TAA and Edge AA from Game .inis and ENB .inis. Once done, DLSS will be ready to work in-game. 
DLSS comes with an integrated control panel in-game. To activate/deactivate it, simply use `END` key. You can change here sharpness, mipmap...
If you don't know what DLSS is, read this guide [here](https://www.nvidia.com/en-gb/geforce/technologies/dlss/)

## Using The List

### Starting The List

Open `Mod Organizer.exe` and launch `SKSE` through the executables. As the modlist is quite big, depending on your pc, it may take some time to load the game. **THIS IS NORMAL DON'T PANIC!** Also I advise you to add Modding folder and Skyrim folder as exeptions in your Antivirus, it may cause some issues and even crashes.

**Note**: I recommend adding the list to your antivirus exceptions list as it will potentially stop it from interfering.

### Configuring MCM 

ALL MCM's have been pre-configured via [MCM Recorder](https://www.nexusmods.com/skyrimspecialedition/mods/61719) and Settings Loader mods, however you can change the settings if you don't like them.

## Updating the List

If this Modlist receives an update, please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your saves will be kept, but please check each update changelog to see if the update is save-compatible. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the overwrite existing Modlist button.

## Editing the List

It is possible that you might not like some of the items in the list and wish to change them to your personal preferences. To make this easier, I have added some special tags to indicate what they are.

Key:
- `Basic Fomod`: Regular fomod with only add-ons and other options. No patches for other mods.
- `Patches Fomod`: Self-explanatory and may contain add-ons and other options.
- `Unpublished`: Again, self-explanatory.
- `Output`: These are files I have generated for the list. You can and should regenerate them if you change something that affects them.

## Removing the List

To uninstall the list simply delete the MO2 folder. As Wunduniik uses the Stock Game system, which copies a game installation within its installation folder, it is entirely self-contained.

## FAQ

This section is for now empty, but will fill up with the question that will be asked. 

### Fix a Crash

If you are playing with my modlist (or any other) and for some reasons, the game crashes, don't panic. It can happen. The first thing we want to know is why does it crashes. To find out, normally once you will go back to Mod organizer 2, the `Overwrite` folder will contain a new folder called ".NetScriptFramework". Expand it until you see a `Crash.txt` file. We will take an example:

![image](https://i.redd.it/tlssuy3elu191.png)

We can see on this crash log that in the `Possible Relevant Objects`, the plugins *etheral_elven_overhaul.esp* and *JK's Temple of Mara....esp* are mentioned a lot. This means they may be the cause of the crashes. So just disable the corresponding plugins and restart your game. If it doesn't crash again, we fixed it, however if it crashes again, follow again the steps. If after that you just can't fix your crashes, you can ask me or the modding helpers in my discord server.

### Reporting an Issue

If, during your playthrough, you encounter any bug, incompatibility, that may disturb your gameplay/immersion, I invite you to head over my discord server and to share the bug you found in the dedicated channel, so I can try to fix it for a future update. We are working together to make this modlist always better!

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

As I already said it, the modlist is exclusively in 2K. This means that every file, including effects such as mists, dandelion seeds, ripples... are in 2K. You can lower them, as well as some clutter retextures, in 1K if you estimate that 2K is not necessary. You may not find a big difference between 1K and 2K for those files. Also, you can change some settings in the Fomods ([Editing the Modlist](#editing-the-modlist)).

**If you have more questions, I invite you to join my Discord Server (Link in [Contact Me](#contact-me))!!**

## Credits and Thanks

- **You** for downloading the list and reading this. You're awesome.
- Halgari and the Wabbajack Team. Without Wabbajack, this list would not exist.
- Althro and the Animonculory Team for their support and feedback. You should also check out their [incredible lists](https://github.com/The-Animonculory/AnimonculoryWJLists/blob/main/README.md).
- AvatarV who helped make the trailer for the list.
- All the modders who make mods. Without you, there'd be no list.

## Contact Me

[![Discord][discord-icon]][discord-link]

[discord-icon]: https://i.redd.it/gpbq94pahz191.png
[discord-link]: https://discord.gg/2BWpEdxwNf

[![Nexus][nexus-icon]][nexus-link]

[nexus-icon]: https://i.redd.it/evvafm26hz191.png
[nexus-link]: https://www.nexusmods.com/users/57127132
