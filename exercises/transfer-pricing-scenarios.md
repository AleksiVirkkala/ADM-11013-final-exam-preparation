# Exercise: Transfer Pricing Scenarios

> **Sources:** Lecture 25 used two paper handouts: [`papers/Transfer Pricing Strategy in Multinational Corporations.md`](../../papers/Transfer%20Pricing%20Strategy%20in%20Multinational%20Corporations.md) (2-country scenario) and [`papers/MNC Example of Transfer Price Strategy.md`](../../papers/MNC%20Example%20of%20Transfer%20Price%20Strategy.md) (3-country tax haven). Both consolidated here.

---

## Scenario 1: Without vs With Transfer Pricing Strategy (2 countries)

### Setup
A multinational with subsidiaries in two countries:
- **Country A** — corporate income tax = **40%**
- **Country B** — corporate income tax = **50%** (the high-tax country)

Country A produces; Country B sells to the public. Country A sells everything to Country B.

### Without transfer price strategy

| | Country A | Country B |
|---|---:|---:|
| Sales | **$10,000** (all to Country B) | $12,000 (to public) |
| Cost of sales | $8,000 | **$10,000** (= Country A's sales) |
| Profit | $2,000 | $2,000 |
| Income tax (40%/50%) | $800 | $1,000 |
| **Net profit** | **$1,200** | **$1,000** |

→ Combined company-wide net profit: **$2,200**

### With transfer price strategy

The MNC artificially raises Country A's selling price to Country B from $10,000 to $12,000 (a "transfer price" between subsidiaries of the same parent — this is a paper transaction).

| | Country A | Country B |
|---|---:|---:|
| Sales | **$12,000** (raised) | $12,000 (to public, same) |
| Cost of sales | $8,000 (same) | **$12,000** (= Country A's higher sales price) |
| Profit | $4,000 | $0 |
| Income tax (40%/50%) | $1,600 | $0 |
| **Net profit** | **$2,400** | **$0** |

→ Combined company-wide net profit: **$2,400** (vs $2,200 before — **gain of $200, or +9%**)

### How it works
- High-tax Country B's profit shifts to lower-tax Country A
- Country B now shows zero profit → no Country B income tax owed
- The MNC's overall tax bill drops, even though the underlying business hasn't changed

### Why this is risky in practice
- The strategy is *flagrant* in this example (Country B suspiciously shows zero profit)
- This would attract tax authority audits
- "You have to be discreet about this"
- Real companies don't go this extreme — they shave a few percent off, not 100%, to look reasonable

---

## Scenario 2: Three-Country Tax Haven Strategy

A more sophisticated approach using a **pass-through tax haven** subsidiary.

### Setup
- **Country A** — production country (e.g., USA), 40% income tax
- **Country B** — **tax haven** (e.g., Bermuda), **0% income tax**, pass-through entity (no real customers)
- **Country C** — sales country (e.g., UK), 50% income tax

The product flows: A → B → C → public (in C). But Country B never touches the actual product — it's just an invoice shuffling exercise.

### Without transfer pricing strategy
(Same as Scenario 1 logic — direct A → C, paying the 40% and 50% income taxes on profit at each end)

### With transfer pricing strategy via tax haven

| | Country A (US) | Country B (Bermuda) | Country C (UK) |
|---|---:|---:|---:|
| Sales | **$8,000** (to Country B) | **$12,000** (to Country C) | $12,000 (to public) |
| Cost of sales | $8,000 | **$8,000** (from Country A) | **$12,000** (from Country B) |
| Profit | $0 | **$4,000** | $0 |
| Income tax (40%, 0%, 50%) | $0 | $0 | $0 |
| **Net profit** | **$0** | **$4,000** | **$0** |

→ Combined company-wide net profit: **$4,000**, paying **zero** income tax anywhere.

### How it works
- Country A sells low to Country B (no profit booked in high-tax US)
- Country B "buys" low and "sells" high to Country C → all the profit accumulates in Bermuda where tax is zero
- Country C's cost equals its selling price → no profit booked in high-tax UK
- All $4,000 of company-wide profit sits in tax-free Bermuda

### Real-world context: why the bank in the middle?

In actual practice, companies don't make Country B such an obvious shell — they use intermediary banks (see "fronting loans" in [chapters/chapter-20-finance-mnc.md](../chapters/chapter-20-finance-mnc.md)) to disguise the related-party nature of the transactions. The teacher's example is simplified for clarity.

### Real-world examples (from teacher)
- **Apple in Ireland** ("double Irish, Dutch sandwich"): Irish operations channeled to Jersey (Channel Islands, zero income tax) via royalties and dividends. Apple accumulated $252B+ in cash overseas via tax-haven operations.
- **Microsoft Mexico → Microsoft Ireland**: Royalties and dividends from Microsoft Mexico go to Microsoft Ireland (12.5% tax rate vs Mexico's 30%)
- **Uber in Amsterdam**: Mexican Uber invoices show an Amsterdam address — channeling profits to Netherlands (lower tax)
- **Companies using these strategies**: Apple, Nike, Uber, Starbucks, Amazon

---

## What to remember for the exam essay question

If asked **"What actions can a firm take to minimize its global tax liability?"** (Q10/Q19 on practice exam):

The four mechanisms are (memorize all four):
1. **Transfer pricing** — manipulate inter-subsidiary prices to shift profits to low-tax countries
2. **Charging royalties** — place IP in low-tax country, charge other subsidiaries royalties for use
3. **Charging dividends** — high-tax subsidiary pays dividends to low-tax owner subsidiary
4. **Fronting loans** — channel funds via international bank between tax-haven and high-tax subsidiaries

All four exploit **tax havens** (countries with very low/zero corporate income tax). See [chapters/chapter-20-finance-mnc.md](../chapters/chapter-20-finance-mnc.md) for fully detailed explanations of each mechanism with the fronting loan diagram.

If asked about **ethics**: be ready to discuss both sides. The strategies are technically legal but morally questionable. Teacher quote: "Companies are not in Mexico, there's any companies. It's not a charitable organization." Companies have a duty to shareholders to minimize taxes legally. But the public and governments view aggressive tax avoidance as unethical, especially when companies operate in countries where they don't pay fair share of taxes.

---

## Key tax rates to know (for exam context, not memorization)

| Country | Approximate marginal corporate income tax |
|---|---|
| Mexico | 30% |
| USA | 21% federal + state (varies; California can hit 34% combined) |
| Ireland | **12.5%** ← tax haven |
| Cayman Islands, Bahamas, Jersey, Bermuda | **0%** ← tax havens |
| Netherlands | 25% (often viewed as semi-tax-haven) |
| Hong Kong | 16.5% |
| France | 31% |
| Germany | 29.65% |

---

## See also

- [Chapter 20 — full detail on tax mechanisms and fronting loans](../chapters/chapter-20-finance-mnc.md)
- [Lecture 25 — class walkthrough](../lectures/lecture-25-transfer-pricing.md)
