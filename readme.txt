Welcome to Chroma

Chroma is a Rockbox theme built around the idea of giving you extensive color choices. Rather than creating separate themes for light, dark and so on, Chroma gives you nearly unlimited choice over background, foreground, and accent coloration. This is because it uses almost no bitmaps, and the bitmaps that *are* used have alpha. This gives the user thousands of combinations all in the same theme. You can see a superb implementation of the approach in d00k's Themify.

In addition to color variety, Chroma makes extensive use of Shortcuts to give you the ability to turn various features on/off. This is done by accessing the lesser-used settings in Rockbox and reapplying them to various theme settings. I learned of this idea from d00k in his adwaitapod series and it is a brilliant way to give the user maximum flexibility in how the theme works for them personnally.

The sbs screen is based on tiles, used cleverly in themes like iRetro and NeoBeat. Each tile is connected to a menu item. While you *can* try to use more than 8 tiles, Chroma works best with 8. Chroma will do its best to work with your current menu items and order. The logic involved with trying to determine the user's menu order is pretty extensive, and results in laggyness while scrolling the tiles. For a much faster experience I have included two 8-tile presets which will hopefully meet the needs of most users. And as a nod to Apple, I have included a Mac OS miniDock which you can turn on or off. The sbs also includes a nice "Now Playing" tile.

As previously mentioned, the user settings are most easily altered via Shortcuts and I have included a shortcuts file that you can add to your file, or if you don't use Shortcuts you could simply replace your Shortcuts file with Chroma's. The file goes in the root of the .rockbox directory.

Here is a list of the settings you can change in Chroma:

SBS
* Turn the miniDock on/off
* Switch between color or monochrome tile icons (coming soon)
* Switch between showing the menu name of each tile icon or showing the date (coming soon)

WPS (While Playing Screen)
* Turn Rounded Album Corners on/off
* Turn Wallpaper (Backdrop) on/off
* Show the Track Counter in play, pause, or turn it off 
* Remove the accent color from the track title
* Show/Hide the Wallpaper on the Lockscreen (coming soon)

Where to manually install the files:

Put the Chroma folder in the root. 

Put shortcuts.txt in the root as well BUT only if you are going to replace your existing shortcuts.txt! Please don't say I didn't warn you! If you have shortcuts that you use regularly, open Chroma's shortcut.txt in a text editor, copy all of it, and paste into your file. 

The other files go into .rockbox's directories that bear the same names. So take the fonts from my font directory and place those in .rockbox/fonts and so on.

REBOOT your iPod.

The next step can take some patience. Go to Shortcuts. Choose "Welcome to Chroma" which will launch the default setup and try to assess your menu items and order. 

Important: It is completely possible you will get no tile icons showing. This is because there are hundreds of possible combinations of menu items and orders. 

What to do if your icons don't show at all, partially show, or are mis-named: Using the menu names at the top of your display (which will be correct even if the tile icons are not) get back to Shortcuts. From here you will need to accept one of Chroma's built-in FAST layouts. Please note that this means your menu items and order *will be altered* so this is your decision to make. It is not difficult to change them back for use in other themes, but I just want to be clear that using Chroma may involve altering your menu.

IF your correct menu items show and all tile icons match, great! You can use Chroma as-is, with a little lag while scrolling the desktop. It's up to you. If you have a specific order you wish to use with FAST scrolling, contact me and I will try to get it added.

