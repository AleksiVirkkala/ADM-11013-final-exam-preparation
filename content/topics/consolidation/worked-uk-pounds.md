---
title: "Worked Example: UK Pounds Subsidiary"
---

> Source: Lectures 26 & 27. UK subsidiary of US multinational. Result: small **\$1,310 GAIN** under Temporal method.

## Setup

- UK subsidiary, converting GBP → USD
- Functional currency for the Temporal version: **USD** → [[temporal-method|Temporal method]]
- Quote direction: "USD per 1 GBP" → **multiply** local by rate to get USD

## Exchange rates (USD per 1 GBP)

| Rate | Description |
|---|---|
| \$1.80 / 1 GBP | Historical when fixed assets acquired AND capital stock issued |
| \$1.49 | Current rate (year-end 31/12) |
| \$1.52 | Average rate for the year |
| \$1.51 | Historical rate when inventory acquired |
| \$1.515 | Historical average for cost of sales |
| \$1.6626 | Retained earnings (average accumulated rate, used in Current Rate method) |

## Balance Sheet — 31 December

| Account | UK Pounds | Temporal Rate | Temporal USD | Current Rate | Current Rate USD |
|---|---:|---:|---:|---:|---:|
| **ASSETS** | | | | | |
| Banks | 20,000 | 1.49 | 29,800 | 1.49 | 29,800 |
| Accounts Receivable | 40,000 | 1.49 | 59,600 | 1.49 | 59,600 |
| Inventory | 40,000 | 1.51 | 60,400 | 1.49 | 59,600 |
| Fixed Assets | 100,000 | 1.80 | 180,000 | 1.49 | 149,000 |
| Accum. Depreciation | (20,000) | 1.80 | (36,000) | 1.49 | (29,800) |
| **TOTAL** | **180,000** | | **293,800** | | **268,200** |
| **LIABILITIES** | | | | | |
| Accounts Payable | 30,000 | 1.49 | 44,700 | 1.49 | 44,700 |
| Long Term Debt | 44,000 | 1.49 | 65,560 | 1.49 | 65,560 |
| Stockholders' Equity | 60,000 | 1.80 | 108,000 | 1.80 | 108,000 |
| Retained Earnings | 46,000 | **(plug)** | 75,540 | 1.6626 | 76,480 |
| Exchange Adjustment | N/A | | **N/A** | **(plug)** | **(26,540)** |
| **TOTAL** | **180,000** | | **293,800** | | **268,200** |

## Income Statement

| Account | UK Pounds | Temporal Rate | Temporal USD | Current Rate | Current Rate USD |
|---|---:|---:|---:|---:|---:|
| Sales | 230,000 | 1.52 | 349,600 | 1.52 | 349,600 |
| Cost of sales | (110,000) | 1.515 | (166,650) | 1.52 | (167,200) |
| Depreciation | (10,000) | 1.80 | (18,000) | 1.52 | (15,200) |
| Other items | (80,000) | 1.52 | (121,600) | 1.52 | (121,600) |
| Taxes | (6,000) | 1.52 | (9,120) | 1.52 | (9,120) |
| **Operational result** | **24,000** | | **34,230** | | **36,480** |
| Exchange Gain/Loss | N/A | | **1,310 gain** | | **N/A** |
| **Net Income** | | | **35,540** | | **36,480** |

> **Given:** Retained earnings 1/1 = **\$40,000**

## Computing the exchange rate gain/loss (Temporal)

| Step | Amount |
|---|---:|
| Retained earnings 31/12 (plug from balance sheet) | \$75,540 |
| Retained earnings 1/1 (given) | \$40,000 |
| ΔRE = 75,540 − 40,000 | **\$35,540** |
| Operational result (income statement, before FX) | **\$34,230** |
| FX effect = ΔRE − Operational = 35,540 − 34,230 | **\$1,310 GAIN** ✓ |

Verify: Operational + FX = ΔRE → \$34,230 + \$1,310 = \$35,540 ✓

## Note on the Current Rate result

The Exchange Adjustment of **(\$26,540) loss** is the balance-sheet plug. It's NOT on the income statement (that's the [[temporal-method|Temporal]] approach). Under [[current-rate-method|Current Rate]], the adjustment is **cumulative** across all prior years, not just this year — so the numbers aren't directly comparable to the Temporal gain of \$1,310.

## What you'd write on the exam paper

```
Method: Temporal (functional currency = USD)

[fill in balance sheet and income statement as above]

Exchange rate gain/loss:
  RE 31/12 (plug)  = $75,540
  RE 1/1 (given)   = $40,000
  ΔRE              = $35,540
  Operational      = $34,230
  
  FX = ΔRE − Operational = 35,540 − 34,230 = $1,310 GAIN ✓
```

## See also

- [[exam-template|Exam template — 12-step approach]]
- [[temporal-method|Temporal method rules]]
- [[current-rate-method|Current Rate method rules]]
- [[worked-japanese-yen|Worked example: Japanese Yen]] — uses inverse direction (Yen per USD)
- [[worked-inflationary|Worked example: Inflationary country]] — likely exam format
