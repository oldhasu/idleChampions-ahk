# idleChampions-ahk
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

Idle Champions of the Forgotten Realms AHK Macro Scripts

### The purpose of this macro script is to automate levelups on Idle Champions of the forgotton Realms
   - This is useful if you want to click less, and especially useful if you would like to run the game AFK and still have things leveled up.
   - It works as if you placed a familiar on the item/slot.
   - There are more advanced tips and tricks in the script comments.

 This script requires AutohotKey (AHK) to run.
 
 It was developed and tested on AutohotKey version 1.1.33.10 https://www.autohotkey.com
 
 Please see the comments in the top of the script, they may stay more up to date than this readme file

 This script adopted and maintained for the benefit of the gaming community.  It is free to use for non commercial purposes.

# Contributors
- Original Author: Abydos, Fritz
- orig filename: idlechamp-v1.4.ahk
- from striderx2048 210614
- edited retaki
- edited Leyline (discord: Swamp Fox II) 2021-09-23
- edited oldhasu (discord: oldhasu) 2022-10-01  <<< this fork <<< https://github.com/oldhasu/idleChampions-ahk

# Helpful tips
  - Use the PAUSE / BREAK key on your keyboard to pause the script.
  - Use Save Setting / Load Settings buttons to store your own custom settings for future use.	
  - The script has a 3s delay for typing safety.
  - If you have pressed a key (anywhere in your PC) recently then you may think the script did not fire a keypress when it was supposed to
  - You are correct: it skipped the keypress command and it will continue the next loop (after 3s of no key activity that is)
  - Increment Formations:
   	- If you want to restart the Increment Formations Timer - reload the script.
   	- You can "increment" the formations in any order by setting them to a shorter time delay than another formation.
   	- You can pick just one formation to increment by only setting a time delay for that formation.
  - Repeat Formation:
   	- This is for one or more special missions where your party members are kicked out and you want to reload them
  - Press HookWindow button to hook this ahk script to game window in case the game has been restarted.
  - Press Exit button to terminate the script	
