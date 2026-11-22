# Reading CKPN and margin signals as an early warning for NPL

**Result:** the signals lit up one year before gross NPL jumped. In this bank, provisioning and margin moved first, and the headline NPL ratio moved later.

> Bank XYZ (name withheld), annual-report data 2021 to 2025. A pattern consistent with an early warning, not proof of cause: five annual data points only.

## The question
If loans and provisions rise but earnings do not follow, borrowers may be slipping from collectibility 1 to 2. Do provisioning and margin move before NPL does?

## Three signals tested
| Signal | What it means |
| --- | --- |
| A. Provisioning outruns lending | CKPN grows faster than gross loans: the bank expects more losses than growth alone explains |
| B. Margin keeps compressing | Net interest margin falls year after year while loans grow: interest earnings are not following the book |
| C. Net NPL rises first | Net NPL climbs while gross NPL still looks calm: early stress lands before the headline ratio moves |

Data: loans, CKPN, NPL gross and net, NIM, ROA, BOPO from the annual report. Absolute interest income was not in the dataset, so NIM stands in for it.

## What the signals said
| Year | Signals | Level | What happened |
| --- | --- | --- | --- |
| 2022 | 1 | Watch | Margin falls to 4.71%; NPL still improves |
| 2023 | 2 | Warning | Margin falls again (4.17%) and net NPL doubles (0.27% to 0.58%) while gross NPL stays flat |
| 2024 | 3 | High alert | CKPN +12.3% vs loans +2.3%; gross NPL rises from 1.76% to 2.54%; net NPL 1.06% |
| 2025 | 1 | Watch | Loans +20.3%, CKPN +12.2%; gross NPL eases to 2.19% (denominator effect); margin 3.72%, ROA 0.51% |

## So what: offer early warning before accounts reach collectibility 3
1. **Act now:** add behavioural scoring or an early-warning system on collectibility 2, before accounts migrate to 3.
2. **Track NPL by origination year,** not only the stock ratio, because 2025 growth may be diluting NPL.
3. **Watch collectibility 2 migration** and coverage on stage 2 (IFRS 9 / PSAK 71).
4. **Add interest income over average loans** (loan yield) and cost of risk against margin.

## Limits
Annual data only; NIM used as a proxy for interest income; the collectibility 2 share is not disclosed in the dataset. The Excel workbook behind this case study has the formulas and flags.

## Files
- [Full deck (PDF)](./ecl-early-warning-bank-xyz.pdf)
- [Excel model](./ecl-early-warning-bank-xyz.xlsx)

See also: [Credit risk analysis](../03-credit-risk-analysis/README.md).

[Back to portfolio](../../README.md)
