# Star Names

Star Names is a simple addon for Elder Scrolls Online (ESO) that shows or hides the names of the stars in the Champion Point (CP) constellations so that users no longer have to hover over each one to find the one they're seeking.  This is especially handy for character re-specs or new builds using unfamiliar CP stars.

Requires: LibAddonMenu-2.0

## Features

* An addon settings menu that allows one to customize the font size and color used for the star names based on whether the star is a passive, slottable, or cluster (subtree)
* The ability to bind a custom hotkey for toggling the names of the stars on or off
* A `/starnames` command to turn the display of star names on or off explicitly, or to toggle between the two, via the chat window

## What it doesn't do

Star Names does not provide any Champion Point management features like CP saving, slotting, or re-spec'ing.  There are many addons that provide those features, but those are often "heavyweights" maintained by world-class developers that deal with the complexities of changes in the CP system and adjacent game systems like the Armory. The ability to display CP star names is rare, and one may experience unexpected and undesirable behavior if they run multiple of these types of addon just to get that feature.

Star Names is designed as a lightweight addon that provides the ability to quickly identify CP stars without conflicting with the CP management features of other addons. 

## Known issues

* May conflict with similar functionality in an addon called "Dynamic CP" if both addons have the feature to display star names/labels enabled (if you use Dynamic CP as your CP manager, you probably will not want to use this separate addon)
* The settings menu toggle to show/hide star names currently does not update if it is open when one uses the `/starnames` command or a bound hotkey to turn on/off the display of star names (the value in the settings menu will be updated when you re-open it)

## Releases

Releases in the form of a ZIP file that one may extract to their ESO "AddOns" folder are provided in the "releases" subdirectory.  Be sure to extract all, including the folder name!

It's now also available on ESOUI and via Minion, the MMOUI addon manager.
