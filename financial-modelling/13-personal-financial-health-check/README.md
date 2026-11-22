# Personal financial health check: an Excel template for households

**Result:** one file that tells a household whether its finances are healthy. Fill in the yellow cells and every total and ratio updates itself.

> Excel template shown with sample household data (IDR, illustrative). Meant to be rerun monthly so each ratio can be tracked over time.

## The gap and the tool
Most households know their salary, but not their net worth, debt burden or savings rate. The template has three linked sheets:

1. **Balance sheet:** what the household owns and owes. Yellow cells are the only inputs; everything else is a formula, so the user cannot break the logic. Assets in three layers (cash, investments, fixed assets at second-hand value); debt split by horizon (due within a year vs remaining mortgage and car loan).
2. **Monthly cash flow:** five income sources and six expense groups (needs, savings, insurance, education, loan installments, lifestyle).
3. **Ratios:** reads both sheets, compares against four benchmarks, returns Pass or Flag for each, and returns 0 instead of an error when inputs are empty.

## Sample household output
Net worth: assets IDR 1.33 bn minus debt 620 mn = **710 mn, flagged Good**. Monthly income IDR 31.0 mn from two salaries and investment interest; net cash flow +IDR 0.5 mn, a thin cushion.

| Ratio | Formula | Target | Sample | Flag |
| --- | --- | --- | --- | --- |
| Emergency fund | Cash / monthly expenses | 12x or more (married) | 3.8x | Flag |
| Debt service ratio | Installments / income | 30% or less | 30.6% | Flag |
| Debt to assets | Liabilities / assets | 50% or less | 46.6% | Pass |
| Savings ratio | Savings and investment / income | 10% or more | 12.9% | Pass |

## From red flag to next step
| Red flag | What it signals | Next action | Sample household |
| --- | --- | --- | --- |
| Emergency fund below 6x / 12x | One shock away from new debt | Build liquid savings first | Raise cash from 115 mn toward 366 mn |
| Debt service above 30% | Installments squeeze needs | Clear the costliest small debt | Paying off paylater brings it to 29% |
| Debt to assets above 50% | A fragile balance sheet | Avoid new financed purchases | Within limit, keep it there |
| Savings below 10% | Goals are unfunded | Automate saving | On track |
| Negative net worth | Debts exceed assets | Debt plan before new goals | +710 mn: healthy |

## Files
- [Full deck (PDF)](./personal-financial-health-check.pdf)
- [Excel template](./personal-financial-health-check.xlsx)

[Back to portfolio](../../README.md)
