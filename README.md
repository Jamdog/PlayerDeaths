# PlayerDeaths
### Current Version: 1.0
A Spigot plugin for minecraft servers that tells you where you last died, and allows moderators to teleport there.

Created by Jamdoggy and A_Brave_Panda for Mumbo Jumbo's Patreon server.

### Requirements
* MySQL Server

### Commands
* <b>/death</b>             - show location of your last known death
* <b>/death [player]</b>    - Show the last known death of the specified player
* <b>/death tp [player]</b> - Teleport to the location of the specified players' last known death

### Permission nodes
The following permission nodes may be used, usually with the PermissionEX server plugin, to restrict/allow access to some of the above commands:

* <b>death.others</b>   - Permission to allow looking at the death of another player
* <b>death.teleport</b> - Permission to allow teleporting to a death location

### Planned Updates
* It would be nice to save the players' inventory at the moment of death, and if, for example, they died in lava and lost everything, then the inventory could be loaded, or even specific items or types <em>(armour, weapons, tools, shulker boxes, blocks, etc...)</em>
