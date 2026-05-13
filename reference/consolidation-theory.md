# Consolidation of Financial Statements — Master Guide

> **Worth 21 points on the final exam.** The single biggest question. Use this guide to fill in the exam paper independently.

---

## What you're being tested on

Given a foreign subsidiary's balance sheet and income statement in the local currency, plus a list of exchange rates and the **functional currency**, you must:

1. **Choose the method** (Temporal or Current Rate) based on the functional currency
2. **Apply the correct exchange rate to each row** to convert to home currency (usually USD)
3. **Plug the balancing figure** to make the balance sheet balance — **Temporal: plug RE; Current Rate: plug Exchange Adjustment**
4. **Compute and label** the exchange rate gain/loss — **must write "gain" or "loss" explicitly**
5. **Decompose** total result into operational result + forex effect

---

## Step 1 — Choose the method based on functional currency

The teacher will tell you the functional currency. You must decide which method to use.

| Functional currency = | Method to use |
|---|---|
| **Home (investor) country currency** (e.g., USD for a US multinational) | **Temporal method** |
| **Host (local) country currency** (e.g., Mexican peso for a Mexican subsidiary that sells locally) | **Current Rate method** |

### How to recognize each in real-world clues (in case teacher just describes the subsidiary):
- Sells to home country, uses home-currency inputs (e.g., a Mexican *maquiladora* exporting to USA) → functional currency = USD → **Temporal**
- Sells in local market, pays local salaries (e.g., Pepsi Mexico selling soft drinks to Mexicans) → functional currency = local peso → **Current Rate**
- High inflation / unstable country (e.g., Venezuela) → functional currency = USD → **Temporal** (because local currency can't be trusted)
- Commodity-priced internationally (e.g., Peñoles silver mining, silver priced in USD globally) → functional currency = USD → **Temporal**

> **On the exam:** Teacher said he'll give you the functional currency directly. Your job is to convert it into the correct method.

---

## Step 2 — Distinguish monetary vs non-monetary items

**Monetary items** = cash equivalents, highly liquid. Their value doesn't change with the market — they represent fixed amounts of currency.

**Non-monetary items** = not liquid; their value can fluctuate with the market.

### Classification cheat sheet:

| Item | Monetary? |
|---|---|
| Banks / Cash | **Monetary** (yes — it's literally cash) |
| Accounts receivable | **Monetary** (fixed amount someone owes you) |
| Inventory | **Non-monetary** (market value can change) |
| Fixed assets (machinery, equipment, buildings) | **Non-monetary** |
| Accumulated depreciation | Same treatment as fixed assets (it's a contra-asset against fixed assets) |
| Accounts payable | **Monetary** (fixed amount you owe) |
| Long-term debt | **Monetary** (debt denominated in fixed amount) |
| Capital (stockholder equity) | **Non-monetary** — but always uses **historical** rate (when stock was issued) |
| Retained earnings | ⚠️ **Depends on method:** Under **Temporal** → RE is the **plug figure** (forced to balance; no exchange rate applied). Under **Current Rate** → RE uses **historical (accumulated avg) rate** |
| Exchange adjustment | Under **Temporal** → not applicable (RE is the plug). Under **Current Rate** → this IS the **plug figure** (forced to balance) |

---

## Step 3 — Apply the correct exchange rate to each row

### TEMPORAL METHOD (functional currency = home country)

Used when subsidiary is essentially an extension of the home country. More volatile in results.

| Account type | Exchange rate to use |
|---|---|
| **Banks / Cash (monetary asset)** | Current rate (year-end, e.g., 31/12) |
| **Accounts receivable (monetary asset)** | Current rate (year-end) |
| **Inventory (non-monetary asset)** | Historical rate when inventory was acquired |
| **Fixed assets (non-monetary asset)** | Historical rate when fixed asset was acquired |
| **Accum. depreciation (contra-asset)** | Same as fixed assets (historical) |
| **Accounts payable (monetary liability)** | Current rate (year-end) |
| **Long-term debt (monetary liability)** | Current rate (year-end) |
| **Capital / Stockholders' equity** | Historical rate when stock was issued (IPO date) |
| **Retained earnings** | **Plug figure** — calculate so balance sheet balances |
| **Exchange adjustment (balance sheet)** | **N/A** — not reported on balance sheet under temporal method |

### Income statement under TEMPORAL:

| Account | Exchange rate to use |
|---|---|
| **Sales** | Average for the year |
| **Cost of sales** | Historical average for cost of sales (when inventory was purchased) |
| **Depreciation expense** | Same rate as fixed assets (historical) |
| **Other items / Other expenses** | Average for the year (default if not specified) |
| **Taxes** | Average for the year (paid periodically all year) |
| **Operational result** | Sales minus all expenses |
| **Exchange gain/loss** | Calculated separately, ON the income statement |
| **Net income** | Operational result ± exchange gain/loss |

### CURRENT RATE METHOD (functional currency = local country)

Used when subsidiary operates primarily in local currency. Less volatile in results because most items use the current rate.

| Account type | Exchange rate to use |
|---|---|
| **Banks / Cash** | Current rate (year-end) |
| **Accounts receivable** | Current rate |
| **Inventory** | Current rate |
| **Fixed assets** | Current rate |
| **Accum. depreciation** | Current rate |
| **Accounts payable** | Current rate |
| **Long-term debt** | Current rate |
| **Capital / Stockholders' equity** | Historical rate (when stock was issued) |
| **Retained earnings** | Historical average for retained earnings |
| **Exchange adjustment (balance sheet)** | **Plug figure** — calculate so balance sheet balances |

> **Key difference:** Under current rate, monetary AND non-monetary items both use the current rate. Only stockholders' equity stays at historical.

### Income statement under CURRENT RATE:

All items use the **average exchange rate for the year** (or specific period rates if given), including depreciation. Simpler than temporal.

| Account | Exchange rate to use |
|---|---|
| **Sales** | Average for the year |
| **Cost of sales** | Average for the year |
| **Depreciation expense** | Average for the year |
| **Other items** | Average for the year |
| **Taxes** | Average for the year |
| **Net income** | Sales minus all expenses |
| **Exchange gain/loss** | **N/A on income statement** — it's on the balance sheet as "exchange adjustment" |

---

## Step 4 — Where the exchange rate gain/loss appears differs by method

### TEMPORAL METHOD
- Exchange gain/loss goes on the **INCOME STATEMENT**
- Shows only **this year's** FX effect
- More volatile — you see the FX impact clearly each year
- On the balance sheet, "Exchange adjustment" = N/A

### CURRENT RATE METHOD
- Exchange gain/loss goes on the **BALANCE SHEET** as "Exchange adjustment"
- **Cumulative** — combines all prior years' FX effects with this year's
- Less volatile because it's hidden in the balance sheet
- On the income statement, "Exchange gain/loss" = N/A

**Why the difference matters:**
- The income statement closes out at year-end (resets to zero each year)
- The balance sheet is continuous from day one of the business
- Showing exchange effect on income statement → see it just for this year (Temporal)
- Showing on balance sheet → it accumulates with all prior years (Current Rate)

---

## Step 5 — How to compute the exchange rate gain/loss

This is the part that gets confusing. Here's the systematic method:

### Method A: Decomposition from retained earnings (cleanest for Temporal; use with care under Current Rate)

> Under the **Current Rate** method, the FX effect flows through the cumulative **Exchange Adjustment** on the balance sheet, not through income-statement RE. The decomposition below still works algebraically, but be aware that the "total result" for Current Rate includes the exchange adjustment change, not just RE change.

**Formula:**
$$\text{Operational result} + \text{Forex gain/loss} = \text{Total result}$$

Where:
- **Operational result** = (Sales − Expenses) in converted USD (the bottom of the income statement, BEFORE the FX line)
- **Total result** = Change in retained earnings during the year = (Retained earnings 31/12) − (Retained earnings 1/1)
- **Forex gain/loss** = Total result − Operational result

**Procedure:**
1. Calculate the change in retained earnings (Δ RE) = end-of-year RE − beginning-of-year RE
2. Calculate operational result (sum of converted income statement before the FX line)
3. Forex gain/loss = Δ RE − Operational result
4. **Label it explicitly as "gain" (positive) or "loss" (negative)**

### Worked example (UK Pounds, Temporal Method)

- Operational result (sales - all expenses) in USD = **$34,230**
- Retained earnings 1/1 = **$40,000** (given)
- Retained earnings 31/12 = **$75,540** (computed as the plug figure on the balance sheet)
- ΔRE = 75,540 − 40,000 = **$35,540**
- Forex effect = 35,540 − 34,230 = **+$1,310 → GAIN**

### Worked example (Inflationary Country, Temporal Method)

- Operational result = **$81,291**
- Retained earnings 1/1 = **−$50,000** (a loss; given)
- Retained earnings 31/12 = **−$11,966** (plug figure)
- ΔRE = (−11,966) − (−50,000) = **+$38,034**
- Forex effect = 38,034 − 81,291 = **−$43,257 → LOSS**

### Worked example (Japanese Yen, Temporal Method)

- Operational result = **$273,034**
- Retained earnings 1/1 = **$50,000**
- Retained earnings 31/12 = **$188,531** (plug figure)
- ΔRE = 188,531 − 50,000 = **$138,531**
- Forex effect = 138,531 − 273,034 = **−$134,503 → LOSS**

---

## Step 6 — Make sure the balance sheet balances

**Assets total must equal Liabilities + Equity total.**

The plug figure (retained earnings under temporal; exchange adjustment under current rate) is calculated by:

1. Convert all other rows using their specified exchange rates
2. Sum up the converted assets → that's your target total
3. Sum up the converted liabilities and known equity (capital)
4. The remaining gap is the plug figure

---

## Working format / template for the exam

The exam paper will look like the UK Pounds template you've practiced with. Suggested approach:

1. **Read the problem statement** — identify functional currency, get the method
2. **Write down the method** at the top of each column (Temporal Method or Current Rate Method)
3. **List all exchange rates** with their descriptions on the side for reference
4. **Fill in the balance sheet assets** row by row using the correct rate
5. **Sum the converted assets total**
6. **Fill in liabilities** EXCEPT retained earnings (and exchange adjustment if current rate)
7. **Plug** to balance
8. **Fill in the income statement** row by row
9. **Sum operational result**
10. **Compute exchange rate gain/loss** using Method A above
11. **Explicitly label "gain" or "loss"**
12. **Double-check totals balance**

---

## Common pitfalls to avoid (teacher's warnings)

1. **Multiplication vs division.** Convert the right way!
   - If exchange rate is **X local currency per 1 USD** (e.g., 109 yen/USD), then to convert local → USD you **divide** by the rate
   - If exchange rate is **X USD per 1 local currency** (e.g., $1.49/pound), then to convert local → USD you **multiply** by the rate
   - Teacher said: "Students make this mistake more than you'd think; lose all 16-21 points"

2. **Don't forget to label gain or loss.** Just writing "$1,310" loses you credit. Must say "$1,310 gain" or "$1,310 loss".

3. **Don't pick the method yourself.** The teacher specifies the functional currency; you derive the method from it.

4. **The balancing figure is a plug — don't convert it with an exchange rate.** Under Temporal, RE is the plug. Under Current Rate, Exchange Adjustment is the plug. Force whichever one to balance.

5. **"Other items" with no specified rate** → use the average for the year (default assumption).

6. **Round to the nearest dollar/unit** — don't include cents/centavos. Small rounding differences (a few dollars) are immaterial.

7. **Cost of sales uses the historical average for inventory** (NOT current rate), under temporal method.

8. **Depreciation expense uses the same rate as fixed assets** (historical), under temporal method.

9. **Capital always uses historical rate** under BOTH methods. The exchange effect on capital is reflected in the adjustment line, not the capital line itself.

10. **Make sure to read the problem twice.** What is the functional currency? Which exchange rate is which?

---

## Quick visual: row-by-row exchange rate chart

| Row | Type | Temporal rate | Current Rate rate |
|---|---|---|---|
| Banks / Cash | Monetary asset | Current | Current |
| Accounts Receivable | Monetary asset | Current | Current |
| Inventory | Non-monetary asset | Historical (acquisition) | Current |
| Fixed Assets | Non-monetary asset | Historical (acquisition) | Current |
| Accum. Depreciation | Contra-asset | Same as fixed assets | Current |
| Accounts Payable | Monetary liability | Current | Current |
| Long-Term Debt | Monetary liability | Current | Current |
| Capital | Equity | Historical (issuance) | Historical (issuance) |
| Retained Earnings | Equity | **Plug** | Historical avg |
| Exchange Adjustment | Equity | **N/A** | **Plug** |
| Sales | Income | Average for year | Average for year |
| Cost of Sales | Expense | Historical (cost of sales) | Average for year |
| Depreciation | Expense | Same as fixed assets | Average for year |
| Other items | Expense | Average for year | Average for year |
| Taxes | Expense | Average for year | Average for year |
| Exchange Gain/Loss | — | **On income statement** | **N/A** (on balance sheet) |

---

## Why this exists / managerial relevance

> Be ready to explain this in essay form too:

You need to disaggregate the two effects in the subsidiary's results:
1. **Operational effect** — actual results from operations in the foreign market
2. **Exchange rate effect** — gain/loss from currency movements

A multinational might have great operations but lose all the profit to FX devaluation (or vice versa). The board of directors needs to know which is which to decide:
- Stay in this country or pull out?
- Invest more or contract?
- Hedge our currency exposure?

If you're earning millions in pesos but the peso is collapsing, your operations are profitable in pesos but you're losing money in USD — it's no longer a good investment.

---

## Cross-references

- **Theory paper from teacher**: *Admon. Internacional Fin. Stmt. Consol (ENG)* (original source)
- **Lectures 26-28** for worked examples: [L26](../lectures/lecture-26-consolidation-temporal.md), [L27](../lectures/lecture-27-current-rate-method.md), [L28](../lectures/lecture-28-inflationary-country.md)
- **Worked exercises**:
  - [UK Pounds balance](../exercises/uk-pounds-balance.md) — both methods
  - [Japanese Yen balance](../exercises/japanese-yen-balance.md) — both methods
  - [Inflationary country balance](../exercises/inflationary-country-balance.md) — temporal method
- **Chapter 20** background on Lessard-Lorange and accounting controls: [chapters/chapter-20-finance-mnc.md](../chapters/chapter-20-finance-mnc.md)
