# Graphical_Overmap
Cataclysm DDA Graphical_Overmap mod

Last updated for build #9934

Installation:
  - Download the ZIP.
  - Extract to your Cataclysm game folder.
  - In graphics options change the overmap font width to "16" then restart.
	
Optional:
  - I would advise disabling the 5x5 location map in the sidebar, as it becomes unreadable by using this mod.
  - For a more muted palette to increase readability move 'base_colors.json' from data/mods/Graphical_Overmap into your /config folder and overwrite. The crossroads with manhole (road_nesw_manhole) actually uses the dark_gray (60,60,60) from this palette, so may look slightly off if you are using a different dark_gray.
	
Issues:
  - MINOR: The arbitrary symbol I have used to represent each icon will appear at the top of the sidebar on the overmap screen when the tile is selected.
  - MINOR: Some locations are hidden in forests. However, some of these have the symbol and colour of a forest, while their name reveals what they really are (eg. "cabin_aban1"). Not sure whether to make them look like forests or as their name suggests. So far have made them the symbol of their name, but green.
  - MINOR: I know it's possible to change dirt roads, although getting the angles right confused me so I left it for now.
	
Happy cartography,
@Larwick
