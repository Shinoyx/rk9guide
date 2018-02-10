# RK9-Guide

I will apologize in advanced as I don't think I will be releasing guide mod for Antaros' Abyss due to how the dungeon works.
 1) There is not much memorization mechs as compared to rk9.
 2) This dungeon is fairly simple with most attacks relying on skill and reaction.
 3) I think it would be fair to players who wish to run without guide to get high scores instead of players with guide winning over them.

However, I will be releasing dungeon guides on my youtube channel so feel free to take a look!
https://www.youtube.com/watch?v=XG2mx9usHsc&t=3s

Donations:
[![paypal](https://www.paypalobjects.com/en_GB/SG/i/btn/btn_paynowCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=JW3A7NS4W7BRY)

*This is OPTIONAL and purely out of goodwill. Thank you for your support!

Can't donate? No worries, you can also support me through in-game currency!

Feel free to check out and support my YouTube channel as well! https://www.youtube.com/user/angxng1995/

Feel free to pm me on discord if you have any issue or bug @Shinoyx#2674


# Commands 
<details>

Only usable in the RK9 Map. Using of commands outside map will return undefined command.

    - !rk9 to toggle module (DEFAULT: ON)
    - !party to toggle party notice (DEFAULT: SELF ONLY)
    - !lastbosstoparty to toggle  IN OUT WAVE call outs (DEFAULT: OFF)
    - !itemhelper to toggle item spawn on ground (DEFAULT: ON)
    - !tank to toggle tank mode (Auto-enabled if you are LANCER or BRAWLER)
    - !info to show all the above settings ON or OFF
    - !help to show what commands are there in the RK9 guide module
    - !debug FOR DEBUGGING PURPOSES
    - !stream to enable streaming mode which will remove all item spawn as well as remove party notice pop ups

</details>

# Extra Notes
<details>

   <details>
      <summary>Script doesn't work?</summary>

        1. Please update your tera data file to the latest from https://github.com/meishuu/tera-data

        2. Make sure you are running the latest version of proxy

        3. Download the latest copy of RK9Guide
   </details>

   <details>
      <summary>How do I view the arrows from the script?</summary>

        - Navigate to the TERA\Client\S1Game\Localization\USA folder.

        - Rename the GFxUI into something else.

        - Going up one folder and enter the INT folder.

        - Copy both files from there and paste them into the USA folder.

        - Rename the ExampleGame.int and GFxUI.int into ExampleGame.usa and GFxUI.usa, respectively.
   </details>

</details>

# Known bugs / Issues
<details>
    
</details>

# Patch Notes
<details>

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

    V1.13
    - Added item spawn for 2nd boss HM

    V1.14
    - Added estimated shield warning call out for last boss (NM & HM)
    - Added streamer mode

    V1.15
    - Reformatted command message as chat box isn't HTML anymore
    - Increased HM shield warning by 5 sec 

    V1.16
    - Reduced last boss NM shield warning by 5 sec
    - Fixed improper shield warning call outs when boss die or resets

    v1.17
    - Fixed last boss wrong call outs

</details>
