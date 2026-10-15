# Hollowmere: Bloodline

A mobile-first, text-based RPG in a single file. Open `index.html` in any browser (or host it on GitHub Pages). Progress auto-saves to the device.

**The loop:** train as a weakling, hunt monsters, join the Lanternwatch Guild, complete contracts, get stronger, die. Your heir inherits gold, gear and the town's goodwill (not levels or skills) and catches up with boosted XP and training.

## What's in it
- **Six regions** to hunt and **explore** (0-100% each). 46 choice-driven events with stat checks, ambushes, merchants, shrines and curses.
- **13 dungeons**: generated room maps with fog of war, locked boss doors, keys guarded by wardens, secret vaults, traps, mimics, shrines, rest springs, lore, NPCs, mini-bosses, and bosses with a second phase. Progress is saved if you leave through the entrance.
- **6 puzzle types**: riddles, lever sequences (logic clues), combination locks (Mastermind), rune memory, three doors (one plaque tells the truth), and offering scales.
- **37 side quests** with branching choices, wilderness wanderers, quest-specific events, and lasting **town perks** that carry to your heirs.
- **Crypt of Heirs**: fight echoes of your dead ancestors for permanent bloodline blessings.
- Bestiary (+1% damage per 10 kills of a species), timed buffs/curses, 30 hand-made legendaries (12 dungeon-exclusive), procedural gear with well over 100k combinations, skills, guild contracts and ranks, and the Tinker's Wagon.

## Party, relics and power spikes
- **14 companions** with distinct roles (tank, healer, rogue, pyromancer, cryomancer, alchemist, bard, berserker, assassin, paladin, druid, necromancer, archer, automaton). They fight automatically, and you can queue **Orders** to fire their specials. They level with you and have bond levels and personal quests.
- **Synergies**: pairings like Tank + Healer or Pyromancer + Cryomancer grant party-wide bonuses, and combat combos (Conflagration, Shatter, Toxic Burst, marks, stuns) reward mixing statuses.
- **17 relics** (two slots, kept by heirs). Some combinations trivialize content on purpose, such as the Prism of Synergy with the Ember Heart.
- **Challenge** setting (Story to Nightmare) and the endless **Abyss Stair**, which scales from your own level, absorb power creep.

## Pacing & mastery
- Hunting is the core loop: find a monster, kill it. Each kill builds **familiarity** with the region. Dungeons, wanderers and a rare special find while hunting appear as familiarity grows, and Scouting unlocks at 20%.
- Skills level up **through use** (max Lv 10). Spamming one skill slows its gain, while neglected skills train up to twice as fast, so rotating abilities makes you stronger overall.

## Earning trust (no hiring)
Companions can't be bought. You meet them naturally (tavern regulars who notice you as you progress, captives in dungeons, people from quests), then build **trust** three ways: one conversation a day each (their personality decides how your answers land), **temporary work** (they fight beside you for 5 fights and you're scored on how well you gel), and a **personal trial** they set once you're close. Pass it and reach 50 trust, and they offer to join. Fail a trial and you can retry after a few days.

## Encounters, packs and the codex
- Enemy levels follow a **bell curve** around yours, with rare out-of-depth monsters. The encounter screen flags them, and you can **slip away** (chance based on level gap and AGI; failure lets it strike first).
- Some creatures appear in **packs** that hit harder at full strength and weaken as you thin them out.
- Every monster has a **procedurally drawn SVG icon** (generated per species, with elite and boss markers).
- The **Codex** (Journal) lists every creature by region and dungeon, with native level range, how hard it is for *you* right now, observed moves and hunting tips.

## A new cast every generation
Companions are **procedurally generated**: each generation gets a fresh cast of 14, built from 17 role archetypes (tank, healer, pyromancer, marksman, monk, hexcaster, and more) with random names, personalities and tones, ability names, passives, traits, stat variance, trial and personal quests, and a drawn portrait. They are placed in tavern, dungeon and quest slots. When you fall, your companions retire; those you bonded with (bond 3+) become **Veterans** who pass a share of their gifts on to your heirs, and your heir meets a brand-new cast and earns their trust all over again.

## Backgrounds, paths, seasons, estate and bounties
- **Backgrounds:** each life starts as a Soldier, Scholar, Thief, Hunter, Acolyte, Noble, Farmhand or Wanderer (stats, a free skill, a perk). Repeating one builds a **family tradition** (+5% potency per past generation, max +25%).
- **Paths:** at level 10 choose Bladeborn, Arcanist or Warden. The skills you master through use ("discipline") feed it, with new tiers at levels 20 and 30.
- **Time, seasons and weather:** the time of day follows your stamina, seasons last 30 days, and weather is rolled every morning. They change which creatures appear, elemental damage, loot and XP, and fog hides enemy danger.
- **Estate (earned, never bought outright):** you begin with nothing: no gold, items, skills or land. Complete the Safe Roads quest and reach Copper rank and the town grants a plot. Housing tiers need contract/dungeon/bounty/Abyss milestones plus time and materials. Staff cannot be hired: they turn up on their own after years on the land and a favour done, and grow with service. Facilities (farm, tavern stake, mine, trading company, dojos, academy, barracks) unlock through quests and mature over time. Heirs inherit the estate.
- **Bounty board:** the guild posts hunts for specific creatures from your Codex, including Notorious elites that start turning up once you accept. Bounty rank grows with marks.
- **Mobile:** auto-battle, text size, vibration, battle speed, contextual tips (not a tutorial), and installable offline files (`manifest.webmanifest`, `sw.js`, icons) when hosted on GitHub Pages or similar.

## First errand and Aspects

- **Nothing but honest work:** the first thing a new hero can own comes from an errand with no fighting. Mira the Baker needs flour sacks hauled (three Training Yard sessions), then pays in a tunic and boots, or a kitchen knife and a loaf. Only the first generation gets this.
- **Aspects:** joining the guild kindles a first aspect (more at Bronze and Gold rank). You are offered three random ones. Each grants a skill and a scaling bonus, and certain pairs form a **harmony** with extra bonuses.
- **Monster cores:** once you have an aspect, kills can leave cores (elites and bosses far more often). Cores deepen an aspect's depth, capped by guild rank. Heirs kindle their own aspects.

### Wicks, vestiges and powers

- **Wicks** are the lantern-light monsters leave behind once you have an aspect. They are scarce: normal kills rarely drop one, elites more often, bosses almost always. They deepen aspects, bind vestiges and reroll aspect offers.
- **Vestiges** are rare fragments of a monster family. There are 26 families (beast, wolf, boar, vermin, stag, bird, undead, wraith, leech, spider, slime, golem, knight, troll, imp, goblin, tree, sprite, eye, maw, mimic, crab, archer, dragon, frost, fire). Grade follows the monster's tier, and the rarer families (mimic, maw, dragon, troll, knight, eye) drop far less often.
- Binding a vestige costs wicks and teaches the family's **power**. A duplicate strengthens it. Rank limits how many powers you can hold.
- **Resonance:** every power lists the aspects it works with. If you hold one, the power is 1.75x stronger.
- **Bloodline memory:** from the second generation on, an heir can rekindle some ancestral powers for wicks, one level weaker. Aspects, skills and levels are not inherited.

## Title screen and a slower opening

The game now opens on a title screen: **Begin a New Story**, **Continue** (shows your hero, level, day and generation), **Load** (paste Export text or pick a file) and **Settings** (text size, vibration, tips). A new story eases in through a three-line prologue, then your name, then a single-background chooser that shows one background's details at a time. The Menu has a **Return to title screen** button.

## Sleeping where you are

The sleep animation now shows a dark silhouette of wherever you rest: the town's rooftops, the meadow, the woods, the catacombs, the ashen cliffs, the frost or the rift, or a dungeon's entrance with torches. Away from town you also see a tent and campfire. You can camp from any region card or dungeon entrance in the Hunt screen ("Camp until morning"). The new-story background tiles also no longer reload on every tap.

## A world that keeps its secrets

- **You only know what you have been told.** A new hero sees one place outside the gate, no bosses, no guild, no estate, and no list of townsfolk. Other regions, boss lairs and boss names are learned from people: **Listen in** (free, once a day) or **buy a round** at the tavern, the **guild contract board** once you have found the guild, favours done for neighbours, and by simply spending time in a region (a lair reveals itself around 40% familiarity, though not its name).
- **The Town Square** is a place to look around, not a list. Once a day you can work the crowd, and someone with a problem may wave you over. Wanderers on the road are strangers until you talk to them.
- **Years, not days.** Life is measured in age. A year is 120 days (four 30-day seasons), heroes start between 16 and 19, and old age takes each one somewhere between 64 and 74. Combat is still the main killer.
- **Things have something to say.** Materials come with a short quip the first time you find them (and in the Pack), and every item type has its own one-liners on its detail sheet and in drop results.
