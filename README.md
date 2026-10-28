# The Eightfold Investing record

This is the public record behind [eightfoldinvesting.com](https://eightfoldinvesting.com): the rules I invest by, and what happened each month under them.

| Folder | What's in it |
|---|---|
| `content/rules/` | Every version of the rules, each committed before it came into force |
| `data/ledger/` | One entry a month: the index level, the benchmark, and the Breach Count |
| `data/holdings/` | Each month's holdings, by weight, published a month late |
| `data/ranked/` | Each month's full ranked list from the screen, published a month late |
| `data/loadings/` | The quarterly factor loadings |

Files here are added and never changed. A new version of the rules is a new file, and every earlier one stays. You can check that yourself:

```bash
git log --name-status
```

Every file should appear once, with an `A` beside it. An `M` or a `D` would mean something published was edited or removed.

There are no dollar amounts here, no balances, and no broker. The site explains why on its [disclosures page](https://eightfoldinvesting.com/disclosures/).
