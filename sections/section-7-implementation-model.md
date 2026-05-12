# 7. Implementation model

The implementation model turns the research into a practical sequence that a non-technical organisation can follow without starting with a platform purchase, a consultancy slide deck, or a heroic spreadsheet that becomes load-bearing by Wednesday.

The model is deliberately narrow. It is designed for low-risk, assistive AI and automation pilots that reduce admin drag while keeping human judgement, data protection, and operational control visible.

## 7.1 Start with admin-burden mapping

Do not begin with a tool. Begin with the repeated workflow that creates friction.

A useful admin-burden map should identify:

- what triggers the workflow;
- who is involved;
- where information enters;
- which channels are used;
- where information is copied, checked, chased, or re-entered;
- where ownership changes;
- what decisions are made;
- where errors or delays occur;
- what data is involved;
- what must be reviewed by a human.

The purpose is to understand the work before improving it. This follows the paper's core principle: simplify before automating. See SRC-008, SRC-009 and SRC-010.

## 7.2 Select one low-risk workflow

A first pilot should be small enough to understand and safe enough to stop.

Good first workflows usually have:

- frequent repetition;
- clear inputs and outputs;
- low or manageable data sensitivity;
- visible errors;
- a named owner;
- a human review point;
- measurable benefit;
- limited downside if the pilot fails.

Poor first workflows include:

- high-stakes decisions;
- sensitive data without controls;
- unclear ownership;
- unstable processes;
- outputs that are hard to verify;
- autonomous external actions;
- workflows that affect rights, care, access, money, employment, safety or legal position.

A good first pilot is usually boring. Boring is useful. Boring is where you find repeat work, measurable friction, and fewer ways to accidentally create an operational horror film.

## 7.3 Define the desired output

The team should define the output before choosing the AI or automation step.

Examples:

| Workflow | Desired output |
|---|---|
| Incoming enquiry | Structured record with category, contact details, missing fields and next action |
| Meeting notes | Confirmed action list with owners and due dates |
| Weekly spreadsheet review | Short control report with key measures and exceptions |
| Customer feedback | Monthly theme summary with sampled source checks |
| Quote request | Draft response requiring human approval |

The output definition should answer:

1. What should be produced?
2. Who will use it?
3. What decision or action does it support?
4. How will the output be checked?
5. What would make the output unsafe or unusable?

If the team cannot define the output, it is too early to automate.

## 7.4 Identify data and privacy constraints

Before introducing AI or automation, the team should identify what data the workflow uses.

At minimum, record whether the workflow includes:

- personal data;
- sensitive personal data;
- customer or client records;
- staff records;
- financial information;
- health, clinical, veterinary or care information;
- confidential business information;
- contractual or regulated information.

If the workflow involves sensitive or confidential data, the team should check tool terms, access, retention, training use, data location and relevant legal or contractual obligations before piloting. See SRC-006 and SRC-007.

The practical rule is simple:

> If the team would not paste the data into a public document, it should not paste it into an AI tool without understanding the controls.

## 7.5 Create the human-review step

The review step should be designed before the pilot starts.

Define:

- who reviews the output;
- what they check;
- what source material they can inspect;
- how they correct the output;
- how they reject the output;
- whether the review must be logged;
- when the workflow should be escalated.

This keeps AI assistive rather than silently authoritative. It also prevents the common failure where a pilot looks efficient only because review has been removed rather than improved.

Useful review modes include:

| Output type | Review mode |
|---|---|
| Draft message | human reads and edits before sending |
| Summary | human checks against source or sample source |
| Classification | human reviews exceptions and samples normal cases |
| Exception list | human decides action |
| KPI commentary | human checks data, definitions and assumptions |
| Evidence extraction | human verifies source and interpretation |

## 7.6 Pilot with a small sample

The first pilot should use a limited sample, not the whole workflow.

Define:

- sample size;
- date range;
- users involved;
- excluded cases;
- success measures;
- stop criteria;
- review date.

Examples:

- triage 25 enquiries from one channel;
- summarise four weekly meetings;
- produce three weekly spreadsheet control reports;
- draft but do not send ten customer follow-up messages;
- classify one month's feedback into themes for review.

The pilot should be reversible. If the team cannot stop it without breaking operations, the first version is too large.

## 7.7 Measure usefulness

The pilot should be judged by operational usefulness, not by whether AI was involved.

Measure before and after where possible.

Useful measures include:

- time spent;
- number of manual steps;
- rework;
- missing information;
- response time;
- overdue items;
- error rate;
- review corrections;
- staff confidence;
- customer or stakeholder experience;
- number of exceptions caught;
- quality of final output.

A time saving is not enough if quality, trust, safety or accountability gets worse.

## 7.8 Decide: scale, adjust, stop

At the end of the pilot, make an explicit decision.

| Decision | Meaning |
|---|---|
| Scale | The pilot produced useful benefit and risk is controlled |
| Adjust | The pattern is promising but workflow, data, prompt, review or tooling needs improvement |
| Stop | Benefit is weak, risk is too high, or the workflow is not ready |
| Simplify first | The process needs redesign before automation |
| Escalate | Specialist review is needed before continuing |

Do not let pilots become permanent by accident. Accidental permanence is how organisations end up depending on a half-tested automation named `final_FINAL_v3_really_this_time`.

## 7.9 Minimum pilot record

Every pilot should leave a short record.

| Field | Notes |
|---|---|
| Workflow | What process was tested? |
| Owner | Who owns the workflow? |
| AI/automation role | What did the tool do? |
| Data used | What information was processed? |
| Review point | Who checked the output? |
| Sample | What was included and excluded? |
| Measures | What changed? |
| Issues found | What failed or needed correction? |
| Decision | Scale, adjust, stop, simplify first, or escalate |
| Next review date | When will this be checked again? |

This record is not bureaucracy. It is the minimum memory required to stop useful experiments becoming mysterious dependencies.

## 7.10 Implementation sequence

The recommended sequence is:

1. Map the admin burden.
2. Select one low-risk workflow.
3. Define the desired output.
4. Identify data and privacy constraints.
5. Design the human-review step.
6. Pilot with a small sample.
7. Measure usefulness and risk.
8. Decide whether to scale, adjust, stop, simplify first or escalate.
9. Document the workflow if it becomes recurring.
10. Review it periodically.

The model is intentionally conservative. It is easier to expand a safe pilot than to unwind an unsafe automation after it has started making decisions in the dark.
