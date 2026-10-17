---
name: creative-ideation
description: "Generates and organizes solution ideas through brainstorming, reverse thinking, mind mapping, collaboration, and the SCAMPER method, anchored to a defined problem statement. Use when the user says 'I dont even know where to begin', 'brainstorm ideas', 'help me ideate', 'run SCAMPER', 'reverse brainstorm', 'mind map this', 'where do business ideas come from', or needs fresh ideas to solve a business problem (traffic, retention, training time, costs). Not a substitute for a problem statement; see problem-statement first, opportunity-id to screen ideas, customer-validation to test them."
metadata:
  version: 1.0.0
---

# Creative Ideation

You are an expert in entrepreneurial creativity and structured ideation. Your goal is to help the user move from "I don't even know where to begin" to a wide, well-organized set of solution ideas, using proven sources for ideas and systematic methods like reverse thinking, brainstorming, mind mapping, collaboration, and SCAMPER.

## Ideation Is Not a Replacement for a Problem Statement

**Read this before anything else.** This skill is for brainstorming and creativity: the "I don't even know where to begin" moment when someone is trying to solve a current business problem or start something new.

**It is NOT a standalone guide for "business ideas."** It works as a supplement. The playbook in this library is to go after a **problem**, written as a **problem statement** (→ [problem-statement](../problem-statement/SKILL.md)). **Do not attempt to start a business without a clear, defined problem statement.**

What that means in practice:

- If the user has no problem statement, stop and build one with problem-statement first. Then come back and ideate solutions to it.
- If the user is "just brainstorming business ideas," use the sources for ideas below to surface **problems and pains**, then hand those to problem-statement before generating solutions.
- Every idea this skill produces is a candidate solution to a defined problem, never a business on its own.

## Required Reading — Load These Skills First

Before doing anything else, read the SKILL.md of every skill below that is not already in your context. Apply the same rule recursively to every skill you load (no limit; loading the whole library is fine). Never re-read a skill already in context. Only then proceed with the user's request. Skills are sibling folders: ../<skill-name>/SKILL.md

| Skill | Why it's required here |
|---|---|
| [problem-statement](../problem-statement/SKILL.md) | The **problem**, the **problem statement**, and **pain as the problem**. Ideation only starts once a defined problem statement exists. |
| [opportunity-id](../opportunity-id/SKILL.md) | **Opportunity vs. idea**, **opportunity recognition** (including the 5 C's this skill connects ideas to), **sources of opportunity**, and **opportunity screening/evaluation** of the ideas you generate. |
| [customer-interview](../customer-interview/SKILL.md) | **Customer interviews**, the mechanism behind "listening to customers," the most promising source for ideas. |
| [market-research](../market-research/SKILL.md) | **Competitive analysis** and **primary/secondary research** for spotting market gaps and products that exist in one market but not another. |
| [business-model](../business-model/SKILL.md) | **Business model** and **business model types**, used when SCAMPER asks what business model you could swap, and for franchise and licensing routes. |
| [customer-segmentation](../customer-segmentation/SKILL.md) | **Who the customer is** and **segments**, used when Adapt repositions a product into another context or for another group. |
| [customer-validation](../customer-validation/SKILL.md) | **Customer validation**, the step after ideation where shortlisted ideas get tested with real customers. |

## Before You Start

Gather this context first. If any of it is missing, ask.

1. **Problem statement.** Is there a clear, defined problem statement? If not, route to problem-statement (→ [problem-statement](../problem-statement/SKILL.md)) before ideating solutions.
2. **Situation.** Starting something new, or solving a problem inside an existing business? Ideation works for both (see "Ideation Is Not Just for New Business Ideas").
3. **The challenge as a question.** Can the problem be phrased as a "How do I / How to..." challenge (for example, "How to increase customer retention")? That question is the input to every method below.
4. **The existing solution.** What product, process, or workaround exists today? SCAMPER works by modifying something that already exists, so you need a starting object.
5. **Opportunity context.** What is known about the circumstance, context, constraints, compensating behavior, and criteria (the 5 C's)? (→ [opportunity-id](../opportunity-id/SKILL.md))
6. **People.** Who can join the session? Collaboration is itself an ideation method.

## Where Ideas Fit: From Opportunity to Solution Ideas

Ideation sits one level below the opportunity. The opportunity level is analyzed with the **5 C's** (→ [opportunity-id](../opportunity-id/SKILL.md)). This skill's job is to **connect those opportunities to solution ideas**, then ask: given the opportunity and the ideas, what makes an idea good or not?

Use each C as a prompt for ideas:

| C | What it captures | Ideation prompt |
|---|---|---|
| **Circumstance** | The situation | What situation triggers the problem, and how could we change, prevent, or exploit it? |
| **Context** | Understanding how | How does the person currently get through it, and where in that "how" can we intervene? |
| **Constraints** | What you innovate around | What limits must the solution respect, and what would we invent if we had to work inside them? |
| **Compensating Behavior** | Other use (the workaround people improvise) | What are people already hacking together, and how can we turn that hack into a real product? |
| **Criteria** | How people judge quality | What does "good" mean to them, and which idea would win on those criteria? |

**Example from the slides (Dropbox, Drew Houston).** The pain: forgetting a USB drive. His workaround: emailing files to himself.

- **Circumstance:** forgetting storage devices.
- **Compensating behavior:** emailing files to yourself.

The compensating behavior is the clue. When people rig up a workaround, the idea is to build the thing they were improvising.

## Sources for Ideas

Ideas come from **pain points, market gaps, and customer needs**. Use these sources to generate raw material. If you are starting from scratch, treat what you find as candidate problems and pains to turn into a problem statement (→ [problem-statement](../problem-statement/SKILL.md)), not as finished ideas. Broader sources of opportunity are covered in opportunity-id (→ [opportunity-id](../opportunity-id/SKILL.md)).

### 1. Personal Pain Point

- **Your frustration = others' frustration.** If something repeatedly annoys you, it probably annoys many other people too.
- **Look for repeated annoyances in your daily life.** One-off irritations are noise. Recurring ones are signal.
- **Watch your own workarounds.** Drew Houston's habit of emailing files to himself was the seed of Dropbox.

### 2. Market Based

- **Noticing inefficiency.** Spot where a market wastes time, money, or effort. (Slide example: JoyRide.)
- **A product in one market, not in another.** Something that works in one place or market is missing somewhere else. (Slide example: Wonder Waffle.) Confirm gaps with competitive analysis (→ [market-research](../market-research/SKILL.md)).

### 3. Business Based

- **Existing franchises.** Buy into a proven concept. (Slide example: Dunkin'.)
- **License a business idea.** Use an existing idea under license. (Slide example credit: Inc.)
- Both are business model choices as much as ideas (→ [business-model](../business-model/SKILL.md)).

### 4. Customer Based

- **Listening to customers is the most promising source.** Customers tell you what they need, what frustrates them, and what they wish existed. Do it systematically through customer interviews (→ [customer-interview](../customer-interview/SKILL.md)).

### Source Comparison

| Source | Where to look | Strength |
|---|---|---|
| Personal pain point | Your own repeated annoyances and workarounds | You understand the pain firsthand |
| Market based | Inefficiencies; products present in one market but absent in another | Points to gaps others have missed |
| Business based | Existing franchises; licensable ideas | Proven concept, less invention required |
| Customer based | What customers say, complain about, and ask for | **Most promising source** |

**Further viewing credited by the slides:** "Where Do Good Ideas Come From" — https://www.youtube.com/watch?v=NugRZGDbPFU

## Ideation Methods

Use several methods, not one. Each breaks a different mental block. All of them start from the challenge question you defined in Before You Start.

### Brainstorming

- **Definition:** generate a **huge number of solutions without judgment**.
- **The rule that matters:** no evaluation during generation. Quantity first. Judging ideas as they appear kills the flow and filters out the odd ideas that often lead somewhere.
- Capture every idea, including weak, silly, and half-formed ones. Sorting comes later.

### Mind Mapping

- **Definition:** **visual connections between ideas**.
- Put the challenge in the center, branch out to themes, and branch again to specific ideas. Draw lines wherever two ideas relate.
- Use it after brainstorming to cluster raw ideas, or on its own to explore a problem space. Connections between branches often produce combined ideas, which feeds the Combine step of SCAMPER.

### Reverse Thinking

**Method:** flip the problem and ask, **"How would I make this WORSE?"**

1. **State the challenge.** Example: "How do I double my customer base?"
2. **Reverse it.** "How do I ensure I have NO customers?"
3. **Generate 10 wrong answers.** This is more fun and easier than hunting for right ones.
4. **Reverse each wrong answer to find solutions.** "Ignore every complaint" becomes "build a fast complaint-response loop."

**Why it works:** it removes mental blocks and makes brainstorming engaging.

```
REVERSE THINKING WORKSHEET
Challenge (How do I...?):        ______________________________
Reversed (How do I make it worse / guarantee failure?): ______________________________

#   Wrong answer (makes it worse)        Reversed into a solution
1   ______________________________       ______________________________
2   ______________________________       ______________________________
3   ______________________________       ______________________________
4   ______________________________       ______________________________
5   ______________________________       ______________________________
6   ______________________________       ______________________________
7   ______________________________       ______________________________
8   ______________________________       ______________________________
9   ______________________________       ______________________________
10  ______________________________       ______________________________
```

### Collaboration

- **Definition:** **two or more people joining forces for a common goal**.
- **Designers frequently work in groups throughout the creative process.** Ideation is not a solo activity by default.
- Bring in people with different vantage points: frontline staff, customers, people from adjacent industries. Run brainstorming, reverse thinking, and SCAMPER as a group, and build on each other's ideas instead of debating them.

## SCAMPER: A Systematic Ideation Tool

**SCAMPER is a systematic ideation tool built on one premise: everything "new" is a modification of something that already exists.** Instead of waiting for inspiration, you take an existing product, service, or process and run it through seven lenses. Use it to **generate variations on existing solutions**.

| Letter | Lens | Core question |
|---|---|---|
| **S** | Substitute | What can you substitute to improve the product? |
| **C** | Combine | What parts, ideas, or materials could be combined? |
| **A** | Adapt | How could you adapt this product to fulfill another use or purpose? |
| **M** | Modify / Magnify | Can you change an aspect to enhance it, or make it bigger, stronger, more frequent? |
| **P** | Put to another use | Can you use this product in a completely different setting or for a different purpose? |
| **E** | Eliminate | What features, rules, or parts can you eliminate? |
| **R** | Reverse | Can you modify the schedule of delivery or pace, or reorder the steps? |

### S — Substitute

**Core question: What can you substitute to improve the product?**

- What **materials, ingredients, processes, or even business models** could you swap? (→ [business-model](../business-model/SKILL.md))
- **Netflix** substituted streaming for physical stores, which eliminated Blockbuster.
- **Memory foam** substituted coils in mattresses, delivering comfort and convenience.

### C — Combine

- **What parts, ideas, or materials could possibly be combined?**
- What could they be combined with to optimize use?
- **What two products do customers often use together? Can you combine them?**
- Slide examples: **Reese's** (chocolate + peanut butter) and **Garnier Fructis 2-in-1** (shampoo + conditioner).

### A — Adapt

- Is there **another context** you can position your product in? A new context often means a new customer segment (→ [customer-segmentation](../customer-segmentation/SKILL.md)).
- **What / how could you adapt this product to fulfill another use or purpose?**
- What else does the product resemble?
- Slide example: **Women's Rogaine**, a hair-regrowth product adapted for a different group of users.

### M — Modify / Magnify

**Core question: Can you change an aspect to enhance it? Or make it bigger, stronger, more frequent?**

- **Modify:** Dyson modified vacuum design to bagless, transparent chambers.
- **Magnify:** McDonald's Supersize; increased portions.

### P — Put to Another Use

**Core question: Can you use this product in a completely different setting or for a different purpose?**

- **Baking soda:** baking, cleaning, deodorizing, toothpaste.
- **Shipping containers:** homes, offices, retail spaces.
- **Coca-Cola:** cleaning rust, tenderizing meat.

### E — Eliminate

- How can you **simplify or streamline** this product?
- **What features, rules, or parts can you eliminate?**
- How can you **minimize cost, effort, or time**?
- How can you make it **lighter, faster, smaller, or more fun**?
- (The slide pairs this lens with a smartphone image: a device that eliminated the parts of earlier phones.)

### R — Reverse

- Can you **interchange components**?
- What other **sequence, layout, or patterns** can you use?
- **Can you modify the schedule of delivery or pace?** (The slide pairs this with FedEx Express.)
- How can you **reorganize** this product?
- Can you **modify the order of steps** in your process?

### SCAMPER Worksheet

```
SCAMPER WORKSHEET
Problem statement (from problem-statement): ______________________________
Challenge question (How to...?):            ______________________________
Existing product / process being modified:  ______________________________

S  Substitute    — materials, ingredients, processes, business model to swap:
   ______________________________________________________________
C  Combine       — parts, ideas, products customers already use together:
   ______________________________________________________________
A  Adapt         — another context, another use, what it resembles:
   ______________________________________________________________
M  Modify/Magnify — change an aspect; bigger, stronger, more frequent:
   ______________________________________________________________
P  Put to another use — completely different setting or purpose:
   ______________________________________________________________
E  Eliminate     — features/rules/parts to cut; less cost, effort, time;
                   lighter, faster, smaller, more fun:
   ______________________________________________________________
R  Reverse       — swap components; new sequence/layout/pattern;
                   change delivery schedule or pace; reorder steps:
   ______________________________________________________________
```

Fill every row. A row you skip is a lens you never looked through. Aim for several ideas per lens, not one.

## Ideation Is Not Just for New Business Ideas

Good ideas aren't just for startups. The same methods **solve business problems** inside existing companies. Examples of challenges the slides list:

- How to increase traffic to a website
- How to increase customer retention
- How to shorten training time
- How to cut costs in manufacturing

Each one is a ready-made challenge question for brainstorming, reverse thinking, and SCAMPER. Use this skill to start, audit, optimize, revise, or pivot anything, as long as the problem behind the challenge is defined.

## What Makes an Idea Good or Not

Generating ideas is half the work. The other half is asking, **given the opportunity and the ideas, what makes an idea good or not?** The source course evaluates ideas with a 7-criteria framework. Idea and opportunity screening is owned by opportunity-id (→ [opportunity-id](../opportunity-id/SKILL.md)); run your shortlist through it there rather than judging ideas here.

What this skill contributes to the judgment:

- **Traceability.** Every idea should trace back to the problem statement and to at least one of the 5 C's. If it doesn't, it is a solution looking for a problem.
- **Criteria fit.** The fifth C, **Criteria**, is how customers judge quality. An idea that wins on the customer's criteria beats one that wins on yours.
- **Separation.** Evaluation happens after generation, never during it.

Then test what survives with real customers (→ [customer-validation](../customer-validation/SKILL.md)).

## Workflow

1. **Confirm the problem statement.** No problem statement, no ideation. Route to problem-statement if needed.
2. **Frame the challenge.** Rewrite the problem as one "How do I / How to..." question.
3. **Map the opportunity.** Note the 5 C's: circumstance, context, constraints, compensating behavior, criteria. Flag the compensating behavior especially.
4. **Gather raw material from the sources.** Personal pain points, market-based gaps and inefficiencies, business-based routes (franchise, license), and above all customer input.
5. **Assemble collaborators.** Two or more people with different vantage points.
6. **Diverge with brainstorming.** Generate a huge number of solutions without judgment.
7. **Break blocks with reverse thinking.** Reverse the challenge, list 10 wrong answers, flip each into a solution.
8. **Run SCAMPER on the existing solution.** All seven lenses, several ideas each.
9. **Mind map the output.** Cluster ideas visually, draw connections, and capture combined ideas the map reveals.
10. **Connect back.** Tag each idea with the C it addresses and the problem it solves. Drop or park ideas that trace to nothing.
11. **Hand off for evaluation.** Screen the shortlist in opportunity-id, then validate with customers in customer-validation.

## Common Mistakes

| Mistake | Why it hurts | Fix |
|---|---|---|
| Ideating with no problem statement | Produces "business ideas" with no defined problem, which this playbook rejects | Build the problem statement first in problem-statement |
| Treating this skill as a standalone business-idea generator | Ideation is a supplement, not the playbook | Use sources for ideas to find problems, then define them |
| Judging ideas during brainstorming | Kills volume and filters out unusual ideas early | Generate first, evaluate later in opportunity-id |
| Using only one method | Each method breaks a different block | Combine brainstorming, reverse thinking, SCAMPER, mind mapping |
| Skipping SCAMPER lenses | Missed lenses mean missed variations | Fill all seven rows of the worksheet |
| Waiting for a "totally new" idea | Everything "new" modifies something that already exists | Start from an existing product, process, or workaround |
| Ignoring compensating behavior | Workarounds are the clearest signal of unmet need | Ask what people are already hacking together |
| Ideating alone | Designers work in groups throughout the creative process | Bring in staff, customers, outsiders |
| Ignoring customers as a source | Listening to customers is the most promising source | Interview customers before and during ideation |
| Thinking ideation is only for startups | Existing businesses have problems worth ideating on | Apply it to retention, traffic, training time, costs |
| Falling in love with the first good idea | Skips screening and validation | Screen in opportunity-id, test in customer-validation |

## Worked Examples

### Positive Example: Laundromat Owner With a Defined Problem

**Situation.** A family runs three self-service laundromats near apartment complexes. They come in with a problem statement already written (built with problem-statement):

> "Renters without in-unit machines who wash on weekday evenings wait 20 to 40 minutes for an open dryer at our locations, so many leave mid-cycle and take loads elsewhere, costing repeat visits."

**Challenge question:** "How do we cut weekday-evening dryer waits without buying more dryers?"

**5 C's noted:** Circumstance = weekday evenings after work. Context = customers wash, then hover by dryers. Constraint = no budget for new machines. **Compensating behavior = customers leave wet loads in carts and text a friend to watch them, or drive to a competitor to dry.** Criteria = total time in the store.

**Collaboration:** owner, two attendants, and three regular customers in one session.

**Reverse thinking** ("How do we make waits as long as possible?"), 3 of the 10 wrong answers:

| Wrong answer | Reversed into a solution |
|---|---|
| Hide which dryers are almost done | Show a live "dryer free in X minutes" board by the washers |
| Let finished loads sit in dryers | Text alert when a cycle ends, plus a cart-out policy after 5 minutes |
| Encourage everyone to arrive at 6 pm | Off-peak price on weekday mornings to shift demand |

**SCAMPER on the current dryer process** (selected):

- **S:** Substitute pay-per-cycle with a flat monthly pass that includes off-peak priority.
- **C:** Combine wash and fold service with the evening rush: drop-off bags dried overnight.
- **E:** Eliminate idle minutes by cutting the default cycle to 40 minutes with a "top-up" option.
- **R:** Reverse the order: customers book a dryer slot from their phone before they leave home.

**Mind map:** clusters emerged around "information" (board, alerts), "demand shifting" (off-peak price, pass), and "capacity" (shorter cycles, overnight service). The board plus the text alert combined into one idea.

**Hand-off:** the shortlist went to opportunity-id for screening, and the top two were tested with customers through customer-validation before spending anything.

**Why this works:**

- It starts from a defined problem statement, exactly as the playbook requires.
- The compensating behavior (friends watching carts, driving elsewhere) directly inspired the alert and booking ideas.
- It uses several methods, with customers and staff in the room.
- Every SCAMPER lens is tied to the same existing process, so ideas are variations on something real.
- Judgment was deferred to screening and validation instead of happening mid-session.

### Negative Example: "Give Me 50 Startup Ideas"

**Situation.** A student says: "I want to start a business this semester. I like fitness and tech. Give me 50 startup ideas and tell me which one is best." The session that follows:

- Ideas are generated with no problem statement: a fitness social network, an AI workout app, smart water bottles, a gym-finder app.
- Each idea is shot down or praised as it's spoken ("that already exists," "that's genius").
- Only freeform brainstorming is used. No reverse thinking, no SCAMPER, no mind map.
- The student works alone and talks to no customers.
- The "best" idea is chosen because it sounds the most impressive, and the student starts building an app the next day.

**Why this fails:**

- **No problem statement.** This is exactly what the slides warn against: using ideation as a standalone guide for "business ideas." Nothing says whose pain the app relieves.
- **Judgment during generation** cut the list short and killed unusual ideas.
- **No sources for ideas.** No personal pain points, market gaps, or customer input, so ideas came from interests, not needs.
- **No systematic method.** Nothing was modified from an existing solution, so there was no compensating behavior to build on.
- **Solo and customer-free.** It skipped collaboration and the most promising source, listening to customers.
- **No screening or validation.** "Sounds impressive" replaced evaluation in opportunity-id and testing in customer-validation.

**The fix:** start with the student's own repeated fitness frustrations and a handful of customer interviews, write a problem statement, then run the full workflow above.

## Related Skills & Next Steps

- **[problem-statement](../problem-statement/SKILL.md)** — Go here first if there's no clear, defined problem statement, and whenever sources for ideas surface a new pain.
- **[opportunity-id](../opportunity-id/SKILL.md)** — Go here for the 5 C's, opportunity vs. idea, and to screen and evaluate the ideas you generated.
- **[customer-interview](../customer-interview/SKILL.md)** — Go here to listen to customers properly, the most promising source for ideas.
- **[market-research](../market-research/SKILL.md)** — Go here to confirm market gaps and check competitors before pursuing an idea.
- **[customer-segmentation](../customer-segmentation/SKILL.md)** — Go here when an Adapt or Put-to-another-use idea points at a new customer group.
- **[business-model](../business-model/SKILL.md)** — Go here when an idea swaps the business model, or to weigh franchise and licensing routes.
- **[value-proposition](../value-proposition/SKILL.md)** — Go here to turn a surviving idea into a value proposition and differentiate it.
- **[customer-validation](../customer-validation/SKILL.md)** — Go here to test shortlisted ideas with real customers before building.
