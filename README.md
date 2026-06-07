# Sovereign

> *Build your colony. Forge your alliances. Shape your legacy.*

Sovereign is a Minecraft mod (NeoForge 1.21.1) that transforms your world into a living medieval fantasy civilisation. It bridges [MineColonies](https://www.curseforge.com/minecraft/mc-mods/minecolonies), [Hundred Years Warfare](https://www.curseforge.com/minecraft/mc-mods/hundred-years-warfare), and [Ice and Fire: Community Edition](https://www.curseforge.com/minecraft/mc-mods/iceandfire-ce) with a full grand strategy layer — giving your colony a world to negotiate with, trade with, go to war against, and leave its mark on.

The end result feels like *Kenshi met Bannerlord and built a kingdom in Minecraft*.

---

## The vision

Vanilla MineColonies gives you a deep colony to build. Hundred Years Warfare fills the world with NPC factions and armies. Ice and Fire populates it with dragons and mythical creatures. But none of these mods know the others exist.

Sovereign is the glue — and the world on top.

It tracks your colony's reputation with every faction in the world, drives diplomatic relationships through a living state machine, simulates faction economies and politics, and makes the consequences of every decision felt across the map. Kingdoms rise, fall, go to war, and forge alliances whether you are involved or not. The world breathes.

---

## Core features

### Diplomacy and reputation
- **Faction reputation system** — every faction tracks your standing dynamically, influenced by trade, combat, quests, gifting, and world events
- **Diplomatic state machine** — relationships move through states: `Unknown → Neutral → Friendly → Allied` and `Neutral → Tense → Hostile → War`
- **Ally and war declarations** — formally ally with factions, declare war, or be dragged in through your allies' conflicts
- **Sue for peace** — propose peace terms during war; offer tribute, territory, or prisoners. Faction personality affects whether they accept
- **Vassal system** — defeat factions and offer them vassalage instead of destruction. Vassals pay tribute and send troops but can revolt if mistreated
- **Gifting and favours** — send resources or military aid to improve standing. Help an ally's war to earn their gratitude
- **Spy and intelligence network** — hire spies to lift the fog of war on enemy military strength, economy, and territory
- **Assassination mechanics** — destabilise enemy leadership by targeting their rulers, triggering succession crises
- **Fame and notoriety** — the world knows who you are. Your reputation spreads and factions react to your deeds before you ever meet them
- **Titles and legacy** — earn titles through deeds: Warlord, Diplomat, Liberator, King, Emperor

### Territory and expansion
- **Faction territory** — every faction claims territory as a connected region. Borders are visible in the world
- **Border patrols** — factions send patrol units along their territory edges. Trespassing as a hostile triggers a response
- **Territory expansion** — factions and the player expand by capturing chunks. Original owners and their allies lose reputation with you
- **Consequences for expansion** — aggressive growth breeds enemies. Balance ambition with diplomacy
- **Visual battle scars** — sieges and battles leave marks on the landscape. Burned villages, crumbled walls, scorched fields tell the history of your world

### World simulation
- **Kingdom personalities** — each faction rolls a personality at world gen: aggressive, mercantile, isolationist, expansionist, paranoid, devout. Personality drives every AI decision
- **AI faction wars and alliances** — factions declare war on and ally with each other autonomously based on personality, territory disputes, and resource scarcity
- **Succession system** — faction rulers age and die. Heirs inherit, sometimes triggering instability, civil wars, or a change in personality
- **Villages linked to kingdoms** — factions own villages that supply them with resources. Capturing them weakens the parent faction. Liberating them earns reputation
- **Faction economy simulation** — each faction has dynamic resource levels (food, iron, gold) that drift based on seasons, wars, and trade. This drives prices, war likelihood, and desperation
- **War weariness** — prolonged wars drain faction morale and economy, eventually forcing peace
- **Refugees** — civilians flee wars and famines. They can settle in your colony, bringing skills and stories
- **Plague and disease** — mundane plagues spread between settlements, weakening faction populations and armies organically
- **Magical corruption** — distinct from mundane plague, magical corruption spreads from ancient ruins and cursed battlefields
- **Emergent world events** — famines, coups, trade route collapses, bandit surges, holy wars, prophecies. The world changes without your involvement

### Military
- **Large scale battles** — factions marshal hundreds of units in open field battles. Performance optimised with LOD and culling. Participate directly or observe
- **Siege system** — full castle siege mechanics: battering rams, siege towers, catapults. Defenders get boiling oil, arrow slits, and gate controls
- **Army rank system** — units progress from recruit to soldier, veteran, elite, and commander through combat. Rank affects stats, equipment, and morale
- **Prisoners of war** — capture enemy soldiers. Ransom them, recruit them, or trade them in peace negotiations
- **Mercenary factions** — unaligned companies sell their swords to anyone. Hire them for your wars; factions can hire them against you
- **Bandit factions** — organised bandit groups operate outside kingdom control, raiding trade routes and weak settlements
- **Allied military support** — allied factions dispatch reinforcements when you are under attack, scaled to your reputation and their strength
- **Ask allies for help** — proactively request military support during a losing war

### Economy and trade
- **In-world economy** — global supply and demand across all factions. Prices shift based on faction economy state, season, and war
- **War economy** — iron and food prices spike during conflicts, creating trading opportunities for neutral players
- **Trade routes** — establish caravans between your colony and allied factions for passive income
- **Diplomatic Post building** — a new MineColonies building that unlocks trade and formal diplomacy with nearby factions once relations are warm enough
- **Faction quests** — factions send requests: deliver resources, clear a dungeon, escort a caravan, assassinate a rival. Quest type driven by personality and economy state
- **Loot and spoils** — battles and raids generate wealth that flows through the faction economy

### Atmosphere and immersion
- **Seasons integration** — works with Ecliptic Seasons. Winter weakens agricultural factions and triggers famine events. Spring brings recovery and expansion
- **Wandering heroes** — named NPCs roam the world, take contracts, and can be recruited as commanders or become rivals
- **Travelling merchants and caravans** — move between towns on roads. Raiding them is profitable but costly to your reputation
- **Inns and taverns** — NPCs gather, gossip, and share rumours. A source of intelligence and quests
- **Festivals and celebrations** — factions hold seasonal events. Attending or sponsoring them builds standing
- **Religions and cults** — factions follow faiths that drive holy wars, pilgrimage quests, and inter-faith tension. Dark cults work toward summoning something terrible — a late game threat
- **Cultural identity** — each faction has unique banners, architecture style, and unit naming. No two kingdoms look alike
- **Orders of knights and mages** — special faction types with unique recruitment, abilities, and political influence
- **A world chronicle** — an in-game history book that records what has happened in your specific world. Read the story of your campaign
- **Dynamic ambience** — ambient sounds tied to faction activity nearby. Smoke on the horizon when a distant village burns

### Dragon and mythical factions
- **Dragon territory** — Ice and Fire CE dragon nests form their own faction. Land near a nest is their domain
- **Dragon aggression scaling** — dragons grow more aggressive as your colony expands into their territory
- **Dragon diplomacy** — with enough effort, dragon factions can be moved from hostile to neutral to, eventually, allied
- **Dragon tamers guild** — players who tame dragons can form a special sub-faction with unique political weight
- **Other mythical creature factions** — other Ice and Fire creatures organise into factions with their own territory and behaviour

---

## Mod dependencies

| Mod | Role |
|---|---|
| [MineColonies](https://www.curseforge.com/minecraft/mc-mods/minecolonies) | Colony building and NPC management |
| [Structurize](https://www.curseforge.com/minecraft/mc-mods/structurize) | MineColonies dependency |
| [Hundred Years Warfare](https://www.curseforge.com/minecraft/mc-mods/hundred-years-warfare) | External NPC factions, armies, and siege warfare |
| [Ice and Fire: Community Edition](https://www.curseforge.com/minecraft/mc-mods/iceandfire-ce) | Dragons and mythical creature factions |

### Recommended companions

| Mod | Role |
|---|---|
| [Ecliptic Seasons](https://www.curseforge.com/minecraft/mc-mods/ecliptic-seasons) | Dynamic seasons, weather, and atmosphere |
| [Dungeons Arise](https://www.curseforge.com/minecraft/mc-mods/dungeons-arise) | Dungeons and ancient ruins with lore |
| [Terralith](https://www.curseforge.com/minecraft/mc-mods/terralith) | Procedural world generation variety |

---

## CS concepts in action

Sovereign is also a living exercise in applied theoretical computer science:

| Concept | Application |
|---|---|
| Graph theory | Faction reputation network (weighted directed graph), territory as connected region graphs, trade route pathfinding |
| Finite automata | Diplomatic state machine, faction AI behaviour states, siege phase progression |
| Horn clause logic | Faction decision rules ("if reputation > 50 AND colony wealth > X THEN offer trade") |
| Simulation | Faction economy drift, war weariness, plague spread, succession instability |
| Procedural generation | Kingdom personality rolling, world event generation, wandering hero naming |

---

## Roadmap

### Phase 1 — Foundation
- [ ] NeoForge 1.21.1 dev environment
- [ ] MineColonies + HYW + IceAndFire CE running together, stable
- [ ] RPG progression mod for personal character selected
- [ ] Supporting content mods (dungeons, world gen, QoL)

### Phase 2 — Content
- [ ] Full modpack stable and playable end to end
- [ ] Seasons integration via Ecliptic Seasons
- [ ] Full playtest before writing custom code

### Phase 3 — Sovereign core
- [ ] MineColonies and HYW API audit
- [ ] Territory system — faction land claims and borders
- [ ] Faction reputation data model
- [ ] Diplomatic state machine
- [ ] Kingdom personality system
- [ ] Reputation change events
- [ ] Ally and war declarations
- [ ] Sue for peace system
- [ ] Diplomatic Post building
- [ ] War state — faction sieges
- [ ] Border patrols
- [ ] Reputation and diplomacy journal HUD

### Phase 4 — World simulation
- [ ] AI faction wars and alliances
- [ ] Territory expansion and consequences
- [ ] Faction economy simulation
- [ ] Villages linked to kingdoms
- [ ] In-world economy and trading
- [ ] Seasons affecting faction food and war likelihood
- [ ] Succession system
- [ ] Wandering heroes
- [ ] Spy and intelligence network
- [ ] Assassination mechanics
- [ ] Emergent world events
- [ ] Plague and disease
- [ ] Magical corruption
- [ ] War weariness and prisoners of war
- [ ] Refugees
- [ ] Mercenary and bandit factions

### Phase 5 — Military depth
- [ ] Army rank system
- [ ] Large scale battle system
- [ ] Siege system
- [ ] Allied military support
- [ ] Vassal system
- [ ] Faction quests

### Phase 6 — Atmosphere and immersion
- [ ] Fame and notoriety system
- [ ] Titles and legacy
- [ ] Religions and cults
- [ ] Cultural identity per faction
- [ ] Orders of knights and mages
- [ ] Travelling merchants and caravans
- [ ] Inns, taverns, and rumour system
- [ ] Festivals and seasonal celebrations
- [ ] World chronicle
- [ ] Visual battle scars on landscape
- [ ] Dragon and mythical creature factions
- [ ] Dynamic ambience

### Phase 7 — Polish and release
- [ ] Balancing pass
- [ ] Packaged as Modrinth modpack
- [ ] Sovereign published on Modrinth

---

## Tech stack

- Java 21
- NeoForge 1.21.1
- Gradle
- MineColonies API (IColony, IBuildingManager, colony events)
- HYW faction and unit API
- Ice and Fire CE creature and faction API

---

## Contributing

Contributions welcome. If you want to help build the most ambitious colony-builder mod ever made, open an issue or a PR.

---

## License

MIT — see [LICENSE](LICENSE) for details.

---

*Built by a software engineer who just wanted Bannerlord and MineColonies to be the same game — and ended up building a world.*
