<a href="https://www.youtube.com/watch?v=70DZ5UV1Bdo"><img src="images/banner.webp" target="_blank"></a>

---

<p align="center">
  <a href="README.md">Installation</a> ·
  <a href="GAMEPLAY.md">Gameplay Guide</a> ·
  <a href="CONFIGURATION.md">Configuration</a> ·
  <a href="CHANGELOG.md">Changelog</a> ·
  <a href="ADDONS.md">Addons</a> ·
  <a href="HELP.md">Help</a>
</p>

---

# Installation

- [Installation](#installation)
- [Introduction](#introduction)
  - [List Contents](#list-contents)
  - [Minimum Specs](#minimum-specs)
  - [Community](#community)
  - [Skyrim: Anniversary Edition](#skyrim-anniversary-edition)
- [Installation](#installation-1)
  - [Pre-Install](#pre-install)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Library](#steam-library)
    - [Set the Game language to English](#set-the-game-language-to-english)
    - [Clean Skyrim](#clean-skyrim)
    - [Start Skyrim](#start-skyrim)
  - [Using Wabbajack](#using-wabbajack)
    - [Preparations](#preparations)
    - [Downloading and Installing](#downloading-and-installing)
    - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Steam Deck](#steam-deck)
  - [Skyrim GOG](#skyrim-gog)
- [Updating](#updating)
- [Startup](#startup)
- [Issues](#issues)

# Introduction

Sovngarde is a lightweight Legacy of the Dragonborn modlist with a minimal yet beautiful visual overhaul and the highest quality quest content. Included is full creation club support and a suite of balance mods to tie it all together with my own cut of simonrim.

## List Contents

You can browse the full list contents [here](https://loadorderlibrary.com/lists/sovngarde-a-dragonborns-legacy) if you want to know exactly what you're getting.

You can find a summary of all changes on the [Gameplay Changes](GAMEPLAY.md) page.

## Minimum Specs
Users have reported running the list fine with as low as a Ryzen 1300x and a GTX960. You may need to adjust settings with systems this low but it should run fine and still look great!

## Community

Support is offered in [The Lost Outpost](https://discord.gg/WF66mMu) server and in the [Issues](https://github.com/Guitarninja2/septimus/issues) section of the Sovngarde GitHub. If you have any questions following the add-on's instructions or if you find a typo or any other mistake in the documentation, feel free to report in The Lost Outpost Discord server's support channel.

## Skyrim: Anniversary Edition

This list requires anniversary edition and all creation club content. Make sure your game is fully up to date in Steam. It will automatically be patched by Wabbajack to work out of the box, but requires the latest game files. You _must_ download all the creation club content before installing.

# Installation

Installation is handled through [Wabbajack](https://www.wabbajack.org/#/) with a one-click install of the modlist. There are some pre-installation steps which must be followed for first time users so please pay attention to those.

## Pre-Install

These steps are only needed if you install the Modlist for the first time. If you are updating the Modlist, jump straight to [Updating](#updating).

### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. This package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

### Steam Library

If you have your Steam library in Program Files, read [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to put it somewhere else.
I will not provide support to people with Skyrim in their Program Files folder.
Locations like Documents, Downloads, Desktop, or OneDrive are NOT fine. The best location would be `C:\SteamLibrary` if you have a single drive, or whichever Drive Letter you have on your main Games drive. Such a location is also called the "root of the drive."

### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it.

[THIS](https://imgur.com/a/1dySo8q) is approximately what a clean Skyrim install should look like after shredding or cleaning it manually.

### Start Skyrim
Start the game and exit once you're in the main menu. This will ensure any settings files needed by Wabbajack are created in the Skyrim directory.

## Using Wabbajack

### Preparations

Download the release to a _working folder_. This folder **must not** be in a _common folder_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in the _working folder_.

### Downloading and Installing

The download and installation process can take a little while (an hour or more) depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Create a folder for the List at the root of your drive (like the Wabbajack folder) called "Sovngarde"
2. Go back to your drive, and create a new folder, called "Wabbajack Downloads Folder". This specific folder can be on a different drive if you wish
3. Download the latest release of `Sovngarde` from the Wabbajack Browse Modlists page
4. Select the created folder in step 1 as your installation folder
5. Select the created folder in step 2 as your downloads folder
6. Click the Go/Begin button and wait for Wabbajack to finish

### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress. Seriously, simply retrying the Wabbajack download fixes most problems. If you still cannot figure out the issue, please check in our support forum or the official Wabbajack discord.

## Steam Deck

This modlist can be played on Steam Deck and special care has been taken to make sure performance is acceptable there. You can view the steam deck install instructions [here](https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki/Skyrim:-Sovngarde) after you finish the normal install.

## Skyrim GOG

This modlist can be played on the GOG version of Skyrim. You will need to do a couple of extra steps which are listed [here](GOG.md)

# Updating

If this Modlist receives an update, please check the [changelog](CHANGELOG.md) before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your saves will be kept, but please check each update changelog to see if the update is save compatible. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

# Startup

Open the installation folder and double click on the program called `ModOrganizer.exe`.

Make sure the dropdown box on the right is set to `Sovngarde` and press the Run button.

# Issues

If you find an issue, you can see if it is already on the list of [known issues](HELP.md), which also documents solutions and workarounds.

For issues that aren't yet [known](HELP.md), you can provide details in the [Sovngarde Github](https://github.com/Lost-Outpost/septimus/issues). Please provide as much info as you can (screenshots are great).

Finally, free feel to hop on the Sovngarde Discord support channel to have discussions with our knowledgeable community members. Support is offered in [The Lost Outpost](https://discord.gg/WF66mMu).

