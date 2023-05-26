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
    - [Starting the Game](#starting-fallout-3)
    - [Downloading and Installing](#downloading-and-installing)
    - [Problems with Wabbajack](#problems-with-wabbajack)
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
1. Run the game through either Steam or GOG
2. There should be two pop-ups about detecting your hardware and applying settings
  > If you don't get any pop-ups, you did not properly do a clean installation! Delete `Documents\My Games\Fallout3` and try again.
3. Select **Options** then select whichever preset you think is best for your PC. I recommend **Ultra** for most PCs, but the **High** preset will provide noticeably better performance for only a minor visual downgrade.
  > For even further performance gains, I highly recommend disabling shadows. Fallout 3 does not have real-time shadows like modern games, only shadows for actors. These are hardly noticeable in most cases but do have an impact on performance
4. Exit out of the launcher

## Downloading and Installing

The download and installation process can take a little while (an hour or more) depending on your system specs. For optimal speed, it is advised to install Wabbajack and the modlist to an SSD.

1. Create a folder for the modist outside of any default Windows folders called **Lost Liberty** (I recommend `C:\Games\Lost Liberty`) 
3. Launch the Wabbajack app and select `Browse Modlists`
4. Make sure `Show Unofficial Lists` is checked and search for `Lost Liberty`
5. Select the **Download** icon in the bottom right, then select he **Play** icon once the download is finished
7. In the **Modlist Installation Location** box, select the `Lost Liberty` folder you created in the first step
  * The Resource Download Location box should automatically fill in `Lost Liberty\Downloads`, but you can move this folder to a different drive if are low on space
8. Click the Go/Begin button and wait for Wabbajack to finish

## Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you won't lose any progress.

**REMINDER:** This list does not work with non-English and non-Steam/GOG versions of the game. 

If you have any other installation issues, I may need to update the list. Please drop by the [Discord](https://discord.gg/VXvZWsxzEG) to report any errors!

# Startup

Open the installation folder and double click on the program called `ModOrganizer.exe`.

Right-click on the mod in the left pane called `Fallout Anniversary Patcher` and seelct **Open in Explorer**

Inside the opened folder, move all of the files to the game's `Root` folder (i.e. where you installed Fallout 3)

Once the file has been moved, double-click `Patcher.exe` to run the patcher 

A command prompt should show up, run for a few seconds, then read as follows:
`Patching completed successfully.
Press any key to continue . . .`

Exit out of the command prompt

Make sure the dropdown box on the right is set to `Fallout 3` and press the Run button.

You're all set! Everything is already configured by default so you can hope right into a new game!

# Credits

Thanks to [Guitarninja2](https://github.com/Lost-Outpost/dragonborn/commits?author=Guitarninja2) for the read-me format taken from their wonderful [Dragonborn](https://github.com/Lost-Outpost/dragonborn) modlist.
