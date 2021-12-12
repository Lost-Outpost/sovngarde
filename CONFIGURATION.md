<a href="https://www.youtube.com/watch?v=70DZ5UV1Bdo"><img src="images/banner.webp" target="_blank"></a>

---

<p align="center">
  <a href="https://www.nexusmods.com/skyrimspecialedition/mods/58229">Nexus Page</a> ·
  <a href="README.md">Installation</a> ·
  <a href="GAMEPLAY.md">Gameplay Guide</a> ·
  <a href="CONFIGURATION.md">Configuration</a> ·
  <a href="CHANGELOG.md">Changelog</a>
</p>

---

# Configuration

- [Mod Organizer 2 Profiles](#mod-organizer-2-profiles)
- [Creation Club Setup](#creation-club-setup)
- [Optional Mods](#optional-mods)
  - [Widescreen](#widescreen)
- [Mod Configuration](#mod-configuration)
  - [MCM Menus](#mcm-menus)
  - [TK Dodge RE](#tk-dodge-re)
  - [ENB Presets](#enb-presets)
- [Performance Guide](#performance-guide)

## Mod Organizer 2 Profiles
Two profiles are pre-configured in MO2 for you. Septimus - Anniversary Edition and Septimus. If you do not own anniversary edition and all creation club content, play the standard Septimus profile. It contains all mods that do not require creation club integration.

## Creation Club Setup
In order to use Creation Club content, Mod Organizer 2 will need a copy of the creation club mod files. 
+ Launch the game from steam and allow all creation club content to download
+ Activate the Anniversary Edition profile in Mod Organizer 2 at the top of the window
+ Right click [NoDelete] Creation Club at the top of the mod list and hit open in explorer
+ Copy all files from Skyrim Special Edition/data beginning with "cc" (example: ccvsvsse004-beafarmer.bsa) into the opened folder
+ Ensure that all creation club content is activated in the "Plugins" tab on the right of mod organizer 2 and moved to the top of the load order
+ If it is not all activated and sent to the top, shift click to select all, right click and hit enable selected, and then right click and hit send to -> top

## Optional Mods

### Widescreen
I have included the necessary mods to enable widescreen UI support. If you play on a widescreen monitor, this can be enabled in the optional mods section.

## Mod Configuration

### MCM Menus
All MCM menus have been automated so you are good to ignore them unless you want to change anything.

### TK Dodge RE
If you wish to change the dodge key, do the following:
+ Double click on the TK Dodge RE mod in SEPTIMUS - SKELETON & ANIMATION
+ Navigate to the ini files tab
+ Change EnableTappingDodge to false to change the keybind
+ Change DodgeHotkey to your prefered one by using instructions [here](https://www.creationkit.com/index.php?title=Input_Script#DXScanCodes)

### ENB Presets
To change ENB presets, do the following:
+ Run ENB Organizer from the exe list in the top right of MO2
+ If the program warns about not being able to check for updates, simply click ok and ignore it

![Exe List](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/exe_menu.png)

+ Go to presets on the left menu and enable the enb preset you wish to use. Be sure to only enable one preset at a time. The safest way is to disable them all and then simply activate one preset.

![Enb Organizer](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/enb_enable.png)

+ Low spec users or first time players may want to choose the Cathedral Minimalist profile to start

## Performance Guide
+ Try turning off any ENB that might be enabled and switching to the ultra lite reshade preset
+ Activate the performance grass and dyndolod mods under Septimus - Performance Mode
+ Replace the files in the profile you're playing (Septimus/profiles/Septimus [- Anniversary Edition]) with [these](https://www.nexusmods.com/Core/Libs/Common/Widgets/DownloadPopUp?id=248298&game_id=1704)

### Extreme Performance (Potato Mode)
+ Turn off No Grass In Objects (Both versions)
+ Turn off enb and reshade
+ Open Bethini in Septimus/Tools/Bethini (Make sure MO2 is closed) and try changing the preset for the activated profile to low or tweaking values

### BethINI Settings (Try Performance INIs First)
+ Make sure to close Mod Organizer 2
+ Open BethINI under (Your Install Folder)/Tools/BethINI 3.5/BethINI.exe
+ Be sure to choose the correct profile you are playing under the Setup tab

![BethINI Setup](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/beth_setup.png)

+ On the basic tab, select the preset you wish to use and checkk `Recommended Tweaks`

![BethINI Basic](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/beth_basic.png)

If you are having serious performance troubles and you wish to gain some extra frames, you can use [this](https://thephoenixflavour.com/tpf/performance-guide/) guide to tweak some settings for better performance.

**NOTE: I cannot provide support for a game which has been tweaked for performance due to the high possibility of user error here. If you have attempted the performance guide and are having issues with it I cannot help, sorry.**
