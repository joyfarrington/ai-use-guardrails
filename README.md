AI Use Guardrails (Healthcare Ops)

Purpose
Use AI to support operational work (drafting, summarizing, organizing) while protecting privacy, accuracy, and accountability.

Scope (What this applies to)
- Prior authorization drafting support
- De-identified documentation summaries
- Patient-facing message polishing (with human review)
- Internal SOPs, checklists, and workflow drafts

What I DO use AI for
- Turning messy notes into clean drafts (after removing identifiers)
- Creating templates (logs, checklists, scripts, SOP outlines)
- Summarizing non-sensitive info for faster decision-making
- Rewording for clarity (plain language)

What I DO NOT use AI for
- Entering or sharing PHI/PII
- Making clinical decisions
- Sending patient communications without review
- Automatically approving denials/authorizations or coverage decisions

Minimum Guardrails (every time)
1) De-identify first
Remove names, DOB, MRN, phone, address, email, account numbers, exact dates tied to a person, and any unique identifiers.

2) State the purpose
One sentence: “I’m using AI to [draft/summarize/format] for [task].”

3) Human verification required
I verify facts against the source system before anything is submitted or sent.

4) Log the use
I log the tool, purpose, input type (de-identified), and what I checked.

5) Escalate uncertainty
If output could affect eligibility, coverage, billing, or patient communication, I slow down and get a second set of eyes.

Quick De-Identification Checklist
- Names removed
- Dates generalized (ex: “late 2025” vs exact date)
- Locations generalized (city/state removed if unnecessary)
- IDs removed (MRN, claim number, account number)
- Rare details removed that could identify someone

How I measure “safe enough”
- If I wouldn’t paste it into a public doc, it doesn’t go into AI
- If I can’t explain it in an audit, it’s not ready

Disclaimer
This repo uses fictional examples only. No patient data is included. This is a personal workflow standard, not legal advice.
