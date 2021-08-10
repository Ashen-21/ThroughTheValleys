# Through The Valleys - Wabbajack port <!-- omit in toc -->

## MODLIST SUMMARY <!-- omit in toc -->

Through The Valleys is a vanilla plus modlist in the style of Viva New Vegas, based off of PushTheWinButton's guide of the same name. The list focuses on stability, performance, and more balanced gameplay. Those interested in playing through Oblivion with more difficult gameplay and nicer, but still lightweight and vanilla like visuals should check this list out.

Check out the original guide(https://www.nexusmods.com/oblivion/mods/51105?tab=description)!

**DO NOT DM ME ASKING FOR SUPPORT, YOU WILL BE BLOCKED. ASK IN THE APPROPRIATE CHANNELS.**

## TABLE OF CONTENTS <!-- omit in toc -->
- [REQUIREMENTS](#requirements)
- [PREPARATION](#preparation)
  - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
  - [Uninstalling the game](#uninstalling-the-game)
  - [Making a new Steam Library](#making-a-new-steam-library)
  - [Set the Game language to English](#set-the-game-language-to-english)
  - [Remove High Resolution Texture Pack DLC](#remove-high-resolution-texture-pack-dlc)
  - [Remove Creation Club Content](#remove-creation-club-content)
  - [Pre Modlist Installation Instructions](#pre-modlist-installation-instructions)
- [MODLIST INSTALLATION](#modlist-installation)
  - [Modlist Installation Instructions](#modlist-installation-instructions)
  - [Post Installation Instructions](#post-installation-instructions)
- [UPDATING](#updating)
- [FREQUENTLY ASKED QUESTIONS](#frequently-asked-questions)
- [CREDITS AND THANKS](#credits-and-thanks)

## REQUIREMENTS

* Latest version of [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases/latest).
* A clean **English** installation of Oblivion, and all DLCs **INCLUDING** the official plugins (Houses, spell tomes, etc.)
  * Also known as Oblivion GOTY Deluxe Edition.
  * **Acquired through [Steam](https://store.steampowered.com/app/900883/The_Elder_Scrolls_IV_Oblivion_Game_of_the_Year_Edition_Deluxe/).**
  * The GOG version should work as well, but it has not been tested as of this moment.
* Around 11-12 GB of free space.
  * 6 GB for Oblivion itself.
  * 1.6 GB for the mod downloads.
  * 3.3 GB for the modlist installation.
* A [Nexusmods](https://www.nexusmods.com/) account.
  * Nexus Premium is not necessary, but will help to download the modlist faster.

## PREPARATION

These steps are only needed if you install this Modlist for the first time. If you are updating the Modlist, jump straight to [UPDATING](#updating).

### Installing Microsoft Visual C++ Redistributable Package

You likely already have this installed, but in case you haven't. This package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

### Uninstalling the game

If you have the game installed under `C:\Program Files\`, `C:\Program Files (x86)\`, your Desktop, or your Documents folders, follow these steps to remove it.

1. Open **Steam** and go to your **Library**.
2. Find **Oblivion** in the list.
3. Right-click on it and select **Manage** -> **Uninstall**.
4. Navigate to `Steam\steamapps\common\` and, if present, delete the **Oblivion** folder.

### Making a new Steam Library

If you already have a Steam library set up outside of any default Windows folder, skip this step.

A new Steam library needs to be set up to install the game on, as the default library is in a default Windows UAC-protected folder (`C:\Program Files (x86)\Steam`).

1. Open **Steam** and select **Steam** -> **Settings** in the top left.
2. In the **Downloads** tab, select **Steam Library Folders**.
3. Select **Add Library Folder** and select a location outside of any default Windows folders.
   * For example, `C:\Games\Steam`.
4. Exit out of the settings when you are finished.

By default, Steam only allows one library per drive, but there is a workaround. If for example you already have the default Steam library at `C:\Program Files (x86)\Steam`, but still want your game on your `C:\` drive, you will need to follow [these instructions](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to do so.

### Set the Game language to English

This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and support will not be given to people with a non-English game.

1. Open **Steam** and go to your **Library**.
2. Find **Oblivion** in the list.
3. Right-click on it and select **Properties...**.
4. Click on **Language** and select **English** from the dropdown menu.

### Pre Modlist Installation Instructions

1. Navigate to **Documents\My Games\\** and if present, delete the **Oblivion** folder.
   * This will delete all saves you have, but the modlist requires you to start a new game anyway.
   * If you want to keep your saves, delete all files ending in ***.ini**.
2. Navigate to your Oblivion installation folder.
3. Run **OblivionLauncher.exe**.
4. Click OK to both pop-ups that say **Detecting Video Hardware**.
5. Select **Options** then select the **Ultra** preset option.
   * I personally don't notice a difference between High and Ultra, do with this what you will.
6. Set the **Resolution** option to your preference.
7. Click **OK** then **Exit**.

## MODLIST INSTALLATION

### Modlist Installation Instructions

1. Download the latest version of Wabbajack.
2. Create a new folder anywhere that is **NOT** under C:\Program Files, C:\Users or C:\Windows.
3. Place the downloaded Wabbajack.exe into this folder.
4. Download the latest [Wabbajack file](https://drive.google.com/file/d/1IEVpVQtQ2Ysu3Yb4rK0TPsDM2nvqjveG/view?usp=sharing) of this modlist.
5. Run **Wabbajack.exe**.
6. Select **Install From Disk**. Click on **···** next to **Target Modlist** to browse for the downloaded modlist.
7. In **Installation Location** select an empty folder that is **NOT** under C:\Program Files, C:\Users or C:\Windows.
   * Do **not** install this list in your **Steam**, **Oblivion** folder or the folder with **Wabbajack.exe**.
8. The downloads location will auto-populate. This can be changed if preferred.
9.  Click the button with the Play Arrow to begin the process.
10. Accept the Nexusmods API request if asked.
11. Wabbajack will now automatically download and install every necessary mod.
    * If you don't have Nexus Premium, you'll have to manually click download for all the mods, but Wabbajack will still install them.
12. When Wabbajack completes you will see either a green **Installation Complete** screen or a red **Installation Failed** screen. If successful, proceed.

### Post Installation Instructions

1. Navigate to the Through The Valleys installation folder.
2. Open the folder named **Game Folder Files**.
3. Copy all files in this folder and paste it into your Oblivion installation folder.
   * **COPY _ONLY_ THE FILES IN THE "GAME FOLDER FILES" FOLDER.**
   * If asked, let it overwrite everything
   * Run "4gb patch.exe", patch both Oblivion.exe and OblivionLauncher.exe

### Playing The Game

1. Launch Mod Organizer 2 from the Through The Valleys Installation Folder.
2. In the drop-down menu on the right, select "Oblivion.exe"
    * DO NOT RUN OBLIVIONLAUNCHER, OR OBSE. OBLIVION.EXE WILL LOAD ALL IT NEEDS FOR YOU TO PLAY.
4. Press Run!
5. Optionally, with Oblivion.exe selected, click shortcut and then desktop. This way you can launch Oblivion without running MO2.
    * Reccommended(https://www.nexusmods.com/oblivion/mods/46446)

## LOD
I have now added generated LOD along with some VWD files. The LOD is disabled by default, as it *will* cause performance drops on most PCs. Oblivion is old and crusty, that's just the way it works. If you struggle to maintain 60 fps, I would not reccommend enabling it. On the other hand if you don't mind losing a few frames to enjoy some pretty architecture from a far, enable LOD (Experimental) in the left pane.


## In game settings

Most of the in game settings work fine as are. I do however reccommend setting your view distance to maximum so you can actually see and enjoy the LOD. Makes a huge difference IMO. Otherwise, do not turn Self Shadowing on. This setting is buggy and will cause your NPCs to have neck seams.

## Mods To Be Familiar With

Ascension(https://www.nexusmods.com/oblivion/mods/50237)
Ascension totally overhauls the game to be more balanced as well as more difficult. Health is determined solely by endurance. Magicka and fatigue regenerate slower. You can carry less based on your strength. I highly reccommend reading the full log of all the changes in this mod.

Balanced Unleveled Rewards(https://www.nexusmods.com/oblivion/mods/51050/)
Balanced unleveled rewards (as well as Balanced NPC level cap) remove the dynamic level scaling from the game and replace it with a more sensical static rebalance of items.

Oblivion DLC Delayers(https://www.nexusmods.com/oblivion/mods/47089)
Avoid a deluge of quest popups upon entering Cyrodiil. Check this page to learn how to start each DLC (including house dlcs).

Simple Saves Plus(https://www.nexusmods.com/oblivion/mods/51122)
Completely replaces the vanilla autosave system. Force an autosave using a hotkey, default is numpad 0.

Simple Horse Utilities(https://www.nexusmods.com/oblivion/mods/51197)
Adds a spell that lets you call your horse, as well as adds saddlebags (Sneak and interact with horse to open).

Teleportation Services(https://www.nexusmods.com/oblivion/mods/50141)
Ascension removes the vanilla fast travel points available to you at the beginning of the game, but fear not as Teleportation Services have you covered. Adds teleporation (for a fee) at the Mages Guild and Nine Divines Wayshrines.

## UPDATING

When this Modlist receives an update, please check the Changelog before doing anything. Always backup your saves. Start a new game after updating, if noted in the Changelog.

**Wabbajack will delete all files that are not part of the Modlist when updating!** This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

You can circumvent this behavior by renaming the mod with the prefix **[NoDelete]**.

Updating is the same as installing. You only have to make sure that you select the same path and tick the **Overwrite Existing Modlist** checkbox in Wabbajack.

## CREDITS AND THANKS

* _YOU_ for actually reading the readme!
* Qolore for the creation of VNV and inspiring Vanilla+ mods community wide
* PushTheWinButton for the original mod guide (and about half the mods in this list), be sure to endorse it on Nexus
* TDarkShadow for his support in my endeavours
* Kaethela and SOVN for the basis of this readme
* ALL the mod authors that made the mods featured in this list.
* Halgari and everyone in the Wabbajack Team.

## PERMISSIONS

This modlist is based off of PushTheWinButton's original work, and all permission to modify/fork the list must be sought from him.
All mods featured in this modlist belong to their original creator.
The wabbajack file is subject to the terms set forth by the Wabbajack developers, and as such will forever and always be *completely free*.

##### This readme is based off of [Viva New Vegas's Readme](https://github.com/TDarkShadow/vivanewvegas-wabbajack/blob/master/README.md), [Starstruck Courier's readme](https://github.com/Kaethela/Starstruck-Courier/blob/main/README.md) and [Qwest's readme](https://github.com/SovnSkyrim/QWEST/blob/main/README.md). <!-- omit in toc -->
