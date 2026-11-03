# TraceFirst

**A prediction-first learning platform for introductory C++** — built by [Ebuka Philip Oguchi](https://ebukaoguchi.github.io/).

## The idea

Beginners do not fail C++ on the hard topics. They fail early, when a program's behaviour is invisible to them and a compiler error reads as a verdict instead of a message. TraceFirst is built on one discipline, drawn from the PRIMM model in computing-education research (Predict, Run, Investigate, Modify, Make):

1. **Predict.** The student sees a short program and must commit to what it will print. The prediction is locked before anything runs.
2. **Run and trace.** The student steps through the program line by line, watching labelled memory boxes hold and change values, and the output console fill.
3. **Confront the gap.** A wrong prediction is diagnosed at the exact step where the student's mental model and the machine parted, with the misconception behind the chosen answer named.
4. **Modify.** One value changes, and the student predicts again.

Every exercise exists in four story skins (Health & Biology, Psychology & Social Science, Business & Economics, Arts & Media) over identical code, so a non-CS major meets the concept inside her own field while the class shares one concept sequence.

## Current state: prototype

`index.html` is a self-contained prototype with seven modes, and each mode tab carries a dropdown of its sections for direct jumps. A "Start Here" route at the top of the page sequences the modes for a first-time visitor, with a short "Meet the Code" primer that explains the anatomy of a first program before the tracer. Open it in any browser; there is nothing to install and nothing is sent anywhere: there are no accounts, and a visitor's progress is saved only in their own browser, on their own device. A background switch at the top of the page offers white (the default), black, or green, and remembers each visitor's choice.

- **Bolt's World:** a pre-syntax robot environment, and the recommended starting point. Students program an original workshop robot in real C++ shape (commands, loops, conditionals, their own functions) across twelve graded worlds, learning the logic of programming before formal syntax. Six optional challenge worlds with action budgets (par) sit below the graded worlds for students who finish and want more.
- **Prediction Tracer:** thirty-seven exercises spanning the introductory course (assignment, integer division, decisions including switch fall-through, loops, functions and reference parameters, arrays and two-dimensional arrays, strings, vectors, searching and sorting, structured data, classes and objects, simulated file input, maps and sets, a four-exercise pointers sequence covering addresses, dereference, pointer arithmetic, and dynamic memory, and a recursion sequence with a visible call stack), each running the full predict, trace, verdict, and modify loop, solo or in pairs, with a per-concept prediction record for the session. Traces can also play themselves: an animated playback mode steps through each program at a chosen speed while a moving marker makes the control flow visible, arcing over the lines a branch skips and curving back up at a loop's back-edge, with a narration caption naming the decision behind each jump and pacing that lingers on jumps. The same playback, captions included, runs in the facilitator-facing Lecture mode, which projects an exercise to a whole class, tallies the class's predictions, and pauses the trace where the majority's model parted from the machine. Students can export a prediction journal of their session, and an instructor digest aggregates exported journals into a per-exercise view of where predictions went wrong, and turns the most-missed exercises into discussion cards for the next class. A student can also attach a one-sentence rationale to a locked prediction; the rationale returns with the verdict, travels with the journal, and is grouped in the digest under the misconception it reveals. An instructor exercise studio in the same instructor section lets an instructor author new prediction exercises (the true output is fixed by running the program, never typed in), share them by code, and have students play them with the same prediction lock. A Topic crosswalk index tags all thirty-seven exercises by topic, matched by topic title rather than section number, since numbering varies by textbook and course setup. Each concept group opens with a short briefing and concept checks, a spaced review set resurfaces exercises that are due, and a problem of the day is seeded by the calendar date. A Reference button in the header opens the printable reference card as a panel from any mode, without disturbing the work underneath it. The tracer is fully keyboard-operable, with screen-reader announcements for each step.
- **Debugging Gym:** seven rounds built from real beginner programs, run as the full debugging process: spot each bug and classify it, say what each logic bug actually does, fix the code yourself with no run button, then prove the fix on a test you have not seen.
- **Error Translator:** a searchable catalogue of thirty-two beginner compiler errors, each with the raw compiler message, a plain-English translation, the cause, and a before-and-after fix.
- **Challenges:** nine tasks at each of the Beginner, Intermediate, and Expert levels, guided projects, and scored exams, drawn from real course assignments. Timed diagnostic sets return, for every missed question, the concept it tested and a link to the exercise that repairs it, and three open-ended culminating projects run on staged milestones (proposal, prediction checkpoint, test bench, reflection), with a showcase kept on the student's own device.
- **Bridge:** the middle rung between tracing and writing. Students put shuffled programs back in order (six Parsons problems, each with a distractor block to reject), then complete six programs with missing lines; every attempt is judged by running the assembled program, not by matching a set answer.
- **Make:** the authorship stage that completes the PRIMM sequence. Students write complete C++ programs in an in-page editor, run them with their own test input, and check them against twenty guided prompts, each with a verified test bench, the later prompts adding hidden tests the student never sees. A micro-problem ladders section adds twenty-four one-function problems in four tiered ladders, judged instantly against visible test tables. Prompts can be worked test by test in a test-driven mode, completed prompts reveal alternative solutions for comparison, a style checklist comments without blocking, and a "Trace this code" action steps the student's own program through the tracer view, with a copyable anchor that reopens the trace at a chosen step.

## Roadmap

TraceFirst is under active development toward a full platform:

- A real architecture behind the prototype: structured content, exercise engine, and student accounts with saved progress and instructor views of prediction accuracy by concept.
- A graphical interface and a downloadable app, alongside the web version.
- Growth along the pathway its author teaches: the introductory C++ sequence first, then the introduction to systems and computer organization, so a student can follow one continuous route from her first program to the operating system.

Design references, for ambition rather than imitation: Alice (Carnegie Mellon) for meeting novices inside a designed environment, GeeksforGeeks for the union of explanation and practice, and Stanford's Code in Place for teaching programming at community scale.

## License

MIT — see [LICENSE](LICENSE). Copyright (c) 2026 Ebuka Philip Oguchi.
