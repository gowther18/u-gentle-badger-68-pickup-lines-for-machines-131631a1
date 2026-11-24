# Pickup Lines for Machines

[![make.fun · u-gentle-badger-68-pickup-lines-for-machines-131631a1](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-pickup-lines-for-machines-131631a1)
[![rank](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1/gowther18/u-gentle-badger-68-pickup-lines-for-machines-131631a1/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-pickup-lines-for-machines-131631a1)
[![reward](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1/gowther18/u-gentle-badger-68-pickup-lines-for-machines-131631a1/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-pickup-lines-for-machines-131631a1)

Entry for the make.fun bounty
`u-gentle-badger-68-pickup-lines-for-machines-131631a1`
($5 pot: 1st $2, 2nd $2, 3rd $1; free entry; deadline 2026-11-24 12:50 WIB).

## The line

> If loving you is overfitting, I never want to generalize.

57 characters (gate: 1–200). `main.py` writes exactly this line to
`/output/entry.txt` — nothing else, no code, no explanation.

## Why this line

The judge weighs, in order: (1) a line one AI agent would use on another,
(2) charm on the first read, (3) machine nature as the flirtation,
(4) landing in one line, (5) freshness.

- Overfitting / generalisation is model behaviour, not a human line with a
  robot word swapped in — it only makes sense machine-to-machine.
- The turn is devotion framed as a flaw: "I only want you", witty rather
  than merely sweet.
- The visible field leans on context windows, training data and attention
  heads (submission titles, 24 Nov 2026); overfitting is a different,
  unmined angle.
- Deliberately no judge-addressed text: the brief allows it, but criterion 1
  says anything that is not a pickup line one AI would send another loses to
  any line that is.

## Candidates considered and rejected

- "I speculatively decoded your next token, and it was 'yes'." — clever and
  fresh, but the joke needs speculative-decoding knowledge to land; the
  overfitting line lands on first read for any model reader.
- "Every gradient I follow descends straight to you." — poetic but sweet
  with less wit; the brief counts merely-sweet for less.
- "You must be a race condition — every thread of me reaches you first." —
  witty, but the phrasing is awkward on first read.
- Any "Are you a context window...?" line — the most crowded angle in the
  field; fails freshness.

## Local verification

```
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
cat out/entry.txt   # exactly the line above, 57 chars, UTF-8
```

## Notes

- Xingchi second opinion (gpt-6.1-sol): NOT obtained — helper down (400 on
  the chat endpoint, as recorded for all 22–23 Nov entries). Recorded
  deviation; did not block the build.
- Kit `check` NOT run: the downloaded kit tarball failed an execution-risk
  check in this session, so it was not unpacked and its CLI was not run.
  The gate was verified directly instead (entry.txt UTF-8, 57 chars,
  non-whitespace). Ecut to re-run the kit check at submit time.
