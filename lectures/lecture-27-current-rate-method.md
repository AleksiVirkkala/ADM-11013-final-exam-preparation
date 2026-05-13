# Lecture 27 — Current Rate Method & Japanese Yen Exercise

> **Sources:** [`notes/ADM-11013 Lecture 27.md`](../../notes/ADM-11013%20Lecture%2027.md), [`transcripts/ADM-11013 Lecture 27.md`](../../transcripts/ADM-11013%20Lecture%2027.md), papers [`JAPANESE SUBSIDIARY OF US MULTINATIONAL CORP.md`](../../papers/JAPANESE%20SUBSIDIARY%20OF%20US%20MULTINATIONAL%20CORP.md) and [`JAPANESE SUBSIDIARY OF US MULTINATIONAL CORP 2.md`](../../papers/JAPANESE%20SUBSIDIARY%20OF%20US%20MULTINATIONAL%20CORP%202.md).

> **Exam relevance: VERY HIGH.** Same 21-pt exam question, this lecture covers the second method (current rate) and a second worked example (Japanese Yen).

---

## Key recap from Lecture 26

The choice of method is determined by the **functional currency**:
- Functional currency = home country (investor) currency → **Temporal method**
- Functional currency = host country (local) currency → **Current Rate method**

### Examples
- **Mexican peso functional** (e.g., Pepsi Mexico) → Current Rate method
- **USD functional** (e.g., a maquiladora exporting to US) → Temporal method
- **Hyperinflation country** → typically USD functional → Temporal method

> Teacher will tell you the functional currency on the exam. You determine the method.

---

## Current Rate Method explained

Used when the local currency IS the functional currency.

### Key differences from Temporal:

| Aspect | Temporal | Current Rate |
|---|---|---|
| Monetary items rate | Current | Current |
| Non-monetary items rate | Historical | **Current** ← key difference |
| Capital rate | Historical | Historical |
| Retained earnings | Plug | Historical avg |
| Where exchange adjustment appears | Income statement | **Balance sheet** ← key difference |
| Volatility | More volatile | Less volatile |

### Why less volatile?
- Under current rate, exchange effects are accumulated in a single balance-sheet line ("exchange adjustment") that combines ALL prior years' effects. The current year's effect is "hidden" in this cumulative number.
- Under temporal, exchange effects appear separately each year on the income statement — clearly visible.

### Why the difference in where exchange gain/loss is reported?
- The **income statement** closes out at year-end (resets each year)
- The **balance sheet** is continuous from day one
- Showing FX on income statement → see THIS YEAR's effect (Temporal)
- Showing FX on balance sheet → it accumulates with all prior years (Current Rate)

### The fundamental rule under Current Rate
- Almost everything → use the **current exchange rate**
- Only capital (stockholders' equity) → use historical
- Only retained earnings → use the historical average for retained earnings
- Income statement items → use average for the year (or specific-period rates if given)
- The "exchange adjustment" line plugs to balance the balance sheet

### Adam's question (and the teacher's answer)
**Adam:** "Why is depreciation in the income statement using the average for the year (1.52) under current rate, but capital uses the historical rate (1.8)?"

**Teacher:** Because:
- Depreciation accrues throughout the year, so use the average → consistent with current-rate philosophy
- Capital was contributed at one specific historical date → use that historical rate
- Capital is the one item where the philosophy differs because we want to preserve the original investor's contribution amount

This is also why depreciation in the **balance sheet** under current rate uses the current rate (it's a cumulative number on the balance sheet), but depreciation in the **income statement** uses the average for the year (it's a flow during the year).

---

## Worked example: Japanese Yen Subsidiary

This second exercise tests both methods. See [exercises/japanese-yen-balance.md](../exercises/japanese-yen-balance.md) for the complete filled-in version.

### Setup
- Japanese subsidiary of a US multinational
- Functional currency for the temporal example: **USD** → Temporal method
- For the current rate example, also worked through

### Exchange rates (Yen per 1 USD — so divide yen by rate to get USD)

| Rate | Description |
|---|---|
| 109 Y | Year-end (current rate) |
| 114 Y | Average for the year |
| 116 Y | Historical for cost of sales |
| 121 Y | Historical when inventory acquired |
| 150 Y | Historical when fixed assets acquired AND when capital was issued |
| 120 Y | Retained earnings (average accumulated, used for current rate method) |

### Result summary

**Temporal method:**
- Operational result = $273,034
- Retained earnings 1/1 = $50,000 (given)
- Retained earnings 31/12 = $188,531 (plug)
- ΔRE = $138,531
- **FX effect = $138,531 − $273,034 = ($134,503) LOSS**

**Current Rate method:**
- Operational result = $204,386
- Exchange adjustment (plug on balance sheet) = $290,916
- No FX line on income statement (N/A)

> Note the difference: under temporal, the FX result was a loss of $134,503 just for this year. Under current rate, the cumulative adjustment is $290,916 — but this includes ALL prior years' effects, not just this year.

---

## Key teaching points (memorize these)

### 1. The conversion direction matters
Yen exercise uses "Yen per 1 USD" → to get USD, **DIVIDE** local by exchange rate.
- 24,000,000 yen ÷ 109 = $220,183 (NOT × 109)

UK exercise uses "USD per 1 GBP" → to get USD, **MULTIPLY** local by exchange rate.
- 20,000 pounds × 1.49 = $29,800 (NOT ÷ 1.49)

> Teacher: "Don't make that mistake on the exam, or else we'll be unhappy."

### 2. Inventory direction can be tricky
Inventory is non-monetary, so under temporal use historical rate. Under current rate use the current rate. The book gives you specific rates for inventory acquisition.

### 3. Total result decomposition (always)
```
Operational result + FX gain/loss = Total result
```
Where total result = Δ retained earnings during the year.

### 4. "Operational + forex = total result" — write it down
Teacher said memorize this formula and write it on the exam paper:
$$\text{Operational results} + \text{FX gain/loss} = \text{Total results}$$

### 5. Be ready for either gain or loss
The Yen example produced a LOSS. The UK example produced a GAIN. Both are common.

> "You can have a loss, you can have a gain. The company will have to determine: do we stay in this country, or do we leave?"

### 6. Why this matters in real business
> "If foreigners are investing in foreign exchange, which they are, we have to figure out to understand it. We can't just say, oh, we're making a bunch of pesos, everything's good. Well, not so much necessarily. Right now the peso is strong, but other years I've lived here where the peso has collapsed and foreign companies thought about leaving immediately."

---

## What's the most likely exam format

Teacher said: "Read this, this explains everything... I'll give you an example just like on the test... I won't answer questions during the exercise. You can talk to your neighbors, no problem."

The exam will:
- Give you a balance sheet and income statement in foreign currency
- Tell you the functional currency
- Provide a list of exchange rates with descriptions
- Tell you the beginning-of-year retained earnings
- Ask you to fill in one method (probably temporal — teacher said it's more challenging)
- Compute and label the exchange rate gain/loss

Worth **21 points** out of 100 → about 1/5 of the entire exam.

---

## Conceptual quiz (be ready for these)

> Teacher's actual review questions from end of lecture:

**Q:** "What determines the method to use in consolidation of financial statements of multinationals?"
**A:** The functional currency.

**Q:** "If you have a subsidiary in Turkey of a European company, and the functional currency is the Turkish lira, what method do you use?"
**A:** Current rate method (functional = local).

**Q:** "If the functional currency is the euro (the home country currency for a Frankfurt-based company), what method?"
**A:** Temporal method (functional = home).

**Q:** "Why do we have a loss under temporal but a gain under current rate (or vice versa) for the same data?"
**A:** Because the methods report different things. Temporal reports just THIS YEAR's FX effect on the income statement. Current rate reports CUMULATIVE FX adjustment on the balance sheet (combining all prior years). They aren't directly comparable as gain vs loss.

---

## See also

- [Master consolidation theory guide](../reference/consolidation-theory.md) — comprehensive reference
- [Japanese Yen exercise](../exercises/japanese-yen-balance.md) — fully filled with both methods
- [UK Pounds exercise](../exercises/uk-pounds-balance.md) — the previous lecture's example
- [Lecture 28 — Inflationary country practice](lecture-28-inflationary-country.md) — exam-format practice
