# Project Summary

This project is a web application for practicing aviation exams. It consists of a main page and three quiz pages, one for each of the following licenses: Private Pilot (PPL), Instrument Rating, and Commercial Pilot.

## Files

### `index.html`

This is the main entry point of the application. It's a simple HTML page with links to the other three pages: `PPL.html`, `Instrumentos.html`, and `Comercial.html`. The page has a modern design with a header and a grid of cards, each representing an exam.

### `PPL.html`

This file contains a quiz for the Private Pilot License (PPL). It has a database of questions and answers, and the user can select a range of questions to practice. It also has a "random mode" that selects a specified number of questions randomly. The page keeps track of the user's progress using `localStorage`.

### `Instrumentos.html`

This file is very similar to `PPL.html`, but it contains a quiz for the Instrument Rating. It has its own set of questions and answers, and the same functionality as `PPL.html`.

### `Comercial.html`

This file is also similar to the other two, but it contains a quiz for the Commercial Pilot License. It has its own set of questions and answers and the same functionality.

## Commonalities

All three quiz pages (`PPL.html`, `Instrumentos.html`, and `Comercial.html`) share a similar structure and functionality. They all use Bootstrap for styling and have a modern design. They all use JavaScript to handle the quiz logic, including question selection, progress tracking, and scoring.
