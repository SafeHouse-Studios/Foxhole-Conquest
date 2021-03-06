# Foxhole Conquest
## Project Description
_

## User Installation Guide:
Steam link: _

Other link: _

Installation Guide: _

## Dev Installation Guide:
1. Go to github.com and make an account.
Give Rega your account name and he will invite you to join the repository (the project).
The invite will appear in the email you registered github with not in your github account.
*Wait for Rega to accept you before moving onto the next steps!

2. Go to https://desktop.github.com/ and download the GitHub Desktop Application.
*Wait for this to be fully downloaded and installed before moving onto the next steps!

3. Download a text editor, for beginners we suggest Notepad ++ https://notepad-plus-plus.org/downloads/v8.1.4/ or for a more advanced editor you could use Visual Studio Code https://code.visualstudio.com/Download (this has an inbuilt extension mechanic, there are extensions to make text more visible and there is also a custom HoI4 extension). Or you could use Sublime Text https://www.sublimetext.com/ (this one is great when you need to compare and search for specific text in files).

4. Go to your Hearts of Iron IV launcher and on the left hand side, select "All installed mods". In the right hand corner, you should see an icon called, "Upload Mod", click that and then click "Create a Mod".
Now fill in the required info:
	Name = Foxhole Conquest: Dev Version
	Version = 1.11
	Directory = FoxholeConquestDevVersion (Cannot have any special cases and spaces)
	Tags = (should have no effect on the mod but select all of consistency so we know if something goes wrong it isn’t that somehow).
	Click Create Mod
Now it will take you to another page, just ignore it. Now close the HOI4 launcher.

5. Go to the newly created folder in your directory.
“C:\Users\YOURPCNAME\Documents\Paradox Interactive\Hearts of Iron IV/mod/FoxholeConquestDevVersion”
Find the file called descriptor and temporarily remove it from this folder (don’t delete it, you may need it later).

6. After the previous installation open the GitHub Desktop Application and connect to your main github account.
Assuming you have followed the instructions properly and have been accepted to the repository, you will see the repository on the right hand side of the app.
Click the repository name RegaSaurus24/Foxhole-Conquest then click the clone button.
Ensure that the Local Path is set to the following file: “C:\Users\YOURPCNAME\Documents\Paradox Interactive\Hearts of Iron IV/mod/FoxholeConquestDevVersion”
Obviously change the YOUR PC NAME to your PC’s name.
Hit clone/download and get the files from github.

7. Open the descriptor file that you have moved as well as the new one downloaded using your text editor (Notepad++ or other). Check for differences in the code (there may be changes as HoI:IV updates the descriptor files. If unsure check with a mod manager but the file should resemble the following step without the path replacements.

8. One step back up in the folders at path:
"C:\Users(username)\Documents\Paradox Interactive\Hearts of Iron IV\mod” 
You will find a newly created descriptor called: “FoxholeConquestDevVersion.mod”
Also open this file in the text editor.
You need to paste the following code into the correct place in the document:


replace_path="map/strategicregions"
replace_path="map/supplyareas"
replace_path="map/terrain"
replace_path="history/countries"
replace_path="history/states"
replace_path="common/bookmarks"
replace_path="gfx/loadingscreens"

The end result should look like this (although there may be changes over time):

version="1.11"
tags={
	"Alternative History"
	"Balance"
	"Events"
	"Fixes"
	"Gameplay"
	"Graphics"
	"Historical"
	"Ideologies"
	"Utilities"
	"Translation"
	"Technologies"
	"Sound"
	"National Focuses"
	"Military"
	"Map"
}
replace_path="map/strategicregions"
replace_path="map/supplyareas"
replace_path="map/terrain"
replace_path="history/states"
replace_path="history/countries"
replace_path="common/bookmarks"
replace_path="gfx/loadingscreens"
replace_path="dlc/gfx/loadingscreens"
name="Foxhole Conquest: Dev Version"
supported_version="1.11.4"
path="C:/Users/PC/Documents/Paradox Interactive/Hearts of Iron IV/mod/FoxholeConquestDevVersion"

9. Enabling your mod:
Open the launcher.
Go to "playsets" on the left hand bar.
Check that all of the files in here are diabled.
Find the mod "Foxhole Conquest: Dev Version" and enable it.
When you launch the game it will now launch your mod files.

10. NOTE: Check with the Lead Programmer what branch of the files is being actively used at the current time. E.G. if we are not currently using the main MASTER branch of the files, you may need to change to the DEV-BRANCH or other branch.
To access these files open your GitHub Desktop and change the "Current Branch" tab to "dev-branch". (This will change the files that you have downloaded, although you may need to use the "Fetch origin" tab (one place to the right and "Pull" the files).
If you set up your files to paste to a different location you will also need to manually move these new files into your Hoi4 mod folder.

11. Open the Debug Mode and test.

12. At this point you can remove the extra descriptor file that you have been keeping around from step 5 as if the mod is running correctly it is no longer needed. If it is not running correctly there have been changes to the descriptor that a mod manager can advise you on how to adjust.
