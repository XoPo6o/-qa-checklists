# Popopo3 Salon — project QA

## Project

- Repository: [XoPo6o/popopo3.github.io](https://github.com/XoPo6o/popopo3.github.io)
- Type: static website / GitHub Pages
- Scope: public-facing salon / hair studio website
- Test basis: current source files and agreed product scope
- QA status: test plan prepared; browser execution is not yet recorded

## Current scope

This project is a website-vizitka. Online booking, user accounts, payments, and backend workflows are out of scope unless explicitly added later.

Known page sections in the current design:
- Hero / first screen
- About
- Services
- Brand statement / manifesto
- Gallery
- Masters
- Contacts
- Footer
- Responsive navigation and visual effects

## Important test rule

Do not invent salon details. Names, prices, address, schedule, phone number, reviews, and booking availability must be confirmed by the site owner. Any placeholder or unapproved sample content should be reported.

## Files

- [Checklist](checklist.md) — scenarios and execution statuses
- [Test results](test-results.md) — actual run summary and environment
- [Bugs](bugs.md) — reproducible defects

## Exit criteria

See [shared release criteria](../../standards/release-criteria.md). A source-level review is not equivalent to a browser test. The final report must clearly distinguish verified, failed, blocked, and not-run checks.
