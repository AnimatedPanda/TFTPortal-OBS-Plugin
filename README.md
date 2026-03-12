# TFTPortal-OBS-Plugin
Shows Portal and Augments for Teamfight Tactics (TFT) in an easy to use OBS overlay.
No Twitch integration, no chat commands, no external apps — it's entirely self-contained in OBS!

1. Install the plugin files
- Close OBS, then copy these files:
- Place the `tftportal-plugin.dll` file into: C:\Program Files\obs-studio\obs-plugins\64bit\
- Place the `tftportal-plugin` folder into  C:\Program Files\obs-studio\data\obs-plugins\

2. Add the Source in OBS
- Open OBS
- In your scene's Sources panel, click + and select TFT Portal & Augments.
- A blank panel will appear showing
- Drag it above your game/desktop capture in the source list so it draws on top of the game.
- Resize and position it wherever you want on your stream layout. (This was designed to fit perfectly in the bottom-right corner and match with the existing TFT UI).

3. Play TFT
- The plugin automatically scans the screen every ~2 seconds.
- Encounters/Portals: At the start of the game (1-1), the encounter text appears (e.g. "Ryze grants you 3 random emblems..."). The plugin reads that text, and displays the friendly name (e.g. "Emblem ensemble") on the overlay.
- Augments: When the "Choose One" augment screen appears, the plugin detects the three augment names and displays the one you click on the overlay.

4. Troubleshooting
- Make sure TFT is running on the same monitor the plugin is capturing (it reads from the primary display).
- Default capture regions are tuned for 1920x1080. If you use a different resolution, right-click the source, open Properties, and adjust the Portal/Augment region coordinates (left, top, width, height).
- Windows OCR must be available: Settings > Time & language > Language & region — make sure English (or your game language) is installed.

5. Customization/Reporting Bugs
If you wish to customize the background panel. Or need to report any issues.

Please reach out:
Discord - @animatedpanda
Twitter/X - @AnimatedPandaTV



# SPECIAL THANKS
- twitch.tv/BoxBox & twitch.tv/aterial - For the original inspiration 