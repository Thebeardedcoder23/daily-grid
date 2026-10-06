# Daily Grid

Private working repository for a mobile-first personalized crossword.

## Status

**Playable v1 complete.**

Validated:
- 11x11 grid
- 12 personalized entries
- Every playable cell belongs to a clued entry
- All entry coordinates and crossing letters validate against the solution
- Mobile/desktop keyboard input
- Across/Down clue navigation
- Check feedback
- Local progress saving
- Completion detection
- Animated final reveal
- Neutral title and pre-reveal presentation

## Puzzle approach

This version uses a compact freeform crossword layout rather than forcing filler words into every row and column. That lets the puzzle stay easy, personal, and clean instead of introducing obscure crosswordese simply to satisfy a fully checked American-style grid.

The entries include relationship-specific material such as Alcatraz, airport, Mandy, Philly, Hayley, porch, YouTube, Karl, and the Hinge-profile “commit to the bit” callback.

## Deployment

Keep the repository private while reviewing/testing. Static hosting can be enabled after approval. If using GitHub Pages on an account/plan that requires a public repository for Pages, make the repository public only when ready to publish, or use a static host connected to this repository.

## Files

- `index.html` — app shell
- `styles.css` — responsive layout and reveal styling
- `app.js` — solver, navigation, persistence, completion/reveal
- `data/puzzle.json` — human-readable puzzle source
- `data/answer-bank.json` — broader relationship clue bank
- `docs/puzzle-spec.md` — design notes
