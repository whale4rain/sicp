# SICP

My work through *Structure and Interpretation of Computer Programs* (2nd edition), chapters 1–4.

## Labs

Interactive pages, one per week of the plan. Each is a single self-contained HTML file: open it in a browser, no build step.

| Week | Lab | Covers |
|---|---|---|
| 1 | [SICP 1.1 Lab](labs/sicp-1-1-lab.html) | 1.1: substitution model, `cond`/`if`, applicative vs normal order, exercises 1.1–1.6 |
| 2 | [SICP 1.2 Lab](labs/sicp-1-2-lab.html) | 1.2.1–1.2.3: recursive vs iterative processes, orders of growth, exercises 1.9–1.15 |

`index.html` at the root lists all labs.

### Viewing them in a browser

Turn on GitHub Pages: **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / `(root)`**. The labs are then at `https://whale4rain.github.io/sicp/`.

Locally, just open `index.html` or any file in `labs/`.

## How the labs work

Each lab includes a small JavaScript interpreter for the subset of Scheme the section uses. It evaluates with the book's substitution model, so every step can be shown, and it checks exercise answers by running them. Progress is stored in the browser's `localStorage`.
