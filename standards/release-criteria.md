# Release criteria

A release recommendation must be based on executed tests and known risks.

## Minimum criteria for a public website

- Published URL is accessible over HTTPS.
- Critical user-facing navigation and contact actions work.
- No open S1 defects.
- No open S2 defects in critical journeys unless explicitly accepted by the owner.
- Supported mobile and desktop layouts have been checked.
- No broken critical assets or unexpected JavaScript errors.
- Content, contact details, prices, and claims are approved by the site owner.
- Known limitations and untested areas are documented.

## Reporting

The final report must include:
- Build / commit and target URL
- Test date, environment, browser, device, and viewport
- Counts for Pass, Fail, Blocked, and Not Run
- Critical and high defects
- Explicitly untested areas
- Release recommendation: Go / Conditional Go / No-Go

## Important

A checklist prepared, source reviewed, or repository updated is not the same as a successful test execution. Do not claim production readiness until the relevant checks have actually been run.
