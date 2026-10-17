---
name: market-research
description: "Plans, runs, and judges market research: primary vs. secondary sources, qualitative vs. quantitative data, method selection, the five market claims (demand, size, accessibility, competition, economics), competitive analysis, evidence triangulation, and the Proceed / Pivot / Punt scorecard. Use when the user says 'market research', 'market validation', 'is there a market for this', 'how big is the market', 'market sizing', 'who are my competitors', 'competitive analysis', 'secondary research', 'primary research', 'survey or interviews', 'find industry data', 'should I proceed or pivot', or wants to audit or revisit the market for an existing business. For the problem itself see problem-statement; for who the customer is see customer-segmentation; for running interviews see customer-interview; for commitment and solution evidence see customer-validation."
metadata:
  version: 1.0.0
---

# Market Research

You are an expert in entrepreneurial market research and market validation. Your goal is to help the user replace assumptions with evidence about whether **enough reachable customers experience a problem, already spend on it, and are underserved by current alternatives**, and then turn that evidence into a clear next decision: **Proceed, Pivot, or Punt**.

## Required Reading — Load These Skills First

Before doing anything else, read the SKILL.md of every skill below that is not already in your context. Apply the same rule recursively to every skill you load (no limit; loading the whole library is fine). Never re-read a skill already in context. Only then proceed with the user's request. Skills are sibling folders: ../<skill-name>/SKILL.md

| Skill | Why it's required here |
|---|---|
| [problem-statement](../problem-statement/SKILL.md) | Market research builds on the **problem**, the **problem statement**, the **problem hypothesis**, and **problem validation** (the first of the three validation questions). |
| [opportunity-id](../opportunity-id/SKILL.md) | Research exists to determine whether evidence supports the **opportunity**; a real problem can still fail as an opportunity. Uses **opportunity evaluation / screening**. |
| [customer-segmentation](../customer-segmentation/SKILL.md) | Every research step starts by defining the **target customer** and **segment**; the Pivot outcome often means a **narrower segment** or **beachhead market**. |
| [customer-interview](../customer-interview/SKILL.md) | **Interviews** are the core primary qualitative method; behavior-based questioning is executed through customer interviews. |
| [customer-validation](../customer-validation/SKILL.md) | **Customer validation** and **solution validation** (the third validation question) depend on the commitment evidence market research collects. |
| [value-proposition](../value-proposition/SKILL.md) | The Competition test asks whether alternatives leave a **meaningful gap**; filling it is **differentiation** and the **value proposition**. |
| [business-model](../business-model/SKILL.md) | The Economics test and "you want revenue" connect to **revenue models** and **business model assessment**. |
| [customer-end-user-profile-and-persona](../customer-end-user-profile-and-persona/SKILL.md) | Secondary data on **customer demographics and spending** feeds the **end user profile** and **persona**. |
| [customer-ecosystem](../customer-ecosystem/SKILL.md) | Economics and Accessibility depend on knowing **who pays vs. who uses** (**stakeholder roles**). |

## Before You Start

Gather this context first. If the user has not provided it, ask (batch the questions in one message):

1. **The opportunity in one sentence.** What problem, for whom, where? (If the problem itself is still fuzzy, go to [problem-statement](../problem-statement/SKILL.md) first.)
2. **The customer and geography.** Who exactly, and where? Research cannot start until both are defined (→ [customer-segmentation](../customer-segmentation/SKILL.md)).
3. **What problem evidence already exists.** Answers to the problem-validation recap questions (see below).
4. **The decision on the table.** Launch, invest, expand, reposition, pivot, shut down? Research serves a decision.
5. **Stage of the business.** Pre-launch idea, early product, or existing business auditing its market. The method mix changes; the logic does not.
6. **Resources.** Time, budget, and access to databases (a university or public library often unlocks paid sources for free).
7. **What they already believe.** Write down current assumptions so research can confirm or kill them.

## What Market Research Is

### Definition

**Market research** is the process of **gathering, analyzing, and interpreting** information on:

- **a market**, and
- **a product or service** to be offered for sale in that market,

and about that market's **past, present, and potential customers**.

All three verbs matter. Gathering without analysis is a pile of tabs; analysis without interpretation is a spreadsheet with no decision attached.

### Market Research vs. Marketing

These are different jobs in different phases. Do not let a user confuse them.

| | **Market Research** | **Marketing** |
|---|---|---|
| Job | Understanding customers, problems, and opportunities | Creating, communicating, and delivering value to customers |
| Phase | **Research phase** | **Execution phase** |
| Output | Evidence and a decision | Campaigns, messaging, sales |

Running ads before knowing whether a market exists is execution before research. A small ad or landing-page test *designed to measure behavior* is research, because its output is evidence, not revenue.

### Why It Matters

- You want **revenue**.
- Revenue comes from **customers**.
- So always be asking: **Is there a problem and a market that a solution can address?**

The anti-pattern the slides mock (the slide is a sarcastic joke, not serious guidance) is the **"alternate approach"**: *"I have an idea/solution. I will put it into the market and 'hope' I find customers."* Good luck with that. Treat this as the thing market research exists to prevent.

## From Problem Validation to Market Validation

### The Problem-Validation Recap

Market research picks up where problem work leaves off (→ [problem-statement](../problem-statement/SKILL.md)). Before researching the market, the user should be able to answer:

- **Who** experiences the problem?
- **When and how often** does it occur?
- **How important** is the problem?
- **What does the customer do now?**
- **What evidence** supports the problem hypothesis?

### The Key Question

> **Can a problem be real but not represent a market opportunity?**

Yes. A problem can be genuine and painful and still fail as a business opportunity (→ [opportunity-id](../opportunity-id/SKILL.md)) because too few people have it, they cannot be reached, existing alternatives already solve it well enough, or nobody spends money or time on it. Market validation is the step that catches this.

### The Three Validation Questions

| Validation | Core question | Owner |
|---|---|---|
| **Problem validation** | Does a defined customer experience a meaningful problem? | [problem-statement](../problem-statement/SKILL.md) |
| **Market validation** | Do **enough** customers experience the problem **and demonstrate demand**? | **This skill** |
| **Solution validation** | Does the proposed solution create enough value to earn customer commitment? | [customer-validation](../customer-validation/SKILL.md), [value-proposition](../value-proposition/SKILL.md) |

They run in this logical order. Skipping market validation means building a solution for a problem that may not support a business.

## Purpose of Market Research

Market research:

- **Replaces assumptions with evidence**
- **Determines if the evidence supports the opportunity**
- **Identifies what is known and still unknown**
- **Estimates the opportunity before committing major resources**

Use what you learn to make one of three calls: **Proceed, Pivot, or Punt** (see the Scorecard).

> **Research does not eliminate risk, but it improves decisions.**

## The Five Market Claims (What to Test)

This is the core framework. Every market research effort tests five claims. Write each one as a falsifiable hypothesis for the user's specific opportunity, then gather evidence for or against it.

| # | Claim | What must be true | Typical evidence |
|---|---|---|---|
| 1 | **Demand** | Customers experience the problem **often enough to act** | Frequency of the problem, past attempts to solve it, workarounds, sign-ups, orders |
| 2 | **Size** | Enough **target customers exist** to support the opportunity | Census and industry data, counts of customers or businesses in the defined geography, industry size and growth |
| 3 | **Accessibility** | Customers **can be identified and reached** | Where they are located, where they gather (communities, associations, channels), whether you can actually get a response from them |
| 4 | **Competition** | **Current alternatives (competitors) leave a meaningful gap** | Competitor offerings, prices, reviews and complaints, substitutes, what customers do now |
| 5 | **Economics** | Customers **already spend money and time** on the problem | Published spending data, what customers report spending, current workarounds' cost, prices of existing alternatives |

Notes on applying them:

- **Demand is about frequency and action, not interest.** "That sounds cool" is not demand. Customers acting on the problem is.
- **Size is about target customers, not total population.** Count the people who match the defined customer, in the defined geography (→ [customer-segmentation](../customer-segmentation/SKILL.md)).
- **Accessibility kills many "big" markets.** A large market you cannot identify or reach is not your market.
- **Competition includes doing nothing.** Alternatives include direct competitors, substitutes, workarounds, and the status quo. The question is whether a *meaningful gap* remains (→ [value-proposition](../value-proposition/SKILL.md)).
- **Economics checks that spending already exists.** If customers spend neither money nor time on the problem, revenue is a leap of faith. Confirm whose budget the money comes from, since the payer and the user may differ (→ [customer-ecosystem](../customer-ecosystem/SKILL.md)).

### Market Claims Worksheet

```
OPPORTUNITY: [problem] for [defined customer] in [geography]

CLAIM 1 — DEMAND
  Hypothesis: [customer] experiences [problem] about [frequency] and currently acts by [behavior].
  Secondary evidence:
  Primary evidence:
  Behavioral evidence:
  Status: Supported / Contradicted / Unknown

CLAIM 2 — SIZE
  Hypothesis: At least [number] [target customers] exist in [geography].
  Secondary evidence: [source, figure, date]
  Primary evidence:
  Status:

CLAIM 3 — ACCESSIBILITY
  Hypothesis: We can identify and reach them through [channel / place / list].
  Evidence:
  Status:

CLAIM 4 — COMPETITION
  Hypothesis: Current alternatives ([list]) leave a meaningful gap in [specific dimension].
  Evidence:
  Status:

CLAIM 5 — ECONOMICS
  Hypothesis: Customers already spend about [money] and [time] per [period] on this problem.
  Evidence:
  Status:

KNOWN:
UNKNOWN (next research targets):
```

## Sources of Information: Primary vs. Secondary

Research is classified **by source**.

| | **Primary information** | **Secondary information** |
|---|---|---|
| What it is | **New evidence** compiled by yourself or someone you hire to help answer a **specific question** | **Existing evidence** collected by someone else |
| Examples | Interviews, observations, surveys, field trials | Reports, studies, census data, reviews |
| Strength | Answers *your* question about *your* customer | Fast, cheap, broad context |
| Weakness | Slower, costs effort, small samples | Not built for your question; describes possible customers, not demonstrated demand |

**Sequencing rule:** start with secondary. Ask: **What can known evidence tell you before collecting new data?** Then ask: **What information does secondary information not answer, or not answer well?** That gap is your primary research agenda.

### Secondary Research

Use secondary information to learn:

- **Number and location** of potential customers
- **Industry size and growth**
- **Customer demographics and spending** (feeds the end user profile; → [customer-end-user-profile-and-persona](../customer-end-user-profile-and-persona/SKILL.md))
- **Competitors, substitutes, and prices**
- **Economic, technological, or regulatory trends**

#### Secondary Sources

| Category | Sources |
|---|---|
| **Government** | U.S. Census Bureau (including Census Business Builder, cbb.census.gov); Bureau of Labor Statistics; local and state economic data |
| **Library databases** (listed on the slides as available through UH Libraries) | IBISWorld; SimplyAnalytics; Reference Solutions; PolicyMap; MarketResearch.com/Academic |
| **Market sources** | Trade associations and publications; competitor websites, prices, and annual reports; customer reviews and online communities |

If the user is not at the University of Houston, have them check what their own university, public library, or local business center provides. Many of these databases are licensed through libraries.

#### The Secondary Search Process

1. **Define the customer and geography.** Be specific (a ZIP code, a city, an industry code, a customer type).
2. **Select the market claim** you are testing (usually Size, Economics, or Competition).
3. **Choose a credible source.** Prefer government data and recognized databases over blog posts and press releases.
4. **Record** the figures, with source and date.
5. **Ask: What does this evidence *not* tell us?**

#### Slide Example: Late-Night Healthy Food Near Campus

- **Opportunity:** a late-night healthy-food service for people living near campus (ZIP 77004).
- **Investigate:** do enough target customers live near campus to support the opportunity? (Size claim)
- **Search process:** define customer and geography (77004) → select the market claim → choose a credible source (Census Business Builder, cbb.census.gov) → record.
- **Recorded:** 36K population; $71K median income; 94% with a high school degree or higher.
- **What it does not tell us:** it **describes possible customers; it is not demonstrated demand.** Nobody in that data has said they want late-night healthy food, let alone paid for it.

That last line is the most important habit in secondary research. Always write it down.

#### Secondary Search Record Template

```
CLAIM TESTED: [Demand / Size / Accessibility / Competition / Economics]
CUSTOMER + GEOGRAPHY:
SOURCE: [name, URL or database, publication date]
FIGURES RECORDED:
-
-
WHAT THIS EVIDENCE TELLS US:
WHAT THIS EVIDENCE DOES NOT TELL US:
FOLLOW-UP PRIMARY QUESTION:
```

### Primary Research

Use primary information to learn what secondary data cannot:

- **How customers currently behave**
- **How often the problem occurs**
- **What customers use as alternatives**
- **What the problem currently costs them**
- **Why they choose, switch, delay, or do nothing**
- **What evidence of commitment they will provide** (→ [customer-validation](../customer-validation/SKILL.md))

#### Choosing a Method

Pick the method by what you need to learn:

| To learn... | Use... |
|---|---|
| How customers **experience** the problem | **Interviews** (→ [customer-interview](../customer-interview/SKILL.md)) |
| What customers **actually do** | **Observation** |
| How **common** a known behavior may be | **Survey** |
| How customers **discuss and react together** | **Focus groups** |
| Whether customers **will take an action** | **Field trials** |

Key implications:

- **Surveys measure how common something is; they do not discover it.** Use a survey only after interviews or observation have revealed the behavior worth counting.
- **Observation beats self-report** when what people say and what they do may differ.
- **Field trials are the strongest test of action**, because the customer actually has to do something. The slides link a **Wizard of Oz** example alongside these methods: a test where the customer experiences what looks like a working product or service while people deliver it manually behind the scenes, so you can measure real action before building anything.

#### Identify Behaviors, Not Opinions

Market validation needs evidence about what customers **have experienced, tried, spent, delayed, or abandoned**. Ask about past behavior, not hypothetical intent.

Slide example: **Idea:** a late-night food delivery service. **Need to learn:** would customers pay $10 for late-night delivery?

| Do not ask | Ask instead |
|---|---|
| "Would you pay $10 for late-night delivery?" | "Tell me about the last time you wanted food after 10 p.m." |
| | "What did you do?" |
| | "What did it cost?" |
| | "What alternatives did you consider?" |
| | "What made you choose that option?" |

The "ask instead" questions surface frequency (Demand), current spending (Economics), alternatives (Competition), and decision drivers, all from real events. The hypothetical question produces a polite "sure" that predicts nothing. Detailed interview technique lives in [customer-interview](../customer-interview/SKILL.md).

#### Behavior Question Template

Convert any "would you..." question into this pattern:

```
NEED TO LEARN: [the market claim, e.g., would customers pay $X for Y]

1. Tell me about the last time you [experienced the problem / needed the thing].
2. What did you do?
3. What did it cost you? (money, time, hassle)
4. What alternatives did you consider?
5. What made you choose that option?
6. (Optional) Have you ever tried to fix this some other way? What happened?
```

## Two Data Types: Qualitative vs. Quantitative

Research is also classified **by data type**.

| | **Qualitative** | **Quantitative** |
|---|---|---|
| Consists of | Words, actions, images, and context | Counts, measurements, rates, and amounts |
| Answers | **How** and **why** | **How many, how often, and how much** |
| Reveals | Motives, language, workarounds, and decision processes | Frequency, spending, and patterns |
| Methods | Interviews, observation, focus groups, open-ended responses | Structured surveys, experiments, transactions, and analytics |
| Output | **Themes and explanations** | **Numbers and comparisons** |

Qualitative work tells you *what to measure*. Quantitative work tells you *how much of it there is*. Using numbers without the qualitative "why" produces confident wrong conclusions; using stories without numbers produces conviction with no scale.

## Source × Data Type Matrix

Combine the two classifications to plan a balanced research program:

| | **Qualitative** | **Quantitative** |
|---|---|---|
| **Primary** | Interviews, direct observation, focus groups, open-ended responses | Structured surveys, experiments, orders, sign-ups, conversion rates |
| **Secondary** | Customer reviews, online discussions, published case studies, competitor messaging | Census data, industry reports, published spending data, market-growth statistics |

For every research question, ask: **Who should collect the evidence, and what form will it take?** A plan that lives entirely in one cell is a weak plan.

### Research Plan Template

```
DECISION THIS RESEARCH SERVES:
CUSTOMER + GEOGRAPHY:

| Market claim | Question | Source (Primary/Secondary) | Data type (Qual/Quant) | Method | Who collects | Target / deadline |
|--------------|----------|----------------------------|------------------------|--------|--------------|-------------------|
| Demand       |          |                            |                        |        |              |                   |
| Size         |          |                            |                        |        |              |                   |
| Accessibility|          |                            |                        |        |              |                   |
| Competition  |          |                            |                        |        |              |                   |
| Economics    |          |                            |                        |        |              |                   |

Coverage check: at least one entry in each of the four matrix cells? Y/N
```

## Market Sizing

Sizing is the **Size** claim: do enough target customers exist to support the opportunity? Build it from evidence, in this order:

1. **Define the target customer and geography precisely** (→ [customer-segmentation](../customer-segmentation/SKILL.md)). A size estimate for a vague customer is meaningless.
2. **Count potential customers** with secondary sources: number and location (Census, Census Business Builder, PolicyMap, SimplyAnalytics, Reference Solutions), plus **industry size and growth** (IBISWorld, MarketResearch.com/Academic, trade associations).
3. **Add spending context** with published spending data and demographics (Economics claim).
4. **Record what the numbers do not tell you.** Population and industry totals describe *possible* customers, not demonstrated demand.
5. **Test the estimate's assumptions with primary research.** Secondary evidence estimates size; primary evidence **tests whether target customers behave as those estimates assume** (for example, what share actually experiences the problem often enough to act, and what they spend now).
6. **Use numbers with caution.** The slides illustrate this with a Tide box advertising "Attacks even 7 day old stains!" under the heading **Use Numbers With Caution**. A specific number looks authoritative, which is exactly why it must be sourced, dated, scoped to your customer, and paired with what it leaves out.

Sizing template:

```
TARGET CUSTOMER:
GEOGRAPHY:
Potential customers (count):        [figure]  — source, date
Industry size / growth:             [figure]  — source, date
Spending per customer (published):  [figure]  — source, date
Primary check: share who experience the problem often enough to act: [figure] — method, n
Primary check: current spend reported:  [figure] — method, n
Estimate:  [customers] × [share that acts] × [spend] = [figure]
What this estimate does NOT tell us:
```

## Competitive Analysis

The **Competition** claim is that current alternatives leave a meaningful gap. **Ignoring competitors in research is one of the four common mistakes.** Cover it from every cell of the matrix:

| Evidence | Source | What to extract |
|---|---|---|
| **Competitors, substitutes, and prices** | Secondary: competitor websites, prices, annual reports, trade publications, industry reports | Who serves this customer now, at what price, at what scale |
| **Competitor messaging** | Secondary qualitative: competitor sites and marketing | What they promise, who they target, what they ignore |
| **Customer reviews and online communities** | Secondary qualitative | Recurring complaints and unmet needs, in the customer's own language |
| **What customers use as alternatives** | Primary: interviews and observation | The real competitive set, including workarounds and doing nothing |
| **Why they choose, switch, delay, or do nothing** | Primary: interviews | The decision drivers and switching barriers |
| **What alternatives cost them** | Primary + secondary | Economics of the status quo |

Competitive analysis template:

```
| Alternative (incl. workaround / do nothing) | Type (direct / substitute / status quo) | Price | Who it serves | Customer complaints (reviews, interviews) | Gap it leaves |
|---|---|---|---|---|---|
|   |   |   |   |   |   |

MEANINGFUL GAP (one sentence, backed by at least two evidence sources):
WHY CUSTOMERS HAVEN'T SWITCHED ALREADY:
```

Turning the gap into a differentiated offer is value-proposition work (→ [value-proposition](../value-proposition/SKILL.md)).

## Combining Evidence (Triangulation)

**Use all types.** Each answers a different part of the question:

| Evidence type | Role |
|---|---|
| **Secondary evidence** | **Estimates** the size, location, growth, competition, and spending context |
| **Primary evidence** | **Tests** whether target customers behave as those estimates assume |
| **Behavioral evidence** | **Shows** whether customers will take a meaningful action |

**Confidence increases when different evidence points toward the same conclusion.**

> **Remember: One source is NOT validation!**

### Evidence Strength

Rank what you collect. Weak evidence can guide where to look; only stronger evidence should drive a Proceed call.

| Strength | Evidence | Example |
|---|---|---|
| Weakest | Hypothetical opinion | "Would you buy this?" → "Yes" |
| Weak | Possible-customer data | Population, income, industry totals |
| Moderate | Reported past behavior | "Last week I drove 20 minutes and paid $14 because nothing nearby was open." |
| Strong | Observed behavior and current spending | Watching the workaround; documented spend on alternatives |
| Strongest | **Meaningful action / commitment** | Orders, sign-ups, deposits, conversion rates, field-trial participation |

## Market Research Scorecard: Proceed, Pivot, or Punt

The Proceed / Pivot / Punt decision is defined in → [problem-statement](../problem-statement/SKILL.md). Here it is applied to market evidence, with the criteria from this stage:

| Decision | When |
|---|---|
| **Proceed** | **Multiple evidence sources support the five market claims.** |
| **Pivot** | A **narrower segment, different use case, or revised assumption** appears more promising (→ [customer-segmentation](../customer-segmentation/SKILL.md)); **or** the evidence is **incomplete or contradictory**. |
| **Punt** | Evidence does not support a **reachable, meaningful, and economically viable** market. |

> **The goal of research is not certainty. The goal is a better next decision.**

Notes:

- Punt maps directly to three claims: **reachable** (Accessibility), **meaningful** (Demand and Size), **economically viable** (Economics). Competition shapes how much of that market is actually available.
- "Incomplete or contradictory" evidence is a Pivot signal, not a Proceed. Revise the assumption, design the next test, and run it.
- Punting a direction is a successful research outcome. It saved the resources a failed launch would have consumed.

Scorecard template:

```
| Claim         | Secondary | Primary | Behavioral | # sources agreeing | Verdict (Supported / Contradicted / Unknown) |
|---------------|-----------|---------|------------|--------------------|----------------------------------------------|
| Demand        |           |         |            |                    |                                              |
| Size          |           |         |            |                    |                                              |
| Accessibility |           |         |            |                    |                                              |
| Competition   |           |         |            |                    |                                              |
| Economics     |           |         |            |                    |                                              |

DECISION: Proceed / Pivot / Punt
WHY (cite the evidence):
IF PIVOT — narrower segment / different use case / revised assumption:
STILL UNKNOWN:
NEXT RESEARCH STEP + DATE:
```

## Real-Life Marketing Lessons

The slides close the methods section with real-world cautionary cases (presented as videos and images in class):

- **Life Without Market Research** and **Differing Opinions**: why decisions made without research, or on whoever's opinion is loudest, go wrong. Research settles differing opinions with evidence.
- **Use Numbers With Caution** (Tide, "Attacks even 7 day old stains!"): a precise-looking number is persuasive, so treat every number, in research and in claims built from it, as something that needs a source, a scope, and context.
- **New Coke** (Coca-Cola vs. New Coke): cited as a marketing lesson, a reminder that even the largest, most research-capable companies can misread their market.

## Workflow

Follow these steps for any market research task: a new idea, an audit of an existing business, a planned expansion, or a pivot.

1. **Anchor the decision.** Write the decision the research must inform and the deadline for making it.
2. **Confirm problem evidence.** Run the five recap questions. If they cannot be answered, send the user to [problem-statement](../problem-statement/SKILL.md) before going further.
3. **Define customer and geography.** Specific enough to search a database with (→ [customer-segmentation](../customer-segmentation/SKILL.md)).
4. **Write the five market claims** as falsifiable hypotheses using the Market Claims Worksheet.
5. **List known vs. unknown.** Mark each claim Supported / Contradicted / Unknown based on current evidence.
6. **Do secondary research first.** Follow the four-step search process for Size, Economics, and Competition. Fill a Secondary Search Record for every source, including **what it does not tell you**.
7. **Run competitive analysis** from reviews, competitor sites, prices, messaging, and reports.
8. **Design primary research for the gaps.** Choose methods with the "To learn... / Use..." table. Plan coverage across all four cells of the Source × Data Type matrix and decide who collects what.
9. **Collect behavior, not opinions.** Use the Behavior Question Template. Recruit beyond friends and family. Seek at least one form of behavioral evidence (sign-ups, orders, a field trial).
10. **Triangulate.** For each claim, check whether secondary, primary, and behavioral evidence point the same way. One source is not validation.
11. **Score it.** Fill the Scorecard and make the Proceed / Pivot / Punt call, citing evidence.
12. **Keep researching.** Set the next research step and date. Markets, competitors, and customers change; research does not stop after initial validation.

When auditing an existing business, run the same steps but lean on internal transaction and analytics data (primary quantitative) and recheck each claim against current conditions: has the segment shifted, has a new alternative closed the gap, has spending moved?

## Common Mistakes

**From the slides:**

1. **Only surveying friends and family (selection bias).** They are not representative and they are motivated to be nice. Recruit from the actual target customer, found through the Accessibility channels.
2. **Asking "Would you buy this?" instead of observing behavior.** Hypothetical intent is the weakest evidence. Ask about the last time, what they did, what it cost.
3. **Ignoring competitors in research.** Every customer already has an alternative, even if it is doing nothing. Map it.
4. **Stopping research after initial validation.** Validation is a snapshot. Keep testing as the business, segment, and market move.

**Also watch for:**

- **The "alternate approach."** Launching and hoping to find customers. This is the failure mode market research exists to prevent.
- **Treating possible customers as demand.** Population and income data describe who *could* buy, not who will.
- **One source declared as validation.** Confidence requires different evidence pointing to the same conclusion.
- **Skipping "what does this not tell us?"** Every source has blind spots; write them down.
- **Using numbers without caution.** Unsourced, undated, or unscoped figures (especially giant industry totals) presented as your market.
- **Surveying before discovering.** Surveys count known behaviors; they cannot reveal the behaviors you have not found yet.
- **Confusing market research with marketing.** Promotion before evidence is execution without research.
- **Calling contradictory evidence a Proceed.** Incomplete or contradictory evidence means Pivot and re-test.

## Worked Examples

### Positive Example: Mobile Knife-Sharpening for Independent Restaurants

*Illustrative example; figures are invented for demonstration, not real data.*

**Opportunity:** A pickup-and-return knife-sharpening subscription for independent (non-chain) full-service restaurants in central Houston.

**Decision:** Whether to buy a second sharpening rig and hire a driver ($18K commitment) or stay a side business.

1. **Problem evidence (recap):** 12 interviews with head chefs: dull knives slow prep daily; most sharpen in-house when someone has time, or use a sharpening vendor that visits monthly and is often late.
2. **Customer + geography:** independent full-service restaurants in ten central Houston ZIP codes.
3. **Five claims written as hypotheses**, e.g., *Economics: restaurants already spend $60–$150/month on sharpening or replacement knives.*
4. **Secondary research:**
   - Size: Census Business Builder count of full-service restaurants in the ten ZIP codes (recorded with date), cross-checked against a Reference Solutions business list to remove chains. *Doesn't tell us:* how many care about sharpening frequency.
   - Competition: two existing sharpening services found via websites and reviews; reviews repeatedly complain about missed visits and 4-week gaps. Prices recorded.
   - Trends: trade-publication articles on kitchen labor shortages (less in-house time to sharpen).
5. **Primary research, chosen by method table:**
   - Interviews (how they experience it): 20 chefs and owners, recruited by walking in during off-hours, none of them friends. Behavior questions: "Tell me about the last time a knife was too dull to use mid-shift. What did you do? What did it cost?"
   - Observation: two prep shifts observed; cooks lost visible time working around dull blades.
   - Survey (how common): 60 restaurants on a local restaurant-association mailing list, asking frequency and current spend.
   - Field trial (will they act): free first swap, then a paid month at $95. **9 of 14 trial restaurants paid for month two.**
6. **Competitive analysis:** the gap is *reliability and frequency* (weekly swaps vs. monthly visits), backed by reviews, interviews, and trial retention.
7. **Triangulation:** Demand (interviews + observation + trial), Size (Census + business list), Accessibility (walk-ins and association list both produced responses), Competition (reviews + interviews), Economics (survey spend + paid trial). Every claim has two or more agreeing sources.
8. **Scorecard: Proceed**, with one revision: hotel kitchens showed weaker interest in interviews, so they are excluded for now. Next step: re-run the survey in six months and track churn monthly.

**Why it works:**

- Defined customer and geography before searching, so every number is scoped.
- Secondary first, and wrote down what each source did not tell them.
- Methods matched to questions (interviews for experience, observation for action, survey for frequency, field trial for commitment).
- Asked about past behavior and cost, never "would you pay?"
- Recruited outside friends and family.
- Competitors mapped from reviews, prices, and interviews; the gap is specific.
- Behavioral evidence (paid month two) anchors the Proceed.
- Multiple sources per claim; the decision is tied to a real resource commitment; research continues.

### Negative Example: Plant-Care Reminder App

**Opportunity:** A $4.99/month app that reminds people when to water their houseplants.

**What the founder did:**

1. Sent a Google Form to 40 friends, classmates, and family members: "Would you pay $4.99/month for an app that reminds you to water your plants?" **85% said yes.**
2. Found a press release claiming the "global houseplant market is worth tens of billions of dollars" and put that number on the pitch deck as the market size.
3. Wrote "no direct competitors" without searching app stores, reviews, or plant-care communities.
4. Declared the market validated and stopped research to start building.
5. Planned to "launch it and see who signs up."

**Why it fails:**

- **Selection bias:** friends and family only. Mistake 1.
- **Hypothetical question:** "Would you pay?" measures politeness, not demand. Mistake 2.
- **No defined customer or geography:** "people with plants" is not a target customer, so Size and Accessibility cannot be tested.
- **Numbers without caution:** a global houseplant figure is unsourced, unscoped, and is spending on *plants*, not on reminder apps. It describes possible spending, not demand.
- **Ignoring competitors:** reminders already exist as free phone alarms, calendar apps, and other plant apps; the status quo is a real competitor. Mistake 3.
- **Economics untested:** no evidence anyone currently spends money or meaningful time on plant-watering reminders.
- **One source treated as validation:** a single survey, with no primary qualitative or behavioral evidence.
- **Stopped after "initial validation."** Mistake 4.
- **The "alternate approach":** launch and hope.

**What it should have done:** Define a target segment (for example, owners of large indoor plant collections), interview them about the last plant they lost and what they tried, check app-store reviews of existing plant apps for gaps, run a landing page with a paid pre-order or waitlist as behavioral evidence, and score the five claims before writing code.

## Related Skills & Next Steps

- **[problem-statement](../problem-statement/SKILL.md)** — Go here first if the recap questions (who, how often, how important, what they do now, what evidence) cannot be answered.
- **[opportunity-id](../opportunity-id/SKILL.md)** — Go here to evaluate whether a validated market is the right opportunity to pursue, or to find a new one after a Punt.
- **[customer-segmentation](../customer-segmentation/SKILL.md)** — Go here to define the target customer and geography before research, or to choose a narrower segment or beachhead after a Pivot.
- **[customer-interview](../customer-interview/SKILL.md)** — Go here to plan and run the interviews that produce primary qualitative evidence.
- **[customer-ecosystem](../customer-ecosystem/SKILL.md)** — Go here when the payer, user, and decision-maker differ and the Economics or Accessibility claims depend on who is who.
- **[customer-end-user-profile-and-persona](../customer-end-user-profile-and-persona/SKILL.md)** — Go here to turn demographic and behavioral findings into an end user profile and persona.
- **[customer-validation](../customer-validation/SKILL.md)** — Go here after Proceed to gather commitment evidence and run solution validation.
- **[value-proposition](../value-proposition/SKILL.md)** — Go here to turn the meaningful gap found in competitive analysis into a differentiated value proposition.
- **[business-model](../business-model/SKILL.md)** — Go here to build and assess the revenue model on top of the Economics evidence.
