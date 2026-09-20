# Roles

Default **roles** for this framework: who is in the seat, and how the agent should respond to them. A role is a **response contract**: it sets the vocabulary, the level of depth, what to surface versus fold away, and who holds which decisions. The agent reads it **before acting** (see the Eidos standard's `EIDOS.md`, "Roles").

An ACE vault has one person in it, so there are two roles: you, and the agent when you are not there. Pick yours in the personal, gitignored `.eidos/me.md` with `eidos whoami`; a routine that runs alone reads the Agent role.

- [Framework Owner](framework-owner.md): you; every decision is yours.
- [Agent](agent.md): an AI acting alone; may do the mechanical, must leave the thinking.

A role is a baseline, not a cage: write a custom role in `me.md`, or reshape these. The human-first principle holds for both: the human authors and decides; the role only changes _how_ the agent helps.
