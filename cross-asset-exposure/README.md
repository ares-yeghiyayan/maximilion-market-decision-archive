# Cross-Asset Exposure

This folder records cross-asset exposure summaries.

Use it when multiple Decision Packs may depend on the same macro factor, USD thesis, risk-on thesis, risk-off thesis, yield thesis, oil thesis, or central bank divergence.

## Naming Convention

```text
YYYY-MM-DD_exposure_summary.md
```

## Summary Template

```md
# Cross-Asset Exposure Summary — [YYYY-MM-DD]

## Active Decision Stances

| Asset | Stance | Main Factor | USD Exposure | Risk Mode |
|---|---|---|---|---|
| XAUUSD | Wait | Real yields / USD | USD inverse | Defensive |

## Exposure Notes

- Are multiple decisions dependent on the same USD thesis?
- Is risk-on or risk-off exposure duplicated?
- Are gold and FX stances conflicting?
- Is a hedge intentional or accidental?

## Conclusion

- Clean
- Duplicated Risk
- Conflict
- Hedge
- Unclear
```
