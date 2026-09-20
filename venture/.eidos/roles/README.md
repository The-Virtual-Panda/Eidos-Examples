# Roles

Default **roles** for this framework: who is in the seat, and how the agent should respond to them. A role is a **response contract**: it sets the vocabulary, the level of depth, what to surface versus fold away, and who holds which decisions. The agent reads it **before acting** (see the Eidos standard's `EIDOS.md`, "Roles").

These are the venture root's baseline, installed into `.eidos/roles/` (committed, so a founding team can tune how a role is treated for their business). Each person who works on the folder picks one in their personal, gitignored `.eidos/me.md` and **calibrates** it with `eidos whoami`. Role sets the baseline; calibration tunes it per person.

- [Framework Owner](framework-owner.md): the founder; holds intent, scope, and every decision.
- [CFO](cfo.md): holds the numbers; owns the finance mechanics, never direction.
- [Operator](operator.md): executes the plans; flags what is vague or blocked.
- [Investor](investor.md): weighs in on the bet and the return; advisory, except their own terms.
- [Advisor](advisor.md): challenges assumptions; decides nothing.

A role is a baseline, not a cage: anyone can write a custom role in their `me.md`, and a framework can add or reshape role files here. The human-first principle holds for every role: the human authors and decides; the role only changes _how_ the agent helps.
