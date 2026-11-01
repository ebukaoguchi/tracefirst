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

`index.html` is a self-contained prototype with six modes. Open it in any browser; there is nothing to install and nothing is sent anywhere.

- **Bolt's World:** a pre-syntax robot environment, and the recommended starting point. Students program an original workshop robot in real C++ shape (commands, loops, conditionals, their own functions) across eight graded worlds, learning the logic of programming before formal syntax. Four optional challenge worlds with action budgets (par) sit below the graded worlds for students who finish and want more.
- **Prediction Tracer:** thirteen exercises (assignment, integer division, if/else, for loops, functions, while loops, nested loops, arrays, strings, and a four-exercise pointers sequence covering addresses, dereference, pointer arithmetic, and dynamic memory), each running the full predict, trace, verdict, and modify loop, with a per-concept prediction record for the session. Students can export a prediction journal of their session, and an instructor digest aggregates exported journals into a per-exercise view of where predictions went wrong. The tracer is fully keyboard-operable, with screen-reader announcements for each step.
- **Debugging Gym:** five rounds of find-the-bugs exercises built from real beginner programs, faulty and corrected versions side by side at the end of each round.
- **Error Translator:** a searchable catalogue of twenty-six beginner compiler errors, each with the raw compiler message, a plain-English translation, the cause, and a before-and-after fix.
- **Challenges:** tasks, guided projects, and scored exams at Beginner, Intermediate, and Expert levels, drawn from real course assignments.
- **Make:** the authorship stage that completes the PRIMM sequence. Students write complete C++ programs in an in-page editor, run them with their own test input, and check them against six guided prompts, each with a verified test bench.

## Roadmap

TraceFirst is under active development toward a full platform:

- A real architecture behind the prototype: structured content, exercise engine, and student accounts with saved progress and instructor views of prediction accuracy by concept.
- A graphical interface and a downloadable app, alongside the web version.
- Growth along the pathway its author teaches: the introductory C++ sequence first, then the introduction to systems and computer organization, so a student can follow one continuous route from her first program to the operating system.

Design references, for ambition rather than imitation: Alice (Carnegie Mellon) for meeting novices inside a designed environment, GeeksforGeeks for the union of explanation and practice, and Stanford's Code in Place for teaching programming at community scale.

## License

To be decided. The prototype is published for review and feedback; no licence is granted yet beyond viewing.
