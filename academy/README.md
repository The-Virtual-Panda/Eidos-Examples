# {{Product}}

> **Start here.** This folder is the one place that says what the school **teaches**, learner by learner
> and course by course: who each course is for, what they will be able to do, and how it is built. It stays true whether or not a lesson has been recorded.

{{One line: what the school teaches, to whom, and what a graduate can do.}}

## Where things are

- **[The School](<The School/>)**: four pages: what it teaches and why, how it teaches, where it sells, and what it costs to make. Everything else gets checked against them.
- **[Learners](Learners/)**: one page per kind of learner: where they start, what they need, what done looks like.
- **[Courses](Courses/)**: one page per course, grouped by track: what they will be able to do, the modules, how they prove it, the format.
- **[Paths](Paths/)**: one page per sequence of courses, for one kind of learner, toward one outcome.
- **[Files](Files/)**: slides, worksheets, recordings, and syllabi the pages link to.

## The one-page docs

- **[Catalog](Catalog.md)**: every course on one page, as a learner sees it.
- **[Lesson Style Guide](<Lesson Style Guide.md>)**: how a lesson is written and recorded.

## How to use it

A course's page says what the course **is**: who it is for, what they will be able to do afterward, the shape of its modules, and what it does not teach. It is not the material and not a task. Learners come first: a course points at the learners it serves with `for`, and a path strings courses together for one of them. Write the page before the recording, and keep it true after: a course you retire stays here, marked `Retired`, so the reasoning survives.

_Built on Eidos. The page types, the properties each page carries, and the roles live in [`.eidos/`](.eidos/); `eidos check` keeps it honest._
