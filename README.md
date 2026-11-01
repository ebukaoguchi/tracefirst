# TraceFirst

**A prediction-first learning platform for introductory C++** — built by [Ebuka Philip Oguchi](https://ebukaoguchi.github.io/), Assistant Professor of Computer and Information Sciences, Spelman College, for SCIS 121, a first-year course serving CS and non-CS majors together.

## The idea

Beginners do not fail C++ on the hard topics. They fail early, when a program's behaviour is invisible to them and a compiler error reads as a verdict instead of a message. TraceFirst is built on one discipline, drawn from the PRIMM model in computing-education research (Predict, Run, Investigate, Modify, Make):

1. **Predict.** The student sees a short program and must commit to what it will print. The prediction is locked before anything runs.
2. **Run and trace.** The student steps through the program line by line, watching labelled memory boxes hold and change values, and the output console fill.
3. **Confront the gap.** A wrong prediction is diagnosed at the exact step where the student's mental model and the machine parted, with the misconception behind the chosen answer named.
4. **Modify.** One value changes, and the student predicts again.

Every exercise exists in four story skins (Health & Biology, Psychology & Social Science, Business & Economics, Arts & Media) over identical code, so a non-CS major meets the concept inside her own field while the class shares one concept sequence.

## Current state: prototype

`index.html` is a self-contained prototype of the prediction tracer: five exercises (assignment, integer division, if/else, for loops, functions), each running the full predict, trace, verdict, and modify loop, with a per-concept prediction record for the session. Open it in any browser; there is nothing to install and nothing is sent anywhere.

The debugging gym and compiler-error translator from the original design are not in this slice yet.

## Roadmap

TraceFirst is under active development toward a full platform:

- A real architecture behind the prototype: structured content, exercise engine, and student accounts with saved progress and instructor views of prediction accuracy by concept.
- A graphical interface and a downloadable app, alongside the web version.
- The debugging gym and error translator.
- Growth along the pathway its author teaches: the introductory C++ sequence first, then the introduction to systems and computer organization (the pathway behind the companion [Systems Labs](https://github.com/ebukaoguchi/systems-labs) collection), so a student can follow one continuous route from her first program to the operating system.

Design references, for ambition rather than imitation: Alice (Carnegie Mellon) for meeting novices inside a designed environment, GeeksforGeeks for the union of explanation and practice, and Stanford's Code in Place for teaching programming at community scale.

## Relationship to Systems Labs

TraceFirst is a separate project from [Systems Labs](https://github.com/ebukaoguchi/systems-labs), the author's open collection of laboratory modules. The two are expected to converge: Systems Labs supplies the systems pathway's content; TraceFirst is the learning environment students will move through.

## License

To be decided. The prototype is published for review and feedback; no licence is granted yet beyond viewing.
