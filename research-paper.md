# Reducing Admin Burden with Practical AI

**Status:** working draft. Section 2 has an initial source-backed draft. Other sections remain outline only.

## 1. Executive summary

_To be drafted after the evidence register contains reviewed sources and the core sections have been developed._

Expected content:

- What admin burden means in this research.
- Why it matters for non-technical organisations.
- Where practical AI and automation can help.
- Where human judgement and review must remain explicit.
- The most useful low-risk starting patterns.

## 2. Problem definition: admin burden as wasted attention and process drag

Admin burden is not just paperwork. In this research, it means the avoidable work created when people, information, systems, decisions, and handoffs do not fit together cleanly.

It shows up as time spent finding, copying, checking, chasing, re-entering, translating, reconciling, and reporting information that should already be usable. It also shows up as process drag: delays, rework, unclear ownership, avoidable support demand, inconsistent records, slow follow-up, and decisions made with poor visibility.

This definition deliberately includes but is not limited to formal regulatory burden. UK businesses reported spending an average of 8.0 days per month on compliance in the 2024 Business Perceptions Survey, with paperwork, record keeping and repeated information provision identified as burdens. That is one visible form of admin burden. The broader operational version also includes the everyday friction hidden inside inboxes, spreadsheets, forms, chat messages, duplicated systems, manual reporting, and undocumented local workarounds. See SRC-013.

For non-technical organisations, admin burden is often intensified by capacity constraints. Small businesses may value digital technology and automation, but adoption is shaped by time, skills, confidence, cost, leadership attention and implementation support. The issue is rarely only whether a useful tool exists. It is whether the organisation has enough clarity and capacity to change the workflow safely. See SRC-004, SRC-005, SRC-011 and SRC-015.

A useful working model is to treat admin burden as four overlapping forms of drag.

### 2.1 Capture drag

Capture drag happens when information enters the organisation inconsistently or incompletely.

Examples:

- enquiries arriving across email, forms, phone, social media, chat and verbal conversations;
- missing fields that need to be chased later;
- free-text notes that cannot easily be reported;
- duplicated data entry into multiple systems;
- customer, client, patient, volunteer or supplier details captured differently by different people.

Capture drag matters because poor intake quality becomes downstream admin work. If the first record is weak, later work becomes checking, interpreting, correcting and chasing.

### 2.2 Handoff drag

Handoff drag happens when work moves between people, teams, systems or stages without clear context, ownership or status.

Examples:

- no shared view of what has happened and what should happen next;
- staff needing to ask for updates manually;
- actions buried in meeting notes or message threads;
- unclear responsibility for follow-up;
- work duplicated because nobody trusts the current record.

The GOV.UK Service Manual highlights the importance of joined-up experiences across channels and notes that poor channel integration can create workarounds and failure demand. Although written for public services, the same pattern applies to small businesses and internal operations: disconnected channels create avoidable work. See SRC-009.

### 2.3 Decision drag

Decision drag happens when people cannot quickly see enough reliable information to decide what to do next.

Examples:

- unclear pipeline or backlog status;
- inconsistent reporting categories;
- weak visibility of overdue work;
- managers manually compiling updates from several sources;
- decisions delayed because information must be reconciled first.

This is where automation and AI are often tempting, but the first intervention may need to be simpler: clarify the decision, data source, owner and review point. The NIST AI RMF and UK Government AI Playbook both support a risk-based approach that starts with context, limitations, accountability and control rather than tool selection. See SRC-001, SRC-002 and SRC-003.

### 2.4 Assurance drag

Assurance drag happens when organisations cannot easily prove that work was done correctly, consistently, safely or lawfully.

Examples:

- no clear record of who approved an output;
- inconsistent source material;
- manual checking of recurring reports;
- unclear data protection handling;
- no review trail for AI-assisted outputs;
- difficulty explaining why a decision or recommendation was made.

For AI-enabled workflows, assurance drag is especially important. The ICO AI and Data Protection Risk Toolkit is designed to help organisations reduce risks to individuals' rights and freedoms caused by AI systems. Secure AI guidance from NCSC also frames AI as something that needs secure design, deployment, operation and maintenance across the lifecycle. For non-technical teams, this points to a practical requirement: AI outputs should be reviewable, accountable and bounded by clear risk rules. See SRC-006 and SRC-007.

### 2.5 Why simplification comes before automation

A consistent theme across the evidence is that organisations should not treat AI as the first answer. The OECD administrative simplification material is explicit that reducing bureaucratic complexity involves simplifying procedures, not just digitising them. GOV.UK service-design guidance makes a similar point from the user side: services should be simple to use, because complexity creates mistakes, support demand and trust damage. See SRC-008 and SRC-010.

The practical implication is blunt:

> Do not automate a broken workflow until you understand why it creates work.

That does not mean automation should wait for perfection. It means the first step should be an admin-burden map, not a tool purchase. Map the trigger, channels, people involved, repeated manual steps, data sensitivity, failure points and review needs. Then decide whether the best intervention is process simplification, a checklist, a structured form, a basic automation, an AI-assisted step, or no change at all.

### 2.6 Working definition for this research

For the rest of this paper, admin burden means:

> The avoidable operational effort created by fragmented information, unclear handoffs, weak process design, repeated manual handling, poor visibility, and insufficient assurance.

This definition matters because it keeps the research focused on useful interventions. Some admin work is necessary. Records, review, compliance, communication and accountability are not automatically waste. The target is not to remove administration. The target is to reduce avoidable drag while preserving the checks, context and human judgement that make organisations safe and trustworthy.

## 3. Where AI and automation help

Candidate intervention areas:

- Intake capture.
- Classification and routing.
- Summarisation.
- Drafting responses.
- Follow-up reminders.
- Document generation.
- Data cleanup support.
- Report preparation.
- Exception detection.
- Knowledge retrieval.

Each area needs evidence review, risk grading, and implementation notes.

## 4. Where AI should not be used unchecked

High-risk areas include:

- Clinical, legal, financial, regulatory, disciplinary, or safety-critical judgement.
- Sensitive personal data without clear controls.
- Decisions affecting access, eligibility, care, pay, employment, or legal status.
- Processes where an error is hard to detect or reverse.
- Workflows where accountability becomes unclear.

## 5. Common small-business automation patterns

Initial patterns to investigate:

- Web form to structured lead register.
- Email enquiry to triage queue.
- Meeting notes to action list.
- Invoice or quote request to draft response.
- Customer feedback to theme summary.
- Spreadsheet cleanup to weekly control report.
- Event or job completion to follow-up sequence.
- Simple KPI snapshot from operational records.

## 6. AI governance for non-technical teams

Governance should be practical enough to use.

Core rules to develop:

- AI can draft; humans approve.
- AI can summarise; humans verify source-critical claims.
- AI can classify low-risk records; humans review exceptions.
- AI can recommend next actions; humans own decisions.
- AI use must be visible where it affects important outputs.
- Sensitive data requires explicit handling rules.

## 7. Implementation model

Suggested model:

1. Map admin burden.
2. Select low-risk workflow.
3. Define desired output.
4. Identify data and privacy constraints.
5. Create human-review step.
6. Pilot with a small sample.
7. Measure time, quality, rework, and confidence.
8. Decide whether to scale, adjust, or stop.

## 8. Metrics and evaluation

Potential measures:

- Time saved.
- Rework reduced.
- Error rate.
- Follow-up speed.
- Cycle time.
- Staff confidence.
- Customer/client response time.
- Number of handoffs.
- Manual copy/paste steps removed.
- Quality of final output.

## 9. Risks and limitations

Risks to cover:

- Hallucination.
- Over-automation.
- Privacy exposure.
- Poor data quality.
- Accountability gaps.
- Staff mistrust.
- Fragile workflows.
- Vendor lock-in.
- Process theatre: automating a bad workflow without fixing it.

## 10. Appendices and templates

Appendices translate the core research into implementation patterns for specific contexts.

Template outputs:

- Admin burden map.
- Automation opportunity scorecard.
- AI governance checklist.
- Human review log.
