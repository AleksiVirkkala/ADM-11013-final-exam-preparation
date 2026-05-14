---
title: Formulas
---

> Every formula you might need on the exam, on one page. For derivation and context, follow the link.

## International Fisher Effect

> [!danger] Book error — use **S₁ in denominator** (book has S₂)
> $$\frac{S_1 - S_2}{S_1} \times 100 = i_D - i_N$$

| Symbol | Meaning |
|---|---|
| $S_1$ | Spot exchange rate today |
| $S_2$ | Spot exchange rate one year from today (forecast) |
| $i_D$ | Nominal interest rate in the **denominator** country |
| $i_N$ | Nominal interest rate in the **numerator** country |

If the rate is quoted "X currency per 1 Y currency," X is the numerator and Y is the denominator.

**Algebraic rearrangement (shortcut):**
$$S_2 = S_1 \cdot (1 - i_D + i_N)$$

Multiplication by 100 is optional — use decimal (0.07) or percent (7%), just be consistent.

Full detail: [[topics/fx-theories/international-fisher-effect|IFE]].

## Purchasing Power Parity (PPP)

Predicted exchange rate that equalizes the price of a basket of goods:
$$E_{A/B} = \frac{P_A}{P_B}$$

Where $P_A$, $P_B$ are the basket prices in each country's currency.

Full detail: [[topics/fx-theories/purchasing-power-parity|PPP]].

## Big Mac Index over/undervaluation

1. **Theoretical rate** = (price in country A's currency) ÷ (price in country B's currency)
2. **Ratio** = theoretical ÷ actual market rate
3. If ratio **> 1**: numerator currency is **overvalued** by (ratio − 1)
4. If ratio **< 1**: numerator currency is **undervalued** by (1 − ratio)

Example: Norway krona, theoretical 12.25 NOK/USD, actual 10.16. Ratio = 1.21 → krona **overvalued by 21%**.

Example: Mexican peso, theoretical 11.36 MXN/USD, actual 19.5. Ratio = 0.58 → peso **undervalued by 42%**.

Full detail: [[topics/fx-theories/purchasing-power-parity|PPP / Big Mac]].

## Domestic Fisher Effect

$$\text{Nominal interest rate} \approx \text{Real rate} + \text{Expected inflation}$$

This is **within** a country. The international Fisher effect chains this together across two countries via PPP.

## Consolidation — total result decomposition

$$\text{Operational result} + \text{FX gain/loss} = \text{Total result}$$

Where **Total result = change in retained earnings during the year (ΔRE)**:
$$\Delta RE = RE_{\text{31/12}} - RE_{\text{1/1}}$$

So under the Temporal method:
$$\text{FX gain/loss} = \Delta RE - \text{Operational result}$$

Positive → label "**gain**". Negative → label "**loss**". Must label explicitly.

Full detail: [[topics/consolidation/exchange-gain-loss|Computing exchange gain/loss]].

## Conversion direction

| Quote format | To convert local → USD |
|---|---|
| "X local per 1 USD" (e.g., 17.5 pesos/USD, 109 yen/USD) | **Divide** local by rate |
| "X USD per 1 local" (e.g., \$1.49/GBP) | **Multiply** local by rate |

## Centralized depository — variance math

Pooled cash requirement is *less* than the sum because subsidiary cash needs are statistically uncorrelated:
$$\sigma_{\text{pool}} = \sqrt{\sigma_1^2 + \sigma_2^2 + \cdots + \sigma_n^2}$$

Book example: 3 subs with σ = 1, 2, 3 ($M) → individual sum = \$6M, pooled σ = √14 ≈ \$3.74M. Total cash savings ~\$6.8M.

Full detail: [[topics/mnc-finance/centralized-depositories|Centralized depositories]].

## Lessard-Lorange (rule, not a formula)

Use the **Projected (P) rate** to translate both budget AND actual. Same rate on both sides eliminates FX-distortion in performance comparison.

Full detail: [[topics/mnc-finance/lessard-lorange|Lessard-Lorange model]].

## Fronting loan flow (worked numbers)

Parent deposits \$1M in London bank at 8%; bank lends \$1M to UK sub at 9%:

- UK sub pays \$90K interest → tax-deductible at 50% → after-tax cost **\$45K**
- Bank keeps \$10K spread, pays \$80K to Bermuda
- Bermuda receives \$80K tax-free
- **Net effect:** \$80K moved from UK to Bermuda; UK only really paid \$45K → \$35K of "free" money moved out

Full detail: [[topics/tax-mechanisms/fronting-loans|Fronting loans]].

## Transfer pricing direction (cheat)

To shift profit OUT of a high-tax country:

- Goods sold **into** the high-tax sub → **raise** the transfer price (raises its costs → lowers profit there)
- Goods sold **out of** the high-tax sub → **lower** the transfer price (lowers its revenue)

Full detail: [[topics/tax-mechanisms/transfer-pricing|Transfer pricing]].
