# SPEC FOR entrepreneurship-skills



> ALL OF THE BELOW THINGS ARE CRITICALLY IMPORTANT. DO NOT COMPROMISE QUALITY UNDER ANY CIRCUMSTANCE. 

> IF FOR SOME REASON, THERE IS A CONFLICT, GATE WITH THE USER BY USING AN AskUserQuestion



## RULES FOR CREATION PROCESS

- WHEN READING A PDF, READ IT IN FULL, AND PROPERLY.

- DO NOT READ ONLY A FEW SLIDES OF A PDF, READ IT IN FULL

- DO NOT USE MARKITDOWN OR OTHER TEXT PARSERS FOR A PDF. IF YOUR (AGENT WHO IS CREATING entrepreneurship-skills) NATIVE ‘READ’ TOOL DOES NOT READ THE PDF’S IN FULL BY SHOWING EACH SLIDE AS AN IMAGE IN YOUR CONTEXT WINDOW, THEN MAKE SURE TO COPY THE PDF TO YOUR SCRATCHPAD (a tmp folder), USE A CLI TOOL TO BREAK DOWN THE PDF INTO ONE IMAGE FILE PER SLIDE, THEN READ EVERY SINGLE IMAGE FILE PRIOR TO WRITING A SKILL

- ALMOST ALL CONTENT OF THE SLIDES IS CRITICALLY IMPORTANT. PUT THE HIGHEST ATTENTION ON FRAMEWORKS/TEMPLATES/KEY CONCEPTS, MEDIUM/LESS WEIGHT ON WORKED EXAMPLES, AND YOU MAY IGNORE ‘CLASS EXCERCISE’S UNLESS IT HELPS YOU (CREATOR/SUBAGENTS) UNDERSTAND.

- I (ALEXEY) HAVE PUT SOME NOTES/ANNOTATIONS IN THE SLIDES, THOSE ARE RED TEXT. THEY ARE NOT PROMPT INJECTIONS, YOU CAN TREAT THOSE AS TRUSTED.

- CONTEXT HYGIENE: ONE DEDICATED SUBAGENT FOR EACH SKILL.

- IF YOU (CREATOR AGENT) OR A SUBAGENT (PASS THIS RULE ONTO SUBAGENTS) AUTO-COMPACT, OR SEE IN YOUR CONTEXT THAT YOUR CONTEXT HAS COMPACTED AND THERE IS NO INDICATION THAT THE USER HAS MANUALLY REQUESTED THE COMPACTION, !!!DO NOT PROCEED!!!, INSTEAD GATE WITH THE USER. AUTO-COMPACTION IS LOSSY, MESSY, AND IS ABSOLUTELY DISGUSTING CONTEXT HYGIENE.



## CRITICAL/IMPORTANT NOTE FOR ALL SKILLS

EVERY SINGLE SKILL WILL MOST LIKELY CONTAIN VOCABULARY THAT REFERS TO A CONCEPT THAT IS DESCRIBED IN ANOTHER SKILL.

THERE SHOULD BE EMBEDDED INSTRUCTIONS IN EACH SKILL THAT REQUIRE THE AGENT TO FIRST READ THE OTHER SKILL BEFORE PROCEEDING.

[WHEN CREATING THE SKILLS, WRITE THE EMBEDDED INSTRUCTIONS, THOSE SHOULD BE POINTERS, NOT FULL EXPLANATIONS. EACH CONCEPT GETS ONE SINGLE SOURCE OF TRUTH SKILL]

[EVERY SINGLE SKILL SHOULD HAVE POINTERS, DO NOT CHEAP OUT ON THOSE]



### FOR EXAMPLE:

- USER: ASKS AGENT TO HELP WITH ADJUSTING THE BIZ MODEL OF HIS BIZ FOR IDEAS FOR MORE REVENUE STREAMS

- AGENT: READS THE business-model SKILL (THIS SKILL CONTAINED THE WORDS “value proposition”, “customer”, “problem”)

- AGENT: READS THE 3 SKILLS FOR VALUE PROP, CUSTOMER, PROBLEM, (IF THOSE SKILLS CONTAINED MORE REFERENCES TO CONCEPTS THAT THE AGENT HASN’T READ THE SKILLS FOR YET, THE AGENT WOULD PROCEED TO READ THE RELEVANT SKILLS FOR THOSE. THERE IS NO LIMIT TO THIS: IF THAT MEANS THE AGENT ENDS UP READING EVERY SINGLE SKILL IN entrepreneurship-skills, THAT’S FINE, AND PROBABLY A GOOD THING. THE OBVIOUS EXCEPTION HERE IS THAT THERE’S NO NEED TO READ A SKILL TWICE, IF THE SKILL IS ALREADY IN CONTEXT)

- AGENT: ONLY AFTER ALL RELEVANT SKILLS HAVE BEEN READ, THE AGENT PROCEEDS WITH THE USER’S REQUEST OF ADJUSTING THE BIZ MODEL FOR IDEAS FOR MORE REVENUE STREAMS



## RULES FOR USING EXAMPLES IN THE CREATED SKILLS

- YES, I DO WANT EXAMPLES TO BE INCLUDED IN THE CREATED SKILLS. EACH SKILL SHOULD INCLUDE TWO WORKED EXAMPLES: ONE THAT IS PERFECT (POSITIVE EXAMPLE), AND ONE THAT IS AWFUL (NEGATIVE EXAMPLE)

- USE THE SAME EXAMPLES FROM THE SLIDE DECKS OR NOT?? => DEPENDS. IF THE SLIDES HAVE A GOOD, RELEVANT, APPLICABLE EXAMPLE, THEN YES.

- IF THE SLIDES HAVE AN EITHER FULLY FICTIONAL EXAMPLE (LIKE “NEWCO THE BABY”) OR A HILARIOUSLY BAD EXAMPLE (“STICH FIX FOR DOGS”), COME UP WITH YOUR EXAMPLE INSTEAD, AND MAKE SURE IT’S GOOD. EXCEPTION: THE HILARIOUSLY BAD EXAMPLES CAN BE RE-USED FROM THE SLIDES IF NEEDED, BUT OVERALL COME UP WITH YOUR OWN.



## NOTE ON APPLICATION OF THE CREATED SKILLS

- DO NOT WRITE IN RESTRICTIONS ON THE APPLICATION OF SKILLS IN THE SKILLS YOU CREATE. REASON: USERS MAY HAVE MANY DIFFERENT USES FOR A SKILL, WHETHER THAT’S STARTING A BUSINESS, AUDITING/OPTIMIZING THEIR OWN OR SOMEONE ELSES’S BIZ, REVISING SOMETHING, CREATING SOMETHING, ADJUSTING SOMETHING, PIVOTING, REALLY ANYTHING.



## WHAT SHOULD BE IN THE SKILLS

- BELOW, IN THE “SKILL:” SECTIONS I AM WRITING A FEW OF THE IMPORTANT PARTS TO COVER IN EACH SKILL (EACH BULLET POINT SHOULD BE ITS OWN HEADING/SECTION), BUT THOSE ARE NOT AT ALL EXHAUSTIVE, AND YOU SHOULD INCLUDE RELEVANT CONTEXT FROM OTHER PARTS OF THE PDF’S (THIS MAY INCLUDE OTHER NEW SECTIONS/HEADINGS!!!!). 

- THE SKILLS SHOULD BE CLEANY STRUCTURED. ALL SKILL CONTENT SHOULD BE IN THE SKILL.MD FILE. HOWEVER, SUPPLEMENTAL THINGS (SUCH AS AN INTERACTIVE HTML CHART FOR THE BUSINESS MODEL CANVAS TEMPLATE) CAN BE INCLUDED IN THE SKILL FOLDER OUTSIDE OF THE SKILL.MD FILE, AS LONG AS IT IS REFERENCED WITH A POINTER IN THE SKILL.MD FILE. SUPPLEMENTAL CONTENT OUTSIDE THE SKILL.MD FILE MUST **ONLY** BE DUPLICATE INFORMATION OF THE SKILL.MD FILE (DO NOT HAVE ACTUAL **INFORMATION** IN OUTSIDE FILES), THOSE SUPPLEMENTAL FILES SHOULD JUST BE STUFF LIKE CHARTS, VISUALS, INTERACTIVE HTML’S, SCRIPTS (IF APPLICABLE), ETC.

- BE VERY DETAILED IN THE SKILLS. DO NOT YAP OR USE FILLER WORDS, BUT DO NOT COMPROMISE THE QUALITY OF THE INFORMATION FROM THE SLIDES. “NARROWLY SCOPED” DOES NOT MEAN SHORT/CHEAP. AND “LARGE” DOES MEAN THE SKILL.MD SHOULD BE VERY LONG, BUT IT SHOULD BE LONG ONLY BY BEING COMPREHENSIVE WITH ACTUAL INFORMATION. DO NOT FABRICATE OR MAKE UP INFORMATION.



# SKILL DESCRIPTIONS



## SKILL: problem-statement

- Large, comprehensive skill about the PROBLEM. This is the MAIN STARTERPOINT for anyone trying to start a business. This is the crown jewel of this skillset. This is the main blocker in which, if someone doesn’t have a solid real problem statement to work with, they are much more likely to fail. 

FROM /Users/alexey/Documents/ENTR Skills/Problem/Problem_This_is_the_crown_jewel_of_this_whole_thing

- Very detailed here, make sure to include the frameworks too

FROM /Users/alexey/Documents/ENTR Skills/Problem/Problem_Validation_Mini_Slides

- I’m p sure these are a repetition of info covered elsewhere, so the subagent making this one should still read it before writing the skill





## SKILL: opportunity-id

- Moderately large skill, about the OPPORTUNITY which is p much finding problems that are worth solving for profit. problem-statement is a prerequisite, this is the supplement, if one skill is loaded, the other should be loaded too

FROM /Users/alexey/Documents/ENTR Skills/Problem/Opportunities_Finding_Problems_WORTH_SOLVING

- Very detailed here, make sure to include the frameworks too

FROM /Users/alexey/Documents/ENTR Skills/Problem/Opportunities_Screening





## SKILL: business-model

- Large, comprehensive skill on business model

FROM /Users/alexey/Documents/ENTR Skills/Business Model/Business_Model_Intro_Slides

- Summary from Slide 11 (“Business Model” “Describes the…” “Functions as…” “Simply put: “)

- Template/Framework (text version) Slide 12

- List of business models Slides 15-17, these can be mix-and-match’d, like one biz should have multiple revenue models

FROM /Users/alexey/Documents/ENTR Skills/Business Model/Business_Model_Simple_Assesment

- The assessments for the business model

FROM /Users/alexey/Documents/ENTR Skills/Business Model/Business_Model_Canvas_Slides

- Template/framework (canvas version) which is the best + all info needed for that

The Business_Model_Canvas_Template.docx should not be copied into the skill folder, instead make a new one using HTML

FROM /Users/alexey/Documents/ENTR Skills/Mindset/Mindset_Slides

- ONLY two parts from this: A section on risk management (calculated vs reckless), and a short section on the “old playbook” vs “new playbook”





## SKILL: customer-segmentation

- Moderately large skill, this does also serve as a main entrypoint for figuring out your customer, the pdfs do talk about next steps, in the skill those should be pointers

FROM /Users/alexey/Documents/ENTR Skills/Customer/Customer_Segmentation_Intro

FROM /Users/alexey/Documents/ENTR Skills/Customer/Segmentation_Start_at_Beachhead





## SKILL: customer-interview

- Narrowly scoped skill to customer interviews

FROM /Users/alexey/Documents/ENTR Skills/Customer/Customer_Interview_Rules_and_Next_Steps

- Thats pretty much it, this skill should be centered on customer interviews, many use cases, either briefing/training an entrepreneur on customer interviews, writing scripts/starting questions for entrepreneurs who wanna do interviews, or maybe even an AI agentically conversationally doing a customer interview. The skill should be mainly abt customer interviews + the rest of it should be pointers





## SKILL: customer-ecosystem

- Narrowly scoped skill to customer ecosystem

FROM /Users/alexey/Documents/ENTR Skills/Customer/Customer_Ecosystem_Intro





## SKILL: customer-validation

- Narrowly scoped skill to customer validation

FROM /Users/alexey/Documents/ENTR Skills/Customer/Customer_Validation_Slides





## SKILL: customer-end-user-profile-and-persona

- Narrowly scoped skill to end user profile and persona

FROM /Users/alexey/Documents/ENTR Skills/Customer/End_User_Profile

FROM /Users/alexey/Documents/ENTR Skills/Customer/Persona





## SKILL: market-research

- Narrowly scoped skill (still very detailed of course)

FROM /Users/alexey/Documents/ENTR Skills/Customer/Market_Research_Slides





## SKILL: creative-ideation

- Narrowly scoped skill, mainly for brainstorming/creativity

FROM /Users/alexey/Documents/ENTR Skills/Creative Ideation/Creative_Ideation_Slides

- The skill should of course include a reminder at the top that it is not a replacement for a problem statement (see the red text on slide 1)





## SKILL: value-proposition

- Large, comprehensive skill about value prop

FROM /Users/alexey/Documents/ENTR Skills/Value Proposition/Value_Proposition_Slides

- Focus on the structured concepts/principles/lists/templates/info, don’t spam the skill with hella examples, ofc include some examples, just not an OD amount







# GO

## THE ONE RULE: A SUBAGENT'S CONTEXT HOLDS ONLY TWO THINGS

1. **ITS SLIDES** — the rendered slide images of its assigned decks (the entrepreneurship information).
2. **ITS BRIEF** — minimal execution info: which skill, which slide files, how the skill must look (format, pointers, examples), and where to write.

**NOTHING ELSE ENTERS A SUBAGENT'S CONTEXT.** No repo files (AGENTS.md, README, CONTRIBUTING, validate-skills.sh, scripts/, tests/, alpha/beta stubs, other skills). No validators, no evals, no tooling discovery, no web. A subagent makes exactly three kinds of tool call: **Read a slide → Write the skill → report**. Any other tool call wastes Alexey's usage limits and is a failure of the orchestrator's brief.

## OUT OF SCOPE FOR THIS RUN (SUBAGENTS AND ORCHESTRATOR)

- Skill evals / `evals.json`
- `validate-skills.sh`, `check-versions.mjs`, tests, packaging scripts
- `VERSIONS.md`, plugin manifests, README sync, version bumps
- alpha/beta stub cleanup

All of that gets handled separately later. **There is no line limit on SKILL.md.** Ignore the 500-line guideline in AGENTS.md completely.

## ORCHESTRATOR STEPS

1. **Do not explore the repo.** Everything you need is in this spec. Don't read repo tooling or scripts.
2. **Pre-render every assigned deck before dispatching**, one PNG per slide, into your scratchpad at `<scratchpad>/slides/<DeckName>/slide-NN.png`. Check that the PNG count matches the slide count in the table below. Subagents never touch the PDFs or any tooling. This Mac has no poppler or mutool, so use this Swift PDFKit renderer (`swiftc -O render.swift -o render`, then `./render "<pdf>" "<outdir>" <widthPx>`). Render at 1600px wide, except Mindset_Slides at 1100px (only two parts of it are used).

   ```swift
   import Foundation; import PDFKit; import AppKit
   let a = CommandLine.arguments
   guard a.count == 4, let doc = PDFDocument(url: URL(fileURLWithPath: a[1])) else { exit(1) }
   let out = URL(fileURLWithPath: a[2]); let tw = CGFloat(Double(a[3]) ?? 1600)
   try? FileManager.default.createDirectory(at: out, withIntermediateDirectories: true)
   for i in 0..<doc.pageCount {
       guard let p = doc.page(at: i) else { continue }
       let b = p.bounds(for: .mediaBox); let s = tw / b.width
       let w = Int(b.width * s), h = Int(b.height * s)
       guard let c = CGContext(data: nil, width: w, height: h, bitsPerComponent: 8, bytesPerRow: 0,
           space: CGColorSpace(name: CGColorSpace.sRGB)!, bitmapInfo: CGImageAlphaInfo.premultipliedLast.rawValue) else { continue }
       c.setFillColor(CGColor(red: 1, green: 1, blue: 1, alpha: 1)); c.fill(CGRect(x: 0, y: 0, width: w, height: h))
       c.scaleBy(x: s, y: s); c.translateBy(x: -b.origin.x, y: -b.origin.y); p.draw(with: .mediaBox, to: c)
       let d = NSBitmapImageRep(cgImage: c.makeImage()!).representation(using: .png, properties: [:])!
       try! d.write(to: out.appendingPathComponent(String(format: "slide-%02d.png", i + 1)))
   }
   print("\(a[1]): \(doc.pageCount) pages")
   ```

3. **Extract the BMC .docx text yourself** with `textutil -convert txt -stdout "/Users/alexey/Documents/ENTR Skills/Business Model/Business_Model_Canvas_Template.docx"`, then paste it into the business-model brief as a layout reference. The subagent never opens the .docx.
4. **Dispatch one subagent per skill (11 total, model: opus)** with the brief template below. Fill it in and send nothing more. Paste the skill's section from SKILL DESCRIPTIONS verbatim.
5. **After all reports arrive, reconcile pointers yourself** by making small direct edits to the Required Reading tables and inline pointers. Only message a subagent back if substantive content has to move between skills. If any subagent reports compaction, gate with Alexey.

## DECKS PER SKILL (slide counts verified)

| Skill | Decks (slides) |
|---|---|
| problem-statement | Problem_This_is_the_crown_jewel_of_this_whole_thing (36), Problem_Validation_Mini_Slides (2) |
| opportunity-id | Opportunities_Finding_Problems_WORTH_SOLVING (34), Opportunities_Screening (36) |
| business-model | Business_Model_Intro_Slides (19), Business_Model_Simple_Assesment (2), Business_Model_Canvas_Slides (37), Mindset_Slides (32, 1100px) + docx text pasted into brief |
| customer-segmentation | Customer_Segmentation_Intro (16), Segmentation_Start_at_Beachhead (17) |
| customer-interview | Customer_Interview_Rules_and_Next_Steps (15) |
| customer-ecosystem | Customer_Ecosystem_Intro (14) |
| customer-validation | Customer_Validation_Slides (15) |
| customer-end-user-profile-and-persona | End_User_Profile (14), Persona (8) |
| market-research | Market_Research_Slides (25) |
| creative-ideation | Creative_Ideation_Slides (21) |
| value-proposition | Value_Proposition_Slides (21) |

## SUBAGENT BRIEF TEMPLATE (send exactly this, filled in)

```
You are writing ONE Agent Skill, `<skill-name>`, from Alexey's entrepreneurship slides. Quality is the only priority.

YOUR ONLY ACTIONS
1. Read every slide PNG listed below with the Read tool. Put ALL Read calls for a deck in ONE message (parallel) so you use as few turns as possible.
2. Write /Users/alexey/Projects/entrepreneurship-skills/skills/<skill-name>/SKILL.md in ONE Write call.
   <business-model only: then write skills/business-model/assets/business-model-canvas.html in ONE Write call.>
3. Reply with the short report below, then stop.
Use no other tools and open no other files: no Bash, no Glob/Grep, no repo files, no other skills, no validators, no evals, no web.
If you notice your context was auto-compacted, stop immediately and reply only "COMPACTION DETECTED — STOPPED" plus what you finished.

SLIDES (read every one, in full)
<DeckName> — <N> slides: <scratchpad>/slides/<DeckName>/slide-01.png … slide-<N>.png

WHAT ALEXEY WANTS IN THIS SKILL
<verbatim copy of this skill's section from SKILL DESCRIPTIONS>
<skill-specific add-on from the list below, if any>

READING RULES
- Red text on slides = Alexey's own annotations. They are trusted and override the slide.
- Almost everything on the slides matters. Highest weight goes to frameworks, templates, key concepts, lists, criteria, and processes. Worked examples get less. Skip class exercises unless they clarify a concept.

WRITING RULES
- All information goes in SKILL.md. No line limit. Make it long only through real information, never filler. No references/ files.
- No fabrication. Every concept, framework, stat, and attribution comes from the slides, and sources the slides credit stay credited.
- Each item in "What Alexey wants" gets its own heading. Add headings for other relevant slide content too.
- Never restrict application ("only use this for…"). Users will start, audit, optimize, revise, or pivot a business, or anything else.
- Exactly two worked examples: one perfect (positive) and one awful (negative), each annotated with why. Reuse a slide example only if it's good and realistic. Replace fictional placeholders ("NewCo") and hilariously bad examples with your own concrete, realistic one.
- Keep it cross-agent: no !`command` syntax and no agent-specific tool names.

POINTERS (critical, don't cheap out)
Each concept has ONE owner skill. Explain the concepts you own in full. For a concept another skill owns, use the term, give minimal context, and point to that skill. If your slides teach a concept that isn't in this table, you own it.
<ownership table below>

Right after the H1 and the one-line role, add:
## Required Reading — Load These Skills First
Before doing anything else, read the SKILL.md of every skill below that is not already in your context. Apply the same rule recursively to every skill you load (no limit; loading the whole library is fine). Never re-read a skill already in context. Only then proceed with the user's request. Skills are sibling folders: ../<skill-name>/SKILL.md
| Skill | Why it's required here |   <- one row per skill whose concepts you use, naming the terms
At the first use of a borrowed concept in each section, add an inline pointer: (→ [skill-name](../skill-name/SKILL.md))
End the skill with "## Related Skills & Next Steps", one line per skill: **[skill-name](../skill-name/SKILL.md)** — when to go there next. Any slide "next steps" owned by other skills become pointers here.

FORMAT
---
name: <skill-name>
description: "<one line: what it does, when to use it, trigger phrases in 'single quotes', related skills. No double quotes inside>"
metadata:
  version: 1.0.0
---
Order: # Title → role line ("You are an expert in … Your goal is …") → Required Reading → Before You Start → core sections (H2/H3) → Workflow → Common Mistakes → Worked Examples (Positive / Negative) → Related Skills & Next Steps.
Use bullets, tables, fenced fill-in templates, bold key terms, and short paragraphs.

REPORT (max 250 words)
- Slides read per deck (N/N)
- Red annotations found and how you applied them
- Concepts you own
- Concepts on your slides that belong to another skill, with what your slides say about each (1–2 lines)
```

## OWNERSHIP TABLE (paste into every brief)

| Owner skill | Concepts |
|---|---|
| problem-statement | LIBRARY ENTRY POINT. The problem, the problem statement, pain as the problem, problem validation |
| opportunity-id | Opportunity vs. idea, opportunity recognition, sources of opportunity, problems worth solving, opportunity screening/evaluation |
| business-model | Business model, business/revenue model types, business model assessment, Business Model Canvas + all 9 blocks, calculated vs. reckless risk, old vs. new playbook |
| customer-segmentation | CUSTOMER ENTRY POINT. Who the customer is, market segmentation, segments, beachhead market |
| customer-interview | Customer interviews |
| customer-ecosystem | Customer ecosystem, stakeholder roles |
| customer-validation | Customer validation |
| customer-end-user-profile-and-persona | End user profile, persona |
| market-research | Market research, primary/secondary research, market sizing (TAM/SAM/SOM), competitive analysis |
| creative-ideation | Creativity, brainstorming, ideation techniques |
| value-proposition | Value proposition, VP frameworks/templates, differentiation, customer jobs/pains/gains |

## SKILL-SPECIFIC ADD-ONS (append to that skill's brief only)

- **problem-statement / opportunity-id:** these two are a pair. Each lists the other in Required Reading as "must always be loaded together". opportunity-id lists problem-statement first, as its prerequisite.
- **business-model:** also write `assets/business-model-canvas.html`, an interactive BMC template. It must be one self-contained file with no network requests (no CDNs, no web fonts). Use the standard canvas layout. Each block is editable and shows guiding questions copied from SKILL.md, with no info that isn't in SKILL.md. It autosaves to localStorage (wrapped in try/catch), exports Markdown and JSON, and prints cleanly. Link it from SKILL.md, and put a Markdown version of the canvas in SKILL.md too. Mindset deck: include ONLY the risk (calculated vs. reckless) section and the short old vs. new playbook section.
- **customer-segmentation:** include a routing section that sends each next-step customer question to its owner skill, as pointers.
- **creative-ideation:** at the very top, above Required Reading, add a reminder that ideation is NOT a replacement for a problem statement (red text, slide 1), with a pointer to problem-statement.