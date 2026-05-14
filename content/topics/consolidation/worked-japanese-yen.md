---
title: "Worked Example: Japanese Yen Subsidiary"
---

> Source: Lecture 27. Japanese subsidiary of US multinational. Result: large **\$134,503 LOSS** under Temporal method.

## Setup

- Japanese subsidiary, converting JPY → USD
- Functional currency for the Temporal version: **USD** → [[temporal-method|Temporal method]]
- Quote direction: "Yen per 1 USD" → **divide** local by rate to get USD

> [!warning] **Conversion direction differs from UK exercise!** Here we **divide** because the quote is "yen per USD," not "USD per yen". E.g., 24,000,000 yen ÷ 109 = \$220,183 (NOT × 109).

## Exchange rates (Yen per 1 USD)

| Rate | Description |
|---|---|
| 150 Y / USD | Historical when fixed assets acquired AND capital stock issued |
| 109 Y | Current rate (year-end 31/12) |
| 114 Y | Average rate during the year |
| 121 Y | Historical when inventory was purchased |
| 116 Y | Historical average for cost of sales |
| 120 Y | Retained earnings (average accumulated, used in Current Rate) |

## Balance Sheet — 31 December

| Account | Yen | Temporal Rate | Temporal USD | Current Rate | Current Rate USD |
|---|---:|---:|---:|---:|---:|
| **ASSETS** | | | | | |
| Banks/Cash | 24,000,000 | ÷109 | 220,183 | ÷109 | 220,183 |
| Accounts Receivable | 6,213,000 | ÷109 | 57,000 | ÷109 | 57,000 |
| Inventory | 27,250,000 | ÷121 | 225,207 | ÷109 | 250,000 |
| Fixed Assets | 237,000,000 | ÷150 | 1,580,000 | ÷109 | 2,174,312 |
| Accum. Depreciation | (47,400,000) | ÷150 | (316,000) | ÷109 | (434,862) |
| **TOTAL** | **247,063,000** | | **1,766,390** | | **2,266,633** |
| **LIABILITIES** | | | | | |
| Accounts Payable | 33,000,000 | ÷109 | 302,752 | ÷109 | 302,752 |
| Long Term Debt | 66,320,000 | ÷109 | 608,440 | ÷109 | 608,440 |
| Capital | 100,000,000 | ÷150 | 666,667 | ÷150 | 666,667 |
| Retained Earnings | 47,743,000 | **(plug)** | 188,531 | ÷120 | 397,858 |
| Exchange Adjustment | N/A | | **N/A** | **(plug)** | **290,916** |
| **TOTAL** | **247,063,000** | | **1,766,390** | | **2,266,633** |

## Income Statement

| Account | Yen | Temporal Rate | Temporal USD | Current Rate | Current Rate USD |
|---|---:|---:|---:|---:|---:|
| Sales | 230,000,000 | ÷114 | 2,017,544 | ÷114 | 2,017,544 |
| Cost of Sales | (124,000,000) | ÷116 | (1,068,966) | ÷114 | (1,087,719) |
| Depreciation | (23,700,000) | ÷150 | (158,000) | ÷114 | (207,895) |
| Other Items | (59,000,000) | ÷114 | (517,544) | ÷114 | (517,544) |
| **Operational result** | **23,300,000** | | **273,034** | | **204,386** |
| Exchange Gain/Loss | N/A | | **(134,503) loss** | | **N/A** |
| **Net Income** | | | **138,531** | | **204,386** |

> **Given:** Retained earnings 1/1 = **\$50,000**

## Computing the exchange rate gain/loss (Temporal)

| Step | Amount |
|---|---:|
| Retained earnings 31/12 (plug from balance sheet) | \$188,531 |
| Retained earnings 1/1 (given) | \$50,000 |
| ΔRE = 188,531 − 50,000 | **\$138,531** |
| Operational result | **\$273,034** |
| FX = ΔRE − Operational = 138,531 − 273,034 | **(\$134,503) LOSS** ✓ |

Verify: \$273,034 + (−\$134,503) = \$138,531 ✓

## What this tells us about the business

The company lost **more than half** of its operational profit (\$273K) to FX movements (\$134K loss). In real-world terms:

- Underlying operations were profitable: 23.3M yen in profit
- But the yen strengthened significantly (150 → 109 yen/USD between historical and current)
- That strengthening means fixed assets and accum. depreciation translated at the historical rate become disadvantaged on the balance sheet → forces RE plug down → FX loss

> The teacher: *"You can have a loss, you can have a gain. The company will have to determine: do we stay in this country, or do we leave?"*

## Key things to notice

1. **Depreciation rate differs between methods**: Under Temporal, depreciation in the I/S uses 150 (the fixed asset rate). Under Current Rate, depreciation in the I/S uses 114 (the average). Common point of confusion.
2. **The Current Rate "Exchange Adjustment" of \$290,916** is cumulative (combines this year's FX effect with all prior years). Don't compare it directly to the Temporal loss of \$134,503.
3. **Conversion direction**: With "X yen per 1 USD," you **divide** local by rate (not multiply).

## See also

- [[exam-template|Exam template — 12-step approach]]
- [[temporal-method|Temporal method]] and [[current-rate-method|Current Rate method]]
- [[worked-uk-pounds|Worked example: UK Pounds]] — opposite direction (USD per GBP) and a gain
- [[worked-inflationary|Worked example: Inflationary country]] — likely exam format
