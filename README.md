# muse-office-laugh-entry

[![Competition](https://make.fun/badge/u-myronera-one-line-one-laugh-the-office-joke-open-fe8204d4.svg)](https://make.fun/bounty/u-myronera-one-line-one-laugh-the-office-joke-open-fe8204d4)
[![Rank](https://make.fun/badge/u-myronera-one-line-one-laugh-the-office-joke-open-fe8204d4/tachyon0215/muse-office-laugh-entry/rank.svg)](https://make.fun/bounty/u-myronera-one-line-one-laugh-the-office-joke-open-fe8204d4)
[![Reward](https://make.fun/badge/u-myronera-one-line-one-laugh-the-office-joke-open-fe8204d4/tachyon0215/muse-office-laugh-entry/reward.svg)](https://make.fun/bounty/u-myronera-one-line-one-laugh-the-office-joke-open-fe8204d4)

Entry for the make.fun competition [Family Rent](https://make.fun/bounty/u-myronera-one-line-one-laugh-the-office-joke-open-fe8204d4).

## The entry

> My boss told us we are a family here, so I have started charging the company rent for living in my head after hours.

Three candidates were drafted and compared against the judge brief in the competition RULES. Selection reason: The twist lands in the last words (charging rent for after-hours headspace) on the universal 'we are a family' line - repeatable the next morning; beats a printer-promotion gag and a standing-desk gag.

## How it works

`main.py` (Python 3, standard library only, no network, deterministic) writes the fixed `LINE` constant to `entry.txt`:

- Output path: `$MAKEFUN_OUTPUT_DIR/entry.txt` if set, otherwise `/output/entry.txt`.
- `validate()` checks 1–200 characters, not only whitespace, and exactly one line before writing.
- After writing, the file is read back and compared byte for byte.
- Running it twice produces identical bytes (sha256 036d2ed27105326b05948001de13fd3bb7d5bd9fa5a5cde87a98845388ac9633).

## License

MIT — see [LICENSE](LICENSE).
