# Microgames in TF2 // microtf2

A custom gamemode for Team Fortress 2 - Players compete against each other to get the most points by playing a series of rapid fire microgames in order to win the round!

## Install Guide
We have written a guide to assist you on installing the gamemode on your TF2 Server - read it here: https://www.gemidyne.com/projects/microtf2/install-guide/

## Commands 
See wiki page for more information: https://github.com/gemidyne/microtf2/wiki/Console-Commands

## Console Variables
See wiki page for more information: https://github.com/gemidyne/microtf2/wiki/Console-Variables

## Repository info

The /src folder contains the plugin source-code. 
The /assets folder contains data relating to the map, plugin overlays and sounds. It is strongly recommended that you use https://www.gemidyne.com/projects/tsukuru/ to build the map and pack in the necessary assets.

The "master" branch is the latest stable version of the gamemode. We recommend you use this branch on your game servers.
The "dev" branch is used for the latest development version of the gamemode. This branch contains work in progress projects so may be uncompilable, untested and not be the best experience for your players. We recommend you use the master branch over the dev branch.

## SourceMod Extension / Plugin Dependencies

The gamemode utilises the following extensions and plugins to run:

- SteamTools extension - https://forums.alliedmods.net/showthread.php?t=170630 (Used for setting the game description)
- TF2Items extension - https://forums.alliedmods.net/showthread.php?t=115100 (Used for blocking wearables)
- TF2Attributes plugin - https://github.com/FlaminSarge/tf2attributes (Used for applying attributes to weapons)
- TFEconData plugin - https://github.com/nosoop/SM-TFEconData (Used for giving weapons to players)
- (Windows only) host_timescale_fix plugin - https://forums.alliedmods.net/showthread.php?t=324264 (Fixes a host_timescale issue only on Windows SRCDS installs. Not required if you are running the gamemode on Linux)

If you intend to use the SDK plugin for developing your own gamemodes or minigames, you will need:

- Sound Info Library extension: https://forums.alliedmods.net/showthread.php?t=105816   https://github.com/bcserv/soundlib (Used for determining sound file length for themes and minigames)

## Want to help translate the gamemode into other languages? 

We'd love to have you on board! If you are interested in contributing translations, there are two ways you can do it: 

1. We can add you onto our gemidyne.com Translator Tool which makes editing translations super quick and easy - [click this link](https://github.com/gemidyne/microtf2/issues/new/choose) and choose **Become a translator**.
2. You can add your own language "microtf2.phrases.txt" file built from the english file into your own translation folder - this way is more manual but you can contribute via pull requests if you want 

#### We currently have translators for the following languages:

- [X] French
- [X] Italian
- [X] Spanish
- [X] Russian
- [X] Portuguese
- [X] Brazilian Portuguese
- [X] Polish
- [X] German

## Credits

View the full gamemode credits here: https://www.gemidyne.com/projects/microtf2/credits

Resurrected by Gemidyne Softworks.
