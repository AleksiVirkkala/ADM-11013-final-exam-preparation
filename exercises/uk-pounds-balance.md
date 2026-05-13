# Exercise: UK Pounds Subsidiary of US Multinational

> **Source:** Lectures 26 and 27. Original paper: [`papers/EXERCISE CONVERSION OF FINANCIAL STATEMENTS.md`](../../papers/EXERCISE%20CONVERSION%20OF%20FINANCIAL%20STATEMENTS.md). This is the **canonical fully-worked version** with both methods filled in.

**Scenario:** A hypothetical UK subsidiary of a US multinational. We will convert from GBP to USD under BOTH methods.

Functional currency for this exercise:
- **Temporal method:** Functional currency = USD (the home country currency)
- **Current Rate method:** Functional currency = GBP (the local UK currency)

---

## Exchange rates (all expressed as **USD per 1 GBP**)

| Rate | Description |
|---|---|
| $1.80 / 1 GBP | Historical rate when fixed assets acquired AND capital stock issued |
| $1.49 | Current rate (year-end 31/12) |
| $1.52 | Average rate for the year |
| $1.51 | Historical rate when inventory in stock was acquired |
| $1.515 | Historical average for cost of sales |
| $1.6626 | Retained earnings (average accumulated rate, used in Current Rate method) |

---

## Balance Sheet — 31 December, 202X

| Account | UK Pounds | Temporal E/R | Temporal USD | Current Rate E/R | Current Rate USD |
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
| Retained Earnings | 46,000 | (plug) | 75,540 | 1.6626 | 76,480 |
| Exchange Adjustment | N/A | | **N/A** | (plug) | **(26,540)** |
| **TOTAL** | **180,000** | | **293,800** | | **268,200** |

---

## Income Statement — Year 202X

| Account | UK Pounds | Temporal E/R | Temporal USD | Current Rate E/R | Current Rate USD |
|---|---:|---:|---:|---:|---:|
| Sales | 230,000 | 1.52 | 349,600 | 1.52 | 349,600 |
| **Expenses:** | | | | | |
| Cost of sales | (110,000) | 1.515 | (166,650) | 1.52 | (167,200) |
| Depreciation | (10,000) | 1.80 | (18,000) | 1.52 | (15,200) |
| Other items | (80,000) | 1.52 | (121,600) | 1.52 | (121,600) |
| Taxes | (6,000) | 1.52 | (9,120) | 1.52 | (9,120) |
| **Operating result** | **24,000** | | **34,230** | | **36,480** |
| Exchange Gain/Loss | N/A | | **1,310 gain** | | **N/A** |
| **Net Income** | **24,000** | | **35,540** | | **36,480** |

> **NOTE:** Initial balance of Retained Earnings as of 1/1/2X = **$40,000** (given).

---

## Verification of Exchange Rate Gain/Loss (Temporal Method)

| Step | Amount |
|---|---:|
| Retained earnings 31/12 (plug from balance sheet) | $75,540 |
| Retained earnings 1/1 (given) | $40,000 |
| Change in retained earnings (Δ) | **$35,540** |
| Operational result (income statement, before FX) | **$34,230** |
| FX effect = ΔRE − Operational = 35,540 − 34,230 | **$1,310 GAIN** ✓ |

> **Must write "gain" or "loss" on the exam.** Just "$1,310" loses points.

---

## Notes on the Current Rate Method values

The "exchange adjustment" of **($26,540) LOSS** is a plug figure to make the balance sheet balance. It's NOT shown on the income statement — only on the balance sheet (this is the key difference from temporal method).

Note that under current rate method, this adjustment is **cumulative** — it includes all prior years' FX effects combined with this year's. It's "hidden" in the balance sheet rather than highlighted on the income statement, which makes the current rate method less volatile.

---

## Practice exam answer template

If this exact exercise appears on the exam (same structure, different numbers), use this answer pattern:

1. **State which method:** "Functional currency is USD → temporal method"
2. **Fill in the balance sheet** row by row, using the rate chart in the [consolidation theory guide](../reference/consolidation-theory.md)
3. **Compute the assets total**
4. **Fill in liabilities** EXCEPT retained earnings
5. **Plug retained earnings** to make assets = liabilities + equity
6. **Fill in income statement**, get operational result
7. **Compute exchange gain/loss** = ΔRE − operational result
8. **Label as gain or loss** (this is mandatory)
9. **Double-check** that everything balances

---

## See also

- [Master consolidation theory guide](../reference/consolidation-theory.md)
- [Lecture 26 walkthrough](../lectures/lecture-26-consolidation-temporal.md)
- [Lecture 27 walkthrough](../lectures/lecture-27-current-rate-method.md)
