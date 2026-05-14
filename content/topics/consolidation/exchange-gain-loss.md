---
title: Computing the Exchange Gain/Loss
---

> The part of the consolidation question that gets most of the points. The formula is simple — but the labeling matters as much as the number.

## The decomposition formula (memorize)

$$\text{Operational result} + \text{FX gain/loss} = \text{Total result}$$

Where **Total result = change in retained earnings during the year**:
$$\Delta RE = RE_{\text{31/12}} - RE_{\text{1/1}}$$

Rearranging:
$$\boxed{\text{FX gain/loss} = \Delta RE - \text{Operational result}}$$

## Procedure (Temporal method)

1. **Calculate ΔRE** = (Retained earnings 31/12, the plug figure on the balance sheet) − (Retained earnings 1/1, given in the problem)
2. **Calculate operational result** = sum of converted income statement BEFORE the FX line
3. **FX gain/loss = ΔRE − operational result**
4. **Label** the result:
   - Positive → write "**gain**"
   - Negative → write "**loss**" (and you can write it as a negative number in parentheses)

> [!danger] **MUST LABEL EXPLICITLY.** Just "\$1,310" is NOT enough — teacher will give zero credit. Must write "\$1,310 **gain**" or "(\$1,310) **loss**".

## Under Current Rate — no income-statement FX line

Under [[current-rate-method|Current Rate]]:
- The Exchange Adjustment is the **plug on the balance sheet** (not the income statement)
- The cumulative figure combines all prior years
- There's **no separate income-statement FX gain/loss** — write "N/A"

If a problem asks for the year's FX effect specifically under Current Rate, you'd compute the change in the cumulative Exchange Adjustment year-over-year. Class exercises usually just ask for the balance-sheet plug, not a separate income-statement number.

## Worked examples

### Example 1: UK Pounds (gain)

| Step | Value |
|---|---|
| Operational result (sum of I/S in USD) | \$34,230 |
| Retained earnings 1/1 (given) | \$40,000 |
| Retained earnings 31/12 (plug from balance sheet) | \$75,540 |
| ΔRE = 75,540 − 40,000 | **\$35,540** |
| FX effect = ΔRE − Operational = 35,540 − 34,230 | **+\$1,310 → GAIN** ✓ |

Full sheet: [[worked-uk-pounds|UK Pounds]].

### Example 2: Japanese Yen (loss)

| Step | Value |
|---|---|
| Operational result | \$273,034 |
| Retained earnings 1/1 (given) | \$50,000 |
| Retained earnings 31/12 (plug) | \$188,531 |
| ΔRE = 188,531 − 50,000 | **\$138,531** |
| FX effect = ΔRE − Operational = 138,531 − 273,034 | **(−\$134,503) → LOSS** ✓ |

The company lost more than **half** of its operational profit to FX. Full sheet: [[worked-japanese-yen|Japanese Yen]].

### Example 3: Inflationary country (loss — exam format!)

| Step | Value |
|---|---|
| Operational result | \$81,291 |
| Retained earnings 1/1 (given) | −\$50,000 (note: negative — cumulative losses) |
| Retained earnings 31/12 (plug) | −\$11,966 |
| ΔRE = (−11,966) − (−50,000) | **+\$38,034** |
| FX effect = ΔRE − Operational = 38,034 − 81,291 | **(−\$43,257) → LOSS** ✓ |

This is the format closest to the actual exam (teacher said so). Full sheet: [[worked-inflationary|Inflationary country]].

## Verification check

Always verify: Operational + FX = Total
- UK: \$34,230 + \$1,310 = \$35,540 ✓
- Yen: \$273,034 + (−\$134,503) = \$138,531 ✓
- Inflationary: \$81,291 + (−\$43,257) = \$38,034 ✓

## Why we separate the two effects

The conceptual point of the whole exercise: shareholders/the board need to know how much profit came from operations vs how much came from FX speculation.

Without this analysis, a company might think the subsidiary is profitable when actually operations made \$5K and FX windfalls made \$30K — in which case continuing investment might be unwise.

If you're earning millions in pesos but the peso is collapsing, your operations are profitable in pesos but you're losing money in USD. Different decision than if operations are weak but FX is a tailwind.

## Common pitfalls

> [!warning]
> 1. **Forgetting to label** — write "gain" or "loss" explicitly
> 2. **Wrong sign on ΔRE** — when RE goes from negative to less-negative, ΔRE is *positive*: (−11,966) − (−50,000) = **+38,034**, not −38,034
> 3. **Using the wrong RE** — RE 1/1 is GIVEN by the problem; RE 31/12 is the PLUG you computed
> 4. **Trying to find FX gain/loss before computing the operational result** — you can't; the formula requires both
> 5. **Confusing Current Rate's Exchange Adjustment with Temporal's FX gain/loss** — they're not the same:
>    - Temporal FX gain/loss = this year only, on income statement
>    - Current Rate Exchange Adjustment = cumulative across all years, on balance sheet
