# Chapter 10 — The Foreign Exchange Market

> **Exam relevance: VERY HIGH.** This chapter contains the International Fisher Effect formula (a guaranteed exam question), Purchasing Power Parity, the Big Mac Index, currency swaps, hedging, and the three types of exchange rate exposure (transaction / translation / economic). Multiple multiple-choice questions and at least one essay question come from here.

## Topics flagged for the exam

| Topic | Teacher quote / signal |
|---|---|
| International Fisher Effect (formula) | *"Will appear on exam"* — formula question guaranteed |
| Purchasing Power Parity / Big Mac Index | *"Will appear on exam"* — over/undervaluation calculation |
| Law of one price ↔ PPP | "How is the law of one price related to PPP?" — explicit review question |
| Currency swap (with **2 different value dates**) | *"I'll probably put on the exam"* + *"Important thing to include: with 2 different value dates"* |
| Hedging | "Be able to explain"; teacher referenced Q18 from practice exam |
| Transaction / Translation / Economic exposure | *"Be able to explain... provide examples"* |
| Spot vs forward exchange rates | Foundational |

---

## 1. International Fisher Effect (IFE) — guaranteed exam question

### 🚨 BOOK ERROR — read this carefully 🚨

The book (p.300) prints the formula with **S₂ in the denominator**:

> ~~$\dfrac{S_1 - S_2}{S_2} \times 100 = i_\$ - i_¥$~~ ← **This is wrong in the book**

The teacher said multiple times during Lectures 29, 30, 31 that this is a typo and to **cross it out and correct it**. The correct formula is:

$$\boxed{\dfrac{S_1 - S_2}{S_1} \times 100 = i_D - i_N}$$

Where:
- $S_1$ = spot exchange rate today
- $S_2$ = futures market exchange rate one year from today (= projected spot rate in 1 year)
- $i_D$ = nominal interest rate in the **denominator** country
- $i_N$ = nominal interest rate in the **numerator** country

**Why S₁ in the denominator?** Because we measure percent change relative to *today's* value, not relative to next year's projected value. Universal convention.

**Whether to multiply by 100:** Either way is fine — just stay consistent. Decimal form (0.07) is equivalent to percentage form (7%). Teacher prefers decimal but accepts both.

### How to identify numerator vs denominator

If we express an exchange rate as **X currency per 1 Y currency**, then:
- **X = numerator country** (the one with the bigger number)
- **Y = denominator country** (the one with value 1)

Example: 17.5 pesos per 1 USD → pesos = numerator (Mexico), USD = denominator (USA).

**Convention:** Markets quote stronger currency in the denominator (because numbers are simpler). USD per 1 EUR (~$1.10), USD per 1 GBP (~$1.50), but pesos per 1 USD (~17.5), yen per 1 USD (~109).

### What IFE actually says (the "big picture")

> The change in spot exchange rate equals (in opposite direction) the difference in nominal interest rates between two countries.

Country with **higher interest rate** → its currency expected to **depreciate**. Why? Because high interest rates reflect expected high inflation, and PPP says high-inflation currencies depreciate.

### Domestic Fisher Effect (don't confuse with IFE)

> **Fisher Effect (domestic):** Nominal interest rate ≈ real interest rate + expected inflation.

If real interest rate is 2% and expected inflation is 5%, the nominal rate should be ~7%. Named after Irving Fisher.

- The **domestic** Fisher Effect links interest rates to inflation *within* a country
- The **international** Fisher Effect links interest rate *differences between countries* to exchange rate *changes*
- The IFE builds on the domestic Fisher Effect + PPP

### Worked example types you'll see on the exam

The teacher will give you **3 of the 4 variables** and ask for the 4th. The 4 variables are: $S_1$, $S_2$, $i_D$, $i_N$.

**Type 1: Solve for $S_2$ (forecast rate)**

Given: Peru's interest rate $i_N$ = 4.5%, US interest rate $i_D$ = 2%, today's spot $S_1$ = 3.42 soles/USD.

$$\dfrac{3.42 - S_2}{3.42} = 0.02 - 0.045 = -0.025$$

$$3.42 - S_2 = -0.025 \times 3.42 = -0.0855$$

$$S_2 = 3.42 + 0.0855 = 3.5055 \text{ soles/USD}$$

**Interpretation:** Peruvian sol expected to weaken slightly against the dollar (need more soles per dollar in 1 year). Why? Because Peru's interest rate is higher → more expected inflation → currency should depreciate.

**Type 2: Solve for $i_D$ or $i_N$ (interest rate)**

Given: $S_1$ = 12.5 CHP/ARP (Chilean pesos per Argentine peso), $S_2$ = 11.07 CHP/ARP, $i_N$ (Chile, numerator) = 7%. Find $i_D$ (Argentina).

$$\dfrac{12.5 - 11.07}{12.5} = i_D - 0.07$$

$$0.1144 = i_D - 0.07$$

$$i_D = 0.1844 = 18.44\%$$

**Interpretation:** Argentine interest rate is higher because Argentine peso is expected to depreciate against Chilean peso (i.e., 1 Argentine peso buys *fewer* Chilean pesos in 1 year — 11.07 vs 12.5). Higher inflation expected in Argentina → higher rates needed.

**Type 3: Solve for $S_1$ (today's spot rate)**

Less common but possible. Just rearrange algebraically.

### Shortcut formula (some students prefer this form)

You can rearrange to: $S_2 = S_1 \cdot (1 - i_D + i_N)$

Quick check from Lecture 29 example: $S_2 = 3.42 \times (1 - 0.02 + 0.045) = 3.42 \times 1.025 = 3.5055$ ✓

For the second example (1200 won/USD, $i_D$=7%, $i_N$=4%): $S_2 = 1200 \times (1 - 0.07 + 0.04) = 1200 \times 0.97 = 1164$ won/USD ✓

---

## 2. Purchasing Power Parity (PPP) and the Big Mac Index

### Law of one price (the prerequisite)

> In efficient markets free of transport costs and trade barriers, identical products sold in different countries must sell for the same price when expressed in a common currency.

If a jacket costs $80 in NYC and £30 in London with exchange rate £1 = $2, the jacket would cost only £40 in NYC dollars vs the £30 London price — arbitrage profit. Trading equalizes prices.

### PPP theory

> Given relatively efficient markets, a "basket of goods" should cost roughly the same in each country once converted at the exchange rate.

$$E_{\$/¥} = \dfrac{P_\$}{P_¥}$$

If the same basket costs $200 in the US and ¥20,000 in Japan, the predicted PPP exchange rate is $1 = ¥100.

### Big Mac Index (The Economist's PPP test)

The Economist uses the price of a Big Mac as a proxy for the basket of goods (Big Macs are made the same way in ~120 countries).

**Calculation pattern (this comes up on the exam):**

1. **Theoretical exchange rate** = (price in country A's local currency) ÷ (price in country B's local currency)
2. Compare with **actual market exchange rate**
3. **Ratio** = theoretical ÷ actual
4. If ratio > 1: numerator currency is **overvalued**; if ratio < 1: numerator currency is **undervalued**
5. The percentage over/under = how far the ratio is from 1.0

**Worked example (Norway, from Lecture 29):**

- Big Mac in Norway: 93 NOK
- Big Mac in NYC: $7.59 USD
- Actual exchange rate: 10.16 NOK/USD

Theoretical rate = 93 / 7.59 = 12.25 NOK/USD
Ratio = theoretical / actual = 12.25 / 10.16 = 1.21

So at theoretical rates, you'd need 12.25 NOK to get $1, but in reality you only need 10.16 NOK — **the krona is overvalued by 21%**.

**Worked example (Mexico, from Lecture 30):**

- Big Mac in Mexico: 67 pesos (older data; was 95 in newer)
- Big Mac in NYC: $5.90
- Actual exchange rate: 19.5 pesos/USD

Theoretical = 67 / 5.90 = 11.36 pesos/USD
Ratio = 11.36 / 19.5 = 0.58

The peso is **undervalued by (1 - 0.58) = 42%**.

### Why PPP often fails in practice

- Transport costs and tariffs (violate the law-of-one-price assumption)
- Government intervention in FX markets
- Multinational firms with market power can price-discriminate
- Investor psychology and **bandwagon effects** (short-term) — see definition below
- **PPP works much better long-run than short-run**

### Bandwagon effect (book key term — possible MC)

> When traders see a currency depreciating, they assume it will continue, and rush to sell it — which *causes* further depreciation. This can push exchange rates **away from fundamentals** for extended periods. The reverse happens with appreciating currencies.

This is a key argument *against* floating exchange rates: speculation can be destabilizing. It's also why PPP fails in the short run — traders aren't looking at relative prices; they're following the crowd.

### Inflation, money supply, and PPP

- High **money supply growth** → high **inflation** → currency **depreciates** (PPP prediction)
- The Bolivia hyperinflation case study in the chapter (1984-85): money supply +17,433%, prices +22,908%, peso depreciation -24,662% — all moved together as PPP predicts
- For the exam: be able to articulate "money supply → inflation → depreciation" as a causal chain

---

## 3. Spot vs Forward exchange rates, and Currency Swaps

| Concept | Definition |
|---|---|
| **Spot exchange rate** | Rate for "on-the-spot" currency conversion (today) |
| **Forward exchange rate** | Rate for currency conversion at a *future* date — agreed today, executed later (typically 30/90/180 days) |
| **Currency swap** | Simultaneous purchase AND sale of foreign exchange — for **two different value dates** |

> **EXAM-CRITICAL:** When defining currency swap, the teacher said the phrase **"with 2 different value dates"** must appear. This is the discriminating phrase he listens for.

### Forward premium vs discount

If the forward rate gives you *more* foreign currency per dollar than the spot rate, the dollar is at a **forward premium** vs that currency.
If it gives you *less*, the dollar is at a **forward discount**.

### Currency swap example (book p.292 region)

Apple has $1M in dollars today and needs ¥120M to pay a Japanese supplier today; in 90 days it will receive ¥120M from Japanese sales and want dollars back. Apple does a swap: spot trade $1M → ¥120M today, AND a 90-day forward trade ¥120M → $X dollars (locked in at the 90-day forward rate). Two transactions, two value dates, one combined contract.

**Two-thirds of all FX transactions are forward (mostly currency swaps); one-third are spot.**

### Why use them: hedging foreign exchange risk

A US importer ordered Japanese cameras today; payment in 30 days at ¥200,000 each, current rate $1=¥120, so $1,667 each. If the yen rises to $1=¥110 by then, each camera costs $1,818 — a $151 loss per unit. To hedge, the importer enters a 30-day forward contract NOW to buy yen at a locked rate. No more uncertainty.

---

## 4. Hedging (foreign exchange risk protection)

> Teacher: "Be able to explain in great detail" — Q18 on the practice exam

**Definition:** Hedging is protection against foreign exchange risk by buying futures (forward contracts, currency swaps, options) in foreign currencies.

**Why "hedge"?** Etymology: a hedgerow in medieval Europe was a row of bushes that protected your property line. In finance, a hedge is anything that protects against loss.

**Hedge fund:** Different concept — invests in high-risk securities expecting higher-than-market returns; the "hedge" refers to hedging against losses through portfolio diversification, not against FX risk specifically.

**Techniques to hedge transaction & translation exposure:**
1. **Forward exchange contracts** — lock in tomorrow's price today
2. **Currency swaps** — combine spot and forward
3. **Lead strategy** — collect receivables EARLY when foreign currency expected to depreciate; pay payables EARLY when it's expected to appreciate
4. **Lag strategy** — opposite: delay collection if currency expected to appreciate; delay payment if currency expected to depreciate

> Memory aid: **L**ead = act early to **L**ock-in good rate; **L**ag = wait when currency moves in your favor.

---

## 5. The three types of foreign exchange exposure (HIGH PRIORITY — examples required)

> Teacher: "Understand all three. Be able to provide examples." — Multiple times

### Transaction exposure
> The extent to which the **income from individual transactions** is affected by FX changes.

Includes obligations to buy/sell at previously agreed prices, and FX-denominated borrowing/lending.

**Example (book):** 2004, US airline orders 10 Airbus A330s at €120M each (€1.2B total), delivery 2008. Spot rate at signing: $1 = €1.10, so projected cost $1.09B. By 2008 dollar weakened to $1 = €0.80 → actual cost $1.5B. Transaction exposure = $0.41B loss.

### Translation exposure
> The impact of FX changes on the **reported financial statements** (consolidation).

These are accounting / "paper" gains and losses — unrealized — but they affect the apparent leverage and equity of the parent.

**Example:** US firm has Mexican subsidiary. Peso depreciates significantly → dollar value of the Mexican equity drops → consolidated balance sheet equity drops → debt ratio rises → cost of borrowing rises. No actual cash flow has happened, but the firm's apparent financial health deteriorates.

> This is exactly the "exchange adjustment" line in the consolidation exercises (lectures 26-28). See [reference/consolidation-theory.md](../reference/consolidation-theory.md).

### Economic exposure
> The extent to which **future earning power** is affected by FX changes — long-run competitive position.

**Example:** US dollar rises sharply against major currencies in the 1990s → US exporters become uncompetitive in world markets → export volumes and market share fall. This isn't about a single transaction; it's about the firm's long-run pricing power.

### Reducing each exposure type

| Exposure | Tactic |
|---|---|
| Transaction | Forward contracts, swaps, leading/lagging |
| Translation | Forward contracts, swaps, leading/lagging |
| Economic | **Strategic** — disperse production globally so no single currency has too much leverage on results (e.g., Toyota plants in many countries; Stanley Black & Decker's flexible-sourcing model) |

---

## 6. Currency convertibility

| Type | Meaning |
|---|---|
| **Freely convertible** | Both residents and non-residents can convert into any foreign currency without limit |
| **Externally convertible** | Only non-residents can; residents are restricted (limits on taking money out) |
| **Nonconvertible** | Neither residents nor non-residents can convert (e.g., old USSR) |

**Why governments restrict convertibility:** to preserve foreign exchange reserves and prevent **capital flight** (mass exodus when the local currency is depreciating fast or economy is shaky).

**Countertrade** = barter-like agreements when nonconvertibility makes normal payment impossible. Used to be widespread; now <5% of world trade.

---

## 7. Exchange rate forecasting

Two schools of thought:

| School | Belief |
|---|---|
| **Efficient market** | Forward rates are the best possible predictor of future spot rates → don't waste money on forecasting services |
| **Inefficient market** | Markets miss things; forecasting services can do better than forward rates |

Two methods used by inefficient-market believers:
- **Fundamental analysis** — uses money supply, inflation, interest rates, balance-of-payments to forecast
- **Technical analysis** — uses price/volume trends; no economic theory; "compared by many economists to fortune-telling"

---

## 8. Carry trade

A speculation strategy: **borrow** in a low-interest-rate currency, **invest** in a high-interest-rate currency, profit from the rate differential. Risk: the high-rate currency might depreciate (canceling the gain — exactly what IFE predicts in the long run).

---

## Cross-references

- **Lecture 29** — Detailed PPP and Fisher Effect walkthrough with worked examples: [lectures/lecture-29-ppp-fisher.md](../lectures/lecture-29-ppp-fisher.md)
- **Lecture 30** — Mock exam practice including Big Mac and IFE problems: [lectures/lecture-30-mock-exam.md](../lectures/lecture-30-mock-exam.md)
- **Lecture 31** — Final review touched on currency swap definition emphasis: [lectures/lecture-31-final-review.md](../lectures/lecture-31-final-review.md)
- **Chapter 20** — Where these concepts are applied in MNC financial management: [chapters/chapter-20-finance-mnc.md](chapter-20-finance-mnc.md)

---

## Quick-fire exam Q&A self-test

- *Write the IFE formula.* → $(S_1 - S_2)/S_1 \times 100 = i_D - i_N$ — **S₁ in denominator** (book is wrong)
- *Country has higher interest rate. What happens to its currency long-run?* → Depreciates
- *What does PPP predict about a high-inflation country's currency?* → Depreciation against low-inflation currencies
- *Currency in numerator vs denominator?* → If quoted "X per 1 Y" → X = numerator, Y = denominator
- *Define a currency swap.* → Simultaneous purchase and sale of foreign exchange **for two different value dates**
- *Three types of FX exposure?* → Transaction, translation, economic
- *Difference between translation and transaction exposure?* → Translation = paper/accounting effect on reported statements; Transaction = real cash effect on individual deals
- *How do you reduce economic exposure?* → Distribute production globally (real hedge), not financial hedging
- *Hedging definition?* → Protection against FX risk via futures contracts in foreign currencies
- *What is the bandwagon effect?* → Traders follow the crowd, selling a depreciating currency and buying an appreciating one, pushing rates away from fundamentals
- *Fisher Effect vs IFE?* → Fisher Effect: nominal rate = real rate + expected inflation (within 1 country). IFE: interest rate *differential* between 2 countries ≈ expected exchange rate change
