

# Messy Milkshake

-
  - [Preface](#preface)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
      - [Change Steams Update Behavior](#change-steams-update-behavior)
      - [Clean Skyrim](#clean-skyrim)
      - [Start Skyrim](#start-skyrim)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
      - [Downloading and Installing](#downloading-and-installing)
        - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Stock Game](#stock-game)
    - [ENB](#enb)
  - [How to start up Messy Milkshake](#how-to-start-up-MessyMilkshake)
  - [Updating](#updating)
  - [Creating your Character](#creating-your-character)
  - [In-Game MCM Options](#in-game-mcm-options)
  - [Other Post Installation FAQ](#other-post-installation-faq)
    - [Removing the Modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)
  - [Changelog](#changelog)

## Preface


## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2, and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right-click the game in your Library->Properties), navigate to the _General_ tab, and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Change Steams Update Behavior

Bethesda is still updating SSE (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically update the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. It would be best if you also disabled the Steam Cloud while you're at it.

Another problem with Steam is that if you have it installed with it's suggested paths, your first Steamlibrary will be in your Program Files folder which is a protected folder. Moving your Steamlibrary out of your Program Files folder is a key setup for a working modded experience. If you are having trouble doing so check [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide).

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting its contents.

#### Start Skyrim

After you have done everything above and got a clean SSE installation-ready, start the Launcher and let it do the initial graphics check. Do not worry about this part as the installation will replace these graphics settings. Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads, or Program Files folder. It's best to create a Wabbajack folder near your drive's root level like `C:/Wabbajack.`

#### Downloading and Installing

The download and installation process can take a very long time, depending on your system specs. Wabbajack will calculate the number of threads it will use at the start of the installation. To have the highest amount of threads and fastest speed, it is advised to place the working folder on an SSD.

1. Open Wabbajack.
2. Click Browse Modlists and download Elysium from the Modlist Gallery. Wait until you are forwarded to the next window.
3. Adjust the download and installation paths. The recommended Installation Path is a blank folder at the root of a drive, such as C:\Elysium. The Download Path will update automatically. You can move it elsewhere if you want.
4. Click the Go/Begin button.
5. Wait for Wabbajack to finish.

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off, so you lose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case, just wait until I update the Modlist.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

## Post-Installation

### Stock Game

Unlike regular Skyrim installation or other Wabbajack lists, Messy Milkshake comes with the **Stock Game Feature** which is a copy of a Skyrim installation located within your installation folder, cleaned, and with everything you need to start playing now. 

It allows you to not worry about conflicting files with Vortex or other Wabbajack lists. Therefore, after Wabbajack completes, you don't need to move anything to your regular Skyrim installation. 

### ENB



A few other ENB suggestions are:

- [Ljoss](https://www.nexusmods.com/skyrimspecialedition/mods/30971)
- [Silent Horizons](https://www.nexusmods.com/skyrimspecialedition/mods/21543)
- [Serio's ENB](https://www.nexusmods.com/skyrimspecialedition/mods/30506)
- [Soul Spectrum ENB](https://www.nexusmods.com/skyrimspecialedition/mods/29675)

**Note:**
Please check that vsync is set to disable in enblocal.ini otherwise you will either be stuck compiling shaders or a black screen, or the menu with no options.

## How to start up Messy Milkshake 

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once it is launched, there will be a dropdown box on the top right and a big run button right next to it. Ensure it is set to MM [SKSE] by selecting it in the dropdown box and then hitting the run button. You have to run MM [SKSE] through Mod Organizer 2 in order to play MM from now on.

## Updating

If this Modlist receives an update, please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## Noteworthy Mods
True Directional Movement makes combat and movement so much better 
CBBE godly texture for females 








### Removing the Modlist

You can remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder, so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a lot!!
- Phoenix and her team - for creating this excellent guide and allowing me to create this fork.
- Halgari and everyone in the WJ Team - Wabbajack is incredible, and so are you!
- Titansbane for the base of this read me i yoinked it ty good sir 
## Contact

My Discord name is Beep#1930 feel free to message or ping



## Licenses


***

[[Back to top]](#elysium)
