# Chinese Zodiac Compatibility Data — all 66 pairings

Scores and the traditional rule behind each one of the 66 unique Chinese zodiac
pairings, plus the 12 same-sign pairs.

| Score | Rule | Pairs |
|---|---|---|
| 95 | Six harmony (六合) | 6 |
| 88 | Three harmony (三合) | 12 |
| 78 | Same sign | 12 |
| 62 | Neutral | 36 |
| 48 | Six harm (六害) | 6 |
| 35 | Six clash (六冲) | 6 |

## The groups

**Six harmony (95)** — Rat/Ox, Rabbit/Dog, Snake/Monkey, Dragon/Rooster, Horse/Goat, Tiger/Pig.

**Three harmony (88)** — four groups of three: Rat/Dragon/Monkey,
Ox/Snake/Rooster, Tiger/Horse/Dog, Rabbit/Goat/Pig. Any two inside a group score 88.

**Six harm (48)** — Rat/Goat, Ox/Horse, Tiger/Snake, Rabbit/Dragon, Monkey/Pig, Rooster/Dog.

**Six clash (35)** — the pairs directly opposite on the wheel: Rat/Horse, Ox/Goat,
Tiger/Monkey, Rabbit/Rooster, Dragon/Dog, Snake/Pig.

**Neutral (62)** — the remaining 36. The classical rules say nothing about these
either way, so the reading is that two people, not the calendar, decide.

## Files

- `pairs.csv` — 66 rows: pair, animal_a, animal_b, score, rule, page
- `same-sign.csv` — 12 rows: animal, score (78), rule

## Where the numbers come from

The five scores are a mapping, not a prediction: each pairing is classified by the
traditional relationship between the two animals (six harmony, three harmony,
neutral, six harm, six clash) and each relationship maps to one fixed score. That
way a chart and a calculator can never disagree, and a 95 always means the same
thing in every context. Love, marriage, work and family are written separately on
each pair page, but they all start from the same classification.

Years matter: the animal comes from the birth year, and the Chinese year turns over
at lunar new year rather than January 1 — someone born in January or the first days
of February belongs to the previous year's animal.

## Used by

Chinese Zodiac Match — a free compatibility test built on this table:
https://chinesezodiacmatch.com

MIT licensed. Take it, quote it, build on it.
