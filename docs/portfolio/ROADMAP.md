# Portfolio Roadmap

## Principle

Highest-value foundation project first (usually: reproducible platform sample + CI quality gates + observability hooks), then deepen adjacent themes from the resume. Avoid many shallow repos.

## Tentative sequencing (refine after resume)

1. **Foundation / platform sample** — containerized service, local compose or kind, CI lint+test+image build, health/readiness, basic metrics
2. **CI/CD & progressive delivery** — gated pipeline, canary or blue/green with automated rollback demo
3. **Infrastructure as Code** — Terraform (or equivalent) modules, plan review, policy checks, safe apply story
4. **Observability & incident response** — synthetic failure → metrics/logs → alert → runbook
5. **Security / supply chain** — scanning, SBOM, least-privilege IAM patterns, secret hygiene
6. **Landing repository** — portfolio index, resume↔project map, interview prep hub

Exact project titles, tech choices, and ordering will be rewritten from the resume mapping (Phase 1). No cloud provision until an approved deployment plan exists.

## Near-term (unblocked now)

- [x] Operating instructions
- [x] Trackers / checklist / matrix scaffold
- [ ] Ingest resume (human action required)
- [ ] Produce project set + prioritize P0 implementation
