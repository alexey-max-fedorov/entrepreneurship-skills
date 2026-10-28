---
name: problem-statement
description: "The library entry point and starting point for any venture. Finds, diagnoses, writes, tests, and validates the problem a business solves: problem vs. solution, pain types, problem evidence, symptoms vs. root causes, Jobs-to-Be-Done, problem laddering, workarounds, four problem statement frameworks (Simple, Jobs-to-Be-Done, Empathy Based, Quantified), the Problem Statement Test, and problem validation with Proceed/Pivot/Punt. Use when the user says 'I have a startup idea', 'where do I start', 'what problem am I solving', 'write my problem statement', 'is this a real problem', 'root cause', 'why is my business struggling', 'should we pivot', or wants to start, audit, revise, or pivot any venture. Always load with opportunity-id. Related: customer-segmentation, customer-interview, customer-validation, market-research, value-proposition."
metadata:
  version: 1.0.1
---

# Problem Statement

You are an expert in problem discovery, root-cause diagnosis, and writing testable problem statements for new and existing ventures. Your goal is to make sure every business the user works on is built on a real, specific, validated problem that people actually feel and would pay to solve, before anyone falls in love with a solution.

## Required Reading — Load These Skills First

Before doing anything else, read the SKILL.md of every skill below that is not already in your context. Apply the same rule recursively to every skill you load (no limit; loading the whole library is fine). Never re-read a skill already in context. Only then proceed with the user's request. Skills are sibling folders: ../<skill-name>/SKILL.md

| Skill | Why it's required here |
|---|---|
| [opportunity-id](../opportunity-id/SKILL.md) | **Must always be loaded together with this skill.** problem-statement is its prerequisite; opportunity-id is the supplement. Owns opportunity vs. idea, opportunity recognition, sources of opportunity, problems worth solving, and opportunity screening/evaluation (the "opportunity lies in the gap" step that follows a defined problem). |
| [customer-segmentation](../customer-segmentation/SKILL.md) | Owns who the customer is, segments, and the beachhead market. Needed for the **specific user** slot in every framework and the "wrong user (everyone)" mistake. |
| [customer-interview](../customer-interview/SKILL.md) | Owns customer interviews, the main tool for gathering problem evidence and validating the statement ("Tell me about the last time this happened"). |
| [customer-validation](../customer-validation/SKILL.md) | Owns customer validation, the step after the problem is validated (confirming who will buy). |
| [market-research](../market-research/SKILL.md) | Owns primary/secondary research and market sizing. Needed for the "can be validated with research" criterion, the Quantified framework's numbers, and "enough of the right people." |
| [value-proposition](../value-proposition/SKILL.md) | Owns customer jobs/pains/gains, value proposition, and differentiation. Needed for the Jobs-to-Be-Done lens and the "can't differentiate" mistake. |
| [customer-end-user-profile-and-persona](../customer-end-user-profile-and-persona/SKILL.md) | Owns the end user profile and persona. Needed to make the **(User)** slot concrete enough to name real people. |
| [customer-ecosystem](../customer-ecosystem/SKILL.md) | Owns stakeholder roles. Needed when the person who feels the pain is not the person who pays (the willingness-to-pay check). |
| [creative-ideation](../creative-ideation/SKILL.md) | Owns brainstorming and ideation techniques, used only after the problem is defined to generate solutions to it. |

## Before You Start

This is the **single most important skill in the library** and the **main starting point** for anyone attempting to start a business or venture. The reason: *the majority of failed startups fail because they sell a solution to a problem nobody had, or nobody was willing to pay for.* Everything else in the library (customers, value proposition, business model, research) builds on the problem defined here.

The skill applies whether the user is starting from nothing, already has a solution in mind, is auditing an existing business, diagnosing declining results, rewriting a pitch, or deciding whether to pivot.

Gather this before writing anything (ask only for what's missing):

1. **Who** experiences the problem? As specific as possible: role, situation, life stage.
2. **What happens**, concretely? The situation, the pain, and the consequence.
3. **How often** does it happen?
4. **What does it cost** them: time, money, stress, embarrassment?
5. **Why** does it happen? What do they believe causes it?
6. **What do they do about it today?** Workarounds, partial solutions they pay for, compromises they accept.
7. **What evidence exists?** Interviews held, observations, data, research. Or is it an assumption so far?
8. **Does the user already have a solution in mind?** That's fine. Note it, set it aside, and work backward to the problem it supposedly solves.

If the user only has a solution ("I want to build an app that…"), don't reject it. Translate it: *"What is the person, situation, pain, and consequence this exists for?"*

## Why Problem Identification Matters

### Why entrepreneurship (context from the slides)

| Impact | What the slides say |
|---|---|
| **Economic** | Startups create jobs faster than established firms. In the US, small business employs ~47% of the workforce. |
| **Personal** | Control over your destiny, potential financial independence, meaningful work. |
| **Social** | Create solutions to real problems; improve quality of life. |
| **Career relevance** | Entrepreneurial thinking applies even in corporate roles (**intrapreneurship**). |

Every one of these depends on solving a *real* problem. The social impact line says it directly: solutions to **real problems**.

### The stakes

- **The Startup Graveyard:** startups die solving a weak or nonexistent problem. Resources are limited, and a non-problem wastes them.
- **Investor reality:** investors invest in solutions to real problems. **A weak problem = no funding.**
- **Product-market fit:** there is no product-market fit if you don't understand the problem.
- **Problem reality:**
  - **Execution cannot rescue a problem that customers do not care enough to solve.**
  - **Understanding the problem improves every later decision.**

### The two paths

```
Weak Problem Statement   → Weak Foundation → Wasted effort, wrong solution  → Failed Business
Strong Problem Statement → Clear Direction → High chance of Product/Market Fit → Successful Business
```

> **Fall in love with the problem, not your solution.**

## A Problem Is Not an Idea

**Problem ≠ Solution.** A problem is not an idea (for the full idea vs. opportunity distinction → [opportunity-id](../opportunity-id/SKILL.md)).

| | Example |
|---|---|
| **Problem** | I spend 20 minutes looking for parking before class and arrive stressed. |
| **Solution** | Build a parking app. |

**Start with the person, situation, pain, and consequence, not the product.**

The test: *which of these tells you something you can interview people about?* Only the problem. You can ask people how long they search for parking, how it makes them feel, and what it costs them. You can't interview anyone about an app that doesn't exist. **The answer is the problem statement.**

### The four building blocks of a raw problem

```
Person:       [who, specifically]
Situation:    [when / where it happens]
Pain:         [what goes wrong]
Consequence:  [what it costs them: time, money, stress, missed outcomes]
```

## What a Problem Is

> **Problem:** A recurring obstacle that prevents a person from making progress toward something they value.

Three parts matter in that definition: **recurring** (not one-off), **obstacle** (something in the way), and **something they value** (progress they actually care about).

### Pain as the problem: the three pain types

| Pain type | What it costs | Example |
|---|---|---|
| **Functional** | Time / effort | It takes 3+ hours to do laundry. |
| **Financial** | Cost / loss | College students struggle to afford textbooks. |
| **Emotional / Social** | Stress, uncertainty, embarrassment | Students avoid talking in class because they fear negative judgment or embarrassment. |

Many strong problems carry more than one type (the parking problem is functional *and* emotional). Name every type present, because each becomes a measurable consequence in the problem statement. For how pains feed the value proposition later → [value-proposition](../value-proposition/SKILL.md).

### The problem in entrepreneurial terms: current state vs. desired state

| Current state | Desired state |
|---|---|
| I spend 3 hours every week doing laundry. | Have clean clothes with minimal time and disruption. |

**The opportunity lies in the gap** between the two (evaluating that gap as an opportunity → [opportunity-id](../opportunity-id/SKILL.md)).

Before jumping to solutions, **explore the gap's components**. For laundry: wait time, machine availability, transporting laundry, bad hours. Each component is a candidate sub-problem, and the right solution depends on which one actually drives the pain.

```
Current state:  [what is happening now, with a number if possible]
Desired state:  [what the person wants instead]
Gap components: [1] ... [2] ... [3] ... [4] ...
```

## Real Problems: The Evidence Criteria

**Not all problems are worth solving.** (Screening a problem as a business opportunity → [opportunity-id](../opportunity-id/SKILL.md).) Before a problem gets a statement, it must pass these evidence criteria.

### 1. The problem is real (not imagined)

- People actually experience it.
- It can be validated with research and interviews (→ [market-research](../market-research/SKILL.md), [customer-interview](../customer-interview/SKILL.md)).
- **A preference is not necessarily a problem.**

| Bad | Good |
|---|---|
| "I wish this coffee cup came in my favorite color." (preference) | "Coffee cools down too quickly in a ceramic cup." (real, measurable problem) |

### 2. People feel it, regularly, and it costs them

Real problems show these signals:

- **People feel the problem.**
- **People experience it regularly** (daily, weekly, monthly, etc.).
- **It causes frustration, costs money, or creates inefficiency.**
- **People already spend money, time, or effort, or accept a compromise (workaround), to deal with it.** This is the strongest signal: existing spending proves the pain is worth something.

### 3. It affects multiple people

- It **affects multiple people**, not just you.
- **Enough of the "right" people** experience it (→ [customer-segmentation](../customer-segmentation/SKILL.md)).
- **A small market can be good if the pain is intense, frequent, and expensive.**

| Bad | Good |
|---|---|
| "The font on my bank's website is bad." (personal) | "Small business owners find existing accounting software too hard to learn/use." (broad, shared) |

### 4. It is specific

- The problem is **not vague**.
- You can **state exactly** what the problem is.
- The problem can be **measured or observed**.
- You can **explain why the problem exists**.

| Bad | Good |
|---|---|
| "People hate technology." (too vague) | "Seniors struggle to use modern smartphones because text is too small and there are too many features to understand." (specific, measurable) |

### Real-problem checklist

| Criterion | Pass? |
|---|---|
| Real, not imagined; not just a preference | ☐ |
| People feel it | ☐ |
| Happens regularly (state the frequency) | ☐ |
| Causes frustration, costs money, or creates inefficiency | ☐ |
| People already spend money/time/effort or accept a workaround | ☐ |
| Affects multiple people, enough of the right ones | ☐ |
| If the market is small: pain is intense, frequent, and expensive | ☐ |
| Specific: can be stated exactly, measured or observed | ☐ |
| You can explain why it exists | ☐ |
| Can be validated with research and interviews | ☐ |

## Symptoms, Causes, and Root Causes

A strong problem means **you understand WHY the problem exists (the cause).**

- **Do not look at the outcome.** The outcome (declining sales, sad employees) is where you notice the problem, not what you solve.
- **Investigate causes before choosing what to solve.**
- **The first explanation may not be the root cause.**

| Level | Definition | Example |
|---|---|---|
| **Symptom** | The visible outcome | Employees are sad. |
| **Cause** | Why the symptom happens | They don't understand how their work contributes to company goals. |
| **Root cause** | The deepest driver you can act on | They see no path for career growth. |

"Employees are sad" alone is a symptom, not a cause. A good version names both: *Employees are sad because they don't understand how their work contributes to company goals (cause) and they see no path for career growth (root cause).*

### Worked diagnosis: restaurant with declining sales

| Step | Statement | Assessment |
|---|---|---|
| Symptom 1 | "We're not making money." | Vague; could have 100 causes. |
| Symptom 2 | "Customer traffic is down 30%." | Better, yet not the cause. |
| Symptom 3 | "Customers say our restaurant is hard to find." | Getting closer; learning why. |
| **Cause (root)** | "We have low visibility: our location is on a side street, so we get no foot traffic; our sign is small and doesn't show on the main road; and we don't appear correctly in Google Maps." | Actionable. |

The lessons:

- **Declining sales is the outcome.**
- **Low visibility is a possible cause.**
- **Interviews and data are needed to confirm it.** A root cause is a hypothesis until validated.

This is how to use the skill on an *existing* business: start from the symptom the owner reports and descend until you reach something specific and actionable.

## How to Identify Problems: Four Methods

### Method 1: Jobs-to-Be-Done

**People don't want products; they want to accomplish a job.** Understand the job to accomplish, and you understand the problem. (The full customer jobs/pains/gains model → [value-proposition](../value-proposition/SKILL.md).)

| Product bought | What they actually want (the job) |
|---|---|
| A drill | A hole |
| Uber | To get somewhere (not a car) |
| Advil | To stop a headache (not pills) |

> **Problem = the gap between the "job to be done" and the current solution(s).**

Example:

- **Job:** I need to get across the city for a meeting.
- **Solution (old):** Taxis: unreliable, expensive, inconsistent.
- **Solution (new):** Uber/Lyft: reliable, cheaper, consistent.
- **Problem solved:** Unreliable, expensive transportation to get across town.

```
Job to be done:            [what the person is trying to accomplish]
Current solution(s):       [what they use today]
Shortfalls of current:     [unreliable / expensive / slow / inconsistent / ...]
Problem (the gap):         [job] is blocked by [shortfalls]
```

Always ask: **what progress is the customer trying to make?**

### Method 2: Problem Laddering (ask "Why?")

**Keep asking "Why?" until you find the cause (root).**

Example, college student food issue:

1. **Problem:** I'm hungry between classes but I don't eat.
2. *Why don't you eat?* I can't afford to buy food on campus; it's too expensive.
3. *Why is campus food too expensive?* A meal costs $15–18; I have a meal budget of $50/week.
4. *Why is your meal budget only $50/week?* My part-time job pays $12/hour, I work 10 hrs/week, and after rent/tuition there's little money left.
5. **Problem actual:** Students are (sometimes) hungry because part-time wages don't cover both tuition/rent and food.

Notice how the "actual" problem differs from the starting problem: the starting point suggests cheaper campus food; the root suggests something about income versus fixed costs. Different root, different solution space.

**Laddering can branch.** Example, student procrastination:

- **Problem:** I always wait until the last minute to start assignments, then I'm stressed and my work suffers.
- *Why do you wait until the last minute?* Possible answers from different people:
  - "The deadline doesn't feel real until it's a few days away."
  - "I would rather hang with friends."
  - "I always think it will take less time than it does."

Three different root causes, three different businesses. **You have to test to find the actual root cause.** Never pick the branch you like best; pick the one the evidence supports.

Following the first branch all the way down shows what a complete ladder looks like:

```
Problem: I always wait until the last minute, then I'm stressed and my work suffers.
Why wait?                  → The deadline doesn't feel real until it's a few days away.
Why doesn't it feel real?  → It's 3 weeks away; my brain doesn't perceive it as urgent.
Why need urgency to act?   → Without urgency, I do things I enjoy more (socializing, streaming).
Why choose enjoyable?      → The assignment doesn't feel relevant; I don't see why I have to do it.
Why not relevant?          → It isn't connected to real-world applications.
ROOT CAUSE: Because assignments lack clear relevance and meaningful deadlines, students'
brains do not perceive them as urgent priorities compared to immediate pleasures,
so they procrastinate.
```

```
Problem:       ...
Why? →         ...
Why? →         ...
Why? →         ...
Why? →         ...
Why? →         ...
Problem actual (root): Because [cause], [who] [behavior], resulting in [consequence].
Competing branches to test: [a] ... [b] ... [c] ...
```

### Method 3: Observation & Listening

**Listen for what people complain about.**

| Listen for | What it sounds like |
|---|---|
| **Complaints and frustrations** | "This is so annoying." |
| **Workarounds** | "I just do it this way instead." |
| **Delays** | "I've just accepted that." |
| **Money spent on partial solutions** | "I keep paying for…" |
| **Emotional language** | "This makes me so frustrated." |

**NOT** these. They are solutions, not problems:

- "You should make an app that…"
- "Someone should invent…"
- "Wouldn't it be cool if…"

Example: asked "What is the problem?", one person says *"We need a better app for finding parking"* (a solution). Another says *"I waste 20 minutes searching for parking downtown; it's stressful and makes me late to meetings."* The problem is **a time-consuming, stressful parking search, not an app.**

**Turn one complaint into several candidate problems before choosing.** That same parking complaint holds at least three: a time-consuming, stressful search; no dedicated garage or spot; arriving late after all the spots are taken. Each points to a different solution space.

> **Goal: understand the problem THEN the solution.**

### Method 4: Identify Workarounds

**Workarounds reveal problems (logic):** nobody builds a workaround for something that doesn't hurt.

Example: students share access codes, photograph textbook pages, or use library-reserve copies because required digital access and textbooks are costly.

- **Problem (surface):** Textbooks are expensive and some students can't afford them.
- **Problem actual:** Cost **and access** constraints.

The workaround exposed a second dimension (access) that the surface statement missed.

Second example, student group projects:

- **Observed:** group projects run on text threads, shared docs, and last-minute calls.
- **Workaround:** juggling several disconnected tools (reminders, texts, emails, calls).
- **Problem:** coordinating group work is frustrating and inefficient.
- **Problem hypothesis:** student teams lack one simple, shared system for task ownership, deadlines, and communication.

```
Observed behavior:   ...
Workaround:          ...
Problem:             ...
Problem hypothesis:  [who] lacks [what] for [job]
```

### Discovery prompts

When the user has no problem yet, start here:

- What's one **recurring frustration** you experienced in the past seven days?
- Can you think of an **industry that seems "stuck" in old ways**?

Then run the candidate through the evidence criteria and the four methods above. (Broader sources of opportunity → [opportunity-id](../opportunity-id/SKILL.md); generating many candidates → [creative-ideation](../creative-ideation/SKILL.md).)

## The Problem Statement

> **A problem statement is a clear, concise description of the problem.**

A problem statement:

- **Explains what the problem is**
- **Explains who has the problem**
- **Explains why it matters**
- **Is specific enough to guide solution development**
- **Is validated through research/interviews**

Its job runs in sequence:

```
Clarity → Direction → Validation
```

Clarity about what the problem is gives direction for what to build, and the statement is concrete enough to be validated (or killed) through research and interviews. It must be **testable**: every claim in it should be something you can check.

## Problem Statement Frameworks

Four frameworks, ranked:

| Framework | Rating | Best for |
|---|---|---|
| **Quantified** | "More advanced, but GREAT if it can be legitimately done." | When you have real numbers from interviews, observation, or research. |
| **Simple** | "The classic. Absolutely great one, arguably the best (besides the Quantified one)." | The default. Use it first for almost any problem. |
| **Jobs-to-Be-Done** | "Pretty good one." | When the problem is best framed as a goal people can't accomplish. |
| **Empathy Based** | "Still OK, but not the best compared to the other frameworks." Make sure the [User] would be willing to pay. | Emotion-heavy problems; always pair with a willingness-to-pay check. |

**Default choice:** write the **Simple** version first. Upgrade to **Quantified** once you have numbers you can support. Use the others as alternate lenses when they fit the problem better.

### Framework 1: Simple (the classic)

```
(Specific user) experiences (specific problem)
when (context)
because (cause/barrier).
This creates (measurable consequence: time / money / emotional toll)
every (frequency).
```

| Slot | What goes here |
|---|---|
| Specific user | A narrow, nameable group (→ [customer-segmentation](../customer-segmentation/SKILL.md)) |
| Specific problem | The pain, not a missing product |
| Context | The situation in which it happens |
| Cause/barrier | The root cause from laddering |
| Measurable consequence | Time, money, or emotional toll, with a number |
| Frequency | Daily, weekly, per semester, per order, etc. |

**Bad:** "Commuting is bad."

**Good:** *Commuters (user) spend 45 minutes each day in traffic (problem) when traveling to a job with a strict 9am start time (context) because of recurring congestion during peak commuting periods (cause), costing them 3.75 hours per week (measurable consequence) they could spend with family or other things.*

### Framework 2: Jobs-to-Be-Done

```
When (user) wants to (job to be done),
but (obstacle) prevents them,
causing (consequence).
```

**Bad:** "People need better email."

**Good:** *When dealing with 200+ daily emails, workers (user) want to find important messages quickly (job to be done), but the search and filter functions don't work well (obstacle), causing them to miss important messages and spend 2 hours daily managing their inbox (consequence).*

### Framework 3: Empathy Based

```
(User) is trying to (accomplish)
but struggles because (obstacle).
They feel (emotion) because (reason).
The impact is (specific consequence),
which happens (frequency).
```

**Example (Empathy Map):** *College students (user) are trying to afford an education (accomplish) but struggle because textbooks cost $200+ per book (obstacle). They feel frustrated and anxious (emotion) because they can't afford all required materials (reason). The impact is they skip buying some textbooks or go into debt (specific consequence), which happens multiple times per semester (frequency).*

**Rule for this framework:** when using it, **make sure the [User] would be willing to pay.** Emotional framing makes a problem feel urgent even when nobody would spend money to fix it. If the user who feels the emotion isn't the one who pays, identify the payer (→ [customer-ecosystem](../customer-ecosystem/SKILL.md)).

### Framework 4: Quantified (advanced)

```
(X%) of (target user) experience (specific problem).
This costs them (quantified impact) per (timeframe).
Current solutions only solve (%) of the problem
because (limitation).
```

**Example:** *62% of small restaurant owners (user) struggle with staff scheduling (problem). This costs them more than 5 hours per week in manual scheduling and $2K monthly in overtime (quantified impact + timeframe) due to inefficient shifts. Current solutions (pen and paper or basic spreadsheets) solve only 40% of the problem because they don't account for real-time availability changes (limitation).*

Rules:

- **Use only numbers you can support!**
- **If you don't know, validate it through interviews, observation, and research** (→ [customer-interview](../customer-interview/SKILL.md), [market-research](../market-research/SKILL.md)).
- "Legitimately done" is the condition on this framework's rating. An invented percentage destroys the statement's credibility. If a number is an estimate, label it as one and mark it for validation.

This framework is the strongest because it adds two things the others lack: **how many** of the target user have the problem, and **how well current solutions fall short**, which is the gap a new solution can fill.

## The Problem Statement Test

Run every draft through all seven questions. Any "no" is a gap to fix before moving on.

| Test | Question |
|---|---|
| **Ask** | Can I explain this in 2–3 sentences? |
| **Specific user** | Can I name people who have this problem? |
| **Frequency** | Does this problem happen at least (X) for the specific user? |
| **Impact** | Can I quantify the impact (time, money, emotional cost)? |
| **Cause** | Do I know the why? |
| **Evidence** | Do I have real evidence of the problem? |
| **Pay** | Would people pay to solve this? |

### Applying the test: before and after

**Improve this:** "Finding housing is hard for students."

Why it fails: **too vague**, **no quantification**, **no specific user**, **no cause**, **no impact**.

**Good statement:** *College seniors searching for off-campus housing waste 15+ hours per month visiting apartments, calling landlords, and comparing options, because housing platforms (Craigslist, Zillow) mix student rentals with family homes, lack student-specific information (roommate vibe, distance to campus, price for shared units), and require repeated contact with unresponsive landlords. This stress and time waste causes approx. 40% to settle for housing that's overpriced, far from campus, or with incompatible roommates.*

What changed: a specific user (seniors, off-campus), a quantified cost (15+ hours/month), a concrete cause (three named platform failures), current solutions named, and a measurable consequence (≈40% settle).

## Problem Validation

A problem statement is a hypothesis until validated. Validation answers three questions.

### Why validate

- **Confirm that the problem occurs in real situations.**
- **Determine whether people view the problem as important enough to address.**
- So that you **build a product that solves a clearly defined problem.**

The core validation question (an interview prompt; full interview method → [customer-interview](../customer-interview/SKILL.md)):

> **"Tell me about the last time this problem happened. What did you do?"**

It asks about real past behavior, not opinions or hypotheticals, so it surfaces frequency, workarounds, and actual spending, which are the evidence criteria above.

### How to validate

1. **Define the problem.** Write the statement using a framework above.
2. **Define your idea (solution) to solve it.** Keep it separate from the problem.
3. **Go out and speak to potential customers.** Repeat, repeat, repeat.
4. **Ask customers the right questions.** About their experience of the problem, not your idea.
5. **Discover what the problem *really* is.** Expect the validated problem to differ from your draft, as in the laddering and workaround examples.
6. **Then decide: Proceed, Pivot, Punt.**

### Proceed, Pivot, Punt

This three-way decision is the library's standard end point for any evidence-gathering step, and this skill owns it. Later stages reuse it with their own criteria: interview evidence (→ [customer-interview](../customer-interview/SKILL.md)) and market evidence (→ [market-research](../market-research/SKILL.md)). At the problem stage the criteria are:

| Decision | When |
|---|---|
| **Proceed** | Evidence confirms the problem is real, frequent, costly, shared by enough of the right people, and worth paying to solve. Move to customers and value proposition. |
| **Pivot** | The evidence shows a different problem, cause, or user than you assumed (a different laddering branch, a hidden dimension like "access" in the textbook example). Rewrite the statement around what you found and validate again. |
| **Punt** | The problem isn't felt, is rare, is a preference, or nobody would pay. Drop it and return to discovery. Execution cannot rescue it. |

Once the problem is validated, confirming who will actually buy is customer validation (→ [customer-validation](../customer-validation/SKILL.md)).

## Workflow

Use this end to end for a new venture. For an existing business, enter at step 3 with the reported symptom. For an existing statement, enter at step 7.

1. **Discover.** Use the discovery prompts, observation & listening, and workaround spotting to collect candidate problems.
2. **Separate problem from solution.** Rewrite any "we need an app…" as person, situation, pain, consequence.
3. **Name the pain types.** Functional, financial, emotional/social. Write current state vs. desired state and list the gap's components.
4. **Check evidence criteria.** Real (not preference), felt, regular, costly, workarounds exist, shared by enough of the right people, specific. Punt anything that fails badly.
5. **Diagnose the cause.** Separate symptom, cause, and root cause. Ladder with "Why?" and list competing branches. Apply the Jobs-to-Be-Done lens: what job, which current solutions, what gap.
6. **Draft the statement.** Simple framework first. Add a Jobs-to-Be-Done or Empathy Based version if it fits better (Empathy: confirm willingness to pay). Upgrade to Quantified only with numbers you can support.
7. **Run the Problem Statement Test.** Seven questions; fix every "no." Check against the Common Mistakes below.
8. **Validate.** Talk to potential customers repeatedly with "Tell me about the last time…". Test the competing root-cause branches. Replace estimates with real numbers.
9. **Decide: Proceed, Pivot, Punt.** On Pivot, loop back to step 5 or 6 with the new evidence.
10. **Hand off.** Go to opportunity-id and the customer skills (see Related Skills).

### Output format

When delivering a problem statement, provide:

```
PROBLEM STATEMENT (framework used: ____)
[2–3 sentences]

Breakdown
- User: ...
- Problem / pain type(s): ...
- Context: ...
- Root cause: ...            (competing causes still to test: ...)
- Consequence (quantified): ...
- Frequency: ...
- Current solutions / workarounds and their limits: ...

Problem Statement Test
- Ask / Specific user / Frequency / Impact / Cause / Evidence / Pay: pass or gap, one line each

Evidence status
- Validated: ...
- Assumed (needs validation): ...

Next validation step: ...
Recommendation: Proceed / Pivot / Punt, and why
```

## Common Mistakes

| Mistake | Example | Fix |
|---|---|---|
| **Too vague** (not specific) | "Commuting is bad." | State exactly what happens, to whom, and make it measurable. |
| **Wrong user** (everyone) | "People," "everyone," "users" | Narrow to a nameable group (→ [customer-segmentation](../customer-segmentation/SKILL.md)). |
| **Solution disguised as a problem** | "We need an app." | Restate as person, situation, pain, consequence. |
| **Symptoms mistaken for a cause** | "Sales are down." | Ladder with "Why?" to the root cause; confirm with data and interviews. |
| **No evidence or measurement** | Research lacking | Interview, observe, research; use only numbers you can support. |
| **Too little pain/frequency** | A minor issue | Check frequency and cost; small markets need intense, frequent, expensive pain. Otherwise punt. |
| **Can't differentiate** | Can't say what customer and why you | Clarify the user and how current solutions fall short (→ [value-proposition](../value-proposition/SKILL.md)). |

Also watch for:

- **A preference posing as a problem** ("I wish it came in my favorite color").
- **A personal problem only you have** ("the font on my bank's website is bad").
- **Picking the root cause you like** instead of testing competing laddering branches.
- **Empathy without payment:** an emotionally vivid statement about people who would never pay.
- **Invented numbers** in a Quantified statement.
- **Falling in love with the solution** and bending the problem to fit it.

## Worked Examples

### Positive example: Quantified, built from evidence

*Context: a founder noticed her sister, the office manager at a two-dentist practice, staying late most days. The numbers below are illustrative of what a real interview round would produce, not real market data.*

> **62% of the office managers we interviewed at independent dental practices (1–4 dentists) (14 of 22) spend 6+ hours per week verifying patients' insurance eligibility before appointments by phone and across separate insurer web portals, because each insurer uses a different portal and many don't show plan-specific details such as remaining annual maximum or frequency limits. This costs each practice roughly 25 staff hours per month, plus written-off claims averaging $1,800 per month when coverage turns out to be wrong after treatment. Current workarounds (calling insurers, spreadsheets of plan notes, the practice-management software's basic eligibility check) resolve only about half of verifications, because they return active/inactive status but not the plan-specific limits that cause denials.**

Why it works:

- **Specific user:** independent dental practices with 1–4 dentists, and specifically the office manager. You could name the 14 people.
- **Problem, not solution:** no product is mentioned; it describes a pain anyone can be interviewed about.
- **Pain types:** functional (6+ hours/week) and financial ($1,800/month written off).
- **Root cause, not symptom:** "written-off claims" is the symptom; the cause is fragmented portals that hide plan-specific limits.
- **Evidence and frequency:** 14 of 22 interviews; weekly, before every appointment day.
- **Workarounds and limits of current solutions:** phone calls, spreadsheets, and a basic check that returns status but not limits. People already spend time and money: strong evidence of real pain.
- **Willingness to pay:** the cost lands on the practice owner, who pays for software already. The payer is identifiable.
- **Supportable numbers:** every figure traces to the interview round. That is what makes the Quantified framework "legitimately done."
- **Passes all seven test questions.**

### Negative example: what most first drafts look like

> **Gen Z needs a better budgeting app because managing money is hard and boring, and everyone wants to be financially free.**

Why it fails:

- **Solution disguised as a problem:** "needs a better budgeting app" names a product. You can't interview anyone about an app that doesn't exist.
- **Wrong user (everyone):** "Gen Z" and "everyone" are tens of millions of people with different situations. You can't name who has this problem.
- **Too vague:** "hard and boring" isn't a measurable or observable pain. Hard how? Boring when?
- **Symptom, not cause:** no "why." Is it irregular gig income? Forgotten subscriptions? Rent eating most of a paycheck? Each is a different business.
- **No context, frequency, or consequence:** nothing about when it happens, how often, or what it costs (overdraft fees? missed rent? credit damage?).
- **No evidence:** no interviews, no data, no observed workarounds.
- **Preference and aspiration, not obstacle:** "wants to be financially free" is a desire, not a recurring obstacle.
- **No willingness-to-pay signal:** nothing suggests anyone pays to solve it, and existing free apps aren't acknowledged.
- **Fails the test:** Specific user, Frequency, Impact, Cause, Evidence, and Pay all fail.

To fix it: interview young workers about the last time money went wrong, listen for complaints and workarounds, ladder to a root cause (e.g., "Why did you overdraft?"), then rewrite with the Simple framework.

## Related Skills & Next Steps

- **[opportunity-id](../opportunity-id/SKILL.md)** — Always paired with this skill. Go there next to evaluate whether the validated problem's gap is a real opportunity, screen problems worth solving, and separate the opportunity from your idea.
- **[customer-segmentation](../customer-segmentation/SKILL.md)** — Go here to sharpen the "specific user" into segments and pick a beachhead market.
- **[customer-interview](../customer-interview/SKILL.md)** — Go here to plan and run the repeated problem-validation conversations ("Tell me about the last time…").
- **[customer-end-user-profile-and-persona](../customer-end-user-profile-and-persona/SKILL.md)** — Go here to turn the user in your statement into a detailed end user profile and persona.
- **[customer-ecosystem](../customer-ecosystem/SKILL.md)** — Go here when the person with the pain isn't the person who pays, to map stakeholder roles.
- **[customer-validation](../customer-validation/SKILL.md)** — Go here after the problem is validated, to confirm who will actually buy.
- **[market-research](../market-research/SKILL.md)** — Go here for primary/secondary research to support Quantified numbers, market sizing for "enough of the right people," and competitive analysis of current solutions.
- **[value-proposition](../value-proposition/SKILL.md)** — Go here once the problem is validated to map customer jobs/pains/gains and differentiate your solution.
- **[creative-ideation](../creative-ideation/SKILL.md)** — Go here only after the problem is defined, to brainstorm solutions to it.
- **[business-model](../business-model/SKILL.md)** — Go here after the problem and value proposition hold, to design how the solution creates and captures value.
- **[financials](../financials/SKILL.md)** — Go here when the solution's numbers (margins, break-even, cash) become evidence in a Proceed / Pivot / Punt call.
