# Exercise: Japanese Yen Subsidiary of US Multinational

> **Source:** Lecture 27. Original papers: *JAPANESE SUBSIDIARY OF US MULTINATIONAL CORP* (temporal only) and *JAPANESE SUBSIDIARY OF US MULTINATIONAL CORP 2* (both methods). This canonical version uses the corrected version-2 values.

**Scenario:** A Japanese subsidiary of a US multinational, converting from JPY to USD under both methods.

Functional currency for this exercise:
- **Temporal method:** Functional currency = USD
- **Current Rate method:** Functional currency = JPY

---

## Exchange rates (all expressed as **JPY per 1 USD** — note the inverse direction vs UK exercise)

| Rate | Description |
|---|---|
| 150 Y/USD | Historical rate when fixed assets acquired AND capital stock issued |
| 109 Y | Current rate (year-end 31/12) |
| 114 Y | Average rate during the year |
| 121 Y | Historical average when inventory was purchased |
| 116 Y | Historical average for cost of sales |
| 120 Y | Retained earnings (average accumulated rate) |

> **Conversion direction:** With "X yen per 1 USD," to convert yen → USD you **divide** by the rate (not multiply). E.g., 24,000,000 yen ÷ 109 = $220,183.

---

## Balance Sheet — 31 December, 200X

| Account | Yen | Temporal E/R | Temporal USD | Current Rate E/R | Current Rate USD |
|---|---:|---:|---:|---:|---:|
| **ASSETS** | | | | | |
| Banks/Cash | 24,000,000 | 109 | 220,183 | 109 | 220,183 |
| Accounts Receivable | 6,213,000 | 109 | 57,000 | 109 | 57,000 |
| Inventory | 27,250,000 | 121 | 225,207 | 109 | 250,000 |
| Fixed Assets | 237,000,000 | 150 | 1,580,000 | 109 | 2,174,312 |
| Accum. Depreciation | (47,400,000) | 150 | (316,000) | 109 | (434,862) |
| **TOTAL** | **247,063,000** | | **1,766,390** | | **2,266,633** |
| **LIABILITIES** | | | | | |
| Accounts Payable | 33,000,000 | 109 | 302,752 | 109 | 302,752 |
| Long Term Debt | 66,320,000 | 109 | 608,440 | 109 | 608,440 |
| Capital | 100,000,000 | 150 | 666,667 | 150 | 666,667 |
| Retained Earnings | 47,743,000 | (plug) | 188,531 | 120 | 397,858 |
| Exch. Rate Gain/Loss | N/A | | **N/A** | (plug) | **290,916** |
| **TOTAL** | **247,063,000** | | **1,766,390** | | **2,266,633** |

---

## Income Statement — Year 200X

| Account | Yen | Temporal E/R | Temporal USD | Current Rate E/R | Current Rate USD |
|---|---:|---:|---:|---:|---:|
| Sales | 230,000,000 | 114 | 2,017,544 | 114 | 2,017,544 |
| **Expenses:** | | | | | |
| Cost of Sales | (124,000,000) | 116 | (1,068,966) | 114 | (1,087,719) |
| Depreciation | (23,700,000) | 150 | (158,000) | 114 | (207,895) |
| Other Items | (59,000,000) | 114 | (517,544) | 114 | (517,544) |
| **Operating Result** | **23,300,000** | | **273,034** | | **204,386** |
| Exch. Rate Gain/Loss | N/A | | **(134,503) loss** | | **N/A** |
| **Net Income** | **23,300,000** | | **138,531** | | **204,386** |

> **NOTE:** Initial balance of Retained Earnings at the beginning of the year was **US$50,000** (given).

---

## Verification of Exchange Rate Gain/Loss (Temporal Method)

| Step | Amount |
|---|---:|
| Retained earnings 31/12 (plug from balance sheet) | $188,531 |
| Retained earnings 1/1 (given) | $50,000 |
| Change in retained earnings (Δ) | **$138,531** |
| Operational result (income statement, before FX) | **$273,034** |
| FX effect = ΔRE − Operational = 138,531 − 273,034 | **($134,503) LOSS** ✓ |

> **The company lost more than half of its operational profit to FX movements** — a real-world signal that the company should consider whether to stay in this currency.

---

## Lessons from this exercise (the teacher emphasized)

1. **The result was a LOSS.** Be ready to identify both gains AND losses on the exam.
2. **Operational + FX must equal Total** ($273,034 + (−$134,503) = $138,531 ✓).
3. **Notice the depreciation rate differs between methods:** Under Temporal, depreciation uses 150 (fixed asset rate); under Current Rate, depreciation uses 114 (income statement average). This is a common point of confusion in lecture 27.

---

## Notes on rounding / source discrepancies

The original papers had small rounding inconsistencies (e.g., 220,199 vs 220,183 for cash). The values shown here use the corrected/cleaner Version 2 of the paper. In the exam, **round to nearest whole dollar** — small differences (a few dollars) won't lose you points.

---

## See also

- [Master consolidation theory guide](../reference/consolidation-theory.md)
- [Lecture 27 walkthrough](../lectures/lecture-27-current-rate-method.md)
