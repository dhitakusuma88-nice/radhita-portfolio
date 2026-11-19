# Retirement investment comparison: which of two instruments can fund 25 years of retirement?

**Result:** Investment B is approved and Investment A is rejected, even though A has the higher return. Withdrawal timing beats headline return.

> Excel model, IDR. Client is 35 and wants her spending covered from age 60 to 85.

![A vs B](chart.png)

## The brief
- **Two horizons:** 25 years to grow the money (35 to 60), then 25 years to live on it (60 to 85).
- **Spending to protect:** IDR 12 mn a month today, rising with 3% annual inflation.
- **Investment A:** 8% a year; the whole balance is taken at 60.
- **Investment B:** 7% a year; half is taken at 60, the rest keeps earning.

## Step 1: inflation doubles spending by retirement
Future value, FV = PV x (1 + i)^n. Today's IDR 144 mn a year becomes **IDR 301.5 mn** a year at 60 (144 mn x 1.03^25). Held flat across 25 retirement years, the target is **IDR 7.54 bn**.

## Step 2: Investment A grows larger but pays too little each year
1. IDR 1 bn at 8% becomes IDR 6.85 bn by age 60.
2. Spread over retirement: 6.85 bn / 25 years = IDR 273.9 mn a year.
3. 273.9 mn is below 301.5 mn: a shortfall of **IDR 27.6 mn every year**.
4. **Decision: reject.** A misses the target in all 25 years.

## Step 3: half of Investment B funds the first nine years, the other half carries her to 85
1. IDR 1 bn at 7% becomes IDR 5.43 bn by age 60.
2. Withdraw 50% (IDR 2.71 bn): it pays IDR 301.5 mn a year for nine years, ending near zero.
3. The other half, left invested at 7%, grows to IDR 4.99 bn by year 10.
4. From there the balance earns 4% a year and IDR 301.5 mn is withdrawn each year. It declines slowly and **IDR 2.76 bn remains at age 85**.
5. **Decision: approve.** B meets the target in all 25 years.

## Verdict
| | Investment A | Investment B |
| --- | --- | --- |
| Return | 8% a year | 7% a year |
| Value at 60 | IDR 6.85 bn | IDR 5.43 bn |
| Yearly income vs 301.5 mn need | IDR 273.9 mn (short) | IDR 301.5 mn (met) |
| Balance at 85 | IDR 0 | IDR 2.76 bn |
| Decision | Reject | Approve |

## Assumptions to stress-test
- Inflation fixed at 3% for 50 years
- Returns fixed at 8%, 7% and 4%
- Spending held at the year-one level after 60
- A spends a fixed 1/25 of the pot; B's second half keeps earning

**Next step:** a sensitivity run on returns and inflation.

## Files
- [Full deck (PDF)](./retirement-investment-comparison.pdf)
- Excel model: upload to this folder if available

[Back to portfolio](../../README.md)
