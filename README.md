# ccSpigot
A paper fork that aims to prevent skylight lag and allow changing the server brand.
<br>
If you want to patch more exploits other than lightlag use my bukkit plugin https://github.com/moom0o/AnarchyExploitFixes
<br>
Don't say anything about those patches that have shit code! I don't know how to use git ROFL
## Config options
These options are in ccspigot.yml (we now have our own config!).

### light-update-max-time
Max time for light updates, this option is much better than disable-light-updates. 
### disable-light-updates
Disable ALL light updates! This will prevent all the lag that comes from them. DO NOT USE. USE LIGHT-UPDATE-MAX-TIME
### server-brand
Change the server brand from Paper to whatever you want! This is shown on futureclient/in the f3 menu.
### disable-chunk-relocation
This will disable the chunk relocation feature for when you have a corrupted world. This seems to have a ton of false positives for me. Remember this is experimental and may brick your server. It is disabled by default.
### limit-entity-speed
Experimental feature where you can restrict entity speed (Do not enable without first changing maxentityspeed to your liking, VERY buggy)
### debug-entity-speed
Shows you how fast players are going on entities so you can tweak max-entity-speed
### remove-console-spam 
Remove the console spam messages like Player_X went too fast!
## Changes from paper
### Autosave
The autosave is now using paper's instead of bukkit by default. This is a lot better.
This will only be used if you delete your paper.yml AND your bukkit.yml before using.
