---
title: Lead and Lag Strategy
---

> Operational hedging technique — adjusting the timing of payments and collections based on FX forecasts. Used to reduce [[three-exposures#1. Transaction exposure|transaction]] and [[three-exposures#2. Translation exposure|translation]] exposure without buying derivatives.

## The rules

| Scenario | What to do |
|---|---|
| Foreign currency expected to **depreciate** | **Lead** receivables (collect early before currency loses value); **lag** payables (delay paying — your debt shrinks in real terms) |
| Foreign currency expected to **appreciate** | **Lag** receivables (delay collection — they'll be worth more); **lead** payables (pay early before they cost more) |

> Memory aid: **L**ead = act early to **L**ock-in good rate; **L**ag = wait when currency moves in your favor.

## Example: Mexico peso expected to depreciate 9% (Q8)

A US firm's Mexican subsidiary owes pesos to other Mexican vendors. Peso expected to depreciate 9% against USD.

- **Lag peso payables**: delay paying Mexican vendors → the same peso debt will cost less in USD next year
- **Lead peso receivables**: collect peso revenues quickly → convert to USD before peso loses value
- Plus consider shifting financing to peso-denominated debt (depreciation makes the real debt burden lower)

See [[../../questions/q08-mexico-peso-depreciation|Q8 page]].

## Why lead/lag is different from financial hedges

- **Financial hedge** (forward, swap, option) → locks in a rate via a contract, costs the bid-ask spread or a premium
- **Lead/lag** → operational adjustment, no contract needed, but requires control over payment timing (works best when you have leverage with suppliers/customers)

Multinationals typically combine both: use forwards for large/predictable exposures, use lead/lag for routine intercompany flows.

## See also

- [[hedging|Hedging — full coverage]]
- [[three-exposures|3 types of FX exposure]]
- [[../mnc-finance/index|MNC finance — broader money-management context]]
