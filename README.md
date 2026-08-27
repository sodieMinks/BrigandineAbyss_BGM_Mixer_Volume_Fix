------------
ISSUE
------------
In Brigandine Abyss as of patch 1.01, the game's BGM volume is lower than Sound Effects and Voices. 
It's my misunderstanding that the BGM is routed through Unreal's sound class, SC_BGM and the class has the volume set to 0.15. 
Compared to SFX (SC_SE) and voice (SC_Voice) that are set at 1.0.

The files in this repo are intended to load after the main game files load to set the SC_BGM volume to 1.0.

------------
INSTRUCTIONS
------------
Place this file in the game directory's BrigandineAbyss\Content\Paks folder.

By default, this would be in a directory such as C:\Program Files (x86)\Steam\steamapps\common\HPN_HPJ\BrigandineAbyss\Content\Paks

Alternatively, you may be able to find this in Steam's interface by:
1. select Library from the  tab at the navigation bar along the top
2. select Home from Library's submenu
3. locate and select Brigandine Abyss from the left Games tree view
4. select Manage / the gear / cog icon on the right-hand side below the title banner
5. select Properties from the Manage sub-menu
6. select Installed Files from Brigandine Abyss dialog box's left-side tabs
7. select Browser toward the upper right
8. the HPN_HPJ folder should appear in Windows (or may be flashing in your taskbar if it does not display)
9. navigate to the "BrigandineAbyss" subfolder
10. navigate to the "Content" subfolder
11. navigate to the "Paks" subfolder
12. place the three files in this repo in that folder

And by that I mean, on the Code tab along this site's navigation bar, there will be a green <> Code button. 
Select the Code button, then select Download ZIP.
Unzip that file.
Copy and paste those files in the location in #11 / the folder being referenced in this README.

------------
REMOVAL
------------
To remove this modification from your game, delete these three files from the Paks folder. The files will all start with "Z".

In theory, even when the devs patch this officially

------------
DISCLAIMER
------------
This is an unofficial patch and I'm not affiliated with Adglobe, Happinet, NIS America, Inc., Steam, Nintendo, Sony, Microsoft,
Epic, Tencent, or the new Esgares Empire.
