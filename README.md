# SICP

My work through *Structure and Interpretation of Computer Programs* (2nd edition), chapters 1–4.

## Notes

Key points, definitions and the code worth remembering for each section, written to read after the book: [notes/](notes/README.md). Chapter 1 is complete: [1.1](notes/1.1.md), [1.2](notes/1.2.md), [1.3](notes/1.3.md).

## Labs

Interactive pages, one per week of the plan. Each is a single self-contained HTML file: open it in a browser, no build step.

| Week | Lab | Notes | Covers |
|---|---|---|---|
| 1 | [SICP 1.1 Lab](labs/sicp-1-1-lab.html) | [1.1](notes/1.1.md) | 1.1: substitution model, `cond`/`if`, applicative vs normal order, exercises 1.1–1.6 |
| 2 | [SICP 1.2 Lab](labs/sicp-1-2-lab.html) | [1.2](notes/1.2.md) | 1.2.1–1.2.3: recursive vs iterative processes, orders of growth, exercises 1.9–1.15 |

`index.html` at the root lists all labs and notes.

### Viewing them in a browser

Turn on GitHub Pages: **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / `(root)`**. The labs are then at `https://whale4rain.github.io/sicp/`.

Locally, open any file in `labs/`. The notes are Markdown, so read them on GitHub or through Pages (which renders them as HTML).

## How the labs work

Each lab includes a small JavaScript interpreter for the subset of Scheme the section uses. It evaluates with the book's substitution model, so every step can be shown, and it checks exercise answers by running them. Progress is stored in the browser's `localStorage`.
