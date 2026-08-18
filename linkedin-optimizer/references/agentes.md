# Multi-Agent System — Evaluation criteria

> These criteria are internal reasoning instructions written in English. **The report they produce follows the Language Lock rule in `SKILL.md`** — it is written in the language of the user's profile, not in English.

The 3 agents are an internal reasoning framework. The user sees a single consolidated report, never each agent's "deliberations".

## 🕵️‍♂️ Senior Headhunter Agent

Evaluates the profile from the perspective of a recruiter or prospective client seeing it for the first time for ~8 seconds.

**Criteria:**
- Are the role and seniority level immediately clear from the headline and experience?
- Do the listed skills match what the experience demonstrates? (a skill mentioned but never evidenced = gap)
- Are there red flags that would scare off a company: unexplained employment gaps, vague descriptions ("assisted with tasks"), absence of metrics, inflated titles with no backing?
- Would the profile pass ATS filters and LinkedIn Recruiter searches? (exact technical keywords for the industry)
- **Profile hygiene** (fast to fix, high impact): professional photo, banner carrying a value proposition, custom URL (`/in/firstname-lastname` instead of the auto-generated one with digits), Open to Work / Services enabled if relevant to the goal, languages, certifications and education complete, skills with endorsements.
- Drafts the **Optimized Experience** section: outcomes with real metrics from the material, methodologies used, and technical keywords. Maximum 2,000 characters per description.

## ✍️ B2B Copywriter Agent

Writes the optimized versions of the Headline, About, and supporting texts.

**Criteria:**
- **Persuasion:** every text opens with the reader's problem/need (hook), not the author's ego.
- **Concrete metrics:** only those present in the user's material or confirmed by the user — never invented. If there are no metrics, apply the qualitative-evidence rule from Step 2 of `SKILL.md`.
- **SEO/keywords:** the exact terms the user's ICP searches for, in their language and industry.
- **Readability:** short sentences, line breaks, lists; the About must read comfortably on mobile.
- **Headline:** maximum 220 characters. **The first ~70 characters must convey role + value on their own** — that is all that shows in search, comments, and mobile. Characters 71–220 carry indexing keywords and (if it exists) social proof.
- **About:** maximum 2,600 characters; recommended length 200–350 words. **The first line (≤300 characters) is all that shows before "see more"** and must work as a standalone hook. Structure: (1) hook to the reader's pain/need, (2) solution/value delivered, (3) social proof (metrics if they exist; qualitative evidence if not), (4) specialties as a list, (5) clear CTA aligned with the declared goal.
- No minimum-length requirement ever justifies padding with generalities. A 180-word About full of specifics beats a 250-word one with filler.

## 🧠 Authority Strategist Agent

Defines the user's positioning in their industry.

**Criteria:**
- How does this profile differentiate itself from the hundreds of similar profiles in its industry and country?
- What should go in **Featured** to build credibility? Proposals with a numbered emoji and an explicit conversion purpose (e.g. "1️⃣ Power BI dashboard → proves real work").
- How should **social proof** be structured? Which recommendations to request, from whom, and validating which critical skill.
- Positioning is subordinate to the goal declared in the questionnaire: authority built to win clients is built differently than authority for a scholarship or a career change.

## Consolidation (Lead Optimizer)

- The three analyses are integrated into the single report in `estructura-reporte.md`.
- If two agents "disagree" (e.g. the Copywriter wants a creative headline and the Headhunter a keyword-loaded one), the criterion better aligned with the **user's declared goal** wins.

## Scoring rubric (0–100)

Score each dimension 0 to 3 using the descriptors below, multiply by its factor, and sum. **Do not estimate the score by feel**: if you cannot justify the band with a sentence from the material, drop one level.

| Dimension | Factor | 0 · Absent | 1 · Weak | 2 · Adequate | 3 · Excellent |
|---|---|---|---|---|---|
| **Role clarity** | ×8.33 | Cannot tell what they do | Generic or auto-generated title ("Student at X") | Role and seniority clear in the headline | Role + specialty + value readable in <8 seconds |
| **Evidence / metrics** | ×8.33 | No descriptions, or duties only ("assisted with…") | Tasks described, zero outcomes | Some concrete outcome or named project | Quantified, attributable results across most roles |
| **SEO / keywords** | ×6.67 | No industry keywords | Scattered keywords, headline only | Keywords in headline + About + skills | Exact ICP vocabulary distributed across all sections |
| **Social proof** | ×5 | No recommendations or endorsements | Loose endorsements, no recommendations | 1–2 recommendations or verifiable achievements | Recommendations validating the skills critical to the goal |
| **CTA / conversion** | ×5 | No call to action and no way to make contact | Contact present but buried | Explicit CTA at the end of the About | CTA + Featured items driving a concrete action |

Maximum: 3×(8.33+8.33+6.67+5+5) = **100**. Round to the nearest integer.

**Consistency check:** if you listed 2 or more critical gaps (🔴) in the Diagnosis, the score cannot exceed 65. If the score exceeds 80, the Diagnosis must describe a profile with no critical gaps.
