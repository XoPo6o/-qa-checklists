# Popopo3 Salon — defect and open-item log

## BUG-SAL-001 — Contact section contains pending business information

- **Status:** Open — awaiting owner input
- **Severity:** S3 — Moderate (content completeness)
- **Priority:** High — blocks a complete public business profile
- **Environment:** Current source on `main`
- **Build / commit:** `d1eb7f541fdfe26610037fe178dcbbdcfad10e84`
- **Preconditions:** Review the public-facing Contacts section
- **Steps to reproduce:**
  1. Open the home page.
  2. Navigate to the Contacts section.
  3. Review booking, address, and schedule fields.
- **Expected result:** Visitors can find confirmed, current ways to contact the salon and understand when/where it operates.
- **Actual result:** Booking is shown as “Скоро появится”; address and schedule are shown as “Уточняется”. No confirmed contact channel is published.
- **Evidence:** `index.html`, section `#contacts`
- **Frequency:** Always
- **Workaround:** None for a visitor who needs to contact or visit the business.
- **Related checklist ID:** SAL-009
- **Resolution needed:** Owner must provide approved phone/messenger/social link, address, and working hours. Do not invent these values.

## Resolved during source review

### FIX-SAL-001 — Service tiles advertised a non-existent action

- **Status:** Resolved in commit `d1eb7f541fdfe26610037fe178dcbbdcfad10e84`
- **Change:** Converted four service tiles from links to informational articles and removed the misleading “Подробнее” call to action.
- **Verification:** Static source inspection confirms four article tiles and no service-card anchors.
