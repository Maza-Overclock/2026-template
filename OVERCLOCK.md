# MAZA Overclock — Repository Standards

This document defines the submission requirements and repository standards for the MAZA Overclock engineering competition.

---

## Repository Organization

Teams may organize the repository however they wish. There is no mandated directory structure beyond the required documentation files.

- **Monorepos are encouraged** for teams building multiple related services or applications.
- **Multiple applications are allowed** — web, mobile, desktop, TUI, API, workers, agents, and any combination thereof.
- Teams are free to add, remove, or restructure directories to match their stack and workflow.

---

## Required Files

Every submission must include the following documents at the repository root:

| File | Purpose |
| ---- | ------- |
| `README.md` | Project overview, setup instructions, and demo guide |
| `ARCHITECTURE.md` | System design, technical decisions, and tradeoffs |
| `TEAM.md` | Team members, roles, and collaboration model |

These files are the primary artifacts judges use for evaluation. Invest time in making them clear, accurate, and complete.

---

## Submission Process

### Code Freeze

At code freeze, teams must create a **GitHub Release** with the following exact name:

```
overclock-2026-final
```

### Official Submission

- The tagged release becomes the **official submission** for judging.
- Commits made after the tagged release are **ignored for judging**.
- Ensure the release tag points to the commit you intend to submit.

### Release Checklist

- [ ] All required documentation is complete and accurate
- [ ] Demo URL is accessible and credentials are documented
- [ ] Application builds and runs from the tagged commit
- [ ] Screenshots are included in `docs/screenshots/`
- [ ] GitHub Release `overclock-2026-final` is created from the final commit

---

## Judging Criteria

Judges evaluate submissions across multiple dimensions. Strong documentation directly supports scoring in several areas:

- **Problem understanding** — clarity of problem statement and target user
- **Technical execution** — architecture quality, code organization, and engineering decisions
- **Completeness** — working demo, feature coverage, and honest assessment of limitations
- **Craftsmanship** — attention to detail in code, documentation, and user experience
- **Team collaboration** — evidence of effective coordination under time pressure

---

## Questions

Contact the competition organizers if you have questions about submission requirements or the judging process.
