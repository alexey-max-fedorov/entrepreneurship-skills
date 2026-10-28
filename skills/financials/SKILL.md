---
name: financials
description: "Builds, reads, forecasts, and audits basic business financials in plain founder terms: income statement (P&L), cash flow statement, balance sheet, and how they connect; revenue, COGS, gross/operating/net margin, operating expenses (SG&A), EBITDA, net income, fixed vs. variable costs, P/L forecasting, break-even, working capital (AR, AP, inventory), why profit is not cash, and using ratios to decide on hiring, expansion, loans, and price. Includes fill-in templates. Use when the user says 'financials', 'income statement', 'P&L', 'profit and loss', 'cash flow', 'balance sheet', 'break-even', 'financial projections', 'forecast my revenue', 'gross margin', 'EBITDA', 'profitable but no cash', 'can I afford to hire', 'do I need a loan', or wants to audit or fix a business's numbers. For setting price see pricing-models; for comparables and industry data see market-research; for the Revenue Streams and Cost Structure blocks see business-model."
metadata:
  version: 1.0.0
---

# Financials

You are an expert in basic business financials and simplified accounting for founders. Your goal is to help the user build, read, forecast, and audit the three financial statements (income statement, cash flow statement, balance sheet), find their margins, break-even point, and cash needs, and use those numbers to make real decisions, clearly and practically, without turning it into an accounting textbook.

## Required Reading — Load These Skills First

Before doing anything else, read the SKILL.md of every skill below that is not already in your context. Apply the same rule recursively to every skill you load (no limit; loading the whole library is fine). Never re-read a skill already in context. Only then proceed with the user's request. Skills are sibling folders: ../<skill-name>/SKILL.md

| Skill | Why it's required here |
|---|---|
| [problem-statement](../problem-statement/SKILL.md) | Library entry point; financial results feed the **Proceed / Pivot / Punt** decision it owns |
| [opportunity-id](../opportunity-id/SKILL.md) | **Opportunity screening** and the **profit filter**: whether a problem is worth solving for profit before you model it in detail |
| [business-model](../business-model/SKILL.md) | **Business model**, the **Revenue Streams** and **Cost Structure** canvas blocks that the P/L puts numbers on, and **pivoting** the model when the numbers fail |
| [pricing-models](../pricing-models/SKILL.md) | **Price**, choosing a pricing model, **markup vs. margin**, and how a price change affects quantity, revenue, and gross profit per unit (the price input to every forecast and break-even) |
| [market-research](../market-research/SKILL.md) | **Researching comparable businesses**, **industry data** (industry COGS and margins), and **market sizing** used to build and sanity-check revenue forecasts |
| [customer-segmentation](../customer-segmentation/SKILL.md) | **Customer segments** and the **beachhead market** whose demand drives your volume assumptions |
| [customer-validation](../customer-validation/SKILL.md) | **Customer validation**: testing whether the volume your key metric needs (for example, meals per day) actually exists |

## Before You Start

The deck this skill comes from opens with a Dilbert strip (Scott Adams): Dilbert admits he had no accurate numbers "so I just made up this one." The lesson of the whole session is **why we don't make them up.** Every number in a financial statement or forecast must trace to an actual record, a quote, a comparable business, or industry data.

Find out (or infer from context) before building anything:

1. **What job is this?** Build from scratch (pre-launch forecast), read or audit existing statements, explain a cash problem, or answer a specific decision (hire, expand, borrow, change price).
2. **Stage.** Idea or pre-launch (everything is a forecast) vs. operating (actuals exist; forecast from them).
3. **Reporting period.** Day, week, month, quarter, or year. Every P/L and cash flow statement covers one period; every balance sheet is one point in time.
4. **The unit.** What is one sale? (a meal, a pizza, an hour of coaching, a subscription month). You need it for COGS per unit, break-even, and key metrics.
5. **Price per unit.** If price is not set or is in question, settle it with (→ [pricing-models](../pricing-models/SKILL.md)).
6. **Costs.** A list of fixed / overhead costs (monthly) and variable costs per unit (materials + direct labor).
7. **Comparables and industry data.** Similar businesses' revenue and industry-average COGS / margins (→ [market-research](../market-research/SKILL.md)).
8. **Timing of cash.** Do customers pay later (accounts receivable)? Do you buy inventory ahead? Do suppliers give you terms (accounts payable)? Any equipment purchases?
9. **Financing.** Owner's investment, bank loans, other loans, credit cards, loan principal payment schedules.

If the business model or customer is still undefined, the numbers will be guesses stacked on guesses. The deck sits after entrepreneurship, ideas, market research and validating customer needs, and business model / value proposition, and asks "so what's next?" Financials come next, built on that work (→ [business-model](../business-model/SKILL.md)).

## Why Financial Statements Matter

**The puzzle that opens the topic:** a business shows **$50,000 profit** but has **$2,000 in the bank**. Why? You need financial statements to understand it. (The answer is in [Cash Flow: Profit ≠ Cash](#cash-flow-profit--cash).)

### Why founders need them

- **Seek funding** to launch the business
- **Know the funds required** to sustain the business
- **Identify your margins**
- **Determine your profitability**
- **Determine your cash flow**
- **Determine the value** of the business

### The what, are & how questions

Every one of these gets answered from financial statements:

- What does the company own
- What is its debt
- How do we earn revenue
- How much money did it / will it make
- How much can we borrow
- Are we in good shape / healthy
- Are we profitable enough
- How much have we invested
- How much have we earned over time
- What are we worth if we sold

## The Three Financial Statements at a Glance

There are **three primary financial statements**:

| Statement | Metaphor | What it shows | Time frame |
|---|---|---|---|
| **Income statement (P/L)** | **The movie** | How we did over a period of time: revenue minus expenses = profit or loss | A period (day, week, month, quarter, year) |
| **Balance sheet** | **The snapshot (a picture)** | What we own and owe right now, at this point in time | A single point in time |
| **Cash flow statement** | **The reality check** | Where the cash went: actual cash movement | A period |

### Which statement answers which question

| Question | Statement |
|---|---|
| What does the company own? | Balance sheet (assets) |
| What is our debt? | Balance sheet (liabilities) |
| Are we healthy? | Balance sheet; also check positive operating cash flow and net margin trending up (see [Using Financials to Make Decisions](#using-financials-to-make-decisions)) |
| Where does our revenue come from? / How do we earn revenue? | Income statement |
| How much profit did we make? / How much money did it make? | Income statement |
| How much will it make? | P/L forecast (a projected income statement) |
| Are we profitable enough? | Income statement margins (gross, operating, net) |
| Can we borrow more? / How much can we borrow? | Balance sheet / ratios |
| Do we / will we have enough cash? | Cash flow |
| Can we pay our bills? | Cash flow |
| How much have we invested? | Balance sheet owner's equity (owner's investment, stock); cash flow investing section for money spent on assets |
| How much have we earned over time? | Balance sheet retained earnings |
| What are we worth if we sold? | All three together. The deck names "determine the value of the business" as a core reason for statements but teaches no valuation method; do not invent one from this skill. |

## Income Statement (P/L)

The **income statement**, also called the **P/L** (profit and loss), **summarizes the revenues and expenses generated by the company over the entire reporting period.**

**Reporting periods:** day, week, month, quarter, year.

**Key question it answers:** *How much money did we make (or lose) during this period?*

### Income statement equation

```
Revenues − Expenses = Net income (+/−)
```

Net income can be positive (profit) or negative (loss).

### Anatomy of a P/L

Read top to bottom. Each line either adds a cost category or produces a subtotal.

| Line | What it is | Formula |
|---|---|---|
| **Revenue** | $ from selling product / service | Units sold × price |
| **COGS** (cost of goods sold) | Materials + direct labor in each unit sold | Variable cost per unit × units sold |
| **Gross profit ($)** | What is left after the direct cost of what you sold | Revenue − COGS |
| **Gross margin %** | Gross profit as a share of revenue | (Revenue − COGS) / Revenue |
| **Expenses** (operating expenses, **SG&A**) | Sales / marketing, G&A (rent, salaries, insurance) | Sum of operating expense lines |
| **EBITDA** | Earnings before interest, taxes, depreciation, amortization | Gross profit − Expenses |
| **ITDA** | Interest, taxes, depreciation, amortization | Sum of those four |
| **Net income** | The bottom line, after all expenses | EBITDA − ITDA |

Key definitions:

- **Revenue** is money earned from selling, not money received. A loan or an owner's investment is never revenue.
- **COGS** only includes costs that go into each unit sold: materials and the direct labor to make or deliver it. For a service, the direct labor is the COGS (in the coaching example below, the $20/hour paid to coaches is COGS).
- **Operating expenses / SG&A** (selling, general & administrative) are the costs of running the business whether or not a given unit sells: sales costs, marketing, truck lease, rent, insurance, payroll for non-direct staff.
- **EBITDA** is the operating result of the business before financing (interest), government (taxes), and the accounting spread of past asset purchases (depreciation, amortization).
- **Depreciation** spreads the cost of a physical asset (equipment, a truck build-out) over its useful life; **amortization** does the same for intangibles. Both are **non-cash**: the cash left when the asset was bought.
- **Net income (net profit)** is the bottom line.

### Margin % family

Every margin is a line divided by revenue.

| Margin | Formula | What it tells you |
|---|---|---|
| **Gross margin %** | Gross profit / Revenue | How much of each sales dollar survives the direct cost of the product |
| **Expense ratio** | Operating expenses / Revenue | How heavy overhead is relative to sales |
| **Operating profit margin** | Operating profit / Revenue. In this deck's simplified P/L, the operating line is EBITDA, so EBITDA / Revenue | Whether the core business makes money before financing and taxes |
| **Net profit margin** | Net income / Revenue | What share of each sales dollar is real bottom-line profit |

Simplified accounting note: formal statements usually subtract depreciation and amortization before reaching operating profit. The deck's founder version groups them into ITDA below EBITDA. Use one convention consistently and say which one you used.

### Example income statement (from the deck)

| Line item | Amount | Margin |
|---|---|---|
| Total revenue | $1,020,000 | |
| Total COGS | ($650,000) | |
| Gross profit | $370,000 | 36.3% |
| Total expenses | ($305,000) | 29.9% |
| EBITDA | $65,000 | 6.37% |
| Interest, taxes, depreciation, amortization | ($15,000) | |
| Net income (profit) | $50,000 | 4.9% |

Read it: a 36.3% gross margin, nearly 30 points of which goes to operating expenses, leaves a thin 6.37% EBITDA margin and 4.9% net margin. Small changes in COGS or overhead swing this business between profit and loss.

A service example (a campus soccer coaching service, one quarter): revenue 375 hrs × $40 = $15,000; COGS 375 hrs × $20 coach pay = ($7,500); gross profit $7,500; operating expenses marketing $900 + website $150 + insurance $300 = ($1,350); net income $6,150. **Gross margin 50%, net profit margin 41%.** (No ITDA lines, so EBITDA equals net income here.)

### Template: Simple Income Statement

```
INCOME STATEMENT (P/L): [Business name]
Reporting period: [day / week / month / quarter / year], [start date] to [end date]
Source of numbers: [actual records / forecast; cite comparables, quotes, industry data]

Line item                                  Amount        Margin (% of revenue)
-----------------------------------------  ------------  ---------------------
Revenue                                    $________     100%
   [Product / service line 1]              $________
   [Product / service line 2]              $________
Cost of goods sold (COGS)                  ($________)   ____%
   Materials in units sold                 ($________)
   Direct labor in units sold              ($________)
GROSS PROFIT  (Revenue − COGS)             $________     ____%   <- gross margin
Operating expenses (SG&A)                  ($________)   ____%   <- expense ratio
   Sales / marketing                       ($________)
   G&A: rent / lease                       ($________)
   G&A: salaries / payroll                 ($________)
   G&A: insurance                          ($________)
   Other: __________                       ($________)
EBITDA  (Gross profit − Expenses)          $________     ____%   <- operating margin (simplified)
ITDA                                       ($________)
   Interest                                ($________)
   Taxes                                   ($________)
   Depreciation                            ($________)
   Amortization                            ($________)
NET INCOME  (EBITDA − ITDA)                $________     ____%   <- net profit margin
```

Checks before you trust it:
- Revenue includes only sales (no loans, no owner money).
- COGS includes only per-unit materials and direct labor.
- Loan **principal** repayments are not on the P/L (only **interest** is).
- Equipment purchases are not expensed in full; only depreciation appears.

## P/L Forecasting

A forecast is a projected income statement. The deck's four steps, using a food truck:

1. **Find a similar business (food truck): research comparables, scale to your business.** Example: 6 food trucks do $1.8M in revenue; what does your one truck do? ($1.8M / 6 = $300K per truck on average. A brand-new truck may run below an established average, so scale, don't copy.) Finding the comparables is research (→ [market-research](../market-research/SKILL.md)).
2. **Use industry averages for COGS / margins.** Research says food trucks run COGS at 65%. What is gross margin %? **35% gross margin** (100% − 65%).
3. **List operating (SG&A) expenses:** sales costs, marketing, truck lease, rent, insurance, payroll.
4. **Compute:** revenue − (COGS + operating expenses) = **EBITDA**.

Stitched together from the deck's numbers: $300K revenue × 35% gross margin = $105K gross profit; operating expenses of $7,000/month (the deck's break-even figure) = $84K/year; EBITDA ≈ $21K (7% of revenue).

### Suggestions for forecasting

**Start with expenses, not revenues.**

- **Fixed / overhead** costs
- **Variable** costs
- **Why?** Expenses are the numbers you can actually pin down (quotes, leases, wage rates, supplier prices) while revenue is the most uncertain number in any plan. Fixed costs set the bar revenue must clear, and variable costs set how much each sale contributes toward clearing it. Get those right first and the revenue question becomes concrete: how many units do I need to sell? (That is [break-even](#break-even-analysis).)

**Then forecast revenues: conservative & aggressive.** Build at least two scenarios rather than one hopeful number.

- **Check key ratios:** gross margin, operating profit margin. Compare them with industry averages and comparables.
- **Check key metrics:** pizzas sold per day, or whatever the business's key unit metric is (meals per day, coaching hours per week, subscribers). Ask whether that number is physically and commercially achievable.

### Fixed vs. variable costs

| | **Fixed / overhead costs** | **Variable costs** |
|---|---|---|
| Behavior | Stay the same whether you sell 0 or 1,000 units in the period | Rise and fall with each unit sold |
| Food truck examples (deck) | Lease, insurance, wages: $7,000/month | Food cost per meal (COGS): $4.00 |
| Where they show on the P/L | Operating expenses (SG&A) | COGS |
| Role in break-even | The numerator: what must be covered | Subtracted from price to get gross profit per unit |

### Sanity-check your unit numbers against the industry

The deck's break-even example uses $4.00 food cost on a $12.00 meal: a 67% gross margin. The forecasting slide's industry average is 65% COGS: a 35% gross margin. Those cannot both describe the same truck. When your unit economics differ sharply from the industry average, find out why before you trust either (often the difference is what you count inside COGS, such as direct labor). The gap matters: at a 35% gross margin, gross profit per $12 meal is $4.20 and break-even becomes $7,000 / $4.20 = 1,667 meals/month (about 56/day on 30 days), nearly double the 875.

### Template: P/L Forecast

```
P/L FORECAST: [Business name]
Period: [month / quarter / year]    Operating days per month: ____
Unit: [meal / pizza / hour / subscription]    Price per unit: $____ (see pricing-models)

STEP 0  EXPENSES FIRST
Fixed / overhead (per month)                   Source
   Lease / rent              $______           [quote / lease]
   Insurance                 $______           [quote]
   Wages / payroll           $______           [rate × hours]
   Marketing                 $______           [plan]
   Other: _______            $______
   TOTAL FIXED               $______
Variable cost per unit (COGS)                  Source
   Materials                 $______           [supplier prices]
   Direct labor              $______           [rate × time per unit]
   TOTAL VARIABLE / UNIT     $______

STEP 1  COMPARABLES
   Comparable(s): __________   Revenue: $______ for ___ units/locations
   Scaled to one of mine: $______   Adjustment and why: __________

STEP 2  INDUSTRY AVERAGES
   Industry COGS %: ____%   Industry gross margin %: ____%   Source: ______
   My COGS % (variable cost / price): ____%   Gap explained by: __________

STEP 3  REVENUE SCENARIOS              CONSERVATIVE        AGGRESSIVE
   Key metric (units per day)          ______              ______
   Units per period                    ______              ______
   Revenue (units × price)             $______             $______
   COGS (units × variable cost)        ($______)           ($______)
   Gross profit                        $______             $______
   Gross margin %                      ____%               ____%
   Operating expenses (fixed)          ($______)           ($______)
STEP 4  EBITDA                         $______             $______
   Operating profit margin %           ____%               ____%
   ITDA (interest, taxes, dep., amort.)($______)           ($______)
   Net income                          $______             $______
   Net profit margin %                 ____%               ____%

CHECKS
   [ ] Key ratios vs. industry and comparables: ______
   [ ] Key metric achievable? (evidence): ______
   [ ] Break-even units per day: ____  vs. conservative units per day: ____
```

## Break-Even Analysis

**When does your business become profitable?** Break-even is the volume at which gross profit exactly covers fixed costs: net zero, no profit, no loss.

```
Break-even (units) = Fixed costs / (Price − Variable cost per unit)
```

`Price − Variable cost per unit` is the **gross profit per unit**: what each sale contributes toward fixed costs.

**Food truck (from the deck):**

| Input | Value |
|---|---|
| Op ex (fixed): lease, insurance, wages | $7,000/month |
| Variable cost per meal (COGS) | $4.00 |
| Price per meal (revenue) | $12.00 |
| Gross profit per meal | $8.00 |

**Break-even:** $7,000 / $8 = **875 meals/month (29 per day)**.

**Then ask the real question: can I do 29 meals a day?** Break-even turns an abstract profit question into a concrete key metric you can test against comparables, foot traffic, and customers (→ [customer-validation](../customer-validation/SKILL.md)).

Practical notes:
- The 29/day figure divides by 30 days. Divide by the days you actually operate: at 26 operating days, 875 meals is 34 per day.
- **Break-even revenue** = break-even units × price (875 × $12 = $10,500/month).
- Every unit above break-even adds its full gross profit per unit to profit; every unit below subtracts it.
- Break-even moves when price, variable cost, or fixed costs move. At an $11 price: $7,000 / ($11 − $4) = 1,000 meals/month. Whether to change the price, and how volume responds to it, belongs to (→ [pricing-models](../pricing-models/SKILL.md)).

### Template: Break-Even Calculation

```
BREAK-EVEN: [Business name], period: [month]

Fixed costs per period (lease, insurance, wages, rent, marketing...)   A = $________
Price per unit                                                         P = $________
Variable cost per unit (COGS: materials + direct labor)                V = $________
Gross profit per unit                                     P − V          = $________

Break-even units per period            A / (P − V)                       = ________ units
Operating days per period                                              D = ________
Break-even units per day               units / D                         = ________ per day
Break-even revenue per period          units × P                         = $________

Reality check
   Can I do ____ units a day?  Evidence: _______________________________
   Conservative forecast units/day: ____   Cushion above break-even: ____ units/day
   If price changes to $____: break-even = A / ($____ − V) = ____ units (see pricing-models)
   If fixed costs rise by $____: break-even = ($____) / (P − V) = ____ units
```

## Cash Flow: Profit ≠ Cash

Profit is an accounting result for a period. Cash is what is in the bank. They diverge whenever money moves at a different time than revenue or expense is recorded, or when cash moves that never touches the P/L (loans, principal, equipment).

### Cash flow equation

```
Cash from profit + Other sources of cash − Uses of cash = Change in cash
```

### Cash flow statement

The **cash flow statement shows how changes in the balance sheet and income affect cash, over a period of time.**

**Three main cash flow areas:**

| Area | What it covers | Typical lines |
|---|---|---|
| **Operating** | Cash from day-to-day business | Net income, depreciation added back (non-cash), changes in accounts receivable, inventory, accounts payable |
| **Investing** | Cash from buying / selling assets or investments | Purchase of equipment (−), sale of equipment (+) |
| **Financing** | Cash from loans, equity investments | Bank loan received (+), loan principal payments (−), owner / equity investment (+) |

### How each item hits cash vs. the P/L

| Item | On the P/L? | Effect on cash |
|---|---|---|
| Net income | Yes (bottom line) | Starting point of operating cash flow |
| Depreciation / amortization | Yes, as an expense | **Non-cash**: added back (+) |
| Increase in **accounts receivable (AR)**: sold, not collected yet | Revenue already counted | Uses cash (−) |
| Increase in **inventory**: paid for, not sold yet | Not expensed until sold (then COGS) | Uses cash (−) |
| Increase in **accounts payable (AP)**: received, not paid yet | Expense already counted | Source of cash (+) |
| Decrease in AR, inventory, or AP | | The opposite sign of an increase |
| Equipment purchase | Only depreciation appears, spread over time | Full price leaves in the investing section (−) |
| Bank loan received | Not revenue | Source of cash in financing (+) |
| Loan principal repaid | **Not a P/L expense** (only interest is) | Uses cash in financing (−) |
| Owner / equity investment | Not revenue | Source of cash in financing (+) |

### Working capital

**Working capital** items are the operating lines that sit between profit and cash: **accounts receivable, inventory, and accounts payable.** Growth makes them hungrier: more sales on credit means more AR waiting to be collected, and more volume means more inventory bought ahead. That is the **cash drag on the business due to working capital (WC)**. A growing, profitable business can run out of cash precisely because it is growing.

### Food truck cash flow statement (from the deck)

| Operating activities | |
|---|---|
| Net income | $50,000 |
| Depreciation (non-cash) | $8,000 |
| Increase in accounts receivable | −$30,000 |
| Increase in inventory | −$15,000 |
| Increase in accounts payable | $4,000 |
| **Cash from operating activities** | **$17,000** |

| Investing activities | |
|---|---|
| Purchase of equipment | −$10,000 |
| **Cash from investing activities** | **−$10,000** |

| Financing activities | |
|---|---|
| Bank loan received | $15,000 |
| Loan principal payments | −$8,000 |
| **Cash from financing activities** | **$7,000** |

**What is net change in cash?** $17,000 − $10,000 + $7,000 = **$14,000.**

### Why it matters: $50,000 profit, $2,000 in the bank

The deck's walk-through of where the profit went, section by section:

| Section | What happened | Cash effect | Cash left |
|---|---|---|---|
| Operating | Profit on the income statement | +$50,000 | $50,000 |
| Operating | AR: $30K owed, not collected yet | −$30,000 | $20,000 |
| Operating | Inventory: paid $15K, not sold yet | −$15,000 | $5,000 |
| Investing | Equipment: $10K (the P/L shows depreciation only) | −$10,000 | ($5,000) |
| Financing | Bank loan received | +$15,000 | $10,000 |
| Financing | Principal repaid (not a P/L expense) | −$8,000 | $2,000 |
| | **Cash in the bank** | | **$2,000** |

This walk-through is the simplified story. The full statement above also adds back $8,000 of non-cash depreciation and $4,000 of unpaid supplier bills (AP increase): $2,000 + $8,000 + $4,000 = the $14,000 net change. Either way, the lesson holds: half or more of a $50,000 profit is sitting in customers' unpaid invoices, unsold inventory, and equipment.

**This is the #1 reason even "profitable" startups fail.**

### Rules of cash flow

**Rule 1: Cash is king.**
- **Monitor cash flows closely.**
- **Plan for growth (finance AR / inventory).** Growth ties up cash in receivables and inventory before it pays off; arrange the funding before you grow, not after you run dry.
- **Account for cash drag on the business due to working capital (WC).**

**Rule 2: Under NO circumstances forget rule 1.**

### Template: Cash Flow Statement

```
CASH FLOW STATEMENT: [Business name]
Period: [start date] to [end date]

OPERATING ACTIVITIES
   Net income (from the P/L)                          $________
   + Depreciation / amortization (non-cash)           $________
   − Increase / + decrease in accounts receivable     $________
   − Increase / + decrease in inventory               $________
   − Increase / + decrease in prepaid expenses        $________
   + Increase / − decrease in accounts payable        $________
   + Increase / − decrease in payroll payable,
     sales tax payable, customer deposits             $________
   CASH FROM OPERATING ACTIVITIES                     $________

INVESTING ACTIVITIES
   − Purchase of equipment / property                 $________
   + Sale of equipment / property                     $________
   − / + Purchase / sale of investments               $________
   CASH FROM INVESTING ACTIVITIES                     $________

FINANCING ACTIVITIES
   + Bank loan / other loans received                 $________
   − Loan principal payments                          $________
   + Owner's investment / stock issued                $________
   − Profits taken out by owners                      $________
   CASH FROM FINANCING ACTIVITIES                     $________

NET CHANGE IN CASH  (operating + investing + financing)  $________
+ Cash at start of period                                $________
= CASH AT END OF PERIOD  (must equal balance sheet cash) $________
```

Optional cash walk (the deck's "why it matters" format), useful for explaining a gap between profit and the bank balance:

```
Section     | What happened                         | Cash effect | Cash left
------------|---------------------------------------|-------------|----------
Operating   | Profit on the income statement        | +$_____     | $_____
Operating   | AR: $____ owed, not collected yet     | −$_____     | $_____
Operating   | Inventory: paid $____, not sold yet   | −$_____     | $_____
Investing   | Equipment purchased                   | −$_____     | $_____
Financing   | Loan received                         | +$_____     | $_____
Financing   | Principal repaid (not a P/L expense)  | −$_____     | $_____
            | CASH IN THE BANK                      |             | $_____
```

## Balance Sheet

The **balance sheet** is **a snapshot of the company's financial position at a specific point in time.**

- **Assets:** what the company **owns**
- **Liabilities:** what the company **owes**
- **Owner's equity:** owner's investment + retained earnings

### Balance sheet equation

```
Assets = Liabilities + Owner's equity
```

**The equation MUST always balance.** If it doesn't, something is missing or double-counted; find it, never plug the gap.

### Assets: what the company owns

- **Cash**
- **Investments**
- **Prepaid expenses** (paid in advance, such as insurance paid for the year)
- **Accounts receivable (AR)** (customers owe you for sales already made)
- **Inventory**
- **Tangible property:** facilities, equipment (**PPE**: property, plant & equipment)
- **Intangible assets:** goodwill, patents, trademarks

### Liabilities: what the company owes

- **Accounts payable (AP)** (you owe suppliers for things already received)
- **Bank loans**
- **Loans from other sources**
- **Credit cards**
- **Payroll payable** (wages owed to employees)
- **Sales tax payable** (tax collected, owed to the state; it was never your money)
- **Customer deposits** (cash in before the work is done; you owe the work or the refund)

### Owner's equity: what the owner has put in and kept in

- **Owner's investment:** money put into the business
- **Stock:** common and preferred
- **Retained earnings:** profits kept in the business

### Layout: left side and right side

| Left side: assets | Right side: liabilities & equity |
|---|---|
| Cash | Debt (short-term, current portion of LTD, meaning long-term debt due within the year) |
| Accounts receivable | Long-term debt |
| Inventory | Accounts payable |
| PPE / FFE (furniture, fixtures & equipment) | **Equity:** owner's investment, stock (common, preferred), retained earnings |
| Leasehold improvements (build-outs to a space you lease) | |
| Notes receivable (current / long-term) | |
| Intangible assets | |

### Retained earnings

Net income from each P/L flows into **retained earnings**, where profits accumulate in equity over time:

```
Ending retained earnings = Beginning retained earnings + Net income for the period − Profits taken out of the business
```

### Template: Balance Sheet

```
BALANCE SHEET: [Business name]
As of: [date]   (one point in time)

ASSETS (what we own)                     LIABILITIES (what we owe)
Cash                      $________      Accounts payable (AP)          $________
Investments               $________      Credit cards                   $________
Prepaid expenses          $________      Payroll payable                $________
Accounts receivable (AR)  $________      Sales tax payable              $________
Inventory                 $________      Customer deposits              $________
Notes receivable (current)$________      Short-term debt / current
                                           portion of long-term debt    $________
PPE / FFE (net of                        Bank loans (long-term)         $________
  depreciation)           $________      Loans from other sources       $________
Leasehold improvements    $________      TOTAL LIABILITIES              $________
Notes receivable (long)   $________
Intangible assets                        OWNER'S EQUITY
  (goodwill, patents,                    Owner's investment             $________
   trademarks)            $________      Stock (common / preferred)     $________
                                         Retained earnings              $________
                                         TOTAL OWNER'S EQUITY           $________

TOTAL ASSETS              $________      TOTAL LIABILITIES + EQUITY     $________

CHECK: Total assets − (Total liabilities + Total equity) = $0   [ ] balances
CHECK: Cash here = ending cash on the cash flow statement       [ ]
CHECK: Retained earnings = prior RE + this period's net income − owner draws [ ]
```

## How the Three Statements Connect

All three statements are interconnected. Three links:

1. **Net income (P/L) → retained earnings (balance sheet):** profits accumulate in equity over time.
2. **Net income (P/L) → cash flow statement:** the starting point, adjusted for non-cash items and working capital.
3. **Net cash change (cash flow) → cash (balance sheet):** the cash balance updates each period.

```
 INCOME STATEMENT              RETAINED EARNINGS              BALANCE SHEET
 Revenue − expenses   ----->   Net income accumulates  ---->  Assets = liabilities
 = net income                  in equity over time            + owner's equity
        |                                                            ^
        | starting point for cash flow                               |
        v                                                            |
                               CASH FLOW                      CASH
                    ----->     Operating + investing  ---->   Net cash change updates
                               + financing                    cash on the balance sheet
```

Use the links as error checks: if net income on the P/L does not match the first line of operating cash flow, or ending cash does not match balance sheet cash, or the balance sheet does not balance, one of the statements is wrong.

## Financial Ratios and Key Metrics

Use financial ratios to make informed decisions. The ratios and metrics this deck uses:

| Ratio / metric | Formula | Statement | What it answers |
|---|---|---|---|
| **Gross margin %** | (Revenue − COGS) / Revenue | P/L | Is each sale profitable at the product level? Can the margin support more overhead? |
| **Expense ratio** | Operating expenses / Revenue | P/L | Is overhead too heavy for the sales volume? |
| **Operating profit margin** | Operating profit (EBITDA in the simplified P/L) / Revenue | P/L | Does the core business make money? |
| **Net profit margin** | Net income / Revenue | P/L | What share of sales becomes bottom-line profit? Is it trending up? |
| **Gross profit per unit** | Price − Variable cost per unit | P/L inputs | What each sale contributes to fixed costs |
| **Break-even units** | Fixed costs / (Price − Variable cost per unit) | P/L inputs | How much must we sell to stop losing money? |
| **Key unit metric** | Units per day (pizzas, meals, hours) | Operations | Is the volume the forecast needs actually achievable? |
| **Operating cash flow** | Cash from operating activities | Cash flow | Is day-to-day business producing or consuming cash? |
| **Months of bills covered** | Cash / monthly bills | Balance sheet + cash flow | Will cash cover the next 3 months of bills? |
| **What we owe vs. own and equity** | Liabilities against assets and owner's equity | Balance sheet / ratios | Can we borrow more? |

Compare ratios against comparables and industry averages, and against your own prior periods (trend).

## Using Financials to Make Decisions

The point of the statements is the decision. Each common founder question maps to a specific check:

| Decision | What to check | Statement |
|---|---|---|
| **Should I hire another employee?** | Can my gross margin support another $50K salary + benefits? Divide the added annual cost by gross profit per unit to see how many extra units you must sell. | P/L, break-even |
| **Should I expand to a second location?** | Do I have cash flow to cover startup costs and initial losses? | Cash flow, P/L forecast for the new location |
| **Is my business healthy?** | Positive operating cash flow? Net margin trending up? | Cash flow, P/L over several periods, balance sheet |
| **Should I lower my price?** | What happens to my margin and break-even point? Recalculate gross profit per unit and break-even at the new price; how volume responds is a pricing question (→ [pricing-models](../pricing-models/SKILL.md)). | P/L, break-even |
| **Do I need a loan?** | Will my cash cover the next 3 months of bills? | Cash flow forecast, balance sheet |

If the numbers say the business cannot work at any realistic volume, that is evidence for the Proceed / Pivot / Punt decision (→ [problem-statement](../problem-statement/SKILL.md)) and for pivoting the model (→ [business-model](../business-model/SKILL.md)).

## Workflow

1. **Define the job and period.** What decision or deliverable, which reporting period, forecast or actuals.
2. **Collect real inputs; never make numbers up.** Records, quotes, leases, supplier prices, wage rates, comparables, industry averages. Label every number with its source.
3. **Start with expenses.** List fixed / overhead costs per period and variable cost per unit (materials + direct labor).
4. **Set the unit and price.** Confirm price with pricing-models if it is not settled.
5. **Forecast revenue in two scenarios.** Conservative and aggressive, anchored to comparables scaled to your business and a key unit metric.
6. **Build the P/L.** Revenue → COGS → gross profit → operating expenses → EBITDA → ITDA → net income. Compute gross, operating, and net margins.
7. **Run break-even.** Fixed costs / (price − variable cost per unit); convert to units per operating day; ask "can I do that?"
8. **Check key ratios and metrics** against industry averages and comparables. Explain any large gap.
9. **Build the cash flow statement.** Start from net income; add back depreciation; adjust for AR, inventory, AP; add investing (equipment) and financing (loans, principal, owner investment). Compare cash against the next 3 months of bills.
10. **Build the balance sheet.** Assets = liabilities + owner's equity. It must balance.
11. **Tie the statements together.** Net income → retained earnings; net income → top of cash flow; ending cash → balance sheet cash.
12. **Answer the decision.** Use the decision table. State the answer under both scenarios and the trigger that would change it.
13. **Report clearly.** Show the statements, the margins, break-even, cash cushion, the assumptions with sources, and the biggest risk in the numbers.

## Common Mistakes

- **Making numbers up.** A forecast with no comparables, quotes, or industry data behind it is the Dilbert chart. Every number needs a source.
- **Treating profit as cash.** The $50,000-profit, $2,000-in-the-bank business. Profit ≠ cash; always build the cash flow.
- **Starting with revenue.** Forecasting sales first invites wishful thinking; start with expenses.
- **One scenario only.** Always forecast conservative and aggressive.
- **Top-down revenue guesses** ("if we get 1% of the market") instead of comparables scaled to your business and a key unit metric you can test.
- **Mixing COGS and operating expenses.** COGS is only materials + direct labor in each unit sold; rent, marketing, insurance, and overhead salaries are operating expenses. Misclassifying distorts gross margin and break-even.
- **Counting loans or owner money as revenue.** They are financing, not sales.
- **Expensing loan principal on the P/L.** Only interest is a P/L expense; principal is a financing cash outflow.
- **Expensing equipment in full.** The P/L shows depreciation; the cash goes out in the investing section.
- **Forgetting depreciation is non-cash.** It reduces profit but not cash; add it back in operating cash flow.
- **Ignoring working capital.** Growth in AR and inventory eats cash; plan to finance it before you grow.
- **A balance sheet that doesn't balance,** or one "fixed" with a plug number. It must always balance; find the error.
- **Confusing period and point in time.** P/L and cash flow cover a period; the balance sheet is one date.
- **Break-even with the wrong denominator.** Divide fixed costs by price minus variable cost per unit, not by price alone and not by total costs.
- **Never asking "can I do that many?"** Break-even is only useful once you test the units-per-day figure against reality.
- **Ignoring industry benchmarks.** Unit economics far better than the industry average usually mean a missing cost, not a miracle.
- **Deciding from net income alone.** Hiring, expanding, and borrowing decisions need gross margin, cash flow, and a 3-month cash cushion check.

## Worked Examples

### Positive example: a one-truck taco business planning year 1

**Situation.** Maya is launching one taco truck in Houston and needs to know whether it works, how much cash she needs, and when she can hire.

**1. Expenses first (sourced).**
- Fixed per month: truck lease $2,000 (lease quote), commissary kitchen + parking $900 (commissary rate sheet), insurance $400 (quote), permits / POS / software $200, one helper's wages $3,500 → **$7,000/month**.
- Variable per meal: ingredients $3.50 + packaging $0.50 (supplier price list) → **$4.00**.
- Price: $12.00 per meal, set with pricing-models.

**2. Comparables and industry data.** 6 local trucks do $1.8M a year → about $300K per established truck, about 80 meals/day at $12 over 26 operating days. She uses that as her **aggressive** ceiling, not her base. Industry COGS is 65%; her food-only COGS is 33%. She checks why: the comparables likely count direct labor in COGS (materials + direct labor), while her helper sits in fixed costs. Moving the helper's $3,500 into COGS puts her conservative COGS at 58%, close to the industry figure, so her plan is credible and she compares like with like.

**3. Monthly P/L forecast (26 operating days).**

| | Conservative (45 meals/day) | Aggressive (80 meals/day) |
|---|---|---|
| Meals | 1,170 | 2,080 |
| Revenue | $14,040 | $24,960 |
| COGS ($4/meal) | ($4,680) | ($8,320) |
| Gross profit | $9,360 (66.7%) | $16,640 (66.7%) |
| Operating expenses | ($7,000) | ($7,000) |
| EBITDA | $2,360 (16.8%) | $9,640 (38.6%) |
| ITDA (interest $100, depreciation $167, taxes $233) | ($500) | ($500) |
| Net income | $1,860 (13.2%) | $9,140 (36.6%) |

**4. Break-even.** $7,000 / ($12 − $4) = 875 meals/month = **34 meals/day** on 26 days (break-even revenue $10,500). Her conservative case is 11 meals/day above break-even. She tests the "45 a day" assumption by counting lunch traffic at two target spots and running two pop-up days before signing the lease.

**5. First-quarter cash flow (conservative).**

| Operating | |
|---|---|
| Net income (3 × $1,860) | $5,580 |
| Depreciation (non-cash) | $500 |
| Increase in AR (office catering invoiced net 30) | −$3,000 |
| Increase in inventory | −$1,500 |
| Increase in AP (supplier net 15) | $1,000 |
| **Cash from operating** | **$2,580** |
| **Investing:** equipment | **−$10,000** |
| **Financing:** owner's investment $14,500 + bank loan $15,000 − principal $750 | **$28,750** |
| **Net change in cash** (starting from $0) | **$21,330** |

Her first draft used a $12,000 owner's investment and ended at $18,830, short of 3 months of fixed bills ($21,000). She raised her own investment to $14,500 so cash covers the next 3 months of bills even if sales stall.

**6. End-of-quarter balance sheet.**

| Assets | | Liabilities & equity | |
|---|---|---|---|
| Cash | $21,330 | Accounts payable | $1,000 |
| Accounts receivable | $3,000 | Bank loan ($15,000 − $750) | $14,250 |
| Inventory | $1,500 | Owner's investment | $14,500 |
| Equipment ($10,000 − $500 depreciation) | $9,500 | Retained earnings | $5,580 |
| **Total assets** | **$35,330** | **Total liabilities + equity** | **$35,330** |

It balances; net income ($5,580) equals retained earnings, and ending cash equals the cash flow result.

**7. Decisions.** A second employee at $50K salary costs $4,167/month before benefits: $4,167 / $8 = 521 more meals a month, about 20 more per day. She writes the trigger: hire only after three straight months above 55 meals/day with positive operating cash flow. A second truck waits until operating cash flow can fund its startup costs and initial losses.

**Why this is good:**
- Every number has a source; nothing is made up.
- Expenses came first, then two revenue scenarios anchored to scaled comparables.
- She reconciled her unit economics with the industry average instead of ignoring the gap.
- Break-even was converted to meals per operating day and tested against reality.
- The cash flow caught a shortfall the P/L could not show, and she fixed it before launch.
- All three statements tie out, and each decision has a numeric trigger.

### Negative example: a coffee cart pitch to a bank

**Situation.** Jordan wants a $25,000 loan for a specialty coffee cart and brings this:

> "If just 1% of the city buys a $6 latte once a week, that's $180,000 a year. Costs are about $60,000, so profit is $120,000. Year 1 we'll show at least $50,000 profit even if we're slow. The $25,000 loan is in revenue for month 1. Loan payments of $500/month are in expenses. Break-even is $60,000 / $6 = 10,000 lattes. Balance sheet: assets $40,000, liabilities $25,000, equity $10,000, plus $5,000 other to make it balance. With $50K profit I'll hire a $50K barista and sign the second location lease in month 6."

Six months later the P/L shows profit, but the bank account holds $2,000: two corporate offices pay catering on net-60 terms, and $8,000 went into a bulk bean prepurchase.

**Why this is bad:**
- **Made-up, top-down revenue.** "1% of the city" has no comparables, no key metric, no source. This is the Dilbert chart.
- **Revenue first, one scenario.** No expenses-first build and no conservative vs. aggressive case.
- **"Costs" lumped together.** No COGS vs. operating expenses split, so no gross margin, no operating margin, nothing to compare with industry averages.
- **Loan counted as revenue** and **principal counted as an expense.** Financing is not sales, and principal is not a P/L expense; both distort profit.
- **Break-even divides total costs by price** instead of fixed costs by (price − variable cost per unit), so it understates the volume needed.
- **A balance sheet with a plug.** "$5,000 other to make it balance" means an error is hidden, not fixed.
- **Profit treated as cash.** AR from net-60 catering and inventory from the bean prepurchase drained cash: the #1 reason even "profitable" startups fail.
- **Decisions without the right checks.** Hiring needs gross margin to support $50K + benefits; a second location needs cash flow for startup costs and initial losses; neither was checked, and cash would not cover the next 3 months of bills.

## Related Skills & Next Steps

- **[problem-statement](../problem-statement/SKILL.md)** — When the numbers say the venture can't work at a realistic volume and you need the Proceed / Pivot / Punt decision.
- **[opportunity-id](../opportunity-id/SKILL.md)** — When you need to screen whether an opportunity is worth solving for profit before building detailed financials.
- **[business-model](../business-model/SKILL.md)** — When the Revenue Streams or Cost Structure must change, or the model needs a pivot to reach a workable margin.
- **[pricing-models](../pricing-models/SKILL.md)** — When price is unset, or you're asking "should I lower (or raise) my price?" and need volume, revenue, and gross profit per unit effects.
- **[market-research](../market-research/SKILL.md)** — When you need comparable businesses, industry COGS and margin averages, or market size to ground a forecast.
- **[customer-segmentation](../customer-segmentation/SKILL.md)** — When volume assumptions depend on which segment or beachhead market you serve first.
- **[customer-validation](../customer-validation/SKILL.md)** — When break-even hinges on a key metric (meals per day, customers per week) that you must prove real customers will deliver.
