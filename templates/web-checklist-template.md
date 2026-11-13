# Web application test checklist — template

> Copy this file into `projects/<project-name>/checklist.md` and adapt it to the product.

| ID | Area | Scenario / steps | Expected result | Actual result / evidence | Status | Priority |
|---|---|---|---|---|---|---|
| WEB-001 | Availability | Open the production/staging URL | Page loads over HTTPS without server error | — | Not Run | High |
| WEB-002 | Navigation | Follow every primary navigation item | Correct section/page opens; no dead links | — | Not Run | High |
| WEB-003 | Responsive | Check common desktop, tablet, and mobile widths | No horizontal overflow; content remains usable | — | Not Run | High |
| WEB-004 | Images | Inspect all visible images | Images load, have suitable crop, and do not distort layout | — | Not Run | Medium |
| WEB-005 | Forms | Submit valid and invalid data in each form | Validation is clear; valid submission has an expected outcome | — | Not Run | High |
| WEB-006 | Links | Open internal and external links | Destinations are correct; external links behave safely | — | Not Run | Medium |
| WEB-007 | Keyboard | Navigate interactive elements using Tab / Enter / Space | Focus is visible and controls are operable | — | Not Run | Medium |
| WEB-008 | Accessibility | Inspect headings, labels, contrast, and image alternatives | Content has meaningful structure and accessible names | — | Not Run | Medium |
| WEB-009 | Browser console | Load and use key page interactions | No uncaught JavaScript errors | — | Not Run | Medium |
| WEB-010 | Network | Inspect failed requests and asset loading | No unexpected failed critical requests | — | Not Run | Medium |
| WEB-011 | Performance | Check loading and large assets | Main content appears promptly; no obviously oversized assets | — | Not Run | Medium |
| WEB-012 | SEO / metadata | Inspect title, description, canonical/robots where relevant | Metadata is relevant and page can be indexed as intended | — | Not Run | Low |
| WEB-013 | Reduced motion | Enable operating-system reduced-motion preference | Non-essential motion is reduced or disabled | — | Not Run | Low |
| WEB-014 | Content | Review text, prices, contacts, dates, and spelling | No placeholders, contradictions, or unapproved claims | — | Not Run | High |

## Execution record

- Environment / URL:
- Date and time:
- Browser and version:
- OS / device:
- Viewport:
- Build / commit:
- Tester:

## Notes

Record reproducible steps, screenshots, console/network evidence, and the exact environment for every failure.
