# Hangman Game

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-16%3A9%20Game%20Layout-4A63F4?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

A portfolio-ready browser game built with HTML, CSS, and JavaScript. This project turns the classic Hangman idea into a more polished experience with a 100-level progression system, responsive widescreen layout, SVG-based visuals, starter clue letters, and unlockable hints.

## Live Demo

[Play the game](https://imnxr.github.io/hangman-game/)

The site is deployed with GitHub Pages through a GitHub Actions workflow.

If GitHub Pages was just enabled, the first deployment can take a few minutes to appear.

## Project Summary

This project was built to showcase front-end fundamentals through a complete mini game rather than a simple static page. The focus was on making the experience feel production-minded: structured game state, scalable level data, responsive layout behavior, separate code files, and a cleaner visual presentation suitable for a public portfolio.

## Why This Project Stands Out

- Expands a familiar game concept into a 100-level playable experience
- Uses progressive difficulty instead of random word selection
- Includes a real gameplay loop with win, loss, retry, and level advancement states
- Separates structure, styling, and logic into maintainable files
- Adapts the interface for desktop, tablet, and mobile screens
- Uses SVG for a crisp hangman scene without relying on images or canvas

## Core Features

- 100 hand-ordered levels with increasing difficulty
- Four difficulty tiers: Easy, Medium, Hard, and Complex
- Starter clue letters revealed at the beginning of each level
- Hint system that unlocks after 4 wrong guesses
- Red fail state when the player loses
- Keyboard input support and on-screen controls
- Retry system that keeps the player on the same level after a loss
- Responsive 16:9 desktop presentation with stacked mobile layout

## Gameplay

1. Start a level and inspect the visible clue letters.
2. Guess the hidden word one letter at a time.
3. Avoid reaching 6 wrong guesses.
4. Use the hint that appears after 4 mistakes.
5. Clear the level to move to the next word.

## Difficulty Progression

- Levels 1-25: 3 to 4 letter easy words
- Levels 26-50: 5 to 6 letter medium words
- Levels 51-75: 7 to 8 letter hard words
- Levels 76-100: 9+ letter complex words

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- SVG for the hangman illustration
- GitHub Pages for deployment
- GitHub Actions for automated publishing

## Project Structure

```text
hangman-game/
|- index.html
|- style.css
|- script.js
`- .github/workflows/deploy-pages.yml
```

## Recommended Screenshots

For a stronger portfolio presentation, add these images to the repository and include them in your GitHub project or portfolio website:

1. Main gameplay screen
Show the clean 16:9 game layout with the word board, hangman scene, and keyboard visible.

2. Hint unlocked state
Show a level after 4 wrong guesses so the hint panel is visible.

3. Losing state
Show the final red stickman fail state to highlight visual feedback and game-state transitions.

4. Mobile responsive view
Show the stacked layout on a phone-sized screen to demonstrate responsiveness.

Recommended filenames:

- `screenshot-desktop.png`
- `screenshot-hint.png`
- `screenshot-loss.png`
- `screenshot-mobile.png`

Recommended cover image text:

`100-level Hangman web game built with HTML, CSS, and JavaScript`

## Technical Highlights

- Level content is stored in structured data objects with both `word` and `hint` values
- Difficulty is derived from level index rather than a separate random system
- Rendering is handled through reusable update functions for the board, keyboard, hint, and hangman state
- Viewport-based sizing keeps the desktop frame shorter and more usable on smaller laptop screens
- Media queries adjust layout, spacing, keyboard columns, and tile sizing for different devices

## Controls

- Click or tap letters on the on-screen keyboard
- Press `A-Z` on the physical keyboard to guess
- Press `Enter` to continue after a win or loss

## Local Development

Open `index.html` directly in a browser, or serve the folder with any static file server.

## Portfolio Value

This repository demonstrates:

- Front-end UI layout and responsive design
- DOM manipulation with vanilla JavaScript
- State management for interactive gameplay
- Clean separation of concerns across HTML, CSS, and JavaScript
- Product thinking beyond a minimal tutorial-level implementation

## Showcase Tips

- Use the desktop gameplay screen as the GitHub social preview or project cover image
- Put the live demo link near the top of your portfolio card or case study
- Mention the 100-level progression because it makes the project sound more substantial
- Highlight that the project was built with vanilla JavaScript rather than a framework
- If you record a short demo, show the hint unlock and fail-state color change

## Recommended GitHub Settings

Repository description:
`A responsive 100-level Hangman web game built with HTML, CSS, and JavaScript.`

Homepage URL:
`https://imnxr.github.io/hangman-game/`

Suggested topics:
`hangman`, `html5`, `javascript`, `css`, `browser-game`, `word-game`, `responsive-design`, `portfolio-project`
