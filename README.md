# Ruvaak

Wabbajack Modlist Installer for Skyrim Special Edition with the **paid Anniversary Edition DLC** by Styyx

![Ruvaak-banner](https://github.com/chri3i/Ruvaak-Readme/blob/main/.github/RuvaakTitleResized.png)

<table stlyle="border: none;">
<tr>
<td><img src="https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>    
<td><img src="https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/GitHub.png" width="72px" /></td>
<td><a href="https://discord.gg/DffHKcszfg">Support Discord</a></td>
</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Contents
  - [Preamble](#preamble)
  - [System Requirements](#system-requirements)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
    - [Wabbajack Installation](#wabbajack-installation)
      - [Installing Wabbajack](#installing-wabbajack)
      - [Downloading and Installing Ruvaak](#downloading-and-installing-ruvaak)
      - [Beta Install](#beta-install)
      - [Problems with installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Game Folder](#game-folder)
    - [BethINI](#bethini)
    - [ENB](#enb)
    - [Optional Mods](#Optional-mods)
  - [Playing the List](#playing-the-list)
    - [Starting up the list](#starting-up-the-list)
    - [In Game MCM Options](#in-game-mcm-options)
    - [Starting the Game](#starting-the-game)
  - [Updating Ruvaak](#updating-the-modlist)
  - [FAQ](#faq)
    - [BA Alchemist Arsenal](#ba-alchemist-arsenal)
    - [Controller Setup](#controller-setup)
    - [Ultrawide Options](#ultrawide-options)
    - [Overpowered Enemies](#overpowered-enemies)
    - [OP Loot](#op-loot)
    - [Survival Mode](#survival-mode)
    - [Can't hit friendly NPCs?](#cant-hit-friendly-npcs)
    - [Equipment is too weak](#equipment-is-too-weak)
    - [Help, my gear broke](#help-my-gear-broke)
    - [TK Dodge Keybinds](#tk-dodge-keybinds)
    - [Power Attacks](#power-attacks)
    - [Can't open Locks](#help-i-cant-open-locks)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
    - [Zoomed in Display](#zoomed-in-display)
    - [Modifications](#modifications)
   - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Known Issues](#known-issues)
  - [Found a bug](#I-found-a-bug)
  - [Changelog](#Changelog)

## Preamble

> "You are not alone. Remember this the next time you wander the harsh, frozen lands of Skyrim. Many have tried --and failed-- to discover what lurks out there, in the mists, and many will after you are gone. Tell me, do you have what it takes to survive?"

Ruvaak is a list focused on making Skyrim: Anniversary Edition (AE) into a dark fantasy roleplaying game. Many new mechanics and changes are present to offer an alternate take on the game. You can view many of these changes in the [Changes to Gameplay](https://github.com/chri3i/Ruvaak-Readme/blob/main/changes%20to%20gameplay.md) article and DroppedIceCream's showcase below.

[![Ruvaak Showcase](https://img.youtube.com/vi/KY1qEnkNpzM/0.jpg)](https://www.youtube.com/watch?v=KY1qEnkNpzM)

# <ins>**Ruvaak requires the *full* AE upgrade, which means you must *purchase* the AE edition of the game for the list to function.**</ins>

Mods to familiarize yourself while with the downloads are running:
- [Synergy](https://www.nexusmods.com/skyrimspecialedition/mods/72352), which makes the first perk of a skill probably the most most important one. Without the first perk you can't use crafting furniture like ``Forges or Armor Tables`` and your magic requires an absurd amount of magicka, to name a few examples.
It also disables EXP gain on the perks you don't have put any perk points into. 
- [ADXP/MCO](https://www.skyrim-guild.com/distars-mods/adxp-mco) combat animations will require you to commit to your attacks and have many more combinations for chained attacks.
- [Rogue Like Encounters](https://www.nexusmods.com/skyrimspecialedition/mods/23872) This mod spawns some creepy and some pretty powerful enemies alongside --or instead of-- vanilla enemies to spice up the gameplay a bit. Don't shy away from fleeing if some enemies are a bit too much. The mod does more than just spawning enemies, as well. You'll see a few powers in your character's magic menu after starting the game. One of them is trap crafting. Explore it as you might need it later on.
- For player homes please refer to [the list of player homes](https://github.com/chri3i/Ruvaak-Readme/blob/main/Ruvaak%20Player%20Homes.md)
- Some noteworthy mods without going into more detail [Darkend](https://www.nexusmods.com/skyrimspecialedition/mods/10423), [Clockwork](https://www.nexusmods.com/skyrimspecialedition/mods/4155), [The Sinister Seven](https://www.nexusmods.com/skyrimspecialedition/mods/19178), [The Shadow of Meresis](https://www.nexusmods.com/skyrimspecialedition/mods/38167) and [Blackreack Railroad](https://www.nexusmods.com/skyrimspecialedition/mods/435)
- The full list of mods in Ruvaak can be viewed [here](https://loadorderlibrary.com/lists/ruvaak-1)

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

Ruvaak is aimed at mid tier machines so a system like the following is advised:

### 1080p (my specs)
- CPU: AMD Ryzen 7 3700X
- RAM: 16GB DDR4
- Drive: SSD
- GPU: NVIDIA GeForce RTX 3070 8GB

It will prob run good on lower specs as well but I recommend at least 6GB VRAM (GPU)

**I can only answer performance questions about my specs as I don't have different systems flying around to check!**

Space required: 
- Approx 190GB (Downloads included) + 20-30GB space for temp files
 
Size without downloads and space for temp files: 
- Approx 112GB

## Installation

Installing Ruvaak is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing Ruvaak, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe)
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside /Documents/My Games/.
4. Reinstall Skyrim into a location that is not Program files. Somewhere like C:\Games is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
6. You also need to start the game to the main menu in order to download all the creations

# Step 3 and 4 are only necessary if you modded the game without 'stock game' and cleaned the master files


### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing Ruvaak

Downloading and installing Ruvaak can take a while depending on your internet connection and computer. To install Ruvaak, complete the following steps.

1. Open Wabbajack and click on ``browse modlists``
2. Press the download button on Ruvaak and wait for it to download.
3. Set the installation folder to be somewhere like C:\Games\Ruvaak. **Do not install it to your desktop, downloads folder or Skyrim's game folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster. You can also have a shared download folder across all Wabbajack lists on a different drive than the install drive.
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

#### Beta Install

- To install a beta version of the list (I might publish updates as an open beta first to ensure stability with the main release) refer to the [beta install instructions](https://github.com/chri3i/Ruvaak-Readme/blob/main/.github/Beta%20Release%20instructions.md)

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

- **Problematic Files**:
	- [NFAC - AE](https://drive.google.com/u/0/uc?id=1C-Hdm1eoA_Tsj1Tik7VZxXFN3fbwXVEi&export=download)

## Post-Installation

### Game Folder

Ruvaak uses a Wabbajack feature called Stock Game to keep your Skyrim installation clean. All the files that you need to run the list are in a folder called “Game Root”. You don’t need to copy anything at all.


### ENB

Ruvaak comes already set up with [E.V.C. ENB](https://www.nexusmods.com/skyrimspecialedition/mods/71743) for Aequinoctium Weathers. In the executables drop down menu in MO2, you will find an ENB Organizer that provides you with **a few** options. Depending on your PC you might want to check them out. All of them are kind of dark, fitting for the theme i was going for, except the new default one. If you want to install your own ENB put them into a seperate folder in Ruvaak/tools/Enb Manager/Managed ENB. You need to manually add them in the ENB Manager program afterwards. Click on Skyrim --> Go to the preset Tab --> Add preset.\
Take a look at [ENB Organizer](https://www.nexusmods.com/skyrim/mods/67077) for more information.

### Optional Mods

In your MO2 window you will find a seperator called 'Optional Mods' mods within this seperator are save to activate mid game unless stated otherwise. Removal of them is not adviced mid game.
- A few music mods. They can be enabled/disabled at any time, feel free to try them.


## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `Play Ruvaak` and press the run button.


### In-Game MCM options

Almost all of the MCM options are automatically configured for you already. Wait until all notifications on the top left are gone before opening the MCM. 
**Failing to do so will cause quite a few issues later on and will require you to start a new save.** 

Note that all keybinding are set to my liking for a **Gamepad**. I do not know the keyboard and mouse settings as I don't use it for playing. 
There are a few ini files you want to check for keybinds like: 
- TK Dodge RE
- Elden Power Attack

You can tweak the MCMs to your liking like:

- Animated Potions
- Combat Difficulty Customizer (again, default profile is loaded but if the game is too hard/easy you can tweak stuff there)
- Conner's Survival Mode
- Dynamic Weather Detection
- Dynamically Darker Dungeons
- Extended Encounters
- Lucien (If you set a supported nickname, he will call you by that)
- SkyUI
- Precision
- Swiftly Order Squad (hotkey is set for gamepad so you need to change that for kb&m; D-Pad right is the default key on Gamepad)
- I recommend to look at 'Breakable Equipment' to flag any lantern as unbreakable

Afterwards, activate ``Shadow of Skyrim`` in its MCM by **clicking into the general tab** and adjust to your liking.
![SOS General Page](https://github.com/chri3i/Ruvaak-Readme/blob/main/.github/ShadowOfSkyrimGeneralPage.png)

I highly recommend turning off ``Nemesis uses Gear`` in order to not get your stuff taken away by a despawning enemy.
![SOS Defeat Page](https://github.com/chri3i/Ruvaak-Readme/blob/main/.github/ShadowOfSkyrimDefeatPage.png)

Ruvaak also makes use of a few GUI menus:

- [CatHub](https://www.nexusmods.com/skyrimspecialedition/mods/65958) allows you to customize kill moves and chances for kill moves. Key ``ctrl + NumPad . (, for German keyboards)``
- [Immersive Equipment Distplay](https://www.nexusmods.com/skyrimspecialedition/mods/62001) allows you to show equipment on your character. Key ``left ctrl + Backspace``
- [QUI](https://www.nexusmods.com/skyrimspecialedition/mods/65343?tab=files) is basically AddItem Menu. I don't suggest using it unless you know which items are definitely safe to take. Key ``F11``
- ENB to adjust visuals and many effects. Only use it when you know what you're doing. Key ``shift + enter``
- [PlayerStats](https://www.nexusmods.com/skyrimspecialedition/mods/67622) allows you to see Actor Values, such as Negative Resistances gained from eating alchemical ingredients, Attributes (current and max), etc using the ``NumPad Enter`` key. 

### Starting the Game

- I added a bunch of character presets for you to create your character off of. The folder system does not work with a controller but you can switch to your mouse on without disabling the controller anyway.
- You will start in a strange place called 'the Realm of Lorkhan' feel free to explore this area for any goods and standing stones. There are boons and class shrines there as well but note that there is no way of removing the boons and curses as of now so make a save before picking one!

### Immersive Equipment Display Presets

Once you've done all that, click ``left CTRL + Backspace`` and IED's UI shall appear. Follow the instructions in the following pic to load the presets.
![IED instructions](https://github.com/chri3i/Ruvaak-Readme/blob/main/.github/RuvaakIEDinstructionsNew.png)

- After you have loaded **both** you're good to go. 

**Note that there will most likely still be clipping but adjust positions as you like it.**


## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ

### BA Alchemist Arsenal

You need to be level 5 and open the crafting kit to use this. Check out the [modpage](https://www.nexusmods.com/skyrimspecialedition/mods/42030) for more infos

### Controller Setup

Controller compatibility is turned on by default as Ruvaak uses a neat SKSE plugin called [Auto Input Switch](https://www.nexusmods.com/skyrimspecialedition/mods/54309) and therefor it won't interfere for anyone using keyboard and mouse for controls.
If you use a gamepad, however, you should make yourself familiar with the changed controls. Ruvaak uses [TUCS](https://www.nexusmods.com/skyrimspecialedition/mods/29381). If you don't like the control layout you can disable the mods under *Gamepad support* at any time/
Also if you use a gamepad, activate the mod 'Gamepad MCM' in the 'Gamepad' section in MO2. This ensures to load a profile for TUDM for controller compatibility.

### Ultrawide Options

I personally do not own an Ultrawide, so I cannot offer support. If you can set it up with the mods present in the list, please tell me how or make a pull request for this part of the readme and write it in here.


### Overpowered Enemies

Enemies are spawned from leveled lists which are semi-random. Ruvaak is not de-leveled but there are occasionally high level enemies in lower level areas. You can't defeat them at low levels. Try your luck later or use some strategies to overcome these hurdles. There are also some extremly powerful bosses scattered around the world. Those are meant for mid to high level characters. Avoid them as a low level character.

### OP Loot

There are some extremely powerful items in most of the dungeon boss chests. While I might make some adjustments, you can assume it's intentional. I want loot to feel rewarding. After all, there's a chance that you had some tough battles before getting to the chest.

### Survival Mode

While the list is made with Survival mode in mind, you will probably sometimes need to disable it to fully utilize the mods in the list (Underwater combat for example as most of the new underwater creatures are in the north and you'll freeze to death there when you swim)
It can be freely enabled and disabled in the settings menu whenever you want (just give it a few seconds to take effect) and don't rapid fire switch between Survival and non-Survival.

### Can't hit friendly NPCs?

The mod [No Follower Attack Collision](https://www.nexusmods.com/skyrimspecialedition/mods/65037) prevents you from hitting friendly NPCs and your followers. 
Usually a great mod, but in some situations you need to hit NPCs (Vilkas at the companions quest, for example) to turn it off temporarily, hit the ``ins`` key.
To change the hotkey for that change the key in the ``loki_NFAC.ini`` file. You get to this file by double-clicking the mod ``No Follower Attack Collisions``.
You can find the keycodes for Skyrim [here](https://www.creationkit.com/index.php?title=Input_Script).

### Equipment is too weak

Make sure you meet the requirements for the equipment you want to use. By default Ruvaak restricts certain equipments to specific skill levels.

### Help, my gear broke

If your equipment got damaged or destroyed, visit a blacksmith to temper it, or temper it yourself at the right crafting station for your equipment type.
Feel free to set the rate of your equipment degradation as high/low as you like it in the ``Breakable Equipment MCM``

### TK Dodge Keybinds

TK Dodge use an ini file to determine the dodge key. The ini file can be found within the mod ``TK Dodge - Gamepad`` and the available keys can be found [here](https://www.creationkit.com/index.php?title=Input_Script#DXScanCodes). It also uses the Sprint Key to dodge, in order to sprint, you need to press the key for longer than **0.3 seconds**

### Power Attacks

Power Attacks are performed with the help of [Elden Power Attack](https://www.nexusmods.com/skyrimspecialedition/mods/66711) and the keybinds for it are set in the Elden.ini in said mod. By default it uses the ``G`` key for kb&m and the ``LB`` key for gamepad

### Help I can't open locks 

Check out your Lockpicking perk tree. The perk mod is designed that way so you better spec into Lockpicking to get all the loot.

### Tweaking the Game Settings

#### BethINI

To get some more FPS, tweak the following value in the detail section in BethINI. You find BethINI inside the tools folder within the list installation folder

- `Shadow Resolution`: 2048
- `Ambient Occlusion`: Either use this or the ENB version. The ENB version is more intensive. Do not have both turned on.
- `Remove Shadows`: I really don’t recommend turning this on, but if you must then you can.

#### ENB

Ruvaak ships with an ENB setup that is configured to match the look of the list. If you wish to make some changes though, here are a few common tweaks. I recommend opening the console before doing edits.

##### Removing the letterbox (in general as the default ENB doesn't have that effect enabled)

1. Press [Shift+Enter] to open the ENB menu.
2. In the tab called Shader Parameters, select the `ENBPOSTPASS.FX` section. It will open once you click on it.
3. Scroll down until you see letterbox and untick it.
4. Press the save configuration button.
5. Press [Shift+Enter] to return to the game.

##### Turning off settings for FPS

If you are struggling for frames but want the colour correction and realism, turn off the following items.

- DetailedShadows
- ComplexFireLights
- ComplexParticleLights – Disable Big Range
- Reflection
- Complex Grass Collision
- Complex Grass

If you really cannot handle the ENB, uncheck `useEffect`.

### Zoomed in Display

This is caused by Windows display scaling feature. To fix this you can do either of the following.
- Set display scaling back to 100% in Windows screen resolution settings
- Edit SSE Display Tweaks ini file under Render
	- Fullscreen: `True`
	- Borderless: `False`
	
For further changes of the ENB please refer to [Anna's ENB Guide](https://github.com/The-Animonculory/Modding-Resources/blob/main/ENB%20Tips.md) but note, you are on your own with that cause neither I, nor Anna can provide any support for everyone who changes values in their ENBs
    
### Modifications
**Can I add? Is X compatible?**

In case you have questions like these, refer to the [modification page](https://github.com/chri3i/Ruvaak-Readme/blob/main/.github/Ruvaak_Modifications.md).<br > Note that you need to know a bit about modding to successfully change stuff. We have a general modding channel in our support server where you can talk about modifications.

## Removing the Modlist
Simply delete the folder and you have uninstalled it.

## Known Issues
- Before reporting any issues please refer to [Known Issues](https://github.com/chri3i/Ruvaak-Readme/blob/main/Known%20Issues.md) to see if your issue is mentioned there already. While i try to fix any issues that come up, I can't fix everything, please be patient.

## I found a bug

Go to the GitHub [Issues](https://github.com/chri3i/Ruvaak-Readme/issues) page and check if your issue was already reported. If you found no similar posts, create a new issue by clicking the green `New issues` button in the top right corner. Select `Bug report` and fill out the document.

## Changelog

For see what changes happened in each version please refer to the [Changelog](https://github.com/chri3i/Ruvaak-Readme/blob/main/Changelog.md). Please note that after a major version update (x.0.0), the changelog might not cover every change.


## Credits and Thanks

- _YOU_ for reading this.
- Althro for assisting with so many things. And allowing me to fork the readme. You’re awesome.
- Chef for the help with the armors and theory crafting random time sinks.
- Spaniard for being an invaluable source of knowledge and helping me a lot with the mod choices.
- Destiny for proofreading the readme and pointing out many errors. Also for testing the list and giving helpful suggestion to improve it.
- Astro for more help than I can list. Be it testing or suggestions, seriously, thanks a lot.
- Anna for adjusting the ENBs for Ruvaak even though they aren't used anymore.
- (A)SanguineAnarchy for beta testing the update and providing a ton of useful feedback.
- The Animonculory Dev Team.
- Noggog for Mutagen.
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you.

