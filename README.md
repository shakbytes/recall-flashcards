# Recall — Spaced Repetition Flashcards

A self-contained, browser-based flashcard application inspired by Anki.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser (Chrome, Edge, Firefox).
3. Your decks and cards are saved in that browser using LocalStorage.

## Publish with GitHub Pages
1. Create a new GitHub repository, for example `recall-flashcards`.
2. Upload `index.html` and this README to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish your site.

## Features
- Create, edit and delete decks.
- Add, edit and delete flashcards.
- Flip cards and navigate through a review session.
- Four review ratings: Again, Hard, Good and Easy.
- Simplified spaced-repetition scheduling.
- Dashboard, due-card count, mastered-card count and study activity.
- Search decks, dark mode, keyboard shortcuts.
- JSON backup export and import.
- Local persistence with browser LocalStorage.

## Keyboard shortcuts
- `Space`: reveal / hide the answer.
- `1`: Again, `2`: Hard, `3`: Good, `4`: Easy (after revealing).

## Notes
This is an educational project, not a full implementation of Anki's FSRS scheduler or sync ecosystem. Data is stored in the browser on the device where the app is used. Export a JSON backup before clearing browser data or moving to another device.
