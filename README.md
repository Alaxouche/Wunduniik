![Logo](https://i.redd.it/1tfaz3eeas191.png)

---

<h3 align="center">
  <a href="https://discord.gg/2BWpEdxwNf/"><img alt="Discord"src="https://www.freepnglogos.com/uploads/discord-logo-png/discord-logo-logodownload-download-logotipos-1.png" width="50" height="50"></a> ︱
  <a href="https://www.nexusmods.com/users/57127132"><img alt="Nexus" src="https://raw.githubusercontent.com/github/explore/781dbc058383a2ee8259ebbab057292f16172d5e/topics/nexus-mods/nexus-mods.png" width="50" height="50"></a> ︱
  <a href="https://www.patreon.com/alaxouche"><img alt="Patreon" src="https://decentered.co.uk/wp-content/uploads/2019/12/patreon-logo-png-badge-7.png" width="50" height="50"></a> ︱
  <a href="https://ko-fi.com/alaxouche"><img alt="Ko-Fi" src="https://uploads-ssl.webflow.com/5c14e387dab576fe667689cf/61e1116779fc0a9bd5bdbcc7_Frame%206.png" width="50" height="50"></a>
</h3>
<hr>

# Wunduniik

A Skyrim Special Edition Wabbajack Modlist Installer.

## Summary
- [Preamble](#preamble)
- [System Requirements& Necessary Tools](#system-requirements)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Accounts & Websites](#accounts-and-websites)
  - [Wabbajack Installation](#wabbajack-installation)
  - [Post-Installation](#post-installation)
    - [Changing Sreen Resolution](#changing-screen-resolution)
    - [ENB](#enb)
    - [DLSS](#dlss)
- [Playing The List](#playing-the-list)
  - [Starting The List](#starting-the-list)
  - [Configuring MCM](#configuring-mcm)
- [Updating The List](#updating-the-list)
- [Editing The List](#editing-the-list)
- [Removing The List](#removing-the-list)
- [FAQ](#faq)
  - [Reporting an Issue](#reporting-an-issue)
  - [Wide and Ultrawide Screens Options](#wide-and-ultrawide-screens-options)
  - [Performance Options](#performance-options)
    - [Tweaking and Swithing ENB](#tweaking-and-switching-enb)
    - [INI Configuration](#bethini)
- [Credits And Thanks](#credits-and-thanks)
- [Contact Me](#contact-me)

## Preamble

Wunduniik is a modlist focused mostly on graphics and textures and creating a game that has a 2023 look instead of a 2011 game. The list does not add new quests or lands, but rather focuses on making the world of Skyrim more exciting and one that you would enjoy travelling through.

*"I created Wunduniik after people were asking how I got my Skyrim to look like it does. I know that it can be difficult to mod correctly when you are starting out, however this list will help you build the Skyrim of your dreams. This is a list which changes Skyrim into what I think is perfect, however you can change things if you don't like it. That's the great thing about modding, you can change something if you don't like it."*

## System Requirements

Wunduniik is aimed at mid to higher tier systems, therefore a system similar to the ones given below is recommended.

Minimum Specs:

| CPU | GPU |  RAM  | Storage | Screen | FPS |
| ------------- |------------- | ----- | ----- | ----------- | ---------- |
| I5-7600k | Nvidia GTX 1080 | 16GB RAM DDR4 | 500 GB SATA II SSD | FHD 60Hz Screen | 35 |

Recommended Specs:

| CPU | GPU |  RAM  | Storage | Screen | FPS |
| ------------- |------------- | ----- | ----- | ----------- | ---------- |
| I7-9700k | Nvidia RTX 3060TI | 16GB RAM DDR5 | 1 TB SATA III/M.2 SSD | FHD 144Hz Screen | 50 |

My Specs:

| CPU | GPU |  RAM  | Storage | Screen | FPS |
| ------------- |------------- | ----- | ----- | ----------- | ---------- |
| I7-7700 | Nvidia RTX 3060TI | 16GB RAM DDR4 | 1TB SATA III SSD | FHD 60Hz Screen | 45 |

## Installation

Installing Wunduniik is not hard and, if you have nexus premium, is more of a waiting game. If you are updating, you can safely skip to updating.

### Pre-Installation

Prior to installing Wunduniik, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop & Console x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.

#### Accounts and Websites

You will require accounts for the following sites in order to install Wunduniik. They are all free to register for.

- [Loverslab](https://www.loverslab.com/)
- [Nexus Mod](https://www.nexusmods.com/) (Premium Recommended for faster installation)
- [Vector Plexis](https://vectorplexis.com/)

***

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Installing Wunduniik

Downloading and installing Wunduniik can take a while depending on your internet connection and computer. To install the list, complete the following.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on Wunduniik and wait for it to download.
3. Set the installation folder to be somewhere like C:\Games\Wunduniik. Do not install it to your desktop or downloads folder.
4. The download location does not need to be on a SSD but it makes installing a bit faster.
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. The installation is now complete. You can move on to the next section. If you have issues with installation, you can refer to Wabbajack Installation Issues

***

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.

- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post Installation

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

Wunduniik was designed and set up to be used with [Rudy ENB for Cathedral Weathers - Zangdar Edit](https://www.nexusmods.com/skyrimspecialedition/mods/39113) last version, but you can change it if you don't like it.

Also to help you with the ENB management, I strongly advise you the [ENB Organizer](https://www.nexusmods.com/skyrim/mods/67077). It will allow you to prepare presets of ENBs you can easely switch as it will remember the files used and their configurations. Here is how you may use/set up it:

1. Launch ENB Organizer through Mod Organizer 2:

![image](https://i.redd.it/bejqj491l7291.png)

2. Browse to the preset section:

![image](https://i.redd.it/0ju9g2a3l7291.png)

3. Select one of the different ENB presets available for the list (all are compatible with the list's weather mod, Cathedral Weather):

![image](https://i.redd.it/tnpyve3el7291.png)

4. If you want to add your presets, follow the instructions directly on the [ENB Organizer](https://www.nexusmods.com/skyrim/mods/67077) mod page.

#### DLSS

If you are struggling with performance, I highly recommend you try out the DLSS mod for Skyrim which is in development. You will find it after a quick google search.

If you don't know what DLSS is, read this guide [here](https://www.nvidia.com/en-gb/geforce/technologies/dlss/)

## Playing The List

### Starting The List

Open the installation folder and double click on the program called `ModOrganizer.exe`. It make take some time to load.

**Note**: I recommend adding the list to you antivirus exceptions list as it will potentially stop it from interfering.

Launch the game by selecting `SKSE` and pressing the `Run` button. It make some time to load as the list is quite big.

### Configuring MCM

ALL MCM's have been pre-configured via [MCM Recorder](https://www.nexusmods.com/skyrimspecialedition/mods/61719), however you can change the settings if yoiu don't like them.

## Updating the List

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## Editing the List

It is possible that you might not like some of the items in the list and wish to change them to your personal preferences. To make this easier, I have added some special tags to indicate what they are.

Key:
- `Basic Fomod`: Regular fomod with only add-ons and other options. No patches for other mods.
- `Patches Fomod`: Self-explanatory and may contain add-ons and other options.
- `Unpublished`: Again, self-explanatory.
- `Output`: These are files I have generated for the list. You can and should regenerate them if you change something that affects them.

## Removing the List

Simply delete the folder, and you have uninstalled it.

## FAQ

This section is for now empty, but will fill up with the question that will be asked. 

### Reporting an issue

Crashes do happen in modlists, however they are not something to worry or panic about. If you do get a crash, you will have a crashlog that is generated to the `Overwrite` section of MO2 in a new folder called `NetScriptFramework`. If you are running with an unmodified list, then please either report the bug here on github on in my personal discord server. The same goes for if you find any other issue in the game. I have a dedicated channel in my server for these so please report them there.

### Wide and Ultrawide Screens Options

If you use an ultrawide screen, you will need to fix the UI. Please install [Nordic UI 32 by 9 and 21 by 9 aspect ratio patch](https://www.nexusmods.com/skyrimspecialedition/mods/53909) to fix the UI. If you find anything else which does not scale correctly, please let me know.

### Performance Options

#### Tweaking and Switching ENB

If you find the ENB I use in this list not to your likeing, you can easily change it to another ENB via ENB organizer. 

If you find that you are still having performance issues, here are some tweaks you can try in the `enbseries.ini` file.

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

#### BethINI

To get some more FPS, tweak the following value in the detail section in BethINI.

- `Shadow Resolution`: 2048
- `Ambiant Occlusion`: The ENB version can be quite taxing so you may wish to use the in game one. Choose one or the other, not both.
- `Remove Shadows`: I really don’t recommend turning this on, but if you must, then you can.


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
