# Tulsa Club Legendary Playbook
## Meeting Analysis System v1.0

Purpose:
Create a repeatable leadership intelligence process for every Tulsa Club meeting.

This system converts meeting artifacts into four leadership reports:

1. Meeting After Action Report
2. Club Intelligence Report
3. Officer Action List
4. Membership Growth Forecast

---

# Required Inputs

Minimum artifact bundle:

- Meeting agenda
- Guest sign-in sheet
- Timer report
- Grammarian / Ah-counter sheet
- Evaluation ballots

Optional:

- Officer notes
- Member attendance sheet
- Speech titles and Pathways objectives
- Award results

---

# Processing Workflow

Step 1 — Attendance Extraction
- count members
- count guests
- identify guest names
- evaluate completeness of contact information

Step 2 — Speaking Participation
- identify prepared speakers
- identify table topics participants
- identify evaluators

Step 3 — Timing Compliance
- evaluate speech timing
- evaluate table topics timing
- detect agenda drift

Step 4 — Feedback Aggregation
Group all ballot feedback by speaker:
- strengths
- suggestions
- recurring themes

Step 5 — Vote Tally
Extract and tally:
- Best Speaker
- Best Table Topics Speaker
- Best Evaluator

Step 6 — Club Health Analysis
Assess:

- participation rate
- guest conversion signals
- speaker pipeline strength
- leadership workload distribution

Step 7 — Action Assignment
Create officer action items.

---

# Club Health Scoring Model

| Dimension | Score |
|---|---|
Attendance strength | 0–1
Guest flow | 0–1
Participation spread | 0–2
Prepared speech quality | 0–1
Evaluation culture | 0–1
Agenda discipline | 0–1
Speaker pipeline health | 0–1
Leadership load balance | 0–1
Follow-up readiness | 0–1

Score Interpretation:

9–10 = growth meeting  
7–8 = healthy meeting  
5–6 = stable but vulnerable  
0–4 = intervention needed

---

# Archive Naming Standard

TM_Meeting_AfterAction_YYYYMMDD_v1.0.md  
TM_Meeting_Intelligence_Report_YYYYMMDD_v1.0.md  
TM_Officer_Action_List_YYYYMMDD_v1.0.md  
TM_Membership_Growth_Forecast_YYYYMMDD_v1.0.md  
TM_Meeting_Artifacts_YYYYMMDD.pdf