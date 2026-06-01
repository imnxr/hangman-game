# Hangman Game

A polished browser-based Hangman project built for portfolio showcase, featuring a 100-level progression system, responsive 16:9 layout, clue letters, unlockable hints, and a clean SVG hangman scene.

## Live Demo

[Play the game](https://imnxr.github.io/hangman-game/)

Note: the first GitHub Pages deployment can take a couple of minutes after the workflow runs.

## Overview

This project is a modern HTML5 Hangman game designed to feel like a complete web game rather than a basic coding exercise. It starts with short easy words and gradually scales up to longer, trickier vocabulary across 100 levels. Each round reveals one or more starter letters, and a hint appears after 4 wrong guesses to help the player recover.

## Features

- 100 hand-ordered levels with increasing difficulty
- Easy, Medium, Hard, and Complex word tiers
- SVG hangman drawing with a red fail state on loss
- Responsive layout for desktop, tablet, and mobile screens
- External `HTML`, `CSS`, and `JavaScript` structure
- Keyboard input support plus on-screen letter controls
- Retry system that keeps the player on the same level after a loss

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- SVG for the hangman illustration

## Controls

- Click or tap letters on the on-screen keyboard
- Press `A-Z` on the physical keyboard to guess
- Press `Enter` to continue after a win or loss

## How It Works

1. Start a level and study the already revealed clue letters.
2. Guess the missing letters before the full hangman is drawn.
3. After 4 wrong guesses, use the unlocked hint to help finish the word.
4. Clear the level to move forward, or retry the same level if you lose.

## Difficulty Progression

- Levels 1-25: Easy words with 3 to 4 letters
- Levels 26-50: Medium words with 5 to 6 letters
- Levels 51-75: Hard words with 7 to 8 letters
- Levels 76-100: Complex words with 9 or more letters

## Portfolio Highlights

- Designed as a visually clean web game instead of a plain demo
- Refactored into separate files for maintainability
- Uses responsive scaling so the game fits smaller viewport heights better
- Includes structured game state, level progression, and reusable rendering logic

## Local Run

Open `index.html` in a browser, or serve the folder with any static file server.

## Suggested GitHub Topics

`hangman`, `html5`, `javascript`, `css`, `browser-game`, `word-game`, `responsive-design`, `portfolio-project`
