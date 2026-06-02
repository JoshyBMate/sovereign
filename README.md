# Sovereign

> *Build your colony. Forge your alliances. Survive your enemies.*

Sovereign is a Minecraft mod (NeoForge 1.21.1) that bridges [MineColonies](https://www.curseforge.com/minecraft/mc-mods/minecolonies) and [Hundred Years Warfare](https://www.curseforge.com/minecraft/mc-mods/hundred-years-warfare) with a living faction diplomacy system — giving your colony a world to negotiate with, trade with, and go to war against.

---

## The vision

Vanilla MineColonies gives you a deep colony to build. Hundred Years Warfare fills the world with NPC factions and armies. But neither mod knows the other exists.

Sovereign is the glue. It tracks your colony's reputation with every HYW faction in the world, drives diplomatic relationships through a state machine, and makes the consequences of those relationships felt — in trade, in quests, in raids, and in the dragons that circle your walls.

The end result: a game that feels like *Kenshi met Bannerlord and built a house in Minecraft*.

---

## Core features

- **Faction reputation system** — every HYW faction tracks your colony's standing on a dynamic scale, influenced by trade, combat, quests, and world events
- **Diplomatic state machine** — relationships progress through states: `Unknown → Neutral → Friendly → Allied` and `Neutral → Tense → Hostile → War`
- **Diplomatic Post building** — a new MineColonies building that unlocks trade and diplomacy with nearby factions once relations are warm enough
- **Faction raids** — when a faction declares war, they marshal HYW forces and target your colony directly; scale of the assault reflects their military strength
- **Allied support** — allied factions can dispatch soldiers to defend your colony when you're under attack
- **Faction quests** — factions periodically send requests (deliver resources, clear a dungeon nearby); completing them builds rep, ignoring them costs it
- **Faction economy simulation** — each faction has dynamic resource levels that drive what they want and what they'll pay
- **Emergent world events** — factions go to war with each other, plagues hit, trade routes collapse; the world changes whether or not you're involved
- **Reputation journal** — an in-game screen showing all known factions, your standing with each, and their current diplomatic state
- **Ice and Fire integration** — dragon nests act as a special hostile faction type; aggression scales as your colony grows

---

## Mod dependencies

| Mod | Role |
|---|---|
| [MineColonies](https://www.curseforge.com/minecraft/mc-mods/minecolonies) | Colony building and NPC management |
| [Structurize](https://www.curseforge.com/minecraft/mc-mods/structurize) | MineColonies dependency |
| [Hundred Years Warfare](https://www.curseforge.com/minecraft/mc-mods/hundred-years-warfare) | External NPC factions and armies |
| [IceAndFire Community Edition](https://www.curseforge.com/minecraft/mc-mods/iceandfire-ce) | Fantasy creatures and dragon factions |

---

## Project roadmap

### Phase 1 — Foundation
- [ ] NeoForge 1.21.1 dev environment setup
- [ ] MineColonies + HYW running together, stable
- [ ] Personal character RPG progression mod selected
- [ ] Supporting content mods (dungeons, world gen, QoL)

### Phase 2 — Content
- [ ] Full modpack stable and playable end-to-end
- [ ] Ice and Fire CE integrated and tested

### Phase 3 — Bridge mod (Sovereign core)
- [ ] MineColonies and HYW API audit
- [ ] Faction reputation data model (weighted graph, NBT persistence)
- [ ] Diplomatic state machine implementation (FSM)
- [ ] Reputation change event hooks
- [ ] Diplomatic Post building
- [ ] War state — faction raids via HYW
- [ ] Reputation journal HUD

### Phase 4 — Custom features
- [ ] Faction quests
- [ ] Faction economy simulation
- [ ] Allied military support
- [ ] Emergent world events
- [ ] Ice and Fire dragon faction integration

### Phase 5 — Polish and release
- [ ] Balancing pass
- [ ] Packaged as CurseForge / Modrinth modpack
- [ ] Sovereign mod published on Modrinth

---

## Tech stack

- Java 17
- NeoForge 1.21.1
- Gradle
- MineColonies API (IColony, IBuildingManager, colony events)
- HYW faction entity API

---

## CS concepts applied

This project is also a learning exercise in applied theoretical computer science:

- **Graph theory** — faction reputation network (weighted directed graph)
- **Finite automata** — diplomatic state machine
- **Horn clause logic** — faction decision rules ("if reputation > 50 AND colony wealth > X THEN offer trade")
- **Simulation** — faction economy drift over time

---

## Contributing

Contributions welcome! If you're interested in Minecraft modding, medieval fantasy, or just want to help make the best colony builder on the planet, open an issue or a PR.

---

## License

MIT — see [LICENSE](LICENSE) for details.

---

*Built by a software engineer who just wanted Bannerlord and MineColonies to be the same game.*
