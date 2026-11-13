# {{Product}}

> **Start here.** This folder is the one place that says what the school **teaches**, learner by learner
> and course by course: who each course is for, what they will be able to do, and how it is built. It stays true whether or not a lesson has been recorded.

{{One line: what the school teaches, to whom, and what a graduate can do.}}

## Where things are

- **[The School](<the-school>)**: four pages: what it teaches and why, how it teaches, where it sells, and what it costs to make. Everything else gets checked against them.
- **[Learners](learners)**: one page per kind of learner: where they start, what they need, what done looks like.
- **[Courses](courses)**: a folder per track, and in it a folder per course: the course's page (who it is for, its learning outcomes, the modules, how they prove it, the format) with a page per lesson beside it. **[Welcome to the School](courses/orientation/welcome-to-the-school/welcome-to-the-school.md)** is the worked example: a course, two lessons, and the quizzes that check them.
- **[Paths](paths)**: one page per sequence of courses, for one kind of learner, toward one outcome.
- **[Files](files)**: slides, worksheets, recordings, and syllabi the pages link to, a course's kit as one bundle.
- **[Academy](academy)**: the quizzes and flashcard decks, kept by the Academy plugin, one Academy course per course here, each quiz drawing on a lesson's page.
- **[Decisions](decisions)**: the calls that shaped a course, a path, or the school, each signed off by whoever made it and listed on the pages it shaped.
- **[Backlog](backlog)**: the production board: making a lesson, revising a course, and fixing what a learner reported.

## The one-page docs

- **[Catalog](catalog.md)**: every course on one page, as a learner sees it.
- **[Lesson Style Guide](<lesson-style-guide.md>)**: how a lesson is written and recorded.

## How to use it

A course's page says what the course **is**: who it is for, what they will be able to do afterward, the shape of its modules, and what it does not teach. It is not the material and not a task. Learners come first: a course points at the learners it serves with `for`, and a path strings courses together for one of them. A course's learning outcomes are labelled LO1, LO2, and on; each lesson links the ones it serves, and each lesson's quiz draws on what the lesson says, so a question always traces back to a promise. Write the page before the recording, and keep it true after: a course you retire stays here, marked `Retired`, so the reasoning survives.

## Tools it comes with

- **Academy**, a plugin from the Eidos Registry: quizzes and decks on the lessons, practice and official attempts, and grading for written answers. Run `eidos plugin install` once on a new machine, then `eidos plugin allow academy`.
- **Records**: Learning Outcomes on every course page, and Decisions.
- **Backlog**: the production board.
- **Metrics**: a reading budget per kind of page (a lesson page in six minutes, a course page in eight) and three to eight outcomes a course.
- **Canvas**: the [Curriculum Map](.eidos/plugins/canvas/curriculum-map.yaml), a frame per track.

_Built on Eidos. The page types, the properties each page carries, and the roles live in [`.eidos/`](.eidos); `eidos check` keeps it honest._
