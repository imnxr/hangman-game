# Hangman Game

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-16%3A9%20Layout-4A63F4?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

A browser-based Hangman game built with HTML, CSS, and JavaScript. This project expands the classic word-guessing format into a 100-level experience with progressive difficulty, starter clue letters, unlockable hints, and a responsive widescreen layout.

## Play Online

[Live Demo](https://imnxr.github.io/hangman-game/)

## About The Project

This game was built as a complete front-end project rather than a basic Hangman exercise. The goal was to create a cleaner and more polished browser game experience with structured progression, readable code separation, and responsive UI behavior across different screen sizes.

The gameplay starts with shorter easy words and gradually moves into longer and more difficult vocabulary. Each level begins with one or more clue letters already visible, and the player can unlock a hint after four wrong guesses. If the player reaches six wrong guesses, the level is lost and can be retried.

## Features

- 100 hand-ordered levels
- Four difficulty tiers: Easy, Medium, Hard, and Complex
- Starter clue letters at the beginning of each round
- Hint unlock after 4 incorrect guesses
- Retry current level after a loss
- Keyboard input support and on-screen controls
- Responsive layout for desktop, tablet, and mobile
- SVG-based hangman scene with a red fail state

## Gameplay

1. Start a level and inspect the visible clue letters.
2. Guess the missing letters one at a time.
3. Avoid reaching 6 incorrect guesses.
4. Use the unlocked hint after 4 wrong guesses.
5. Complete the word to move to the next level.

## Difficulty Progression

- Levels 1-25: 3 to 4 letter words
- Levels 26-50: 5 to 6 letter words
- Levels 51-75: 7 to 8 letter words
- Levels 76-100: 9+ letter words

## How It Was Built

The project is split into separate files for structure, styling, and logic:

- `index.html` contains the page structure and the SVG hangman scene
- `style.css` contains layout, responsiveness, colors, and game UI styling
- `script.js` contains the level data, game state, input handling, and rendering updates

The JavaScript logic is driven by level objects that store both a `word` and a `hint`. The UI updates dynamically based on the current level, guessed letters, number of mistakes, and win/loss state.

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- SVG
- GitHub Pages
- GitHub Actions

## Technical Highlights

- Structured level data for 100 levels
- Game-state driven rendering
- Dynamic keyboard generation and input handling
- Viewport-based sizing for a less crowded desktop layout
- Media queries for responsive behavior on smaller screens
- Separate files for maintainability and cleaner project structure

## Project Structure

```text
hangman-game/
|- index.html
|- style.css
|- script.js
`- .github/workflows/deploy-pages.yml
```

## Run Locally

Open `index.html` directly in a browser, or serve the folder with any static file server.

## License

This project is licensed under the MIT License.
