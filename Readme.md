README for OpenBAT
==================

Version 1.0


OpenBAT is an open-source project intented to revive and extend the discontinued BAT mod for CIV IV BTS. So far, no C++ development has been done, and only includes non-compiled assets. For now, this project will serve as the (non-DLL) base for other mods.

**Timeline, and what's BAT, BUG, BULL, and OpenBAT?**

**BUG**

BTS Unaltered Gameplay: The BUG Mod makes many interface improvements, but will not alter any unit, terrain, or city graphics. With a few exceptions, The BUG Mod is customizable, and features can be disabled or altered from within the game by just pressing Alt + Ctrl + O..  This will allow you to customize BUG to fit your style!

**BULL**

An optional DLL file for BUG that "allows" for more options that couldn't be modded in via XML/Python

**BAT**

"The BAT Mod makes the game look as it should have when you first purchased it.  We have combined many graphical changes into one mod, striving to give each Civilization its own look and feel."

BAT includes BUG and BULL, and a bunch of other texture and interface mods (see below). Most notably, BAT includes Blue Marble (NASA-based terrain textures), and Varietas Delectat (unique unit sets for civilizations).
Source code was lost in 2018, and discontinued with 4.1 as the last release.


Now: (Dec. 2018)
==================

BAT has become a staple mod for vetran players, combining some of the greatest mods for BTS. However, it's not open-source, so extending it for / combining with gameplay/DLL mods is simply not ideal.

**OpenBAT**

An open-source base for other mods to extend and include many of the great features of BAT.






**OpenBAT includes:**

- BlueMarble terrain mod
- Varietas Delectat 9.2 (Cheetah Edition) by Avain
- Better Flags & Buttons by KingKongTR
- BUG Mod 4.4

**Imported from BAT 4.1 (Classic) but untested:**

- Cultural Diversity 1.1 by Chugginator (Optimized by Avain.)
- Cultural Citystyles 0.99 by GeoModder (Optimized by Avain.)
- Actual Quotes - Better Diplomacy Text by Willowmound
- Better Flags & Buttons by KingKongTR
- Improved Graphics Leaderheads by Chuginator
- Advanced Combat Odds by Piece of Mind
- Events with Images Mod by asioasioasio, Renegade Chicken and EmperorFool.  Images by Arian.
- Female Unit Graphics (Great People, CEO's and Missionaries) by SaibotLieh.  Code by Lemon and EF.
- Lemon's Movie Mod by Lemon Merchant, with slices, dices, and interpolations of music from Cybrxkhan's Diplomacy Music Packs.  Used with his gracious permission.
	A note about the movie mod:
	These are little movies for the Shrines and National Wonders.  The available ones for download were very good, but so darn long, and I felt that they broke the flow of the game.  I created new ones with an individual length of 15 seconds each, with new music, so that they would be a little less obtrusive.  The music has also had the volume leveled out so that it's closer to the volume levels in the game.


- OrionVeteran and Roamty's Great Person Mod (Bare Bones).  The pictures pack will be a separately available download.
- Era Movies by Lemon Merchant.
- Lemon's Spy Mod by Lemon Merchant.  A selectable option to have spies return to the nearest city, rather than the capital.  NOTE THAT THIS DOES ALTER GAMEPLAY.  THAT'S WHY IT'S AN OPTION!!
- Peakblend mountain textures, icepack textures, and new crops by Kissa
- Water Mod 2.0 by Nitram15, with blue water textures.  With files from cool3a2.
- New aspect ratio load screens by Lemon Merchant.  The load screens now render better on widescreen monitors. (I can't do anything about the Baba Yetu screen,  unfortunately).
- Messages Mod from The_J. Displays messages when wonders are captured or destroyed.


**To be added:**

- BUG DLL (BULL) 

	




README for BUG
==============

1. Introduction
2. Installation
3. Configuration
4. Troubleshooting


____________________________________________________________________________________________________
1. INTRODUCTION

BUG is an unaltered-gameplay mod for Civ4:BTS. This readme covers how to install BUG manually, but we recommend that you use the installer when you can.


____________________________________________________________________________________________________
2. INSTALLATION

WARNING: You should never modify or replace the original BTS Assets files.

__________________________________________________
2.1. AS A MOD

To install BUG as a mod so that you must load it to play, place the folder that contains this README file into your BTS's Mods folder.

    C:\Program Files
      Sid Meier's Civilization 4
        Beyond the Sword
          Mods
            BUG Mod x.x
              Readme.txt
              ...

__________________________________________________
2.2. CUSTOM ASSETS

To install BUG so that it is always active with your games (this will allow you to use it with succession games and games you open from the CivFanatics forum), you must first copy the files and folders from the Assets folder into your CustomAssets folder. Next create a "BUG Mod" folder next to CustomAssets and copy the Info and UserSettings folders into it. Finally, copy the files inside PrivateMaps into BTS's PublicMaps folder.

At each step it is important that you tell it to overwrite files.

    C:\Documents and Settings
      <your user name>
        My Documents
          My Games
            Beyond the Sword
              CustomAssets        <-- folders in Assets go here
              BUG Mod             <-- create this folder
                GameSetUpCheck    <-- copy these three folders here
                Info
                UserSettings
              PublicMaps          <-- copy files from PrivateMaps here


____________________________________________________________________________________________________
3. CONFIGURATION

Once you start a game with BUG you can customize how BUG looks by hitting ALT + CTRL + O to get to the BUG Options screen. It has many tabs to organize the settings, and they are all written to INI files inside the UserSettings folder. You can also change them in these files, but this is only necessary for a handful of options.


____________________________________________________________________________________________________
4. TROUBLESHOOTING

If you are having any trouble getting BUG to work, start with our Troubleshooting wiki page:

    http://sourceforge.net/apps/mediawiki/civ4bug/index.php?title=Troubleshooting

Post the information that page asks for to the Questions thread at our forum:

    http://forums.civfanatics.com/showthread.php?t=242396

If you find a feature or option that doesn't work properly, please post to our Bug Reporting thread:

    http://forums.civfanatics.com/showthread.php?t=241796
