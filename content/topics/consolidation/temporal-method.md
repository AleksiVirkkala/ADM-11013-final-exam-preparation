---
title: Temporal Method
---

> Used when the functional currency is the **home (investor) country's** currency. The subsidiary is essentially an extension of the parent. **More volatile** in results because the FX effect appears each year on the income statement.

## When to use

- Functional currency = home country currency (e.g., a Mexican maquiladora that exports to USA, functional = USD)
- Inflationary country (functional = USD because local currency can't be trusted)
- Commodity-priced subsidiary (e.g., silver mining, priced in USD globally)

See [[functional-currency|Functional currency]] for how to recognize.

## Balance sheet — exchange rate per row

| Account | Type | Rate to use |
|---|---|---|
| Banks / Cash | [[monetary-vs-non-monetary\|Monetary]] asset | **Current** (year-end) |
| Accounts Receivable | Monetary asset | **Current** |
| Inventory | Non-monetary asset | **Historical** (when acquired) |
| Fixed Assets | Non-monetary asset | **Historical** (when acquired) |
| Accum. Depreciation | Contra-asset | **Same as fixed assets** (historical) |
| Accounts Payable | Monetary liability | **Current** |
| Long-Term Debt | Monetary liability | **Current** |
| Capital / Stockholders' Equity | Equity | **Historical** (when stock issued / IPO) |
| **Retained Earnings** | Equity | **PLUG** — force to balance |
| Exchange Adjustment | — | **N/A** (not on B/S under Temporal) |

## Income statement — exchange rate per row

| Account | Rate |
|---|---|
| Sales | **Average** for year |
| **Cost of sales** | **Historical** average (when inventory was acquired) ← not current! |
| **Depreciation** | **Same rate as fixed assets** (historical) ← not average! |
| Other items | Average for year (default) |
| Taxes | Average for year |
| Operational result | Sum of above |
| **Exchange gain/loss** | Computed separately — appears HERE on income statement |
| Net income (total) | Operational result ± FX gain/loss |

## Why these specific rates?

| Item | Why historical rate |
|---|---|
| Fixed assets, inventory | Their cost basis was set at acquisition; market-value fluctuations aren't translated to USD year-by-year |
| Depreciation | It's just systematic recognition of the historical cost over time — must use the same rate as the underlying asset |
| Cost of sales | Reflects the cost of inventory consumed — that inventory was purchased at the historical inventory rate |
| Capital | Reflects original investor contribution — preserved at the rate when stock was issued |

## Where the FX gain/loss appears

> [!important] **Under Temporal: FX gain/loss appears on the INCOME STATEMENT**, not the balance sheet.

This means:
- You see **this year's** FX effect clearly, separate from operations
- More volatile year-over-year (no smoothing)
- Balance sheet "Exchange Adjustment" line = N/A

This is the conceptual point of Temporal method — it lets shareholders see the FX effect each year, separately from operations. Useful for boards deciding whether to stay in a country.

## Computing the FX gain/loss

$$\text{FX gain/loss} = \Delta RE - \text{Operational result}$$

Where ΔRE = (RE 31/12, the plug figure) − (RE 1/1, given).

**Then label "gain" or "loss" explicitly** — see [[exchange-gain-loss|exchange gain/loss]] for details and worked examples.

## Worked examples

- [[worked-uk-pounds|UK Pounds]] — small gain of \$1,310
- [[worked-japanese-yen|Japanese Yen]] — large loss of \$134,503
- [[worked-inflationary|Inflationary country]] — moderate loss of \$43,257; this is the **format closest to the exam**

## How Temporal differs from Current Rate

| Aspect | Temporal | [[current-rate-method\|Current Rate]] |
|---|---|---|
| Non-monetary items rate | Historical | Current |
| Income statement cost of sales | Historical | Average |
| Income statement depreciation | Historical (= fixed assets) | Average |
| Balance sheet plug | Retained Earnings | Exchange Adjustment |
| Where FX appears | Income statement | Balance sheet (cumulative) |
| Volatility | More | Less |
