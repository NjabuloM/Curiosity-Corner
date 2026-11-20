# Curiosity Corner

> Exploring the things I'm curious about and figuring out how they work.

A personal learning journal about how complex systems work: how they are built, what keeps them stable, and what happens when they fail. It starts with the human body.

The aim is understanding, not a collection of facts: being able to look at something unfamiliar, build a mental model of it, test that model, and explain it simply.

## How it works

This project is driven by **questions, not a curriculum**.

1. Pick a question from [QUESTIONS.md](QUESTIONS.md).
2. Investigate it in its own file under [`questions/`](questions/), using the [template](questions/_template.md).
3. Write down a guess **before** reading anything, then find out how it actually works.
4. Finish with something tangible: an explanation, a diagram, a checked prediction or a model.
5. Log anything I got wrong in [MISCONCEPTIONS.md](MISCONCEPTIONS.md).
6. Add any new questions that come up back to [QUESTIONS.md](QUESTIONS.md).

Background knowledge (cell biology, anatomy, chemistry) is picked up when a question needs it, not studied in advance. Topic notes in [`notes/`](notes/) grow out of questions once several of them point at the same system.

## Three tests of understanding

- **Explain it.** To a 12-year-old, without notes, simply but without being wrong.
- **Predict it.** "If X changes, what happens to Y, and why?" Then check against a reliable source.
- **Model it.** Build a small simulation in [`models/`](models/). If I can't write down what affects what, and by how much, I don't understand it yet.

## Layout

| Path | What lives there |
| --- | --- |
| [QUESTIONS.md](QUESTIONS.md) | Backlog of open questions, and an index of the answered ones |
| [`questions/`](questions/) | One file per question investigated |
| [`notes/`](notes/) | Topic notes per system, written once enough questions have built them up |
| [`models/`](models/) | Small code simulations of feedback loops and mechanisms |
| [MISCONCEPTIONS.md](MISCONCEPTIONS.md) | Things I used to believe that turned out to be wrong |
| [MILESTONES.md](MILESTONES.md) | The current focus and what "done" means for it |

## Current focus

**Milestone 1: How does the body keep blood pressure stable?** See [MILESTONES.md](MILESTONES.md).

It is a deliberate first choice. Blood pressure regulation is the richest feedback-control system in the body, and following it properly reaches into the cardiovascular, urinary, nervous and endocrine systems.

## The first territory: the human body

The 11 major organ systems are a map, not a schedule:

integumentary · skeletal · muscular · nervous · endocrine · cardiovascular · lymphatic and immune · respiratory · digestive · urinary · reproductive

Each is looked at through the same lens: its **structure** (anatomy), how it **works normally** (physiology), what **goes wrong** (pathophysiology), and how it **connects** to the other systems. Diagnostics and pharmacology come in when a question leads there.

## Later

Human biology is the starting point, not the destination. The same approach can later go to ecology, economics, political institutions, technology and astronomy. The ideas that carry across are specific ones: stocks and flows, feedback loops, delays, set points, bottlenecks, redundancy, and compensation that eventually breaks down.

## Principles

1. **Understand, don't memorise.** Learn enough vocabulary to read, then focus on mechanisms.
2. **Think in systems.** Follow relationships, dependencies and chains of cause and effect.
3. **Normal before broken.** Understand how something works before studying how it fails.
4. **Keep it explainable.** Simple language, no loss of accuracy.
5. **Question assumptions.** Write down what doesn't make sense instead of skimming past it.
6. **Make something.** Every question ends in an output, not just reading or watching.

## Sources

- [OpenStax Anatomy & Physiology 2e](https://openstax.org/details/books/anatomy-and-physiology-2e): free, main reference
- [Khan Academy: Health and medicine](https://www.khanacademy.org/science/health-and-medicine): first introductions to a topic
- [Visible Body](https://www.visiblebody.com/learn): 3D anatomy
- Donella Meadows, *Thinking in Systems*: the general systems toolkit

AI tools are used as a tutor, quizzer and case simulator. Their claims are checked against the references above.

## Disclaimer

This is a personal educational project. The biological and medical material is for learning only. It is not medical advice and must not be used to diagnose or treat anything.
