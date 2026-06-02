# Pair Programming Workshop

A practical peer learning event for researchers who use code in their work. Organised as part of an [SSI Fellowship](https://www.software.ac.uk/fellowships).

## What is this?

Many researchers — especially bioinformaticians — write code as part of their work but have had little formal training in software development practices. This workshop uses pair programming as a low-barrier way to share skills, build confidence, and learn from peers.

Pair programming is simply two people working on one piece of code together, at one computer. One person types (the *driver*); the other thinks about direction and catches issues (the *navigator*). They switch regularly.

## Why pair programming?

- **Low barrier**: you bring your own code, so you're immediately useful to your partner
- **Real knowledge transfer**: you learn by doing, not by watching
- **Cross-pollination**: a computational biologist and a genomics analyst may use completely different tools — working together surfaces approaches neither knew about
- **No prior preparation needed**: unlike code review, you don't need to understand someone else's code before you arrive

## Format

A typical session runs ~2 hours:

| Time | Activity |
|------|----------|
| 0:00 | Welcome and intro talk (~20 min) |
| 0:20 | Round 1 — pair A works on person 1's code (~25 min) |
| 0:45 | Short break + swap partners (~5 min) |
| 0:50 | Round 2 — pair B works on person 2's code (~25 min) |
| 1:15 | Optional round 3 or open hacking (~30 min) |
| 1:45 | Debrief and close (~15 min) |

Participants are paired randomly, and pairings rotate each round.

## Materials

This repo is a Quarto website. Pages:

- `index.qmd` — landing page with event overview and sign-up link
- `participant.qmd` — pairing tips and what to bring (also renders to PDF)
- `facilitator.qmd` — how to organise and run the event
- `slides.qmd` — Reveal.js slide deck for the intro talk

### Building locally

```bash
quarto preview
```

### Deploying to GitHub Pages

```bash
quarto publish gh-pages
```

The `docs/` directory contains the original plain-markdown versions of the facilitator guide and participant reference.

## Contributing

Feedback and improvements welcome — open an issue or PR.
