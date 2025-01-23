Welcome to Chroma BETA (expect issues)

Chroma is a Rockbox theme built around the idea of giving you extensive color choices. Rather than creating separate themes for light, dark and so on, Chroma gives you nearly unlimited choice over background, foreground, and accent coloration. This is because it uses almost no bitmaps, and the bitmaps that *are* used have alpha. This gives the user thousands of combinations all in the same theme. You can see a superb implementation of the approach in d00k's Themify.

In addition to color variety, Chroma makes extensive use of Shortcuts to give you the ability to turn various features on/off. This is done by accessing the lesser-used settings in Rockbox and reapplying them to various theme settings. I learned of this idea from d00k in his adwaitapod series and it is a brilliant way to give the user maximum flexibility in how the theme works for them personnally.

The sbs screen is based on tiles, used cleverly in themes like iRetro and NeoBeat. Each tile is connected to a menu item. While you *can* try to use more than 8 tiles, Chroma works best with 8. Chroma will do its best to work with your current menu items and order. The logic involved with trying to determine the user's menu order is pretty extensive, and results in laggyness while scrolling the tiles. For a much faster experience I have included two 8-tile presets which will hopefully meet the needs of most users. And as a nod to Apple, I have included a Mac OS miniDock which you can turn on or off. The sbs also includes a nice "Now Playing" tile.

There is a custom Quickscreen (like you see in d00k's and Dreaml1iner's themes). I didn't want to force the quickscreen settings on the user, in case you have your own custom quickscreen items chosen. If you want to use Chroma's custom quickscreen, open the cfg file you are currently using (Chroma.cfg, for example) and uncomment or add: 

qs top: brightness
qs bottom: brightness
qs left: shuffle
qs right: repeat

This will give you a more pleasant looking Quickscreen. You can experiment with using your own quickscreen settings instead, but you'll need to edit Chroma.sbs.

As previously mentioned, the user settings are most easily navigated via Shortcuts and I have included a shortcuts file that you can add to your file, or if you don't use Shortcuts you could simply replace your Shortcuts file with Chroma's. The file goes in the root of the .rockbox directory. Changes are handled via .cfg files that reside in Chroma Stuff/Settings.

Here is a list of the settings you can change in Chroma:

SBS
* Turn the miniDock on/off
* Switch between color or monochrome tile icons (coming soon)
* Switch between showing the menu name of each tile icon or showing the date (coming soon)
* Change the viewport at the top to show the date while on the main desktop

WPS (While Playing Screen)
* Turn Rounded Album Corners on/off
* Turn Wallpaper (Backdrop) on/off
* Show the Track Counter in play, pause, or turn it off 
* Remove the accent color from the track title
* Show/Hide the Wallpaper on the Lockscreen (coming soon)

Where to manually install the files:

Put the Chroma Stuff folder NOT in .rockbox but rather the root of your storage. This gives you easy access for making changes. All the shortcuts expect this path, so if you decide to move Chroma Stuff you will need to update the shortcuts.

Put shortcuts.txt in .rockbox BUT only if you are going to replace your existing shortcuts.txt! Please don't say I didn't warn you! If you have shortcuts that you use regularly, open Chroma's shortcut.txt in a text editor, copy all of it, and paste into your file above/below your existing shortcuts.

The other files go into .rockbox's directories that bear the same names. So take the fonts from Chroma's font directory and place those in .rockbox/fonts, and so on.

REBOOT your iPod.

The next step can take some patience. Go to Shortcuts. Choose "Welcome to Chroma" which will launch the default setup and try to assess your menu items and order. 

Important: It is completely possible you will get no tile icons showing. This is because there are hundreds of possible combinations of menu items and orders. Chroma will do its best to match, but no guarantees. But don't worry, workarounds exist...

What to do if your icons don't show at all, partially show, or are mis-named: Using the menu names at the top of your display (which will be correct even if the tile icons are not) get back to Shortcuts. From here you will need to accept one of Chroma's built-in FAST layouts. Please note that this means your menu items and order *will be altered* so this is your decision to make. It is not difficult to change them back for use in other themes, but I just want to be clear that using Chroma may involve altering your menu items. Once you see how easy it is to edit them (you don't need to use the plugin) you will be customizing in no time.

IF your correct menu items show and all tile icons match, great! You can use Chroma as-is, with a little lag while scrolling the desktop. It's up to you. If you have a specific order you wish to use with FAST scrolling, contact me and I will try to get it added.

Finally, a little info about the color-logic. Chroma includes some presets that will get you started, but you will likely want to explore your own color combinations. Similar to the tile icon matching, Chroma does its best to determine your color choices. The short story is...if the album artwork corners look pefectly rounded, Chroma has determined and matched your color choice. If not, you could still stick with that color and turn off rounded corners...up to you.

In general, steer clear of colors with letters involved. If you stick with numbers, you'll have the best chance of matching and having nicely rounded album corners.

For foreground (text elements, mostly) you should also try to use numbers-only but that said, Chroma does look for FFFFFF and F7F7F7 specifically, which will give you some nice accenting options like red or blue. Experiement and see.

SAVE your custom settings by going to Settings--> Manage Settings --> Save Theme Settings. Now you will have your own Chroma look with the options just as you prefer. Do this for any other color/feature combinations you like. You can add these to the shortcuts.txt and quickly access them when the mood strikes.

There's still a fair amount to be done, especially work on the lockscreen/usb screen/always on display logic. Anyway.....

I hope you enjoy Chroma.

