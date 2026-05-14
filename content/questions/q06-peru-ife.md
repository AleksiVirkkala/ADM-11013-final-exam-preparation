---
title: "Q6 — Peru IFE Forecast"
---

## Question

> The interest rate on Peruvian government securities with one-year maturity is **4.5 percent**, and the expected inflation rate for the coming year is two percent. The interest rate on US government securities with one-year maturity is **2 percent**, and the expected rate of inflation is 3.5 percent. The current spot exchange rate for Peruvian soles is **3.42 soles per US dollar**. Forecast the spot exchange rate one year from today. Explain the logic of your answer.

## Setup

- $i_N$ (Peru, numerator since PEN is the bigger number per USD) = 4.5% = 0.045
- $i_D$ (US, denominator) = 2% = 0.02
- $S_1$ = 3.42 PEN/USD
- Find $S_2$

> [!info] **Note on inflation rates:** The inflation rates given are not used directly — IFE uses **interest rates**. Inflation just explains *why* interest rates differ.

## Apply [[../topics/fx-theories/international-fisher-effect|IFE formula]]

$$\frac{S_1 - S_2}{S_1} = i_D - i_N = 0.02 - 0.045 = -0.025$$

$$3.42 - S_2 = -0.025 \times 3.42 = -0.0855$$

$$S_2 = 3.42 + 0.0855 = \textbf{3.5055 PEN/USD}$$

## Quick verify with shortcut

$$S_2 = S_1 \cdot (1 - i_D + i_N) = 3.42 \times (1 - 0.02 + 0.045) = 3.42 \times 1.025 = 3.5055 \, ✓$$

## Answer

> **One year from today, the spot exchange rate should be approximately 3.5055 soles per US dollar — the sol is expected to depreciate slightly against the dollar.**

## Logic of the answer (the "Explain" part)

Peru has a **higher nominal interest rate** (4.5%) than the US (2%). Per the [[../topics/fx-theories/international-fisher-effect|International Fisher Effect]], the currency of the country with the higher interest rate is expected to **depreciate** against the currency of the country with the lower interest rate. The intuition: high interest rates reflect expected high inflation, and per [[../topics/fx-theories/purchasing-power-parity|PPP]], high inflation erodes a currency's value over time.

The 2.5-percentage-point interest rate differential ($i_D - i_N = -2.5\%$) translates into an expected depreciation of the sol by roughly 2.5% over the year — taking the rate from 3.42 to ~3.5055 soles/USD.

## See also

- [[../topics/fx-theories/international-fisher-effect|IFE]]
- [[../topics/fx-theories/purchasing-power-parity|PPP]]
- [[../formulas|Formula sheet]]
