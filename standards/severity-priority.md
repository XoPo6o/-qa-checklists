# Defect severity and priority

Severity describes the impact of a defect. Priority describes how urgently it should be fixed. They are related but not interchangeable.

## Severity

| Level | Meaning | Example |
|---|---|---|
| S1 — Critical | Core product unavailable, data/security compromise, or a critical user journey impossible | Published site is unavailable for all visitors |
| S2 — Major | Important functionality is broken with no reasonable workaround | Mobile navigation is unusable on supported phones |
| S3 — Moderate | Partial functionality or visible issue with a workaround | Gallery image is broken while the rest of the page works |
| S4 — Minor | Cosmetic or low-impact issue | Slight spacing inconsistency |

## Priority

| Level | Meaning |
|---|---|
| Critical | Fix immediately; blocks release |
| High | Fix before release unless explicitly accepted |
| Medium | Fix in the planned cycle |
| Low | Fix when practical |

## Guidance

- A typo in a phone number can be high priority because it prevents contact.
- A cosmetic issue can be low priority even if it is visually noticeable.
- Always explain the user/business impact; do not assign severity based only on how easy a defect is to reproduce.
