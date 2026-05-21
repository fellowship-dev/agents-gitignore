# Quality Score — fellowship-dev/agents-gitignore

Last updated: 2026-05-21

## Domains

| Domain | Grade | Last audit | Notes |
|--------|-------|------------|-------|
| gitignore-template | C | 2026-05-21 | S3 ⚠️ (55d since last commit — static resource, expected drift); S6 ❌ (hookshot not configured) |

## Signal Matrix

| Domain | S1 Doc | S2 FlowChad | S3 Stale | S4 Issues | S5 Tests | S6 Hookshot |
|--------|--------|-------------|----------|-----------|----------|-------------|
| gitignore-template | N/A | N/A | ⚠️ (55d) | ✅ (0) | N/A | ❌ |

## Signal Applicability

| Signal | Applicable? | Reason |
|--------|------------|--------|
| S1 Doc Coverage | No | No application code — single-file community resource; README is the documentation |
| S2 FlowChad | No | No frontend framework — static gitignore template repo |
| S3 Staleness | Yes | Last commit 2026-03-27 (55 days) — expected for static resource, yellow |
| S4 Open Issues | Yes | 0 open issues ✅ |
| S5 Tests | No | No test framework applicable for a gitignore file |
| S6 Hookshot | Yes | `.claude/doc-coverage.json` not configured ❌ |

## Grade Summary

- A: 0
- B: 0
- C: 1 (gitignore-template)
- D: 0
- F: 0

**Notes**: Single-domain community resource repo. S3 staleness is expected behaviour for a static gitignore template — no active development cycles. Primary gap is S6 hookshot not configured.

## History

| Date | Trigger | Summary |
|------|---------|---------|
| 2026-05-18 | weekly sweep | Initial scan — 1 domain, grade C (S3 ⚠️ 52d, S6 ❌) |
| 2026-05-19 | daily sweep | 1 domain, 0 regressions, 0 improvements. S3 53d (static resource). |
| 2026-05-21 | daily sweep | 1 domain, 0 regressions, 0 improvements. S3 55d (static resource, expected). |
