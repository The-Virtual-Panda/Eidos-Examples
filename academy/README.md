# {{Product}}

> **Start here.** This is the root for **{{Product}}**: the source of truth for what the school
> teaches, learner by learner and course by course, true whether or not a lesson has been recorded.

{{One line: what the school teaches, to whom, and what a graduate can do.}}

## Where things are

- **[Frames](Frames/)**: what the school teaches and why, how it teaches, where it sells, and what it may cost to make.
- **[Learners](Learners/)**: one file per kind of learner: where they start, what they need, what done looks like.
- **[Courses](Courses/)**: one file per course, grouped by track: outcomes, outline, assessment, format.
- **[Paths](Paths/)**: one file per ordered sequence of courses, for one learner toward one outcome.
- **[Assets](Assets/)**: slides, worksheets, recordings, and syllabi the blueprints link to.

## Top-level documents

_Your own one-of-a-kind docs: a Catalog page, a Style Guide for lessons, a Certification Policy. Add them here as you write them._

The full index, every folder, its variants, and the Properties table, is in
[`.eidos/Framework.yaml`](.eidos/Framework.yaml).

## How to use it

A course here describes what the course **is**: why it exists, what a learner can do afterward, the shape of its modules, and what it does not teach. It is not the material and not a task. Learners come first: a course points at the personas it serves with `for`, and a path strings courses together for one of them. Write the blueprint before the recording, and keep it true after: a course you retire stays here, marked `Retired`, so the reasoning survives.

_A root. Its framework lives in [`.eidos/`](.eidos/); see [`.eidos/Framework.yaml`](.eidos/Framework.yaml) for the full index._
