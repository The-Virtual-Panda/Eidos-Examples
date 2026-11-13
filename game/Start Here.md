# {{Product}}

> **Start here.** This folder is the one place that says what the game **is**, mechanic by mechanic and level by level:
> why each piece is in the game, how it plays, its rules and numbers, and what it is not. It stays true whether or not a line of it has been built.

{{One line: what the game is, and who plays it.}}

## Where things are

- **[The Game](<The Game>)**: five pages: the pillars and the core loop, who plays, where it runs, how much game the team can finish, and where it sits in the market. Everything else gets checked against them.
- **[Mechanics](Mechanics)**: one page per mechanic, in a folder per system. A system can hold smaller ones (Combat, then Melee and Ranged inside it), and its own page sits beside its mechanics: what the system is for and how its mechanics feed each other.
- **[Levels](Levels)**: one page per level, in a folder per act. A level with several fights, puzzles, or set pieces becomes a folder of its own, its page beside an encounter page for each.
- **[Characters](Characters)**: one page per character the player meets or plays at the top, and the enemies in [Enemies](Characters/Enemies), with the [Bosses](Characters/Enemies/Bosses) inside it; both start on the enemy page.
- **[Items](Items)**: one page per item, upgrade, or collectible, in the same systems as the mechanics.
- **[Decisions](Decisions)**: one record per call that shaped the game: a rule chosen, a number tuned after a playtest, something cut or added. Each is proposed, then confirmed by the designer, and listed on every page it touches.
- **[Files](Files)**: concept art, blockouts, maps, balance sheets, and the pitch deck the pages link to. A set of files that ships together, a playable prototype build or the [Art Bible](<Files/Art Bible>)'s reference sheets, is a bundle: one folder, opened and linked as one.
- **[Backlog](Backlog)**: the work that builds the game, one task each, on a board from Triage to Done: tasks, and the bugs playtesters send in through the **Report a Bug** form. Milestones follow the Scope page (Prototype, Vertical Slice, Content Complete, Launch), and the board runs in sprints.
- **The Game Map** canvas: the core loop, the system map, and the level flow, drawn with the pages themselves on them.

## The one-page docs

- **[The One-Pager](<The One-Pager.md>)**: the whole game on one page, for a publisher, a festival, or a new teammate.
- **[Cut List](<Cut List.md>)**: everything cut from the game, and why.
- **[Playtest Log](<Playtest Log.md>)**: every playtest, dated: the build, who played, what you saw, what changed.
- **[Art Bible](<Art Bible.md>)**: how the game looks and sounds.

## How to use it

A page here says what one piece of the game **is**: why it is in the game, which pillar it serves, how it plays, its rules and numbers, and what it is not. It is not a task list and not a script: the build is where the game gets made, the Backlog is the work of making it, and these pages are what both are checked against, by the team and by a coding agent if you work with one. Every page starts as a one-pager; grow it into the full page when it earns it. Write the page before the prototype and keep it true after: a number you tuned is a decision, recorded in Decisions with the playtest that showed it, and a mechanic you cut stays here, marked `Cut` with its `cut_reason`, so nobody builds it again by accident.

The Health Check keeps the pages short and honest: a one-pager reads in three minutes, a full page in eight, and a mechanic, level, character, or item that names no pillar is flagged, since it is the first to question when the scope gets tight.

_Built on Eidos. The page types, the properties each page carries, the roles, and the plugins' settings live in [`.eidos/`](.eidos); `eidos check` keeps it honest._
