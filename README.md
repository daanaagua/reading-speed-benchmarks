# Reading Speed Benchmarks

Practical reading-speed reference data (WPM) by genre and content type.

This repository supports **MyReadingSpeed**, a free tool that first measures your speed by content type and then estimates realistic reading time.

- Main tool: https://myreadingspeed.top/
- Genre benchmarks page: https://myreadingspeed.top/average-reading-speed-by-genre
- Words-to-time page: https://myreadingspeed.top/words-to-reading-time-calculator

## Why this exists

Many reading-time calculators assume one generic WPM value for all users and all text types.
That creates large planning errors for academic, legal, or technical material.

This project keeps a transparent benchmark table so users can:

1. Start from a realistic baseline.
2. Measure their own speed.
3. Replace defaults with personal values.

## Repository contents

- `data/benchmarks.csv` - Genre-level default WPM values.
- `docs/methodology.md` - Modeling assumptions, formula, and source notes.
- `docs/examples.md` - Worked conversion examples.

## Quick formula

Reading time (minutes) = word count / WPM

Example:

- 10,000 words at 250 WPM -> 40 minutes
- 10,000 words at 100 WPM -> 100 minutes

## Notes

- Values in this repository are practical benchmark defaults, not guarantees.
- Individual speed depends on text difficulty, prior knowledge, fatigue, and reading goal.
