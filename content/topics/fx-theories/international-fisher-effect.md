---
title: International Fisher Effect (IFE)
---

> **The teacher confirmed multiple times this WILL be on the exam.** Either a multiple choice or a full calculation question. Likely both.

## The formula

> [!danger] **BOOK ERROR (p. 300):** The book prints **S₂ in the denominator**. That's a typo. **Cross it out** and write S₁.

$$\boxed{\frac{S_1 - S_2}{S_1} \times 100 = i_D - i_N}$$

Where:

| Symbol | Meaning |
|---|---|
| $S_1$ | Spot exchange rate **today** |
| $S_2$ | Spot exchange rate **one year from today** (forecast / futures rate) |
| $i_D$ | Nominal interest rate in the **denominator** country |
| $i_N$ | Nominal interest rate in the **numerator** country |

**Multiplication by 100 is optional** — use decimal (0.07) OR percent (7%), just stay consistent.

> Teacher: *"Don't correct it now. The book is wrong, class. I repeat, correct your book. It's a typo, an orthographical error. It says S2. You measure the percent change in terms of what it is today, not in terms of what it will be in one year."*

## Identifying numerator vs denominator

If the exchange rate is quoted "X currency per 1 Y currency":

- **X** = numerator country
- **Y** = denominator country

Examples:

| Quote | Numerator | Denominator |
|---|---|---|
| 17.5 MXN per 1 USD | Mexico | USA |
| 109 yen per 1 USD | Japan | USA |
| \$1.10 USD per 1 EUR | USA | Eurozone |
| 12.5 CLP per 1 ARP | Chile | Argentina |

> **Convention:** Markets quote stronger currency in the denominator (smaller, cleaner number).

## What IFE says in plain English

> The change in spot exchange rate equals (in the opposite direction) the difference in nominal interest rates between two countries.

**Country with higher interest rate → its currency expected to depreciate** (long run).

**Why?** Interest rates reflect expected inflation. Higher rate → market expects higher inflation → currency loses value (via [[purchasing-power-parity|PPP]] logic).

## Shortcut formula (algebraic rearrangement)

$$S_2 = S_1 \cdot (1 - i_D + i_N)$$

Useful when solving for $S_2$. Verify with the Peru example below.

## Domestic Fisher Effect (don't confuse)

$$\text{Nominal interest rate} \approx \text{Real rate} + \text{Expected inflation}$$

This is **within a country**. The IFE chains the domestic Fisher Effect across two countries via PPP.

## Worked example 1: Solve for $i_N$ (MXN vs GBP)

Given:
- $S_1$ = 25 MXN/GBP (today), $S_2$ = 35 MXN/GBP (1 year)
- UK interest rate $i_D$ = 1%
- MXN = numerator, GBP = denominator

Find $i_N$ (Mexico).

$$\frac{25 - 35}{25} = i_D - i_N = 0.01 - i_N$$

$$\frac{-10}{25} = -0.4$$

$$-0.4 = 0.01 - i_N \implies i_N = 0.41 = \textbf{41\%}$$

The Mexican interest rate is **41%** — reflecting massive expected peso depreciation. See [[../../questions/q03-ife-mxn-gbp|Q3]].

## Worked example 2: Solve for $S_2$ (Peru)

Given:
- $i_N$ (Peru) = 4.5%, $i_D$ (US) = 2%
- $S_1$ = 3.42 PEN/USD (PEN = numerator)

Find $S_2$.

$$\frac{3.42 - S_2}{3.42} = 0.02 - 0.045 = -0.025$$

$$3.42 - S_2 = -0.025 \times 3.42 = -0.0855$$

$$S_2 = 3.42 + 0.0855 = \textbf{3.5055 PEN/USD}$$

The sol weakens slightly (need more soles per dollar). See [[../../questions/q06-peru-ife|Q6]].

**Verify with shortcut:** $S_2 = 3.42 \times (1 - 0.02 + 0.045) = 3.42 \times 1.025 = 3.5055$ ✓

## Worked example 3: Solve for $i_D$ (Chile-Argentina)

Given:
- $S_1$ = 12.5 CLP/ARP, $S_2$ = 11.07 CLP/ARP
- $i_N$ (Chile, numerator) = 7%

Find $i_D$ (Argentina).

$$\frac{12.5 - 11.07}{12.5} = i_D - 0.07$$

$$0.1144 = i_D - 0.07 \implies i_D = \textbf{18.44\%}$$

Argentina's rate is higher because the ARP depreciates against CLP (need fewer CLP per ARP in 1 year). See [[../../questions/q05-chile-argentina-ppp-ife|Q5]].

## Worked example 4: Korean won

Given $i_D$ = 7%, $i_N$ = 4%, $S_1$ = 1,200 KRW/USD. Find $S_2$.

Using shortcut: $S_2 = 1,200 \times (1 - 0.07 + 0.04) = 1,200 \times 0.97 = \textbf{1,164 KRW/USD}$

The won **appreciates** (need fewer won per dollar). Korea's interest rate is LOWER → less expected inflation → currency strengthens.

## How the exam will test you

The teacher will give you **3 of the 4 variables** ($S_1$, $S_2$, $i_D$, $i_N$) and ask for the 4th. Multiple choice or short essay.

Format will be something like:
> *"Two countries [X and Y]. Spot rate today is [S₁]. The interest rate in [country A] is [X%]. According to the IFE, what should [missing variable] be?"*

You must:
1. **Identify numerator vs denominator** (the very first step — get this wrong and everything else is wrong)
2. Plug into the formula correctly
3. Solve algebraically

## When IFE fails in practice

Better long-run than short-run predictor. Short-run failures from:

- **Bandwagon effects** — traders follow the crowd, push rates away from fundamentals
- **Speculation** (e.g., George Soros 1992 vs British pound)
- **Government intervention** in FX markets
- **Carry trade** — money flows IN to capture high interest rates → currency appreciates (opposite of IFE prediction); teacher mentioned current Mexico (high rates, strong peso) as an example. See [[carry-trade|carry trade]].

## See also

- [[purchasing-power-parity|PPP]] — the underlying inflation/exchange-rate theory
- [[../../questions/q03-ife-mxn-gbp|Q3 walkthrough]]
- [[../../questions/q05-chile-argentina-ppp-ife|Q5 walkthrough]]
- [[../../questions/q06-peru-ife|Q6 walkthrough]]
- [[../../formulas#International Fisher Effect|Formula sheet]]
