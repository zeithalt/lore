# Global Map / Factions Game merger

> This document describes the rules for the Global Map / Factions Game during the experimental merge period between the two games.

For this experiment, we borrow the core elements from both games:
- Factions Game provides... factions. As well as the map, politics, and the schedule for battles;
- Global Map provides the actual battlefield as a dynamic representation of the map.

## Move order

> *Cycle* confusingly can refer to two things: 
> - generally - one full round of all factions' turns. 
> - during a battle - one hour of real-time when the score is measured.

There are six factions on the island:
- [Band of Brothers](<https://zeithalt.github.io/r/band_of_brothers.html>)
- [Cloudy Operatives](<https://zeithalt.github.io/r/cloudy_operatives.html>)
- [Cybernetics Inc](<https://zeithalt.github.io/r/cybernetics_inc.html>)
- [Delta Collective](<https://zeithalt.github.io/r/delta_collective.html>)
- [MindTech Institute](<https://zeithalt.github.io/r/mindtech_institute.html>)
- [Protectores Silva](<https://zeithalt.github.io/r/protectores_silva.html>)

The move order is determined by a random roll on our discord server at the beginning of each cycle.

There's also one more playable team: [Fighters Guild](<https://zeithalt.github.io/r/fighters_guild.html>) to represent team-less people offering their services for gold, but they do have a land on the map and do not get a turn in the move order.

## Schedule

> *[Eon](<https://zeithalt.github.io/r/eon.html>)* - a unit of time equal to IRL one day, but flexible for lore purposes.

> *[Key members](<https://zeithalt.github.io/rules/#rules_07_key_members>)* - most active members of the faction, who can make decisions on behalf of the faction.

Every faction's turn consists of four phases:

- ### Decision - up to 3 eons
  - it may end early when the decision is made; 
  - during this time, the faction needs to **confirm that they’re not skipping their turn**;  
  - if the deadline is missed - it’s an auto-skip, GM passes the turn to the next faction; 
  - this decision is announced at the end of the current eon, after which either the _preparation_ phase starts, or the faction skips their turn;
  - after the decision is made, the faction has until the end of the current eon to change their mind.

- ### Preparation - 3 days
  - this is a mandatory wait period before the attack window opens;
  - during this time, the faction has to choose their attack target and prepare for the battle.

- ### Attack window - up to 3 days
  - it may end early when the attack is initiated;
  - during this time, the faction may start their attack at any minute;
  - this can be done via discord's /gm_start_attack command by any key member;
  - a faction can only attack adjacent lands, 
  - if the deadline is missed - GM initiates the battle for them with a  disadvantage.;  
   
- ### Battle time - 3 days
  - battle ends on timer;
  - during this time, we play a global map battle in Influence;
  - it has its own big set of rules, key ones are listed below.

## Preparation actions and units

> [Actions](<https://zeithalt.github.io/rules/#rules_14_faction_actions>) - a set of in-lore events that factions can start to _influence_ the game. (discord only at the moment)

> [Map units](<https://zeithalt.github.io/rules/#rules_06_map_units>) - various units that can be moved around the map and give bonuses to faction in battle. (discord only at the moment)

These are discord game's features that allow factions to increase their base IP bonus in battles. 

The extra points acquired via these are translated into global map bonuses:
- initial bonuses are calculated as usual, say 300 vs 500;
- global map bonuses = 300 vs 500 = 300/1000 vs 500/100 = 30% vs 50%.

Only attacker and defender will get bonuses from these actions, other teams will have to do their surprise interventions in battles without them.

## Other Factions Game's features

There will be ***no feature parity*** with the current Factions Game during this experiment.

This means sell-swording might be limited, no payments from [Bank of Zeithalt](<https://zeithalt.github.io/r/bank_of_zeithalt.html>) for hits in battle, [Resources](<https://zeithalt.github.io/rules/#rules_16_resources>) cannot be used, Hall of Fame would not be updated, weapons won't have an effect and so on.

Some of these features may be implemented if I get enough development in-between battles during the cycle.

## Key Global Map rules
- a battle lasts **72** full cycles;
- one battle cycle lasts **1h;** 
- to capture a tile - win **1 cycle** on it;
- cooldown for attacking captured tiles again is **3 cycles**;
- you can only attack adjacent tiles, no air/coastal landing rules;
- "attacking early in the cycle" and big team bonuses are **disabled**;
- adjacency bonuses are **active**;
- sea attacks are not possible until later updates;
- we’re playing in the context of a [bigger map](<https://zeithalt.github.io/t/#index>), but the “play area” is only one region - this means tiles along the borders with other regions will always be possible to attack by that faction;


- <details>
    <summary>Example 1</summary>
  
  > - BB attacks CI in Cybertron Jungle;
  > - All tiles outside Cybertron Jungle are not attackable and cannot change ownership;
  > - Cybertron Jungle tiles along the green border have an outside connection to other CI lands, so CI can always attack them (except cooldown);
  > - Cybertron Jungle tiles along the pink border have an outside connection to another BB land, so BB can always attack them (except cooldown).
    > ![example1](https://zeithalt.github.io/lore/i//global_map_example1.png)
</details>

- the battle is in general 1 vs 1 (attacking vs defending faction);
- however, if a faction has an outside connection to the “play area”, they can play against both the attacker and the defender by declaring war on them during the battle;


- <details>
  <summary>Example 2</summary>

  > - DC attacks PS in Mt. Pickles
  > - DC progresses quickly and captures the majority of PS lands;
  > - But PS is in a pickle - they have only one tile to counter-attack if they quickly lose it all;
  > - In this situation, CI may open a new front against DC by invading Mt. Pickles from the east;
  > - CO too can join the battle directly, however, both MT and BB do not have a connection to the “play area” so their only options is supporting others according to global map diplomacy rules.  
  > 
  > ![example2](https://zeithalt.github.io/lore/i//global_map_example2.png)
</details> 

During this experiment, the Global Map battles happen in the context of the _Factions Game_ and within its fictional world called _Zeithalt Island_.

To learn more about it, you might want to check out these links:
- [Zeithalt Lore Guide](./guidebook.html) and [Mimbot Lore Database](<https://zeithalt.github.io/r/index.html>) can help you get acquainted with the lore;
- [Zeithalt Timeline](<https://zeithalt.github.io/t/#index>) holds the 2-year history of the world; 
- or you may ask questions on our [discord server](<https://discord.com/channels/562910943848169472/995639554042249246>).

-----
*This is the updatable draft of the rules - please ask questions and suggest changes [on discord](<https://discord.com/channels/562910943848169472/1284126907008417833>).*