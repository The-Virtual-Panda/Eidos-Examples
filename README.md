# Eidos-Examples

Worked Eidos roots, one per kind of thing: a channel, a venture, an academy, a wedding, a world, a house renovation, an ACE vault. Each installs from the Registry as `@The-Virtual-Panda/<name>`.

Every root here is a complete framework for its kind: the frames it is judged against, a collection per kind of unit with a template per variant, the properties that make a blueprint findable, and the roles that say how an agent responds to each person in the seat. The collections ship empty, on purpose. Eidos frameworks hold what their owner decided, not prose invented for them; install one and fill it.

| Root | For | Frames | Collections | Roles |
| --- | --- | --- | --- | --- |
| [`channel/`](channel) | a video channel, podcast, or stream, and its site | audience, format, voice, market | `Videos` by series, `Posts` by series, `Pages` | the creator, editor, producer, viewer, sponsor |
| [`venture/`](venture) | a business as it develops: ideas, plans, bets, and the calls made | thesis, market, model, criteria | `Ideas`, `Plans` by line, `Investments` by line, `Decisions` | the founder, CFO, operator, investor, advisor |
| [`academy/`](academy) | a school of courses, learner first | mission, pedagogy, market, criteria | `Learners`, `Courses` by track, `Paths` | the creator, editor, producer, learner, expert |
| [`wedding/`](wedding) | a wedding, planned as its run of show | purpose, guests, venue, criteria | `Moments` by day, `Vendors` by category | the couple, planner, vendor, family, guest |
| [`world/`](world) | a fictional world, for a table or a series | premise, tone, laws, table | `Places` by region, `Factions`, `Characters`, `Arcs` by campaign | the game master, co-writer, player (sees only what is `revealed`) |
| [`renovation/`](renovation) | a house renovation, room by room and package by package | brief, site, criteria, code | `Rooms` by floor, `Packages` by phase, `Selections` by room | the homeowner, contractor, designer, inspector |
| [`ace/`](ace) | an Obsidian vault in the ACE shape (Atlas, Calendar, Efforts) | purpose, practice | `Atlas` (flat, with maps), `Calendar` by series, `Efforts` (heat as `status`) | you, and the agent acting alone |

Every root uses the Title Case naming convention, since each is meant to be opened in Obsidian as much as in an editor.

## Installing one

```bash
npx eidosmd install @The-Virtual-Panda/wedding --product "Our Wedding" --group "Wedding Day"
```

Or pull one piece into a root you already have: a collection, a variant, or a role.

```bash
npx eidosmd install @The-Virtual-Panda/world --role player
```

## Checking them

Each root is checked in place with the same CLI the Registry runs.

```bash
npx eidosmd@0.4.0 check --root wedding
```

## Publishing

Each root is tagged on its own, `<name>/v<version>`, and published by a manifest in the [Eidos Registry](https://github.com/The-Virtual-Panda/Eidos-Registry) that points at this repository, the root's folder, and that tag.
