# FROST - Below Zero Fallout 4 Wabbajack Modlist
This is a github repository for a modlist made by following [Below Zero - A FROST Modding Guide](https://redawt.github.io/f4-frost-guide) -  Recommended Setup. 

It also contains a small guide on how to install the modlist, some clarifications about the small changes, requirements, recommended specs, and credits.

The author is not connected to the FROST Development Team, but has the permission to make this modlist.

## Description
FROST is a total conversion mod for Fallout 4. For best experience, FROST requires a number of different mods to supplement it. [Below Zero](https://redawt.github.io/f4-frost-guide) is a list of such mods and a guide on how to properly install them. Wabbajack is a tool used to install mod lists with pre-defined load order and other settings, effectively doing the work of the guides such as Below Zero for you.

The goal of this Wabbajack modlist is to provide a simple way to install a basic FROST modlist in just a few clicks. It was made by following the [Below Zero](https://redawt.github.io/f4-frost-guide) guide (Recommended Setup), from INI settings to applying all needed FROST patches. It doesn't contain anything else besides the mods mentioned in Recommended Setup section, with few exceptions:
- It includes some additional INI tweaks from BethINI, The Midnight Ride, Optimization Guides Collection, and FO4 Step Modifications.
- It installs all FallUI options and therefore includes a generated Complex Sorter patch for FIS - The NEW FallUI Item Sorter.
- It doesn't include Pack Attack NPC (PANPC) mod, because the author doesn't allow its distrubtion through modlists or NexusMods. You can find instructions on how to get it in Below Zero guide itself, in the Imporant Mods section.
- It uses Ultra Interior Lighting and Ultra Exterior Lighting as Lighting Mods options.
- It uses Root Builder to manage files that need to be placed in the Root folder of the game instead of the Data folder, such as F4SE.

## Requirements
- An English copy of Fallout 4 from Steam
  - [Read Initial Setup section of Below Zero guide](https://redawt.github.io/f4-frost-guide/initialsetup.html) to learn how to properly install Fallout 4.
  - Only the English version of the game is supported for maximum compatibility.
- All DLCs for Fallout 4 (except the High Resolution Texture Pack DLC)
- At least 37.5 GB of free drive space
- Windows 7 or higher (64bit)
- [Microsoft VC++ 2015-2022](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170) (x86 and x64 versions)
  - Just download the files and install them
  - Do not download the ARM64 version or Visual Studio itself, they aren’t needed.
- The latest GPU drivers (Either NVIDIA or AMD)
- A Nexus Mods account

## Recommended Specs
Installing the game on an SSD can drastically improve load times and decrease stuttering. Here are the (minimal) recommended specs for being able to run the game at 60FPS in 1080p:

- **CPU:** Modern quad-core processor (2.75GHz or more)
- **RAM:** 16 GB of RAM
- **GPU:** NVIDIA 900 series card or an AMD RX 400 series card

## Installation
1. Follow [Initial Setup section of Below Zero](https://redawt.github.io/f4-frost-guide/initialsetup.html) guide to properly install Fallout 4. No need to do anything else from the guide.
2. Download [Wabbajack](https://www.wabbajack.org/) and install.
3. Pick this Modlist from the Gallery (Browse Modlist button), you can search for it by its name in the Search field. Tick "Show Unnoficial Lists" for that.
4. Press the download button and wait for it to download. 
6. Set Modlist Installation Location to be somewhere like C:\Games\FROST. DO NOT place it in Program Files, User folders (such as Desktop, Documents, Downloads, etc.), or in your Fallout's Steam folder.
7. Set Resource Download Location to be wherever you prefer.
8. Press the play button to begin.
9. After the installation is complete, go to Modlist Installation Location and run ModOrganizer.exe. Click Run button on the top right part of the MO2 window. You should always launch FROST from MO2.
10. Done. You don't need to do anything else, the game should launch properly.

## Modification 
If you want to modify the list, follow [Load Order section](https://redawt.github.io/f4-frost-guide/normallo.html) from Below Zero guide. Otherwise you may encounter nasty bugs that will ruin your game.

## Support and questions
Join [FROST Official Discord](https://discord.com/invite/BaKsm7Fn4A) if you have question about the game or just want to discuss it with others.
If you have questions about the installation process or encounter errors related to installation, you can DM @august to ask them. If you have questions about the game process and errors related to it, use support-and-bugs channel.

## Credits
[naugrim04](https://www.nexusmods.com/fallout4/users/6324000) - for creating FROST.

[Red](https://www.nexusmods.com/fallout4/users/47725848) and FROST Development Team - for continuing the work on FROST, all improvements, and maintaining its great community.

[The Midnight Ride Guide](https://themidnightride.moddinglinked.com/) and its authors - it inspired Below Zero guide, and therefore this modlist. A lot of sections from Below Zero guide are identical to the Midnight Ride Guide. If you are planning to make a non-FROST Fallout 4 setup, you should use The Midnight Ride guide or its [Wabbajack list](https://themidnightride.moddinglinked.com/wabbajack.html).

[Optimization Guides Collection 2](https://www.nexusmods.com/fallout4/mods/50005) - the modlist uses some of its INI settings.

[Step Fallout 4 - FO4 - Guide](https://www.nexusmods.com/fallout4/mods/74193) - the modlist uses some of its INI settings.
