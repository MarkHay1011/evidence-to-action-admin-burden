# 6. AI governance for non-technical teams

AI governance for non-technical teams should be simple enough to use and serious enough to matter. It should not require a committee, a 90-page policy, or a priesthood of acronyms before anyone can improve a workflow. It should give teams clear rules for what AI can do, what humans must review, what must be logged, and what should trigger escalation.

The governance model in this paper is based on four ideas from the reviewed evidence: risk-based use, meaningful human control, data protection, and secure operation. See SRC-001, SRC-003, SRC-006, SRC-007 and SRC-012.

## 6.1 The governance goal

The goal is not to stop people using AI. The goal is to stop casual, invisible, unreviewed AI use from becoming part of important work.

A useful governance rule should answer five questions:

1. What is AI being used for?
2. What data is involved?
3. Who checks the output?
4. What happens if the output is wrong?
5. Who owns the workflow?

If the team cannot answer those five questions, the workflow is not ready for AI automation. It may still be ready for mapping, simplification or a manual template.

## 6.2 A simple use-tier model

Non-technical teams can use a four-tier model.

| Tier | Use type | Examples | Governance requirement |
|---|---|---|---|
| Tier 1 | Personal productivity | rewriting notes, planning, brainstorming with non-sensitive information | User judgement; no sensitive data |
| Tier 2 | Internal assistive drafting | draft emails, meeting summaries, action extraction, internal summaries | Human review before use |
| Tier 3 | Operational workflow support | classification, routing suggestions, exception lists, KPI summaries | Named owner, review log, data check, pilot controls |
| Tier 4 | High-impact or sensitive use | access decisions, regulated work, clinical/legal/financial judgement, sensitive personal data | Specialist review; do not proceed casually |

Most small organisations should start with Tier 2 or low-risk Tier 3. Tier 4 should not be piloted without qualified review.

## 6.3 Core operating rules

Use these rules as the default governance baseline.

1. **AI can draft; humans approve.** Customer-facing, staff-facing or stakeholder-facing outputs should be reviewed before use.
2. **AI can summarise; humans verify important claims.** Source-critical summaries should link to original material where possible.
3. **AI can classify; humans review exceptions.** Classification should be correctable, especially where it affects priority, routing or reporting.
4. **AI can recommend; humans decide.** Recommendations should be treated as decision support, not decision authority.
5. **AI can flag; humans act.** Exception lists should prompt review, not trigger high-impact action automatically.
6. **AI use should be visible where it matters.** If AI materially shapes an important output, the team should know.
7. **Sensitive data needs explicit handling rules.** Do not rely on vibes, hope, or the sacred incantation of "it is probably fine".

## 6.4 Minimum workflow record

Every AI-supported operational workflow should have a short record. This does not need to be heavy. A one-page note is enough for low-risk use.

Minimum fields:

- workflow name;
- workflow owner;
- AI tool or automation used;
- purpose;
- data used;
- data sensitivity;
- output produced;
- human review point;
- known risks;
- stop condition;
- review date.

This creates lightweight assurance. It also prevents the common failure where a useful experiment becomes a hidden dependency nobody remembers how to maintain.

## 6.5 Review thresholds

Not every output needs the same review. The review level should follow the risk.

| Situation | Review level |
|---|---|
| Personal, non-sensitive brainstorming | User checks before relying on it |
| Internal low-risk draft | Human review before sharing |
| Customer-facing draft | Human review before sending |
| Summary of source material | Check against source or sample source |
| Categorisation or routing | Review exceptions and sample normal cases |
| KPI or dashboard commentary | Check source data, definitions and assumptions |
| Sensitive data involved | Data protection and security review first |
| High-stakes outcome | Qualified human decision; AI assistive only |

The key is to avoid fake review. A rubber-stamp review is just automation risk wearing a lanyard.

## 6.6 Logging rules

Logs should be proportional. Small teams do not need enterprise bureaucracy for every draft. They do need review evidence for operational workflows that affect customers, staff, money, access, reporting, compliance or reputation.

Log when AI is used to support:

- customer-facing outputs;
- operational decisions;
- reporting or KPI commentary;
- source-backed summaries;
- classification or routing;
- exception lists;
- sensitive or confidential workflows;
- any pilot that may become a repeat process.

A useful log should record:

- date;
- workflow;
- AI-assisted task type;
- reviewer;
- source material checked;
- decision: accepted, edited, rejected, or needs further review;
- issues found;
- action taken.

The `human-review-log.md` template exists for this purpose.

## 6.7 Escalation triggers

Escalate before proceeding if any of the following apply:

- the workflow involves sensitive personal data;
- the output affects access, rights, money, care, employment, safety or legal position;
- the team cannot explain how the AI output will be checked;
- the source data is unreliable;
- the automation sends messages or takes action externally;
- the workflow is regulated or contractual;
- people affected by the output would reasonably expect explanation or challenge rights;
- the tool terms, retention, training use, or data location are unclear.

Escalation does not always mean stop. It means the workflow needs a more qualified review before it becomes operational.

## 6.8 The non-technical governance checklist

Before a pilot starts, the team should be able to say yes to these questions.

| Question | Yes/No |
|---|---|
| Is the workflow mapped? |  |
| Is there a named owner? |  |
| Is the AI task specific? |  |
| Is the output defined? |  |
| Is the data sensitivity understood? |  |
| Is the human review point explicit? |  |
| Can the output be corrected? |  |
| Can the pilot be stopped? |  |
| Is success measurable? |  |
| Are high-risk decisions excluded? |  |

If several answers are no, do not pilot the AI step yet. Fix the workflow first.

## 6.9 Governance roles for small teams

A small team does not need a full governance board. It does need named responsibilities.

| Role | Responsibility |
|---|---|
| Workflow owner | Owns the process and decides whether the pilot is useful |
| Reviewer | Checks AI outputs before use |
| Data owner | Confirms what data can be used and where it can go |
| Tool owner | Understands the tool settings, terms and access |
| Escalation contact | Knows when specialist advice is needed |

In a small business, one person may hold several roles. That is fine. What matters is that the responsibility is explicit.

## 6.10 Default governance posture

For non-technical organisations, the default posture should be:

> Start low-risk, keep AI assistive, make review visible, log what matters, and escalate before high-impact use.

That posture is deliberately boring. Boring governance is underrated. It is the seatbelt of useful automation: annoying only until the crash starts.
