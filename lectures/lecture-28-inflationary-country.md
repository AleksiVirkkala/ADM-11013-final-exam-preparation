# Lecture 28 — Practice Exercise: Inflationary Country (Exam-Format)

> **Sources:** Lecture 28 notes and transcript, paper: *SUBSIDIARY OF US MULTINATIONAL IN AN INFLATIONARY COUNTRY*.

> **Exam relevance: VERY HIGH.** Teacher: *"This is a practice that will be like we will have in the final exam."* This lecture's format is the most likely template for the actual 21-pt exam question.

---

## Setup

A US multinational with a subsidiary in an inflationary country (the local currency is depreciating fast).

**Functional currency: USD** (because the local currency can't be trusted in an inflationary environment) → use **Temporal method**.

> Teacher confirmed: "In an inflationary country, the functional currency is the home country currency. So what method do you use? Temporal method."

---

## Why functional currency = USD in this scenario

In financially unstable countries (high inflation, devaluing currency), the parent company's home currency becomes the functional reality:
- Pricing decisions are made in USD-equivalent terms
- People hoard USD-denominated assets
- Local currency is used only for transactions, not for long-term value storage

> Teacher's anecdote: When he worked at Pepsi Mexico in the 1980s during 150% annual hyperinflation, the functional currency of his division was USD: "Everybody was buying dollars immediately when they got paid. You'd go down to the money exchange with $5 and buy a washing machine."

Real-world examples: 1980s Mexico, present-day Venezuela, Argentina at various points.

---

## Exchange rates (Local currency per 1 USD)

| Rate | Description |
|---|---|
| 19.5 | Current rate (year-end 31/12) |
| 18.0 | Average for year AND date of acquisition of inventory |
| 12.0 | Date of acquisition of fixed assets |
| 9.0 | Date of issuance of stock |
| 17.0 | Cost of sales |

---

## The exercise (this is what an exam question looks like)

See [exercises/inflationary-country-balance.md](../exercises/inflationary-country-balance.md) for the fully-filled version.

### Balance sheet (Temporal method)

| Account | Local | Rate | USD |
|---|---:|---|---:|
| Banks (monetary) | 1,200,000 | 19.5 | 61,538 |
| Accounts Receivable (monetary) | 2,400,000 | 19.5 | 123,077 |
| Inventory (non-monetary) | 2,400,000 | 18 (acquisition) | 133,333 |
| Fixed Assets (non-monetary) | 3,000,000 | 12 (acquisition) | 250,000 |
| Depreciation | (600,000) | 12 (= fixed assets) | (50,000) |
| **TOTAL ASSETS** | 8,400,000 | | **517,948** |
| Accounts Payable (monetary) | 2,000,000 | 19.5 | 102,564 |
| Debt (monetary) | 4,000,000 | 19.5 | 205,128 |
| Stockholders' Equity | 2,000,000 | 9.0 (issuance) | 222,222 |
| Retained Earnings | 400,000 | (PLUG) | (11,966) |
| Exchange Adjustment | N/A | (N/A on temporal) | N/A |
| **TOTAL LIAB+EQUITY** | 8,400,000 | | **517,948** |

> Notice retained earnings is **negative** in USD ($-11,966) — the business has cumulative losses. That's fine; the plug works regardless of sign.

### Income statement (Temporal method)

| Account | Local | Rate | USD |
|---|---:|---|---:|
| Sales | 4,000,000 | 18 (avg year) | 222,222 |
| Cost of sales | (1,900,000) | 17 (historical) | (111,765) |
| Depreciation | (190,000) | 12 (= fixed assets) | (15,833) |
| Other expenses | (90,000) | 18 (avg year) | (5,000) |
| Taxes | (150,000) | 18 (avg year) | (8,333) |
| **Net (operational)** | 1,670,000 | | **81,291** |
| Exchange rate gain/loss | N/A | (compute) | **(43,257) LOSS** |

### Computing the FX gain/loss

```
Retained earnings 31/12 = (−$11,966)  (the plug from balance sheet)
Retained earnings 1/1 = (−$50,000)    (given)
ΔRE = −11,966 − (−50,000) = +$38,034

Operational result = $81,291
FX effect = ΔRE − Operational = $38,034 − $81,291 = (−$43,257) LOSS
```

> **The FX loss wiped out more than half of the operational profit.** A real-world signal that the company should consider hedging or exiting the country.

---

## Key teaching moments

### "Don't be ashamed if you don't understand"
Teacher repeatedly emphasized students should ask. The conceptual flow is:
1. The local subsidiary made 1,670,000 in local currency profit
2. That's only $81,291 USD operationally (because of conversions)
3. AND we lost $43,257 of that to FX effects
4. **Net useful gain: $38,034** in USD — a fraction of the apparent local profit

### Why sometimes equity has to be "plugged"
The retained earnings line will balance whatever is needed. Don't try to use an exchange rate. Just:
1. Compute total assets in USD
2. Compute everything else on the liability side EXCEPT retained earnings
3. The remainder = retained earnings (could be positive or negative)

### Negative retained earnings is normal in inflationary countries
Don't be confused if the business shows cumulative losses. Many businesses in unstable countries do.

### Re-emphasis: must label gain or loss
> Teacher: "I will ask you on the test: what is the foreign exchange gain or loss for this company? Make sure you use 'gain' or 'loss' explicitly."

---

## Why this exercise is the exam template

- Same structure as the actual exam
- Tests temporal method (more challenging than current rate)
- Includes the gain/loss decomposition (the part that earns most of the points)
- Has clear, simple exchange rate table

> Teacher said in the next lecture: "Class, you have done this successfully. We have a loss in foreign exchange effects. Remember that, you can have a loss, you can have a gain."

---

## Practice strategy for the exam

If you can do this exercise from a blank template (just the local currency numbers + exchange rate descriptions), you're ready for the 21-pt question.

Suggested timing: **45 minutes** for the consolidation question on the exam (it's worth 21% of the points; if total exam is 2h45m, that's about 35 minutes plus buffer).

---

## See also

- [Inflationary country exercise](../exercises/inflationary-country-balance.md) — the full filled exercise
- [Master consolidation theory guide](../reference/consolidation-theory.md) — comprehensive reference
- [Lecture 26](lecture-26-consolidation-temporal.md) — temporal method intro
- [Lecture 27](lecture-27-current-rate-method.md) — current rate method
