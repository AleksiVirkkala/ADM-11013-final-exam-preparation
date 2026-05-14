---
title: "Worked Example: Inflationary Country (Most Likely Exam Format)"
---

> Source: Lecture 28. Subsidiary of US multinational in an inflationary country. Result: **(\$43,257) LOSS** under Temporal method.

> [!important] **Teacher (Lecture 28):** *"This is a practice that will be like we will have in the final exam."* If you only practice one exercise, do this one — it's the format closest to the actual exam.

## Setup

- US multinational with subsidiary in an inflationary country (currency depreciating fast)
- Functional currency: **USD** (because the local currency can't be trusted in hyperinflation) → [[temporal-method|Temporal method]]
- Quote direction: "Local currency per 1 USD" → **divide** local by rate

> See [[functional-currency#Why a high-inflation country implies USD functional|why hyperinflation → USD functional]].

## Exchange rates (Local currency per 1 USD)

| Rate | Description |
|---|---|
| 19.5 | Current rate (year-end 31/12) |
| 18.0 | Average for year AND date of acquisition of inventory |
| 17.0 | Cost of sales |
| 12.0 | Date of acquisition of fixed assets |
| 9.0 | Date of issuance of stock |

## Balance Sheet — 31/12

| Account | Local | Rate | USD |
|---|---:|---:|---:|
| **ASSETS** | | | |
| Banks | 1,200,000 | ÷19.5 | 61,538 |
| Accounts Receivable | 2,400,000 | ÷19.5 | 123,077 |
| Inventory | 2,400,000 | ÷18 | 133,333 |
| Fixed Assets | 3,000,000 | ÷12 | 250,000 |
| Depreciation | (600,000) | ÷12 | (50,000) |
| **TOTAL ASSETS** | **8,400,000** | | **517,948** |
| **LIABILITIES** | | | |
| Accounts Payable | 2,000,000 | ÷19.5 | 102,564 |
| Debt | 4,000,000 | ÷19.5 | 205,128 |
| Stockholders' Equity | 2,000,000 | ÷9.0 | 222,222 |
| Retained Earnings | 400,000 | **(plug)** | **(11,966)** |
| Exchange Adjustment | N/A | | N/A |
| **TOTAL L+E** | **8,400,000** | | **517,948** |

> **Notice:** Retained earnings is **negative** in USD terms (−\$11,966). The business has cumulative losses. The plug works regardless of sign.

## Income Statement

| Account | Local | Rate | USD |
|---|---:|---:|---:|
| Sales | 4,000,000 | ÷18 | 222,222 |
| Cost of sales | (1,900,000) | ÷17 | (111,765) |
| Depreciation | (190,000) | ÷12 | (15,833) |
| Other expenses | (90,000) | ÷18 | (5,000) |
| Taxes | (150,000) | ÷18 | (8,333) |
| **Operational result** | **1,670,000** | | **81,291** |
| Exchange rate gain/loss | N/A | | **(43,257) LOSS** |

> **Given:** Retained earnings 1/1 = **−\$50,000** (a cumulative loss; given negative)

## Computing the exchange rate gain/loss

| Step | Amount |
|---|---:|
| Retained earnings 31/12 (plug from balance sheet) | (−\$11,966) |
| Retained earnings 1/1 (given) | (−\$50,000) |
| ΔRE = (−11,966) − (−50,000) | **+\$38,034** |
| Operational result | **+\$81,291** |
| FX effect = ΔRE − Operational = 38,034 − 81,291 | **(−\$43,257) LOSS** ✓ |

Verify: \$81,291 + (−\$43,257) = \$38,034 ✓

> [!warning] **Sign trap:** When RE goes from −50,000 to −11,966, the change is **positive** \$38,034 (the loss got smaller). Not negative. Be careful with sign arithmetic when negatives are involved.

## What this tells us

The subsidiary made an apparent profit of **1,670,000 in local currency**. After conversion:

1. **\$81,291 in USD operational profit** (still positive, decent)
2. But **\$43,257 of FX loss** — more than half the operational profit wiped out
3. **Net useful gain = \$38,034 USD** — a fraction of the apparent local profit

Without this analysis, headquarters would think the subsidiary is doing 20× better than it actually is in USD terms. They might keep investing when they should be hedging or exiting.

## What you'd write on the exam paper

```
Method: Temporal (functional currency = USD; country is inflationary)

BALANCE SHEET — converted to USD
[table as above]

INCOME STATEMENT — converted to USD
[table as above]

OPERATIONAL RESULT = $81,291

EXCHANGE RATE GAIN/LOSS:
  RE 31/12 (plug)  = ($11,966)
  RE 1/1 (given)   = ($50,000)
  ΔRE              = $38,034
  Operational      = $81,291
  
  FX = ΔRE − Operational
     = 38,034 − 81,291
     = ($43,257) LOSS ✓

Verify: Op + FX = ΔRE → 81,291 + (−43,257) = $38,034 ✓
```

> **REMEMBER: Write "LOSS" explicitly.** Just "(\$43,257)" loses points.

## Why this format is closest to the exam

- Tests Temporal method (more challenging than Current Rate; teacher prefers)
- Has clear, simple exchange rate table
- Includes the gain/loss decomposition (the highest-point part)
- Includes a sign trap (negative RE 1/1) that the exam might replicate

## See also

- [[exam-template|Exam template — 12-step approach]]
- [[temporal-method|Temporal method rules]]
- [[exchange-gain-loss|FX gain/loss computation]]
- [[functional-currency|Why inflationary countries use USD as functional]]
