# Test statuses

| Status | Use when | Evidence / note |
|---|---|---|
| Not Run | Test has not been executed | No result is implied |
| Pass | Executed and actual result matches expected result | Record environment; attach evidence when useful |
| Fail | Executed and actual result differs from expected result | Create a defect with reproducible steps |
| Blocked | Could not execute because of an external dependency, access, or environment issue | Explain the blocker and what is needed |
| Not Applicable | Scenario does not apply to this product or scope | Give a short reason |

## Rules

1. Never mark a scenario Pass based only on reading source code.
2. Do not convert an untested scenario to Pass because the page appears correct at a glance.
3. A failed environment setup is Blocked, not Fail, unless the environment itself is what is being tested.
4. Keep test status separate from defect status.
5. Update summary counts whenever checklist statuses change.
