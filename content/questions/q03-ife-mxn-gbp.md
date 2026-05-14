---
title: "Q3 — IFE Calculation (MXN/GBP)"
---

## Question

> If the spot exchange rate in the future (1 year) between the Mexican peso (MXN) and the British Pound (UKP) is expected to be **35 MXN = 1 UKP** and the current spot exchange rate is **25 MXN = 1 UKP**, then what will happen after 1 year if the **UK interest rate is 1% p.a.**?

## Setup

- $S_1$ = 25 MXN/GBP (today)
- $S_2$ = 35 MXN/GBP (1 year forecast)
- Quote format: "MXN per 1 GBP" → MXN is numerator, GBP is denominator
- UK interest rate (denominator country) $i_D$ = 1% = 0.01
- Find: Mexican interest rate $i_N$

## Apply [[../topics/fx-theories/international-fisher-effect|IFE formula]]

$$\frac{S_1 - S_2}{S_1} = i_D - i_N$$

$$\frac{25 - 35}{25} = 0.01 - i_N$$

$$\frac{-10}{25} = -0.4$$

$$-0.4 = 0.01 - i_N$$

$$\boxed{i_N = 0.41 = 41\%}$$

## Answer

**The Mexican interest rate should be 41% per annum** — reflecting massive expected depreciation of the peso against the pound.

## Why

The peso is expected to lose value rapidly (need 35 pesos per pound in 1 year vs only 25 today, a 40% depreciation). Per [[../topics/fx-theories/international-fisher-effect|IFE]], that depreciation reflects expected inflation in Mexico, which forces Mexican nominal interest rates to be much higher than UK rates.

## See also

- [[../topics/fx-theories/international-fisher-effect|IFE]]
- [[../formulas#International Fisher Effect|Formula sheet]]
