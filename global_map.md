# Global Map / Factions Game merger

> This document describes the rules for the Global Map / Factions Game during the experimental merge period between the two games.

For this experiment, we borrow the core elements from both games:
- Factions Game provides... factions. As well as the map, politics, and the schedule for battles;
- Global Map provides the actual battlefield as a dynamic representation of the map.

## Changes in the Factions Game rules

Every faction's turn consists of four phases:

- **decision - 3 days**  
  during this time the faction needs to **confirm that they’re not skipping their turn**;  
  if the deadline is missed - it’s an auto-skip, GM passes the turn to the next faction;

- **preparation - 3 days**  
  during this time the faction has to choose their attack target, which __has to be announced to GM__ before the time attack window opens;

- **attack window - 3 days**
  during this time the faction may start their attack at any minute, to initiate the battle they may use with the discord command;
  if the deadline is missed - GM initiates the battle;  
  _note: I may not be able to automate this in time, in this case I'll have to start the battle manually. Please plan accordingly;_

- **battle time - 3 days**
  during this time we play a global map battle in Influence with the modified rules to allow for a faster gameplay.

Doing preparation actions / forts / units etc still possible, but they’re translated into global map bonuses for the factions:
- initial bonuses are calculated as usual, say 300 vs 500;
- global map bonuses = 300 vs 500 = 300/1000 vs 500/100 = 30% vs 50%.

There will be ***no feature parity*** with the current Factions Game during this experiment.

This means sell-swording might not be possible, no payments from BoZ for hits in battle, RES cannot be used, Hall of Fame would not be updated and so on.

Some of these features may be implemented if I get enough development time in advance or during the cycle.

## Changes in the Global Map rules
- a cycle lasts **1h;**
- to capture a tile - win **1 cycle** on it;
- cooldown for attacking captured tiles again is **3 cycles**;
- you can only attack adjacent tiles, no air/coastal landing rules;
- "attacking early in the cycle" and big team bonuses are **disabled**;
- adjacency bonuses are **active**;
- sea attacks are not possible until later updates;
- we’re playing in the context of a bigger map, but the “play area” is only one region - this means tiles along the borders with other regions will always be possible to attack by that faction;

> ### Example 1:
> - BB attacks CI in Cybertron Jungle
> - All tiles outside Cybertron Jungle are not attackable and cannot change ownership;
> - Cybertron Jungle tiles along the green border have an outside connection to other CI lands, so CI can always attack them (except cooldown);
> - Cybertron Jungle tiles along the pink border have an outside connection to another BB land, so BB can always attack them (except cooldown);  
> ![example1](./img/global_map_example1.png)

- the battle is in general 1 vs 1: attacker vs defender, however, if a faction has an outside connection to the “play area” - they can play against both the attacker and the defender by declaring war on them during the battle;

> ### Example 2:
> - DC attacks PS in Mt. Pickles
> - DC progresses quickly and captures the majority of PS lands;
> - But PS is in a pickle - they have only one tile to counter-attack if they quickly lose it all;
> - In this situation, CI may open a new front against DC by invading Mt. Pickles from the east;
> - CO too can join the battle directly, however, both MT and BB do not have a connection to the “play area” so their only options is supporting others according to global map diplomacy rules.  
> 
> ![example2](./img/global_map_example2.png)

During this experiment, the Global Map battles happen in the context the _Factions Game_ and within its fictional world called _Zeithalt Island_. 

To learn more about it, you might want to check out the [Zeithalt Lore Guide](./guidebook.html), [Mimbot Lore Database](<https://zeithalt.github.io/r/index.html>) or just ask questions on our [discord server](<https://discord.com/channels/562910943848169472/995639554042249246>).

-----
*This is the updatable draft of the rules - please ask questions and suggest changes [on discord](<https://discord.com/channels/562910943848169472/1284126907008417833>).*