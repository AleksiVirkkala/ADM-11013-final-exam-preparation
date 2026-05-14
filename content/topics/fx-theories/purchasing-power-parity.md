---
title: Purchasing Power Parity & Big Mac Index
---

> Theory: a basket of goods should cost the same in different countries when converted at the exchange rate. The Big Mac Index is The Economist's test of this. **Likely on the exam as a calculation problem.**

## PPP theory

> Given relatively efficient markets, a "basket of goods" should cost roughly the same in each country once converted at the exchange rate.

$$E_{A/B} = \frac{P_A}{P_B}$$

If the same basket costs \$200 in the US and ¥20,000 in Japan, predicted PPP rate is **\$1 = ¥100**.

## The Big Mac Index

The Economist uses the price of a Big Mac (a standardized "basket" made the same way in ~120 countries) as a PPP test. Compare the theoretical PPP rate to the actual market rate to derive over/undervaluation.

## Over/undervaluation pattern (memorize)

1. **Theoretical rate** = (price in country A's currency) ÷ (price in country B's currency)
2. **Ratio** = theoretical ÷ actual market rate
3. If ratio **> 1**: numerator currency is **overvalued** by (ratio − 1)
4. If ratio **< 1**: numerator currency is **undervalued** by (1 − ratio)

The percentage = how far the ratio is from 1.0.

## Worked example: Norway

| Input | Value |
|---|---|
| Big Mac in Norway | 93 NOK |
| Big Mac in NYC | \$7.59 USD |
| Actual exchange rate | 10.16 NOK/USD |

$$\text{Theoretical} = \frac{93}{7.59} = 12.25 \text{ NOK/USD}$$

$$\text{Ratio} = \frac{12.25}{10.16} = 1.21$$

→ **Norwegian krona is OVERVALUED by 21%**.

(Interpretation: at theoretical rates, you'd need 12.25 NOK to get \$1, but in reality only 10.16 NOK is needed. The krona is more expensive than fundamentals suggest.)

## Worked example: Mexico (Q4 on practice exam)

| Input | Value |
|---|---|
| Big Mac in Mexico | 67 pesos |
| Big Mac in NYC | \$5.90 |
| Actual exchange rate | 19.5 pesos/USD |

$$\text{Theoretical} = \frac{67}{5.90} = 11.36 \text{ MXN/USD}$$

$$\text{Ratio} = \frac{11.36}{19.5} = 0.58$$

→ **Mexican peso is UNDERVALUED by (1 − 0.58) = 42%**.

See [[../../questions/q04-bigmac-mexico|Q4 walkthrough]].

## Worked example: Switzerland

Big Mac in Switzerland: 8.17 CHF. NYC: \$5.81. Actual rate: 0.909 CHF/USD.

- Theoretical = 8.17 / 5.81 = **1.406 CHF/USD**
- Ratio = 1.406 / 0.909 = **1.547**
- Swiss franc is **overvalued by ~55%**

## Why some currencies are over/undervalued

| Currency | Direction | Why |
|---|---|---|
| **Norwegian krona** | Overvalued | Market premium for stability, oil reserves, low corruption |
| **Swiss franc** | Overvalued | Similar, plus banking secrecy reputation |
| **Mexican peso** | Undervalued | Market punishes Mexico for perceived corruption, drug violence, less stable institutions |

## Why PPP fails in practice

- **Transport costs and tariffs** violate the law-of-one-price assumption
- **Government intervention** in FX markets
- **Multinational price discrimination** — McDonald's can charge differently in different markets even for the same Big Mac
- **Investor psychology / bandwagon effects** (short-term) push rates away from fundamentals
- **PPP works much better long-run than short-run**

## Inflation, money supply, and PPP

- High **money supply growth** → high **inflation** → currency **depreciates** (PPP prediction)
- Bolivia hyperinflation case study (1984-85): money supply +17,433%, prices +22,908%, peso depreciated −24,662% — all aligned with PPP
- Memorize the causal chain: **money supply → inflation → depreciation**

## Bandwagon effect (likely MC)

> When traders see a currency depreciating, they assume it will continue, rush to sell, which *causes* further depreciation. The opposite happens with appreciating currencies. Pushes rates away from fundamentals for extended periods.

This is a key argument *against* floating exchange rates (speculation is destabilizing). Also why PPP fails in the short run.

## Relationship with [[international-fisher-effect|IFE]] (Q5 connection)

PPP and IFE make the same fundamental prediction via different routes:

- **PPP**: higher inflation → currency depreciates (via goods prices)
- **IFE**: higher interest rate → currency depreciates (via interest rates, which reflect expected inflation)

So in Q5 (Chile/Argentina), you can:
1. Use PPP to find $S_1$ and $S_2$ (theoretical rates based on beef prices)
2. Then apply IFE to find the missing interest rate

## Relationship with [[law-of-one-price|Law of one price]]

PPP extends law-of-one-price from a single product to a **basket of goods**. Q20 asks specifically how they relate.

## See also

- [[law-of-one-price|Law of one price]]
- [[international-fisher-effect|IFE]]
- [[../../questions/q04-bigmac-mexico|Q4 — Big Mac calculation]]
- [[../../questions/q05-chile-argentina-ppp-ife|Q5 — PPP + IFE combined]]
- [[../../questions/q20-law-of-one-price-ppp|Q20 — Law of one price ↔ PPP]]
- [[../../formulas#Big Mac Index over/undervaluation|Formula sheet]]
