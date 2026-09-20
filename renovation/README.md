# {{Product}}

> **Start here.** This is the root for **{{Product}}**: the source of truth for what the
> finished house is, room by room and package by package, true whether or not a wall has come down.

{{One line: which house, what work, and what life it is for afterward.}}

## Where things are

- **[Frames](Frames/)**: what the owner wants, the house as it stands, what it may cost, and what the code requires.
- **[Rooms](Rooms/)**: one file per room the project touches, grouped by floor: what the finished room must do.
- **[Packages](Packages/)**: one file per package of work, grouped by phase: what is done, in what order, and what each waits on.
- **[Selections](Selections/)**: one file per fixture, finish, or material, grouped by room: what it must be, and what was chosen.
- **[Assets](Assets/)**: drawings, permits, quotes, spec sheets, and site photos the blueprints link to.

## Top-level documents

_Your own one-of-a-kind docs: a Floor Plan, a Schedule, a Change Order Log. Add them here as you write them._

The full index, every folder, its variants, and the Properties table, is in
[`.eidos/Framework.yaml`](.eidos/Framework.yaml).

## How to use it

A room here describes what the finished room **is**: why it is in the project, what it must do, and what it does not get. A package describes what is **done** to get there, as a scope a contractor can quote and an owner can walk. A selection describes what must be **true** of a thing before it is bought. None of them is a task list. Write the blueprint before the quote, and keep it true after: a room you cut stays here, marked `Cut`, so the reasoning survives the next conversation about it.

_A root. Its framework lives in [`.eidos/`](.eidos/); see [`.eidos/Framework.yaml`](.eidos/Framework.yaml) for the full index._
