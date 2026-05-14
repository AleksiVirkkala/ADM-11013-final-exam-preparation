---
title: Consolidation Exam Template (Step-by-Step)
---

> What the 21-pt question looks like, and the exact 12-step approach to solving it.

## What the exam question will look like

The teacher confirmed (Lecture 28): *"This is a practice that will be like we will have in the final exam."* The format closest to the actual exam is [[worked-inflationary|the Inflationary country exercise]] from Lecture 28.

You'll be given:

1. A balance sheet and income statement of a foreign subsidiary, in **local currency**
2. A list of exchange rates with descriptions (current, average, historical for inventory, historical for fixed assets, historical for capital, etc.)
3. The **functional currency** (e.g., "the functional currency is USD")
4. The **beginning-of-year retained earnings** (the only known reference point for RE)

You'll be asked to:

1. Convert the balance sheet and income statement to USD (or other home currency)
2. Compute and explicitly label the exchange rate **gain or loss**

## Timing

The exam is 2h 45min. Allocate ~45 minutes for consolidation (it's 21% of the points, slightly more time than proportional to allow for double-checking).

## 12-step approach

### Step 1: Read the problem twice
What's the functional currency? Which method does it imply? Which currency direction (X local per 1 USD, or X USD per 1 local)?

### Step 2: State the method at the top
Write at the top of your work: "Functional currency = [USD/local]; therefore [[temporal-method|Temporal]] / [[current-rate-method|Current Rate]] method."

### Step 3: List all exchange rates with their descriptions
Make a small reference table at the side of your paper so you don't have to flip back to the problem.

### Step 4: Determine conversion direction
- "X local per 1 USD" → divide local by rate
- "X USD per 1 local" → multiply local by rate

Write "÷" or "×" next to each rate in your reference table.

### Step 5: Fill in the balance sheet ASSETS
Row by row using the rate per [[temporal-method|Temporal]] or [[current-rate-method|Current Rate]] rules. Skip RE and Exchange Adjustment for now.

### Step 6: Sum the converted assets total
This is your **target** that liabilities + equity must match.

### Step 7: Fill in the balance sheet LIABILITIES + Capital
Convert Accounts Payable, Long-Term Debt at current rate; Capital at historical (IPO) rate.

### Step 8: Plug to balance
- **Temporal**: Solve for **Retained Earnings (USD, 31/12)** = Total assets − (AP + LTD + Capital, all in USD)
- **Current Rate**: First compute RE at the historical average rate, then **Exchange Adjustment** = Total assets − (AP + LTD + Capital + RE)

### Step 9: Fill in the income statement
Row by row using the income-statement rates per the method. Sum to get **operational result**.

### Step 10: Compute exchange rate gain/loss
- **Temporal**: FX gain/loss = ΔRE − Operational result, where ΔRE = (RE 31/12, plug) − (RE 1/1, given)
- **Current Rate**: Income-statement FX gain/loss is **N/A**. The cumulative effect is the Exchange Adjustment plug already on the balance sheet.

### Step 11: Label explicitly
Write "**gain**" or "**loss**" next to the number. Just "\$1,310" loses points.

### Step 12: Double-check
- Balance sheet: assets total = liabilities + equity total
- Income statement: operational + FX = total = ΔRE
- Signs make sense (loss when local currency depreciated badly; gain when it appreciated)

## What the answer sheet might look like

For an [[worked-inflationary|Inflationary country]] example (Temporal):

```
Method: Temporal (functional currency = USD)

BALANCE SHEET
Banks         1,200,000 ÷ 19.5  =     61,538
A/R           2,400,000 ÷ 19.5  =    123,077
Inventory     2,400,000 ÷ 18    =    133,333
Fixed Assets  3,000,000 ÷ 12    =    250,000
Depreciation  (600,000) ÷ 12    =   (50,000)
TOTAL ASSETS  8,400,000              517,948

A/P           2,000,000 ÷ 19.5  =    102,564
Debt          4,000,000 ÷ 19.5  =    205,128
Capital       2,000,000 ÷ 9.0   =    222,222
RE              400,000  (plug) =    (11,966)
TOTAL L+E     8,400,000              517,948  ✓

INCOME STATEMENT
Sales         4,000,000 ÷ 18    =    222,222
Cost of sales (1,900,000) ÷ 17  =   (111,765)
Depreciation  (190,000) ÷ 12    =    (15,833)
Other expenses (90,000) ÷ 18    =     (5,000)
Taxes         (150,000) ÷ 18    =     (8,333)
OPERATIONAL                          81,291

EXCHANGE RATE GAIN/LOSS:
  RE 31/12 (plug)  = ($11,966)
  RE 1/1 (given)   = ($50,000)
  ΔRE              = $38,034
  Operational      = $81,291
  FX = 38,034 - 81,291 = ($43,257) LOSS  ✓
```

## What to avoid

> [!warning]
> 1. **Don't pick the method yourself** — read what functional currency the teacher gave you
> 2. **Don't try to apply an exchange rate to the plug** — RE (under Temporal) or Exchange Adjustment (under Current Rate) is a plug, not rate-converted
> 3. **Don't forget the labeling** — write "gain" or "loss"
> 4. **Don't mix up cost of sales rate** under Temporal — uses **historical** (when inventory was purchased), NOT current
> 5. **Don't mix up depreciation rate** under Temporal — uses **same as fixed assets** (historical), NOT average
> 6. **Round to nearest dollar** — no cents/centavos
> 7. **Verify Operational + FX = ΔRE** at the end — if it doesn't match, you have an error somewhere

## See also

- [[temporal-method|Temporal method rules]]
- [[current-rate-method|Current Rate method rules]]
- [[exchange-gain-loss|Detailed FX gain/loss computation]]
- [[worked-uk-pounds|Worked example: UK Pounds (gain)]]
- [[worked-japanese-yen|Worked example: Japanese Yen (loss)]]
- [[worked-inflationary|Worked example: Inflationary country (likely exam format)]]
