# Math Plus Quest

A personal, private prototype for learning mathematics from foundations to university level, with the Myanmar Grade 11 textbook as the main track.

## What it is
- A single-file web app (`index.html`): quest map by grade world, adaptive 5-question lessons with stars and XP, 60-second speed round, test builder, spaced-repetition review, function plotter, and a directory of 65 external learning resources.
- Every practice question comes with worked steps (Myanmar marking expects shown steps).
- All progress is stored locally in the browser (`localStorage`). There are no accounts, no cloud sync and no AI tutor.

## Run it
Open `index.html` in any modern browser. No build step.

## Status
| Item | State |
|---|---|
| Quest, speed, test, review, plot, library | Implemented and smoke-tested with a script (jsdom), not yet tested on real devices |
| Export / import backup (copy and paste JSON) | Implemented |
| Migration from the v1 save format | Implemented |
| Library links | External links, not individually verified |
| Refactor into modules, Vitest suite, link checker | Planned (Phases 1–2) |
| Cloud sync, accounts, AI tutor | Not started; deliberately deferred |

## Layout
- `index.html` current app
- `legacy/math-plus-v1.html` first version, kept for rollback
- `CHANGELOG.md`

## License
All rights reserved for now (personal project).
