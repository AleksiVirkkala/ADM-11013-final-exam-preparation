# Lecture 30 — Mock Exam Walkthrough

> **Sources:** [`notes/ADM-11013 Lecture 30.md`](../../notes/ADM-11013%20Lecture%2030.md), [`transcripts/ADM-11013 Lecture 30.md`](../../transcripts/ADM-11013%20Lecture%2030.md), paper [`PRACTICE QUESTIONS FOR FINAL EXAM—INTERNATIONAL BUSINESS.md`](../../papers/PRACTICE%20QUESTIONS%20FOR%20FINAL%20EXAM%E2%80%94INTERNATIONAL%20BUSINESS.md).

> **Exam relevance: VERY HIGH.** This is the practice exam the teacher walked through in class. Expect SOME (but not all) of the actual exam questions to be similar to these.

> **Important caveat:** The teacher said *"these are not guaranteed to be exam questions but still useful data"* — treat as study material, not a leaked exam.

---

## What teacher confirmed about the final exam structure

- 16 points for **consolidation** (revised in Lecture 31 to 21 points)
- Indicate clearly whether result is **gain or loss**
- Format: 17 multiple choice (likely from book) + 7 essays (longer questions)
- Multiple choice from book chapters 2, 10, 11, 20
- Essays cover topics from class

---

## The 20 practice questions and how they map to exam topics

> The teacher walked through these in lecture 30. The discussion is summarized here in question order.

### Q1 — Transfer pricing direction (multiple choice)

**Q:** "When an MNC chooses to export components to an affiliate subsidiary in country X which has a relatively HIGH income tax rate, the natural decision would be to:"
- a. Lower transfer prices on the sale of goods to the subsidiary in country X
- b. **Raise transfer prices on the sale of goods to the subsidiary in country X** ← correct
- c. Cease exporting goods to the subsidiary in country X
- d. Reduce dividend payments from the subsidiary in country X

**Answer: B.** Raising transfer prices = raising the cost to the high-tax subsidiary → reducing its taxable profit there. Move income out of high-tax country into our country.

> **Cross-reference:** [chapters/chapter-20-finance-mnc.md](../chapters/chapter-20-finance-mnc.md) section on transfer pricing.

### Q2 — Outsourcing/Offshore production definition

**Q:** "Outsourcing or Offshore production relates to:"
- a. **FDI undertaken by a firm to serve its home market** ← correct
- b. FDI undertaken by a firm to serve the host market
- c. Outflow of foreign investment from developed to developing countries
- d. Outflow of foreign investment from developing to developed countries

**Answer: A.** Outsourcing = producing abroad to ship back home for sale in the home market.

### Q3 — IFE problem

**Q:** "If the spot exchange rate in 1 year between MXN and GBP is expected to be 35 MXN = 1 GBP, current spot is 25 MXN = 1 GBP, then what will happen after 1 year if the UK interest rate is 1% p.a.?"

**Setup:**
- $S_1$ = 25 MXN/GBP (today)
- $S_2$ = 35 MXN/GBP (1 year forecast)
- MXN = numerator, GBP = denominator
- $i_D$ (UK) = 1%
- Find: $i_N$ (Mexican interest rate)

**Apply formula:**
$$\dfrac{25 - 35}{25} = i_D - i_N = 0.01 - i_N$$

$$\dfrac{-10}{25} = -0.4$$

$$-0.4 = 0.01 - i_N$$

$$i_N = 0.41 = 41\%$$

**Answer:** The Mexican interest rate is **41%** — reflecting massive expected depreciation of the peso.

### Q4 — Big Mac / PPP problem

**Q:** "If Big Mac in NY = $5.90, Big Mac in Mexico = 67 pesos, market exchange rate = 19.5 MXN/USD, the Mexican peso is undervalued/overvalued? By what %?"

**Solution:**
- Theoretical rate = 67 / 5.90 = 11.36 MXN/USD
- Ratio = 11.36 / 19.5 = 0.58
- Peso is undervalued by (1 − 0.58) = **42%**

> See [Lecture 29 PPP/IFE](lecture-29-ppp-fisher.md) for more examples and the full method.

### Q5 — Chile/Argentina IFE problem

**Q:** "Chile and Argentina, both produce only beef. Beef is 750 CLP/kg in Chile, 60 ARP/kg in Argentina. (a) PPP exchange rate today? (b) If beef rises to 830 CLP and 75 ARP in 1 year, what's the 1-year forward rate? (c) Given Chile interest rate is 7%, what should Argentina's interest rate be?"

**Solution:**
- (a) $S_1$ = 750 / 60 = **12.5 CLP/ARP**
- (b) $S_2$ = 830 / 75 = **11.07 CLP/ARP**
- (c) $\dfrac{12.5 - 11.07}{12.5} = i_D - 0.07$ → $0.1144 = i_D - 0.07$ → $i_D = $ **18.44%** (Argentina)

### Q6 — Peru/US IFE problem

**Q:** "Peru: 4.5% interest, expected inflation 2%. US: 2% interest, expected inflation 3.5%. Spot 3.42 PEN/USD. Forecast spot rate in 1 year."

**Setup:**
- $i_N$ (Peru) = 4.5%, $i_D$ (US) = 2%
- $S_1$ = 3.42

**Apply:** $S_2 = S_1 (1 - i_D + i_N) = 3.42 \times (1 - 0.02 + 0.045) = 3.42 \times 1.025 = $ **3.5055 PEN/USD**

The Peruvian sol is expected to slightly depreciate.

> Note: The inflation rates given in the question are not actually used directly — the IFE uses interest rates. Inflation just explains why interest rates differ.

### Q7 — Wine glass / hedging strategy

**Q:** "You manufacture wine glasses. In mid-June, you receive an order for 10,000 glasses from Japan. Payment of 400,000 yen is due in mid-December. You expect the yen to RISE from $1=¥130 to $1=¥100 by December. You can borrow yen at 6% a year. What should you do?"

**The strategic question** — multiple valid answers, but the teacher wants reasoning.

**Analysis:**
- If yen rises (¥100 = $1 instead of ¥130 = $1), then 400,000 yen is worth MORE in dollars later
- ¥400,000 today @ ¥130/$1 = $3,077
- ¥400,000 later @ ¥100/$1 = $4,000
- So waiting is a $923 GAIN (~30%)

**Strategy options:**
1. **Don't hedge** — accept the upside; you expect the yen to rise
2. **Borrow yen now** at 6%, convert to USD now, repay the yen loan with the customer's payment in December — locks in current rate but loses the upside
3. **Forward contract** — sell yen forward at the locked-in 6-month forward rate

The teacher would accept any well-reasoned answer. Key is showing you understand the trade-offs.

> Note: Lecture 31 the teacher said "this question is for you" — i.e., he expects students to think through it themselves.

### Q8 — Mexican peso depreciation strategy

**Q:** "You are CFO of a US firm whose Mexican subsidiary manufactures parts for US assembly. Subsidiary financed by US bank borrowings. Mexican peso expected to depreciate by 9% next year. What actions?"

**Strategic answer points:**
- Pesos earnings will be worth less in USD when remitted → translation/transaction loss
- Consider hedging: forward contracts on peso, currency swaps
- Consider shifting financing to peso-denominated debt (depreciating peso means we owe LESS in real terms over time)
- Consider lead/lag strategies (collect peso receivables early; delay peso payables)
- Consider **leading and lagging** payments

### Q9 — Currency Board

**Q:** "What is the purpose of a Currency Board and how does it work?"

**Answer (memorize):**
- A currency board commits a country to converting its domestic currency to a foreign currency at a **fixed exchange rate**
- To make this credible, the board holds **at least 100% reserves** of the foreign currency to back the domestic currency in circulation ← **MUST INCLUDE THIS**
- Limits ability to print money → prevents inflation
- Interest rates adjust automatically (if locals flee, supply shrinks, rates rise)
- Examples: Hong Kong (1983, still in place), Argentina (1991-2002, abandoned)
- Drawback: government loses control of monetary/interest policy; if local inflation differs from anchor country's, currency becomes overvalued

> See [chapters/chapter-11-monetary-system.md](../chapters/chapter-11-monetary-system.md) for full detail.

### Q10 (and Q19) — 4 mechanisms to minimize tax + ethics

**Q10:** "What actions can a firm take to minimize its global tax liability? On ethical grounds, can such actions be justified?"

**Answer (the 4 mechanisms — memorize):**
1. **Transfer pricing** — manipulate inter-subsidiary prices
2. **Charging royalties** — IP in low-tax sub, charge royalties to high-tax subs
3. **Charging dividends** — high-tax sub pays dividends to low-tax owner
4. **Fronting loans** — channel funds via international bank between tax haven and high-tax sub

All four exploit **tax havens**.

**Ethics argument (both sides):**
- Pro: Companies have duty to shareholders to legally minimize tax. The strategies are technically legal. Companies are not charities.
- Con: Strategies are morally questionable, exploit gray areas, deny tax revenue to countries where the company actually operates and creates value. Encourages inequality. Some countries (Mexico, EU) increasingly auditing.

> See [chapters/chapter-20-finance-mnc.md](../chapters/chapter-20-finance-mnc.md) for full detail of each mechanism.

### Q11 — Floating vs Fixed exchange rates

**Q:** "What are the advantages of the floating exchange rate regime versus the advantages of the fixed exchange rate regime?"

**Answer:**

**FLOATING advantages:**
1. Monetary policy autonomy
2. Automatic trade balance adjustments
3. Crisis recovery via depreciation

**FIXED advantages:**
1. Monetary discipline
2. Speculation control
3. Reduced uncertainty for international business
4. Trade balance argument is overstated (depreciation doesn't actually fix deficits)

> See [chapters/chapter-11-monetary-system.md](../chapters/chapter-11-monetary-system.md) for full detail.

### Q12 — Intellectual property classes

**Q:** "Explain the distinct classes of intellectual property."

**Answer:**
- **Patent** — exclusive rights to a new invention/process for ~20 years
- **Copyright** — exclusive rights of authors/composers/artists; ~50 years after death
- **Trademark** — registered designs/names that distinguish products (Christian Dior, Starbucks logo); indefinite

> See [chapters/chapter-2-legal-systems.md](../chapters/chapter-2-legal-systems.md).

### Q13 — Method for subsidiary financial statement consolidation

**Q:** "How does a firm determine which method it will use for subsidiary financial statement consolidation? Explain the logic."

**Answer:**
- It's NOT the firm's choice — it's determined by the **functional currency**
- If functional currency = home country currency → **Temporal method**
- If functional currency = host country currency → **Current Rate method**
- The firm's CFO can't pick whichever gives better numbers — auditors enforce
- Logic: the method that best reflects the economic reality of the subsidiary

> See [reference/consolidation-theory.md](../reference/consolidation-theory.md) for full detail.

### Q14 — Torts

**Q:** "What are the distinct classes of torts under Common Law? Create a hypothetical situation of tort claim under each one."

**Answer (memorize the 3 types + examples):**

1. **Intentional torts** — deliberate harm
   - Example: Defendant punches plaintiff in the face → battery
2. **Negligence** — unreasonable but unintentional harm
   - Example: Driver texting runs red light, hits pedestrian
3. **Strict liability** — liable even without fault (typically products)
   - Example: Store sells defective blender, injures buyer; store liable even though it didn't make the defect

> See [reference/torts.md](../reference/torts.md) for full detail.

### Q15 — Civil law vs Common law

**Q:** "What are the relative advantages and disadvantages of the Civil Law system (codified) and the Common Law system?"

**Answer (compare both — don't take a strong stance):**

| | Common Law | Civil Law |
|---|---|---|
| Pros | Flexible; judges adapt to unique cases; evolves | Predictable; cheaper contracts; less adversarial |
| Cons | Costly contracts (must spell out everything); adversarial disputes | Inflexible; harder to adapt to new situations |

> See [chapters/chapter-2-legal-systems.md](../chapters/chapter-2-legal-systems.md).

### Q16 — Lessard-Lorange

**Q:** "What does the Lessard-Lorange model have to say about budgeting and comparison of actual results to the budget?"

**Answer:**
- Three exchange rates: Initial (when budget set), Projected (forward rate forecast), Ending (when comparing)
- Of 9 possible combinations, 5 are sensible
- Lessard-Lorange recommends combination **PP** = use Projected (forward) rate to translate BOTH budget and actual
- Why: same rate on both sides eliminates distortion from FX changes during the year
- Plus, projected rate incorporates expected future FX movements

> See [chapters/chapter-20-finance-mnc.md](../chapters/chapter-20-finance-mnc.md).

### Q17 — Fronting loan

**Q:** "Describe a fronting loan (préstamo subsidiado)."

**Answer:**
- A loan between a parent and subsidiary channeled through an international bank
- Tax-haven sub deposits cash with the bank → receives tax-free interest
- Bank lends to high-tax sub at slightly higher interest → high-tax sub deducts the interest
- Bank takes a small spread for the service
- Two purposes: (1) circumvent host-country capital flow restrictions, (2) tax advantages

> See [chapters/chapter-20-finance-mnc.md](../chapters/chapter-20-finance-mnc.md) for the diagram.

### Q18 — Hedging

**Q:** "Explain the concept of hedging."

**Answer:**
- Protection against foreign exchange risk
- Achieved by buying futures contracts in foreign currencies (forward contracts, currency swaps, options)
- Etymology: "hedge" originally a row of bushes in medieval Europe protecting property lines; in finance, hedging protects against loss
- Different from a "hedge fund" (which is something else: invests in high-risk securities, "hedges" via diversification)

> See [chapters/chapter-10-fx-market.md](../chapters/chapter-10-fx-market.md).

### Q19 — Same as Q10 (tax havens question, slight variation)

### Q20 — Law of one price ↔ PPP

**Q:** "What is the law of one price? How is it related to the concept of Purchasing Power Parity?"

**Answer:**
- **Law of one price**: in efficient markets free of trade barriers, identical products must sell for the same price across countries when expressed in a common currency
- **PPP**: extends law of one price to a "basket" of goods — predicts the exchange rate that would equalize the cost of the basket
- The Big Mac Index is The Economist's PPP test using the Big Mac as the "basket"
- In the real world, neither always holds because of transport costs, tariffs, government intervention, market power, investor psychology

> See [chapters/chapter-10-fx-market.md](../chapters/chapter-10-fx-market.md).

---

## What's NOT in this practice exam (but might still be on the actual exam)

The teacher said in Lecture 31 you should also know:
- **Currency swap** definition (must mention "2 different value dates")
- **IMF vs World Bank** roles
- **Gold standard** history
- **Dirty float** definition
- **Centralized depositories** (3 reasons)
- **Currency board** (already in Q9)
- **Transaction / translation / economic exposure** (with examples)

---

## Strategy advice from the teacher

> "Don't be superficial. Write thorough, complete answers. Don't take it lightly."

> "If you lost points in the 2nd exam, it was probably because you were superficial. Write in detail, professionally."

> "Answer in numerical order. If you need to skip, leave a space."

---

## See also

- [Practice questions paper (full)](../../papers/PRACTICE%20QUESTIONS%20FOR%20FINAL%20EXAM%E2%80%94INTERNATIONAL%20BUSINESS.md) — the original handout
- [Lecture 29 — PPP and Fisher Effect detail](lecture-29-ppp-fisher.md)
- [Lecture 31 — Final review with extended topic list](lecture-31-final-review.md)
- All chapters in [`chapters/`](../chapters/) for the underlying theory
