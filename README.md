# KZTierMapchooser
This is a modification of SourceMod's mapchooser, adding the tiers of maps in the vote menu

## Screenshots
![alt text](https://github.com/Kidev/KZTierMapchooser/raw/master/screenshots/votemap.jpg "Vote menu with tiers")

## Download
You can download the compiled plugin from [here](https://raw.githubusercontent.com/Kidev/KZTierMapchooser/master/compiled/mapchooser_tier.smx)

## Dependencies
This plugin uses:
- SourceMod 1.10.0
- SteamWorks (edited in include/, to use the latest SourcePawn declaration style)
- SMJansson (edited in include/, to use the latest SourcePawn declaration style)
- KZTimerGlobal.com's maps API

## Build instructions on Windows (for any server OS)
- Download the latest SourceMod for Windows from [here](https://www.sourcemod.net/downloads.php?branch=stable)
- Copy the current repo inside "sourcemod-xxxx-windows/addons/sourcemod/scripting/"
- In "sourcemod-xxxx-windows/addons/sourcemod/scripting", drag and drop "mapchooser_tier.sp" into "compile.exe"
- The compiled plugin "mapchooser_tier.smx" is now inside "sourcemod-xxxx-windows/addons/sourcemod/scripting/compiled/"

Do not forget to remove any other mapchooser from your active plugins directory

## Known bugs
None, please use the "Issues" tab if you find any

## TODO
- Add tiers to the !nominate menu
- Add a completion marker using KZTimerGlobal.com's players API
- Turn the edited part of this code into an easy to use API, so that any mapchooser could easily add tiers to its plugin