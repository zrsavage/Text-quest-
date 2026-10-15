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
- **Estate (a gold sink your heirs inherit):** housing tiers, 7 kinds of staff, 4 businesses, and training grounds (dojos, an academy, barracks).
- **Bounty board:** the guild posts hunts for specific creatures from your Codex, including Notorious elites that start turning up once you accept. Bounty rank grows with marks.
- **Mobile:** auto-battle, text size, vibration, battle speed, contextual tips (not a tutorial), and installable offline files (`manifest.webmanifest`, `sw.js`, icons) when hosted on GitHub Pages or similar.
