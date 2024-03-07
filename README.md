# Kingdom Hearts Boss Rush Save Loader and Auto Splitter

## Description
This automatically splits for the bosses in Kingdom Hearts Final Mix HD, while also loading the next boss in a autosave.dat file

## Dependencies
1. luabackend hook - https://github.com/Sirius902/LuaBackend/releases/tag/v1.7.3-hook
2. KHPCSpeedrun Tools - https://github.com/S0nzero/KHPCSpeedrunTools/tree/main
3. Livesplit - https://livesplit.org/

# Install and Using
1. Download luabackend hook from https://github.com/Sirius902/LuaBackend/releases/tag/v1.7.3-hook and install it by following their instructions
2. Download the 1fmSaveAnywhere.lua from https://github.com/S0nzero/KHPCSpeedrunTools/tree/main/1FMMods/scripts and install it by following their instructions
3. Download Livesplit
4. Download "Boss Rush.asl" and the Boss Rush save files that you need for you version of the game.
5. Place your "Boss Rush" save folder inside your livesplit folder
6. Add "Scriptable Auto Splitter" in your livesplit layout
7. Select the Boss Rush.asl file as your script path when editting the Scriptable Auto Splitter in livesplit
8. Start your splits whenever you start to move with Sora after loading Darkside 1
9. When you best a boss, press the button command to load your autosave.dat file, L1+L2+R1+R2+right on the dpad

# Updating Saves
1. Load the autosave of the boss you want to update by using my practice helper found here https://github.com/RebelWatt/Kingdom-Hearts-Practice-Helper
2. Commit your changes like editting your customize menu, then either save and reload the game, or do a room transition to update the autosave.dat file in your kh1.5+2.5 folder
3. Copy the autosave.dat file from your kh1.5+2.5 folder to you Boss Rush folder
4. Change the name from autosave.dat to the exact name of the boss save file you are replacing. It is very important that this name is exactly like the file that is currently in the folder. If your save isnt loading, I can almost guarantee it is because you incorrectly named your save.

# Useful Button Commands
1. Load an auto save - L1+L2+R1+R2+right on d-pad
2. Save Anywhere - L1+L2+R2+Touchpad
3. Instantly kills Sora in order to try a boss again - R1+r2+L2+Touchpad