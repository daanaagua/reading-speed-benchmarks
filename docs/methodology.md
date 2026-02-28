# Methodology

This document explains how benchmark defaults are used in MyReadingSpeed.

## Objective

Provide realistic default WPM values for different content types before a user has measured personal speed.

## Core model

- Reading time (minutes) = word count / WPM
- Word count is user-provided or inferred from text input.
- WPM starts from benchmark defaults and should be replaced by measured personal values.

## Design principles

1. **Genre-specific defaults**
   One global average is avoided because reading speed differs heavily by content type.

2. **Comprehension-aware baseline**
   Values prioritize practical comprehension speed, not speed-reading claims.

3. **Transparent assumptions**
   Benchmarks are visible in `data/benchmarks.csv` and can be adjusted over time.

## Interpreting benchmark bands

- `fast`: typically 260+ WPM for lower cognitive load text.
- `moderate`: roughly 180-259 WPM.
- `careful`: roughly 120-179 WPM.
- `deep`: below 120 WPM where frequent rereading is common.

These bands are descriptive labels, not score targets.

## Known limitations

- Individual variation can be 3x or more within the same genre.
- Text complexity varies inside each category.
- Purpose changes speed (skim vs study vs proofreading).
- Language proficiency and domain familiarity can dominate all defaults.

## Source notes

The benchmark design is informed by widely cited reading research and usability references, including:

- Carver (1990)
- Rayner et al. (2016)
- Nielsen Norman Group reading and web readability studies

This repository is a practical implementation layer, not a formal meta-analysis.
