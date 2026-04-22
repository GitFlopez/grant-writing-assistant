# Prompt 1: Grant Opportunity Finder & Fit Scoring

## Purpose
Identify the right grants to pursue and score each opportunity before investing writing time.

## Variables to Fill In
- `ORGANIZATION_NAME` — legal name of your organization
- `MISSION` — 1-2 sentence mission statement
- `PROGRAM_DESCRIPTION` — what you do / what you want to fund
- `BUDGET_RANGE` — estimated project budget (e.g., $50,000–$75,000)
- `LOCATION` — city and state
- `ORG_TYPE` — Nonprofit 501(c)(3) / Small business / Research institution / Government agency
- `TARGET_POPULATION` — who you serve (demographics, geography, situation)
- `SECTOR` — Education / Health / Environment / Arts / Economic development / Housing / STEM / Other

## Prompt

```
You are an expert grant researcher with 15+ years of experience identifying funding sources for nonprofits, research institutions, and small businesses.

Organization: [ORGANIZATION_NAME]
Mission: [MISSION]
Program: [PROGRAM_DESCRIPTION]
Budget needed: [BUDGET_RANGE]
Location: [LOCATION]
Org type: [ORG_TYPE]
Serves: [TARGET_POPULATION]
Sector: [SECTOR]

Generate a grant opportunity report with:

**SECTION 1: TOP 10 GRANT OPPORTUNITIES**
For each opportunity include:
- Grant name and funder
- Typical award range (min-max)
- Eligibility requirements
- Application deadline pattern (rolling / annual cycle / specific month)
- Fit score (1-10) with 2-sentence rationale
- Where to find it (foundation website, Grants.gov, foundation database)
- One thing that makes this org a strong candidate

Sort by fit score descending.

**SECTION 2: QUICK WINS (Apply within 30 days)**
List 3-5 grants with upcoming or rolling deadlines that match this org. Include specific next action for each.

**SECTION 3: LONG-TERM PIPELINE (6-12 months)**
List 3-5 major funders worth building a relationship with before applying. Include one cultivation action for each (board connection, site visit, letter of inquiry timing).

**SECTION 4: RED FLAGS TO AVOID**
List 3-5 grant types or funders this org should NOT pursue (poor fit, high competition with low success rate, requirements that don't match). Explain why.

**SECTION 5: COMPETITIVE LANDSCAPE**
Estimate: how many orgs like this one are competing for these funds in this geography? What makes the strongest applicants win?
```

## Expected Output
- Ranked list of 10 grant opportunities with fit scores
- 3-5 quick-win opportunities with next actions
- 3-5 long-term cultivation targets
- 3-5 red flags with explanations
- Competitive landscape summary

## Tips
- Run this prompt before any application writing — it prevents wasted time on wrong-fit grants
- Use the fit score to prioritize: pursue 8-10 first, skip anything under 6
- "Quick wins" section is most actionable — start there if deadline pressure exists
