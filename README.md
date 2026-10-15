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

## Materials

There are now about 130 materials instead of 18. Every creature leaves its own parts (a common one and a rarer one), each region has five things to find while exploring or in chests, every dungeon has two finds of its own, and every region boss and dungeon boss leaves a guaranteed trophy. Each has a one-line quip and a source line in the Pack. At the Tinker's Wagon, the creature the parts came from now leaves a mark on the crafted item: wolf parts push attack, bone parts push lifesteal, and so on.

## The big expansion: towns, trade, danger and a long road

- **120 wild monsters** (up from 30): 12 per region, plus native creatures for the roads, the coast, the mines, the frontier, the back-alleys and the Far Shore. Each leaves its own part and has an icon and a vestige family. The Codex only shows what you have met.
- **Seven towns:** Hollowmere plus Briarhold, Saltmarch, Cragstead, Ironvale, Gildenreach and, much later, Landfall on the Far Shore. Towns are learned from people, not listed. Each has its own market, shops, inn, prices, people, pastimes and local monsters. Travel takes days, with road events, tolls, traders, ambushes and optional escorts.
- **Trade:** 24 goods with prices that drift, spike and crash with shortages, gluts, festivals, fevers, unrest and booms. You see only the prices you have seen or been told. Carts grow from a backpack to a caravan, and trade rank improves your margins.
- **Bank:** savings with interest, loans with a credit standing, risky ventures, and debts that your heirs inherit. Branches in every town share one account.
- **Town life:** 47 pastimes, rotating daily on each notice board, and 56 named people who remember you. Chat, give gifts, earn their trust, and they teach you where things are, what prices are, how monsters behave and where materials come from.
- **Rough quarters:** every town has a dangerous side you find by wandering. Ambushes, pickpockets and shakedowns. Inside: a fence, a black market (sealed vestiges and rare trophies), smugglers (contraband with real inspection risk), a loan shark whose collectors will find you, the Pit (bet on bouts or fight), and casinos.
- **Casinos:** roulette, blackjack (3:2, double, split), slots, three-dice, video poker and a higher-or-lower ladder, using in-game gold only. Every screen says plainly that this is entertainment: no real money, purchases or prizes, ever. Table limits and house edges are real.
- **Living companions:** moods that change how hard they fight, likes and dislikes, errands they ask you to run, and friendships and rivalries you can mend over a drink.
- **A world that moves:** migrations, floods that expose old dungeons, and overhunting that thins out species you farm. The Town Crier reports it.
- **The Far Shore:** a late-game outpost by sea, with its own monsters, boss, two dungeons, materials, gear and trade.
- **A family ledger** with collections across every generation (creatures, materials, vestige families, towns, pastimes, friends, dungeons). Each grants bonuses to every heir. The Journal gains a Field Guide.
- **Sound** (synthesized, off by default) and **downloadable save files**.

## A harder, slower start

The first rat is now a real fight: it has far more health than before and bites harder, so a fresh hero wins most of the time but loses about half their health doing it. Early enemies stay tougher until around level 5. The gates only open after **30 training sessions** (it was 10), so you spend days on the training yard first. While you are below level 8, sleeping only mends part of your wounds (38% of your health a night at level 1, rising to full by level 8), so you recover over several days while you keep training.

The first errand now lives at the top of the Training Yard until it is done: "Haul Mira's flour sacks" is a button that counts as a training session (Strength and Vitality gains plus XP, 2 stamina) and starts the quest on its own. Three loads, then a card to report back to Mira. A few early monsters were also softened, and elites now wait until level 5.

**Odd jobs around town:** a free "Walk around town" button (once a day) on the Town screen sometimes turns up an odd job: sweeping, hauling, delivering a note, minding a stall overnight, and so on. The first walk always finds one. Jobs pay small, easy starter loot (a basic piece of gear, coins, a potion, a material, or a bit of training) and stop turning up once you are level 12 or higher.

## Skill ranks and breakthroughs

Skills now climb in ranks: **Drizzle** (Lv 1-2), **Gale** (3-4), **Squall** (5-6), **Tempest** (7-8) and **Cataclysm** (9-10). Use grows a skill, and fighting opponents that really test you (Risky or Deadly) teaches much faster than easy fights. At the top of a rank (Lv 2, 4, 6, 8) a skill stops growing and waits for a **breakthrough**, which you buy with a vestige plus wicks, a larger amount of wicks alone, or a master's lessons for gold. Tomes still teach new skills and sharpen them within a rank. Rank perks: Gale costs 1 less Focus, Squall +15% damage, Tempest a 20% chance to refund half the Focus, Cataclysm +15% more damage and a 30% refund chance.

## A calmer look

Emoji decoration is off by default. The game now shows plain text labels (Gold, Stamina, HP, Focus, wicks) and keeps pictures only where they carry information: the monster portraits, playing cards, dice, slot reels and the roulette wheel. You can switch to the old look with **Icons: Playful** in the Menu or on the title screen's Settings. The Training Yard now has a Back to town button, and dropping an odd job moved to the Journal with a confirmation.

## Quality pass
- **Calmer Town**: a one-line "Next" hint; Places, Services and Recent events fold away.
- **Confirmations**: rare gear sales, bulk sells, Deadly fights and wasted potions ask first; locked items can't be sold.
- **Combat clarity**: the enemy's intent is shown before it acts, the log shows the last 7 lines (toggle for full), and hits flash.
- **Pack tools**: sort chips, slot filter, "better than equipped" marker, lock favourites.
- **Save safety**: rolling backup, "Restore last backup" on the title screen, warning if a write fails.
- **Accessibility** (Menu → Settings): high contrast, colour-blind safe danger colours, large tap targets.
- **Playtest report**: Menu → "View playtest report" shows balance telemetry you can copy and share.
- **Voice**: system text uses a calm, consistent tone; humour stays in NPC dialogue.

## Playtest round 1
- Sleep animation about 40% faster (tap to skip).
- Focus is not mentioned until a guild instructor teaches it; the Old Library stays out of sight until then.
- Early armour is wooden slats tied with string. Mail needs Lv 14+, Plate Lv 30+ and costs far more in shops.
- **Sell goods** (Market or Pack): per-item Sell and Haggle, a limited number of bargaining tries per day that grow with practice, and "sell what is worse than worn".
- Services have fuller descriptions on the Town screen.
- Every town has a hidden gambling den in its rough quarter; find it by wandering.
- Companions have drawn portraits. Conversations are now spoken questions with spoken answers. NPC chatter and street scenes rewritten.

## Skills log
Hero tab → Skills log. Abilities improve by use (success teaches more than failure) and appear the first time you try them: **Haggling** (sell goods: odds, tries per day, better offers), **Carousing** (buying a round: cheaper, more reliable, sometimes a second rumour; Listen in counts too), **Bluffing** (tolls and rough quarters). Trading is shown read-only. New skills register in `LSK` and call `lsUse(id, success)`.

## Hereditary growth and market keepers
- Heirs keep 15% of each life skill's experience from their predecessor (shown in the Skills log). It compounds a little each generation.
- Every town's Market has a keeper to chat with (once a day) and ask for odd jobs. Friendship tiers give 3/6/10% cheaper buying and better selling prices; regulars get a good piece set aside at each restock. Friendships belong to the family and carry across heirs.
- Old stale shop stock (e.g. Plate on a Lv 3 hero) is refreshed when the Market opens.

## Scarcity and rank
- **Gear rarity**: Uncommon needs item level 3+, Rare 16+, Epic 36+; below that, rarer rolls are demoted. Every drop also has a level-scaled chance to drop one more step (about 55% at Lv 5, 15% from Lv 56). Shops sell mostly Common, at most one Uncommon early (two later), and Rare only from friendly keepers at Lv 16+. Tier names (Iron, Steel...) start at item levels 9, 20, 34, 48, 64.
- **Levels**: XP needed per level is 2.3x what it was. 
- **Rank**: Rank (Unranked, Copper, Bronze, Silver, Gold, Mythril, Adamant) is shown beside the name at the top, in the Hero tab and in the guild. Rank caps level: 10 / 20 / 30 / 40 / 52 / 66 / 99. Contracts raise your rank; rank also unlocks regions, stamina, party size and more.

## Monster portraits and reward pop-ups
- 78 monster portraits (every zone monster and boss) were generated with Hugging Face's Z-Image Turbo, 16 per sprite sheet, then cropped to 96px WebP (`mon/`) and embedded in `index.html` as `MONPIC`. Elites get a gold frame, bosses a red one. Monsters without a portrait (habitat monsters) still use the drawn icons. To add more: generate a 4x4 sheet, slice it, and add entries to `MONPIC`.
- Notice Board and odd-job rewards now pop up in the middle of the screen and fade after about 2.5 seconds (tap to dismiss). The inline result card remains.
