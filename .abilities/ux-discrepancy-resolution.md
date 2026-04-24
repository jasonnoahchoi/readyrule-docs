# UX Discrepancy Resolution Status
**Verified:** 2026-03-06 via agent-browser against localhost:3000

## HIGH PRIORITY

| # | Issue | Status | Notes |
|---|-------|--------|-------|
| 1 | 12-Week Trend Chart | STILL OPEN | Score breakdown exists but no trend chart/graph. Doc should describe score breakdown only. |
| 2 | Mark Absent Button | PARTIALLY RESOLVED | Expected absence tracking exists via attendance log. No dedicated "Mark Absent" button on child roster. |
| 3 | QR Code Settings | RESOLVED | Settings has both "Parent Check-In" and "Staff Check-In" QR sections with copy link and download. |
| 4 | Add Staff Form | RESOLVED | Proper form with First Name, Last Name, Role (6 options), Email, Phone fields. |
| 5 | Signature Step | DOCS UPDATE | Parent flow shows "Sign in with a tap" (step 3). Docs should match current flow. |
| 6 | Parent UI Pattern | DOCS UPDATE | Current UI uses phone/email verification flow. Docs should describe current state. |
| 7 | Production URL | DOCS UPDATE | Use readyrule.com (not app.readyrule.com) in docs. |
| 8 | Ratio Forecast Hidden | RESOLVED | "Ratio Forecast" link now in sidebar navigation. |

## MEDIUM PRIORITY

| # | Issue | Status | Notes |
|---|-------|--------|-------|
| 9 | Child Roster vs Attendance | RESOLVED | Separate sidebar links: "Attendance" and "Child Roster". |
| 10 | Notifications vs Alerts | RESOLVED | Sidebar uses "Alerts" label. Notification area is a separate region. |
| 11 | Chat vs Compliance Assistant | RESOLVED | Compliance Chat is a sidebar link at /app/compliance-chat. |
| 12 | Checklist Location | STILL OPEN | Not in sidebar nav. Accessible via /app/checklist but only via quick action. |
| 13-18 | Button labels | DOCS UPDATE | Update docs to match current button labels in the app. |
| 19 | "it remembers you" | STILL OPEN | Phone entry still required each time on parent sign-in. |

## Action Taken
- Mintlify docs written to match CURRENT app state (not aspirational state)
- STILL OPEN issues are code changes, not doc issues — docs correctly describe current behavior
- All resolved items reflected in the corresponding MDX docs
