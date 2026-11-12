# Plant ID Quiz

A free, single-page study and quiz tool for B.Pharm and D.Pharm students (Pharmacognosy I). No build step, no dependencies, no timer, instant feedback.

## Quiz sets

- **Drugs from plants:** common name, scientific name, constituent, chemical class and use.
- **Pharmaceutical aids:** enzymes, proteins, lipids, fibres, gums and bee products with synonyms, biological source, family and geographical source.
- **Crude drug list:** 28 drugs from class notes (synonyms, biological source, family) plus 17 added drugs marked "added" in the study table. Check added entries against your syllabus.
- **Crude drug casebook:** Pharmacognosy I cases (Units I to V) turned into clue-based questions, with the case file as feedback.

Each set has searchable study cards and quizzes of 10 questions, including a mixed mode.

## Run locally

Open `index.html` in a browser.

## Publish on GitHub Pages

1. Push this repository to GitHub.
2. Go to Settings, then Pages.
3. Set the source to the `main` branch and the `/ (root)` folder.

## Adding content

All data is in the arrays at the top of the `<script>` in `index.html` (`D`, `A`, `L` and `C`). Each row is documented by a comment above its array.
