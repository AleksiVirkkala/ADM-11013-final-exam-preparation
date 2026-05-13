# Lecture 25 — Transfer Pricing Strategy & Tax Havens

> **Sources:** Lecture 25 notes and transcript, papers: *MNC Example of Transfer Price Strategy* and *Transfer Pricing Strategy in Multinational Corporations*.

> **⚠️ IMPORTANT:** Lecture 25 was held BEFORE the partial exam. Most of the transcript discusses partial-exam content (NAFTA, USMCA, export plan, 5 export documents, Incoterms, letters of credit) that is **NOT** on the final exam. This refined note **only includes the part that IS on the final exam** — transfer pricing and tax havens.

> **Exam relevance: VERY HIGH.** This is the foundation for the 4-mechanisms tax-reduction question. Teacher said directly: *"This will be a question of the final exam — what are the 4 mechanisms?"*

---

## Core concept: MNC tax-minimization strategy

Multinational companies (MNCs) try to **shift profits from high-tax countries to low-tax countries** to minimize their global tax bill. They do this in four main ways.

### Why this matters
- Mexico's corporate income tax: 30%
- Ireland's: 12.5%
- Cayman Islands, Bahamas: 0%
- Even small percent differences across billions of dollars = huge tax savings

### Tax havens (the destinations for shifted profits)

Countries with very low or zero corporate income tax. Common examples teacher cited:
- **Ireland** (12.5%) — major hub for tech companies
- **Bermuda, Bahamas, Cayman Islands, British Virgin Islands** (0%)
- **Channel Islands** (Jersey, Guernsey, Sark) — between England and France, near-zero tax
- **Panama, Belize, Hong Kong, Singapore, Switzerland, Luxembourg**
- **Netherlands** (25%, but considered "soft" tax haven for various structures)

> Teacher's anecdote: When he visited Bermuda (population ~65,000), he was struck by the number of bank and insurance company offices — all "shell corporations" / "phantom corporations" using Bermuda as a paper domicile.

---

## The 4 mechanisms (THE EXAM QUESTION)

> Teacher: "Be able to explain the 4 methods. I'll write a question on the exam: explain the four methods, fronting loan, all right? That's how it works."

### 1. Charging dividends
The high-tax-country subsidiary pays dividends to a parent or sister company in a low-tax country.

**Example:** Microsoft Mexico is "owned" by Microsoft Ireland. Microsoft Mexico pays dividends to Microsoft Ireland → income leaves Mexico (30% tax), arrives in Ireland (12.5% tax).

The artificiality: Microsoft Ireland exists primarily to be the legal owner of other Microsoft subsidiaries — it's a tax structure, not an operational reality.

### 2. Charging royalties on intellectual property (patents, brands, copyright)
Place the IP ownership in a low-tax-country subsidiary. Other subsidiaries pay royalties to use the IP.

**Example:** Microsoft Ireland holds the Microsoft patents. Microsoft Mexico must pay Microsoft Ireland for the right to use them. → expenses go up in Mexico (lowering Mexican taxable income), royalty income arrives in Ireland (taxed at 12.5%).

### 3. Transfer pricing
Manipulate the prices at which subsidiaries of the same parent buy/sell from each other.

- Charge HIGH prices on goods sold INTO high-tax countries (raises their costs, lowers their profit)
- Charge LOW prices on goods sold OUT of high-tax countries (lowers their revenue)
- Net effect: profit shifts to low-tax country

See the worked numerical examples in [exercises/transfer-pricing-scenarios.md](../exercises/transfer-pricing-scenarios.md).

### 4. Fronting loans (CRITICAL — needs the diagram)
A loan between two related subsidiaries, channeled **through an international bank**.

**Structure:**
```
   Tax Haven Subsidiary (Bermuda, 0% tax)
            │
            │  Deposits cash at bank
            │  Receives interest tax-free
            ▼
       International Bank (e.g., Barclays, London)
            │
            │  Lends to high-tax sub
            │  High-tax sub deducts interest (tax-deductible)
            ▼
   Operational Subsidiary (UK, ~50% tax)
```

**Why the bank in the middle?** To **disguise** the related-party nature of the loan. A direct loan from Bermuda → UK would attract tax authority scrutiny (it might be reclassified as a disguised dividend, losing the tax-deductible interest treatment). The bank provides cover.

**Example flow** (based on book p.603; teacher's whiteboard used simplified numbers):
- Tax haven sub (Bermuda) deposits $1M with international bank at **8%** interest
- Bank lends $1M to operating sub (e.g., UK, 50% tax) at **9%** interest
- UK sub pays $90,000 interest → tax-deductible at 50% → after-tax cost $45,000
- Bank keeps $10,000 spread (9% − 8%), pays $80,000 to Bermuda
- Bermuda receives $80,000 **tax-free**
- Net effect: $80,000 moved from high-tax UK to zero-tax Bermuda; UK's real cost was only $45,000 → $35,000 of "free" money moved out

> See [chapters/chapter-20-finance-mnc.md](../chapters/chapter-20-finance-mnc.md) section on fronting loans for the full detailed diagram and numerical example.

---

## Real-world examples teacher mentioned

### Apple and the "Double Irish, Dutch Sandwich"
- Apple Ireland (12.5% tax) → channels income to Apple Jersey (Channel Islands, 0% tax)
- Sub-Irish operation charges royalties and dividends to other Apple subs worldwide
- Result: Apple has accumulated $252B+ in cash held overseas, paying virtually no tax

### Other companies known for using these strategies
- Nike, Uber, Starbucks, Amazon, Microsoft, Google

### Uber example
When you use Uber in Mexico, the invoice shows an Amsterdam address. Uber channels Mexican (and non-US) profits through Netherlands (lower tax than Mexico).

---

## Ethics discussion (teacher wanted students to form an opinion)

The strategies are **technically legal** but morally questionable. Key points:
- Companies have a duty to shareholders to minimize taxes legally
- But governments and the public view aggressive tax avoidance as unethical
- Especially when companies operate in countries where they don't pay their fair share
- Mexico's tax authority (SAT/Hacienda) is increasingly auditing multinationals on these practices
- President Joe Biden proposed a global minimum tax to harmonize rates — proposal not approved
- The EU is unhappy with Ireland's tax structure but can't force change
- Mexico's marginal tax rate is high → Mexico WOULD benefit from global harmonization
- But politically difficult — countries (like Ireland) want to stay competitive

> **For the exam essay:** Be ready to discuss both sides honestly. Don't take a strong position without acknowledging the counterargument.

---

## What teacher emphasized about reasonableness

When using these strategies in practice, **discretion matters**. The 0% profit example in the worked exercise is "flagrant" — would attract immediate audit. Real companies shave 5-10% off their profits, not 100%. The IRS / SAT / European tax authorities apply an **arm's-length pricing standard** (Section 482 in US Internal Revenue Code) — transfer prices must be what unrelated firms would charge each other in the market.

---

## What's NOT on the final exam from this lecture

The first half of Lecture 25 (and most of the transcript) covered partial-exam topics:
- 5 documents in the export process (packing list, bill of lading, invoice, certificate of origin, pedimento)
- Incoterms (4 groups)
- 8 stages of an export operation
- Letters of credit
- T-MEC / NAFTA / USMCA

These are **excluded from the final exam**. Skip them when reviewing.

---

## See also

- [Chapter 20 — full detail on tax mechanisms](../chapters/chapter-20-finance-mnc.md)
- [Transfer pricing exercises](../exercises/transfer-pricing-scenarios.md) — worked numerical examples
- [Lecture 31 — final review](lecture-31-final-review.md) — teacher's recap of these mechanisms
