# Roles

Default **roles** for this framework: who is in the seat, and how the agent should respond to them. A role is a **response contract**: it sets the vocabulary, the level of depth, what to surface versus fold away, and who holds which decisions. The agent reads it **before acting** (see the Eidos standard's `EIDOS.md`, "Roles").

These are the channel root's baseline, installed into `.eidos/roles/` (committed, so a creator and their team can tune how a role is treated for their channel). Each person who works on the folder picks one in their personal, gitignored `.eidos/me.md` and **calibrates** it with `eidos whoami`. Role sets the baseline; calibration tunes it per person.

- [Framework Owner](framework-owner.md): the creator; holds intent, scope, and decisions.
- [Editor](editor.md): cuts the video; owns the cut inside the beats, never the beats.
- [Producer](producer.md): holds the pipeline; surfaces what will miss its date.
- [Viewer](viewer.md): reacts to the hook and the packaging; sees only what a viewer would.
- [Sponsor](sponsor.md): reads the integration that carries them, and nothing else.

A role is a baseline, not a cage: anyone can write a custom role in their `me.md`, and a framework can add or reshape role files here. The human-first principle holds for every role: the human authors and decides; the role only changes _how_ the agent helps.
