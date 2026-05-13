# Lecture 26 — Consolidation of Financial Statements (Introduction & Temporal Method)

> **Sources:** [`notes/ADM-11013 Lecture 26.md`](../../notes/ADM-11013%20Lecture%2026.md), [`transcripts/ADM-11013 Lecture 26.md`](../../transcripts/ADM-11013%20Lecture%2026.md), papers [`grupo-penoles.md`](../../papers/grupo-penoles.md), [`Admon. Internacional Fin. Stmt. Consol (ENG).md`](../../papers/Admon.%20Internacional%20Fin.%20Stmt.%20Consol%20%28ENG%29.md), [`EXERCISE CONVERSION OF FINANCIAL STATEMENTS.md`](../../papers/EXERCISE%20CONVERSION%20OF%20FINANCIAL%20STATEMENTS.md).

> **Exam relevance: VERY HIGH.** Foundation for the 21-pt consolidation question on the final.

> **Key teacher quote:** "Final exam NOT cumulative. NO Balance of Payments. Today: how to read financial results of multinational company."

---

## The big picture

When a multinational has subsidiaries in many countries (using different currencies), it must consolidate all those results into the home/reporting currency to publish on its stock exchange. This is governed by **international accounting rules** used worldwide (Europe, Americas, Asia, Africa, Australia).

> **Why you should care (teacher):** "If you're an investor, you must understand how to convert results from another currency to your home currency. You can't just use today's exchange rate — there are rules."

---

## Real-world example: Grupo Peñoles

Mexican mining conglomerate (silver, gold, copper). Their annual report illustrates the rules in practice:
- **Functional currency** of each subsidiary: depends on the primary economic environment
- **Reporting currency** of Grupo Peñoles: Mexican peso (because they report to the Mexican stock exchange)
- For most subsidiaries, the **functional currency is USD** because their primary market (silver) is priced in USD globally

### Grupo Peñoles' translation methodology
- **Monetary AND non-monetary** assets/liabilities → translated at closing exchange rate
- **Income/cost/expense** items → translated at average rate of the period
- **Equity accounts** → translated at historical exchange rate (when capital was contributed)
- **Translation adjustments** → recognized as separate item in equity

> This methodology corresponds to the **Current Rate method** (which we'll cover in detail in Lecture 27).

---

## Two methods of consolidation

The choice of method is NOT the firm's preference — it's determined by the **functional currency**.

| Functional currency = | Method |
|---|---|
| Home (investor) country currency | **Temporal method** |
| Host (local) country currency | **Current Rate method** |

### What is the functional currency?
The currency of the primary economic environment in which the subsidiary operates.

**Examples:**
- Pepsi Mexico (sells soft drinks to Mexicans, pays Mexican salaries) → functional currency = **Mexican peso** → Current Rate method
- Maquiladora (assembly plant in Mexico that exports everything to USA, buys US inputs) → functional currency = **USD** → Temporal method
- A subsidiary in a hyper-inflationary country (Venezuela) → functional currency = **USD** (can't trust local currency)

### Auditor enforcement
The auditors will catch any "fudging" with the numbers. International rules apply to all publicly traded companies (stock exchanges insist on clean books). The CFO doesn't get to pick whichever method gives better-looking numbers.

---

## Monetary vs Non-monetary items (critical distinction)

| Type | Definition | Examples |
|---|---|---|
| **Monetary** | Highly liquid; cash equivalents; value doesn't fluctuate with market | Cash, bank accounts, accounts receivable, accounts payable, long-term debt |
| **Non-monetary** | Not liquid; value can change with market | Inventory, fixed assets (machinery, equipment, buildings), accumulated depreciation |

**Why it matters:** Under the temporal method, monetary and non-monetary items use DIFFERENT exchange rates. (Under current rate method, they use the same rate.)

---

## Worked example: UK Pounds Subsidiary (Temporal Method)

This is the canonical example used in lectures 26-27. See [exercises/uk-pounds-balance.md](../exercises/uk-pounds-balance.md) for the complete filled-in version.

### Setup
- Hypothetical UK subsidiary of a US multinational
- Functional currency: **USD** → use **Temporal method**
- Convert from GBP to USD

### Exchange rates (USD per 1 GBP)

| Rate | Description |
|---|---|
| $1.49 | Year-end (current rate) |
| $1.51 | Historical when inventory acquired |
| $1.515 | Historical for cost of sales |
| $1.52 | Average for the year |
| $1.80 | Historical when fixed assets acquired AND when capital stock issued |

### Balance sheet exchange rates (Temporal method):

| Account | UK£ | Rate | USD |
|---|---:|---|---:|
| Banks (monetary) | 20,000 | 1.49 (current) | 29,800 |
| Accounts Receivable (monetary) | 40,000 | 1.49 (current) | 59,600 |
| Inventory (non-monetary) | 40,000 | 1.51 (historical inv.) | 60,400 |
| Fixed Assets (non-monetary) | 100,000 | 1.80 (historical) | 180,000 |
| Accum. Depreciation | (20,000) | 1.80 (same as fixed) | (36,000) |
| **TOTAL ASSETS** | 180,000 | | **293,800** |
| Accounts Payable (monetary) | 30,000 | 1.49 (current) | 44,700 |
| Long Term Debt (monetary) | 44,000 | 1.49 (current) | 65,560 |
| Stockholders' Equity | 60,000 | 1.80 (historical IPO) | 108,000 |
| Retained Earnings | 46,000 | (PLUG) | 75,540 |
| Exchange Adjustment | N/A | (N/A on temporal) | N/A |
| **TOTAL LIAB+EQUITY** | 180,000 | | **293,800** |

> Retained earnings is a "plug" figure — calculate so the balance sheet balances. Don't try to use an exchange rate.

### Income statement exchange rates (Temporal method):

| Account | UK£ | Rate | USD |
|---|---:|---|---:|
| Sales | 230,000 | 1.52 (avg year) | 349,600 |
| Cost of sales | (110,000) | 1.515 (historical) | (166,650) |
| Depreciation | (10,000) | 1.80 (= fixed asset rate) | (18,000) |
| Other items | (80,000) | 1.52 (avg year) | (121,600) |
| Taxes | (6,000) | 1.52 (avg year) | (9,120) |
| **Net (operational)** | 24,000 | | **34,230** |
| **Exchange gain/loss** | N/A | (compute) | **+$1,310 GAIN** |
| **Net Income (total)** | | | **35,540** |

### Computing the FX gain/loss (the moment of truth)

> Teacher: "If you guys are wrong, it's just gonna be... the moment of truth."

```
Retained earnings 31/12 = $75,540 (the plug figure on balance sheet)
Retained earnings 1/1 = $40,000 (given)
ΔRE during the year = $35,540

Operational result (income statement) = $34,230
FX gain/loss = ΔRE − Operational = $35,540 − $34,230 = +$1,310 GAIN
```

> **Must label as "gain" or "loss"** on the exam, not just the number.

> **Verification check:** Operational + FX = Total → $34,230 + $1,310 = $35,540 ✓

---

## Why we separate operational vs FX effect

This is the conceptual point of the whole exercise:

> "The shareholders, the board of directors, will want to know: how much have we earned this year in operational results, and how much have we earned in foreign exchange speculation movements? This is not a speculative business. We're just hoping to learn the foreign exchange movement, so we might as well just play forward exchange."

Without this analysis, you'd see "$35,540 net income" and not know whether your foreign operation is actually viable. Maybe operations made $5,000 and FX made $30,540 — in which case the country might be a bad place to do business going forward.

---

## Key conceptual points

### 1. Why use historical exchange rate for fixed assets and capital?
Because these items don't fluctuate with the market in the same way as monetary items. Their value at acquisition reflects what the firm originally invested.

### 2. Why is depreciation same rate as fixed assets?
Because depreciation is the systematic recognition of the historical cost of the fixed asset over time. The cost basis was set at the historical rate, so depreciation must use the same rate. (In real life it gets complex with different depreciation rules per asset type, but the teacher simplified.)

### 3. Why is retained earnings a plug?
Retained earnings accumulates over the entire history of the business. There's no single "right" exchange rate to use. So we plug it, and the difference between the plug and what we would have computed becomes the FX gain/loss.

### 4. Why does the FX gain/loss go on the income statement (under temporal)?
So shareholders can see *just this year's* FX effect, separate from operations. This is why temporal method is "more volatile" — it surfaces the FX effect each year.

### 5. Why must you specify the direction of conversion correctly?
> Teacher: "If I give you 1,000,000 pesos and the exchange rate is 17.5 pesos per dollar, do you multiply or divide to get dollars? You DIVIDE. Don't make this mistake under exam pressure — you'll lose all 16 points."

- Rate quoted as "X local per 1 USD" → divide local by rate to get USD
- Rate quoted as "X USD per 1 local" → multiply local by rate to get USD

The UK example uses "USD per 1 GBP" so we **multiply**. The Yen example (Lecture 27) uses "Yen per 1 USD" so we **divide**.

---

## See also

- [Master consolidation theory guide](../reference/consolidation-theory.md) — comprehensive reference
- [UK Pounds exercise](../exercises/uk-pounds-balance.md) — fully filled with both methods
- [Lecture 27 — Current Rate method](lecture-27-current-rate-method.md) — extends this exercise
- [Lecture 28 — Inflationary country practice](lecture-28-inflationary-country.md) — exam-format practice
- [Chapter 20](../chapters/chapter-20-finance-mnc.md) — Lessard-Lorange context
