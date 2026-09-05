# Morrisons LBO & Credit Analysis

A leveraged buyout model and credit covenant stress test built on Clayton, Dubilier & Rice's real 2021 acquisition of Wm Morrison Supermarkets plc.

## What's in this repo

- **Excel model** — Sources & Uses, 5-year operating model, debt schedule, credit metrics, and returns analysis (MOIC/IRR)
- **Python stress test** — flexes EBITDA down under Base / Moderate (-15%) / Severe (-30%) downturn scenarios and checks whether leverage and interest coverage covenants are breached each year
- **Chart** — visualises leverage and coverage ratios across all three scenarios against covenant thresholds

## Key finding

Even in the base case, entry leverage (~8.0x, matching Fitch's real reported figure) starts above a typical 6.5x covenant threshold and only normalises by Year 3. Under a severe downturn, leverage never recovers within the 5-year hold period — showing the deal had very little margin for error, consistent with Fitch's real assessment that this leverage was "incompatible" with an investment-grade rating.

## Tools used

Excel (financial modelling), Python (pandas, matplotlib)
![Covenant Stress Test Chart](stress_test_summary.csv)

