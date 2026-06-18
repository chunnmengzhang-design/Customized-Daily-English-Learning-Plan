# Customized Daily English Learning Plan

A customizable daily business English learning planner with level-based lessons, free authoritative materials, built-in countdown timers, and interactive Q&A.

## Overview

This project turns a local HTML page into a daily business English study sheet for learners who want a structured 60-minute routine.

It is designed for learners around Level 4 and focuses on:

- listening
- speaking
- vocabulary plus spaced review
- short reading
- short writing

The daily page is generated in a lecture-style format so the learner can simply open the page and study from top to bottom.

## Highlights

- Level-based customization: the daily plan can be tailored to the learner's current English level and business communication goals.
- Free and authoritative materials: listening and reading tasks prioritize trusted sources such as BBC Learning English, TED, Harvard Business Review, and Cambridge Dictionary.
- Built-in countdown timer: the HTML page includes a timer to support a 60-minute study flow.
- Interactive Q&A: each daily plan ends with practical questions and ready-to-use answers for likely speaking, writing, or vocabulary blockers.
- Text-to-speech support: users can select English text and use the built-in read-aloud controls for fast follow-along practice.
- GitHub Pages ready: the project can be published as a static site and updated automatically through git push.

## What the Daily Plan Includes

Each generated study page follows a fixed structure:

1. Today's topic
2. Today's goal
3. Today's schedule
4. Listening material
5. Vocabulary study plus review
6. Speaking practice
7. Reading material
8. Writing task
9. Output assignment
10. Check-in standard
11. Daily Q&A

## Live Site

GitHub Pages URL:

[https://chunnmengzhang-design.github.io/Customized-Daily-English-Learning-Plan/](https://chunnmengzhang-design.github.io/Customized-Daily-English-Learning-Plan/)

## Project Files

- `index.html`: the main daily study page
- `data/checkin.csv`: day tracking and study history
- `notion-business-english-system.md`: the full 30-day study framework and template reference

## How to Use

1. Open `index.html` in a browser.
2. Follow the study page from top to bottom.
3. Use the timer for each study block.
4. Click the vocabulary or sentence read-aloud buttons, or select text and use the read-aloud control.
5. Complete the daily speaking, reading, and writing tasks.
6. Record progress in the daily check-in flow.

## Local Development

This is a static HTML project, so no build step is required.

To preview locally:

1. Open `index.html` directly in a browser.
2. Or serve the folder with any static server if you prefer a localhost URL.

## Automation

The project is connected to a daily automation that:

- generates the next daily English learning plan
- updates local project files
- commits the relevant changes
- pushes them to `origin/main`

That means the GitHub Pages site can stay in sync with the latest generated study plan.

## Content Sources

Preferred sources used by the study plans:

- BBC Learning English
- TED
- Harvard Business Review
- Cambridge Dictionary

The project favors:

- free access
- direct content links
- concrete listening or reading assignments
- materials suitable for business English study

## Notes

- The current structure is optimized for daily use rather than for storing every full lesson on the README page.
- Detailed study system content remains in `notion-business-english-system.md`.
- The site is intended to be practical first: open, study, speak, write, and check in.
