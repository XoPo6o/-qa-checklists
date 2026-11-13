# QA Checklists

A reusable QA knowledge base for testing web, mobile, and API projects.

The repository is organized by project. Shared templates and quality standards live separately so they can be reused without copying the same rules into every project.

## Repository structure

```
.
├── README.md
├── templates/
│   ├── web-checklist-template.md
│   ├── mobile-checklist-template.md
│   └── api-checklist-template.md
├── projects/
│   └── popopo3-salon/
│       ├── README.md
│       ├── checklist.md
│       ├── test-results.md
│       └── bugs.md
└── standards/
    ├── severity-priority.md
    ├── test-statuses.md
    └── release-criteria.md
```

## How to use

1. Create a folder under `projects/` for each new project.
2. Copy the relevant template from `templates/`.
3. Add project-specific scenarios and acceptance criteria.
4. Record execution evidence and defects. Never mark a test as passed unless it was actually executed.
5. Use the shared standards for status, severity, priority, and release decisions.

## Status discipline

- **Not Run** — not executed yet.
- **Pass** — executed and actual result matches expected result.
- **Fail** — executed and actual result differs from expected result.
- **Blocked** — execution is prevented by an external dependency or environment issue.
- **Not Applicable** — scenario does not apply to this project, with a reason recorded.

A checklist is a test plan, not proof of successful testing. Execution results must be supported by evidence where practical.
