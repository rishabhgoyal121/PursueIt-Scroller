# Decision Context

This document tracks major and minor project decisions for `PursueIt-Scroller`.

## 2026-05-11 IST

### D-001: Rebuild README from Placeholder to Recruiter-Ready Technical Summary
- Decision: Replace one-line placeholder README with a complete recruiter-oriented project overview.
- Alternatives considered:
  - Keep README minimal with only project title.
  - Add high-level marketing copy without technical structure.
- Rationale: This project demonstrates frontend depth through D3 and scrollytelling, which needs explicit technical framing.
- Impact: Repository now communicates value, architecture, run steps, and project structure clearly.

### D-002: Keep Claims Strictly Code-Backed and Use TODO for Unverified Hosting Details
- Decision: Include only code-verifiable claims and add TODO markers for uncertain deployed URL/screenshots.
- Alternatives considered:
  - Guess deployment details from historical context.
  - Omit all placeholders.
- Rationale: Maintains accuracy and avoids introducing false claims in public-facing documentation.
- Impact: README quality improved immediately while preserving factual correctness.

### D-003: Convert README References to Clickable Markdown Links
- Decision: Convert localhost run URL and screenshot placeholder paths in README to Markdown links.
- Alternatives considered:
  - Keep references as inline code text.
  - Convert only deployed/public URLs.
- Rationale: Gives reviewers one-click navigation consistency and reduces friction while evaluating the repository.
- Impact: README usability improved without changing project setup or behavior.
