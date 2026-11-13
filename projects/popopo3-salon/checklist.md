# Popopo3 Salon — website test checklist

**Status legend:** Not Run / Pass / Fail / Blocked / Not Applicable  
**Important:** All scenarios below start as **Not Run**. Change a status only after executing the scenario and recording the actual result.

| ID | Area | Preconditions | Scenario / steps | Expected result | Actual result / evidence | Status | Priority |
|---|---|---|---|---|---|---|
| SAL-001 | Availability | — | Open the published GitHub Pages URL over HTTPS | Site loads successfully; no browser error | — | Not Run | Critical |
| SAL-002 | First screen | — | Inspect hero on desktop and mobile | Main message, image, and primary action are visible and readable | — | Not Run | High |
| SAL-003 | Navigation | — | Click each desktop navigation item | Correct page section is reached | — | Not Run | High |
| SAL-004 | Mobile menu | — | Open, use, and close the mobile navigation | Menu opens/closes reliably; links work; page scroll behaves correctly | — | Not Run | High |
| SAL-005 | About section | — | Navigate to About section | Section appears in the correct position; text is readable | — | Not Run | Medium |
| SAL-006 | Services | — | Review every service item | Service names and descriptions are accurate; no invented prices or claims | — | Not Run | High |
| SAL-007 | Gallery | — | Inspect every gallery image | Images load, crop correctly, and do not stretch or overlap | — | Not Run | Medium |
| SAL-008 | Masters | — | Review master profiles and photos | Only approved names, roles, and portraits are shown; layout is consistent | — | Not Run | High |
| SAL-009 | Contacts | Current HTML on main | Inspect address, phone, schedule, and contact actions | Visitors can find confirmed contact details and business hours | Booking/address/schedule are placeholders; no confirmed contact channel is published (BUG-SAL-001) | Fail | High |
| SAL-010 | Footer | — | Follow footer navigation and social links | Links are valid and lead to intended destinations | — | Not Run | Medium |
| SAL-011 | Images / assets | — | Reload with cache disabled and inspect all assets | No broken image, font, CSS, or JavaScript resources | — | Not Run | High |
| SAL-012 | Responsive | — | Check 360px, 390px, 768px, 1024px, and 1440px widths | No horizontal scrolling or clipped content; layout adapts | — | Not Run | High |
| SAL-013 | Typography | — | Inspect headings, body text, and buttons | Fonts load; hierarchy and line lengths remain readable | — | Not Run | Medium |
| SAL-014 | Interactions | — | Test every button and clickable element | Each control has a meaningful, working action; no empty links | — | Not Run | High |
| SAL-015 | Keyboard | — | Navigate the page using Tab, Shift+Tab, Enter, and Space | Focus is visible; interactive elements are reachable and usable | — | Not Run | Medium |
| SAL-016 | Accessibility | — | Inspect heading order, image alt text, contrast, and accessible names | Meaningful structure and accessible control names are present | — | Not Run | Medium |
| SAL-017 | Motion | — | Check reveal effects and decorative sparkles; enable reduced motion | Motion does not block content or cause discomfort; reduced-motion preference is respected | — | Not Run | Low |
| SAL-018 | Console | — | Load page and exercise navigation/interactions | No uncaught JavaScript errors or critical warnings | — | Not Run | Medium |
| SAL-019 | Network | — | Inspect requests in browser DevTools | No unexpected failed requests; assets use valid paths and casing | — | Not Run | Medium |
| SAL-020 | Cross-browser | — | Check current Chrome, Firefox, Safari, and Edge where available | Core layout and interactions work consistently | — | Not Run | Medium |
| SAL-021 | SEO | — | Inspect title, description, favicon, and indexing directives | Metadata is relevant and consistent with the salon brand | — | Not Run | Low |
| SAL-022 | Content quality | — | Proofread all visible text and inspect placeholders | No typos, broken text, placeholder content, or unsupported claims | — | Not Run | High |
| SAL-023 | Performance | — | Inspect load behavior and image sizes | Main content loads promptly; no avoidable oversized assets | — | Not Run | Medium |
| SAL-024 | Direct navigation | — | Refresh page and open the published URL in a new tab | Static site remains available; no routing/404 issue | — | Not Run | High |

## Source-level checks completed

These checks were performed against the committed HTML and GitHub repository file tree. They do not replace browser execution.

| ID | Area | Preconditions | Scenario / steps | Expected result | Actual result / evidence | Status | Priority |
|---|---|---|---|---|---|---|---|
| SRC-001 | Asset references | Current `main` branch | Compare all image paths referenced by `index.html` with repository paths | Every referenced image exists with matching path and letter case | 11 of 11 referenced image paths matched repository files | Pass | High |
| SRC-002 | Internal anchors | Current `main` branch | Compare in-page hash links with element IDs | Every non-empty internal target exists | All referenced section targets exist | Pass | High |
| SRC-003 | Service card actions | Current `main` branch | Inspect service card markup after fix | Informational cards do not advertise a dead click action | Converted four cards to non-link articles and removed the misleading “Подробнее” CTA | Pass | Medium |

## Run details

- Published URL: https://xopo6o.github.io/popopo3.github.io/
- Source repository: https://github.com/XoPo6o/popopo3.github.io
- Commit under test: record exact SHA before execution
- Date/time:
- Tester:
- Browser/version:
- OS/device:
- Viewport:

## Execution notes

For each Fail or Blocked result, add a matching entry to [bugs.md](bugs.md). Include reproducible steps and evidence. Do not use Pass based only on source inspection.
