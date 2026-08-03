# How to Use the Cardhaven Ruleset: A Guide for Authors

This document is for LitRPG authors, not tabletop GMs. If you're
looking for dice-based stat blocks to run at a table, see
`bestiary/conversions/`. This guide is about using Cardhaven's system
as scaffolding for your own progression-fantasy fiction.

## Start Here: This Is a Toolkit, Not a Rulebook

Everything in this ruleset exists to serve your story, not the other
way around. Treat every number, formula, and threshold here as a
starting point you're free to adjust, ignore, or reinterpret the moment
it stops serving your scene. A tabletop system has to be precise
because a GM has to adjudicate outcomes fairly, in real time, for
players who didn't write the plot. You don't have that constraint. You
know how the fight ends before you write the first punch. Use that.

The value of a shared mechanical system isn't precision — it's
*consistency* and *speed*. Once you've internalized how Cardhaven's
stats, cards, and progression hang together, you stop reinventing game
design every time a character levels up or a new creature shows up on
the page. You just write.

## Using Core Stats to Establish a Character Fast

The four core stats — STR, CON, INT, DEX — aren't meant to be tracked
like a spreadsheet. They're a shorthand for telegraphing who a
character is in combat, in one or two attribute callouts.

A character built around STR and CON reads as a frontline bruiser
without you needing to say so directly — high Focus Cap, high HP,
someone who plants their feet and takes hits. A DEX-heavy build reads
as fast and evasive. INT-heavy reads as a caster who's fragile up
close. You don't need exact numbers in every scene to make this land —
readers pick up on relative stat emphasis fast, especially once you've
shown one full stat block early on to establish the pattern.

One derived formula is fully confirmed and safe to build on directly:
**Agility = DEX × 2**. If you want a quick, reliable way to make a
character feel faster or slower relative to their peers, adjusting DEX
and letting Agility scale off it is a clean, established lever.

The other three derived pools (Focus Cap from STR, Stamina/HP from
CON, Mana from INT) are **deliberately left open**. This isn't a gap
you need to fill before you can use the system — it's flexibility
built in on purpose. Different stories need different power curves. A
grounded, gritty progression story might want HP to scale slowly and
painfully; a power-fantasy might want it to scale fast and
satisfyingly. Pick numbers that match the *feel* you're going for
scene to scene, and don't worry about locking in a universal formula
unless your own story specifically needs one.

## Progression as a Pacing Tool

Leveling, XP, and Card Slot growth aren't really about the math — they're
about giving your reader a felt sense of *how far this character has
come*. Use Cardhaven's rough tiering as a pacing scaffold for your
arc, not a strict gate:

- **Level 0 / Trash Mob-tier content** reads as genuinely low stakes —
  useful for opening chapters, training arcs, or establishing a
  baseline before things get real.
- **Elite-tier content** (a named, tougher variant of something the
  character already fought) is a natural way to signal "this fight
  matters more than the last one" without changing the whole scene
  structure.
- **Boss-tier content** is your arc's climax beat — the place to spend
  your best prose, not just your character's biggest numbers.

You don't need every fight to escalate linearly. A story that dips
back into Trash Mob-tier content after a Boss fight can read as a
deliberate breather beat, not a mistake — as long as it's a *choice*,
not an accident.

## Cards and the Triple Bind as Character-Decision Engines

The Card Slot system and the Triple Bind economy (Economy / Crafting /
Progression) aren't just inventory management — they're a built-in
source of dramatic tension you can lean on whenever a character needs
a hard choice.

Every Shard a character picks up is implicitly a decision point: spend
it now for an immediate edge, save it toward a bigger craft later, or
cash it in for XP. You don't need to narrate the accounting every
time, but knowing this tension exists in the background gives you a
ready-made source of stakes whenever a scene needs one — "do I burn my
last few shards to survive this fight, or hold them for the class
upgrade I've been building toward" is a real decision your system
already supports, without you needing to invent new stakes from
scratch.

The Soulbound death mechanic (a class card shatters permanently on
death, no refund) is a genuinely useful narrative lever too — it means
character death, or even a near-death scare, can carry real mechanical
weight on the page, not just emotional weight. Use it sparingly, the
way you'd use any high-stakes consequence.

## Using the Bestiary to Calibrate Challenge

This is the part most directly useful for figuring out "how tough
should this fight feel for my characters right now."

Every creature in `bestiary/cardhaven/` carries a **Role** tag (Trash
Mob, Swarm, Ambusher, Artillery, Elite, Boss) and a **Rank/Level**
field where one is confirmed. Use these as a quick gut-check when
you're writing a fight scene, not as a formula to solve:

- **Trash Mob / Swarm** creatures should feel manageable individually,
  dangerous mainly in numbers. Good for showing a character's growth
  by having them casually handle something that used to be a real
  threat.
- **Ambusher / Artillery** creatures are about *tactics*, not raw
  power — the tension comes from positioning and surprise, not from
  a big HP pool. A fight against one of these should read as a puzzle
  your character has to solve, not a slog to grind through.
- **Elite** creatures are where a fight starts costing something —
  resources spent, a close call, maybe a scar. This is your tier for
  "this one actually worries me" moments.
- **Boss** creatures are set-piece encounters. These should get your
  most deliberate pacing and your character's best moment of growth,
  cleverness, or sacrifice.

The Habitat field on each entry is there to help you place a creature
in *your own* setting logically — swap it freely for wherever your
story actually takes place. None of these entries are tied to a
specific world; they're meant to be dropped into whatever coastal
cave, ruined hive, or overgrown dungeon your own plot calls for.

If you want harder mechanical grounding for a fight scene — actual
attack values, damage ranges, HP totals to reference while writing —
the `bestiary/conversions/` folder has full stat blocks in five
different tabletop-game formats. You don't need to know any of those
systems to use them for reference; picking whichever one's numbers
feel right for the scene and borrowing them is a completely valid way
to use that folder, even if you never intend to run an actual tabletop
session.

## When to Ignore All of This

If a rule, a formula, or a creature's stated toughness gets in the way
of the scene you actually want to write, the scene wins. Nothing in
this ruleset is worth breaking your story's internal logic or your
reader's investment to preserve. Use it exactly as much as it helps,
and no more.
