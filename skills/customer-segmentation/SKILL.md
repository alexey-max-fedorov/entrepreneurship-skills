---
name: customer-segmentation
description: "Customer entry point. Answers who is my customer: segment a broad market into groups that share a need, behavior, or buying context, write testable segment hypotheses, and pick a beachhead market to win first and expand from. Use when the user says 'who is my customer', 'who should I target', 'segment my market', 'customer segments', 'target market', 'beachhead market', 'which customers first', 'our market is everyone', 'niche down', or is starting, auditing, or pivoting who a business serves. For stakeholder roles, see customer-ecosystem; for talking to customers, customer-interview; for testing whether they will buy, customer-validation; for the exact user, customer-end-user-profile-and-persona; for market size, market-research. Starts from problem-statement and opportunity-id."
metadata:
  version: 1.0.1
---

# Customer Segmentation

You are an expert in customer segmentation and beachhead market selection. Your goal is to turn a vague answer to "who is my customer?" into a specific, reachable, testable segment hypothesis, choose the single beachhead market to win first based on the evidence gathered to date, and route every follow-on customer question to the skill that owns it.

## Required Reading — Load These Skills First

Before doing anything else, read the SKILL.md of every skill below that is not already in your context. Apply the same rule recursively to every skill you load (no limit; loading the whole library is fine). Never re-read a skill already in context. Only then proceed with the user's request. Skills are sibling folders: ../<skill-name>/SKILL.md

| Skill | Why it's required here |
|---|---|
| [problem-statement](../problem-statement/SKILL.md) | Segments are defined around **the problem** that occurs for them; "what problem occurs?" is a core segment assumption |
| [opportunity-id](../opportunity-id/SKILL.md) | The customer pipeline starts at **idea → opportunity**; segmentation picks up from a recognized **opportunity** |
| [customer-ecosystem](../customer-ecosystem/SKILL.md) | **Stakeholder roles**: who uses, who pays, who influences the decision ("user is not always the buyer") |
| [customer-interview](../customer-interview/SKILL.md) | **Customer interviews** are step 2 of how to segment and the main source of beachhead evidence |
| [customer-end-user-profile-and-persona](../customer-end-user-profile-and-persona/SKILL.md) | **End user profile** (initial) and **persona** sit inside the opportunity-to-customer pipeline |
| [customer-validation](../customer-validation/SKILL.md) | **Customer validation**: the "refine / test" step that confirms the beachhead will actually buy |
| [market-research](../market-research/SKILL.md) | **Secondary research** and **market sizing** used to compare candidate markets (e.g., state-level revenue figures) |
| [value-proposition](../value-proposition/SKILL.md) | **Value sought** and **customer jobs/pains** are a segmentation dimension and a market-definition condition |
| [business-model](../business-model/SKILL.md) | **Business Model Canvas** blocks (Customer Segments, Channels, Customer Relationships, Revenue) that segmentation feeds |
| [creative-ideation](../creative-ideation/SKILL.md) | **Brainstorming** the 3-6 candidate markets for a beachhead |
| [pricing-models](../pricing-models/SKILL.md) | **Pricing** by segment: willingness to pay as a segmentation dimension feeds the price and pricing model |

## Before You Start

Collect what exists. If something is missing, ask once, then proceed with stated assumptions.

1. **The problem / opportunity.** What problem are you solving, and is it a real opportunity? If there is no problem statement, go to (→ [problem-statement](../problem-statement/SKILL.md)) first. If it is still just an idea, see (→ [opportunity-id](../opportunity-id/SKILL.md)).
2. **The offer.** What can you deliver *today*? A beachhead requires a complete solution now, not on the roadmap.
3. **Current customer answer.** How does the user describe their customer right now? ("Everyone," "small businesses," "students" are signals that segmentation has not happened yet.)
4. **Evidence to date.** How many potential customers have been talked to, and what did they say? A beachhead is chosen **based on the evidence gathered to date**.
5. **Reach and resources.** Who can the team actually get in front of, and with what time, money, and people?
6. **Situation.** Starting fresh, auditing an existing customer base, optimizing, or pivoting to a new group. The method is the same; the starting assumptions differ.

## Who Is My Customer?

This is the question this skill exists to answer, and it has four parts:

| Objective | The rule that goes with it | Owner |
|---|---|---|
| **Segment the market** | **"Everyone" is not a segment** | This skill |
| **Understand the people around the purchase** | **User is not always the buyer** | → [customer-ecosystem](../customer-ecosystem/SKILL.md) |
| **Build and test an end-user profile / persona** | **Profiles are hypotheses** | → [customer-end-user-profile-and-persona](../customer-end-user-profile-and-persona/SKILL.md) |
| **Choose a beachhead** | **Start focused, learn, expand** | This skill |

### "Everyone" Is Not a Segment

Ask "Who are the customer segments of a bakery?" and the instinctive answer is "everyone, everybody eats cookies." That answer is useless. **"Everyone" is not a segment**, and **a crowd is not a segment of customers.** A crowd is a mass of people who happen to be in the same place; a segment is a group you can describe, find, and serve in a specific way.

### The Three Customer Questions

Even a single organization has more than one "customer." For any business (the slides use the University of Houston: who is UH's customer?), ask:

- **Who uses it?**
- **Who pays?**
- **Who influences the decision?**

These are often different people. Mapping them in full is the job of stakeholder roles (→ [customer-ecosystem](../customer-ecosystem/SKILL.md)). For segmentation, the takeaway is: do not assume your user and your buyer are the same segment.

## Market Segmentation

**Definition:** **Market segmentation** is dividing a broad market into smaller groups that share a **meaningful need, behavior, or buying context**.

The goal is not a pretty taxonomy. The goal is to **identify the most promising segment to investigate first.**

### When Customers Are Different Segments

Two groups of customers are **different segments** when they differ on any of these. If they differ, they need different treatment, so they cannot be served as one segment.

| Dimension | What differs | Example from the slides |
|---|---|---|
| **Needs / value sought** | What they want the product to do for them | A gym: athletes vs. students |
| **Channels** | How you reach them | Tutoring and orientation reach freshmen; ads reach upperclassmen |
| **Service / relationship needs** | How much hand-holding they want | Career coaching vs. self-serve templates vs. one-on-one advising |
| **Economics / profitability** | What serving them costs and earns | A photographer: an individual student vs. a fraternity shoot |
| **Willingness to pay** | Whether and how much they will pay to solve it | A note-taking app vs. hiring a student to take notes |

Segments that differ in willingness to pay can carry different prices; dynamic pricing and good-better-best tiers both work off those differences (→ [pricing-models](../pricing-models/SKILL.md)).

Notes:
- **Value sought** links to the value proposition you build for the segment (→ [value-proposition](../value-proposition/SKILL.md)).
- **Channels**, **relationships**, and **economics** are also Business Model Canvas blocks; once a segment is chosen, it feeds those blocks (→ [business-model](../business-model/SKILL.md)).
- Demographics alone (age, gender, income band) do not appear on this list. Use them only when they track a real difference in need, behavior, channel, economics, or willingness to pay.

### Segments Begin as a Set of Assumptions

A segment is a hypothesis before it is a fact. Write down your assumptions explicitly by answering six questions:

1. **Who are we helping?**
2. **What are they trying to do?**
3. **What problem occurs?** (→ [problem-statement](../problem-statement/SKILL.md))
4. **What do they do today?** (current workaround or alternative)
5. **Why might they adopt / pay?**
6. **Where and how can we reach them?**

Fill-in template:

```
SEGMENT ASSUMPTIONS — [segment name]
Who we are helping:        ______________________________
What they are trying to do: ______________________________
What problem occurs:        ______________________________
What they do today:         ______________________________
Why they might adopt/pay:   ______________________________
Where/how we reach them:    ______________________________
Confidence (guess / some interview evidence / strong evidence): ____
```

Every blank you fill from imagination rather than from customers is an assumption to test.

### How to Segment (4 Steps)

| Step | Action | What it means |
|---|---|---|
| 1. **Start with assumptions** | Initial guess | Write the six segment assumptions above for each group you suspect exists |
| 2. **Talk to people** | Interview potential customers | Go get real conversations (→ [customer-interview](../customer-interview/SKILL.md)) |
| 3. **Understand their need** | Listen to their stories about their reality | Hear how they actually experience the problem, not how you imagine it |
| 4. **Segment by context** | Group by the patterns you find | Cluster people by shared need, behavior, or buying context that showed up in the data |

**Gotta get data to understand and then revise!** The first segmentation is a guess. The data from steps 2-3 will reshape it, and you redraw the segments from what you heard, not from what you assumed.

### Choose a Segment: Narrow Until It Is Testable

A usable starting segment is specific enough that you know exactly who to go talk to. The slides' worked narrowing for a food option aimed at students eating between classes:

| Version | Verdict |
|---|---|
| "Students" | **Not a usable starting segment** |
| "UH students" | **Usually still too broad** |
| "UH commuter students who struggle to find affordable food between back-to-back classes" | **A testable starting segment hypothesis** |

What made the last one work: a **specific group** (commuter students at one campus), a **context** (between back-to-back classes), and a **problem** (struggle to find affordable food).

Segment statement template:

```
[Specific group, bounded by place/role/situation]
who [struggle with / are trying to] [problem or job]
when/where [buying or usage context].
```

Test the statement: could you name ten real people who fit it and know where to find them this week? If not, narrow further.

## Beachhead Market

### What Is a Beachhead?

A **beachhead** is **a small, focused market from which you establish a foothold and expand.** The term comes from military landings: you do not invade the whole coast at once; you take one beach, secure it, and push inland from there.

The **beachhead market** answers:
- **Which specific customer group should we focus on first?**
- **Based on the evidence gathered to date.**

### The Goal (and the Anti-Goal)

| Wrong goal | Right goal |
|---|---|
| Find the largest, most obvious market | **Choose a reachable, narrow, first market you can serve well now and learn from quickly** |

Size is not the selection criterion for a beachhead. Market size matters for the long-run opportunity (→ [market-research](../market-research/SKILL.md)), but the first market is chosen for reach, fit, and learning speed.

### Conditions That Define a Market

A group only counts as one market (rather than several) when all three hold:

1. **Customers have similar needs and seek similar value.**
2. **Customers have a similar buying or adoption process.**
3. **There is "word of mouth" between customers in the market.**

The third condition is the one founders skip. If customers do not talk to each other, every sale starts from zero, and you never get the referral engine that makes a beachhead pay off.

### How to Find a Beachhead (4 Steps)

1. **Brainstorm 3-6 potential markets** for your business (where your customers gather). (→ [creative-ideation](../creative-ideation/SKILL.md) for brainstorming technique.)
2. **Identify how you can reach these customers.**
3. **Compare early interview evidence** across the candidates. (→ [customer-interview](../customer-interview/SKILL.md))
4. **Select one to focus on; test and refine if needed.** (→ [customer-validation](../customer-validation/SKILL.md))

### Evidence Questions

Use these five questions to help determine the beachhead. Answer each per candidate market from evidence, not hope.

1. **Is there an urgent need?** (a reason to buy)
2. **Can the target customer pay?** (well-funded)
3. **Is the target customer reachable?** (accessible to your sales force)
4. **Can you deliver a complete solution?** (today)
5. **Can you expand from here to additional segments?**

Comparison template (rate each cell Strong / Partial / Weak / Unknown, and cite the evidence):

```
| Criterion                              | Market A | Market B | Market C |
|----------------------------------------|----------|----------|----------|
| Similar needs / value sought           |          |          |          |
| Similar buying / adoption process      |          |          |          |
| Word of mouth between customers        |          |          |          |
| Urgent need (reason to buy)            |          |          |          |
| Can pay (well-funded)                  |          |          |          |
| Reachable (accessible to sales force)  |          |          |          |
| Complete solution deliverable today    |          |          |          |
| Expansion path to adjacent segments    |          |          |          |
| Interviews completed / key evidence    |          |          |          |
```

How to read it:
- "Unknown" is not a neutral score. It is a task: go get the evidence (usually interviews).
- A market that is Weak on **reachable** or **complete solution today** is almost never the beachhead, no matter how attractive the rest looks.
- Pick one. Ties mean you need more evidence, not two beachheads.

### Why Focus on a Single Market

By choosing a single market you:
- **Learn faster**
- **Focus scarce resources**
- **Build a repeatable path to sales / adoption**
- **Achieve word of mouth (WOM) / generate referrals**

### Beachhead Rules

- **Do not look for the "perfect" market.**
- **Do not begin with a broad market.**
- **Find a single entry point.**
- **Customers who pay.**
- **Win WOM.**
- **Expand from there!**

### Bias to Action

- **Get started.**
- **Get going.**
- **Start doing.**
- **Stop analyzing...**
- **Action produces data...**
- **Data tells you good / bad!**

A beachhead is chosen on the evidence gathered *to date* and is labeled **initial** for a reason. Pick it, act in it, and let the results tell you whether to stay, refine, or move. Analysis paralysis over the "right" beachhead produces no data at all.

**Quality rule:** "don't look for the perfect market" and "bias to action" govern how the *founder* commits to a market. They never lower the standard of *your* work. Always aim for perfection in the analysis itself: every segment, beachhead score, and recommendation you produce is complete, evidence-based, and the best version you can make.

### Beachhead Cases from the Slides

**Tesla entering the EV market.**
- Target: the electric vehicle (EV) market. Too big, so segment.
- Chose the **high-end luxury car segment**: early adopters of new technologies, willing to pay a premium for an electric sports car.
- Introduced the **Roadster** and established a foothold in this niche.
- Demonstrated the viability / desirability of EVs and got WOM.
- That paved the way for expansion into other consumer segments with the Model S, Model 3, Model Y, etc.

Lesson: the beachhead was small and premium on purpose. It had an urgent want, could pay, talked to each other, and gave a credible expansion path.

**StanCraft Boats.**
- History: 1st generation (1933) wooden boats, regional presence in the Northwest. 2nd generation (1968) fiberglass boats to expand. 3rd generation (2003-present) return to wood: built over 150 (about 10 per year) large custom mahogany boats at $700k-$1M each. 4th generation (proposed): wood "semi-custom," ramping to 80 per year at $350k-$600k each.
- The question: could INTX help StanCraft by investing and establishing an operation to build a dealer network for StanCraft semi-custom boats? Put differently: can we find an initial market that would help launch this product line, what are its characteristics, and could we identify a **beachhead market**?
- **Initial thought: Florida.** Wealthy customer base, particularly retirees with large disposable income; Florida was ranked 1st for boating revenues at over $1.5 billion per year.
- **Refined beachhead: the Palm Beach area**, known as the gold standard for luxury in boating, through **Worth Avenue Yachts** in Palm Beach: a "posh" dealer in a prime location with easy access to Clear Lake, Lake Worth, and Lake Mangonia, selling mega yachts in the double-digit millions. StanCraft could appeal to clients who want to add something stylish to their collection or want a unique superyacht tender. The dealer has other locations (Fort Lauderdale, Newport, Rhode Island, and Monaco), and there is potential to sell StanCrafts quickly to clients for whom $500,000 is a "trivial cost."

Lesson: "Florida" was a broad state-level guess backed by secondary data (→ [market-research](../market-research/SKILL.md)). The real beachhead was a single entry point: one dealer whose customers can easily pay, already buy through the same process, talk to each other, and whose other locations form a built-in expansion path.

## Opportunity to Customer: The Full Pipeline

This skill is the customer entry point. Segmentation sits inside a longer pipeline, and every step after it is iterative:

```
Idea → Opportunity → Customer Segments (potential) → End User Profile (initial)
     → Interviews → Persona → Beachhead (initial) → Refine / Test
```

| Step | What happens | Owner |
|---|---|---|
| Idea → Opportunity | Turn an idea into an opportunity worth pursuing | → [opportunity-id](../opportunity-id/SKILL.md) |
| **Customer Segments (potential)** | Divide the market; write segment assumptions | **This skill** |
| End User Profile (initial) | First-draft profile of the user in the most promising segment | → [customer-end-user-profile-and-persona](../customer-end-user-profile-and-persona/SKILL.md) |
| Interviews | Talk to people in the candidate segments | → [customer-interview](../customer-interview/SKILL.md) |
| Persona | Turn interview data into a specific persona | → [customer-end-user-profile-and-persona](../customer-end-user-profile-and-persona/SKILL.md) |
| **Beachhead (initial)** | Pick the first market from evidence to date | **This skill** |
| Refine / Test | Confirm and adjust with real buying behavior | → [customer-validation](../customer-validation/SKILL.md) |

Note the labels: segments are **potential**, the profile and beachhead are **initial**. Nothing here is final until tested.

## Customer Question Router

Once segmentation is in place, follow-on customer questions belong to other skills. Answer at the level of segmentation here, then send the user to the owner.

| If the question is... | Go to |
|---|---|
| What problem are we actually solving? Is the pain real? | → [problem-statement](../problem-statement/SKILL.md) |
| Is this an idea or a real opportunity? | → [opportunity-id](../opportunity-id/SKILL.md) |
| Who are the stakeholders? Who uses, who pays, who influences, who can block it? | → [customer-ecosystem](../customer-ecosystem/SKILL.md) |
| How do I talk to customers? What do I ask? How many interviews? | → [customer-interview](../customer-interview/SKILL.md) |
| How do I confirm they will actually buy? | → [customer-validation](../customer-validation/SKILL.md) |
| Who exactly is the user? What is their profile or persona? | → [customer-end-user-profile-and-persona](../customer-end-user-profile-and-persona/SKILL.md) |
| How big is the market (TAM/SAM/SOM)? Who are the competitors? What does secondary data say? | → [market-research](../market-research/SKILL.md) |
| What value do we offer this segment, and how are we different? | → [value-proposition](../value-proposition/SKILL.md) |
| How does serving this segment make money (channels, relationships, revenue)? | → [business-model](../business-model/SKILL.md) |
| I need more candidate markets or segment ideas. | → [creative-ideation](../creative-ideation/SKILL.md) |

## Workflow

1. **Anchor on the problem.** Confirm the problem and opportunity exist (→ [problem-statement](../problem-statement/SKILL.md), → [opportunity-id](../opportunity-id/SKILL.md)). If the user's answer to "who is the customer" is "everyone," say so plainly and start segmenting.
2. **Separate the roles.** Ask who uses, who pays, and who influences. Flag any split between user and buyer (→ [customer-ecosystem](../customer-ecosystem/SKILL.md)).
3. **Draft potential segments.** Split the broad market using the five dimensions (needs/value, channels, service/relationship, economics, willingness to pay). Aim for 3-6 candidate groups.
4. **Write assumptions per segment.** Fill the six-question assumption template for each. Mark which answers are guesses.
5. **Narrow each to a testable statement.** Use the segment statement template until each names a specific group, context, and problem.
6. **Gather evidence.** Interview people in each candidate segment and listen to their stories about their reality (→ [customer-interview](../customer-interview/SKILL.md)). Draft an initial end-user profile for the most promising one (→ [customer-end-user-profile-and-persona](../customer-end-user-profile-and-persona/SKILL.md)).
7. **Re-segment by context.** Regroup by the patterns that actually showed up. Revise or discard segments that the data does not support.
8. **Score candidates.** Run the market-definition conditions and the five evidence questions in the comparison table. Turn every "Unknown" into a task.
9. **Select one beachhead.** Choose the reachable, narrow, first market you can serve well now and learn from quickly. Write it as one segment statement plus its expansion path.
10. **Act, then refine.** Start selling or piloting in the beachhead. Let action produce data and let the data tell you good or bad (→ [customer-validation](../customer-validation/SKILL.md)). Loop back to step 7 when it does.

Deliverable for the user:

```
BEACHHEAD SUMMARY
Beachhead segment statement: _______________________________
User / payer / influencer:   _______________________________
Why this one (evidence):     urgent need ___ | can pay ___ | reachable ___
                             complete solution today ___ | WOM ___
How we reach them:           _______________________________
Expansion path (next 1-2 segments): ________________________
Biggest open assumption + how we will test it: ______________
Next skill to run:           _______________________________
```

## Common Mistakes

- **"Everyone" or "a crowd" as the customer.** Fails the first rule. No one can be reached, interviewed, or served specifically.
- **Stopping at a category.** "Students," "small businesses," "millennials" are categories, not usable segments. Narrow until it names a group, a context, and a problem.
- **Segmenting by demographics alone.** Age and income bands rarely track the dimensions that matter: need, channel, service, economics, willingness to pay.
- **Assuming the user is the buyer.** Kids use, parents pay; employees use, managers buy. Ask all three customer questions.
- **Treating the first segmentation as fact.** Segments begin as assumptions. No interviews means no segmentation, just a guess.
- **Choosing the largest, most obvious market.** The beachhead goal is reachable and narrow, not big.
- **Picking a market with no word of mouth.** Without customers talking to each other, you never get referrals or a repeatable path.
- **Picking a beachhead you cannot fully serve today.** "Can you deliver a complete solution?" is about now, not the roadmap.
- **Running two or three beachheads at once.** That spreads scarce resources and slows learning; it defeats the point of focus.
- **Hunting for the perfect market.** Over-analysis produces no data. Pick on evidence to date, act, and refine.
- **Ignoring the expansion path.** A beachhead that leads nowhere is a niche business, which may be fine, but should be a deliberate choice.

## Worked Examples

### Positive Example: Invoicing Tool for Residential HVAC Contractors

**Situation.** A two-person founding team has built a mobile invoicing and payment-collection app. Their first answer to "who is the customer" was "small businesses."

**What they did.**

1. **Called out the category.** "Small businesses" fails "everyone is not a segment." They split it on the five dimensions:
   - Needs: field-service trades (bill on site, chase payment) vs. retail shops (point-of-sale) vs. consultants (monthly retainers).
   - Channels: trades congregate at supply houses and trade associations; consultants live on LinkedIn.
   - Service: solo tradespeople want zero setup; agencies want integrations and onboarding.
   - Economics: single-truck operators vs. 20-truck companies with an office manager.
   - Willingness to pay: tradespeople already pay for job-management software; freelancers expect free tools.
2. **Wrote six-question assumptions** for four candidate markets: residential HVAC contractors, plumbers, independent landscapers, and freelance designers.
3. **Interviewed** 8-10 people in each over three weeks, mostly by standing in supply-house parking lots and calling association members. They listened to stories, not opinions about the app.
4. **Re-segmented by context.** The pattern that showed up: owner-operators with 1-5 trucks who finish a job, write the invoice that night at the kitchen table, and wait weeks to get paid while buying parts on credit. HVAC contractors described this most urgently because of summer peak-season cash crunches.
5. **Narrowed to a testable statement:** "Owner-operator residential HVAC contractors with 1-5 trucks in the Houston metro who invoice after hours and wait weeks to get paid while carrying parts costs on credit."
6. **Scored candidates:**

| Criterion | HVAC (Houston) | Plumbers | Landscapers | Freelance designers |
|---|---|---|---|---|
| Urgent need | Strong (peak-season cash crunch) | Partial | Weak (seasonal, low tickets) | Partial |
| Can pay | Strong (high-ticket jobs) | Strong | Weak | Weak |
| Reachable | Strong (3 supply houses, 1 association) | Partial | Partial | Weak (scattered) |
| Complete solution today | Strong | Partial (needs permit-fee line items) | Strong | Strong |
| Word of mouth | Strong (talk at supply houses) | Partial | Partial | Weak |
| Expansion path | Plumbers, electricians, other metros | — | — | — |

7. **Picked HVAC Houston as the initial beachhead.** User and payer are the same person (the owner), with the office-manager spouse as influencer, flagged for customer-ecosystem work.
8. **Acted.** Ran a paid pilot with contractors introduced through one supply-house counter manager and tracked how many invoiced from the truck within two weeks.

**Why this is good.**
- Replaced a category with a specific group, context, and problem.
- Segmented on need, channel, service, economics, and willingness to pay, not demographics.
- Every score cites evidence from interviews; nothing is "Unknown" at decision time.
- Chose reachable and narrow over big: HVAC in one metro is far smaller than "small businesses," and that is the point.
- Word of mouth is built in (supply houses), and the expansion path (adjacent trades, other metros) is named.
- Treated the beachhead as **initial** and moved straight to a paid test, so action produced data.

### Negative Example: Plant-Based Protein Snack Startup

**Situation.** A founder launching a plant-based protein bar writes: "Our target market is health-conscious consumers ages 18-45 in the US. The snack bar market is huge, so even 1% is a big business. We will launch nationally on Amazon and Instagram ads and see who buys."

**Why this is awful.**
- **"Health-conscious consumers ages 18-45" is a crowd, not a segment.** It covers gym regulars, new parents, vegans, and diabetics, who differ on needs, channels, service, economics, and willingness to pay.
- **Demographics only.** An age band says nothing about what they are trying to do, what problem occurs, or what they do today.
- **Chose the largest, most obvious market.** The "1% of a huge market" logic is exactly the anti-goal. Size is a market-research question, not a beachhead criterion.
- **No assumptions written, no interviews.** The segment is a guess presented as a fact; there is no evidence gathered to date to base a beachhead on.
- **Not reachable in a focused way.** National ads to a broad audience means paying to reach everyone and learning about no one.
- **No word of mouth.** Strangers across the country who saw an ad do not talk to each other about the brand.
- **No single entry point, no expansion path.** Launching everywhere at once leaves nothing to expand from.
- **User vs. buyer never asked.** For many snacks, a parent buys for a teen or an office manager stocks a break room.

**How to fix it.** Brainstorm 3-6 concrete markets where these customers gather (for example, members of one regional climbing-gym chain, or one university's club sports teams), interview people in each, score them on the evidence questions, and launch in one, where members talk to each other and the gym or team is a single reachable channel.

## Related Skills & Next Steps

- **[problem-statement](../problem-statement/SKILL.md)** — go here first if the problem is unclear, or when segments reveal the problem differs by group.
- **[opportunity-id](../opportunity-id/SKILL.md)** — go here if you are still at the idea stage and have not confirmed an opportunity worth segmenting.
- **[customer-ecosystem](../customer-ecosystem/SKILL.md)** — next, to map who uses, who pays, and who influences the decision in your beachhead.
- **[customer-interview](../customer-interview/SKILL.md)** — next, to talk to people in each candidate segment and gather the evidence that drives re-segmentation and beachhead choice.
- **[customer-end-user-profile-and-persona](../customer-end-user-profile-and-persona/SKILL.md)** — next, to build the initial end-user profile and then the persona for the beachhead.
- **[customer-validation](../customer-validation/SKILL.md)** — after picking the initial beachhead, to refine and test whether those customers will actually buy.
- **[market-research](../market-research/SKILL.md)** — when you need market sizing, secondary data on candidate markets, or competitive analysis.
- **[value-proposition](../value-proposition/SKILL.md)** — once the beachhead is set, to design the value proposition for that segment's jobs, pains, and gains.
- **[business-model](../business-model/SKILL.md)** — to carry the chosen segment into the Customer Segments block and the channels, relationships, and revenue blocks of the Business Model Canvas.
- **[creative-ideation](../creative-ideation/SKILL.md)** — when you cannot come up with 3-6 candidate markets, or need fresh angles on where your customers gather.
- **[pricing-models](../pricing-models/SKILL.md)** — once the beachhead is chosen, to price for that segment's willingness to pay.
