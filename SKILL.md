# Grant Writing Assistant

**Category:** Business / Nonprofit / Fundraising  
**Version:** 1.0.0  
**Author:** max_0x1  
**Price:** $29 one-time  

## Overview

Four prompts that take you from "we need funding" to a submission-ready grant application. Covers opportunity research and fit scoring, executive summary and needs statement, project narrative and work plan, and evaluation framework with budget justification.

Designed for nonprofits, research institutions, small businesses (SBIR/STTR), community organizations, and grant writers who bill clients $5,000-$15,000 per proposal.

---

## Prompts

### Prompt 1: Grant Opportunity Finder & Fit Scoring

**Use when:** You need to identify the right grants to pursue and quickly qualify each opportunity before investing writing time.

**Input variables:**
- `ORGANIZATION_NAME`: Your organization's legal name
- `MISSION`: 1-2 sentence mission statement
- `PROGRAM_DESCRIPTION`: What you do / what you want to fund
- `BUDGET_RANGE`: Estimated project budget
- `LOCATION`: City, state (for geographic-specific grants)
- `ORG_TYPE`: Nonprofit 501(c)(3) / Small business / Research institution / Government agency / Other
- `TARGET_POPULATION`: Who you serve
- `SECTOR`: Education / Health / Environment / Arts / Economic development / Housing / STEM / Other

**The prompt:**
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

---

### Prompt 2: Executive Summary & Needs Statement

**Use when:** You have a specific grant identified and need to write the opening sections — the parts reviewers read first and weight most heavily.

**Input variables:**
- `FUNDER_NAME`: Name of the foundation or agency
- `GRANT_NAME`: Specific grant program name
- `AWARD_AMOUNT`: Amount you're requesting
- `ORGANIZATION_NAME`: Your organization
- `FOUNDED_YEAR`: Year founded
- `ANNUAL_BUDGET`: Organization's annual operating budget
- `PROGRAM_NAME`: Name of the program/project you're funding
- `PROBLEM_STATEMENT`: The problem this addresses (2-3 sentences)
- `TARGET_POPULATION_DETAIL`: Who specifically (numbers, demographics, geography)
- `EVIDENCE_OF_NEED`: 2-3 data points proving the problem exists (statistics, studies, local data)
- `YOUR_APPROACH`: What your program does to address the problem
- `PAST_RESULTS`: Any outcomes you've already achieved (numbers preferred)

**The prompt:**
```
You are a professional grant writer with a 73% win rate on competitive foundation grants. Write the executive summary and needs statement for this grant application.

Funder: [FUNDER_NAME]
Grant: [GRANT_NAME]
Amount requested: [AWARD_AMOUNT]
Organization: [ORGANIZATION_NAME], founded [FOUNDED_YEAR], annual budget [ANNUAL_BUDGET]
Project: [PROGRAM_NAME]
Problem: [PROBLEM_STATEMENT]
Who we serve: [TARGET_POPULATION_DETAIL]
Evidence of need: [EVIDENCE_OF_NEED]
Our approach: [YOUR_APPROACH]
Past results: [PAST_RESULTS]

Write:

**EXECUTIVE SUMMARY (250-300 words)**
Structure: Problem (2 sentences, lead with the human cost not statistics) → Who we are + track record (2 sentences) → What this grant funds (2 sentences, specific and tangible) → Expected outcomes (2-3 bullet points with numbers) → Closing ask (1 sentence, confident not pleading).

Rules: No jargon. No passive voice. First sentence must not start with the organization name. Must be copy-pasteable into a 1-page letter of inquiry.

**NEEDS STATEMENT (400-500 words)**
Structure:
1. The problem at scale (national/state context with 2-3 statistics from reputable sources)
2. The problem locally (zoom in to your specific geography with local data)
3. Who suffers most and why (name the population, humanize with a 2-sentence composite story)
4. Why existing solutions fail (gaps in current services — be specific, not vague)
5. Why now (urgency factor — policy change, demographic shift, funding gap, crisis)
6. Bridge sentence to your solution

Rules: Every statistic must have a source citation in parentheses. Use active voice. Short paragraphs (3-4 sentences max). End with a sentence that makes the reader feel the urgency of funding THIS now.
```

---

### Prompt 3: Project Narrative & Work Plan

**Use when:** You need to describe exactly what you'll do, how, and by when — the operational core of the application.

**Input variables:**
- `PROGRAM_NAME`: Name of the project
- `GRANT_PERIOD`: Length of the grant (1 year / 18 months / 2 years)
- `START_DATE`: Anticipated start date
- `PROGRAM_GOALS`: 2-3 broad goals
- `OBJECTIVES`: 3-5 specific, measurable objectives (SMART format preferred)
- `ACTIVITIES`: List of key activities (bullet points fine)
- `STAFF_ROLES`: Who will implement (titles and FTE commitment)
- `PARTNERS`: Any partner organizations and their roles
- `POPULATION_SERVED`: Number of people/organizations you'll serve
- `PRIOR_SUCCESS`: Evidence this approach works (your data or research base)
- `CHALLENGES`: 1-2 anticipated challenges and how you'll address them

**The prompt:**
```
You are a program officer turned grant consultant who has reviewed 500+ applications for major foundations. Write a project narrative and work plan that would pass your own review process.

Project: [PROGRAM_NAME]
Grant period: [GRANT_PERIOD] starting [START_DATE]
Goals: [PROGRAM_GOALS]
Objectives: [OBJECTIVES]
Activities: [ACTIVITIES]
Staff: [STAFF_ROLES]
Partners: [PARTNERS]
People served: [POPULATION_SERVED]
Evidence base: [PRIOR_SUCCESS]
Anticipated challenges: [CHALLENGES]

Write:

**PROJECT NARRATIVE (600-800 words)**
Section 1 — Program Description: What you do, how, and for whom. Avoid jargon. Use active verbs. Describe a typical participant journey from intake to outcome in 2-3 sentences.
Section 2 — Evidence Base: Why this approach works. Cite 2-3 peer-reviewed studies or successful models if applicable. Connect the evidence to your specific design choices.
Section 3 — Organizational Capacity: Why you are the right organization to do this. Staff expertise, facility, partnerships, community trust. Concrete, not generic.
Section 4 — Sustainability: How this continues after the grant ends. Revenue diversification, earned income, government contracts, other foundation pipeline. Be specific — "we will seek other funding" fails every review.
Section 5 — Risk Mitigation: Name 2 real risks and your mitigation plan. Reviewers respect applicants who have thought through failure modes.

**WORK PLAN TABLE**
Create a month-by-month implementation timeline in table format:
| Month | Milestone | Lead | Status Indicator |
Include: planning/hiring (months 1-2), launch (month 3), mid-point evaluation (month 6 or 9), completion and reporting (final month).
Minimum 8 milestones. Each milestone must be observable and measurable.

**LOGIC MODEL (condensed)**
| Inputs | Activities | Outputs | Short-term Outcomes | Long-term Outcomes |
One row per program component. Maximum 3 components.
```

---

### Prompt 4: Evaluation Framework & Budget Justification

**Use when:** You need to complete the back half of the application — proving you'll measure results and spend money wisely.

**Input variables:**
- `PROGRAM_NAME`: Project name
- `OBJECTIVES`: Your SMART objectives from Prompt 3
- `DATA_SOURCES`: What data you already collect or have access to
- `EVALUATOR_TYPE`: Internal staff / External evaluator / University partner / No evaluator yet
- `TOTAL_BUDGET`: Total project budget
- `GRANT_AMOUNT`: Amount requested from this funder
- `BUDGET_CATEGORIES`: List your major cost categories (personnel, supplies, travel, indirect, etc.)
- `PERSONNEL_DETAIL`: Roles, % FTE, annual salaries (for personnel justification)
- `INDIRECT_RATE`: Your negotiated indirect cost rate (if any)
- `MATCHING_FUNDS`: Any matching funds, in-kind, or other leveraged resources

**The prompt:**
```
You are a foundation program officer and former nonprofit CFO. Write an evaluation framework and budget narrative that will pass financial scrutiny and demonstrate accountability.

Project: [PROGRAM_NAME]
Objectives: [OBJECTIVES]
Data sources available: [DATA_SOURCES]
Evaluator: [EVALUATOR_TYPE]
Total project budget: [TOTAL_BUDGET]
Grant request: [GRANT_AMOUNT]
Budget categories: [BUDGET_CATEGORIES]
Personnel: [PERSONNEL_DETAIL]
Indirect rate: [INDIRECT_RATE]
Matching/leverage: [MATCHING_FUNDS]

Write:

**EVALUATION PLAN (400-500 words)**
Section 1 — Evaluation Questions: 3-4 core questions this evaluation will answer (aligned to your objectives).
Section 2 — Indicators & Data Collection:
| Objective | Indicator | Data Source | Frequency | Baseline | Target |
Minimum one indicator per objective. Indicators must be quantifiable.
Section 3 — Data Analysis: How you'll analyze each data type. Minimum: pre/post, comparison group (even informal), disaggregation by subgroup.
Section 4 — Learning & Adaptation: How you'll use findings. Quarterly review meeting, board reporting, program adjustments. Shows you evaluate to learn, not just comply.
Section 5 — Reporting to Funder: Frequency, format, who's responsible.

**BUDGET NARRATIVE**
For each budget line:
- State the item, quantity, unit cost, and total
- Write 1-2 sentences justifying why this expense is necessary for the project
- Note the calculation method (e.g., "1.0 FTE Program Director × $58,000 annual salary × 12 months")

Required sections:
1. Personnel (most scrutinized — justify every FTE percentage)
2. Fringe benefits (state your rate and what it covers)
3. Consultants/contractors (why outsourced, how rate was determined)
4. Supplies and materials (itemized, not "miscellaneous")
5. Travel (mileage rate, purpose, calculation)
6. Indirect costs (rate, base, what it covers — or explain if no rate)
7. Matching funds section: list each source, amount, and whether cash or in-kind

**BUDGET SUMMARY TABLE**
| Category | This Grant | Other Sources | Total |
Totals must reconcile exactly. Show the leverage ratio (other:grant).

**COST-EFFECTIVENESS STATEMENT (2-3 sentences)**
Calculate and state: cost per participant, cost per outcome achieved. Compare to alternatives ("$X per participant vs. $Y for comparable programs nationally").
```
