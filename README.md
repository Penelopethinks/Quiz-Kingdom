# Quiz Kingdom

A responsive browser based trivia arcade in a sage green theme. It includes a welcome intro, six subject realms, four game modes, 120 themed quiz editions, answer reviews, progress and crown rewards, a daily quest, and browser saved preferences.

## Run it

Open [index.html](./index.html) in a modern browser. Keep `quiz-expansion.js` beside it; the page loads the expanded quiz bank from that file. No build step or package install is needed.

Progress and settings are saved in the browser's local storage.

## Game modes

- **Classic Quiz** — multiple choice with explanations.
- **True or False** — judge a statement for each question.
- **Lightning Round** — answer before the 10 second timer expires.
- **Word Scramble** — unscramble and type each answer.

Choose a subject in Game Arcade before starting a game. The question rotation prioritizes unseen questions and resets after a pool has been exhausted.
