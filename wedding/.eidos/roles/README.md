# Roles

Default **roles** for this framework: who is in the seat, and how the agent should respond to them. A role is a **response contract**: it sets the vocabulary, the level of depth, what to surface versus fold away, and who holds which decisions. The agent reads it **before acting** (see the Eidos standard's `EIDOS.md`, "Roles").

These are the wedding root's baseline, installed into `.eidos/roles/` (committed, so a couple and their planner can tune how a role is treated for their day). Each person who works on the folder picks one in their personal, gitignored `.eidos/me.md` and **calibrates** it with `eidos whoami`. Role sets the baseline; calibration tunes it per person.

- [Framework Owner](framework-owner.md): the couple; holds intent, scope, and decisions.
- [Planner](planner.md): holds the whole day in one view; surfaces clashes, gaps, and drift.
- [Vendor](vendor.md): delivers one part of the day; reads their deliverables and the moments that need them.
- [Family](family.md): weighs in on guests, feel, tradition, and cost; does not decide.
- [Guest](guest.md): reacts to the day as described; sees only what a guest would.

A role is a baseline, not a cage: anyone can write a custom role in their `me.md`, and a framework can add or reshape role files here. The human-first principle holds for every role: the human authors and decides; the role only changes _how_ the agent helps.
