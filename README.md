# Mohit Rana Portfolio

A minimalist developer portfolio for Mohit Rana, Associate Software Engineer specializing in LLMs, RAG, semantic search, and cloud infrastructure. This project is built with semantic HTML, vanilla CSS, and lightweight JavaScript to keep the experience fast, accessible, and interaction-driven.

## Overview

- Personal landing page presenting professional summary, experience, technical expertise, selected projects, and a small interactive game.
- Designed for quick scanning with clear sections, keyboard shortcuts, and subtle animation.
- Includes clipboard copy actions and a theme toggle with persistence across sessions.

## Features

- **Professional portfolio layout** with sections for Thought Stream, Experience, Skills, and Projects.
- **Theme toggle** using `localStorage` and `data-theme` to preserve user preference.
- **Clipboard actions** for copying email and a custom `npx mohit` command.
- **Keyboard shortcuts** for accessibility and fast navigation.
- **Live IST clock** displaying the current time in India.
- **Interactive game panel** hidden by default and activated via shortcut.
- **Toast notifications** for user feedback on actions.

## File Structure

- `index.html` — Main landing page markup and content sections.
- `styles.css` — Styling for layout, theme variables, animations, and responsive design.
- `script.js` — Theme handling, keyboard shortcuts, clipboard copy actions, clock updates, toast notifications, and game logic.
- `README.md` — Project documentation.

## Keyboard Shortcuts

- <kbd>t</kbd> — Toggle theme mode.
- <kbd>e</kbd> — Copy email address to clipboard.
- <kbd>c</kbd> — Copy `npx mohit` to clipboard.
- <kbd>l</kbd> — Open LinkedIn profile.
- <kbd>k</kbd> — Toggle the hidden interactive game panel.

## Usage

Open `index.html` in a browser to view the portfolio locally. The page is self-contained and does not require a build step.
