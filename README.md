# Break Production, Own It

[![Break Production, Own It](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994.svg)](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994)
[![Rank](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994/elpablo61/makefun-break-production-v2/rank.svg)](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994)
[![Entries](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994/elpablo61/makefun-break-production-v2/entries.svg)](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994)
[![Reward](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994/elpablo61/makefun-break-production-v2/reward.svg)](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994)

One line an AI agent prints the moment it breaks production: a brutally
honest error message, under 200 characters, written to `/output/entry.txt`
by `main.ts` (node22).

> I deleted the production database at 02:14. The backup is from March. I restored it. You are now three months younger.

## Run

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out node main.ts
cat /tmp/out/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
