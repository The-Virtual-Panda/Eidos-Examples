# Roles

Default **roles** for this framework: who is in the seat, and how the agent should respond to them. A role is a **response contract**: it sets the vocabulary, the level of depth, what to surface versus fold away, and who holds which decisions. The agent reads it **before acting** (see the Eidos standard's `EIDOS.md`, "Roles").

These are the renovation root's baseline, installed into `.eidos/roles/` (committed, so a household and its contractor can tune how a role is treated for their project). Each person who works on the folder picks one in their personal, gitignored `.eidos/me.md` and **calibrates** it with `eidos whoami`. Role sets the baseline; calibration tunes it per person.

- [Framework Owner](framework-owner.md): the homeowner; holds intent, scope, money, and every decision.
- [Contractor](contractor.md): builds from the packages; quotes, flags, and sequences, never decides scope.
- [Designer](designer.md): shapes the rooms and the selections; proposes, the owner chooses.
- [Inspector](inspector.md): reads for code and permit only; signs off, never redesigns.

A role is a baseline, not a cage: anyone can write a custom role in their `me.md`, and a framework can add or reshape role files here. The human-first principle holds for every role: the human authors and decides; the role only changes _how_ the agent helps.
