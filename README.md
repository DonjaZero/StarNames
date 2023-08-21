# Star Names

Star Names is a lightweight addon for The Elder Scrolls Online (ESO). It displays the names of the stars in the Champion Point (CP) constellations so that players no longer have to hover over each one to find the one they're seeking.  This is especially handy for character re-specs or when making new builds using unfamiliar CP stars.

Requires: LibAddonMenu-2.0

## Features

* Streamlined settings menu to customize the font size and color of star names based on star type
* Optional custom keybind to toggle display of star names
* A `/starnames` command to disable, enable, or toggle display of star names
* Option to disable display of star names on the main CP screen only (to avoid an overcrowded look)

## What it does

Star Names makes manual Champion Point changes easier and more convenient by eliminating the need to hover over each star in order to see its name.  It is based in part on code from Dynamic CP by Kyzeragon which automatically exposes in-game data like star name and type via the GUI. Star Names provides that functionality, along with additional features and performance improvements, without the additional complexity and overhead of a full-featured CP management automation solution.

## What it doesn't do

Star Names does **NOT** automate any Champion Point management actions such as automatic saving, slotting, or re-spec'ing of CP.  If you require those features, please consider using Dynamic CP by Kyzeragon instead.  These can be used with some other CP management addons like Jack of all Trades for even more options and fine-tuned control over automatic CP management.

## Known issues

* The values in the settings menu do not update if it is open when the `/starnames` command or a hotkey is used to turn on/off the display of star names (close and re-open the settings menu to see the current values)
* While both Star Names and Dynamic CP will run side-by-side without errors, changes to settings that affect the display of star names in one may override settings in the other

## Releases

Releases in the form of a ZIP file that one may extract to their ESO "AddOns" folder are provided in the "releases" subdirectory.  Be sure to extract all, including the folder name!

It's now also available on ESOUI and via Minion, the MMOUI addon manager.
