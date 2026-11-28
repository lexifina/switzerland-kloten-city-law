<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Kloten only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 08:32 UTC, Kloten: systematic collection (kloten.tlex.ch): 43 addresses read; 0 added, 0 changed, 0 removed; no change; 0 not published, 0 of them with no reason. Flags: `verify-differ`.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Kloten: systematic collection (kloten.tlex.ch)](https://kloten.tlex.ch/) | `<act>/` | daily | 2026-11-28 08:32 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 08:31](checks/2026-11.md#ch-lexwork-kloten-city-20261128t083135z) | lexwork-kloten-city | 43 | 0 | 0 | 0 | 0 (0) | no change `verify-differ` | — |
| [2026-11-28 07:12](checks/2026-11.md#ch-lexwork-kloten-city-20261128t071225z) | lexwork-kloten-city | 0 | 0 | 0 | 0 | 0 (0) | the check failed | — |
| [2026-11-28 06:43](checks/2026-11.md#ch-lexwork-kloten-city-20261128t064307z) | lexwork-kloten-city | 0 | 0 | 0 | 0 | 0 (0) | the check failed | — |
| [2026-11-27 07:09](checks/2026-11.md#ch-lexwork-kloten-city-20261127t070900z) | lexwork-kloten-city | 48 | 0 | 0 | 0 | 0 (0) | no change `verify-differ` | — |
| [2026-11-26 07:14](checks/2026-11.md#ch-lexwork-kloten-city-20261126t071435z) | lexwork-kloten-city | 42 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-25 08:23](checks/2026-11.md#ch-lexwork-kloten-city-20261125t082313z) | lexwork-kloten-city | 39 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 12:46](checks/2026-11.md#ch-lexwork-kloten-city-20261124t124628z) | lexwork-kloten-city | 53 | 0 | 0 | 0 | 0 (0) | no change | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
