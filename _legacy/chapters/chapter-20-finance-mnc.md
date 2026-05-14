# Chapter 20 — Accounting and Finance in the International Business

> **Exam relevance: VERY HIGH.** This chapter underlies the consolidation question (21 pts), the 4-tax-mechanisms question, the Lessard-Lorange question, the hedging question, and the centralized depository question. Teacher: *"This is a chapter which I tend to like because my interests personally involved financial management of the multinational firm."*

## Topics in this chapter that the teacher flagged for the exam

| Topic | Teacher quote / signal |
|---|---|
| 4 mechanisms to minimize tax (transfer pricing, royalties, dividends, fronting loans) | "Be able to explain in great detail" |
| Fronting loans diagram (p. 603) | "I'll put it on the board the next class" — drew the diagram explicitly |
| Lessard-Lorange model (p. 589) | *"Need to know"* / "You should know that" |
| Centralized depositories (p. 397-398 in his version, ch20 in book) | *"Read or will go bad in the final exam"* |
| Transaction / Translation / Economic exposure | *"Be able to explain... provide examples"* (also covered in Ch10) |
| Capital budgeting (p. 522 in his version) | Mentioned in walkthrough |
| Advantages/disadvantages of transfer prices (p. 601-602) | Listed in review |
| Tax havens | "Use of tax havens... 4 methods" |

---

## 1. The Lessard-Lorange model (high exam priority)

**The problem it solves:** International budgets are usually denominated in the home (corporate) currency. If exchange rates move during the year, comparing actual results against budget gets distorted — the subsidiary's "performance" gets confused with FX fluctuations.

**The three exchange rates Lessard-Lorange identify:**

| Rate | What it is |
|---|---|
| **Initial rate (I)** | Spot exchange rate when the budget was *adopted* |
| **Projected rate (P)** | Forecast spot rate for end of budget period (= the **forward rate**, OR a company-internal forecast called the **internal forward rate**) |
| **Ending rate (E)** | Spot rate when budget vs. performance is being *compared* |

These create a 3×3 matrix (rate used to translate Budget × rate used to translate Actual). Lessard-Lorange rule out 4 of the 9 combinations as illogical.

**The recommendation: use combination PP** — Projected rate for both Budget AND Actual.

**Why PP?**
- Same rate used on both sides → exchange rate movements during the year don't distort the comparison
- Uses a forecast (forward rate or internal forward rate) → realistic and forward-looking
- Other "same rate on both sides" combos (II, EE) work too, but PP incorporates expected FX movements

**For the exam:** If asked which exchange rate to use when comparing budget to actual, the answer is the **projected (forward) rate**, applied to **both** budget and actual.

---

## 2. The 4 mechanisms to minimize tax liability (HIGH PRIORITY — explain in detail)

> Teacher said multiple times this WILL be on the exam. Be able to explain each one with an example.

All four exploit differences in tax rates between countries. **Tax havens** (Bermuda, Bahamas, Cayman Islands, Ireland, etc. — countries with very low or zero corporate income tax) are the destination for the moved profits.

### 2.1 Transfer pricing
The price at which goods/services are sold *between subsidiaries of the same firm*. By manipulating this internal price:
- Set HIGH transfer prices on goods sold INTO a high-tax country (raises that subsidiary's costs → lowers its taxable profit there)
- Set LOW transfer prices on goods sold OUT of a high-tax country (lowers revenue recognized there)
- Result: profit shifts from high-tax country to low-tax country

**Four gains from transfer pricing manipulation** (per book p.601):
1. Reduce tax liability (shift earnings high→low tax country)
2. Move funds out of a country with expected currency devaluation (FX risk reduction)
3. Move funds when dividend remittances are blocked
4. Reduce import duties when ad valorem tariffs apply (use low transfer prices)

**Disadvantages / problems:**
- Most governments dislike it; many have "arm's-length pricing" rules (e.g., U.S. IRS Section 482 — burden of proof on the company)
- Distorts internal performance measurement (subsidiary profitability stops reflecting management effort)
- Ethically dubious — "violates at least the spirit of the law"
- Increasing audit scrutiny worldwide

See [exercises/transfer-pricing-scenarios.md](../exercises/transfer-pricing-scenarios.md) for worked numerical examples.

### 2.2 Charging royalties (on intellectual property)
Royalties are payments for the use of patents, copyrights, trademarks, technology, brand names. By placing the IP ownership in a low-tax country subsidiary:
- The high-tax-country subsidiary pays royalties → tax-deductible expense there → lowers its taxable income
- The low-tax-country subsidiary receives royalty income → taxed at the low rate

Teacher's example: Microsoft Ireland owns the Microsoft brand/patents. Microsoft Mexico must pay royalties to Microsoft Ireland for using them. Income shifts from Mexico (30% corporate tax) to Ireland (12.5%).

**Tax advantage over dividends:** Royalties are typically tax-deductible locally (treated as an expense), so they reduce the foreign subsidiary's tax liability before it ever pays a dividend.

### 2.3 Dividend remittances
Most common method of moving funds. The subsidiary in the high-tax country pays dividends to a parent or sister subsidiary in a tax haven.

Teacher's example: Microsoft Mexico pays dividends to Microsoft Ireland (its "owner"). Income leaves Mexico, arrives in Ireland tax-favorably.

The artificiality: Microsoft Ireland is set up specifically as the legal owner of Microsoft Mexico, even though they're really one company.

**Note:** Dividends are paid AFTER local income tax. Royalties/fees are deducted BEFORE local tax. So royalties have a tax advantage over dividends when the host country tax rate is high.

### 2.4 Fronting loans (CRITICAL — teacher drew the diagram twice)

A loan between a parent and its subsidiary that is **channeled through a financial intermediary** (an international bank — usually London-based, e.g., Barclays, HSBC). The bank "fronts" for the parent.

**Structure (canonical exam answer):**

```
   Tax Haven Subsidiary (Bermuda, 0% tax)
            │
            │  Deposits $X at 8% interest
            │  (interest received tax-free)
            ▼
       London Bank (intermediary)
            │
            │  Lends $X at 9% interest
            │  (interest paid is tax-deductible in UK)
            ▼
   Foreign Operating Subsidiary (UK, ~50% tax)
```

**Why the bank in the middle?**
- Disguises the related-party nature of the loan
- Avoids alerting tax authorities (a direct loan would draw scrutiny)
- A direct intra-firm loan might be reclassified by the host government as a disguised dividend → losing the tax-deductible interest treatment
- Host governments are less willing to block payments to international banks (would damage country's credit reputation) than payments to a parent company

**The economics (worked example from book p.603):**
Parent deposits $1M in London bank → bank lends $1M to UK operating subsidiary at 9%.
- UK sub pays $90,000 interest → tax-deductible at 50% → after-tax cost only $45,000
- Bank keeps $10,000 spread, pays $80,000 to Bermuda
- Bermuda receives $80,000 tax-free
- Net effect: $80,000 moved from UK to Bermuda, while UK sub only really paid $45,000 → $35,000 of "free" money moved out of the high-tax country

**Two reasons firms use fronting loans:**
1. **Circumvent host-country restrictions** on remitting funds to a foreign parent (common in countries with high political risk / capital controls)
2. **Tax advantages** as shown above

---

## 3. Centralized depositories (Global Money Management)

> Teacher: *"Read or will go bad in the final exam"*

**The question:** Should each foreign subsidiary hold its own cash, or pool everything in one central location (e.g., London, New York, Tokyo)?

**Answer: pool centrally.** Three reasons (memorize):

1. **Higher interest rates on bigger deposits.** Pooling enables larger deposits, which earn higher money-market rates.
2. **Better investment expertise.** A central depository in a financial hub has access to more investment opportunities and skilled financial experts than any individual subsidiary would.
3. **Smaller required cash buffer.** Because cash needs of independent subsidiaries are statistically uncorrelated, the pooled standard deviation is *less than the sum* of the individual standard deviations. The firm can hold less precautionary cash overall, freeing the rest for higher-yielding (less liquid) investments.

**Worked example from book:** 3 subsidiaries (Korea, China, Japan) each hold day-to-day cash + 3 standard deviations of precautionary cash. Sum of individual requirements = $46M. If centralized in Tokyo, the combined precautionary buffer (variance-additive math: √(1² + 2² + 3²) million) drops to ~$3.74M, total requirement ~$39.2M — saves about **$6.8M** in cash that can be redeployed.

**Limits:** Government capital controls, transaction costs of cross-border money movement. Many firms compromise — central depository for precautionary balances, local cash for day-to-day needs.

---

## 4. Reducing transaction costs: Multilateral netting

When many subsidiaries trade with each other, the volume of cross-currency money flows generates large foreign-exchange commissions and transfer fees.

**Bilateral netting:** A owes B $6M, B owes A $4M → A pays B just $2M.

**Multilateral netting:** Extends to N subsidiaries via a payment matrix. The book example with 4 Asian subsidiaries reduces $43M of gross flows to just $5M of net flows, saving $380,000 (90%) in transaction costs.

---

## 5. Capital budgeting for international projects

Same theoretical framework as domestic capital budgeting (estimate cash flows, discount at cost of capital, accept if NPV > 0), but with three complications:

1. **Project cash flows ≠ Parent cash flows.** Earnings may be blocked from repatriation (host government restrictions, taxes, mandatory local reinvestment). Stockholders only value cash that actually reaches the parent.

2. **Political risk.** Likelihood of political change harming the business — extreme case: expropriation. Adjust by:
   - Increasing the discount rate (penalizes early cash flows heavily — controversial)
   - OR adjusting future cash flows downward (more popular in practice)

3. **Economic risk.** Mainly inflation → currency depreciation → falling value of local-currency cash flows when converted to home currency.

---

## 6. Moving money across borders (recap)

Four techniques (= the same 4 tax mechanisms above, viewed from a money-management lens):

| Technique | Tax treatment |
|---|---|
| **Dividend remittances** | Most common. Paid AFTER local income tax. Subject to dividend withholding tax. |
| **Royalty payments and fees** | Tax-deductible locally → reduces foreign sub's tax liability. |
| **Transfer prices** | Manipulable to shift profits. Subject to arm's-length scrutiny. |
| **Fronting loans** | Tax-deductible interest. Circumvents capital controls. |

**Unbundling** = using a *mix* of these techniques rather than relying on one — looks less suspicious to host governments and minimizes tax exposure across multiple regulatory regimes.

---

## 7. Tax burden management — key concepts

| Term | Definition |
|---|---|
| **Tax credit** | Reduces home-country tax by the amount paid to foreign government |
| **Tax treaty** | Bilateral agreement specifying which country taxes which kind of income |
| **Deferral principle** | Parent isn't taxed on foreign-source income until a dividend is actually received |
| **Tax haven** | Country with very low or zero corporate income tax (Bermuda, Bahamas, Cayman, Ireland 12.5%) |
| **Double taxation** | Income taxed by both host-country and home-country governments — mitigated by the three above |

---

## 8. Accounting standards & control systems (background)

- National accounting differences make cross-country financial comparisons difficult
- **IASB** (International Accounting Standards Board) is the main push for harmonization
- Annual budget is the main control instrument over foreign subsidiaries
- Most companies require all budgets/performance in the home (corporate) currency → why Lessard-Lorange matters

This section is unlikely to be heavily tested, but the IASB term and the role of the annual budget are background you should know.

---

## Cross-references

- **Lecture 25** — Transfer pricing strategy + 4 tax mechanisms in detail: [lectures/lecture-25-transfer-pricing.md](../lectures/lecture-25-transfer-pricing.md)
- **Lectures 26-28** — Apply Ch20 concepts via consolidation exercises
- **Lecture 31** — Teacher's review walkthrough of Chapter 20: [lectures/lecture-31-final-review.md](../lectures/lecture-31-final-review.md)
- **Consolidation theory** (the master guide for the 21-pt question): [reference/consolidation-theory.md](../reference/consolidation-theory.md)
- **Worked exercises**: [exercises/](../exercises/)

---

## Quick-fire exam Q&A self-test

- *What 4 mechanisms minimize multinational tax?* → Transfer pricing, royalties, dividends, fronting loans
- *What does Lessard-Lorange recommend?* → Projected (forward) exchange rate for both budget AND actual (combination PP)
- *Why pool cash in a central depository?* → 3 reasons: higher interest on big deposits, better investment expertise, smaller pooled cash buffer (variance math)
- *What's a fronting loan structure?* → Tax-haven sub deposits at international bank → bank lends to high-tax sub. Diagram on p.603.
- *What's the arm's-length price?* → The price unrelated parties would set in a market — IRS standard for transfer pricing legitimacy
- *Three complications in international capital budgeting?* → Project vs parent cash flows, political risk, economic risk
