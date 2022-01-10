<a href="https://www.youtube.com/watch?v=70DZ5UV1Bdo"><img src="images/banner.webp" target="_blank"></a>

---

<p align="center">
  <a href="https://www.nexusmods.com/skyrimspecialedition/mods/58229">Nexus Page</a> ·
  <a href="README.md">Installation</a> ·
  <a href="GAMEPLAY.md">Gameplay Guide</a> ·
  <a href="CONFIGURATION.md">Configuration</a> ·
  <a href="CHANGELOG.md">Changelog</a> ·
  <a href="ADDONS.md">Add-ons</a>
</p>

---

# Configuration

- [Mod Organizer 2 Profiles](#mod-organizer-2-profiles)
- [Creation Club Setup](#creation-club-setup)
- [Alternate Start](#alternate-start)
- [Optional Tweaks](#optional-tweaks)
- [Optional Content](#optional-content)
  - [Widescreen](#widescreen)
- [Mod Configuration](#mod-configuration)
  - [MCM Menus](#mcm-menus)
  - [TK Dodge RE](#tk-dodge-re)
- [ENB and Reshade Presets](#ENB-and-Reshade-Presets)
- [Performance Guide](#performance-guide)

## Mod Organizer 2 Profiles

Two profiles are pre-configured in MO2 for you. Septimus - Anniversary Edition and Septimus. If you do not own anniversary edition and all creation club content, play the standard Septimus profile. It contains all mods that do not require creation club integration.

Select the profile you wish to use here:

![Profiles](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/profiles.png)

## Creation Club Setup

In order to use Creation Club content, Mod Organizer 2 will need a copy of the creation club mod files.

- Launch the game from steam and allow all creation club content to download
- Activate the Anniversary Edition profile in Mod Organizer 2 at the top of the window
- Right click `[NoDelete] Official Creation Club - Paid` at the top of the mod list and hit open in explorer
- Copy all files from Skyrim Special Edition/data beginning with "cc" (example: ccvsvsse004-beafarmer.bsa) into the opened folder
- Ensure that all creation club content is activated in the "Plugins" tab on the right of mod organizer 2 and moved to the top of the load order
- If it is not all activated and sent to the top, shift click to select all, right click and hit enable selected, and then right click and hit send to -> top

When you have setup Creation Club content correctly, your Septimus MO2 will look like this:

![CC Top](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/ccenabled_top.png)

## Alternate Start

- Septimus is configured with optional alternate start mods which you can enable. If you do, be sure to move them in the right panel just above any patches which start with Septimus - as seen in the screenshot below.
- If you enable Live another life, be sure the esp files (in the plugin tab on the right of mo2) are loaded in the exact order shown in the screenshot below or it may not function properly

![Exe List](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/altstartloadorder.png)

## Optional Tweaks

When enabling any optional tweaks, make sure they are always loaded BEFORE any Septimus patches in your load order. See the alternate start section for an example of this.

### Widescreen

I have included the necessary mods to enable widescreen UI support. If you play on a widescreen monitor, this can be enabled in the optional mods section.

![Widescreen](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/widescreen.png)

## Optional Content
**As a warning. The optional content has not been tested nearly as heavily as the rest of the list as not everyone has it enabled. Support will be limited if you enable any of the optional content as its more difficult to account for them. If you are at all worried about stability, do NOT enable any.**

### General Rules
When enabling this content, just like with alternate start mods, ensure all mod esp files are above and Septimus - (Patch) files in your load order and if there is a Septimus patch for them, load that after the mod's esp and above all other Septimus patches. This applies for any optional content not specifically mentioned here. For content with its own section, follow the appropriate readme section for it.

### Legacy of the Dragonborn
Once enabled, place the patches as shown in the following screenshots

+ Legacyofthedragonborn.esm should be dragged to the top of the load order (dragging it at all will trigger this automatically)
+ LOTD Patches beginning with LOTD_TCC or DBM should go here just after the Literally Unplayable Patches and above any Septimus patches

![LOTD Patches](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/dbm_patches.png)

+ The LOTD Occlusion Patch should go here with the rest of the occlusion patches

![LOTD Occlusion](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/lotd_occ.png)

+ The LOTD Septimus patch should go here just before the conflict resolution patch

![LOTD Septimus Patch](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/lotd_sep_patch.png)

## Mod Configuration

### MCM Menus

All MCM menus have been automated so you are good to ignore them unless you want to change anything.

### TK Dodge RE

If you wish to change the dodge key, do the following:

- Double click on the TK Dodge RE mod in SEPTIMUS - SKELETON & ANIMATION
- Navigate to the ini files tab
- Change EnableTappingDodge to false to change the keybind
- Change DodgeHotkey to your prefered one by using instructions [here](https://www.creationkit.com/index.php?title=Input_Script#DXScanCodes)

## ENB and Reshade Presets

Septimus includes an awesome tool called ENB Organizer for trying out different ENB and Reshade presets.

To change ENB & Reshade presets, do the following:

- Run ENB Organizer from the exe list in the top right of MO2
- If the program warns about not being able to check for updates, simply click ok and ignore it

![Exe List](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/exe_menu.png)

- Go to presets on the left menu and enable the enb preset you wish to use. Be sure to only enable one preset at a time. The safest way is to disable them all and then simply activate one preset. Mixing presets (including mixing ENB and Reshade presets) will not work.

![Enb Organizer](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/enb_enable.png)

- Low spec users or first time players may want to stick with the default (Davinci Reshade) profile to start

## Performance Guide

- Try turning off any ENB that might be enabled and switching to the ultra lite reshade preset
- Activate the performance grass and dyndolod mods under Septimus - Performance Mode
- Copy the files from one of the presets in Septimus/Performance Options to the profile you're using and overwrite (Septimus/profiles/Septimus [- Anniversary Edition])

![Perf Options](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/perf_options.png)
![Perf Options 2](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/perf_options2.png)
![Perf Options 3](https://raw.githubusercontent.com/Guitarninja2/septimus/main/images/perf_options3.png)
- Double click on `SSE Display Tweaks - Septimus Settings` under `Essentials` and set the resolution to match your monitor resolution and remove the # at the beginning of the line

**NOTE: I cannot provide support for a game which has been tweaked for performance due to the high possibility of user error here. If you have attempted the performance guide and are having issues with it I cannot help, sorry.**
