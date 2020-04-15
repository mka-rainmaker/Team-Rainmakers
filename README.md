# WIP - Team Rainmakers

Current release - *no release available yet*

Action-adventure survival video game with RPG and strategy elements built with Unity.

The purpose of this repository is to learn Unity, build all basic mechanics (character controller, GUI, interactions, inventory, crafting, quests, dialogs, weapons, AI), share knowledge and help other enthusiasts.

** Game idea is big enough for at least the mid-size agency, and insanely big for the indie, therefore I clearly understands that this might be endless project **

Must-have point before starting any development is to clearly define plot, game philosophy, objects and etc.

# Pre-requirements

Free Unity assets

[Blockout](https://assetstore.unity.com/packages/tools/level-design/blockout-100388)
[Simple FPS Controller](https://assetstore.unity.com/packages/tools/input-management/simple-fps-controller-162291)

# Game features
- Lowpoly design
- 1st/3rd person character controller
- Range/melee weapons
- Inventory with limit on capacity
- Character abilities
- Rotten shall kill player in average by 3 attacks or by 1 bite

# Plot

A global pandemic occurred which decimated the globe (yeah-yean, I know that's corny), turning millions of humans into feral cannibalistic creatures, called Rottens.
Those who managed to survive, united into guilds and built their own shelters, fighting against Rottens and ... other guilds.

# Guilds

There are 8 major guilds on the map, every with it's special ability. Player can choose guild on the game start or join another after (requires special quest to complete).
Based on the relations between guilds, their members will either help, ignore or attack the player.
Player has it's own reputation across guilds.

### Resolute Ancients
<img src="https://github.com/mka-rainmaker/Team-Rainmakers/blob/master/Assets/Guilds/Resolute%20Ancients.png" width="48" />

Special ability - increased stamina and regeneration

### Refugees of the Lion
<img src="https://github.com/mka-rainmaker/Team-Rainmakers/blob/master/Assets/Guilds/Refugees%20of%20the%20Lion.png" width="48" />

Special ability - the roar of the lion, chance that enemies will drop their weapons and run away, increased range and melee damage

### Blackshapers
<img src="https://github.com/mka-rainmaker/Team-Rainmakers/blob/master/Assets/Guilds/Blackshapers.png" width="48" />

Special ability - 50% bonus on melee weapons

### Fire Maggots
<img src="https://github.com/mka-rainmaker/Team-Rainmakers/blob/master/Assets/Guilds/Fire%20Maggots.png" width="48" />

Special ability - put enemy/object on fire

### Gang of the Bound
<img src="https://github.com/mka-rainmaker/Team-Rainmakers/blob/master/Assets/Guilds/Gang%20of%20the%20Bound.png" width="48" />

Special ability - drive any vehicle

### Mighty Jackals
<img src="https://github.com/mka-rainmaker/Team-Rainmakers/blob/master/Assets/Guilds/Mighty%20Jackals.png" width="48" />

Special ability - pickable items are highlighted around character

### Green Berets
<img src="https://github.com/mka-rainmaker/Team-Rainmakers/blob/master/Assets/Guilds/Green%20Berets.png" width="48" />

Special ability - maximum weapon accuracy, cam carry more weapons at once

### Uno Solo
<img src="https://github.com/mka-rainmaker/Team-Rainmakers/blob/master/Assets/Guilds/Uno%20Solo.png" width="48" />

Special ability - attack and armom bonuses when solo

# Shelters

There are 3 types of shelters.

Underground - stronghold, that is close to impossible to capture because of only 1 entrance, but also hard to get out when surrounded by Rottens.
Camp - located on open field. Defense depends on the building type, but easy to get out.
Water camp - located on lakes and rivers with 2-3 entrances, same advantages/disadvantages of underground shelter.

Every guild has their own shelter and one for Player (Camp type only).

Every shelter has the following characteristics (visible to the guild members only):
- Population
- Defense status
- Current needs

If guild members are not supplying shelter enough, population gets lower, and guild can even dissapear at all.

# Game philosophy

That's simple moral choice - help others or conquer them.
And, despite other games, this should be HARD. 
Player should carefully count every single bullet you find, every bottle of water or food. 
Player can not beat Rotten's horde alone.


# Quest types

Expedition - search for items in abandoned buildings (stores, markets, etc) for the supply items.
Freelance - explore the map, find others who survived, fight against enemies. Basically - do everything you like
Battle - help your guild members to capture enemy shelter or their supplies
Plot quests

Expedition quests requires the following scenes to be designed:
- 5 hospitals/clinics
- 5 supermarkets/store
- 5 small villages
- 5 plants/fabrics
- 5 urban districts
