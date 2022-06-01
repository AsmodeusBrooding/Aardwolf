# Khadaji's Aardwolf Affects Window

Located here is the animated affects window plugin for the Aardwolf MUSHclient.
The plugin can provide a visual cue to knowing when you're spelled up, unspelled, or when 
your spells are GOING to run out, giving you proper time to know you should re-up your
sanctuary or other important spells before starting a tough battle.
This plugin is also very useful for PK, as you can easily see if you're cursed, blinded,
webbed, etc without spending precious time to check.


https://user-images.githubusercontent.com/56989870/171307785-9dc19e0f-c718-424f-ae9d-ed7a3d233d77.mp4


You can grab this entire subdirectory by following this link:

https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/AsmodeusBrooding/Aardwolf/tree/main/Affects%20Window/worlds/plugins


To install this plugin, just drag the images folder over your images folder, and confirm overwriting if necessary.
You can then put the xml file of your choice into the /worlds/plugins folder.

You can install AARDWOLF_AFFECTS_BETA.xml if you DON'T want the auto spellup functionality, or you can install
AARDWOLF_AFFECTS_SPELLUP.xml if you DO want spellup functionality. The SPELLUP plugin was built mostly by Hadar, with help from me.


If affects aren't showing up, make sure you've got TAGS ON, and more specifically,
SPELLUP tags set to on, and on your next spellup the affects should show up.

If they're still not showing up, you've placed the images into the wrong place somehow.


------------------------------------------------TO DO --------------------------------------------------------

- [x] Toggle spellup tags on by default upon startup.

- [x] Add grey SPELL_DOWN icons for all existing icons

- [x] Make time numbers higher than 10 minutes show green, more than 2 minutes show yellow, and under 2 minutes show red.

- [x] Fix drawing of timers when window is vertically aligned

- [x] Add right click system to set priorities

- [x] Add click to cast system

- [ ] Add icon for NO FORGE, when forge is on cooldown, so you can tell your friends "sorry, i can't forge for XX more minutes"

- [ ] On login, reconnect, etc, type aflags to check for perm sanc and other effects. Check saf sanc and aflags?

- [ ] Get AARD equipment working

- [ ] If sanctuary is ON via some methods, and you wear the sanc aura, leave the timer and when it falls if the aura is on
change timer to PERMA

- [ ] Add PERMA or infinity timer for AARD eq, and hunger/thirst

- [ ] Add protection good icon

- [ ] Add protection evil icon

- [ ] Handle wraith form

- [ ] Add a ton more spells/icons to the affects table

- [ ] When logging on use priority system to load grey images of all priorities


----------------------------------------------------------------------------------------------------------
