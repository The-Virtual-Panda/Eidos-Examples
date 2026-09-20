# Eidos-Examples

Worked Eidos roots, one per kind of thing: a channel, a venture, an academy, a wedding, a world, a house renovation, an ACE vault. Each installs from the Registry as `@The-Virtual-Panda/<name>`.

Every root is a complete framework for its kind, written in the words of the person who would use it: a few big-picture pages everything else is checked against, a folder per kind of page with a template for each, the handful of properties that make a page findable, the one-page docs that person already keeps, and the roles that tell an agent how to talk to each person in the seat. The page folders ship empty, on purpose: an Eidos root holds what its owner decided, not prose invented for them. Install one and fill it.

| Root | For | The big picture | Page folders | One-page docs | Roles |
| --- | --- | --- | --- | --- | --- |
| [`channel/`](channel) | a video channel, podcast, or stream, and its site | `The Channel/`: Audience, Formats, Voice, Niche and Money | `Videos` by series, `Posts` by series, `Pages` | Content Calendar, Brand Kit, Rate Card | the creator, editor, producer, viewer, sponsor |
| [`venture/`](venture) | a business as it develops: ideas, plans, bets, and the calls made | `The Business/`: Thesis, Market, How It Makes Money, Runway and Limits | `Ideas`, `Plans` by line, `Investments` by line, `Decisions` | The Pitch, Roadmap, Team | the founder, CFO, operator, investor, advisor |
| [`academy/`](academy) | a school of courses, learner first | `The School/`: Mission, How We Teach, Market, Production | `Learners`, `Courses` by track, `Paths` | Catalog, Lesson Style Guide | the instructor, editor, producer, learner, expert |
| [`wedding/`](wedding) | a wedding, planned as its run of show | `The Big Picture/`: Vision, Guests, Venue, Budget | `Run of Show` by day, `Vendors` by category | The Timeline, Day-Of Contacts | the couple, planner, vendor, family, guest |
| [`world/`](world) | a fictional world, for a table or a series | `The World/`: Premise, Tone, How It Works, The Table | `Places` by region, `Factions`, `Characters`, `Arcs` by campaign | History, Player's Guide, Names | the game master, co-writer, player (sees only what is `revealed`) |
| [`renovation/`](renovation) | a house renovation, room by room and job by job | `The Brief/`: What We Want, The House, Budget, Permits | `Rooms` by floor, `The Work` by phase, `Selections` by room | Schedule, Contacts, Change Log | the homeowner, contractor, designer, inspector |
| [`ace/`](ace) | an Obsidian vault in the ACE shape (Atlas, Calendar, Efforts) | `About This Vault/`: What This Is For, How It Runs | `Atlas` (flat, with maps), `Calendar` by series, `Efforts` (heat as `status`) | Home | you, and the agent acting alone |

Every root targets Eidos 5.4.0 and uses the Title Case naming convention, since each is meant to be opened in Obsidian as much as in an editor. Each keeps a `Files/` folder for the things that are not pages: contracts, maps, drawings, decks.

## Installing one

```bash
npx eidosmd install @The-Virtual-Panda/wedding --product "The Ungers 2026" --group "Wedding Day"
```

Or pull one piece into a root you already have: a page folder, a page type, a role, or a one-page doc.

```bash
npx eidosmd install @The-Virtual-Panda/world --role player
```

## Checking them

Each root is checked in place with the same CLI the Registry runs.

```bash
npx eidosmd@0.5.0 check --root wedding
```

## Publishing

Each root is tagged on its own, `<name>/v<version>`, and published by a manifest in the [Eidos Registry](https://github.com/The-Virtual-Panda/Eidos-Registry) that points at this repository, the root's folder, and that tag.
