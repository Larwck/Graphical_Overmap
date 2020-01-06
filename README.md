# Graphical Overmap
Cataclysm DDA Graphical_Overmap mod <br>
Gives the overmap a graphical overhaul

Last updated 2020-1-6

### Installation:
  - *If your build is between #9942 and #10116 make sure to remove 'fonts.json' from data/mods/graphical_overmap.*
  - Download the ZIP.
  - Extract to your Cataclysm game folder. *Keep in mind this will overwrite your 'config/fonts.json' file so If you have previously made changes to it you will need to back them up first and modify it manually.*
  - In graphics options make sure the overmap font width/height/size are all set to "**16**" then restart.
	
### Optional:
  - I would advise disabling the 5x5 location map in the sidebar, as it becomes unreadable by using this mod. Press } to access sidebar options and choose either 'labels' (using the Location Alt panel instead of Location) or 'labels-narrow'.
  - For a more muted palette to increase readability move 'base_colors.json' from data/mods/Graphical_Overmap into your /config folder and overwrite. The crossroads with manhole (road_nesw_manhole) actually uses the dark_gray (60,60,60) from this palette, so may look slightly off if you are using a different dark_gray.
	
### Issues:
  - MAJOR: Having to go through the installation every update isn't ideal.
  - MAJOR: Mod doesn't work for people using cyrillic script or diacritic glyphs.
  - MAJOR: You may have problems (usually color based) when running this on anything but Windows.
  - MINOR: The arbitrary symbol I have used to represent each icon will appear at the top of the sidebar on the overmap screen when the tile is selected.
  - MINOR: Some locations are hidden in forests. However, some of these have the symbol and colour of a forest, while their name reveals what they really are (eg. "cabin_aban1"). Not sure whether to make them look like forests or as their name suggests. So far have made them the symbol of their name, but green.
  - MINOR: I know it's possible to change dirt roads, although getting the angles right confused me so I left it for now.
	
Happy cartography, <br>
@Larwick
