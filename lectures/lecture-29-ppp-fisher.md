# Lecture 29 — Purchasing Power Parity & International Fisher Effect

> **Sources:** Lecture 29 notes and transcript.

> **Exam relevance: VERY HIGH.** Fisher Effect is a guaranteed exam question. PPP / Big Mac Index also explicitly covered.

> **Teacher: "Will appear on exam."**

---

## Purchasing Power Parity (PPP)

> **Theory:** A given product (commodity) should have the same price in different countries when prices are converted using the exchange rate. The exchange rate equalizes prices.

### Big Mac Index (The Economist's PPP test)
The price of a Big Mac in 120+ countries is the proxy "basket of goods." Compare the actual exchange rate to the rate that would make Big Macs cost the same everywhere → tells you whether currencies are over/undervalued.

### Worked example: Norway

- Big Mac in Norway: 93 NOK
- Big Mac in NYC: $7.59 USD
- Actual exchange rate: 10.16 NOK/USD
- **Theoretical PPP rate** = 93 ÷ 7.59 = 12.25 NOK/USD
- **Ratio** = 12.25 / 10.16 = 1.21
- **Norwegian krona is overvalued by 21%**

### Worked example: Mexico

- Big Mac in Mexico: 67 pesos (older data)
- Big Mac in NYC: $5.90
- Actual exchange rate: 19.5 pesos/USD
- **Theoretical** = 67 / 5.90 = 11.36 pesos/USD
- **Ratio** = 11.36 / 19.5 = 0.58
- **Mexican peso is undervalued by 1 − 0.58 = 42%**

### Pattern (memorize for the exam):
1. **Theoretical rate** = (price in country A's currency) ÷ (price in country B's currency)
2. **Ratio** = theoretical ÷ actual market rate
3. If ratio > 1: numerator currency is **overvalued**
4. If ratio < 1: numerator currency is **undervalued**
5. The percentage = how far the ratio is from 1.0

### Why some currencies over/undervalued
- **Norway overvalued:** Markets give Norway a premium because of its reputation for managing economy well, oil reserves, low corruption
- **Mexico undervalued:** Markets punish Mexico due to perception of corruption, drug violence, less stable institutions
- **Switzerland overvalued:** Similar reasons to Norway, plus banking secrecy reputation

### Other examples to know
- Switzerland: Swiss franc overvalued by ~55% (Swiss Big Mac at 8.17 CHF vs $5.81 in NYC; rate 0.909 CHF/USD vs theoretical 1.406)
- The teacher might ask about any country on the exam

---

## International Fisher Effect (IFE)

### The big picture
> The change in spot exchange rate between two countries equals (in the OPPOSITE direction) the difference in nominal interest rates between those countries.

In plain English: a country with a HIGHER interest rate will see its currency DEPRECIATE relative to the lower-interest-rate country.

### Why? (The economic logic)
- Interest rates reflect **expected inflation**
- High interest rate → market expects high inflation
- High inflation → currency loses value (PPP principle)
- So: high interest rate → currency depreciation

### THE FORMULA (must memorize)

$$\boxed{\dfrac{S_1 - S_2}{S_1} \times 100 = i_D - i_N}$$

Where:
- $S_1$ = spot exchange rate today
- $S_2$ = futures market rate one year from today
- $i_D$ = nominal interest rate in **denominator** country
- $i_N$ = nominal interest rate in **numerator** country

### 🚨 CRITICAL: BOOK ERROR 🚨

The book on **page 300** prints S₂ in the denominator. That's a typo. **Cross it out** and write S₁. The teacher said this multiple times across lectures 29, 30, 31:

> "Don't correct it now. The book is wrong, class. I repeat, correct your book. It's a typo, an orthographical error. It says S2. You measure the percent change in terms of what it is today, not in terms of what it will be in one year."

### Identifying numerator vs denominator
If exchange rate is "X currency per 1 Y currency":
- X = numerator country
- Y = denominator country

Examples:
- "12.5 Chilean pesos per 1 Argentine peso" → CLP = numerator, ARS = denominator
- "17.5 Mexican pesos per 1 USD" → MXN = numerator, USD = denominator

### Convention: bigger-number currency goes in numerator
Markets typically quote stronger currencies in the denominator (smaller number = simpler).
- USD/EUR: ~$1.10 per 1 EUR (USD numerator)
- USD/GBP: ~$1.50 per 1 GBP (USD numerator)
- MXN/USD: ~17.5 pesos per 1 USD (MXN numerator)
- JPY/USD: ~109 yen per 1 USD (JPY numerator)

---

## Worked Example 1: Solve for $i_D$ (Argentina interest rate)

**Given:**
- Chile-Argentina exchange rate
- Chilean beef price: 750 CLP/kg today, 830 CLP/kg in 1 year (forecast)
- Argentine beef price: 60 ARP/kg today, 75 ARP/kg in 1 year (forecast)
- Chilean interest rate (numerator) = 7%

**Step 1: Compute $S_1$ (today's PPP rate)**
$$S_1 = \dfrac{750}{60} = 12.5 \text{ CLP/ARP}$$

**Step 2: Compute $S_2$ (1-year-ahead PPP rate)**
$$S_2 = \dfrac{830}{75} = 11.07 \text{ CLP/ARP}$$

**Step 3: Apply IFE formula**
$$\dfrac{12.5 - 11.07}{12.5} = i_D - 0.07$$

$$0.1144 = i_D - 0.07$$

$$\boxed{i_D = 0.1844 = 18.44\%}$$

So Argentina's interest rate should be 18.44% — much higher than Chile's 7%, because the Argentine peso is expected to depreciate (1 ARP buys fewer CLP in 1 year: 11.07 vs 12.5).

---

## Worked Example 2: Solve for $S_2$ (Peru forecast rate)

**Given:**
- Peruvian interest rate (numerator) = 4.5%
- US interest rate (denominator) = 2%
- Today's spot rate $S_1$ = 3.42 PEN/USD

**Find:** $S_2$ in one year.

$$\dfrac{3.42 - S_2}{3.42} = 0.02 - 0.045 = -0.025$$

$$3.42 - S_2 = -0.025 \times 3.42 = -0.0855$$

$$S_2 = 3.42 + 0.0855 = 3.5055 \text{ PEN/USD}$$

So the Peruvian sol is expected to depreciate slightly: today $1 buys 3.42 soles; in 1 year $1 buys 3.5055 soles. Why? Peru has higher interest rate → more expected inflation → currency weakens.

### Quick shortcut formula
$$S_2 = S_1 \cdot (1 - i_D + i_N)$$

Verify: $S_2 = 3.42 \times (1 - 0.02 + 0.045) = 3.42 \times 1.025 = 3.5055$ ✓

---

## Worked Example 3: Solve for $S_2$ (Korean Won)

**Given:**
- US interest rate (denominator) = 7%
- Korean interest rate (numerator) = 4%
- Today's spot $S_1$ = 1,200 KRW/USD

**Find:** $S_2$.

Using shortcut: $S_2 = 1,200 \times (1 - 0.07 + 0.04) = 1,200 \times 0.97 = 1,164$ KRW/USD

The Korean won is expected to APPRECIATE (need fewer won per dollar). Why? Korea has LOWER interest rate → less expected inflation → currency strengthens.

---

## How the exam will test you

The teacher will give you **3 of the 4 variables** ($S_1$, $S_2$, $i_D$, $i_N$) and ask you to find the 4th. Format:

> "Two countries [X and Y]. Spot rate today is [S₁]. The interest rate in [country A] is [X%]. According to the International Fisher Effect, what should [the missing variable] be?"

You must:
1. Identify which country is numerator vs denominator
2. Plug into the formula correctly
3. Solve algebraically

Be careful:
- Whether to multiply by 100 doesn't matter (decimal vs percent), as long as you're consistent
- Sign convention: percent change can be negative (currency strengthens) or positive (depreciates)

---

## Relationship between PPP and IFE

Both flow from the same root principle:
- **PPP**: prices equalize across countries (with the exchange rate)
- **IFE**: interest rates and exchange rates compensate for inflation differences

Connection: If country A has higher inflation than country B → PPP predicts A's currency depreciates against B → because interest rates reflect expected inflation, A's interest rate is also higher → IFE's prediction matches PPP's.

So both theories make the same fundamental prediction: **higher inflation → currency depreciation**, just expressed differently (one through goods prices, the other through interest rates).

---

## Why these theories don't always work in practice

**Both PPP and IFE are better long-run than short-run predictors.** Why short-run failures?
- **Investor psychology / bandwagon effects** — currencies overshoot
- **Speculation** (e.g., George Soros 1992 vs British pound)
- **Government intervention** in FX markets
- **Transport costs and trade barriers** (block arbitrage)
- **Market power** of multinationals (price discrimination)

The teacher mentioned that **Mexico's interest rates are high but the peso is also strong** right now, contradicting IFE. This is because money is flowing INTO Mexico to capture the high interest rates → demand for pesos rises → peso appreciates. This is the "carry trade" effect, opposite to IFE's prediction. In the long run, IFE should reassert.

---

## Quick conceptual quiz

- *What does PPP theory say?* → Same product should have the same price in different countries when converted at the exchange rate
- *What does IFE say?* → The change in spot rate equals (in opposite direction) the difference in interest rates
- *Country with higher interest rate — currency direction?* → Long-run: depreciates
- *Big Mac in Norway costs much more than NYC. Krona is over- or undervalued?* → Overvalued
- *Big Mac in Mexico costs less than NYC after conversion. Peso is over- or undervalued?* → Undervalued
- *IFE formula denominator?* → S₁ (book is wrong; teacher repeatedly said correct it)

---

## See also

- [Chapter 10 — full theoretical context](../chapters/chapter-10-fx-market.md)
- [Lecture 30 — Mock exam practice](lecture-30-mock-exam.md) — applies these concepts on practice questions
- [Lecture 31 — Final review](lecture-31-final-review.md)
