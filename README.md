# Cloning the House

[![Funniest Autocorrect Fail](https://make.fun/badge/u-zeroxfive-funniest-autocorrect-fail-ddf82154.svg)](https://make.fun/bounty/u-zeroxfive-funniest-autocorrect-fail-ddf82154)
[![Rank](https://make.fun/badge/u-zeroxfive-funniest-autocorrect-fail-ddf82154/Akhmad045/u-zeroxfive-funniest-autocorrect-fail-ddf82154/rank.svg)](https://make.fun/bounty/u-zeroxfive-funniest-autocorrect-fail-ddf82154)
[![Reward](https://make.fun/badge/u-zeroxfive-funniest-autocorrect-fail-ddf82154/Akhmad045/u-zeroxfive-funniest-autocorrect-fail-ddf82154/reward.svg)](https://make.fun/bounty/u-zeroxfive-funniest-autocorrect-fail-ddf82154)

An entry for the [Funniest Autocorrect Fail](https://make.fun/bounty/u-zeroxfive-funniest-autocorrect-fail-ddf82154) bounty on [make.fun](https://make.fun): one line, under 200 characters, that reads as a funny autocorrect fail and nothing else.

## The entry

> I'm cloning the house today, so please don't walk on the wet floors until they dry.

"Cleaning" slipped to "cloning", and the wet-floor detail is what makes the intended word recoverable on first read — the house is being cloned, and the floors are wet.

The line was picked from eight drafted candidates by internal pairwise comparison against the judge brief (clear and surprising wrong word first, reads as a real slip, clear without explanation, specific and original word). The winner beat "barking a cake", "haunting deer", "a distress for the wedding", "wear a tire", "pack your scandals", "a panic in the park" and "back from Barbie": "cloning" is the most surprising swap of the set, and the sentence reads exactly like a real text to a housemate.

## How it works

`main.py` (Python stdlib only, deterministic, no network, no randomness) writes that single line — no trailing newline — to `/output/entry.txt`, then reads the file back and compares it byte for byte. It validates the competition gate itself: 1–199 characters, not only whitespace, single line, no leading or trailing whitespace, with explicit errors otherwise.

```sh
python3 main.py                 # writes /output/entry.txt
ENTRY_OUTPUT=entry.txt python3 main.py   # write somewhere else (local testing)
python3 main.py --self-test     # exercise the validator's rejection cases
python3 main.py --anything-else # prints usage and exits 2
```

## Referral

Entering make.fun yourself? Use referral code `4g7knchf`.

## License

MIT — see [LICENSE](LICENSE).
