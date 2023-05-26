<a href="https://www.nexusmods.com/fallout3/mods/25686"><img src="https://staticdelivery.nexusmods.com/mods/120/images/25686/25686-1685047932-1567809472.png" target="_blank"></a>

---

<p align="center">
  <a href="https://www.nexusmods.com/fallout3/mods/25686">Nexus Page</a> ·
  <a href="README.md">Installation</a> ·
  <a href="GAMEPLAY.md">Gameplay Guide</a> ·
  <a href="CHANGELOG.md">Changelog</a> ·
  <a href="https://discord.gg/VXvZWsxzEG">Discord</a>
</p>

---

# Read-Me

- [Introduction](#introduction)
  - [List Contents](#list-contents)
  - [Requirements](#requirements)
- [Installation](#installation)
    - [Clean Install](#clean-installation)
    - [Starting the Game](#starting-fallout-3)
    - [Downloading and Installing](#downloading-and-installing)
- [Startup](#startup)
- [Credits](#credits)

## Introduction

Lost Liberty is a lightweight and highly-curated wabbajack modlist aimed at creating a polished survival-like experience in Fallout 3. Lost Liberty creates a harsh yet rewarding wasteland, much akin to that of my other modlists.

## List Contents

You can browse the full list contents [here](https://loadorderlibrary.com/lists/lost-liberty) if you want to know exactly what you're getting.

You can find a summary of all changes on the [Gameplay Changes](GAMEPLAY.md) page.

## Requirements:

- An fresh installation of the **English** version of the game with the all of the DLCs from Steam or GOG
  * Only the English version is supported. I understand that this may be frustrating for non-English speaking users, but due to the core file differences between the different versions, only one version can be supported. 
  * The game MUST be installed outside of any default Windows folders, such as `Program Files`, your `Desktop`, or `Documents`. If you have your Steam library in any of these locations, please follow [these](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) instructions to move it.

- [Microsoft Visual C++ Redistributable Package](https://aka.ms/vs/16/release/vc_redist.x64.exe)

- The latest release of [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases) installed outside of any default Windows folders.

# Installation:

## Clean Install
Lost Liberty requires a completely clean installation of Fallout 3. This means completely deleting both the game folder and also the folder located in `Documents\My Games\Fallout3` then reinstalling the game through Steam/GOG. The game MUST be installed outside of any default Windows folders, such as `Program Files`, your `Desktop`, or `Documents`. If you have your Steam library in any of these locations, please follow [these](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) instructions to move it.

## Starting Fallout 3
Start the game and exit once you're at the main menu. This will ensure any settings files needed by Wabbajack are created.

## Downloading and Installing

The download and installation process can take a little while (an hour or more) depending on your system specs. For optimal speed, it is advised to install Wabbajack and the modlist to an SSD.

1. Create a folder for the modist outside of any default Windows folders called **Lost Liberty** (I recommend `C:\Games\Lost Liberty`) 
3. Launch the Wabbajack app and select `Browse Modlists`
4. Make sure `Show Unofficial Lists` is checked and search for `Lost Liberty`
5. Select the **Download** icon in the bottom right, then select he **Play** icon once the download is finished
7. In the **Modlist Installation Location** box, select the `Lost Liberty` folder you created in the first step
  * The Resource Download Location box should automatically fill in `Lost Liberty\Downloads`, but you can move this folder to a different drive if are low on space
8. Click the Go/Begin button and wait for Wabbajack to finish

# Startup

1. Open the installation folder and double click on the program called `ModOrganizer.exe`.
2. Select the **Fallout 3 Launcher** option from the drop-down in the top left then select **Run**
  > If you have the GOG version of the game, you may need to add the launcher to MO2 yourself. You can do so by clicking the **Executables Menu** icon (the two colored gears) in the top bar of MO2, selecting the **+** then **Add from file...**
3. The launcher should run and there should be two pop-ups about detecting your hardware and applying settings
4. Select **Options** then select whichever preset you think is best for your PC. I recommend **Ultra** for most PCs, but the **High** preset will provide noticeably better performance for only a minor visual downgrade.
  > For even further performance gains, I highly recommend disabling shadows. Fallout 3 does not have real-time shadows like modern games, only shadows for actors. These are hardly noticeable in most cases but do have an    impact on performance
5. Set the Resolution option to your preference (The launcher usually does not set it to your monitor's max resolution)
6. Exit out of the launcher
7. Back in MO2, right-click on the mod in the left pane called `Fallout Anniversary Patcher` and seelct **Open in Explorer**
8. Inside the opened folder, move all of the files to the game's `Root` folder (i.e. where you installed Fallout 3)
9. Once the file has been moved, double-click `Patcher.exe` to run the patcher 
9. A command prompt should show up, run for a few seconds, then read as follows:

>Patching completed successfully.
>
>Press any key to continue . . .

10. Exit out of the command prompt
11. Make sure the dropdown box on the right is set to `Fallout 3` and press the Run button.
12. You're all set! Everything is already configured by default so you can hope right into a new game!

# Credits

Thanks to [Guitarninja2](https://github.com/Lost-Outpost/dragonborn/commits?author=Guitarninja2) for the read-me format taken from their wonderful [Dragonborn](https://github.com/Lost-Outpost/dragonborn) modlist.
