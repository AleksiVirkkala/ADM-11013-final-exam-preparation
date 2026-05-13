# Exercise: Subsidiary of US Multinational in an Inflationary Country

> **Source:** Lecture 28 (in-class practice exercise — represents the format you'll see on the exam). Original paper: [`papers/SUBSIDIARY OF US MULTINATIONAL IN AN INFLATIONARY COUNTR.md`](../../papers/SUBSIDIARY%20OF%20US%20MULTINATIONAL%20IN%20AN%20INFLATIONARY%20COUNTR.md).

**Scenario:** US multinational with a subsidiary in an inflationary country (the local currency is depreciating fast → the company essentially operates in USD-equivalents).

**Functional currency: USD** → use the **Temporal method**.

> Teacher in Lecture 28: "This is a practice that will be like we will have in the final exam." — This format is the most likely template for the actual exam question.

---

## Exchange rates (Local currency per 1 USD)

| Rate | Description |
|---|---|
| 19.5 | Current rate 31/12/XX |
| 18.0 | Average for year AND date of acquisition of inventory |
| 12.0 | Date of acquisition of fixed assets |
| 9.0 | Date of issuance of stock |
| 17.0 | Cost of sales |

---

## Balance Sheet — 31/12/XX

| Account | Local currency | Exchange rate | USD |
|---|---:|---:|---:|
| **ASSETS** | | | |
| Banks | 1,200,000 | 19.5 | 61,538 |
| Accounts Receivable | 2,400,000 | 19.5 | 123,077 |
| Inventory | 2,400,000 | 18 | 133,333 |
| Fixed Assets | 3,000,000 | 12 | 250,000 |
| Depreciation | (600,000) | 12 | (50,000) |
| **TOTAL** | **8,400,000** | | **517,948** |
| **LIABILITIES** | | | |
| Accounts Payable | 2,000,000 | 19.5 | 102,564 |
| Debt | 4,000,000 | 19.5 | 205,128 |
| Stockholders' Equity | 2,000,000 | 9.0 | 222,222 |
| Retained Earnings | 400,000 | (plug) | (11,966) |
| Exch. Rate Gain/Loss | N/A | | N/A |
| **TOTAL** | **8,400,000** | | **517,948** |

> Note: Retained earnings is **negative** in USD terms (−$11,966). This means the business has lost money on a cumulative basis since inception.

---

## Income Statement — Year XX

| Account | Local currency | Exchange rate | USD |
|---|---:|---:|---:|
| Sales | 4,000,000 | 18 | 222,222 |
| **Expenses** | | | |
| - Cost of sales | (1,900,000) | 17 | (111,765) |
| - Depreciation | (190,000) | 12 | (15,833) |
| - Other expenses | (90,000) | 18 | (5,000) |
| - Taxes | (150,000) | 18 | (8,333) |
| **Net Income (operational)** | **1,670,000** | | **81,291** |
| Exchange rate gain/loss | N/A | | (43,257) loss |

> **NOTE:** Initial balance of Retained Earnings (at 1/1/XX) was **−US$50,000** (a loss; given).

---

## Verification of Exchange Rate Gain/Loss

| Step | Amount |
|---|---:|
| Retained earnings 31/12 (plug from balance sheet) | (−$11,966) |
| Retained earnings 1/1 (given) | (−$50,000) |
| Change in retained earnings: −11,966 − (−50,000) = | **+$38,034** |
| Operational result (income statement) | **+$81,291** |
| FX effect = ΔRE − Operational = 38,034 − 81,291 | **(−$43,257) LOSS** ✓ |

> **The exchange rate effect wiped out more than half of the operational profit.** This is a common pattern in inflationary countries: profitable operations in local currency, but the home currency conversion erodes most of the gains. Be ready to interpret this for the exam essay portion.

---

## Lessons (likely exam essay points)

This exercise shows clearly *why* we go through the consolidation process:

1. The subsidiary made **1,670,000 in local currency profit** — sounds great in local terms
2. But that's only **$81,291 in USD operational terms**
3. AND the FX rate movement **lost $43,257** of that
4. **Net useful gain: $38,034** in USD — a fraction of the apparent local profit

> **Managerial implication:** Without this analysis, headquarters would think the subsidiary is doing 20× better than it actually is in USD. They might keep investing when they should be hedging or exiting.

---

## Why functional currency = USD here

Even though the subsidiary operates in a foreign country, the teacher specifies USD as functional currency because the country is inflationary. In real life:

> "In financially unstable country, functional currency would likely be USD (can't trust host country currency)."

Examples include 1980s Mexico (hyperinflation, Pepsi Mexico used USD as functional), present-day Venezuela, Argentina at various points.

---

## See also

- [Master consolidation theory guide](../reference/consolidation-theory.md)
- [Lecture 28 walkthrough](../lectures/lecture-28-inflationary-country.md)
- [UK Pounds exercise](uk-pounds-balance.md) — compare with stable-country example
- [Japanese Yen exercise](japanese-yen-balance.md) — another stable-country example
