# Financial modelling toolkit: FV, PV, NPV, payback

**Result:** four everyday money decisions, each solved in Excel with one time-value-of-money model, and each ending in a clear go / no-go.

> Excel model, USD.

## The four decisions
| Case | Model | Decision rule | Result | Decision |
| --- | --- | --- | --- | --- |
| Melaney | Future value | Plan to the inflation-adjusted need | USD 3,116 a month at 60 | Set a savings target |
| Jhon | Present value | Implied return above inflation | 20.9% above 3% | Take the investment |
| Max | Net present value | NPV above 0 | +USD 2,572 | Buy the machine |
| Robert | Payback period | Payback below asset life | 4.67 years below 8 years | Buy the car |

## How each one works
**Future value: what Melaney's budget will cost when she retires.** FV = PV x (1 + i)^n. USD 2,000 a month today, 3% inflation, 15 years to retirement: the budget becomes USD 3,116 a month at 60. Projecting each of the 20 retirement years forward and summing them gives about USD 1.0 mn: the savings target her plan must hit.

**Present value: is Jhon's offer worth taking?** PV = FV / (1 + r)^n. USD 10,000 received in 10 years at 6% is worth USD 5,584 today. For the offer itself (pay USD 1,500 today for USD 10,000 in 10 years), Goal Seek solves the implied return: 20.9% a year, far above 3% inflation, so the money grows in real terms.

**Net present value: should Max buy the USD 12,000 machine?** Inflows of USD 16,000 nominal over five years, discounted at 3%, are worth USD 14,572 today. NPV = 14,572 - 12,000 = +USD 2,572, so the machine creates value.

**Payback: how fast does Robert's car pay for itself?** Payback is 4.67 years (4 + 1,000 / 1,500), about 4 years 8 months, well inside the 8-year life.

The same four models scale to real decisions: retirement targets, investment offers, capital spending and asset purchases.

## Files
- [Full deck (PDF)](./financial-modelling-toolkit.pdf)
- [Excel model](./financial-modelling-toolkit.xlsx)

[Back to portfolio](../../README.md)
