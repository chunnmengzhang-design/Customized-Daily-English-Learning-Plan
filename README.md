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

## Before First Use

If someone forks or copies this project, the first step should be defining a learner profile before generating daily plans.

Recommended setup fields:

- English level: for example `Level 2`, `Level 4`, or another starting level
- Learning goal: for example `Business English`, `IELTS`, `Primary School`, `Middle School`, or `High School`
- Daily study time: for example `30 minutes`, `60 minutes`, or `90 minutes`
- Main focus: for example listening, speaking, vocabulary, reading, writing, exam practice, or schoolwork

Example learner profiles:

- `Level 4 + Business English`: meetings, emails, project updates, client communication
- `Level 2 + School English`: basic vocabulary, sentence building, textbook reading, homework support
- `Level 4 + IELTS`: listening practice, speaking responses, reading speed, writing task structure

## Customization for Forks

This repository is currently configured for one fixed learner profile:

- Level: `Level 4`
- Goal: `Business English`
- Daily time: about `1 hour`

If another user wants to reuse this project, they should first customize these files:

- `README.md`: update the project description and target learner
- `notion-business-english-system.md`: replace the 30-day structure with a plan that matches the new level and learning goal
- `index.html`: update the live study page layout content, wording, and examples
- `data/checkin.csv`: reset or rebuild the tracking records for the new learner

Recommended initialization flow for a new user:

1. Decide the learner's English level.
2. Decide the learning purpose, such as business, IELTS, or school study.
3. Set the daily study time.
4. Rewrite the 30-day topic progression to match that profile.
5. Regenerate the daily page content and tracking file from that customized plan.

## Quick Start for New Users

If you fork this project for your own use, start by filling in a simple learner profile like this:

```text
English level: Level 2 / Level 4 / Level 6
Learning goal: Business English / IELTS / Primary School / Middle School / High School
Daily study time: 30 minutes / 60 minutes / 90 minutes
Main focus: listening / speaking / vocabulary / reading / writing / exam practice
```

Example profiles:

```text
English level: Level 4
Learning goal: Business English
Daily study time: 60 minutes
Main focus: listening + speaking + vocabulary
```

```text
English level: Level 2
Learning goal: High School English
Daily study time: 45 minutes
Main focus: vocabulary + reading + sentence building
```

```text
English level: Level 4
Learning goal: IELTS
Daily study time: 90 minutes
Main focus: listening + speaking + writing
```

After that, update the study system so the daily topics, materials, and exercises actually match that learner profile.

## Suggested Setup Questions

Before generating a personalized plan, answer these questions:

1. What is the learner's current English level?
2. What is the learner studying for?
3. How much time can they study each day?
4. Which skills need the most improvement?
5. Should the plan focus on work communication, school study, or exam preparation?

The clearer these answers are, the easier it is to generate a useful daily study plan.

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
