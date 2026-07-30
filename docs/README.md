# OctoAcme Project Management Docs

This folder centralizes OctoAcme's project management process documents. The goal is to make processes, roles, and workflows easy to find and reference for new teammates and cross-functional partners. Each file below includes practical guidance, templates, and checklists that support initiation, planning, execution, release, and continuous improvement.

## Project management processes (brief overview)

OctoAcme runs an iterative, outcome-focused lifecycle that moves work from initiation through planning, execution, release, and retrospective. Initiation centers on a Project One-pager (problem, goal, success metrics, stakeholders) and a decision gate before planning. Planning breaks approved initiatives into a prioritized backlog with clear acceptance criteria, estimates, a Definition of Done, and a release/milestone plan. Execution uses a project board with explicit states so work is shippable in small increments.

Workflows emphasize fast feedback, quality, and risk management. Backlog items use a standard template (description, acceptance criteria, estimate, owner). Pull Request and branching conventions encourage small PRs, require CI checks (tests and linting) before review, and include acceptance criteria and an issue link. Releases follow a checklist (staging smoke tests, automated pipelines preferred, rollback plan) and include a release notes template. Incident and rollback playbooks are documented for production issues.

Roles, communication, and quality assurance are explicit. Product Managers define outcomes and success metrics; Project Managers coordinate delivery, risks, and stakeholder communication; Developers and QA own implementation and validation. The rhythm includes daily standups, weekly delivery syncs, sprint demos, PM+PdM weekly alignment, and monthly stakeholder updates. Quality practices include unit, integration, and end-to-end smoke tests, security scans in CI, manual QA as needed, and retro action items tracked in the backlog to drive continuous improvement.

## Docs in this folder

- Project overview: docs/octoacme-project-management-overview.md  
- Project initiation guide: docs/octoacme-project-initiation.md  
- Project planning: docs/octoacme-project-planning.md  
- Execution & tracking: docs/octoacme-execution-and-tracking.md  
- Risks & communication: docs/octoacme-risks-and-communication.md  
- Release & deployment guide: docs/octoacme-release-and-deployment.md  
- Retrospective & continuous improvement: docs/octoacme-retrospective-and-continuous-improvement.md  
- Roles & personas: docs/octoacme-roles-and-personas.md

## How to use this README

- Link this file from the repository root README to make processes discoverable.
- Keep summaries short and update them when the linked docs change.
- Use the included issue template (.github/ISSUE_TEMPLATE/) to request changes to any process doc.

## Acceptance criteria for this README update

- [x] Content aligns with existing process docs  
- [x] Improves clarity and centralizes navigation  
- [ ] Proposed content has been reviewed with stakeholders (if needed)
