Unity NM Fighter
=============

#### Automatic Unity Fighter and coffer user  - addon for Ashita

Allows you to automatically continue to fight Unity NM's until you cap sparks.

### installation
Place UnityNMFighter folder with the lua file inside into the addons directory of Ashita, load in game via:

/addon load UnityNMFighter

### notes
Pet functionality and assistmode is NOT yet active

### enternity notes
If you use the ENTERNITY addon please set variables.EnternityActive to true

### settings
Settings can be changed using commands or by editing the SETTINGS section in UnityNMFighter.lua

### commands
The following commands are available and can be activated with the prefixes

***/unmf***,  ***/unitynmfighter*** or ***/unmfighter***

start - start the fighter

stop - stop the fighter and run the closer

shutdownoncap [bool] - Will /shutdown when the stop command is called or you reach capped sparks.

enternity [bool] - set to true if you use the addon ENTERNITY false otherwise

weaponskill [string] - The weaponskill name should be it's full name, for example Chant du Cygne

engagetype [int] - 1 FOR MELEE / 2 FOR PET

warptype [int] - 0 FOR NONE, 1 FOR RING, 2 FOR INSTANT WARP SCROLL, 3 FOR SPELL

pet [string] - THE SUMMONER PET TO USE

usecoffers [bool] - true or false 

petweaponskill [string] - The pet weaponskill to use

assistmode [bool] - true for enabled false for disabled
