# Portfolio Task Tracker

Last updated: 2026-10-15  
Branch: `cursor/portfolio-foundation-0812`  
Owner: autonomous portfolio agent

## Status legend

- `[ ]` pending
- `[~]` in progress
- `[x]` done
- `[!]` blocked
- `[-]` cancelled / N/A

## Phase 0 — Foundation

| ID | Task | Status | Notes |
|----|------|--------|-------|
| P0-1 | Inspect workspace, git, tools | [x] | Repo mostly empty; tooling inventory recorded |
| P0-2 | Persistent operating instructions (`AGENTS.md`, `.cursor/rules`) | [x] | Created |
| P0-3 | Task tracker + completion checklist | [x] | This file + COMPLETION_CHECKLIST |
| P0-4 | Locate / ingest resume | [!] | **BLOCKER: resume file not in workspace** |
| P0-5 | Tooling gap remediation plan | [x] | See ASSUMPTIONS.md — docker/tf/k8s not preinstalled |
| P0-6 | Roadmap + empty traceability scaffold | [x] | Awaiting resume to populate |

## Phase 1 — Resume → project mapping

| ID | Task | Status | Notes |
|----|------|--------|-------|
| P1-1 | Extract all technical bullets | [!] | Needs resume |
| P1-2 | Map bullets → projects + evidence | [!] | Needs resume |
| P1-3 | Group into coherent project set | [!] | Needs resume |
| P1-4 | Prioritize foundation project | [!] | Needs resume |

## Phase 2 — Design (per prioritized project)

| ID | Task | Status | Notes |
|----|------|--------|-------|
| P2-1 | Architecture + tech selection | [ ] | |
| P2-2 | Implementation plan + acceptance criteria | [ ] | |
| P2-3 | Cost/security/teardown plan (if cloud) | [ ] | Approval gate before provision |

## Phase 3 — Implement & verify (iterate per project)

| ID | Task | Status | Notes |
|----|------|--------|-------|
| P3-1 | Sample app / workloads | [ ] | |
| P3-2 | IaC / config / scripts | [ ] | |
| P3-3 | CI/CD + quality gates | [ ] | |
| P3-4 | Observability + alerts (as applicable) | [ ] | |
| P3-5 | Success + failure demos | [ ] | |
| P3-6 | Diagrams (editable + rendered) | [ ] | |
| P3-7 | Tests / lint / security checks | [ ] | |
| P3-8 | Docs + runbooks + interview Q&A | [ ] | |
| P3-9 | Staff-level interview review + fixes | [ ] | |

## Phase 4 — Portfolio packaging

| ID | Task | Status | Notes |
|----|------|--------|-------|
| P4-1 | Landing page / index repo structure | [ ] | |
| P4-2 | Resume↔project link table | [ ] | |
| P4-3 | Secret/confidentiality review | [ ] | Before public |
| P4-4 | Publication approval request | [ ] | Approval gate |
| P4-5 | Verified repo URLs | [ ] | |

## Phase 5 — Cloud demos (approval-gated)

| ID | Task | Status | Notes |
|----|------|--------|-------|
| P5-1 | Deployment plan for approval | [ ] | |
| P5-2 | Provision + verify + evidence | [ ] | Only after approval |
| P5-3 | Teardown temps | [ ] | |

## Phase 6 — Final report

| ID | Task | Status | Notes |
|----|------|--------|-------|
| P6-1 | Independent final review | [ ] | |
| P6-2 | Concise report to human | [ ] | |

## Active blockers

1. **Resume missing** — No resume PDF/DOCX/MD/TXT found under `/workspace` or project store. Cannot extract bullets or design projects without inventing content (forbidden).
