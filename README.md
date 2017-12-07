# RK9-Guide

(1st Dec 2017) 
- *Please download latest version for HM/EM for NA/EU servers as there is a change in packet defination
- *Please also update your tera data file to the latest from https://github.com/meishuu/tera-data

** TO SEE ARROWS ON THE SCRIPT ** Credits to fortunefavor
- I have yet to test this. Use this at your own risk.
Navigate to the TERA\Client\S1Game\Localization\USA folder.
Rename the GFxUI into something else.
Going up one folder and enter the INT folder.
Copy both files from there and paste them into the USA folder.
Rename the ExampleGame.int and GFxUI.int into ExampleGame.usa and GFxUI.usa, respectively.
Your in game font will change but the arrows will show. This also improves font size so you don't squint while reading stuff in game lol.



Your in game font will change but the arrows will show. This also improves font size so you don't squint while reading stuff in game lol.

Last boss protocol message has been updated to SAFEZONES. IN+OUT means boss will be hitting outer then inner.
If you wish to have the older version where call outs are what the boss is doing, feel free to drop me a pm on discord.

Credits to teralove and soler91 for their VS guides

Call out attacks from RK-9 Bosses all 3 of them including both NORMAL MODE & HARD MODE & EXTREME MODE

Script automatically detects bosses and which dungeon hard or normal.

Please report any issues to me either here or on discord :)

# Commands 
Only usable in the RK9 Map. Using of commands outside map will return undefine command.
- !rk9 to toggle module (DEFAULT: ON)
- !party to toggle party notice (DEFAULT: SELF ONLY)
- !lastbosstoparty to toggle  IN OUT WAVE call outs (DEFAULT: OFF)
- !itemhelper to toggle item spawn on ground (DEFAULT: ON)
- !tank to toggle tank mode (Auto-enabled if you are LANCER or BRAWLER)
- !info to show all the above settings ON or OFF
- !help to show what commands are there in the RK9 guide module
- !debug FOR DEBUGGING PURPOSES

# Known issues
- All fixed as of 15th Nov

# Patch Notes
V1.00
- Created RK-9 Guide NORMAL MODE

V1.01 - 04
- Added RK-9 HARD MODE

V1.05
- Added more functionality checks to prevent errors

V1.06 - 08
- Fixed HARD MODE last boss call out <70% hp
- Fixed last boss multiple call outs
- Added S_QUEST_BALLOON Hook for HARD MODE
- Added Floor display (Flower) for safe zones

V1.09
- Added more codes to hardmode first boss pizza
- Fix hardmode last boss incorrect call outs
- Edit code to use Pinkie's command
- Deleted format.js due to usage of command
- Edit and shorten code length due to inefficient spawn item

V1.10
- Fixed normal mode first boss rocket jump call out
- Added last boss 97% call out
- Fixed hardmode last boss call outs on extrememode as well
- Added toggle function for item spawn
- Added function to call out only last boss in out wave mechs

V1.11
- Changed last boss to mini flowers with outline

V1.12
- Added item spawn for 2nd boss NM

# Future updates
- 2nd Boss orbs line (HM)
- Streamer friendly
