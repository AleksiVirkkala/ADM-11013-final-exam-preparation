---
title: Centralized Depositories (Global Money Management)
---

> **Teacher: *"Read or will go bad in the final exam. You'll lose a bunch of points."*** Likely essay. Memorize the 3 reasons.

## The question

> Should each foreign subsidiary hold its own cash, or **pool everything in one central location** (e.g., London, New York, Tokyo)?

## The answer: pool centrally — for 3 reasons (memorize)

### 1. Higher interest rates on larger deposits

Pooling enables larger deposits, which earn higher money-market interest rates. Big institutional balances get rate tiers that small subsidiary balances can't.

### 2. Better investment expertise

A central depository located in a financial hub (London, NYC, Tokyo, Singapore) has access to:

- More investment opportunities (a wider variety of instruments)
- More skilled financial experts
- Better visibility on market trends

than any individual subsidiary scattered around the world.

### 3. Smaller required cash buffer (the variance math)

This is the most counterintuitive reason and the one most likely to get points if you explain it well.

Cash needs of independent subsidiaries are statistically **uncorrelated**. By the standard variance-addition rule:

$$\sigma_{\text{pool}} = \sqrt{\sigma_1^2 + \sigma_2^2 + \cdots + \sigma_n^2}$$

The pooled standard deviation is **less than the sum of the individual standard deviations** — so the firm can hold less precautionary cash overall.

The freed-up cash can be redeployed to **higher-yielding (less liquid) investments**.

## Worked example (book)

3 subsidiaries (Korea, China, Japan) each hold day-to-day cash + 3 standard deviations of precautionary cash.

- Subsidiary σ values: σ₁ = 1, σ₂ = 2, σ₃ = 3 ($M)
- Without pooling: precautionary needed = 3·(1 + 2 + 3) = \$18M
- Sum of all individual cash requirements: ~\$46M

If centralized in Tokyo:

- Combined σ = √(1² + 2² + 3²) = √14 ≈ \$3.74M
- 3·3.74 ≈ \$11.2M precautionary
- Total requirement drops to ~\$39.2M

**Saves ~\$6.8M** in cash that can be redeployed to higher-yielding investments.

## Limits in practice

Why some firms compromise:

- **Government capital controls** in some countries restrict cross-border money movement
- **Transaction costs** of moving money internationally
- **Local cash needs** for day-to-day operations (payroll, taxes) can't be eliminated

Many firms compromise: **central depository for precautionary balances, local cash for day-to-day needs**.

## Q-style essay answer

> *"Explain how multinational corporations use centralized depositories for global money management."*

**Answer:**

A centralized depository is a single financial location (typically in a major financial hub like London, New York, or Tokyo) where a multinational pools cash from its various foreign subsidiaries, rather than letting each subsidiary hold its own large cash balance.

**Three reasons to centralize:**

1. **Higher interest rates on larger pooled deposits** — institutional rate tiers reward bigger balances
2. **Better investment expertise** — a financial-hub depository has access to more sophisticated instruments and skilled managers than any single subsidiary
3. **Smaller required cash buffer** — because individual subsidiaries' cash needs are statistically uncorrelated, the pooled standard deviation is *less than the sum* of individual standard deviations (√(σ₁² + σ₂² + ... + σₙ²)). The firm can hold less precautionary cash overall and redeploy the rest to higher-yielding, less-liquid investments.

**Worked example:** Three subsidiaries with σ = \$1M, \$2M, \$3M individually need ~\$46M total cash including buffer. Pooled in Tokyo, the combined buffer drops via the variance math to roughly \$11M (vs \$18M un-pooled), saving ~\$6.8M that can be redeployed.

**Limits:** government capital controls and transaction costs prevent full centralization. Many firms compromise — central depository for precautionary balances, local cash for day-to-day operations.

See [[../../questions/q-centralized-depositories|Q page]].

## See also

- [[multilateral-netting|Multilateral netting]] — related transaction-cost reduction
- [[moving-money|Moving money across borders]]
- [[../../formulas#Centralized depository - variance math|Formula sheet]]
- [[../../questions/q-centralized-depositories|Q walkthrough]]
