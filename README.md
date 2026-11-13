# Plant ID Quiz

A free, single-page study and quiz tool for B.Pharm and D.Pharm students (Pharmacognosy I). No build step, no dependencies, no timer, instant feedback.

## Game modes

- **Specimen Hunt:** flashcard game. Type the answer within 30 seconds or the card flips and shows it. 3 hearts, combos, XP and stars.
- **Quiz:** 10 questions with 50:50 hints, a streak counter, an optional timer and a retry round for missed questions.
- **Match pairs:** pick one category (family, chemical class, constituent, use and more). Every round has 5 pairs of that category, and rounds repeat with new pairs.
- **Study table:** searchable and colour coded by chemical class.
- **Herbarium, levels and badges:** progress is saved in the browser (per device).

## Quiz sets

- **Crude drug list:** 55 drugs with synonyms, biological source, family, chemical constituent, class and use. 28 come from class notes and 27 are marked "added" in the study table. Check added entries against your syllabus.
- **Pharmaceutical aids:** enzymes, proteins, lipids, fibres, gums and bee products with synonyms, biological source, family and geographical source.
- **Crude drug casebook:** Pharmacognosy I cases (Units I to V) turned into clue-based questions, with the case file as feedback.

## Run locally

Open `index.html` in a browser.

## Publish on GitHub Pages

1. Push this repository to GitHub.
2. Go to Settings, then Pages.
3. Set the source to the `main` branch and the `/ (root)` folder.

## Adding content

All data is in the arrays at the top of the `<script>` in `index.html` (`L`, `A` and `C`).
