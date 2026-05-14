---
title: "Q7 — Wine Glass Hedging Strategy"
---

## Question

> You manufacture wine glasses. In mid-June, you receive an order for 10,000 glasses from Japan. **Payment of 400,000 Yen is due in mid-December.** You expect the Yen to **rise from its present rate of \$1=¥130 to \$1=¥100 by December.** You can **borrow Yen at 6 percent a year.** What should you do?

> [!info] **Strategic / open-ended question** — multiple valid answers, but you must show reasoning through the trade-offs. The teacher said: *"This question is for you to think through."*

## The setup, quantified

| | Today (mid-June) | December (forecast) |
|---|---:|---:|
| Yen/USD | ¥130 = \$1 | ¥100 = \$1 |
| ¥400,000 in USD | \$3,077 | **\$4,000** |
| 6-month yen borrowing cost | 6% / 2 = 3% | — |

If your forecast is right and you do nothing, you **gain ~\$923 (~30%)** by waiting (the yen appreciates so the same ¥400,000 buys more dollars).

## Three strategies to discuss

### Strategy 1 — Don't hedge (accept the upside)

If you genuinely expect the yen to rise, the unhedged position is the best bet:

- **Pro:** Capture the full \$4,000 if forecast is right (~30% gain over the \$3,077 "today" value)
- **Con:** If forecast is wrong and yen *falls* instead, you lose
- **Best for:** firms confident in their forecast and willing to bear the risk

### Strategy 2 — Borrow yen now, convert to USD now, repay yen loan with December payment

A textbook "money market hedge":

1. Borrow **¥400,000 / (1 + 0.03) ≈ ¥388,350** today at 6% annualized
2. Convert to USD at today's spot (130 yen/USD) → ~\$2,987
3. Invest the \$2,987 in dollar assets through December
4. Repay ¥400,000 yen loan with the December customer payment

- **Pro:** Locks in roughly today's USD value; no FX exposure
- **Con:** Loses the upside if yen rises as you expect
- **Best for:** firms that can't afford the variance and want certainty

### Strategy 3 — Forward contract (sell yen forward)

Sell ¥400,000 forward at the 6-month forward rate. Lock in the dollar value today; deliver the yen when the customer pays.

- **Pro:** Simple; locks in a known rate without taking on a loan
- **Con:** Same downside as Strategy 2 — gives up the upside
- **Best for:** simplest hedge if your bank offers forwards

## How to write this answer on the exam

The teacher wants you to **show the trade-off reasoning**, not pick a single "right" answer. Suggested template:

1. Quantify the situation (today value vs forecast value)
2. State the strategies (don't hedge, borrow yen, forward contract)
3. Discuss trade-offs (upside captured vs risk avoided)
4. **Take a position** with rationale ("Given my confidence in the yen-rise forecast, I would not hedge; alternatively, if risk-averse, the forward contract gives certainty.")

Any well-reasoned answer is acceptable. The grading is on the analytical structure, not on the choice.

## See also

- [[../topics/fx-exposure/hedging|Hedging]]
- [[../topics/fx-exposure/three-exposures#1. Transaction exposure|Transaction exposure]]
- [[../topics/fx-theories/spot-forward-swap|Spot, forward, currency swap]]
