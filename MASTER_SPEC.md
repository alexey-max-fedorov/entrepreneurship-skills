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

Make sure to give VERY CLEAR instructions to subagents, and pass on ALL RELEVANT RULES TO THEM (excluding rules that are for orchestration or for other skills, as each subagent makes exactly one skill. subagents should use the opus model). They should ONLY read the files I wrote above (per skill), and should ONLY write to the skill specified [they may use scratchpad if they need to split the PDF’s]