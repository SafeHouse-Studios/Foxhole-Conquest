# Foxhole Conquest
## Installation
1. Enable the *Debug Mode* using [this video](https://youtu.be/aMhmkrYOvMk?list=PLt_7vUaEvaGTJ0ISBqY2v4EyfmPALiVS7).
2. Go to your **Heart Of Iron IV** launcher, on the left hand side, select *"All installed mods"*.
3. In the right hand corner, you should see an icon called, *"Mod Tools"*, click that and then click on *"Create a Mod"*.
4. Fill in the required informations:
    * Name: Foxhole Conquest
    * Version: 1.10
    * Directory: FoxholeMod
    * Tags: Whatever you want, this does not affect the mod
5. Click on *"Create Mod"*. It will take you to another page, just ignore it.
6. Close the **Heart Of Iron IV** launcher.
7. Clone this Github Repository (Or dowload the files).
8. Go to your ```"C:\Users(username)\Documents\Paradox Interactive\Hearts of Iron IV\mod\FoxholeMod"```
9. Put every folders (Example: common, gfx, history...) inside the FoxholeMod Directory.
10. Inside the FoxholeMod folder, go to your descriptor using an IDE ([Notepad++](https://notepad-plus-plus.org/downloads/), [Sublime Text 3](https://www.sublimetext.com/3), [Visual Studio Code](https://code.visualstudio.com/)).
11. At the bottom of the code, add this:

```bash
replace_path="map/strategicregions"
replace_path="map/supplyareas"
replace_path="map/terrain"
replace_path="history/countries"
replace_path="history/states"
replace_path="common/bookmarks"
replace_path="gfx/loadingscreens"
```
12. Leave the FoxholeMod folder to the mod folder and do the same step as 
**#7** with the icon that is named *"FoxholeMod"*.