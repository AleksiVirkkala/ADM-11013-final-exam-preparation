---
title: Current Rate Method
---

> Used when the functional currency is the **host (local) country's** currency. The subsidiary operates primarily in local terms. **Less volatile** results because the FX effect lives in the balance sheet, cumulative across all years.

## When to use

- Functional currency = host country currency (e.g., Pepsi Mexico sells soft drinks to Mexicans → functional = peso)
- Subsidiary is primarily a stand-alone operation in the local market

See [[functional-currency|Functional currency]] for full recognition rules.

## Balance sheet — exchange rate per row

| Account | Rate |
|---|---|
| Banks / Cash | **Current** (year-end) |
| Accounts Receivable | **Current** |
| Inventory | **Current** ← key difference from [[temporal-method\|Temporal]] |
| Fixed Assets | **Current** ← key difference |
| Accum. Depreciation | **Current** ← key difference |
| Accounts Payable | **Current** |
| Long-Term Debt | **Current** |
| Capital | **Historical** (when stock issued) ← only exception |
| Retained Earnings | **Historical average** (accumulated avg) |
| **Exchange Adjustment** | **PLUG** — force to balance |

> [!important] **Key principle:** Under Current Rate, monetary AND non-monetary items both use the current rate. Only stockholders' equity (capital, RE) uses historical. The "Exchange Adjustment" line plugs to balance.

## Income statement — exchange rate per row

All items use the **average rate for the year** — simpler than Temporal.

| Account | Rate |
|---|---|
| Sales | Average for year |
| Cost of sales | **Average for year** (not historical!) |
| Depreciation | **Average for year** (not historical!) |
| Other items | Average for year |
| Taxes | Average for year |
| Net income | Sales − all expenses |
| **Exchange gain/loss** | **N/A on income statement** — it's on the balance sheet |

## Where the FX gain/loss appears

> [!important] **Under Current Rate: FX adjustment appears on the BALANCE SHEET** as "Exchange Adjustment", **NOT** on the income statement.

This means:
- The adjustment is **cumulative** — it combines this year's FX effect with all prior years
- Less volatile because individual-year effects are blended into the cumulative number
- The income statement looks clean (no FX line)

## Why depreciation differs from Temporal

A student question Adam asked the teacher in Lecture 27:
> *"Why is depreciation in the income statement using the average for the year under current rate, but capital uses the historical rate?"*

Answer:
- **Depreciation** accrues throughout the year → use the average (consistent with current-rate philosophy that almost everything is "current")
- **Capital** was contributed at one specific historical date → preserve that rate to honor the original investor contribution amount
- This is also why depreciation in the **balance sheet** under current rate uses the current rate (cumulative), but depreciation in the **income statement** uses the average (flow during the year)

## How to compute the Exchange Adjustment (the plug)

1. Convert assets using their rates (mostly current rate)
2. Sum assets total
3. Convert liabilities + known equity (capital at historical, RE at historical average)
4. The remainder needed to balance the equation = Exchange Adjustment

> [!warning] For the exam: Income-statement FX gain/loss is **N/A** under Current Rate. Don't fabricate one. The cumulative effect lives on the balance sheet only.

## Worked example

[[worked-uk-pounds|UK Pounds — both methods]] shows the Current Rate result side-by-side with Temporal:
- Exchange Adjustment plug = **(\$26,540) loss** under Current Rate
- vs. **\$1,310 gain** on the income statement under Temporal

These numbers are NOT directly comparable (Temporal is just this year; Current Rate is cumulative across all years).

## Difference at a glance

|  | [[temporal-method\|Temporal]] | Current Rate |
|---|---|---|
| Non-monetary B/S items | Historical | **Current** |
| Cost of sales | Historical | Average |
| Depreciation in I/S | Historical (= fixed assets) | Average |
| Plug | RE | Exchange Adjustment |
| Where FX appears | I/S (current year) | B/S (cumulative) |
| Volatility | More | Less |
