## Installing with Wabbajack:

### Step 0:

Run Fallout 4 once from Steam. You can close the launcher when it detects your video settings. After this, create a new folder named `HREInstall` (Or any other name, that's just what I will refer to it as) anywhere outside of Program Files. I HIGHLY recoomend installing on an SSD! Then, in Wabbajack, click the `...` next to `Installation Location` and select the `HREInstall` folder you just made. Feel free to keep the `Download Location` anywhere you like, or leave it at the default.

### Step 1:

After it finishes, go to your install folder, and open up the `Game Folder Files` folder and Copy these all into your Fallout 4 Directory.

### Step 2:

Download the latest ENB binaries from [the ENB website](http://enbdev.com/download_mod_fallout4.htm). Open the archive you downloaded, and go into the `WrapperVersion` folder. Extract ONLY the two files `d3d11.dll` and `d3dcompiler_46e.dll` into your Fallout 4 Directory.

### Step 3:

Launch BethINI from the exe found in your `HREInstall/tools/BethINI Standalone` folder.

### Step 4:

These instructions will be listed by Tabs in BethINI, please follow them in order, or things will not work.

* **Setup**:   
Make sure `Game` is set to `Fallout 4`.
`Game Path` should be set to whatever directory your game is in, ending with `Steam/steamapps/common/Fallout 4`.
`Mod Organizer` should be set to your `HREInstall` directory, wherever that is.
`INI Path` should be set to `ModOrganizer > HRE 2.0 Beta` OR `ModOrganizer > HRE 2.0 Quality Beta`.
* **Basic**:  
Here, set your screen's resolution is set properly, and also set your graphical preset. I recommend using BethINI's High preset (I used to recommend Ultra, but it really just hurts performance).
Ensure that `FPS` is set to `60`. Don't worry, we can get more in game, it just needs to be that way in the INIs.
Be sure to check the `Recommended Tweaks` Box as well!
* **General**:  
Check the `Intro Logo` checkbox. It needs to be checked, otherwise custom main menu audio doesn't work. No idea why.
You can also choose to disable tutorial messages here.
* **Interface**:  
You can check here if you want subtitles or not.
* **Custom**:  
If you want your PipBoy Flashlight to be colored a flat white rather than whatever color your PipBoy is, then do this:
Under `Section`, select `Pipboy`.
Under `Setting`, select `bPipboyEffectColorOnLight`.
In the text box below, change the `1` to a `0`, and then click `Save`.
* **Basic**:  
Now, hit `Save and Exit` in the bottom right.

### Step 5:

Launch ModOrganizer from the exe found in your `HREInstall` folder.

NOTE: If you are on Windows 11, update the MO2 Installation using the Update button (It looks like a globe) in the top right of MO2.

### Step 5.5 (Optional):

**NOTE FOR STREAMERS**: Disable the mod 'Musical Lore - Wasteland Edition', because the author has a bot that will Copyright claim YouTube videos. You are free to contact the Author, NirShor, to ask permission to use it, because it does make the atmosphere even better! Sorry about the inconvenience!

Now, you have a few choices before starting your game. You can follow the simple instructions at the bottom of the left pane of MO2 to decide if you want your Protagonist to talk or not. By default, it will not.

You can also choose to install Pack Attack NPC and its companion mod, Pack Attack Companion Edition by Greslin, which is are *amazing* AI mods that were removed from the Nexus. You might be able to grab it from the author's discord server [here](https://discord.gg/Kacy6Z5BFM), but there are NO guarantees. Then, place the archive in your downloads folder, and install it like you would any other mod in MO2. If you don't know how to do that, then see [Lively's Learn To Mod](https://github.com/LivelyDismay/Learn-To-Mod/tree/main/lessons). Now, simply place this mod above `HRE PANPC Patch` in the left pane, and enable both, and you will be good to go, with smarter enemies enabled.

### Step 6:

Now, launch your game from `F4SE` in the top left of your MO2! 

If this does not work, please update your MO2 installation. I will fix this in the next update.

After creating your character, be sure to follow these steps exactly!

* **Inside the Bathroom**:  
- While inside the bathroom, allow all of the messages in the top left of your screen to disappear.   
- After this is done, open your MCM menu and use 'MCM Settings Manager' to load the 'Before Vault' Configuration.  
- Now, make a save here, and WAIT for 2 minutes. Do nothing. Just stand there. If you do not do this, your game will destroy itself after you walk through the door.  
- Before you walk through the door, set your game to 'Survival' Difficulty.  
- Now Walk through the door, and go through the menus.  
- Now play through the Vault normally, until you come outside.
* **After the Vault**:
- After exiting the Vault, use the 'MCM Settings Manager' again to load the 'After Vault' Configuration.  
- Now, open your PipBoy, go to `Misc`, and `Settings`, and open the `Beantown Interiors` Holotape. Go to `Customize Options -> Other Options` and `Enable Hardcore Clutter`.   
- Then, go to `Mod Compatibility` and `Enable Insidejobs Compatibility`.

### Step 7 (Optional):

For an additional little tweak for those of you who can run this at 60+ FPS, you will use the ENB Menu to limit your FPS (Which I HIGHLY recommend).  
To open the menu, hit `Shift+Enter` anytime in game, and in the top left, a menu will pop up.  
Navigate to `FPS` and change the value to whatever you desire.  
I recommend using a factor of whatever your screen's refresh rate is at. So, for a 120hz screen, use 60, 120, or 240.  
To prevent screen tears, use your GPU's inbuilt profile selctor for Fallout 4 to use Fast V-Sync.  
