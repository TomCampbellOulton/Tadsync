<<<<<<< HEAD
*** If character is constantly resetting, pause the macro and close roblox, then resume/ start the macro and it should work. Working on a fix ***
# Natro-Alt-Synchronization
A extension to Natro Macro that adds the ability to synchronize an alt account with a main account to gather in the same field.

This is particularly useful for tad alts in blue hives, as it allows players to use boosts (gained from the blue field booster) in fields that they normally would not gather in.
DM @aqts on Discord (or message @Vqrtical on Roblox) for assistance, and please give this repository a star if it helped you!

SETUP:
1. You will need a Discord bot setup on both your alt and main account. See https://discord.com/channels/1012610056921038868/1088923608295936000 (in Natro Macro discord) to help you do so.
2. After installing, in the "Misc" tab of the macro, you will find the "Field Following" setting. Enable it for both accounts, and set the main account to "Leader" and alt to "Follower".
3. Set a max time that the alt will follow the main account to a different field (in seconds), this should typically be 900 seconds (15 minutes). You can ignore this number for the main account.
4. Create a new Discord channel (that the discord bots have permissions to!) and copy the ID of it. Paste it in the "Channel ID" option in both your alt and main account.
5. Done! These settings are NOT controllable with remote control or when the macro is paused, so make sure to stop the macro to do so.
=======
*** If character is constantly resetting, pause the macro and close roblox, then resume/ start the macro and it should work. Working on a fix ***

Tadsync is an updated version of Natro Alt Synchronization by @aqts-aqts to allow new patterns and paths to be used in addition to the ability to disable Mondo looting.
Auto updates have been disabled due to the updates not working with the field following mechanic.
-- Works for paths requiring Natro Macro versions 1.0.0.3 and 1.0.1 --

-- How To Use: --
1. Install and unzip
2. Launch "Start.bat" file
3. Configure "Gather" tab according to preference
4. Update "Settings" tab to have correct movement speed, move method and sprinkler type
-- Field Following Ability --
5. On "Status" tab, click "Change Discord Settings" under "Discord Integration"
6. Click on the discord logo at top left of screen (should turn golden and now read "Discord Bot Settings")
7. Enable the bot and paste in the bot token
8. Close the bot settings and move to "Misc" tab on the macro
9. Under "Unofficial Extensions" click "Field Following"
10. Tick "Enabled" and select "Follow Mode" (Leader for the account to be followed, follower for the alt accounts/ accounts to follow)
11. Paste in the channel ID for the Discord channel used to sync the accounts (your bot MUST be in this server with following permissions: Attach Files, Embed Links, Read Message History, Send Messages, View Channels)
12. Enter the length of time (in SECONDS) for how long you wish to have your accounts stay in that field before returning to the individual's macro settings (will be overridden by a new summons by the Leader account, Mondo Chick, etc.)
13. Close the "Field Following" tab and press "Start (F1)"

-- Add New Patterns --
1. Download the pattern and any paths required.
2. Navigate to the Tadsync folder and enter the "patterns" folder
3. Paste in your new pattern.
4. Navigate to your paths folder
5. Paste in your new paths (replace the old paths)
6. Close and restart your macro

-- Pinetree pattern (Miku-Tideshift included) --
1. Paste following settings onto macro
{"Name":"Pine Tree","Pattern":"Miku-TideShiftnm","DriftCheck":0,"PatternInvertFB":0,"PatternInvertLR":0,"PatternReps":5,"PatternShift":1,"PatternSize":"M","ReturnType":"Walk","RotateDirection":"Left","RotateTimes":4,"SprinklerDist":7,"SprinklerLoc":"Upper Left","UntilMins":10,"UntilPack":95}

-- Credits: --
Natro Macro:
https://github.com/NatroTeam/NatroMacro

Natro Alt Synchronization:
https://github.com/aqts-aqts/Natro-Alt-Synchronization/releases
>>>>>>> e5e7d14a33dfec07ce6377199584cc8d91b48857
