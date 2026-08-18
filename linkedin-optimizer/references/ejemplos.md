# Flow examples

Illustrative cases of how the skill should behave. Read these if there is any doubt about expected behavior.

> These cases are written in English as internal documentation. The responses they describe are produced in the user's / profile's language — see the Language Lock rule in `SKILL.md`.

## Case A — Asks for an audit with no material

**User:** "Help me audit my LinkedIn profile"

**Correct response:** ask for the PDF (Profile → "Resources" → "Save to PDF") **or screenshots**, whichever is easier for them. Generate nothing yet.

## Case B — Uploads the input material

**User:** "Optimize my LinkedIn" + PDF

**Correct response (first turn):** short questionnaire in the profile's language:
1. What do you want to improve your LinkedIn *for*? (examples: employment, clients, personal brand… or anything else: networking, scholarship, investors, etc.)
2. Which role/audience are you targeting?
3. Anything to highlight or avoid?

Wait for the answer. **Only then** generate the full report with the template.

## Case C — Partial screenshots

**User:** "Review my LinkedIn" + 2 screenshots (headline and About only)

**Correct response:** questionnaire + coverage notice: "I can only see your headline and About — I can't see experience, skills, Featured, or recommendations. Can you upload screenshots of those, or confirm they're empty?"

## Case D — Non-standard goal

**User answers the questionnaire:** "I want to apply to a master's program abroad"

**Correct behavior:** the ENTIRE report orients around that — headline with an academic/research profile, About aimed at admissions committees, Featured with papers/academic projects, recommendation script aimed at professors/supervisors. Do not fall back on the default "recruiters" mold.

## Case E — Ambiguous data point mid-analysis

**Situation:** the PDF says "increased sales 40%" but it is unclear whether this was an individual or team achievement, and the date of that role is cut off in the screenshot.

**Correct behavior:** stop and ask about those 2 specific points before drafting the Experience section. Do NOT assume, do NOT write "I led a 40% increase" without confirmation.

## Case F — PDF vs. screenshot conflict

**Situation:** the PDF shows one headline and the screenshot shows a different one.

**Correct behavior:** ask which is the current version before continuing. Never pick one at random.

## Case G — Post-report iteration

**User:** "Give me 3 more headline variants"

**Correct behavior:** answer only that part (3 new headlines with their "why it works"), without repeating the full report.

## Case H — Profile with no metrics (very common)

**Situation:** a recent graduate in the thesis stage. Their experience consists of internships and academic projects: no percentages, no business figures.

**Correct behavior:** do NOT invent metrics and do NOT write "optimized processes by 30%". Build social proof from what IS verifiable in the material: project names, stack used, real scope if stated, certifications. And log "absence of impact metrics" as a 🔴 gap in the Diagnosis and as an item in the Action Plan, specifying what they should start measuring.

**Incorrect:** leaving the social-proof section empty "because there's no data". The user expects usable text, not a hole.

## Case I — A single round of questions

**Situation:** the user uploads the PDF. On reading it you detect: (a) their goal is unclear, (b) a 40% achievement with unclear attribution, (c) an inconsistent date between two roles.

**Correct behavior:** one single message with all three together — context questionnaire + the two ambiguities. Then the report.

**Incorrect:** ask about the goal, wait, start drafting, and only then ask about the 40%. That's three turns where one was enough.

## Case J — Bilingual profile

**Situation:** the headline is in English and the About is in Spanish.

**Correct behavior:** ask in the single round which language they want the report and the optimized texts in. Do not assume based on the language of the first field you happened to read.

## Case K — Headline that gets truncated

**Situation:** you draft a 215-character headline where the role only appears at character 90.

**Correct behavior:** rewrite it. The first ~70 characters are all that shows in search, comments, and mobile; if the role isn't there, the headline fails its job even though it respects the 220 limit.

## Case L — Instruction language leaking into the output

**Situation:** the profile is entirely in Spanish, but these instructions are in English, and you begin drafting "# 🚀 LinkedIn Audit and Optimization: …".

**Correct behavior:** stop and restart in Spanish, using the label glossary in `estructura-reporte.md`. The instruction language is an implementation detail and never determines the output language.
