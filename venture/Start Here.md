# {{Product}}

> **Start here.** This folder is the one place that says what the business **is** and where it is going:
> every idea, every line and product, every plan, every bet, every call, with the reasons attached. It stays true whether or not a dollar has moved.

{{One line: what the business does, for whom, and why now.}}

## Where things are

- **[The Business](<The Business>)**: four pages: what it is and why now, who pays, how it makes money, and how long you have. Everything else gets checked against them.
- **[Ideas](Ideas)**: one page per opportunity you are weighing. A spark grows into a case; a case becomes a line, a product, or a plan, or a call to stop.
- **[Lines](Lines)**: the business by line. Each line of business is a folder with its own page inside it, each product a folder inside its line, and each plan sits in the folder of what it grows: `Lines/Wholesale/Wholesale.md`, `Lines/Wholesale/Cold Brew/Cold Brew.md`, `Lines/Wholesale/Cold Brew/Grocery Launch.md`. Make the folder when the line or product needs one.
- **[Investments](Investments)**: one page per bet with money on it, raised or spent. A round for the whole company sits at the top; money for one line or product sits in that line's folder.
- **[Calls](Calls)**: one record per call you made. Each one names the pages it serves and is listed on them, and the founder signs it off once it is made.
- **[Files](Files)**: decks, models, term sheets, contracts, and research the pages link to. The Pitch Deck, the Financial Model, and the Data Room are bundles: each one set of files, linked and shared as one.
- **[Backlog](backlog)**: the work that carries out a plan's moves, one task per file, each serving the plan or deal it moves.

## The one-page docs

- **[The Pitch](<The Pitch.md>)**: the thirty-second version of the business.
- **[Roadmap](Roadmap.md)**: the next twelve months on one page.
- **[Team](Team.md)**: who does what, and which seats are empty.

## How to use it

Building a business is mostly making calls, so this folder keeps the three things a company usually loses: the ideas it considered and why they died, the plans as they were meant before they got changed, and the calls it made with the reasons attached. Every idea, plan, and deal carries `decide_by`, the day you have to make a call on it, and the saved views (Raising, Deploying, Live ideas, and Active, next call first) list them by that date. None of it is a to-do list: the to-dos are tasks on the Backlog, and a plan's milestones can be the Backlog's milestones. Write the page before the money moves, and keep it true after: an idea you kill stays here, marked `Killed`, so nobody pitches it again without the reasons.

A call starts as Proposed and waits for the founder; once made, it is Made and signed off, and a call later undone is Overturned by the call that undid it. Its notes say what was going on, what you could have done (doing nothing included), what you did and who made it, what it closed and what it cost, and what would reopen it. A call without that last line is either permanent or arbitrary.

_Built on Eidos. The page types, the properties each page carries, and the roles live in [`.eidos/`](.eidos); `eidos check` keeps it honest, and Metrics warns when a page runs past its reading time or a plan has no `decide_by`._
