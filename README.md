# ADM-11013 Final Exam Preparation

Refined study material for the final exam. The raw notes, transcripts, and exercise papers live one level up (in `notes/`, `transcripts/`, `papers/`) and are intentionally **not** part of this repo — they are the source data, not the deliverable.

---

## Exam logistics (from Lecture 31)

| | |
|---|---|
| **Date** | May 19 |
| **Room** | 101 (verify on the day — teacher said "look on the board") |
| **Start time** | 1:00 PM (verify) |
| **Duration** | 2 hours 45 minutes |
| **Bring** | Calculator (required), 2 pens/pencils |
| **Format** | 17 multiple choice (2 pts each = 34 pts) + 7 long/essay questions (66 pts) |
| **Cumulative?** | **No** — only material from "two legal systems" onward |

### Excluded topics (will NOT be on exam)
- Balance of Payments
- T-MEC / USMCA / NAFTA
- Export plan / 8 stages of export flow
- 5 export documents (packing list, bill of lading, invoice, etc.)

These were tested on the partial exam.

### Point breakdown of the long questions
- **Consolidation of financial statements: 21 pts** (single biggest question)
- 6 other long questions ≈ 7-8 pts each
- Multiple choice from book chapters 2, 10, 11, 20
- Essays from class topics

---

## What's in this repo

```
.
├── README.md           ← this file
├── chapters/           ← refined book content, one file per chapter
├── lectures/           ← refined lecture notes 25-31
├── exercises/          ← canonicalized practice exercises
└── reference/          ← cross-cutting reference docs (e.g., torts)
```

---

## Topic-to-source map (use this to find anything)

### HIGHEST-PRIORITY topics (multiple "exam" mentions, big point values)

| Topic | Lecture | Chapter | Exercise/Reference |
|---|---|---|---|
| Consolidation of financial statements (Temporal vs Current Rate method) — **21 pts** | [L26](lectures/lecture-26-consolidation-temporal.md), [L27](lectures/lecture-27-current-rate-method.md), [L28](lectures/lecture-28-inflationary-country.md) | [Ch20](chapters/chapter-20-finance-mnc.md) | [UK Pounds exercise](exercises/uk-pounds-balance.md), [Japanese Yen](exercises/japanese-yen-balance.md), [Inflationary country](exercises/inflationary-country-balance.md), [Theory & method guide](reference/consolidation-theory.md) |
| International Fisher Effect (formula!) | [L29](lectures/lecture-29-ppp-fisher.md), [L30](lectures/lecture-30-mock-exam.md), [L31](lectures/lecture-31-final-review.md) | [Ch10](chapters/chapter-10-fx-market.md) | — |
| Purchasing Power Parity / Big Mac Index | [L29](lectures/lecture-29-ppp-fisher.md), [L30](lectures/lecture-30-mock-exam.md) | [Ch10](chapters/chapter-10-fx-market.md) | — |
| 4 tax-reduction mechanisms (transfer pricing, royalties, dividends, fronting loans) | [L25](lectures/lecture-25-transfer-pricing.md), [L31](lectures/lecture-31-final-review.md) | [Ch20](chapters/chapter-20-finance-mnc.md) | [Transfer pricing 2-country](exercises/transfer-pricing-scenarios.md), [Tax haven 3-country](exercises/transfer-pricing-scenarios.md) |
| Two legal systems (Common law vs Civil law) | [L31](lectures/lecture-31-final-review.md) | [Ch2](chapters/chapter-2-legal-systems.md) | [Tort summary](reference/torts.md) |
| Torts (definition, types, examples) | [L31](lectures/lecture-31-final-review.md) | [Ch2](chapters/chapter-2-legal-systems.md) | [Tort summary](reference/torts.md) |

### HIGH-PRIORITY topics (single explicit "must know" / "I'll probably put on exam")

| Topic | Source |
|---|---|
| Currency swap (with **2 different value dates** — teacher emphasized this phrase) | [Ch10](chapters/chapter-10-fx-market.md), [L31](lectures/lecture-31-final-review.md) |
| Lessard-Lorange model (which exchange rate for budget vs actual) | [Ch20](chapters/chapter-20-finance-mnc.md), [L31](lectures/lecture-31-final-review.md) |
| IMF vs World Bank (roles) | [Ch11](chapters/chapter-11-monetary-system.md), [L31](lectures/lecture-31-final-review.md) |
| Centralized depositories (global money management) | [Ch20](chapters/chapter-20-finance-mnc.md), [L31](lectures/lecture-31-final-review.md) |
| Transaction / Translation / Economic exposure (with examples) | [Ch10](chapters/chapter-10-fx-market.md), [L31](lectures/lecture-31-final-review.md) |
| Hedging | [Ch10](chapters/chapter-10-fx-market.md), [L31](lectures/lecture-31-final-review.md) |
| Currency board (must mention 100% reserves requirement) | [Ch11](chapters/chapter-11-monetary-system.md), [L31](lectures/lecture-31-final-review.md) |
| Floating vs fixed exchange rates (advantages/disadvantages) | [Ch11](chapters/chapter-11-monetary-system.md), [L31](lectures/lecture-31-final-review.md) |
| Intellectual property (patents, copyrights, trademarks) | [Ch2](chapters/chapter-2-legal-systems.md) |

### MEDIUM-PRIORITY topics (mentioned during chapter walkthrough)

- Gold standard history (when ceased: Bretton Woods 1973; gold convertibility ended 1971 by Nixon)
- Bretton Woods system
- Dirty float / managed float definition
- Capital budgeting (project vs parent cash flows, political/economic risk adjustment)
- Outsourcing/offshore production (FDI definitions)
- Law of one price (relationship to PPP)
- Foreign Corrupt Practices Act (FCPA)
- Multilateral netting (transaction cost reduction)

---

## Critical exam tips

1. **International Fisher Effect formula — BOOK HAS WRONG FORMULA** (Chapter 10, p.300). Book says S2 in denominator. The correct formula per the teacher (he's said this multiple times) is:

   $$\frac{S_1 - S_2}{S_1} \times 100 = i_D - i_N$$

   Use S₁ in the denominator. Do NOT trust the book on this one.

2. **Consolidation question** — When stating the exchange rate gain/loss, you **must explicitly write "gain" or "loss"**. Teacher will not give credit otherwise.

3. **Functional currency** — The teacher will tell you what the functional currency is. You must determine which method to use:
   - Functional currency = home country (investor) currency → **Temporal method**
   - Functional currency = host country (local) currency → **Current Rate method**

4. **Don't be superficial** in essay answers. Teacher said this repeatedly: shallow answers lose points. Write professional, in-depth responses.

5. **Numerical order** — Answer questions in numerical order. If you skip one, leave a gap so you can come back.

6. **Multiple choice** — Only ONE correct answer per question. Don't circle multiple.

---

## Study workflow recommendation

If you have limited time, in order:

1. **[Consolidation theory & method guide](reference/consolidation-theory.md)** — 21 pts on this one question alone
2. **[Chapter 10](chapters/chapter-10-fx-market.md) + [Lecture 29](lectures/lecture-29-ppp-fisher.md)** — Fisher effect formula + PPP + exposure types
3. **[Chapter 20](chapters/chapter-20-finance-mnc.md) + [Lecture 25](lectures/lecture-25-transfer-pricing.md) + [Lecture 31](lectures/lecture-31-final-review.md)** — Tax mechanisms, hedging, Lessard-Lorange
4. **[Chapter 11](chapters/chapter-11-monetary-system.md)** — IMF/WB, fixed vs floating, currency board
5. **[Chapter 2](chapters/chapter-2-legal-systems.md) + [Tort summary](reference/torts.md)** — Legal systems comparison, torts, IP

Practice exercises last (after reviewing the theory): work through [UK Pounds](exercises/uk-pounds-balance.md), [Japanese Yen](exercises/japanese-yen-balance.md), and [Inflationary country](exercises/inflationary-country-balance.md) under exam conditions with your calculator.
