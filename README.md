# Librum (for Skyrim VR)
Wabbajack modlist installer for Librum

- [Librum](#librum-for-skyrim-vr)
  - [Preamble](#preamble)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
        - [Set the Game language to English](#set-the-game-language-to-english)
        - [Clean Skyrim](#clean-skyrim)
      - [Start Skyrim](#start-up-skyrim)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
      - [Downloading and Installing](#downloading-and-installing)
        - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Copy "Game Folder Files"](#copy-game-folder-files)
    - [Starting Librum and Choosing Optional Plugins](#starting-librum-and-choosing-optional-plugins)
    - [Start Skyrim... again](#start-up-skyrim-again)
    - [MCM Settings](#mcm)
  - [Updating](#updating)
  - [Features of Librum](#features)
    - [Leveling and Experience](#leveling-and-experience)
    - [Survival and Realism](#survival-and-realism)
    - [Combat, Loot, and Challenge](#combat-loot-and-challenge)
    - [Magic](#magic)
    - [Quests and Adventures](#quests-and-adventures)
    - [Followers](#followers)
    - [Graphics and Ambience](#graphics-and-ambience)
  - [Getting Started in Librum](#getting-started-in-librum)
  - [Frequently Asked Questions](#frequently-asked-questions)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)
  - [Contributing](#contributing)
  - [Changelog](#changelog)
  - [Discussions](#discussions)
 
## Preamble

_You're lost in the woods, having narrowly escaped after scaring off a pack of wolves with a summoned flame atronach. Your torch finally fades out, and it's getting cold. You can conjure basic foods, and your summoned atronach provides enough heat for the time being, but you'll need to gather wood in order to sustain a fire and survive the night. With little time to spare, you can't search far for materials -- luckily, you've fashioned a basic hatchet the night before, and you can chop down a nearby tree for lumber. You fall asleep next to your fire, having placed several runes nearby to dispatch would-be predators. Despite a few interruptions in the night, the morning comes at last, and the sun finally breaks over the horizon._

Skyrim VR is a wonderful experience, but it's a very familiar one. Even in stunning 3D, we visit the same locales and repeat the same adventures we have since the end of 2011.

_Librum_ is a comprehensive gameplay, graphics, and content overhaul that attempts to change all of this. Combining together some of the best and most popular mods for Skyrim SE, a suite of new quests and adventures that outnumber Skyrim's own, the tradition of great "hardcore" gameplay overhauls that have come before -- like Skyrim's _Requiem_ and _YASH_ or Oblivion's _Oscuro's Oblivion Overhaul_ -- and a host of unique-to-VR immersion improvements, Librum brings new life (and new challenge!) to Skyrim in a way that has never been experienced before.

## Installation

Librum makes use of the excellent [Wabbajack](https://www.wabbajack.org/#/) program to make its installation as fast and painless as possible. That said, there are a few, very easy steps involved in setting up Librum. We will go over each in detail, but they are summarized as follows:

1. Clean your Skyrim folder and disable the Steam overlay.
2. Install the Wabbajack desktop client from [here](https://github.com/wabbajack-tools/wabbajack/releases).
3. Navigate to Librum under the _Browse for Modlists_ tab.
4. Install Librum to a new folder, outside of `Program Files`.
5. Copy the `Game Data Files` folder to your Skyrim VR directory.
6. Start a new game, and wait until mod installation notes finish appearing.
7. Configure the Mod Configuration Menu according to the [instructions that follow](#mcm).

### Pre-Installation

These steps are only needed if you are installing Librum for the first time. If you only want to update Librum, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

##### Set the Game language to English

Librum is entirely in English, as many excellent mods are English-exclusive. This may change in the future, but for now, I highly recommend playing the game in English.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

##### Clean Skyrim

If your Skyrim VR installation is not newly installed, I recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the `Skyrim VR` folder in `Documents/My Games/` by deleting the contents in it.

#### Start up Skyrim

After you have done everything above and have a clean Skyrim VR installation ready, start the Launcher and and let it do the initial graphics check. Do not worry about the graphics settings at this point, as the Librum installation will replace them. 
Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads, or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

#### Downloading and Installing

The download and installation process can take a very long time, depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack.
2. Download the modlist from [here](must update link) and choose the  _Install from Drive_ option in Wabbajack.
3. Once the download is complete, set the installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Program Files, or Desktop. Put it somewhere easy like `C:/Modlists/Librum`). The downloads path should automatically fill in the installation path.
4. Click the Go/Begin button.
5. Wait for Wabbajack to finish.
6. If you run into any issues, see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off, so you lose no progress.

***Could not download x***:

If a mod updated and the old files got deleted, it is impossible to download them. In this case, just wait until I update Librum.

***x is not a whitelisted download***:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

***Wabbajack could not find my game folder***:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

***Windows is reporting that a virus has been detected***:

Windows 10 has started to auto-quarantine the usvfs_proxy_x86.exe file from the latest version of Mod Organizer 2, saying a threat has been detected. This is a known false postive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. Example for Windows Defender can be found [here](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

### Post-Installation
Now that Librum is installed, it is time to start the game up for real and create your character. The character creation process has changed with Librum, so we will give details below. Moreover, it is highly recommended that you **configure the MCM after race selection** as described below.

#### Copy "Game Folder Files"
Navigate to the installed Librum folder, where you will find a folder titled `Game Folder Files`. Copy the contents of this folder to the Skyrim VR root folder.

#### Starting Librum and Choosing Optional Plugins
Navigate back to the installed Librum folder, and launch the program `ModOrganizer2.exe`. Before launching the game itself, take a look at the _Optional_ category at the bottom of the Mod Organizer 2 mod list. I will go over each below.

***End Times*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/39201)]. This plugin adds a sense of urgency to the Main Quest, and it ties in nicely with Librum's re-centering of Skyrim around being the Dragonborn. Specifically, if you do not defeat Alduin within a certain amount of time (365 days by default, but configurable in the MCM), he will swallow the world (accompanied by a nice visual), and you will have to reload and try again. You will have a _Doomsday Clock_ spell available, as well as configurable regular updates, to tell you how much time you have left.

If you do not want this plugin, disable it in MO2.

***Dragons from the Start*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/41453)]. This plugin enables dragon encounters from the very beginning of the game. This is highly recommended for Librum's Dragonborn-centric play, and it is especially important if you use the next optional plugin. 

If you do not want this plugin, disable it in MO2.

***No Perks on Level-Up***. This is a core feature of Librum, so it is highly recommended. With this plugin, you will no longer earn perks when you level up; rather, you will have to spend dragon souls in order to earn perk points. This accomplishes two things. First, along with other mods from the core modlist, this re-centers the Skyrim experience on you _actually being the Dragonborn_. You will not progress without hunting dragons and progressing the main quest. Secondly, this reframes the role of perks in the Librum experience. Because (especially at the beginning) they are much harder to obtain, they will form a much smaller part of your character's identity, and your character will spend a longer time being a "normal person".

If you do not want this plugin, disable it in MO2.

***High Fidelity ENB - LCD vs OLED*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/27308)]. Librum makes use of the excellent _High Fidelity ENB_, which fixes Skyrim's lighting while retaining the high framerates necessary for a good VR experience. If you have an LCD-based headset (Valve Index, Rift S), enable only the LCD version. If you have an OLED-based headset (Vive, Rift CV1), enable only the OLED version.

Choose the appropriate plugin.

***WICO Non-Nude Meshes*** [[Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/2136)]. Librum uses WICO as a base, in order to overhaul character appearances in a natural-looking way. If you do not want nudity in your game, enable this plugin.

If you want this plugin, enable it in MO2.

#### Start up Skyrim... again
To start the game for real, start SKSE through Mod Organizer 2. This will be necessary every time you start the game; if you try to launch Skyrim through its default folder or through Steam, the game will be entirely vanilla.

Start a new game once you get to the main menu. The "yes/no" dialogue in the _New Game_ menu does not always indicate which you are selecting, but the buttons will work as expected. You will start in the character creation area from [Realm of Lorkhan](https://www.nexusmods.com/skyrimspecialedition/mods/18223). Here are some things to know as you create your character:

1. Race and gender differences are changed in accordance with [Race Abilities Enhanced](https://www.nexusmods.com/skyrimspecialedition/mods/23223) and [Genders are Boringly Indistinct](https://www.nexusmods.com/skyrimspecialedition/mods/23145), but with the modifications made by [Elemental Destruction Magic](https://www.nexusmods.com/skyrimspecialedition/mods/440). Namely, Orcs are 50% resistant to earth magic, and Argonians are 50% resistant to water magic.
2. Standing stones are changed in accordance with [Andromeda](https://www.nexusmods.com/skyrimspecialedition/mods/14910). However, **the standing stone you choose in the Realm of Lorkhan is final**.

