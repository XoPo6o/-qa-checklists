# API test checklist — template

| ID | Area | Scenario | Expected result | Actual result / evidence | Status | Priority |
|---|---|---|---|---|---|---|
| API-001 | Positive | Send a valid request with required fields | Expected success status and response schema | — | Not Run | High |
| API-002 | Required fields | Omit each required field | Clear validation error; no unintended side effect | — | Not Run | High |
| API-003 | Data types | Send incorrect types and formats | Request is rejected consistently | — | Not Run | High |
| API-004 | Boundaries | Test min/max values and just-outside values | Boundary rules are enforced | — | Not Run | High |
| API-005 | Authentication | Send request without credentials / with invalid credentials | Access is denied with correct status | — | Not Run | High |
| API-006 | Authorization | Access another user's restricted resource | No unauthorized data is disclosed or changed | — | Not Run | Critical |
| API-007 | Not found | Request a nonexistent resource | Correct not-found response | — | Not Run | Medium |
| API-008 | Duplicates | Repeat a create/payment/action request | Duplicate handling follows requirements; no double processing | — | Not Run | Critical |
| API-009 | State transitions | Attempt valid and invalid status transitions | Only permitted transitions are accepted | — | Not Run | High |
| API-010 | Idempotency | Repeat requests with the same idempotency key, if supported | Repeated request does not create duplicate effects | — | Not Run | High |
| API-011 | Errors | Trigger server-side and dependency errors | Safe, consistent error response; no sensitive details leaked | — | Not Run | High |
| API-012 | Performance | Send representative requests under expected load | Response time meets agreed service target | — | Not Run | Medium |
| API-013 | Data integrity | Compare API result with persisted data where authorized | Stored data matches the accepted request and response | — | Not Run | High |
| API-014 | Security | Check injection, mass assignment, and sensitive fields | Inputs are safely handled; restricted fields are not exposed | — | Not Run | Critical |

## Execution record

- Base URL / environment:
- API version:
- Authentication type (never store secrets here):
- Collection / test run:
- Date and tester:
