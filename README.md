<a href="https://www.youtube.com/watch?v=70DZ5UV1Bdo"><img src="images/septimus2.png" target="_blank"></a>

---

<p align="center">
  <a href="https://www.nexusmods.com/skyrimspecialedition/mods/58229">Nexus Page</a> ·
  <a href="README.md">Installation</a> ·
  <a href="GAMEPLAY.md">Gameplay Guide</a> ·
  <a href="CONFIGURATION.md">Configuration</a> ·
  <a href="CHANGELOG.md">Changelog</a>
</p>

---

# Installation

- [Preamble](#preamble)
  - [Gameplay](#gameplay)
  - [Community](#community)
  - [List Contents](#list-contents)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Library](#steam-library)
    - [Change Steams Update Behavior](#change-steams-update-behavior)
    - [Set the Game language to English](#set-the-game-language-to-english)
    - [Clean Skyrim](#clean-skyrim)
    - [Start Skyrim](#start-skyrim)
  - [Using Wabbajack](#using-wabbajack)
    - [Preparations](#preparations)
    - [Downloading and Installing](#downloading-and-installing)
      - [Problems with Wabbajack](#problems-with-wabbajack)
    - [Stock Game](#stock-game)
    - [Pagefile in prevention of memory crashes](#pagefile-in-prevention-of-memory-crashes)
- [Updating](#updating)
- [Starting](#starting)
- [Configuration](#configuration)
- [Issues](#issues)

# Preamble
Septimus is an extended version of The Phoenix Flavor with lots of new items, quests, visual tweaks and optional survival elements all built on top of the fantastic base that Phoenix has created. It also has full Anniversary Edition support including all the new creation club content for those eager to get right into the new content.

### Gameplay
Septimus seeks to modify Skyrim in the least intrusive possible way attempting to keep what makes the vanilla game great, while introducing new and fun things to find and do. You can find a summary of all [Gameplay Changes](GAMEPLAY.md) on a dedicated page [here](GAMEPLAY.md). 

### Community
Support is offered in [TPF Discord](https://discord.gg/tpf) server's #tpf-addons-support channel and in the Bugs section of this page according to the Bugs section of the add-on's documentation. If you have any questions following the add-on's instructions or if you find a typo or any other mistake in the documentation, feel free to report in TPF Discord server's #tpf-addons-support channel.

### List Contents
You can browse the full list contents [here](https://loadorderlibrary.com/lists/septimus) if you want to know exactly what you're getting.

# Installation
Installation is handled through Wabbajack with a one-click install of the modlist. There are some pre-installation steps which must be followed for first time users so please pay attention to those.

## Pre-Installation

These steps are only needed if you install the Modlist for the first time. If you are updating the Modlist, jump straight to [Updating](#updating).

### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. This package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

### Installing Microsoft .NET 5.0

Please ensure you have .NET v5.0 installed. Download the **desktop app installer and console app x64** from Microsoft here https://dotnet.microsoft.com/download/dotnet/5.0/runtime.

### Steam Library

If you have your Steam library in Program Files, read [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to put it somewhere else.
I will not provide support to people with Skyrim in their Program Files folder.
Locations like Documents, Downloads, Desktop, or OneDrive are NOT fine. The best location would be ``C:\SteamLibrary`` if you have a single drive, or whichever Drive Letter you have on your main Games drive. Such a location is also called the "root of the drive."

### Change Steam's Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically update the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it. 

[THIS](https://imgur.com/a/1dySo8q) is approximately what a clean Skyrim install should look like after shredding or cleaning it manually.

### Skyrim: Anniversary Edition (AE)

This list fully supports anniversary edition and all creation club content. Make sure your game is fully up to date in steam. It will automatically be patched by Wabbajack to work out of the box, but requires the latest game files.

## Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and open the _Options_ menu.

1. Leave the quality to what Skyrim sets it to, but you can lower it if you wish. FPS gain is minor though.
2. Set the _Aspect Ratio_ and _Resolution_ to your monitor's native values
3. Set _Antialiasing_ to _Off_
4. Check _Windowed Mode_ and _Borderless_

Start the game and exit once you're in the main menu.

## Using Wabbajack

### Preparations

Download the release to a _working folder_. This folder **must not** be in a _common folder_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in the _working folder_.

### Downloading and Installing

The download and installation process can take a little while (an hour or more) depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Download the latest release of `Septimus.wabbajack` from [Google Drive](https://drive.google.com/drive/folders/1-VIcggcf49sTHnqQgyifhTSGwgcKd6Jz?usp=sharing)
2. Create a folder for the List at the root of your drive (like the Wabbajack folder) called "Septimus"
3. Open the Septimus .wabbajack file and select the created folder in 3. as your installation folder
4. Go back to your drive, and create a new folder, called "Wabbajack Downloads Folder". This specific folder can be on a different drive if you wish
5. Select the created folder in step 3 as your downloads folder
6. Click the Go/Begin button and wait for Wabbajack to finish

### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case, just wait until I update the Modlist.

Some files are known to be problematic, it is likely those are the ones that failed. You can download them manually from their source and place the archives **AS IS** in the downloads folder.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Stock Game

Unlike regular Skyrim installation or some other Wabbajack Lists, Septimus comes with the **Stock Game Feature**, basically, it's a copy of a Skyrim installation located within your installation folder, cleaned and with everything but an ENB in it. It allows you to not worry about conflicting files with Vortex or other Wabbajack lists. Thus, after Wabbajack completes, you need not to move anything to your regular Skyrim Installation.

There are more steps though, so please keep following the next steps to setup the game optimally.

### Pagefile in prevention of memory crashes

Bigger Skyrim modlists need a lot of memory, and when there is not enough available it may fail allocating more. To fix this, you'll want to have a bigger pagefile.
A pagefile is a file on your disk Windows will use when there is not enough RAM available.
Never disable the pagefile - this may lead to various issues on your system, such as this Skyrim crash.

If you've never touched the pagefile, perform the following steps to prevent from memory crashes:
1. Press Windows + R on your keyboard and enter `sysdm.cpl ,3`
2. Under the Performance section, press 'Settings'
3. Go to the Advanced tab at the top, and at the Virtual memory section press 'Change...'
4. Disable 'Automatically manage paging file size for all drives'
5. If you have more than one drive, try enabling it for at least one more drive as a backup (make sure it has a decent bit of free space, like 15GB). Set the size to 'System managed size'.
Otherwise, set a custom size for the drive it's currently on and increase the maximum size to be at least 20GB.

# Updating

If this Modlist receives an update, please check the [changelog](CHANGELOG.md) before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your saves will be kept, but please check each update changelog to see if the update is save compatible.  Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

# Starting
When you first launch the game, unless it has been disabled, Skyrim Unbound reborn will perform startup tasks. You can configure it in the MCM to change starting gear. Press ENTER to begin character creation.

# Configuration
If you wish to further customize by changing the ENB preset, adding in creation club content, changing dodge keys, or swapping optional mods you can visit the [Configuration](CONFIGURATION.md) page for more info.

# Issues
Find an [issue](https://github.com/Guitarninja2/septimus/issues)? Feel free to report it [here](https://github.com/Guitarninja2/septimus/issues) with as much info as you can (screenshots are great). 
